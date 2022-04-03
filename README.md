# NoBG (BetterDiscord Theme)

/**
 * @name NOBG
 * @version 1.0.6.3
 * @description A translucent/frosted glass Discord theme
 * @author CapnKitten
 *
 * @website https://www.youtube.com/watch?v=dQw4w9WgXcQ
 * @source https://www.youtube.com/watch?v=dQw4w9WgXcQ
 * @donate https://www.youtube.com/watch?v=dQw4w9WgXcQ
 * @invite CTk6Z86cEU
 */

@import url("https://capnkitten.github.io/BetterDiscord/Themes/user-icons.css");
:root {
  --app-bg: url();
  --app-blur: 6px;
  --app-margin: 24px;
  --app-radius: 10px;
  --app-accent-image: none;
  --app-accent-rgb: 27,213,140;
  --app-accent-opacity: 1;
  --app-accent-text: #000;
  --sidebar-color: rgba(0,0,0,0.4);
  --main-content-color: rgba(0,0,0,0.2);
  --messages-color: rgba(0,0,0,0.4);
  --messages-radius: var(--app-radius);
  --messages-padding: 8px;
  --mention-rgb: var(--app-accent-rgb);
  --mention-hover-color: var(--app-accent-text);
  --mention-alt: 82,116,233;
  --mention-alpha: 1;
  --notification-color: #fff;
  --textarea-color: 255,255,255;
  --textarea-alpha: 0.1;
  --textarea-alpha-focus: 0.15;
  --textarea-text-color: #fff;
  --textarea-radius: 22px;
  --input-height: 36px;
  --input-radius: calc(var(--input-height) / 2);
  --card-color: rgba(0,0,0,0.4);
  --card-color-hover: rgba(0,0,0,0.5);
  --card-color-select: rgba(0,0,0,0.7);
  --card-radius: var(--app-radius);
  --button-color: rgba(var(--app-accent-rgb),var(--app-accent-opacity));
  --button-action-color: #000;
  --button-text-color: var(--app-accent-text);
  --button-radius: var(--app-radius);
  --button-alt-color: var(--card-color);
  --alert-color: #f04747;
  --alert-action-color: #fff;
  --alert-text-color: #fff;
  --popout-color: rgba(0,0,0,0.55);
  --popout-blur: 8px;
  --popout-header-opacity: 0.3;
  --popout-header-shadow: 0px 3px 9px 0px rgba(0,0,0,0.25);
  --popout-radius: var(--app-radius);
  --popout-shadow: 0 8px 10px 1px rgba(0,0,0,0.14), 0 3px 14px 2px rgba(0,0,0,0.12), 0 5px 5px -3px rgba(0,0,0,0.2);
  --nowplaying-color: 88,101,242;
  --streaming-color: 89,54,149;
  --spotify-color: 29,185,84;
  --supporter-color: rgba(var(--app-accent-rgb),var(--app-accent-opacity));
  --tooltip-color: rgba(var(--app-accent-rgb),var(--app-accent-opacity));
  --tooltip-text-color: var(--app-accent-text);
  --tooltip-font-size: 14px;
  --tooltip-padding: 8px 12px;
  --tooltip-radius: var(--app-radius);
  --tooltip-shadow: var(--elevation-high);
  --interactive-normal: #aaa;
  --interactive-hover: #ddd;
  --interactive-active: #fff;
  --interactive-muted: #777;
  --channels-default: #aaa;
  --header-secondary: #dfdfdf;
  --background-primary: transparent;
  --background-modifier-hover: rgba(255,255,255,0.075);
  --background-modifier-selected: rgba(255,255,255,0.125);
  --background-modifier-accent: rgba(255,255,255,0.175);
  --channels-default: var(--interactive-normal);
  --text-muted: var(--interactive-normal);
  --transition-time: 250ms;
  --transition-type: cubic-bezier(0.4,0,0.2,1);
  --scrollbar-color: 255,255,255;
  --scrollbar-color-alt: 0,0,0;
  --scrollbar-opacity: 0.2;
  --scrollbar-opacity-hover: 0.3;
  --scrollbar-width: 10px;
  --font-primary: Whitney,"Helvetica Neue",Helvetica,Arial,sans-serif !important;
  --font-display: Whitney,"Helvetica Neue",Helvetica,Arial,sans-serif !important;
}

/*
 *
 *	APP ELEMENTS
 *
 */
body {
  background-color: transparent;
}

.appMount-2yBXZl {
  background: var(--app-bg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

.layers-OrUESM {
  z-index: 1;
}

.layers-OrUESM {
  margin: calc(var(--app-margin) / 2) var(--app-margin) var(--app-margin) var(--app-margin);
  border-radius: var(--app-radius);
  backdrop-filter: blur(var(--app-blur));
  /*&:before {
  	position: absolute;
  	content: " ";
  	width: calc(100% + (var(--app-margin) * 2));
  	height: calc(100% + (var(--app-margin) * 2) + 24px);
  	top: calc((var(--app-margin) + 24px) * -1);
  	left: calc(var(--app-margin) * -1);
  	background-image: var(--app-bg);
  	background-repeat: no-repeat;
  	background-position: center;
  	background-size: cover;
  	background-attachment: fixed;
  	filter: blur(var(--app-blur));
  	pointer-events: none;
  	z-index: -1;
  }*/
}

.typeMacOS-3V4xXE + .app-3xd6d0 .layers-OrUESM {
  margin: var(--app-margin);
}

.app-2CXKsg,
.bg-1QIAus {
  background-color: transparent;
}

.appMount-2yBXZl * {
  text-shadow: 0px 1px 2px rgba(0, 0, 0, 0.5);
}

.anchor-1MIwyf {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.appMount-2yBXZl svg {
  filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.5));
}

::selection {
  background: rgba(var(--app-accent-rgb), 0.65);
  color: var(--app-accent-text);
}

/* APP ELEMENTS -> TOP BAR */
.titleBar-1it3bQ {
  height: 24px;
}

.wordmarkWindows-2dq6rw {
  color: #fff;
}

.withFrame-2dL45i {
  margin-top: 0;
}

.winButton-3UMjdg {
  height: 100%;
  top: 0;
  color: #fff;
}

.platform-osx .wrapper-1_HaEi {
  margin-top: 0;
  padding-top: 35px;
}
.platform-osx .tree-3tCaw8 {
  margin-top: 32px;
}

.typeMacOS-3V4xXE {
  top: var(--app-margin);
  left: var(--app-margin);
}
.typeMacOS-3V4xXE .macButtons-eIdy0e {
  width: 72px;
  border-top-left-radius: var(--app-radius);
}
.typeMacOS-3V4xXE .macButtons-eIdy0e .macButton-2M5W_9 {
  cursor: pointer;
}

.topic-11NuQZ a {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

/* APP ELEMENTS -> NOTIFICATION BAR */
.notice-2FJMB4,
.notice-1tZwqv,
.noticeWrapper-8z511t,
.colorInfo-1kEg3T,
.noticeSurvey-1XW9Ln.noticeInfo-3_iTE1.notice-2FJMB4.size14-y91Il2.height36-36OHCc {
  /*margin: 0 var(--app-margin);*/
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  /*border-radius: 18px !important;*/
  border-radius: 0;
  border-top-right-radius: var(--app-radius);
  box-shadow: none;
  color: var(--app-accent-text);
}

.notice-2HEN-u,
.noticeStreamerMode-2TSQpg {
  margin: 0;
  background-color: rgba(var(--streaming-color), 0.5);
  border-radius: 0 !important;
  color: #fff;
}

.notice-2FJMB4 + .notice-2FJMB4 {
  margin-top: 4px;
}

#outdatedPlugins > span,
#pluginNotice #outdatedPlugins span {
  color: var(--app-accent-text) !important;
}

.notice-2FJMB4 .button-1MICoQ {
  color: var(--app-accent-text);
}

.noticeStreamerMode-2TSQpg .button-1MICoQ {
  color: #fff;
}

/* APP ELEMENTS -> NOTIFICATION BAR -> BUTTONS */
.notice-1tZwqv .lookOutlined-3yKVGo.colorWhite-rEQuAQ {
  color: var(--app-accent-text);
  border-color: var(--app-accent-text);
}

.notice-1tZwqv .button-3Ijpww:hover {
  background-color: transparent;
}

/* APP ELEMENTS -> LOADING ICON */
@keyframes spinnerone {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  75% {
    -webkit-transform: rotate(-720deg);
    transform: rotate(-720deg);
  }
  100% {
    -webkit-transform: rotate(-720deg);
    transform: rotate(-720deg);
  }
}
@keyframes spinnertwo {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  75% {
    -webkit-transform: rotate(720deg);
    transform: rotate(720deg);
  }
  100% {
    -webkit-transform: rotate(720deg);
    transform: rotate(720deg);
  }
}
.spinner-2RT7ZC:not(.ti-indicator) {
  --spinner-size: 2em;
}

.spinner-2RT7ZC:not(.ti-indicator) .inner-26JK4f {
  width: calc(var(--spinner-size) * 1.175);
  height: calc(var(--spinner-size) * 1.175);
}

.spinningCircleInner-C1kTEL {
  transform: rotate(0deg);
}

.spinningCircleInner-C1kTEL:before,
.spinningCircleInner-C1kTEL:after {
  content: " ";
}

.wanderingCubesItem-3Us-UG,
.spinningCircleInner-C1kTEL:before,
.spinningCircleInner-C1kTEL:after {
  position: absolute;
  display: inline-block;
  background-color: transparent;
  border: calc(var(--spinner-size) / 12) solid transparent;
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) transparent rgba(var(--app-accent-rgb), var(--app-accent-opacity)) transparent;
}

.wanderingCubesItem-3Us-UG:first-of-type,
.spinningCircleInner-C1kTEL:before {
  width: calc(var(--spinner-size) / 2);
  height: calc(var(--spinner-size) / 2);
  border-radius: calc(var(--spinner-size) / 2);
  margin: calc(var(--spinner-size) / 4) 0 0 calc(var(--spinner-size) / 4);
  -webkit-animation: spinnerone 2000ms ease-in-out infinite;
  -moz-animation: spinnerone 2000ms ease-in-out infinite;
  animation: spinnerone 2000ms ease-in-out infinite;
}

.wanderingCubesItem-3Us-UG:last-of-type,
.spinningCircleInner-C1kTEL:after {
  width: var(--spinner-size);
  height: var(--spinner-size);
  border-radius: var(--spinner-size);
  -webkit-animation: spinnertwo 2000ms ease-in-out infinite;
  -moz-animation: spinnertwo 2000ms ease-in-out infinite;
  animation: spinnertwo 2000ms ease-in-out infinite;
}

.circular-3Fmqjd {
  display: none;
}

/*
 *
 *	MODALS
 *
 */
.root-g14mjS {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
}
.root-g14mjS.popout-3gby1q {
  backdrop-filter: blur(var(--app-blur));
}
.root-g14mjS .footer-31IekZ {
  background-color: transparent;
  box-shadow: none;
}
.root-g14mjS.modal-ZdazA8 {
  height: auto;
  min-height: 150px;
}

/* */
.backdrop-2ByYRN,
.backdropWithLayer-3_uhz4 {
  background-color: rgba(0, 0, 0, 0.3) !important;
  backdrop-filter: blur(calc(var(--popout-blur) * 1.4));
  opacity: 1 !important;
}

.popouts-2bnG9Z + div:not(:empty) + div:not([class]) + .layerContainer-2v_Sit .backdropWithLayer-3_uhz4 {
  opacity: 0 !important;
}

.root-g14mjS .modal-2RrUKJ:before {
  display: none;
}

.small-23Atuv {
  min-height: 100px;
}

.header-1zd7se,
.header-1zd7se.separator-2lLxgC {
  box-shadow: var(--popout-header-shadow);
}

.content-2hZxGK {
  padding-top: 16px;
}

/* MODALS -> TOOLTIPS */
.subscribeTooltipWrapper-32-Ce8:after {
  display: none;
}

/* MODALS -> LOGIN */
[class*=theme-] .authBox-1HR6Ha {
  background-color: var(--popout-color);
}

[class*=theme-] .authBox-1HR6Ha:before {
  background-image: none;
}

.image-3yFrLs,
.canvas-2dBZRV,
.fallbackImage-kwjEnv {
  display: none;
}

.leftSplit-hm3715 {
  max-width: 100%;
}

/* MODALS -> CREATE SERVER */
.container-1Lk8p7 {
  --modal-header-text: #ddd;
  --modal-normal-text: #aaa;
}
.container-1Lk8p7 .header-1c1AhF,
.container-1Lk8p7 .header-1AP5SJ,
.container-1Lk8p7 .header-1zd7se {
  padding: 24px 16px 12px;
}

.header-1c1AhF .title-1_TkpU,
.header-1AP5SJ .title-2Giw-4,
.header-1zd7se .title-1LqMUp,
.footer-3ie9JP .colorStandard-21JIj7 {
  color: var(--modal-header-text);
}

.container-1Lk8p7 .colorHeaderSecondary-g5teka {
  color: var(--modal-normal-text);
}

.container-1Lk8p7 .lookBlank-3eh9lL,
[class*=theme-] .container-1Lk8p7 .lookLink-15mFoz.colorPrimary-2AuQVo {
  color: var(--modal-normal-text);
}

.iconContainer-GFfNaA path {
  fill: var(--modal-normal-text);
}

.iconContainer-GFfNaA circle {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.iconContainer-GFfNaA circle + path {
  fill: var(--app-accent-text);
}

[class*=theme-] .footer-3ie9JP {
  box-shadow: none;
}

/* MODALS -> CREATE SERVER -> OPTIONS */
.templatesList-uohY49 {
  --scrollbar-color-alt: 255,255,255;
  margin-top: 0;
  padding-top: 16px;
}

.container-x8Y1ix {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.container-x8Y1ix:hover {
  background-color: var(--card-color-hover);
}
.container-x8Y1ix .colorStandard-21JIj7 {
  color: var(--modal-normal-text);
}

/* MODALS -> JOIN SERVER */
.input-m1-Y7Q {
  background-color: transparent;
}

.formTitle-2YQyhj {
  color: var(--modal-normal-text);
}

.sampleLink-5BWNy9 {
  color: #999;
}

/* MODALS -> QUICK SWITCHER */
.container-qBnZJg {
  background-color: transparent !important;
  box-shadow: none !important;
}

.quickswitcher-pKcM9U {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}

/* MODALS -> PINNED MESSAGES */
.iconBadge-3Mmg92 {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.5);
}

.messagesPopoutWrap-3zryHW {
  background-color: transparent;
  border-radius: var(--popout-radius);
  overflow: hidden;
}
.messagesPopoutWrap-3zryHW:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

#pinned-messages,
.messagesPopoutWrap-3zryHW {
  max-height: 80vh !important;
}

.header-1w9Q93 {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

.messagesPopout-eVzQcI {
  padding: 16px 0 0 8px;
}

.messageGroupWrapper-1jf_7C {
  margin-bottom: 16px;
  background-color: transparent;
  border: none;
}
.messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN {
  margin-left: 56px !important;
  margin-right: 16px !important;
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
}
.messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN .contents-2MsGLg,
.messageGroupWrapper-1jf_7C .messageGroupCozy-3v_RqN .container-2sjPya {
  overflow: hidden;
}

.footer-5ji8u1 {
  background-color: transparent;
}

/* MODALS -> SEARCH SERVER */
.container-2McqkF {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}

.option-ayUoaq {
  border-radius: var(--popout-radius);
}
.option-ayUoaq:after {
  display: none;
}
.option-ayUoaq[aria-selected=true] {
  background-color: var(--background-modifier-hover);
}

.focused-2FU0YH {
  background-color: transparent !important;
}

.queryContainer-ZunrLZ {
  border: none;
  box-shadow: var(--popout-header-shadow);
}

.resultsGroup-cfY57t:before {
  display: none;
}

/* MODALS -> INBOX */
.container-2ebMPP {
  background-color: transparent;
  border-radius: var(--popout-radius);
  overflow: hidden;
}
.container-2ebMPP:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

.scroller-MIi2ab,
.scroller-145h9c {
  margin-top: 16px;
  padding: 0 16px 8px 16px;
}

.container-iA3Qrz,
.channel-3NJZ1V {
  margin: 0;
  margin-bottom: 16px;
  padding-left: 0;
  padding-right: 0;
}

.channel-3NJZ1V {
  margin: 0 0 24px;
  padding-bottom: 0;
}

.channelHeader-DFRX8q,
.messageContainer-3VTXBC {
  background-color: transparent;
}

.channelHeader-DFRX8q {
  padding: 12px 16px 12px 28px;
  background-color: transparent;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}
.channelHeader-DFRX8q:before {
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
}

.button-1_oXub {
  background-color: var(--background-modifier-hover);
}
.button-1_oXub:hover {
  background-color: var(--background-modifier-selected) !important;
}

.collapseButton-39-IRc {
  left: 4px;
}

.messageContainer-3VTXBC,
.messageContainer-8dSNjf {
  padding: 16px 0;
}
.messageContainer-3VTXBC .cozy-VmLDNB.wrapper-30-Nkg,
.messageContainer-8dSNjf .cozy-VmLDNB.wrapper-30-Nkg {
  margin-left: 88px;
  margin-right: 0;
}
.messageContainer-3VTXBC .cozy-VmLDNB.wrapper-30-Nkg:not(.groupStart-3Mlgv1),
.messageContainer-8dSNjf .cozy-VmLDNB.wrapper-30-Nkg:not(.groupStart-3Mlgv1) {
  margin-top: 2px;
}

.message-3g3FYR,
.message-372Ods {
  overflow: visible;
}

.messages-23can0 {
  padding: 16px 0;
  background-color: transparent;
}

.container-2sjPya {
  overflow: hidden;
}

/* MODALS -> USER POPOUT */
.userPopout-2j1gM4 {
  background-color: transparent;
  background-color: transparent !important;
  border-radius: var(--popout-radius);
  overflow: hidden;
}
.userPopout-2j1gM4:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

.headerNormal-1mX3KY {
  background-color: rgba(0, 0, 0, var(--popout-header-opacity));
}

.banner-1YaD3N {
  border-radius: var(--popout-radius) var(--popout-radius) 0 0;
}

.headerTop-3GPUSF {
  background-color: rgba(0, 0, 0, var(--popout-header-opacity));
  border-bottom: 1px solid var(--background-modifier-accent);
}

.divider-1wtgZ3 {
  display: none;
}

.activity-3v9l4T {
  padding: 16px;
}

.body-2wLx-E,
.bodyInnerWrapper-2bQs1k,
.footer-3naVBw {
  background-color: transparent;
}

.body-2wLx-E {
  padding: 16px;
}

.footer-3naVBw {
  padding: 0 16px 16px;
}

.avatar-2Vndt_ {
  background-color: transparent;
  border: none;
  box-shadow: var(--popout-shadow);
}
.avatar-2Vndt_ svg {
  filter: none;
}

.role-2TIOKu {
  background-color: var(--card-color);
  border-radius: 11px;
}

.StatusEverywhere-avatar-userPopout {
  border: none !important;
}

.avatarHint-k7pYop {
  top: 0;
  left: 0;
}

.loadingPopout-1feYe_ {
  border-radius: var(--popout-radius);
}

/* MODALS -> USER PROFILE */
.avatar-3QF_VA {
  background-color: transparent;
  border: none;
  box-shadow: var(--popout-shadow);
}
.avatar-3QF_VA svg {
  filter: none;
}

.topSection-13QKHs {
  background-color: rgba(0, 0, 0, var(--popout-header-opacity));
}

.body-1Ukv50 {
  background-color: transparent;
}

.note-Go5ZP2 textarea {
  padding: 7px 8px;
  border-radius: var(--input-radius);
  font-size: 14px;
}

/* MODALS -> UPLOAD */
.uploadModal-2ie9O_ .footer-VCsJQY {
  background-color: transparent !important;
  box-shadow: none;
}
.uploadModal-2ie9O_ .footer-VCsJQY .lookLink-15mFoz {
  margin-right: 8px;
}

.upload-3GTSF9 {
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
}

.channelTextAreaUpload-30SRDh {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 22px;
}

/* MODALS -> UPLOAD -> DRAG AND DROP */
.uploadArea-2Nu_Vc {
  height: 100vh;
  top: -24px;
  background-color: rgba(0, 0, 0, 0.3) !important;
  backdrop-filter: blur(calc(var(--popout-blur) * 1.4));
}

.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .bgScale-1iWuPF {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
}
.uploadModalIn-2w48Zf .uploadDropModal-13Kd20 .inner-rBP-MS {
  border: none;
}

/* MODALS -> INVITE */
.header-1J9IaL .inner-1NoIT5 {
  height: 36px;
  padding: 0 8px;
}
.header-1J9IaL .inner-1NoIT5 .input-2FSSDe {
  height: 100%;
  margin: 0;
}
.header-1J9IaL .inner-1NoIT5 .iconLayout-SqV3nb {
  height: 100%;
}

.scroller-3nFW5p {
  padding-right: 12px !important;
}

/* MODALS -> INVITED TO SERVER */
[class*=theme-] .contentWrapper-3oy4Xo {
  background-color: transparent;
}

.pill-qMtBTq {
  background-color: var(--popout-color);
}

.inviteSplash-2Q0PLE {
  border-radius: 0 var(--popout-radius) var(--popout-radius) 0;
}

/* MODALS -> INVITED TO SERVER -> WELCOME STUFF */
.optionContainer-yOpaLq {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}
.optionContainer-yOpaLq:hover {
  background-color: var(--card-color-hover);
}

/*
 *
 *	CONTEXT MENU
 *
 */
.item-1OdjEX {
  border-radius: var(--popout-radius);
}
.item-1OdjEX.colorBrand-3cPPsm {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.colorDefault-CDqZdO.focused-3qFvc8, .colorDefault-CDqZdO:active:not(.hideInteraction-2jPGL_) {
  background-color: var(--background-modifier-selected);
  background-image: var(--app-accent-image);
}

/*
 *
 *	BUTTONS
 *
 */
.button-f2h6uQ {
  border-radius: var(--button-radius);
  /*filter: saturate(var(--saturation-factor));*/
}

.centerButton-1IShs7 {
  border-radius: 50%;
}

.lookLink-15mFoz.colorBrand-I6CyqQ {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

/* BUTTONS -> ACCENT BACKGROUND-COLOR */
.lookFilled-yCfaCM {
  background-color: var(--button-color) !important;
}
.lookFilled-yCfaCM:hover, .lookFilled-yCfaCM:active, .lookFilled-yCfaCM:disabled {
  background-color: var(--button-color) !important;
}
.lookFilled-yCfaCM .contents-3ca1mk {
  color: var(--button-text-color);
}

.lookOutlined-3yKVGo.colorRed-rQXKgM {
  background-color: var(--alert-color);
}
.lookOutlined-3yKVGo.colorRed-rQXKgM:hover, .lookOutlined-3yKVGo.colorRed-rQXKgM:active, .lookOutlined-3yKVGo.colorRed-rQXKgM:disabled {
  background-color: var(--alert-color);
}
.lookOutlined-3yKVGo.colorRed-rQXKgM .contents-3ca1mk {
  color: var(--alert-text-color);
}

.lookLink-15mFoz {
  --button-action-color: #fff;
}
.lookLink-15mFoz:hover .contents-3ca1mk {
  background-image: none !important;
}

.colorable-3rVGna.green-3wkLbx, .colorable-3rVGna.primaryDark-2UJt1G {
  background-color: var(--button-color) !important;
}
.colorable-3rVGna.green-3wkLbx:hover, .colorable-3rVGna.green-3wkLbx:active, .colorable-3rVGna.green-3wkLbx:disabled, .colorable-3rVGna.primaryDark-2UJt1G:hover, .colorable-3rVGna.primaryDark-2UJt1G:active, .colorable-3rVGna.primaryDark-2UJt1G:disabled {
  background-color: var(--button-color) !important;
}
.colorable-3rVGna.green-3wkLbx .centerIcon-JYpTUi, .colorable-3rVGna.primaryDark-2UJt1G .centerIcon-JYpTUi {
  color: var(--button-text-color);
}
.colorable-3rVGna.red-3T8maV {
  background-color: var(--alert-color) !important;
}
.colorable-3rVGna.red-3T8maV:hover, .colorable-3rVGna.red-3T8maV:active, .colorable-3rVGna.red-3T8maV:disabled {
  background-color: var(--alert-color) !important;
}
.colorable-3rVGna.red-3T8maV .centerIcon-JYpTUi {
  color: var(--alert-text-color);
}

.lookFilled-yCfaCM,
.lookOutlined-3yKVGo,
.lookLink-15mFoz,
.colorable-3rVGna {
  overflow: hidden;
}
.lookFilled-yCfaCM:before,
.lookOutlined-3yKVGo:before,
.lookLink-15mFoz:before,
.colorable-3rVGna:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--button-action-color);
  opacity: 0;
  pointer-events: none;
  transition: var(--transition-time) var(--transition-type);
}
.lookFilled-yCfaCM:hover:before,
.lookOutlined-3yKVGo:hover:before,
.lookLink-15mFoz:hover:before,
.colorable-3rVGna:hover:before {
  opacity: 0.075;
}
.lookFilled-yCfaCM:active:before,
.lookOutlined-3yKVGo:active:before,
.lookLink-15mFoz:active:before,
.colorable-3rVGna:active:before {
  opacity: 0.15;
}

.lookFilled-yCfaCM.colorBrand-I6CyqQ:disabled:before,
.lookFilled-yCfaCM.colorBrand-I6CyqQ.fauxDisabled-8w0hCZ:before {
  display: none;
}

/*
 *
 *	TOOLTIPS
 *
 */
.tooltip-14MtrL.tooltipPrimary-3qLMbS, .tooltip-14MtrL.tooltipBlack-vMYxvw, .tooltip-14MtrL.tooltipGrey-lpLZjh, .tooltip-14MtrL.tooltipRed-2z14Wl, .tooltip-14MtrL.tooltipBrand-20XsMA {
  background-color: var(--tooltip-color) !important;
  background-image: var(--app-accent-image);
  border-radius: var(--tooltip-radius);
}
.tooltip-14MtrL.tooltipPrimary-3qLMbS .tooltipPointer-3L49xb, .tooltip-14MtrL.tooltipBlack-vMYxvw .tooltipPointer-3L49xb, .tooltip-14MtrL.tooltipGrey-lpLZjh .tooltipPointer-3L49xb, .tooltip-14MtrL.tooltipRed-2z14Wl .tooltipPointer-3L49xb, .tooltip-14MtrL.tooltipBrand-20XsMA .tooltipPointer-3L49xb {
  border-top-color: var(--tooltip-color);
}
.tooltip-14MtrL.tooltipPrimary-3qLMbS,
.tooltip-14MtrL.tooltipPrimary-3qLMbS .guildNameText-jBFbNC, .tooltip-14MtrL.tooltipBlack-vMYxvw,
.tooltip-14MtrL.tooltipBlack-vMYxvw .guildNameText-jBFbNC, .tooltip-14MtrL.tooltipGrey-lpLZjh,
.tooltip-14MtrL.tooltipGrey-lpLZjh .guildNameText-jBFbNC, .tooltip-14MtrL.tooltipRed-2z14Wl,
.tooltip-14MtrL.tooltipRed-2z14Wl .guildNameText-jBFbNC, .tooltip-14MtrL.tooltipBrand-20XsMA,
.tooltip-14MtrL.tooltipBrand-20XsMA .guildNameText-jBFbNC {
  color: var(--tooltip-text-color);
}

[class*=theme-] .activityIcon-vfIBet,
[class*=theme-] .tooltipGrey-lpLZjh,
.title-2IIJok,
.clickCTA-1bk0UN {
  color: var(--tooltip-text-color);
}

.subscribeTooltipWrapper-3ipXtC {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}
.subscribeTooltipWrapper-3ipXtC:after {
  border-bottom-color: var(--popout-color);
  backdrop-filter: blur(var(--popout-blur));
}

/*
 *
 *	TOASTS
 *
 */
.bd-toasts {
  bottom: 96px !important;
}

.toast,
.bd-toast {
  top: -56px;
  margin-top: 8px;
  padding: 10px !important;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  border-radius: 16px;
  color: var(--text-normal);
}
.toast:not(.toast-custom),
.bd-toast:not(.toast-custom) {
  background-color: var(--popout-color) !important;
  background-image: none !important;
}
.toast.toast-custom,
.bd-toast.toast-custom {
  border-radius: 23px;
}
.toast.toast-custom:before,
.bd-toast.toast-custom:before {
  display: none !important;
}

.bd-toast:before {
  background-color: rgba(0, 0, 0, 0.5);
  border-radius: 17px;
}

/*
 *
 *	TITLEBARS
 *
 */
.container-ZMc96U.themed-Hp1KC_ {
  background-color: transparent;
  overflow: hidden;
}

.container-ZMc96U.themed-Hp1KC_:before {
  background-color: transparent;
}

.chat-2ZfjoI .container-ZMc96U.themed-Hp1KC_,
.libraryHeader-2loraV.container-ZMc96U.themed-Hp1KC_:before {
  background-color: transparent;
}

.clickable-vvKY2q .header-3OsQeK:hover,
.selected-1GtAC5 .header-3OsQeK {
  background-color: transparent;
}

.container-ZMc96U.themed-Hp1KC_,
.header-2o-2hj,
.header-3OsQeK,
.searchBar-3TnChZ {
  box-shadow: var(--popout-header-shadow);
}

.children-3xh0VB:after {
  display: none;
}

/* TITLEBARS -> SEARCH BARS */
.searchBar-jGtisZ,
.searchBar-3TnChZ .searchBarComponent-3N7dCG {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 12px;
}

.searchBar-jGtisZ {
  padding: 0 6px;
}
.searchBar-jGtisZ .searchBarComponent-3N7dCG {
  padding: 0 8px;
  border-radius: 14px;
}

/*
 *
 *	INPUTS, TEXTAREAS, SELECTS
 *
 */
input,
textarea {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha)) !important;
  border: none !important;
  color: var(--textarea-text-color) !important;
  transition: var(--transition-time) var(--transition-type) !important;
}
input:focus,
textarea:focus {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha-focus)) !important;
}

input::-webkit-input-placeholder {
  color: var(--textarea-text-color) !important;
  opacity: 0.75;
}

.input-2g-os5 {
  background-color: transparent;
  border: none;
}

.inputDefault-3FGxgL,
.input-2QVoG3 {
  height: var(--input-height);
  border-radius: var(--input-radius);
}

.inputMaxLength-3n06SD textarea.input-2g-os5 {
  height: unset;
  min-height: var(--input-height);
}

.copyInput-1dXbXE,
.copyInput-3AbKWB {
  height: var(--input-height);
  background-color: rgba(var(--textarea-color), var(--textarea-alpha)) !important;
  border-radius: var(--input-radius);
  border: none;
  transition: var(--transition-time) var(--transition-type);
}
.copyInput-1dXbXE:focus-within,
.copyInput-3AbKWB:focus-within {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha-focus)) !important;
}
.copyInput-1dXbXE + .copyButton-2k4drX,
.copyInput-3AbKWB + .copyButton-2k4drX {
  margin-left: 12px;
}
.copyInput-1dXbXE .inputWrapper-2-2Zoc,
.copyInput-3AbKWB .inputWrapper-2-2Zoc {
  margin-right: 0;
}

.copyInput-1dXbXE .inputDefault-3FGxgL,
.copyInput-3AbKWB .inputDefault-1AaKiD {
  background-color: transparent !important;
}

.copyInput-3AbKWB .lookGhost-2Fn_0-.colorGrey-2iAG-B {
  height: var(--input-height);
  margin: 0 4px 0 0;
  padding: 0 20px !important;
  background-color: transparent;
}

/* SELECTS */
.lookFilled-1h1y05.select-1Pkeg4,
.css-1a8reka-control,
.css-2yldzf-control,
.css-1yegjoj-control,
.css-17yssst-control,
.css-gd8if9-control,
.css-gvi9bl-control,
.css-6fzn47-control,
.css-17e1tep-control,
.css-118dehu-control {
  min-height: var(--input-height);
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 20px;
  border: none;
  transition: var(--transition-time) var(--transition-type);
}

.css-118dehu-control {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  opacity: 0.5;
}

.css-hsd1lu-singleValue,
.css-1fb6fll-indicatorContainer {
  opacity: 1;
}

.css-eo20y5 {
  opacity: 0;
}

.css-2yldzf-control {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha-focus));
}

.popout-2sKjHu,
.css-n57xjs-menu,
.css-3vaxre-menu {
  margin-top: 8px;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  border: none;
  overflow: hidden;
}

.optionActive-KkAdqq,
.optionFocused-8MflSE,
.css-1gnr91b-option,
.css-1gnr91b-option:active,
.css-rzbxvl-option,
.css-rzbxvl-option:active {
  background-color: var(--background-modifier-hover);
  color: var(--text-normal);
}

.css-12o7ek3-option,
.css-1ba14n5-option {
  background-color: var(--background-modifier-selected);
}

.option-1mJRMP:first-child,
.css-1gnr91b-option:first-child,
.css-12o7ek3-option:first-child,
.css-1ba14n5-option:first-child {
  border-radius: var(--popout-radius) var(--popout-radius) 0 0;
}

.option-1mJRMP:last-child,
.css-1gnr91b-option:last-childm .css-1ba14n5-option:last-child {
  border-radius: 0 0 var(--popout-radius) var(--popout-radius);
}

.option-1mJRMP:only-child {
  border-radius: var(--popout-radius);
}

.css-7s2e5v {
  opacity: 0;
}

/*
 *
 *	SWITCHES, CHECKBOXES, RADIOS
 *
 */
.barFill-2Bh7CX {
  background: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  /*filter: saturate(var(--saturation-factor));*/
}

.grabber-2GQyvM {
  background-color: var(--app-accent-text);
  border: none;
  /*filter: saturate(var(--saturation-factor));*/
}

.volumeSlider-sR5g00 .grabber-2GQyvM {
  width: 12px;
  height: 12px;
  background-color: #fff;
}

/* SWITCHES */
.themeDefault-24hCdX.valueChecked-m-4IJZ {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}

.valueUnchecked-2lU_20:after,
.themeDefault-24hCdX.sizeDefault-2YlOZr.valueUnchecked-2lU_20:after,
.bd-switch:after {
  background-color: #222 !important;
}

.container-2nx-BQ {
  /*filter: saturate(var(--saturation-factor));*/
}
.container-2nx-BQ[style*="background-color: hsl(138"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(138"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(138"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(139"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(139"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(139"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(140"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(140"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(140"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(141"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(141"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(141"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(142"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(142"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(142"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(143"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(143"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(143"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(144"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(144"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(144"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(145"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(145"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(145"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(146"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(146"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(146"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(147"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(147"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(147"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(148"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(148"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(148"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(149"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(149"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(149"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(150"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(150"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(150"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(151"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(151"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(151"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(152"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(152"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(152"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(153"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(153"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(153"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(154"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(154"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(154"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(155"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(155"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(155"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(156"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(156"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(156"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(157"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(157"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(157"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(158"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(158"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(158"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(159"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(159"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(159"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(160"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(160"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(160"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(161"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(161"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(161"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(162"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(162"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(162"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(163"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(163"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(163"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(164"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.container-2nx-BQ[style*="background-color: hsl(164"] .slider-32CRPX rect {
  fill: var(--app-accent-text) !important;
}
.container-2nx-BQ[style*="background-color: hsl(164"] .slider-32CRPX path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}

.container-2nx-BQ[style*="background-color: hsl(194"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(194"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(194"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(195"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(195"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(195"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(196"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(196"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(196"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(197"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(197"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(197"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(198"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(198"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(198"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(199"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(199"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(199"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(200"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(200"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(200"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(201"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(201"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(201"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(202"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(202"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(202"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(203"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(203"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(203"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(204"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(204"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(204"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(205"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(205"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(205"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(206"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(206"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(206"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(207"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(207"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(207"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(208"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(208"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(208"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(209"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(209"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(209"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(210"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(210"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(210"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(211"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(211"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(211"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(212"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(212"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(212"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(213"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(213"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(213"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(214"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(214"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(214"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(215"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(215"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(215"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(216"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(216"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(216"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(217"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(217"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(217"] .slider-32CRPX path {
  fill: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(218"] {
  background-color: #777 !important;
}
.container-2nx-BQ[style*="background-color: hsl(218"] .slider-32CRPX rect {
  fill: #222 !important;
}
.container-2nx-BQ[style*="background-color: hsl(218"] .slider-32CRPX path {
  fill: #777 !important;
}

.size-3rFEHg:after,
.size-3rFEHg:active:after,
.bd-switch-checked:after {
  background-color: var(--app-accent-text) !important;
  transition: var(--transition-time) var(--transition-type);
}

.cardPrimaryEditable-2mz_3i[style*="border-color: rgb(114, 137, 218); background-color: rgb(114, 137, 218);"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}

.bd-switch input:checked + .bd-switch-body {
  --switch-color: rgba(var(--app-accent-rgb),var(--app-accent-opacity));
}

.bd-switch .bd-switch-body .bd-switch-slider .bd-switch-handle {
  fill: #222;
}

.bd-switch.bd-switch-checked .bd-switch-body .bd-switch-slider .bd-switch-handle {
  fill: var(--app-accent-text);
}

/* CHECKBOXES */
[class*=theme-] .checkbox-f1HnKB {
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  /*filter: saturate(var(--saturation-factor));*/
}
[class*=theme-] .checkbox-f1HnKB.checked-1pZh2h {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
[class*=theme-] .checkbox-f1HnKB.checked-1pZh2h path {
  fill: var(--app-accent-text) !important;
}

.colorDefault-CDqZdO .checkbox-hADx5o {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.colorDefault-CDqZdO .check-3HZJs4 {
  color: var(--app-accent-text);
}
.colorDefault-CDqZdO.focused-3qFvc8 .checkbox-hADx5o {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.colorDefault-CDqZdO.focused-3qFvc8 .check-3HZJs4 {
  color: var(--app-accent-text);
}

/* CHECKBOXES -> SPECIAL COLORS */
.item-2idW98[style*="background-color: rgb(67, 181, 129)"] .checked-1pZh2h path {
  fill: #43b581 !important;
}

.item-2idW98[style*="background-color: rgb(250, 166, 26)"] .checked-1pZh2h path {
  fill: #faa61a !important;
}

.item-2idW98[style*="background-color: rgb(240, 71, 71)"] .checked-1pZh2h path {
  fill: #f04747 !important;
}

.connection-YOVI9j .size-3rFEHg:after {
  background-color: #fff;
}

/* RADIOS */
.item-2idW98 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  /*filter: saturate(var(--saturation-factor));*/
}
.item-2idW98:hover {
  background-color: var(--card-color-hover);
}
.item-2idW98[aria-checked=true] {
  background-color: var(--card-color-select);
}
.item-2idW98[aria-checked=true] path,
.item-2idW98[aria-checked=true] .radioIconForeground-2BMavi {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

/*
 *
 *	CARDS
 *
 */
.cardPrimary-3qRT__,
.cardPrimaryEditable-2mz_3i,
.cardPrimaryOutline-1ofwVz,
.integration-1f5IUi,
.tutorial-Nb3Zz5,
.ctaBar-2UsjF2,
[class*=theme-] .codeRedemptionRedirect-3SBiCp,
[class*=theme-] .perk-2WeBWW,
[class*=theme-] .bd-addon-list .bd-addon-card,
.footer-3Zgy_M,
.connection-YOVI9j,
.warning-RBGtx2 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

.warning-RBGtx2 {
  border: 1px solid rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.warning-RBGtx2 .icon-2fP4ae {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.connection-YOVI9j {
  box-shadow: none !important;
}

.bd-addon-list .bd-addon-header {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

/*
 *
 *	SERVER LIST
 *
 */
.wrapper-1_HaEi {
  background-color: var(--sidebar-color);
}
.wrapper-1_HaEi .tree-3agP2X:focus {
  outline: none;
}

.scroller-3X7KbA {
  background-color: transparent;
}

.childWrapper-1j_1ub,
.wrapper-3kah-n.selected-1Drb7Z .childWrapper-1j_1ub,
.wrapper-3kah-n:hover .childWrapper-1j_1ub {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
}

.childWrapper-1j_1ub,
.wrapper-3kah-n.selected-1Drb7Z .childWrapper-1j_1ub,
.wrapper-3kah-n:hover .childWrapper-1j_1ub {
  color: var(--app-accent-text);
}

.mention-3XBnnZ {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.circleIconButton-1VxDrg, .circleIconButton-1VxDrg:hover, .circleIconButton-1VxDrg.selected-2r1Hvo {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.numberBadge-37OJ3S {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.guildsError-b7zR5H {
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.guildsError-b7zR5H:hover {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  color: var(--app-accent-text);
}

.verified-1Jv_7P,
.partnered-23cXFN {
  color: var(--app-accent-text);
}

.icon-3BYlXK {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.header-2o-2hj .verified-1Jv_7P,
.header-2o-2hj .partnered-23cXFN,
.listRow-hutiT_ .verified-1Jv_7P,
.listRow-hutiT_ .partnered-23cXFN {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.header-2o-2hj .icon-3BYlXK,
.listRow-hutiT_ .icon-3BYlXK {
  color: var(--app-accent-text);
}

.guildInfo-PdhToW .flowerStar-2tNFCR path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.guildInfo-PdhToW .icon-3BYlXK {
  color: var(--app-accent-text);
}

.flowerStar-2tNFCR {
  stroke: none;
}

.iconBadge-1D5-9X.participating-1NvRVd {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
}
.iconBadge-1D5-9X.participating-1NvRVd path {
  fill: var(--app-accent-text);
}

.item-2LIpTv {
  background-color: var(--notification-color);
}

/* SERVER LIST -> FOLDERS */
.expandedFolderBackground-1cujaW {
  background-color: rgba(255, 255, 255, 0.1);
  border-radius: 16px 16px 24px 24px;
}
.expandedFolderBackground-1cujaW + .listItem-GuPuDH .svg-2zuE5p {
  filter: none;
}

.folder-1hbNCn {
  background-color: transparent;
}
.folder-1hbNCn.hover-qTxTR_ {
  background-color: rgba(255, 255, 255, 0.1);
}

/* SERVER LIST -> CREATE/JOIN SERVER */
.header-3ZP1MY,
.title-OdeD-o {
  color: #eee;
}

.action-1lSjCi .colorStandard-21JIj7,
.description-QF3836,
.description-Bw8krY,
.inputLabel-vJ2Z0B,
.label-wQQoIq,
.helpText-h3r3wC,
.avatarUploader-AF-hm- .sizeInfo-Wk0Ksj,
.connectCTA-37DS2Y,
.nameInput-ph8KMi .h5-2RwDNl,
.guidelines-FvqqF2,
.creationIntentText-OH-CFI,
.footerTitle-3Bslxi {
  color: #ccc;
}

.action-1lSjCi {
  background-color: var(--card-color);
  border: none;
}

.input-1mgnkM,
.input-UJ9Tr3 {
  padding-left: 12px;
  padding-right: 12px;
  border-radius: 20px;
}

/* SERVER LIST -> CREATE/JOIN SERVER -> CREATE */
.avatarUploaderInner-yEhTv5 {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  border: none;
  box-shadow: var(--popout-shadow);
}
.avatarUploaderInner-yEhTv5 > * {
  color: var(--app-accent-text);
}

/* SERVER LIST -> CREATE/JOIN SERVER -> CREATE -> SERVER REGION */
.regionSelectModal-12e-57 {
  background-color: transparent !important;
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border-color: transparent;
  transition: var(--transition-time) var(--transition-type);
}
.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover {
  background-color: var(--card-color-hover);
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

/*
 *
 *	CHANNELS LIST
 *
 */
.platform-win .sidebar-1tnWFu {
  border-radius: 0;
}

.sidebar-1tnWFu {
  background-color: var(--sidebar-color);
}

.container-1NXEtd,
.container-PNkimc {
  background-color: transparent;
}

.animatedContainer-1pJv5C {
  box-shadow: var(--popout-header-shadow);
}

.content-1gYQeQ {
  border-radius: var(--card-radius);
}

.container-36u7Lw,
.name-3_Dsmg {
  color: var(--channels-default);
}

.containerDragAfter-1F4fgZ:after,
.containerDragBefore-31UGCO:before {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
}

.unread-3zKkbm {
  width: 6px;
  height: 6px;
  background-color: var(--notification-color);
  border-radius: 3px;
}

/* CHANNELS LIST -> PERMISSIONS */
.settingCard-xZSDjS, .settingCard-xZSDjS.active-3EK-ed {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}
.settingCard-xZSDjS .cardContent-1-5hym, .settingCard-xZSDjS.active-3EK-ed .cardContent-1-5hym {
  border-radius: var(--card-radius) var(--card-radius) 0 0;
  box-shadow: var(--popout-header-shadow);
}

.cardFolder-3H4uH4 {
  background-color: transparent;
}

/*
 *
 *	STATUS PICKER
 *
 */
.menu-1QACrS {
  background-color: transparent;
  border-radius: var(--popout-radius);
  overflow: hidden;
}
.menu-1QACrS:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

.panels-3wFtMD {
  background-color: transparent;
}

.container-6sXIoE .interpret-F93iqP {
  color: var(--text-normal);
}

/*
 *
 *	VOICE CONNECTED
 *
 */
.content-1Tgc42 {
  border-radius: var(--button-radius);
}

[class*=theme-] .container-1ILvLB .header-2C89wJ,
[class*=theme-] .container-1ILvLB section {
  background-color: transparent;
}

.container-1ILvLB .header-2C89wJ {
  box-shadow: var(--popout-header-shadow);
}

.avatarSpeaking-2pCGrZ,
.border-2Vy6FN.speaking-7QZEkv,
.border-2BJQjd.speaking-3RWJBr {
  box-shadow: inset 0 0 0 2px rgba(var(--app-accent-rgb), var(--app-accent-opacity)), inset 0 0 3px 3px rgba(0, 0, 0, 0.35);
}

.tile-2TcwiO {
  background-color: var(--card-color);
}

.button-3Vyz67:before {
  border-radius: 100px;
}

.container-1ILvLB {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}
.container-1ILvLB section p {
  color: var(--text-normal) !important;
}
.container-1ILvLB section strong {
  color: var(--text-primary) !important;
}

/* VOICE CONNECTED -> STREAMING PREVIEW */
.streamPreview-3qoMP4 {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}

.previewContainer-21fFBz {
  background-color: transparent !important;
}
.previewContainer-21fFBz .image-1YnNzZ {
  border-radius: 0;
}

.liveSmall-1Urjcy {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  color: var(--app-accent-text);
}

/* VOICE CONNECTED -> ACTIVITY HOVER */
.container-8Futzw {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}
.container-8Futzw:before {
  position: fixed;
  width: calc(100% - 16px);
  height: 100%;
  margin-left: 16px;
}

/*
 *
 *	STREAMING
 *
 */
.scroller-2TWLdF {
  background-color: transparent;
}

[class*=theme-] .memberListItem-3V-x8Q:not(.popoutDisabled-PP2QdB):hover {
  background-color: var(--background-modifier-hover);
}

.participantsButton-1WBdFP {
  position: absolute;
}
.participantsButton-1WBdFP, .participantsButton-1WBdFP:hover {
  background-color: transparent;
}

/*
 *
 *	CHAT AREA
 *
 */
.chat-2ZfjoI,
.noChannel-Z1DQK7 {
  background-color: var(--main-content-color);
}

.chat-2ZfjoI.threadSidebarOpen-1LSXvU {
  border-radius: 0 var(--app-radius) var(--app-radius) 0;
}

.iconWrapper-3plkqh {
  background-color: var(--background-modifier-selected);
}

.messages-3amgkR,
.wrapper-22ayhK,
.wrapper-15CKyy {
  background-color: transparent;
}

.button-1kija8 {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.attachment-16cAbS,
.avatar-l9Txm5,
.blob-1uHjdp {
  background-color: #000;
}

.content-1jQy2l:before {
  display: none;
}

.newMessagesBar-1hF-9G,
.jumpToPresentBar-1cEnH0 {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
}

.newMessagesBar-1hF-9G {
  border-radius: 0 0 var(--messages-radius) var(--messages-radius);
}

.jumpToPresentBar-1cEnH0 {
  padding-bottom: 0;
  border-radius: var(--messages-radius);
}
.jumpToPresentBar-1cEnH0 .spinner-3xAPm0 {
  --spinner-size: auto;
}
.jumpToPresentBar-1cEnH0 .spinnerItem-_2a-1N {
  background-color: var(--app-accent-text);
}

.barButtonBase-Sk2mdB {
  color: var(--app-accent-text);
}

.emptyChannelIcon-1YdEz2 {
  background-color: var(--card-color);
}

.role-23oyrw {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.role-23oyrw:hover {
  background-color: var(--card-color-hover);
}

/* CHAT AREA -> MESSAGES */
.message-2CShn3:not(.groupStart-3Mlgv1),
.message-2CShn3.compact-2Nkcau {
  margin-top: 2px;
}

.wrapper-30-Nkg {
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
}
.wrapper-30-Nkg.groupStart-3Mlgv1 .avatar-2e8lTP {
  width: 40px;
  height: 40px;
  top: 0;
  left: -50px;
  margin-top: 0;
}
.wrapper-30-Nkg.cozy-VmLDNB, .wrapper-30-Nkg.compact-2Nkcau {
  margin-left: 76px;
  margin-right: 24px;
  padding: var(--messages-padding);
  padding-right: 8px !important;
  border: 2px solid transparent;
}
.wrapper-30-Nkg.cozy-VmLDNB .timestamp-p1Df1m, .wrapper-30-Nkg.cozy-VmLDNB .timestamp-p1Df1m.alt-1dvXnH, .wrapper-30-Nkg.compact-2Nkcau .timestamp-p1Df1m, .wrapper-30-Nkg.compact-2Nkcau .timestamp-p1Df1m.alt-1dvXnH {
  color: var(--text-normal);
}
.wrapper-30-Nkg.cozy-VmLDNB .timestamp-p1Df1m.alt-1dvXnH {
  left: -70px;
}
.wrapper-30-Nkg.compact-2Nkcau {
  padding: 4px;
  padding-left: 6px;
}
.wrapper-30-Nkg.compact-2Nkcau .timestamp-p1Df1m {
  margin-right: 0.75rem;
}
.wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .contents-2MsGLg:before {
  display: none;
}
.wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .iconContainer-2rPbqG {
  left: -16px;
}
.wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .content-vSHmMD {
  margin-left: 44px;
}
.wrapper-30-Nkg.compact-2Nkcau.hasThread-3h-KJV .spine-2vt3pM {
  display: none;
}
.wrapper-30-Nkg.hasThread-3h-KJV:after {
  display: none;
}
.wrapper-30-Nkg.hasThread-3h-KJV .messageContent-2t3eCI {
  overflow: visible;
}
.wrapper-30-Nkg.hasThread-3h-KJV .container-x059i8 {
  padding: 0;
}
.wrapper-30-Nkg.hasThread-3h-KJV .iconContainer-2rPbqG {
  position: absolute;
  width: 40px !important;
  height: 40px;
  top: -8px;
  left: -62px;
  margin-right: 0;
  padding-top: 0;
  background-color: var(--messages-color);
  border-radius: 50%;
}
.wrapper-30-Nkg.hasThread-3h-KJV .container-3i3IzO {
  padding: 12px;
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
}
.wrapper-30-Nkg.hasThread-3h-KJV .cta-1XhfrG {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.backgroundFlash-1X5jVs {
  background-color: transparent !important;
}

.mouse-mode.full-motion .backgroundFlash-1X5jVs[style*="background-color: rgba(114, 137, 218, 0.2)"] .mentioned-Tre-dv:hover,
.mouse-mode.full-motion .backgroundFlash-1X5jVs[style*="background-color: rgba(114, 137, 218, 0.2)"] .message-2CShn3.mentioned-Tre-dv:hover {
  background-color: var(--messages-color);
  border-color: rgb(var(--mention-rgb));
  box-shadow: inset 0px 0px 10px 3px rgb(var(--mention-rgb)), 0px 0px 13px 4px rgb(var(--mention-rgb));
}

[class*=theme-] .message-G6O-Wv {
  background-color: transparent;
  box-shadow: none;
}

.header-1zd7se + .content-2hZxGK .cozyMessage-1DWF9U.groupStart-3Mlgv1 {
  margin-top: 16px;
}

.message-G6O-Wv .cozy-VmLDNB.wrapper-30-Nkg {
  margin-left: 52px;
  margin-right: 0;
}

.group-spacing-0 .wrapper-30-Nkg + .wrapper-30-Nkg:not(.message-2CShn3) {
  --margin-spacing: 0.0625rem;
}

.group-spacing-4 .wrapper-30-Nkg + .wrapper-30-Nkg:not(.message-2CShn3) {
  --margin-spacing: 0.3125rem;
}

.group-spacing-8 .wrapper-30-Nkg + .wrapper-30-Nkg:not(.message-2CShn3) {
  --margin-spacing: 0.5625rem;
}

.group-spacing-16 .wrapper-30-Nkg + .wrapper-30-Nkg:not(.message-2CShn3) {
  --margin-spacing: 1.0625rem;
}

.group-spacing-24 .wrapper-30-Nkg + .wrapper-30-Nkg:not(.message-2CShn3) {
  --margin-spacing: 1.5625rem;
}

.wrapper-30-Nkg.message-2CShn3 + .wrapper-30-Nkg:not(.message-2CShn3) {
  margin-top: var(--margin-spacing);
}

.message-2CShn3.selected-2LX7Jy,
.mouse-mode.full-motion .message-2CShn3:hover {
  background-color: var(--messages-color);
}

.mentioned-Tre-dv,
.message-2CShn3.mentioned-Tre-dv.selected-2LX7Jy,
.mouse-mode.full-motion .mentioned-Tre-dv:hover,
.mouse-mode.full-motion .message-2CShn3.mentioned-Tre-dv:hover {
  background-color: var(--messages-color);
  border-color: rgb(var(--mention-rgb)) !important;
  box-shadow: inset 0px 0px 6px 1px rgb(var(--mention-rgb)), 0px 0px 9px 2px rgb(var(--mention-rgb));
}

.localBot-GrCgVt:before,
.mentioned-Tre-dv:before {
  display: none;
}

[class*=theme-] .wrapper-1ZcZW- {
  background-color: rgba(var(--mention-rgb), 0.175);
  color: rgb(var(--mention-rgb));
}
[class*=theme-] .wrapper-1ZcZW-:hover {
  background-color: rgb(var(--mention-rgb));
  color: var(--mention-hover-color);
}

.wrapper-2vIMkT {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}

.interactive {
  transition: var(--transition-time) var(--transition-type);
}

.interactive:hover {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.isUnread-3Lojb- {
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.unreadPill-3nEWYM {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.unreadPillCap-2-iI4h {
  filter: none !important;
}

.unreadPillCapStroke-1nE1Q8 {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.content-3spvdd {
  position: relative;
  padding: 2px 6px;
  background-color: transparent;
  color: var(--text-normal);
}
.content-3spvdd:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: 9px;
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

.hasMore-3e72_v {
  margin: 28px 24px 16px 24px;
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  box-shadow: none;
  color: var(--text-normal);
  font-size: 14px;
  text-transform: lowercase;
  transition: var(--transition-time) var(--transition-type);
}
.hasMore-3e72_v:first-letter {
  text-transform: capitalize;
}
.hasMore-3e72_v:hover {
  background-color: var(--card-color-hover);
}

/* CHAT AREA -> MESSAGES -> SCALED FONT */
.a11y-font-scaled-down[style*="font-size: 75%"] {
  --text-indent: 62px;
}
.a11y-font-scaled-down[style*="font-size: 87.5%"] {
  --text-indent: 70px;
}
.a11y-font-scaled-down[style*="font-size: 93.75%"] {
  --text-indent: 74px;
}
.a11y-font-scaled-down[style*="font-size: 112.5%"] {
  --text-indent: 89px;
}
.a11y-font-scaled-down[style*="font-size: 125%"] {
  --text-indent: 99px;
}
.a11y-font-scaled-down[style*="font-size: 150%"] {
  --text-indent: 115px;
}
.a11y-font-scaled-down .cozy-VmLDNB.wrapper-30-Nkg,
.a11y-font-scaled-down .compact-2Nkcau.wrapper-30-Nkg {
  margin-left: var(--text-indent);
  margin-right: 24px;
  padding: 8px;
  padding-right: 8px;
}

/* CHAT AREA -> MESSAGES -> SPOILERS */
.spoilerText-27bIiA.hidden-3B-Rum {
  background-color: var(--messages-color) !important;
}

/* CHAT AREA -> MESSAGES -> ACTIONS */
.button-3bklZh:first-child {
  border-radius: var(--popout-radius) 0 0 var(--popout-radius);
}
.button-3bklZh:last-child {
  border-radius: 0 var(--popout-radius) var(--popout-radius) 0;
}
.button-3bklZh:only-child {
  border-radius: var(--popout-radius);
}

/* CHAT AREA -> MESSAGES -> EMBEDDED */
.embedFull-1HGV2S,
[class*=theme-] .invite-3uuHYQ,
[class*=theme-] .wrapperAudio-1Bzv_Z,
.wrapper-1HIH0j,
.attachment-1PZZB2,
[class*=theme-] .tile-2mmK5T,
[class*=theme-] .tile-2mmK5T:hover {
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
}

.invite-3uuHYQ,
.wrapperAudio-1Bzv_Z,
.attachment-1PZZB2 {
  border: none;
}

.markup-eYLPri a {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  /*filter: saturate(var(--saturation-factor));*/
}
.markup-eYLPri pre {
  border-radius: var(--messages-radius);
}
.markup-eYLPri code {
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
  border: none;
}

.textContainer-36wgKK {
  background-color: var(--card-color);
  border-radius: var(--messages-radius) var(--messages-radius) 0 0;
  border: none;
}

.footer-GXWBBp {
  background-color: var(--card-color);
  border-radius: 0 0 var(--messages-radius) var(--messages-radius);
  border: none;
  border-top: 1px solid var(--card-color);
}

.low-saturation .anchor-1MIwyf {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  /*filter: saturate(var(--saturation-factor));*/
}

/* CHAT AREA -> MESSAGES -> EDIT MESSAGE */
.channelTextArea-220_Gz {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: var(--textarea-radius);
}

/* CHAT AREA -> MESSAGES -> REACTIONS */
.size-2kUz0R {
  max-height: 350px;
}

[class*=theme-] .scroller-2GkvCq {
  background-color: var(--sidebar-color);
}

[class*=theme-] .container-KM8BU6,
[class*=theme-] .reactors-1VXca7 {
  background-color: transparent;
}

.reaction-2A2y9y {
  background-color: var(--messages-color);
  border-radius: var(--messages-radius);
  border: none;
}
.reaction-2A2y9y:hover {
  background-color: var(--messages-color);
}
.reaction-2A2y9y.reactionMe-3I9gFK {
  background-color: rgba(var(--app-accent-rgb), 0.3);
  border-color: transparent;
}
.reaction-2A2y9y.reactionMe-3I9gFK:hover {
  background-color: rgba(var(--app-accent-rgb), 0.4);
}
.reaction-2A2y9y.reactionMe-3I9gFK .reactionCount-1zkLcN {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

/* CHAT AREA -> MESSAGES -> EMOJI INFO */
.emojiSection-3QtaWO {
  background-color: rgba(0, 0, 0, var(--popout-header-opacity));
  box-shadow: var(--popout-header-shadow);
}
.emojiSection-3QtaWO:only-child {
  background-color: transparent;
  box-shadow: none;
}

.guildSection-2Zyzy8 {
  background-color: transparent;
}

/* CHAT AREA -> TEXTAREA */
.form-3gdLxP {
  margin-top: 0;
}
.form-3gdLxP:before {
  display: none;
}

.channelTextArea-1FufC0,
.wrapper-2SplAX {
  --textarea-alpha: 0.1;
  min-height: 44px;
  margin: 12px 0 12px 0;
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: var(--textarea-radius);
}

.container-9gOVw0 {
  background-color: transparent;
  border-radius: var(--textarea-radius) var(--textarea-radius) 0 0;
  border-bottom: 1px solid rgba(255, 255, 255, 0.15);
}

.wrapper-2SplAX {
  padding: 0;
}

.buttonContainer-KMz3Ex {
  margin-right: 16px;
}

.scrollableContainer-15eg7h {
  background-color: transparent;
}
.scrollableContainer-15eg7h + .autocomplete-3NRXG8 {
  position: absolute;
  border-radius: var(--popout-radius) !important;
}

.typing-2J1mQU {
  width: calc(100% - 32px);
  height: 24px;
  top: -12px;
  left: unset;
  right: unset;
  margin-right: 0 !important;
}
.typing-2J1mQU .cooldownWrapper-2k1jHK {
  color: var(--text-normal) !important;
}

.fakeLink-2FvUR7 {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

/* CHAT AREA -> TEXTAREA -> MENTION AUTOCOMPLETE */
.autocomplete-3l_oCd,
.autocomplete-3NRXG8 {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}

.selectorSelected-1_M1WV {
  background-color: var(--background-modifier-hover) !important;
}

.wrapper-3z7DuG {
  background-color: transparent;
}

.base-2v-uc0 {
  border-radius: var(--popout-radius);
}
.base-2v-uc0.selected-3H3-RC {
  background-color: var(--background-modifier-hover) !important;
}

.bar-AokMp3 {
  background-color: transparent;
}

/* CHAT AREA -> TEXTAREA -> FORMAT TOOLBAR */
.toolbar-37BrJ5 {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
  overflow: hidden;
}
.toolbar-37BrJ5:after {
  border-radius: 16px;
}
.toolbar-37BrJ5 .button-lA2rvH {
  --button-radius: 0;
  background-color: transparent !important;
}
.toolbar-37BrJ5 .button-lA2rvH:before {
  --button-action-color: #fff;
}

[class*=theme-] .container-Qj4uIL {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
}

.containerBackground-3PNziK {
  background-color: transparent;
  border: none;
}
.containerBackground-3PNziK:after {
  border-top-color: var(--popout-color);
}

.maskBackground-1WpXoP {
  background-color: var(--background-modifier-hover);
}

/* CHAT AREA -> TEXTAREA -> INLINE REPLIES */
.attachedBars-2BCP3l {
  background-color: transparent;
}
.attachedBars-2BCP3l .colorLink-2apWfY {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.clipContainer-31nYlH {
  margin-top: 0;
  padding-top: 0;
}
.clipContainer-31nYlH .container-A2jo65 {
  background-color: transparent;
  border-radius: var(--textarea-radius) var(--textarea-radius) 0 0;
  border-bottom: 1px solid var(--background-modifier-accent);
}
.clipContainer-31nYlH .replyBar-1oi75v {
  background-color: transparent;
}
.clipContainer-31nYlH .threadSuggestionBar-3ExSyc {
  background-color: transparent;
  box-shadow: none;
}

.container-A2jo65 {
  background-color: transparent;
  border-radius: var(--textarea-radius) var(--textarea-radius) 0 0;
  border-bottom: 1px solid var(--background-modifier-accent);
}

.repliedMessage-3Z6XBG:before {
  transform: translateX(42px);
}

.replyAvatar-sHd2sU,
.executedCommandAvatar-3oOnb1,
.repliedMessage-3Z6XBG > .replyBadge-LMm_Ic {
  margin-left: 42px;
}

.compact-2Nkcau .repliedMessage-3Z6XBG > .replyBadge-LMm_Ic {
  margin-left: 0;
}

.ephemeral-2nDdnn,
.replying-eZ7p5z,
.backgroundFlash-1X5jVs[style*="background-color: rgba(114, 137, 218, 0.2)"] .wrapper-30-Nkg {
  border-color: rgba(var(--mention-alt), var(--mention-alpha)) !important;
  box-shadow: inset 0px 0px 6px 1px rgba(var(--mention-alt), var(--mention-alpha)), 0px 0px 9px 2px rgba(var(--mention-alt), var(--mention-alpha));
}
.ephemeral-2nDdnn:before,
.replying-eZ7p5z:before,
.backgroundFlash-1X5jVs[style*="background-color: rgba(114, 137, 218, 0.2)"] .wrapper-30-Nkg:before {
  display: none;
}

.ephemeralMessage-11q8XZ a {
  color: rgba(var(--mention-alt), var(--mention-alpha));
}

/* CHAT AREA -> TEXTAREA -> INLINE REPLIES -> COMPACT */
.repliedMessage-3Z6XBG:before {
  border-color: var(--text-normal);
  opacity: 0.5;
}

.compact-2Nkcau .repliedMessage-3Z6XBG {
  margin-left: calc(var(--timestamp-width) + 3.1rem + var(--text-indent));
}
.compact-2Nkcau .repliedMessage-3Z6XBG:before {
  transform: none;
}

/* CHAT AREA -> SPAM FILTER */
.spamBanner-1auiob {
  margin: 12px 16px;
  padding: 4px 12px;
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 28px;
}
.spamBanner-1auiob .bannerTextContainer-TbC9W4 {
  margin: 0 8px 0 0;
}
.spamBanner-1auiob .actionButtons-2SAg-Q {
  margin: 0;
}

/*
 *
 *	THREADS
 *
 */
.threadSidebar-1o3BTy {
  background-color: var(--main-content-color);
  border-radius: var(--app-radius);
}
.threadSidebar-1o3BTy .chatHeaderBar-2fUORh {
  background-color: transparent;
}
.threadSidebar-1o3BTy .chat-3JZdy8:before {
  display: none;
}

.browser-mnQ1T7 .header-3_zmOb {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}
.browser-mnQ1T7 .container-2rzKKA {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.browser-mnQ1T7 .container-2rzKKA:hover {
  background-color: var(--card-color-hover);
  border: none;
}

.browser-mnQ1T7 {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}

.container-18GwIk .header-3_zmOb {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}
.container-18GwIk .list-1uSVgu {
  padding-bottom: 16px;
}
.container-18GwIk .container-2rzKKA {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.container-18GwIk .container-2rzKKA:hover {
  background-color: var(--card-color-hover);
  border: none;
}
.container-18GwIk .container-2rzKKA:last-of-type {
  margin-bottom: 0;
}

/* THREADS -> SPLIT VIEW */
.container-3XgAHv {
  background-color: var(--main-content-color);
  border-radius: var(--app-radius);
}

.chat-1-OBC7:before,
.chat-1rZYgu:before {
  display: none;
}

.channelTextArea-3TZH74 {
  --textarea-alpha: 0.1;
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: var(--textarea-radius);
}
.channelTextArea-3TZH74 .channelTextAreaInner-ITp5kW {
  border-radius: inherit;
  border: none;
}

/*
 *
 *	EMOJI PICKER
 *
 */
.contentWrapper-3vHNP2,
.emojiPicker-6YCk8a {
  background-color: transparent;
}

.drawerSizingWrapper-1txdWG {
  background-color: transparent !important;
  border-radius: var(--popout-radius);
  overflow: hidden;
}
.drawerSizingWrapper-1txdWG:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

.translate-PeW1wK .wrapper-3u51GQ {
  background-color: transparent !important;
  border-radius: var(--popout-radius);
  overflow: hidden;
}
.translate-PeW1wK .wrapper-3u51GQ:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  pointer-events: none;
  z-index: -1;
}

.contentWrapper-3vHNP2 .wrapper-3u51GQ:before {
  display: none;
}

.categoryList-2qRrlj .scroller-2MALzE::-webkit-scrollbar {
  width: 0 !important;
}

.header-11eigE,
[class*=theme-] .header-JHwfVI,
.header-uVCAlo {
  box-shadow: var(--popout-header-shadow);
}

.navButton-1XuvI-:hover {
  background-color: var(--background-modifier-hover);
}
.navButton-1XuvI-.navButtonActive-1EqC5l {
  background-color: var(--background-modifier-selected);
}

.container-1SX9VC,
.container-2oNtJn {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 17px;
}
.container-1SX9VC input,
.container-2oNtJn input {
  background-color: transparent !important;
}

.searchBar-3OIGe3 {
  border: none;
}

.wrapper-22rqw6 {
  background-color: var(--sidebar-color);
}

.wrapper-1NNaWG {
  position: relative;
  overflow: hidden;
}

[class*=theme-] .wrapper-1NNaWG {
  background-color: transparent;
}

.emojiItem-277VFM.emojiItemSelected-2Lg50V {
  background-color: var(--background-modifier-hover);
}

.inspector-DFKXwB,
.unicodeShortcut-3N8oDe,
.stickerCategoryShopWrapper-3EnJdQ {
  background-color: transparent;
}

.unicodeShortcut-3N8oDe:before {
  position: absolute;
  content: " ";
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background-color: var(--sidebar-color);
  backdrop-filter: blur(var(--popout-blur));
  opacity: 1;
  pointer-events: none;
}

.diversitySelectorOptions-3DhNYs {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  border: none;
  overflow: hidden;
}

/* EMOJI PICKER -> GIFS */
.result-3OpoO7 {
  border-radius: var(--card-radius);
}
.result-3OpoO7:after {
  border-radius: inherit;
}
.result-3OpoO7:hover:after {
  box-shadow: inset 0 0 0 2px rgba(var(--app-accent-rgb), var(--app-accent-opacity)), inset 0 0 0 3px #2f3136 !important;
}
.result-3OpoO7:hover .categoryFadeBlurple-1HuV1x {
  background-color: rgba(var(--app-accent-rgb), 0.9);
}
.result-3OpoO7 .categoryFade-2EGqIh,
.result-3OpoO7 .categoryFadeBlurple-1HuV1x,
.result-3OpoO7 .gif-1EWTs- {
  border-radius: inherit;
}
.result-3OpoO7 .categoryFadeBlurple-1HuV1x {
  background-color: rgba(var(--app-accent-rgb), 0.7);
}
.result-3OpoO7 .categoryFadeBlurple-1HuV1x + .categoryText-2i9GtE {
  color: var(--app-accent-text);
}

.emptyHintCard-3Btf0V {
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius) !important;
  border: none !important;
}

/* EMOJI PICKER -> STICKERS */
.row-2mBMW2 {
  column-gap: 6px !important;
}

/*
 *
 *	MEMBERS LIST
 *
 */
.members-3WRCEx,
.members-3WRCEx > div {
  background-color: transparent;
}

.botTagRegular-kpctgU,
.botTagInvert-1nKcq_ {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.layout-1qmrhw {
  border-radius: var(--button-radius);
}

/* MEMBERS LIST -> CHANNEL BANNER */
.bannerPlaceholder-edbQI2 {
  width: calc(100% - 12px);
  margin: 12px 0 0;
  border-radius: var(--card-radius);
}

.contentWrapper-3wXY8L {
  padding: 16px 12px 0 0;
  background-color: transparent;
}
.contentWrapper-3wXY8L .contentWrapperInner-17OxmC {
  padding: 12px;
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

.tabs-1RhQha {
  padding: 16px 0;
}

.tabs-1RhQha,
.container-2o3qEW,
.container-NkLXgf,
.container-2Oqvgx {
  background-color: transparent;
}

.container-NkLXgf {
  overflow-y: auto;
}

/*
 *
 *	SEARCH RESULTS
 *
 */
.searchResultsWrap-5RVOkx {
  background-color: var(--sidebar-color);
}

/* SEARCH RESULTS -> HEADER */
.searchHeader-1r_ZSh {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

.channelName-3w2Y3c {
  background-color: transparent;
}

/* SEARCH RESULTS -> HEADER -> TABS */
[class*=theme-] .tab-2j5AEF {
  border-radius: var(--card-radius);
}
[class*=theme-] .tab-2j5AEF.selected-2LAck8 {
  background-color: var(--background-modifier-selected);
}

/* SEARCH RESULTS -> MESSAGES */
.searchResult-O9NDji:before, .searchResult-O9NDji:after {
  display: none;
}
.searchResult-O9NDji .cozy-VmLDNB.wrapper-30-Nkg,
.searchResult-O9NDji .compact-2Nkcau.wrapper-30-Nkg {
  margin-left: 50px;
  margin-right: 0;
}

.searchResultMessage-1fxgXh.hit-1fVM9e {
  background-color: transparent;
  border: none;
  box-shadow: none;
  overflow: visible;
}
.searchResultMessage-1fxgXh.before-2RL1Gz, .searchResultMessage-1fxgXh.after-20SH8W {
  margin-top: 0;
  border: none;
}
.searchResultMessage-1fxgXh.sibling-1eJVjd {
  opacity: 0.35;
}

/* SEARCH RESULTS -> MESSAGES -> EXPANDED */
.searchResult-O9NDji.expanded-w_LCGl,
.expanded-w_LCGl .searchResultMessage-1fxgXh.hit-1fVM9e {
  background-color: transparent;
  border: none;
}

.searchResultMessage-1fxgXh {
  margin-bottom: 8px !important;
}

.expanded-w_LCGl .searchResultMessage-1fxgXh.hit-1fVM9e {
  margin-left: 0;
  margin-right: 0;
}

/* SEARCH RESULTS -> PAGINATION */
.activeButton-LRWFC_ {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  color: var(--app-accent-text) !important;
}

/*
 *
 *	SERVER BOOST
 *
 */
.root-2zfUH6 {
  margin: calc(var(--app-margin) / 2 + 24px) var(--app-margin) var(--app-margin) var(--app-margin);
}

.wrapper-WLdlSO {
  background-color: var(--main-content-color);
}

.navigationBar-2Z_P4D {
  background-color: transparent !important;
  box-shadow: var(--popout-header-shadow);
}

.planCard-vET3Ia {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

.perksTable-H9sPBm {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.perksTable-H9sPBm .perksTableRow-31boQO.perksTableRowBody-3Ppvgz:hover {
  background-color: var(--card-color);
}
.perksTable-H9sPBm .perksTableRowLabelCopy-1tRwM4 {
  font-size: 16px;
}

.perkPopout-18_jX- {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}

[class*=theme-] .perksModal-fSYqOq {
  background-image: none;
  background-color: var(--main-content-color);
}

.tier-12tKuZ {
  border-radius: var(--card-radius);
}

[class*=theme-] .tierHeaderLocked-1s2JJz,
[class*=theme-] .tierHeaderUnlocked-1n-OTI,
[class*=theme-] .tierBody-16Chc9,
[class*=theme-] .tierHeaderUnlocked-1n-OTI {
  background-color: var(--card-color);
  background-image: none;
}

.tierHeader---JJFb {
  border-radius: var(--card-radius) var(--card-radius) 0 0;
  box-shadow: var(--popout-header-shadow);
}

[class*=theme-] .tierUnlocked-25K6Kv {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  color: var(--app-accent-text);
}

.tierBody-16Chc9 {
  border-radius: 0 0 var(--card-radius) var(--card-radius);
}

.subscription-3aLGnG {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

/*
 *
 *	USER SETTINGS
 *
 */
.layer-86YKbF,
.standardSidebarView-E9Pc3j {
  background-color: transparent;
}

.sidebarRegionScroller-FXiQOh {
  background-color: var(--sidebar-color);
}

.contentRegion-3HkfJJ {
  background-color: var(--main-content-color);
}

.contentRegionScroller-2_GT_N {
  background-color: transparent;
}

.side-2ur1Qk .item-3XjbnG,
#bd-settings-sidebar .ui-tab-bar-item {
  border-radius: var(--button-radius);
}

/* USER SETTINGS -> MY ACCOUNT */
.accountProfileCard-lbN7n- {
  background-color: var(--card-color);
}
.accountProfileCard-lbN7n- .background-3d_SjE {
  background-color: var(--card-color);
}
.accountProfileCard-lbN7n- .fieldList-in8WkP {
  background-color: transparent;
}

.avatar-3mTjvZ {
  background-color: transparent;
  border: none;
  box-shadow: var(--popout-shadow);
}
.avatar-3mTjvZ svg {
  filter: none;
}

[class*=theme-] .userSettingsAccount-2eMFVR .viewBody-2Qz-jg {
  color: var(--text-normal);
}

.avatarUploaderInner-yEhTv5 .avatarUploaderHint-2ZdBlc {
  color: var(--text-normal);
}

.userInfoEditing-1CEzdT .multiInput-1e2xJ7 .multiInputLast-1aQ3YA,
.multiInputFirst-3-OxIz + .multiInputLast-35zVz0 {
  margin: 0 8px;
}

.userInfoEditing-1CEzdT .multiInputLast-1aQ3YA:before,
.multiInputLast-35zVz0:before {
  display: none;
}

.questionMark-CWEQZn,
.questionMark-3V9mGJ {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  border-radius: 50%;
}
.questionMark-CWEQZn .icon-3JHfo7,
.questionMark-3V9mGJ .icon-3JHfo7 {
  color: var(--app-accent-text);
}

.phoneField-3NAPDv {
  padding: 2px 8px;
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 22px;
  border: none;
}
.phoneField-3NAPDv .countryButton-1cNDvB {
  border-radius: var(--button-radius);
}
.phoneField-3NAPDv .plusSign-1BkjXr,
.phoneField-3NAPDv .countryCode-2RFA3i {
  color: var(--app-accent-text);
}
.phoneField-3NAPDv .phoneFieldExpand-1CqrEb {
  stroke: var(--app-accent-text);
}
.phoneField-3NAPDv input {
  background-color: transparent !important;
}

/* USER SETTINGS -> USER PROFILE */
.notice-1Qe0b_ {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

.swatch-3mFIiP {
  border-radius: var(--card-radius);
}

.aboutMeTextarea-2DKNIM {
  height: unset;
}

.profileBannerPreview-3mLIdO {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}
.profileBannerPreview-3mLIdO .divider-1wtgZ3 {
  display: none;
}
.profileBannerPreview-3mLIdO .popoutInfo-16MuYF {
  padding: 16px;
}
.profileBannerPreview-3mLIdO .fakeActivityWrapper-2i1oU- {
  padding: 0 16px 0;
}

.bioTextArea-dDGOeC {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: var(--textarea-radius);
  border: none;
}

/* USER SETTINGS -> AUTHORIZED APPS */
.authedApp-8q3NA9 {
  margin-bottom: 16px;
  padding: 0;
}
.authedApp-8q3NA9 .marginBottom20-315RVT {
  padding: 16px;
  border-radius: var(--card-radius) var(--card-radius) 0 0;
  box-shadow: var(--popout-header-shadow);
}
.authedApp-8q3NA9 .marginBottom20-315RVT + div:not([class]) {
  padding: 0 16px;
}
.authedApp-8q3NA9 .marginTop20-2T8ZJx {
  padding: 0 16px 16px;
}

/* USER SETTINGS -> CONNECTIONS */
.accountList-Wii_T5 {
  padding: 16px 16px 8px;
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.accountBtn-3pgcgr .accountBtnInner-3ttD-i {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  transition: var(--transition-time) var(--transition-type);
}
.accountBtn-3pgcgr .accountBtnInner-3ttD-i:hover {
  background-color: var(--card-color-hover);
}

.connectionList-1NoxUk {
  grid-gap: 16px;
}

.connection-YOVI9j {
  margin-bottom: 0;
}

.connectionHeader-Ixbb1s {
  padding: 16px;
  background-color: transparent;
  border-bottom: none;
  box-shadow: var(--popout-header-shadow);
}

.connectionDelete-3YgMVq span {
  font-size: 0;
}

.connectionOptionsWrapper-3aVWcp {
  padding: 16px 8px 0;
}

.connectionOptionSwitch-y1S-cR {
  margin-bottom: 16px;
  padding-left: 8px;
  padding-right: 8px;
}

/* USER SETTINGS -> BILLING */
.paymentSourceRow-1z8x7Z {
  margin: 0 0 16px 0;
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.paymentSourceRow-1z8x7Z,
.card-2aHs8C {
  padding: 16px;
}

.defaultMarginh2-t7G-2y + div + .divider-3LgWDL {
  display: none;
}

.codeRedemptionRedirect-3SBiCp {
  margin-top: 20px;
  padding: 16px;
}

/* USER SETTINGS -> DISCORD NITRO */
.gridItem-HzCfl4:before {
  opacity: 0.4;
}

/* USER SETTINGS -> SUBSCRIPTIONS */
.banner-3Kac2g {
  border-radius: var(--card-radius);
}

.detailsBlock-FoDTGA {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.lookFilled-1GseHa.select-1Ia3hD {
  min-height: var(--input-height);
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 23px;
  border: none;
  transition: var(--transition-time) var(--transition-type);
}
.lookFilled-1GseHa.select-1Ia3hD input {
  background-color: transparent !important;
}

.popout-1KHNAq {
  border: none;
  border-radius: var(--popout-radius);
  overflow: auto !important;
}

.option-2eIyOn:hover {
  background-color: var(--background-modifier-hover);
}
.option-2eIyOn[aria-selected=true] {
  background-color: var(--background-modifier-selected);
}

/* USER SETTINGS -> SERVER BOOST */
.feature-1Q4U_R {
  padding: 16px;
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.cardWrapper-CyvwQv {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.outer-2JOHae:hover {
  background-color: var(--card-color-hover);
}

.guild-Hq0WWA {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.guildHeader-3nh5RK,
.guildSubscriptionSlots-JPXXvN {
  background-color: transparent;
}

.guildHeader-3nh5RK {
  box-shadow: var(--popout-header-shadow);
}

.gemIndicatorProgressCircle-Wb8Ju8,
.gemWithLabel-9XSuaB {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

[class*=theme-] .gemIndicatorContainer-PqApbX {
  background-color: var(--card-color);
}

/* USER SETTINGS -> ACCESSIBILITY */
.previewMessage-2uxBrA .wrapper-30-Nkg {
  margin-left: 42px;
  margin-right: 0;
}

/* USER SETTINGS -> OVERLAY */
.wrapper-SdcMKg {
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.selected-18Wszc.option-1QI4c9,
.option-1QI4c9:hover {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  border-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.container-30qY7E .input-3MU9bJ {
  background-color: transparent !important;
}

.container-1_EVMa.recording-3ny5_E {
  border-color: rgba(var(--app-accent-rgb), 0.6) !important;
  box-shadow: 0 0 8px rgba(var(--app-accent-rgb), 0.5);
}

@keyframes shadowPulse-3-iHTS {
  0% {
    box-shadow: 0 0 8px rgba(var(--app-accent-rgb), 0.5);
  }
  50% {
    box-shadow: 0 0 12px rgba(var(--app-accent-rgb), 0.8);
  }
  to {
    box-shadow: 0 0 8px rgba(var(--app-accent-rgb), 0.5);
  }
}
/* USER SETTINGS -> KEYBINDS */
.keybindGroup-eTTYMW .container-30qY7E .input-3MU9bJ {
  background-color: transparent !important;
}

/* USER SETTINGS -> KEYBINDS -> DEFAULT KEYBINDS */
.keybindShortcut-3zF1P9 span {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

/* USER SETTINGS -> LANGUAGE */
.item-3eFBNF {
  border-radius: var(--card-radius);
}
.item-3eFBNF:hover {
  background-color: var(--card-color);
}
.item-3eFBNF.selected-2DeaDa {
  background-color: var(--card-color-hover);
}
.item-3eFBNF .checked-1pZh2h {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}
.item-3eFBNF .checked-1pZh2h path {
  fill: var(--app-accent-text) !important;
}

[class*=theme-] .item-3eFBNF {
  box-shadow: none;
}

/* USER SETTINGS -> ACTIVITY STATUS */
.notDetected-2HEmAp,
.nowPlaying-zBamm2 {
  border-radius: var(--card-radius);
}

.notDetected-2HEmAp,
.nowPlaying-zBamm2 {
  background-color: var(--card-color) !important;
}

.addGamePopout-3yePJc {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}

.gameNameInput-3TuPuA {
  margin-bottom: 4px;
  padding: 0 8px;
  line-height: 32px;
  border-radius: 16px;
}

.header-2o-2hj .background-3Da2vZ {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.row-2OVM4t .background-3Da2vZ {
  color: var(--app-accent-text);
}

.game-3x3aDt {
  box-shadow: 0 1px 0 0 var(--background-modifier-accent) !important;
}
.game-3x3aDt:last-of-type {
  box-shadow: none !important;
}
.game-3x3aDt .flowerStar-2tNFCR path {
  fill: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}
.game-3x3aDt .flowerStar-2tNFCR path + .childContainer-U_a6Yh path {
  fill: var(--app-accent-text);
}

[class*=theme-] .lastPlayed-3aHvxk {
  color: var(--text-normal);
}

/*
 *
 *	SERVER SETTINGS
 *
 */
.container-30qY7E {
  border-radius: 20px;
}

[class*=theme-] .container-30qY7E {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border: none;
}

.layout-RmPevB {
  padding: 0 12px 0 4px;
}

.container-20TyK0 {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}

/* SERVER SETTINGS -> ROLES */
.scroller-3_YDR2 {
  background-color: transparent;
}

.group-1_ptLP {
  background-color: var(--card-color);
  border-radius: 14px;
}

.container-3EtAkD {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.container-3EtAkD:hover {
  background-color: var(--card-color-hover);
  border: none;
}

.container-2O1UgZ {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
  border: none;
}

.titleContainer-3fPic2 {
  margin: 0 8px 0 16px;
}
.titleContainer-3fPic2.titleElevated-eN3exl {
  position: relative;
  padding: 67px 8px 24px;
  box-shadow: none;
}

/* SERVER SETTINGS -> ROLES -> EDIT */
.roleDot-2a4Pv7 {
  border: none;
}

.titleContainer-3fPic2.titleElevated-eN3exl, .titleContainer-3fPic2.stickyHeaderElevated-dNSSrJ,
.header-JUTO-g.titleElevated-eN3exl,
.header-JUTO-g.stickyHeaderElevated-dNSSrJ {
  overflow: hidden;
}
.titleContainer-3fPic2.titleElevated-eN3exl:before, .titleContainer-3fPic2.stickyHeaderElevated-dNSSrJ:before,
.header-JUTO-g.titleElevated-eN3exl:before,
.header-JUTO-g.stickyHeaderElevated-dNSSrJ:before {
  content: " ";
  position: absolute;
  width: calc(100% + var(--app-margin) * 2);
  height: calc(100% + var(--app-margin) * 2 + 24px);
  top: calc((var(--app-margin) + 24px) * -1);
  left: calc(var(--app-margin) * -1);
  background-image: var(--app-bg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
  box-shadow: inset 0 0 0 100vmax var(--main-content-color);
  filter: blur(var(--app-blur));
  z-index: -1;
  pointer-events: none;
}

.previewContainer-1xQAsw {
  border-radius: var(--card-radius);
  border: none;
}
.previewContainer-1xQAsw .theme-light {
  display: none;
}
.previewContainer-1xQAsw .messageContainer-3a6gLR {
  background-color: var(--main-content-color);
}

/* SERVER SETTINGS -> EMOJI */
.emojiRow-1aPaM- .input-2g-os5 {
  border-radius: 13px;
}

/* SERVER SETTINGS -> STICKERS */
.tier-3CS7-p {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

.tierHeaderLocked-30MLlO {
  background-color: transparent !important;
  box-shadow: var(--popout-header-shadow);
}

.tierBody-1d3UiS {
  background-color: transparent !important;
}

/* SERVER SETTINGS -> AUDIT LOG */
.auditLog-1NVAY0 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
  overflow: hidden;
}
.auditLog-1NVAY0 .header-2pgFQm,
.auditLog-1NVAY0 .changeDetails-1kMZqI {
  background-color: transparent;
}
.auditLog-1NVAY0 .headerExpanded-1-zwDr {
  box-shadow: var(--popout-header-shadow);
}
.auditLog-1NVAY0 .divider-M3saWq {
  display: none;
}

/* SERVER SETTINGS -> SERVER TEMPLATE */
.descriptionBox-SKGNgB {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

/* SERVER SETTINGS -> COMMUNITY OVERVIEW */
.upsellContainer-2a5eMP {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.upsellFooter-3M1V33 {
  background-color: transparent;
}

/* SERVER SETTINGS -> SERVER INSIGHTS */
.error-3AuLwi,
.developerPortalCtaWrapper-2PniQs {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

/* SERVER SETTINGS -> PARTNER PROGRAM */
.featureCard-3XHbjy,
.checklistContainer-12xGp5 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.checklistHeader-3liG7E {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

/* SERVER SETTINGS -> ENABLE DISCOVERY */
.card-3_CqkU {
  border-radius: var(--card-radius);
}

[class*=theme-] .card-3_CqkU,
[class*=theme-] .iconMask-30Tvqs {
  background-color: var(--card-color);
}

.container-2w0lh0 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.header-2Y0-A- {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

/* SERVER SETTINGS -> MEMBERSHIP SCREENING */
.enableContainer-1J91Aq,
.settingsFormItem-25zW3t,
.formFieldWrapper-2LV3S6 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.formFieldWrapper-2LV3S6 {
  border: none;
}

/* SERVER SETTINGS -> MEMBERSHIP SCREENING -> PREVIEW */
.guildSidebar-UHnQqs {
  background-color: var(--popout-color);
}

/* SERVER SETTINGS -> WELCOME SCREEN */
.enableContainer-2MEsKV,
.previewContainer-29oeA6,
.welcomeChannel-1rFrIO {
  background-color: var(--card-color);
}

.enableContainer-2MEsKV {
  border-radius: var(--card-radius) var(--card-radius) 0 0;
  box-shadow: var(--popout-header-shadow);
}

.previewContainer-29oeA6 {
  border-radius: 0 0 var(--card-radius) var(--card-radius);
}

.welcomeChannel-_Q4qAA {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

.descriptionWrapper-1GiGtP .inputDefault-3FGxgL {
  height: auto;
}

/* SERVER SETTINGS -> SERVER BOOST STATUS */
.side-2ur1Qk .item-3XjbnG[style="color: rgb(114, 137, 218);"] {
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}

.side-2ur1Qk .item-3XjbnG[style="color: rgb(114, 137, 218); background-color: rgba(114, 137, 218, 0.1);"] {
  background-color: rgba(var(--app-accent-rgb), 0.1) !important;
  color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
}

.side-2ur1Qk .item-3XjbnG[style*="background-color: rgb(114, 137, 218)"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  color: var(--app-accent-text) !important;
}

.tier-3H4BXk {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

[class*=theme-] .tierHeader-rlkkJd,
[class*=theme-] .tierBody-x9kBBp {
  background-color: transparent;
}

.tierHeader-rlkkJd {
  box-shadow: var(--popout-header-shadow);
}

[class*=theme-] .tierAccomplished-1I5NaT,
[class*=theme-] .tierCurrent-2nowYi,
[class*=theme-] .tierDefault-39L2SF {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
  box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.5);
}

[class*=theme-] .tierInProgress-1vFUnw {
  background-color: var(--card-color);
}

[class*=theme-] .background-3xJH_4 {
  color: var(--card-color);
}

/* SERVER SETTINGS -> MEMBERS */
.container-1S70rv {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
  backdrop-filter: blur(var(--popout-blur));
}

[class*=theme-] .autocompleteShadow-2nfsSy {
  box-shadow: none;
}

[class*=theme-] .autocompleteArrow-jJE9TQ {
  background-color: var(--popout-color);
}

[class*=theme-] .container-1S70rv .header-3i_Csh,
[class*=theme-] .container-1S70rv .sectionTag-28mLyE {
  background-color: transparent;
}

.container-1S70rv .input-2lpFVz {
  padding: 0 8px;
  border-radius: 11px;
}

[class*=theme-] .selectableItem-3-fmiM:hover {
  background-color: var(--background-modifier-hover);
}

[class*=theme-] .member-1q7VfX,
[class*=theme-] .inviteSettingsInviteRow-1rZeIM {
  box-shadow: 0 1px 0 0 rgba(255, 255, 255, 0.1);
}

[class*=theme-] .card-2ART2V:before {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}

[class*=theme-] .member-1q7VfX .tag-1YGWN9 {
  color: var(--text-normal);
}

/* SERVER SETTINGS -> INVITES */
[class*=theme-] .text-27cdrj,
[class*=theme-] .title-2CL_z0 {
  color: var(--text-normal);
}

/*
 *
 *	SERVER DISCOVERY
 *
 */
[class*=theme-] .pageWrapper-2PwDoS {
  background-color: var(--main-content-color);
}

/* SERVER DISCOVERY -> SIDEBAR */
.categoryItem-1QIroW.selectedCategoryItem-FHKU_o {
  color: var(--interactive-active);
}
.categoryItem-1QIroW.selectedCategoryItem-FHKU_o .itemInner-gPkiWb {
  background-color: var(--background-modifier-selected);
  background-image: var(--app-accent-image);
}

/* SERVER DISCOVERY -> MAIN CONTENT */
.search-25t1e9 .searchBox-31Zv9h {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha-focus));
  border-radius: 17px;
  border: none;
  box-shadow: none;
}
.search-25t1e9 .searchBox-31Zv9h .searchBoxInput-3h4etz {
  padding: 8px 12px;
  background-color: transparent !important;
}
.search-25t1e9 .searchBox-31Zv9h .searchIcon-3X4BYL {
  color: var(--textarea-text-color);
}

.card-2TuZPZ {
  background-color: var(--card-color) !important;
  border-radius: var(--card-radius) !important;
  border: none !important;
}
.card-2TuZPZ:hover {
  background-color: var(--card-color-hover) !important;
  border: none;
}

.container-1wv6C6 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
  border: none;
}
.container-1wv6C6 .addButton-Jt0onL {
  color: var(--app-accent-text);
}

/*
 *
 *	HOME TAB
 *
 */
.privateChannels-oVe7HL,
.scroller-WSmht3,
.nowPlayingColumn-1eCBCN {
  background-color: transparent;
}

.sidebar-1tnWFu {
  background-color: var(--sidebar-color);
}

.container-36u7Lw,
[class*=theme-] .container-2cd8Mz {
  background-color: var(--main-content-color);
}

/* HOME TAB -> FIND OR START A CONVERSATION */
.scroller-2qwVWY {
  margin: 0;
  background-color: transparent;
  overflow-y: auto !important;
}

.input-3r5zZY {
  height: 42px;
  line-height: 42px;
  padding: 0 16px;
  border-radius: 21px;
  font-size: 1.15em;
}

/* HOME TAB -> STAGE DISCOVERY */
.container-1a3EgQ {
  background-color: var(--main-content-color);
}

[class*=theme-] .container-S9SaVf {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}
[class*=theme-] .container-S9SaVf:hover {
  background-color: var(--card-color-hover);
}
[class*=theme-] .container-S9SaVf .container-7Unqij {
  background-color: var(--card-color);
}

/* HOME TAB -> FRIENDS */
.actionButton-3-B2x-,
.actionButton-3-B2x-.highlight-3DSi7b {
  background-color: var(--main-content-color);
}

.tabBody-2dgbAs:before {
  display: none;
}

.peopleListItem-u6dGxF:last-of-type {
  margin-bottom: 16px;
}

.tabBar-ra-EuL .item-3mHhwr[style*="background-color: rgb(67, 181, 129)"] {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity)) !important;
  color: var(--app-accent-text) !important;
}

/* HOME TAB -> FRIENDS -> ACTIVE NOW */
.wrapper-2RrXDg,
.emptyCard-KDifrB {
  background-color: var(--card-color);
  transition: var(--transition-time) var(--transition-type);
}

[class*=theme-] .outer-2JOHae.active-1W_Gl9,
[class*=theme-] .outer-2JOHae.interactive-2zD88a:hover {
  background-color: var(--card-color-hover);
}

[class*=theme-] .inset-SbsSFp {
  background-color: transparent;
}

.wrapper-3Rixsz,
.emptyCard-KDifrB,
.memberListItem-31QoHj {
  border-radius: var(--popout-radius);
}

[class*=theme-] .enabled-1t_Gxm:hover,
[class*=theme-] .memberListItem-31QoHj:not(.popoutDisabled-2RK7MF):hover {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
}

[class*=theme-] .enabled-1t_Gxm:hover .colorStandard-21JIj7,
[class*=theme-] .memberListItem-31QoHj:not(.popoutDisabled-2RK7MF):hover .colorStandard-21JIj7 {
  color: var(--app-accent-text);
}

[class*=theme-] .separator-2OaeRP {
  background-color: rgba(255, 255, 255, 0.2);
}

[class*=theme-] .applicationStreamingPreviewWrapper-7j27t8 {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

.image-1YnNzZ {
  border-radius: var(--card-radius);
}

/* HOME TAB -> FRIENDS -> ADD FRIEND */
.wrapper-1cBijl {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 26px;
  border: none;
  transition: var(--transition-time) var(--transition-type);
}
.wrapper-1cBijl:focus-within {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha-focus));
}

.addFriendInput-1Ta-rO, .addFriendInput-1Ta-rO:focus {
  background-color: transparent !important;
}

/* HOME TAB -> LIBRARY */
.scroller-2XLwLg,
.header-2EadGG {
  background-color: transparent;
}

.libraryHeader-2loraV {
  border-radius: 0;
  border: none;
}

.textCell-sKsLUQ {
  color: var(--text-normal);
}

/* HOME TAB -> LIBRARY -> DOWNLOADING GAME */
.gameUpdates-3Ts_5W {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

.progressCellText-3ajYcj {
  color: var(--text-normal);
}

/* HOME TAB -> LIBRARY -> SETTINGS */
.scroller-1TOeMq {
  background-color: transparent;
}

/* HOME TAB -> NITRO */
.applicationStore-2nk7Lo {
  background-color: var(--main-content-color);
}

.scroller-29cQFV {
  background-color: transparent;
}

[class*=theme-] .feature-2IUcBI,
.banner-WELp4M {
  background-color: var(--card-color);
  border-radius: var(--card-radius);
}

/*
 *
 *	DIRECT MESSAGES
 *
 */
.root-1e2tfc {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}

.incomingCallInner-2VmFiR {
  border: none;
}

.input-1nrc5P {
  border-radius: var(--input-radius);
}

.input-1nrc5P:focus,
.outer-1KB3kA:hover .input-1nrc5P {
  box-shadow: none;
}

.outer-1KB3kA:hover .input-1nrc5P {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
}

.compactButton-3hG-bs {
  background-color: var(--background-modifier-hover);
}
.compactButton-3hG-bs:hover {
  background-color: var(--background-modifier-selected);
}

/* DIRECT MESSAGES -> VOICE CALL */
.wrapper-1gVUIN.minimum-fXpVNc {
  background-color: transparent;
  box-shadow: var(--popout-header-shadow);
}

.callContainer-HtHELf {
  background-color: transparent;
}

.regionSelectPopout-3sEzVB {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow) !important;
  backdrop-filter: blur(var(--popout-blur));
}
.regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS:hover {
  background-color: var(--background-modifier-hover);
}
.regionSelectPopout-3sEzVB .quickSelectPopoutOption-2E2UmS:focus {
  background-color: var(--background-modifier-selected);
}

/*
 *
 *	SCREEN SHARE
 *
 */
.wrapper-1gVUIN {
  background-color: transparent;
}
.wrapper-1gVUIN.normal-qRirv5 {
  box-shadow: var(--popout-header-shadow);
}
.wrapper-1gVUIN .flexCenter-1Vz5gs {
  background-color: transparent;
  transition: 250ms ease background-color;
}
.wrapper-1gVUIN .flexCenter-1Vz5gs[style*="padding-right: 236px"] {
  background-color: transparent;
}

/* SCREEN SHARE -> SETTINGS */
.art-2OaYX0 + form .header-1zd7se {
  box-shadow: none;
}

.segmentControl-2FOwa5 {
  box-shadow: var(--popout-header-shadow);
}

.tile-38DNjt:hover .sourceThumbnail-3n4cjJ,
.sourceThumbnail-3n4cjJ.selected-2BhCFl {
  box-shadow: inset 0 0 0 2px rgba(var(--app-accent-rgb), var(--app-accent-opacity));
}

.card-1SdQ2- {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
  border-radius: 20px;
  border: none;
}

[class*=theme-] .item-2OyinQ {
  border: none;
}

.item-2OyinQ:first-child {
  border-radius: 15px 0 0 15px;
}
.item-2OyinQ:last-child {
  border-radius: 0 15px 15px 0;
}

.selectorButton-3sW6Qm {
  background-color: rgba(var(--textarea-color), var(--textarea-alpha));
}

.selectorButtonSelected-3cQUnj,
.selectorButton-3fWZ0_:not(.selectorButtonPremiumRequired-IZXhgV):hover {
  background-color: rgba(var(--app-accent-rgb), var(--app-accent-opacity));
  background-image: var(--app-accent-image);
}

.selectorTextSelected-2zup8I {
  color: var(--app-accent-text);
}

.selectorTextSelected-6vUbIH,
.selectorButton-3fWZ0_:not(.selectorButtonPremiumRequired-IZXhgV):hover .selectorText-LxivBc {
  color: var(--app-accent-text);
}

/* SCREEN SHARE -> PiP */
.pictureInPictureWindow-3ms5Zy {
  border-radius: var(--popout-radius);
  box-shadow: var(--popout-shadow);
}

.media-OcqfvM {
  border-radius: var(--popout-radius);
}

/*
 *
 *	BETTERDISCORD SETTINGS
 *
 */
.bd-settings-title {
  margin-bottom: 20px;
  line-height: 24px;
  font-size: 20px;
  font-weight: 600;
  color: var(--header-primary);
}

#bd-settings-sidebar .ui-tab-bar-item {
  margin-bottom: 2px;
}

[class*=theme-] #bd-settings-sidebar .ui-tab-bar-item.selected {
  background-color: var(--background-modifier-selected);
}

[class*=theme-] #bd-settingspane-container .ui-switch-item .style-description {
  color: var(--header-secondary);
}

/* BETTERDISCORD -> CUSTOM CSS */
.ace_editor {
  position: relative;
  overflow: visible;
}

.contentColumnDefault-3eyv5o .ace_editor {
  margin: 295px 0 0 0;
}
.contentColumnDefault-3eyv5o .ace_editor:before {
  position: absolute;
  content: "To change the colors such as the accent, copy the code below into\athe custom CSS. More variables can be found on the theme's GitHub\arepo page. bit.ly/TranslucenceDiscord\a\a:root {\a 	--app-bg: url(https://i.imgur.com/U8bSjj5.jpg) !important;\a 	--app-blur: 6px !important;\a 	--app-margin: 24px !important;\a 	--app-radius: 8px !important;\a 	--app-accent: #d73d3d !important;\a 	--app-accent-rgb: 215,61,61 !important;\a 	--app-accent-text: #000 !important;\a}";
  display: block;
  width: calc(100% - 32px);
  top: -295px;
  left: 0;
  padding: 16px;
  background: var(--card-color);
  border-radius: var(--card-radius);
  white-space: pre;
  font-size: 16px;
  color: #eee;
  font-family: Consolas, Menlo, Monaco, Lucida Console, Liberation Mono, DejaVu Sans Mono, Bitstream Vera Sans Mono, Courier New, monospace, serif !important;
}

/*
 *
 *	SCROLLBARS
 *
 */
::-webkit-scrollbar {
  width: var(--scrollbar-width) !important;
}

::-webkit-scrollbar-thumb {
  background: rgba(var(--scrollbar-color), var(--scrollbar-opacity)) !important;
  border-radius: calc(var(--scrollbar-width) / 2) !important;
}
::-webkit-scrollbar-thumb:hover {
  background: rgba(var(--scrollbar-color), var(--scrollbar-opacity-hover)) !important;
}

::-webkit-scrollbar,
::-webkit-scrollbar-track,
::-webkit-scrollbar-track-piece,
.scroller-2qwVWY::-webkit-scrollbar-track {
  background: transparent !important;
  border-color: transparent !important;
}

/* SCROLLBARS -> ALT SCROLLBAR */
.thin-31rlnD::-webkit-scrollbar {
  width: 8px !important;
  height: 8px !important;
}

/* SCROLLBARS -> REMOVE SCROLLBAR */
.wrapper-1_HaEi [class*=scroller]::-webkit-scrollbar {
  width: 0px !important;
}

/*
 *
 *	SUPPORTED PLUGINS
 *
 */
/* SUPPORTED PLUGINS -> CharCounter */
.charCounter-7fw40k {
  position: relative;
  z-index: 1;
}

.chatCounter-XOMPsh {
  bottom: auto;
}

.charCounterAdded-zz9O4t {
  margin-bottom: 24px;
}

.counter-uAzbKp {
  position: absolute !important;
  width: auto;
  height: 24px;
  margin-top: -12px;
  padding: 0;
  line-height: 24px;
  border-top: none;
  box-sizing: border-box;
  text-align: right;
  font-weight: 500;
  color: var(--text-normal);
}

/* SUPPORTED PLUGINS -> EditUploads*/
#EditUploadsModal {
  background-color: var(--popout-color);
}

#EditUploadsToolbar {
  background-color: transparent;
}

/* SUPPORTED PLUGINS -> HideChannels */
.sidebar-1tnWFu.hideElement .container-YkUktl {
  position: absolute;
  overflow: hidden;
}
.sidebar-1tnWFu.hideElement .container-YkUktl, .sidebar-1tnWFu.hideElement .container-YkUktl:before {
  background-color: transparent !important;
  border-radius: 0;
  box-shadow: none !important;
}
.sidebar-1tnWFu.hideElement .container-YkUktl:before {
  box-shadow: inset 0 0 0 100vmax var(--main-content-color) !important;
}

/* SUPPORTED PLUGINS -> ServerSearch */
.popoutRight-1veHKi.noArrow-2foL9g {
  overflow: hidden;
}

/*
 *
 *	OLD DISCORD LOGO
 *
 */
.wordmarkWindows-2dq6rw {
  width: 55px;
  height: 16px;
}
.wordmarkWindows-2dq6rw:after {
  position: absolute;
  content: url("data:image/svg+xml;utf8,<svg viewBox='0 0 55 16' width='55' height='16' xmlns='http://www.w3.org/2000/svg'><path fill='white' d='M3.57642276,0.141304348 L0,0.141304348 L0,4.22826087 L2.38069106,6.40217391 L2.38069106,2.43478261 L3.66260163,2.43478261 C4.47052846,2.43478261 4.86910569,2.83695652 4.86910569,3.4673913 L4.86910569,6.5 C4.86910569,7.13043478 4.49207317,7.55434783 3.66260163,7.55434783 L0,7.55434783 L0,9.85869565 L3.57642276,9.85869565 C5.49390244,9.86956522 7.29288618,8.90217391 7.29288618,6.66304348 L7.29288618,3.39130435 C7.29288618,1.13043478 5.49390244,0.141304348 3.57642276,0.141304348 Z M22.3310976,6.67391304 L22.3310976,3.32608696 C22.3310976,2.11956522 24.4640244,1.83695652 25.1103659,3.05434783 L27.0817073,2.23913043 C26.3168699,0.510869565 24.8949187,0 23.7207317,0 C21.803252,0 19.9073171,1.13043478 19.9073171,3.32608696 L19.9073171,6.67391304 C19.9073171,8.88043478 21.803252,10 23.6776423,10 C24.8841463,10 26.3276423,9.39130435 27.1247967,7.81521739 L25.0134146,6.82608696 C24.4963415,8.17391304 22.3310976,7.84782609 22.3310976,6.67391304 Z M15.8030488,3.7826087 C15.0597561,3.61956522 14.5642276,3.34782609 14.5319106,2.88043478 C14.575,1.75 16.2878049,1.7173913 17.2896341,2.79347826 L18.8731707,1.55434783 C17.8821138,0.326086957 16.7617886,0 15.598374,0 C13.8424797,0 12.1404472,1 12.1404472,2.91304348 C12.1404472,4.77173913 13.5408537,5.76086957 15.0813008,6 C15.8676829,6.10869565 16.7402439,6.42391304 16.7186992,6.97826087 C16.654065,8.02173913 14.5426829,7.9673913 13.5839431,6.7826087 L12.0650407,8.23913043 C12.9591463,9.40217391 14.1764228,10 15.3182927,10 C17.074187,10 19.0239837,8.9673913 19.0993902,7.08695652 C19.2071138,4.69565217 17.5050813,4.09782609 15.8030488,3.7826087 Z M8.59634146,9.85869565 L11.0093496,9.85869565 L11.0093496,0.141304348 L8.59634146,0.141304348 L8.59634146,9.85869565 Z M49.2835366,0.141304348 L45.7071138,0.141304348 L45.7071138,4.22826087 L48.0878049,6.40217391 L48.0878049,2.43478261 L49.3589431,2.43478261 C50.1668699,2.43478261 50.5654472,2.83695652 50.5654472,3.4673913 L50.5654472,6.5 C50.5654472,7.13043478 50.1884146,7.55434783 49.3589431,7.55434783 L45.6963415,7.55434783 L45.6963415,9.85869565 L49.2727642,9.85869565 C51.1902439,9.86956522 52.9892276,8.90217391 52.9892276,6.66304348 L52.9892276,3.39130435 C53,1.13043478 51.2010163,0.141304348 49.2835366,0.141304348 Z M31.7353659,0 C29.753252,0 27.7819106,1.09782609 27.7819106,3.33695652 L27.7819106,6.66304348 C27.7819106,8.89130435 29.7640244,10 31.7569106,10 C33.7390244,10 35.7103659,8.89130435 35.7103659,6.66304348 L35.7103659,3.33695652 C35.7103659,1.10869565 33.7174797,0 31.7353659,0 Z M33.2865854,6.66304348 C33.2865854,7.35869565 32.5109756,7.7173913 31.7461382,7.7173913 C30.9705285,7.7173913 30.1949187,7.36956522 30.1949187,6.66304348 L30.1949187,3.33695652 C30.1949187,2.61956522 30.9489837,2.23913043 31.7030488,2.23913043 C32.4894309,2.23913043 33.2865854,2.58695652 33.2865854,3.33695652 L33.2865854,6.66304348 Z M44.3605691,3.33695652 C44.3067073,1.05434783 42.7770325,0.141304348 40.8056911,0.141304348 L36.9815041,0.141304348 L36.9815041,9.86956522 L39.4268293,9.86956522 L39.4268293,6.77173913 L39.8577236,6.77173913 L42.0768293,9.85869565 L45.0930894,9.85869565 L42.4861789,6.52173913 C43.6495935,6.15217391 44.3605691,5.14130435 44.3605691,3.33695652 Z M40.8487805,4.65217391 L39.4268293,4.65217391 L39.4268293,2.43478261 L40.8487805,2.43478261 C42.3784553,2.43478261 42.3784553,4.65217391 40.8487805,4.65217391 Z' transform='translate(1 3)'/></svg>");
  width: 55px;
  height: 16px;
  opacity: 0.6;
}
.wordmarkWindows-2dq6rw svg {
  display: none;
}

/*# sourceMappingURL=Translucence.theme.css.map */
