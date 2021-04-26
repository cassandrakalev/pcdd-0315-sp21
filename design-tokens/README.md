0.0.1 (04-19-2021)
Added initial design tokens for New Museum design system
 11  design-tokens/README.md 
@@ -0,0 +1,11 @@
New Museum Design Tokens

This repository contains design tokens for building newmuseum.org.

|-- css
|    |-- design-tokens.css (A CSS file containing the design tokens)
|-- json
|    |-- design-tokens.json (A JSON representation of the design tokens)

To create these result files locally, clone this repository, run npm install and then npm run build.

 87  design-tokens/design-tokens.css 
@@ -0,0 +1,87 @@
/* colors */
:root {
  --brand-nmds-brand-pink: #e62f88;
  --brand-nmds-brand-scarlet: #ec473e;
  --brand-nmds-brand-blue: #00b6e0;
  --brand-nmds-brand-emerald: #00b09b;
  --brand-nmds-brand-lime: #c7d545;
  --brand-nmds-brand-yellow: #feb33f;
  --backgrounds-nmds-background-white: #ffffff;
  --backgrounds-nmds-background-light: #f1f3f4;
  --neutrals-nmds-gray-100: #f1f3f4;
  --neutrals-nmds-gray-200: #e4e7e9;
  --neutrals-nmds-gray-300: #b8bbbe;
  --neutrals-nmds-gray-800: #636669;
  --neutrals-nmds-gray-900: #212429;
}
/* fonts */
:root {        
--primary-font: Neographik MT Std;
--secondary-font: DIN Next LT Pro;
}
/* text styles*/
.heading-1 {
  font-family : var(--primary-font);
  font-size : 91px;
  line-height: 104px;
  letter-spacing : 0em;
}
.heading-2 {
  font-family : var(--primary-font);
  font-size : 60px;
  line-height: 70px;
  letter-spacing : 0em;
}
.heading-3 {
  font-family : var(--primary-font);
  font-size : 40px;
  line-height: 40px;
  letter-spacing : 0em;
}
.heading-4 {
  font-family : var(--primary-font);
  font-size : 27px;
  line-height: 34px;
  letter-spacing : 0em;
}
.heading-5 {
  font-family : var(--primary-font);
  font-size : 18px;
  line-height: 24px;
  letter-spacing : 0em;
}
.heading-6 {
  font-family : var(--primary-font);
  font-size : 12px;
  line-height: 17px;
  letter-spacing : 0em;
}
.body-text {
  font-family : var(--secondary-font);
  font-size : 18px;
  line-height: 27px;
  letter-spacing : 0em;
}
.image-caption {
  font-family : var(--secondary-font);
  font-size : 18px;
  line-height: 27px;
  letter-spacing : 0em;
}
.pull-quote {
  font-family : var(--primary-font);
  font-size : 27px;
  line-height: 40px;
  letter-spacing : 0em;
}
/* SpacePatterns */
:root {
  --none: 0px;
  --xx-small: 2px;
  --x-small: 4px;
  --small: 8px;
  --regular: 16px;
  --large: 32px;
  --x-large: 64px;
  --xx-large: 128px;
}
 167  design-tokens/design-tokens.json 
@@ -0,0 +1,167 @@
{
  "colors" : [
    {
      "name" : "Brand/NMDS brand pink",
      "value" : "#e62f88"
    },
    {
      "name" : "Brand/NMDS brand scarlet",
      "value" : "#ec473e"
    },
    {
      "name" : "Brand/NMDS brand blue",
      "value" : "#00b6e0"
    },
    {
      "name" : "Brand/NMDS brand emerald",
      "value" : "#00b09b"
    },
    {
      "name" : "Brand/NMDS brand lime",
      "value" : "#c7d545"
    },
    {
      "name" : "Brand/NMDS brand yellow",
      "value" : "#feb33f"
    },
    {
      "name" : "Backgrounds/NMDS background white",
      "value" : "#ffffff"
    },
    {
      "name" : "Backgrounds/NMDS background light",
      "value" : "#f1f3f4"
    },
    {
      "name" : "Neutrals/NMDS gray 100",
      "value" : "#f1f3f4"
    },
    {
      "name" : "Neutrals/NMDS gray 200",
      "value" : "#e4e7e9"
    },
    {
      "name" : "Neutrals/NMDS gray 300",
      "value" : "#b8bbbe"
    },
    {
      "name" : "Neutrals/NMDS gray 800",
      "value" : "#636669"
    },
    {
      "name" : "Neutrals/NMDS gray 900",
      "value" : "#212429"
    },
  ]
}{
  "fonts" : [
    "primary-font" : {
      "name" : "Primary Font",
      "fontFamily" : "Neographik MT Std"
    },
    "secondary-font" : {
      "name" : "Secondary Font",
      "fontFamily" : "DIN Next LT Pro"
    },
  ],
  "typeStyles" : [
    "heading-1" : {
      "name" : "Heading 1",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "91px",
      "lineHeight" : "104px",
      "letterSpacing" : "0em",
    },
    "heading-2" : {
      "name" : "Heading 2",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "60px",
      "lineHeight" : "70px",
      "letterSpacing" : "0em",
    },
    "heading-3" : {
      "name" : "Heading 3",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "40px",
      "lineHeight" : "40px",
      "letterSpacing" : "0em",
    },
    "heading-4" : {
      "name" : "Heading 4",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "27px",
      "lineHeight" : "34px",
      "letterSpacing" : "0em",
    },
    "heading-5" : {
      "name" : "Heading 5",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "18px",
      "lineHeight" : "24px",
      "letterSpacing" : "0em",
    },
    "heading-6" : {
      "name" : "Heading 6",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "12px",
      "lineHeight" : "17px",
      "letterSpacing" : "0em",
    },
    "body-text" : {
      "name" : "Body text",
      "fontFamily" : "DIN Next LT Pro",
      "fontSize" : "18px",
      "lineHeight" : "27px",
      "letterSpacing" : "0em",
    },
    "image-caption" : {
      "name" : "Image caption",
      "fontFamily" : "DIN Next LT Pro",
      "fontSize" : "18px",
      "lineHeight" : "27px",
      "letterSpacing" : "0em",
    },
    "pull-quote" : {
      "name" : "Pull quote ",
      "fontFamily" : "Neographik MT Std",
      "fontSize" : "27px",
      "lineHeight" : "40px",
      "letterSpacing" : "0em",
    },
  ]
}{
  "SpacePatterns" : [
    {
      "name" : "none",
      "value" : "0px"
    },
    {
      "name" : "xx-small",
      "value" : "2px"
    },
    {
      "name" : "x-small",
      "value" : "4px"
    },
    {
      "name" : "small",
      "value" : "8px"
    },
    {
      "name" : "regular",
      "value" : "16px"
    },
    {
      "name" : "large",
      "value" : "32px"
    },
    {
      "name" : "x-large",
      "value" : "64px"
    },
    {
      "name" : "xx-large",
      "value" : "128px"
    },
  ]
} 