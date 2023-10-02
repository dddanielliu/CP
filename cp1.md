# 1121 CP1

[TOC]

<style>.ͼ1.cm-focused {outline: 1px dotted #212121;}
.ͼ1 {position: relative !important; box-sizing: border-box; display: flex !important; flex-direction: column;}
.ͼ1 .cm-scroller {display: flex !important; align-items: flex-start !important; font-family: monospace; line-height: 1.4; height: 100%; overflow-x: auto; position: relative; z-index: 0;}
.ͼ1 .cm-content[contenteditable=true] {-webkit-user-modify: read-write-plaintext-only;}
.ͼ1 .cm-content {margin: 0; flex-grow: 2; flex-shrink: 0; display: block; white-space: pre; word-wrap: normal; box-sizing: border-box; padding: 4px 0; outline: none;}
.ͼ1 .cm-lineWrapping {white-space: pre-wrap; white-space: break-spaces; word-break: break-word; overflow-wrap: anywhere; flex-shrink: 1;}
.ͼ2 .cm-content {caret-color: black;}
.ͼ3 .cm-content {caret-color: white;}
.ͼ1 .cm-line {display: block; padding: 0 2px 0 6px;}
.ͼ1 .cm-layer > * {position: absolute;}
.ͼ1 .cm-layer {position: absolute; left: 0; top: 0; contain: size style;}
.ͼ2 .cm-selectionBackground {background: #d9d9d9;}
.ͼ3 .cm-selectionBackground {background: #222;}
.ͼ2.cm-focused > .cm-scroller > .cm-selectionLayer .cm-selectionBackground {background: #d7d4f0;}
.ͼ3.cm-focused > .cm-scroller > .cm-selectionLayer .cm-selectionBackground {background: #233;}
.ͼ1 .cm-cursorLayer {pointer-events: none;}
.ͼ1.cm-focused > .cm-scroller > .cm-cursorLayer {animation: steps(1) cm-blink 1.2s infinite;}
@keyframes cm-blink {50% {opacity: 0;}}
@keyframes cm-blink2 {50% {opacity: 0;}}
.ͼ1 .cm-cursor, .ͼ1 .cm-dropCursor {border-left: 1.2px solid black; margin-left: -0.6px; pointer-events: none;}
.ͼ1 .cm-cursor {display: none;}
.ͼ3 .cm-cursor {border-left-color: #444;}
.ͼ1 .cm-dropCursor {position: absolute;}
.ͼ1.cm-focused > .cm-scroller > .cm-cursorLayer .cm-cursor {display: block;}
.ͼ2 .cm-activeLine {background-color: #cceeff44;}
.ͼ3 .cm-activeLine {background-color: #99eeff33;}
.ͼ2 .cm-specialChar {color: red;}
.ͼ3 .cm-specialChar {color: #f78;}
.ͼ1 .cm-gutters {flex-shrink: 0; display: flex; height: 100%; box-sizing: border-box; left: 0; z-index: 200;}
.ͼ2 .cm-gutters {background-color: #f5f5f5; color: #6c6c6c; border-right: 1px solid #ddd;}
.ͼ3 .cm-gutters {background-color: #333338; color: #ccc;}
.ͼ1 .cm-gutter {display: flex !important; flex-direction: column; flex-shrink: 0; box-sizing: border-box; min-height: 100%; overflow: hidden;}
.ͼ1 .cm-gutterElement {box-sizing: border-box;}
.ͼ1 .cm-lineNumbers .cm-gutterElement {padding: 0 3px 0 5px; min-width: 20px; text-align: right; white-space: nowrap;}
.ͼ2 .cm-activeLineGutter {background-color: #e2f2ff;}
.ͼ3 .cm-activeLineGutter {background-color: #222227;}
.ͼ1 .cm-panels {box-sizing: border-box; position: sticky; left: 0; right: 0;}
.ͼ2 .cm-panels {background-color: #f5f5f5; color: black;}
.ͼ2 .cm-panels-top {border-bottom: 1px solid #ddd;}
.ͼ2 .cm-panels-bottom {border-top: 1px solid #ddd;}
.ͼ3 .cm-panels {background-color: #333338; color: white;}
.ͼ1 .cm-tab {display: inline-block; overflow: hidden; vertical-align: bottom;}
.ͼ1 .cm-widgetBuffer {vertical-align: text-top; height: 1em; width: 0; display: inline;}
.ͼ1 .cm-placeholder {color: #888; display: inline-block; vertical-align: top;}
.ͼ1 .cm-highlightSpace:before {content: attr(data-display); position: absolute; pointer-events: none; color: #888;}
.ͼ1 .cm-highlightTab {background-image: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="200" height="20"><path stroke="%23888" stroke-width="1" fill="none" d="M1 10H196L190 5M190 15L196 10M197 4L197 16"/></svg>'); background-size: auto 100%; background-position: right 90%; background-repeat: no-repeat;}
.ͼ1 .cm-trailingSpace {background-color: #ff332255;}
.ͼ1 .cm-button {vertical-align: middle; color: inherit; font-size: 70%; padding: .2em 1em; border-radius: 1px;}
.ͼ2 .cm-button:active {background-image: linear-gradient(#b4b4b4, #d0d3d6);}
.ͼ2 .cm-button {background-image: linear-gradient(#eff1f5, #d9d9df); border: 1px solid #888;}
.ͼ3 .cm-button:active {background-image: linear-gradient(#111, #333);}
.ͼ3 .cm-button {background-image: linear-gradient(#393939, #111); border: 1px solid #888;}
.ͼ1 .cm-textfield {vertical-align: middle; color: inherit; font-size: 70%; border: 1px solid silver; padding: .2em .5em;}
.ͼ2 .cm-textfield {background-color: white;}
.ͼ3 .cm-textfield {border: 1px solid #555; background-color: inherit;}
.ͼ1 .cm-selectionMatch {background-color: #99ff7780;}
.ͼ1 .cm-searchMatch .cm-selectionMatch {background-color: transparent;}
.ͼ1 .cm-tooltip.cm-tooltip-autocomplete > ul > li, .ͼ1 .cm-tooltip.cm-tooltip-autocomplete > ul > completion-section {padding: 1px 3px; line-height: 1.2;}
.ͼ1 .cm-tooltip.cm-tooltip-autocomplete > ul > li {overflow-x: hidden; text-overflow: ellipsis; cursor: pointer;}
.ͼ1 .cm-tooltip.cm-tooltip-autocomplete > ul > completion-section {display: list-item; border-bottom: 1px solid silver; padding-left: 0.5em; opacity: 0.7;}
.ͼ1 .cm-tooltip.cm-tooltip-autocomplete > ul {font-family: monospace; white-space: nowrap; overflow: hidden auto; max-width: 700px; max-width: min(700px, 95vw); min-width: 250px; max-height: 10em; height: 100%; list-style: none; margin: 0; padding: 0;}
.ͼ2 .cm-tooltip-autocomplete ul li[aria-selected] {background: #17c; color: white;}
.ͼ2 .cm-tooltip-autocomplete-disabled ul li[aria-selected] {background: #777;}
.ͼ3 .cm-tooltip-autocomplete ul li[aria-selected] {background: #347; color: white;}
.ͼ3 .cm-tooltip-autocomplete-disabled ul li[aria-selected] {background: #444;}
.ͼ1 .cm-completionListIncompleteTop:before, .ͼ1 .cm-completionListIncompleteBottom:after {content: "···"; opacity: 0.5; display: block; text-align: center;}
.ͼ1 .cm-tooltip.cm-completionInfo {position: absolute; padding: 3px 9px; width: max-content; max-width: 400px; box-sizing: border-box;}
.ͼ1 .cm-completionInfo.cm-completionInfo-left {right: 100%;}
.ͼ1 .cm-completionInfo.cm-completionInfo-right {left: 100%;}
.ͼ1 .cm-completionInfo.cm-completionInfo-left-narrow {right: 30px;}
.ͼ1 .cm-completionInfo.cm-completionInfo-right-narrow {left: 30px;}
.ͼ2 .cm-snippetField {background-color: #00000022;}
.ͼ3 .cm-snippetField {background-color: #ffffff22;}
.ͼ1 .cm-snippetFieldPosition {vertical-align: text-top; width: 0; height: 1.15em; display: inline-block; margin: 0 -0.7px -.7em; border-left: 1.4px dotted #888;}
.ͼ1 .cm-completionMatchedText {text-decoration: underline;}
.ͼ1 .cm-completionDetail {margin-left: 0.5em; font-style: italic;}
.ͼ1 .cm-completionIcon {font-size: 90%; width: .8em; display: inline-block; text-align: center; padding-right: .6em; opacity: 0.6; box-sizing: content-box;}
.ͼ1 .cm-completionIcon-function:after, .ͼ1 .cm-completionIcon-method:after {content: 'ƒ';}
.ͼ1 .cm-completionIcon-class:after {content: '○';}
.ͼ1 .cm-completionIcon-interface:after {content: '◌';}
.ͼ1 .cm-completionIcon-variable:after {content: '𝑥';}
.ͼ1 .cm-completionIcon-constant:after {content: '𝐶';}
.ͼ1 .cm-completionIcon-type:after {content: '𝑡';}
.ͼ1 .cm-completionIcon-enum:after {content: '∪';}
.ͼ1 .cm-completionIcon-property:after {content: '□';}
.ͼ1 .cm-completionIcon-keyword:after {content: '🔑︎';}
.ͼ1 .cm-completionIcon-namespace:after {content: '▢';}
.ͼ1 .cm-completionIcon-text:after {content: 'abc'; font-size: 50%; vertical-align: middle;}
.ͼ1 .cm-tooltip {z-index: 100; box-sizing: border-box;}
.ͼ2 .cm-tooltip {border: 1px solid #bbb; background-color: #f5f5f5;}
.ͼ2 .cm-tooltip-section:not(:first-child) {border-top: 1px solid #bbb;}
.ͼ3 .cm-tooltip {background-color: #333338; color: white;}
.ͼ1 .cm-tooltip-arrow:before, .ͼ1 .cm-tooltip-arrow:after {content: ''; position: absolute; width: 0; height: 0; border-left: 7px solid transparent; border-right: 7px solid transparent;}
.ͼ1 .cm-tooltip-above .cm-tooltip-arrow:before {border-top: 7px solid #bbb;}
.ͼ1 .cm-tooltip-above .cm-tooltip-arrow:after {border-top: 7px solid #f5f5f5; bottom: 1px;}
.ͼ1 .cm-tooltip-above .cm-tooltip-arrow {bottom: -7px;}
.ͼ1 .cm-tooltip-below .cm-tooltip-arrow:before {border-bottom: 7px solid #bbb;}
.ͼ1 .cm-tooltip-below .cm-tooltip-arrow:after {border-bottom: 7px solid #f5f5f5; top: 1px;}
.ͼ1 .cm-tooltip-below .cm-tooltip-arrow {top: -7px;}
.ͼ1 .cm-tooltip-arrow {height: 7px; width: 14px; position: absolute; z-index: -1; overflow: hidden;}
.ͼ3 .cm-tooltip .cm-tooltip-arrow:before {border-top-color: #333338; border-bottom-color: #333338;}
.ͼ3 .cm-tooltip .cm-tooltip-arrow:after {border-top-color: transparent; border-bottom-color: transparent;}
.ͼ1.cm-focused .cm-matchingBracket {background-color: #328c8252;}
.ͼ1.cm-focused .cm-nonmatchingBracket {background-color: #bb555544;}
.ͼ1 .cm-foldPlaceholder {background-color: #eee; border: 1px solid #ddd; color: #888; border-radius: .2em; margin: 0 1px; padding: 0 1px; cursor: pointer;}
.ͼ1 .cm-foldGutter span {padding: 0 1px; cursor: pointer;}
.ͼp {color: #c678dd;}
.ͼq {color: #e06c75;}
.ͼr {color: #61afef;}
.ͼs {color: #d19a66;}
.ͼt {color: #abb2bf;}
.ͼu {color: #e5c07b;}
.ͼv {color: #56b6c2;}
.ͼw {color: #7d8799;}
.ͼx {font-weight: bold;}
.ͼy {font-style: italic;}
.ͼz {text-decoration: line-through;}
.ͼ10 {color: #7d8799; text-decoration: underline;}
.ͼ11 {font-weight: bold; color: #e06c75;}
.ͼ12 {color: #d19a66;}
.ͼ13 {color: #98c379;}
.ͼ14 {color: #ffffff;}
.ͼo {color: #abb2bf; background-color: #282c34;}
.ͼo .cm-content {caret-color: #528bff;}
.ͼo .cm-cursor, .ͼo .cm-dropCursor {border-left-color: #528bff;}
.ͼo.cm-focused > .cm-scroller > .cm-selectionLayer .cm-selectionBackground, .ͼo .cm-selectionBackground, .ͼo .cm-content ::selection {background-color: #3E4451;}
.ͼo .cm-panels {background-color: #21252b; color: #abb2bf;}
.ͼo .cm-panels.cm-panels-top {border-bottom: 2px solid black;}
.ͼo .cm-panels.cm-panels-bottom {border-top: 2px solid black;}
.ͼo .cm-searchMatch {background-color: #72a1ff59; outline: 1px solid #457dff;}
.ͼo .cm-searchMatch.cm-searchMatch-selected {background-color: #6199ff2f;}
.ͼo .cm-activeLine {background-color: #6699ff0b;}
.ͼo .cm-selectionMatch {background-color: #aafe661a;}
.ͼo.cm-focused .cm-matchingBracket, .ͼo.cm-focused .cm-nonmatchingBracket {background-color: #bad0f847;}
.ͼo .cm-gutters {background-color: #282c34; color: #7d8799; border: none;}
.ͼo .cm-activeLineGutter {background-color: #2c313a;}
.ͼo .cm-foldPlaceholder {background-color: transparent; border: none; color: #ddd;}
.ͼo .cm-tooltip {border: none; background-color: #353a42;}
.ͼo .cm-tooltip .cm-tooltip-arrow:before {border-top-color: transparent; border-bottom-color: transparent;}
.ͼo .cm-tooltip .cm-tooltip-arrow:after {border-top-color: #353a42; border-bottom-color: #353a42;}
.ͼo .cm-tooltip-autocomplete > ul > li[aria-selected] {background-color: #2c313a; color: #abb2bf;}
.ͼ1b {height: 300px;}
.ͼ1b.cm-editor.cm-focused {outline: 0px;}
.ͼ1b .cm-scroller {overflow: auto;}

.ͼ19 {height: 300px;}
.ͼ19.cm-editor.cm-focused {outline: 0px;}
.ͼ19 .cm-scroller {overflow: auto;}

.ͼ17 {height: 300px;}
.ͼ17.cm-editor.cm-focused {outline: 0px;}
.ͼ17 .cm-scroller {overflow: auto;}

.ͼ15 {height: 300px;}
.ͼ15.cm-editor.cm-focused {outline: 0px;}
.ͼ15 .cm-scroller {overflow: auto;}

.ͼ5 {color: #404740;}
.ͼ6 {text-decoration: underline;}
.ͼ7 {text-decoration: underline; font-weight: bold;}
.ͼ8 {font-style: italic;}
.ͼ9 {font-weight: bold;}
.ͼa {text-decoration: line-through;}
.ͼb {color: #708;}
.ͼc {color: #219;}
.ͼd {color: #164;}
.ͼe {color: #a11;}
.ͼf {color: #e40;}
.ͼg {color: #00f;}
.ͼh {color: #30a;}
.ͼi {color: #085;}
.ͼj {color: #167;}
.ͼk {color: #256;}
.ͼl {color: #00c;}
.ͼm {color: #940;}
.ͼn {color: #f00;}
.ͼ4 .cm-line ::selection {background-color: transparent !important;}
.ͼ4 .cm-line::selection {background-color: transparent !important;}
.ͼ4 .cm-line {caret-color: transparent !important;}
</style>
<meta charset="UTF-8">
<link rel="icon" type="image/svg+xml" href="https://oj.ebg.tw/vite.svg">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC&amp;display=swap" rel="stylesheet">
<title>NCCU OJ | Rectangle Area</title>
<script type="module" crossorigin="" src="https://oj.ebg.tw/assets/index-f88b100c.js"></script>
<link rel="modulepreload" crossorigin="" href="https://oj.ebg.tw/assets/codemirror-f2bda4e9.js">
<link rel="modulepreload" crossorigin="" href="https://oj.ebg.tw/assets/md-editor-b32411e7.js">
<link rel="modulepreload" crossorigin="" href="https://oj.ebg.tw/assets/utils-21e62eac.js">
<link rel="modulepreload" crossorigin="" href="https://oj.ebg.tw/assets/codemirror-lang-6451e576.js">
<link rel="stylesheet" href="https://oj.ebg.tw/assets/index-53b8fb40.css">
<link rel="manifest" href="https://oj.ebg.tw/manifest.webmanifest"><script id="vite-plugin-pwa:register-sw" src="https://oj.ebg.tw/registerSW.js"></script><style type="text/css" id="vuetify-theme-stylesheet">:root {
      color-scheme: dark;
    }
    :root {
      --v-theme-background: 18,18,18;
      --v-theme-background-overlay-multiplier: 1;
      --v-theme-surface: 33,33,33;
      --v-theme-surface-overlay-multiplier: 1;
      --v-theme-surface-variant: 189,189,189;
      --v-theme-surface-variant-overlay-multiplier: 2;
      --v-theme-on-surface-variant: 66,66,66;
      --v-theme-primary: 92,107,192;
      --v-theme-primary-overlay-multiplier: 1;
      --v-theme-primary-darken-1: 57,73,171;
      --v-theme-primary-darken-1-overlay-multiplier: 1;
      --v-theme-secondary: 0,121,107;
      --v-theme-secondary-overlay-multiplier: 1;
      --v-theme-secondary-darken-1: 0,105,92;
      --v-theme-secondary-darken-1-overlay-multiplier: 1;
      --v-theme-error: 207,102,121;
      --v-theme-error-overlay-multiplier: 2;
      --v-theme-info: 33,150,243;
      --v-theme-info-overlay-multiplier: 2;
      --v-theme-success: 76,175,80;
      --v-theme-success-overlay-multiplier: 2;
      --v-theme-warning: 251,140,0;
      --v-theme-warning-overlay-multiplier: 2;
      --v-theme-on-background: 255,255,255;
      --v-theme-on-surface: 255,255,255;
      --v-theme-on-primary: 255,255,255;
      --v-theme-on-primary-darken-1: 255,255,255;
      --v-theme-on-secondary: 255,255,255;
      --v-theme-on-secondary-darken-1: 255,255,255;
      --v-theme-on-error: 255,255,255;
      --v-theme-on-info: 255,255,255;
      --v-theme-on-success: 255,255,255;
      --v-theme-on-warning: 255,255,255;
      --v-border-color: 255, 255, 255;
      --v-border-opacity: 0.12;
      --v-high-emphasis-opacity: 1;
      --v-medium-emphasis-opacity: 0.7;
      --v-disabled-opacity: 0.5;
      --v-idle-opacity: 0.1;
      --v-hover-opacity: 0.04;
      --v-focus-opacity: 0.12;
      --v-selected-opacity: 0.08;
      --v-activated-opacity: 0.12;
      --v-pressed-opacity: 0.16;
      --v-dragged-opacity: 0.08;
      --v-theme-kbd: 33, 37, 41;
      --v-theme-on-kbd: 255, 255, 255;
      --v-theme-code: 52, 52, 52;
      --v-theme-on-code: 204, 204, 204;
    }
    .v-theme--light {
      color-scheme: normal;
      --v-theme-background: 255,255,255;
      --v-theme-background-overlay-multiplier: 1;
      --v-theme-surface: 255,255,255;
      --v-theme-surface-overlay-multiplier: 1;
      --v-theme-surface-variant: 66,66,66;
      --v-theme-surface-variant-overlay-multiplier: 2;
      --v-theme-on-surface-variant: 238,238,238;
      --v-theme-primary: 121,134,203;
      --v-theme-primary-overlay-multiplier: 1;
      --v-theme-primary-darken-1: 92,107,192;
      --v-theme-primary-darken-1-overlay-multiplier: 2;
      --v-theme-secondary: 0,137,123;
      --v-theme-secondary-overlay-multiplier: 1;
      --v-theme-secondary-darken-1: 0,121,107;
      --v-theme-secondary-darken-1-overlay-multiplier: 2;
      --v-theme-error: 176,0,32;
      --v-theme-error-overlay-multiplier: 2;
      --v-theme-info: 33,150,243;
      --v-theme-info-overlay-multiplier: 1;
      --v-theme-success: 76,175,80;
      --v-theme-success-overlay-multiplier: 1;
      --v-theme-warning: 251,140,0;
      --v-theme-warning-overlay-multiplier: 1;
      --v-theme-on-background: 0,0,0;
      --v-theme-on-surface: 0,0,0;
      --v-theme-on-primary: 255,255,255;
      --v-theme-on-primary-darken-1: 255,255,255;
      --v-theme-on-secondary: 255,255,255;
      --v-theme-on-secondary-darken-1: 255,255,255;
      --v-theme-on-error: 255,255,255;
      --v-theme-on-info: 255,255,255;
      --v-theme-on-success: 255,255,255;
      --v-theme-on-warning: 255,255,255;
      --v-border-color: 0, 0, 0;
      --v-border-opacity: 0.12;
      --v-high-emphasis-opacity: 0.87;
      --v-medium-emphasis-opacity: 0.6;
      --v-disabled-opacity: 0.38;
      --v-idle-opacity: 0.04;
      --v-hover-opacity: 0.04;
      --v-focus-opacity: 0.12;
      --v-selected-opacity: 0.08;
      --v-activated-opacity: 0.12;
      --v-pressed-opacity: 0.12;
      --v-dragged-opacity: 0.08;
      --v-theme-kbd: 33, 37, 41;
      --v-theme-on-kbd: 255, 255, 255;
      --v-theme-code: 245, 245, 245;
      --v-theme-on-code: 0, 0, 0;
    }
    .v-theme--dark {
      color-scheme: dark;
      --v-theme-background: 18,18,18;
      --v-theme-background-overlay-multiplier: 1;
      --v-theme-surface: 33,33,33;
      --v-theme-surface-overlay-multiplier: 1;
      --v-theme-surface-variant: 189,189,189;
      --v-theme-surface-variant-overlay-multiplier: 2;
      --v-theme-on-surface-variant: 66,66,66;
      --v-theme-primary: 92,107,192;
      --v-theme-primary-overlay-multiplier: 1;
      --v-theme-primary-darken-1: 57,73,171;
      --v-theme-primary-darken-1-overlay-multiplier: 1;
      --v-theme-secondary: 0,121,107;
      --v-theme-secondary-overlay-multiplier: 1;
      --v-theme-secondary-darken-1: 0,105,92;
      --v-theme-secondary-darken-1-overlay-multiplier: 1;
      --v-theme-error: 207,102,121;
      --v-theme-error-overlay-multiplier: 2;
      --v-theme-info: 33,150,243;
      --v-theme-info-overlay-multiplier: 2;
      --v-theme-success: 76,175,80;
      --v-theme-success-overlay-multiplier: 2;
      --v-theme-warning: 251,140,0;
      --v-theme-warning-overlay-multiplier: 2;
      --v-theme-on-background: 255,255,255;
      --v-theme-on-surface: 255,255,255;
      --v-theme-on-primary: 255,255,255;
      --v-theme-on-primary-darken-1: 255,255,255;
      --v-theme-on-secondary: 255,255,255;
      --v-theme-on-secondary-darken-1: 255,255,255;
      --v-theme-on-error: 255,255,255;
      --v-theme-on-info: 255,255,255;
      --v-theme-on-success: 255,255,255;
      --v-theme-on-warning: 255,255,255;
      --v-border-color: 255, 255, 255;
      --v-border-opacity: 0.12;
      --v-high-emphasis-opacity: 1;
      --v-medium-emphasis-opacity: 0.7;
      --v-disabled-opacity: 0.5;
      --v-idle-opacity: 0.1;
      --v-hover-opacity: 0.04;
      --v-focus-opacity: 0.12;
      --v-selected-opacity: 0.08;
      --v-activated-opacity: 0.12;
      --v-pressed-opacity: 0.16;
      --v-dragged-opacity: 0.08;
      --v-theme-kbd: 33, 37, 41;
      --v-theme-on-kbd: 255, 255, 255;
      --v-theme-code: 52, 52, 52;
      --v-theme-on-code: 204, 204, 204;
    }
    .bg-background {
      --v-theme-overlay-multiplier: var(--v-theme-background-overlay-multiplier);
      background-color: rgb(var(--v-theme-background)) !important;
      color: rgb(var(--v-theme-on-background)) !important;
    }
    .bg-surface {
      --v-theme-overlay-multiplier: var(--v-theme-surface-overlay-multiplier);
      background-color: rgb(var(--v-theme-surface)) !important;
      color: rgb(var(--v-theme-on-surface)) !important;
    }
    .bg-surface-variant {
      --v-theme-overlay-multiplier: var(--v-theme-surface-variant-overlay-multiplier);
      background-color: rgb(var(--v-theme-surface-variant)) !important;
      color: rgb(var(--v-theme-on-surface-variant)) !important;
    }
    .bg-primary {
      --v-theme-overlay-multiplier: var(--v-theme-primary-overlay-multiplier);
      background-color: rgb(var(--v-theme-primary)) !important;
      color: rgb(var(--v-theme-on-primary)) !important;
    }
    .bg-primary-darken-1 {
      --v-theme-overlay-multiplier: var(--v-theme-primary-darken-1-overlay-multiplier);
      background-color: rgb(var(--v-theme-primary-darken-1)) !important;
      color: rgb(var(--v-theme-on-primary-darken-1)) !important;
    }
    .bg-secondary {
      --v-theme-overlay-multiplier: var(--v-theme-secondary-overlay-multiplier);
      background-color: rgb(var(--v-theme-secondary)) !important;
      color: rgb(var(--v-theme-on-secondary)) !important;
    }
    .bg-secondary-darken-1 {
      --v-theme-overlay-multiplier: var(--v-theme-secondary-darken-1-overlay-multiplier);
      background-color: rgb(var(--v-theme-secondary-darken-1)) !important;
      color: rgb(var(--v-theme-on-secondary-darken-1)) !important;
    }
    .bg-error {
      --v-theme-overlay-multiplier: var(--v-theme-error-overlay-multiplier);
      background-color: rgb(var(--v-theme-error)) !important;
      color: rgb(var(--v-theme-on-error)) !important;
    }
    .bg-info {
      --v-theme-overlay-multiplier: var(--v-theme-info-overlay-multiplier);
      background-color: rgb(var(--v-theme-info)) !important;
      color: rgb(var(--v-theme-on-info)) !important;
    }
    .bg-success {
      --v-theme-overlay-multiplier: var(--v-theme-success-overlay-multiplier);
      background-color: rgb(var(--v-theme-success)) !important;
      color: rgb(var(--v-theme-on-success)) !important;
    }
    .bg-warning {
      --v-theme-overlay-multiplier: var(--v-theme-warning-overlay-multiplier);
      background-color: rgb(var(--v-theme-warning)) !important;
      color: rgb(var(--v-theme-on-warning)) !important;
    }
    .text-background {
      color: rgb(var(--v-theme-background)) !important;
    }
    .border-background {
      --v-border-color: var(--v-theme-background);
    }
    .text-surface {
      color: rgb(var(--v-theme-surface)) !important;
    }
    .border-surface {
      --v-border-color: var(--v-theme-surface);
    }
    .text-surface-variant {
      color: rgb(var(--v-theme-surface-variant)) !important;
    }
    .border-surface-variant {
      --v-border-color: var(--v-theme-surface-variant);
    }
    .on-surface-variant {
      color: rgb(var(--v-theme-on-surface-variant)) !important;
    }
    .text-primary {
      color: rgb(var(--v-theme-primary)) !important;
    }
    .border-primary {
      --v-border-color: var(--v-theme-primary);
    }
    .text-primary-darken-1 {
      color: rgb(var(--v-theme-primary-darken-1)) !important;
    }
    .border-primary-darken-1 {
      --v-border-color: var(--v-theme-primary-darken-1);
    }
    .text-secondary {
      color: rgb(var(--v-theme-secondary)) !important;
    }
    .border-secondary {
      --v-border-color: var(--v-theme-secondary);
    }
    .text-secondary-darken-1 {
      color: rgb(var(--v-theme-secondary-darken-1)) !important;
    }
    .border-secondary-darken-1 {
      --v-border-color: var(--v-theme-secondary-darken-1);
    }
    .text-error {
      color: rgb(var(--v-theme-error)) !important;
    }
    .border-error {
      --v-border-color: var(--v-theme-error);
    }
    .text-info {
      color: rgb(var(--v-theme-info)) !important;
    }
    .border-info {
      --v-border-color: var(--v-theme-info);
    }
    .text-success {
      color: rgb(var(--v-theme-success)) !important;
    }
    .border-success {
      --v-border-color: var(--v-theme-success);
    }
    .text-warning {
      color: rgb(var(--v-theme-warning)) !important;
    }
    .border-warning {
      --v-border-color: var(--v-theme-warning);
    }
    .on-background {
      color: rgb(var(--v-theme-on-background)) !important;
    }
    .on-surface {
      color: rgb(var(--v-theme-on-surface)) !important;
    }
    .on-primary {
      color: rgb(var(--v-theme-on-primary)) !important;
    }
    .on-primary-darken-1 {
      color: rgb(var(--v-theme-on-primary-darken-1)) !important;
    }
    .on-secondary {
      color: rgb(var(--v-theme-on-secondary)) !important;
    }
    .on-secondary-darken-1 {
      color: rgb(var(--v-theme-on-secondary-darken-1)) !important;
    }
    .on-error {
      color: rgb(var(--v-theme-on-error)) !important;
    }
    .on-info {
      color: rgb(var(--v-theme-on-info)) !important;
    }
    .on-success {
      color: rgb(var(--v-theme-on-success)) !important;
    }
    .on-warning {
      color: rgb(var(--v-theme-on-warning)) !important;
    }
</style>


## 2023/09/19
### hw01 Rectangle Area
<div class="v-card v-theme--light v-card--density-default elevation-5 rounded-lg v-card--variant-elevated pa-2"><!----><!----><div class="pa-4"><h5 class="text-h5 font-weight-bold mb-2">Description</h5><div class="v-md-editor-preview pa-2" style="tab-size: 2;"><div class="vuepress-markdown-body"><h3 data-v-md-heading="objective" data-v-md-line="1">Objective</h3>
<p data-v-md-line="2">Practice how to write a C program that includes basic components such as main function, arithmetic expressions, and basic input and output.</p>
<h3 data-v-md-heading="description" data-v-md-line="4">Description</h3>
<p data-v-md-line="5">There is a rectangle in plane coordinates. Give you the coordinates of the upper-left and bottom-right points of the given rectangle. Please calculate the area of the rectangle.</p>
<p data-v-md-line="7"><img src="https://oj.ebg.tw/public/upload/aea7fe88aa.png" alt="Description"></p>
</div></div></div><div class="pa-4"><h5 class="text-h5 font-weight-bold mb-2">Input</h5><div class="v-md-editor-preview pa-2" style="tab-size: 2;"><div class="vuepress-markdown-body"><p data-v-md-line="1">Input contains two lines, and each line contains two numbers.</p>
<p data-v-md-line="3">The two numbers in the first line are the coordinate of the upper-left point <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>1</mn></msub><mtext>​</mtext><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mtext>​</mtext><mo stretchy="false">)</mo></mrow><annotation encoding="application/x-tex">(x_1​,y_1​)</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mclose">)</span></span></span></span><br>
The two numbers in the secend line are the coordinate of the bottom-right point <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo stretchy="false">(</mo><msub><mi>x</mi><mn>2</mn></msub><mtext>​</mtext><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mtext>​</mtext><mo stretchy="false">)</mo></mrow><annotation encoding="application/x-tex">(x_2​,y_2​)</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:1em;vertical-align:-0.25em;"></span><span class="mopen">(</span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mord">​</span><span class="mclose">)</span></span></span></span></p>
<h3 data-v-md-heading="technical-specification" data-v-md-line="6">Technical Specification</h3>
<ul data-v-md-line="8">
<li>for <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mn>30</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">30\%</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.8056em;vertical-align:-0.0556em;"></span><span class="mord">30%</span></span></span></span> of data, <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo>−</mo><mn>100</mn><mo>≤</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mn>2</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mo>≤</mo><mn>100</mn></mrow><annotation encoding="application/x-tex">-100 \le x_1, x_2, y_1, y_2 \le 100</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.7804em;vertical-align:-0.136em;"></span><span class="mord">−</span><span class="mord">100</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8304em;vertical-align:-0.1944em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.6444em;"></span><span class="mord">100</span></span></span></span>.</li>
<li>for <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mn>50</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">50\%</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.8056em;vertical-align:-0.0556em;"></span><span class="mord">50%</span></span></span></span> of data, <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo>−</mo><mn>1000</mn><mo>≤</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mn>2</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mo>≤</mo><mn>1000</mn></mrow><annotation encoding="application/x-tex">-1000 \le x_1, x_2, y_1, y_2 \le 1000</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.7804em;vertical-align:-0.136em;"></span><span class="mord">−</span><span class="mord">1000</span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8304em;vertical-align:-0.1944em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.6444em;"></span><span class="mord">1000</span></span></span></span>.</li>
<li>for <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mn>100</mn><mi mathvariant="normal">%</mi></mrow><annotation encoding="application/x-tex">100\%</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.8056em;vertical-align:-0.0556em;"></span><span class="mord">100%</span></span></span></span> of data, <span class="katex"><span class="katex-mathml"><math xmlns="http://www.w3.org/1998/Math/MathML"><semantics><mrow><mo>−</mo><msup><mn>2</mn><mn>31</mn></msup><mo>≤</mo><msub><mi>x</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>x</mi><mn>2</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>1</mn></msub><mo separator="true">,</mo><msub><mi>y</mi><mn>2</mn></msub><mo>≤</mo><msup><mn>2</mn><mn>31</mn></msup><mo>−</mo><mn>1</mn></mrow><annotation encoding="application/x-tex">-2^{31} \le x_1, x_2, y_1, y_2 \le 2^{31}-1</annotation></semantics></math></span><span class="katex-html"><span class="base"><span class="strut" style="height:0.9501em;vertical-align:-0.136em;"></span><span class="mord">−</span><span class="mord"><span class="mord">2</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height:0.8141em;"><span style="top:-3.063em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">31</span></span></span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8304em;vertical-align:-0.1944em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal">x</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:0em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">1</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mpunct">,</span><span class="mspace" style="margin-right:0.1667em;"></span><span class="mord"><span class="mord mathnormal" style="margin-right:0.03588em;">y</span><span class="msupsub"><span class="vlist-t vlist-t2"><span class="vlist-r"><span class="vlist" style="height:0.3011em;"><span style="top:-2.55em;margin-left:-0.0359em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight">2</span></span></span></span><span class="vlist-s">​</span></span><span class="vlist-r"><span class="vlist" style="height:0.15em;"><span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2778em;"></span><span class="mrel">≤</span><span class="mspace" style="margin-right:0.2778em;"></span></span><span class="base"><span class="strut" style="height:0.8974em;vertical-align:-0.0833em;"></span><span class="mord"><span class="mord">2</span><span class="msupsub"><span class="vlist-t"><span class="vlist-r"><span class="vlist" style="height:0.8141em;"><span style="top:-3.063em;margin-right:0.05em;"><span class="pstrut" style="height:2.7em;"></span><span class="sizing reset-size6 size3 mtight"><span class="mord mtight"><span class="mord mtight">31</span></span></span></span></span></span></span></span></span><span class="mspace" style="margin-right:0.2222em;"></span><span class="mbin">−</span><span class="mspace" style="margin-right:0.2222em;"></span></span><span class="base"><span class="strut" style="height:0.6444em;"></span><span class="mord">1</span></span></span></span>.</li>
</ul>
</div></div></div><div class="pa-4"><h5 class="text-h5 font-weight-bold mb-2">Output</h5><div class="v-md-editor-preview pa-2" style="tab-size: 2;"><div class="vuepress-markdown-body"><p data-v-md-line="1">The area of the rectangle.</p>
</div></div></div><div class="v-row pa-4"><div class="v-col-sm-6 v-col-12 d-flex flex-column"><h5 class="text-h5 font-weight-bold mb-2">Sample Input 1</h5><div class="position-relative flex-grow-1"><pre class="v-code pa-2 overflow-auto h-100">4 5
10 1</pre></div></div><div class="v-col-sm-6 v-col-12 d-flex flex-column"><h5 class="text-h5 font-weight-bold mb-2">Sample Output 1</h5><div class="position-relative flex-grow-1"><pre class="v-code pa-2 overflow-auto h-100">24</pre></div></div></div><!----><!----><!----><span class="v-card__underlay"></span></div>

**code**
```c=
#include <stdio.h>
#define ll long long
#define abs(x) ((x)>0?(x):(-x))
int main(void){
    ll x1, x2, y1, y2;
    scanf("%lld %lld %lld %lld", &x1, &y1, &x2, &y2);
    printf("%lld\n", abs(x1-x2)*abs(y1-y2));
    return 0;
}
```

---

## 2023/09/26
### hw02 Citizen ID Validator
[https://oj.ebg.tw/contest/115/problem/hw02](https://oj.ebg.tw/contest/115/problem/hw02)
```c=
#include <stdio.h>
int main(void){
    char s[11];
    // int list[] = {1, 0, 9, 8, 7, 6, 5, 4, 9, 3, 2, 2, 1, 0, 8, 9, 8, 7, 6, 5, 4, 3, 1, 3, 2, 0};
    int convert[] = {10, 11, 12, 13, 14, 15, 16, 17, 34, 18, 19, 20, 21, 22, 35, 23, 24, 25, 26, 27, 28, 29, 32, 30, 31, 33};
    int mu[] = {1,8,7,6,5,4,3,2,1,1};
    int T;
    scanf("%d", &T);
    while(T--){
        scanf("%s", s);
        int arr[10];
        // arr[0] = list[(int)(s[0]-'A')];
        arr[0] = convert[(int)(s[0]-'A')]/10 + (convert[(int)(s[0]-'A')]%10)*9;
        for(int i=1;i<10;i++)
            arr[i] = (int)(s[i])-(int)('0');
        if(arr[1]!=1 && arr[1]!=2){
            printf("Invalid\n");
            continue;
        }
        int sum = 0;
        for(int i=0;i<10;i++){
            sum += arr[i] * mu[i];
        }
        if(sum % 10 == 0)
            printf("Valid\n");
        else
            printf("Invalid\n");
    }
    return 0;
}
```
### ex02 Rectangle Area +
[https://oj.ebg.tw/contest/115/problem/ex02](https://oj.ebg.tw/contest/115/problem/ex02)
```c=
#include <stdio.h>
#define abs(x) ((x)>0?(x):(-(x)))
struct rec{
    double x[4];
    double y[4];
};
double getArea(struct rec R){
    //  |  | x0 x1 x2 x3 x0 |  |
    //  |  | y0 y1 y2 y3 y0 |  |  / 2
    return abs((R.x[0]*R.y[1] + R.x[1]*R.y[2] + R.x[2]*R.y[3] + R.x[3]*R.y[0])
              -(R.x[1]*R.y[0] + R.x[2]*R.y[1] + R.x[3]*R.y[2] + R.x[0]*R.y[3]))/2;
    // return sqrt(pow(R.x[1] - R.x[0],2) + pow(R.y[1] - R.y[0],2)) * sqrt(pow(R.x[2] - R.x[1],2) + pow(R.y[2] - R.y[1],2));
    // return = (R.x[0]-R.x[1])*(R.y[2]-R.y[1])-(R.y[0]-R.y[1])*(R.x[2]-R.x[1]);
}
void print_area(double area){
    if(area - (int)(area) == 0)
        printf("%d\n", (int)(area));
    else if(area*10 - (int)(area*10) == 0)
        printf("%.1lf\n", area);
    else
        printf("%.2lf\n", area);
}
int main(void){
    struct rec A, B;

    scanf("(%lf, %lf), (%lf, %lf), (%lf, %lf), (%lf, %lf)\n", &A.x[0], &A.y[0], &A.x[1], &A.y[1], &A.x[2], &A.y[2], &A.x[3], &A.y[3]);
    scanf("(%lf, %lf), (%lf, %lf), (%lf, %lf), (%lf, %lf)", &B.x[0], &B.y[0], &B.x[1], &B.y[1], &B.x[2], &B.y[2], &B.x[3], &B.y[3]);

    double A_area = getArea(A);
    double B_area = getArea(B);

    print_area(A_area);
    print_area(B_area);

    char c = ' ';
    if(A_area > B_area) c = '>';
    else if(A_area == B_area) c = '=';
    else if(A_area < B_area) c = '<';
    printf("A %c B\n", c);
    return 0;
}
```

---

## 2023/10/03
### hw03 Sudoku

---

[TOC]