/* ------------------------------------------------------------ 🌷 BASE ------------------------------------------------------------ */

/* ---- Style ---- */
.theme-dark {
    --header-primary: #fff;
    --header-secondary: #b9bbbe;
    --text-normal: #dcddde;
    --text-muted: #b9bbbe;
    --interactive-normal: #b9bbbe;
    --interactive-hover: #dcddde;
    --interactive-active: #fff;
    --interactive-muted: #72767d;
    --background-primary: #292841;
    --background-secondary: #232438;
    --background-secondary-alt: #1d1f2f;
    --background-tertiary: #182626;
    --background-accent: #4f8d8d;
    --background-floating: #101918;
    --background-mobile-primary: #292841;
    --background-mobile-secondary: #232438;
    --background-modifier-hover: rgba(62, 98, 101, 0.589);
    --background-modifier-active: rgba(62, 98, 101, 0.24);
    --background-modifier-selected: rgba(62, 98, 101, 0.32);
    --background-modifier-accent: hsla(0, 0%, 100%, 0.06);
    --info-positive-text: #fff;
    --info-warning-text: #fff;
    --info-danger-text: #fff;
    --info-help-background: hsla(
        197,
        calc(var(--saturation-factor, 1) * 100%),
        47.8%,
        0.1
    );
    --info-help-foreground: hsl(
        197,
        calc(var(--saturation-factor, 1) * 100%),
        47.8%
    );
    --info-help-text: #fff;
    --status-warning-text: #000;
    --scrollbar-thin-thumb: #181926;
    --scrollbar-thin-track: transparent;
    --scrollbar-auto-thumb: #181926;
    --scrollbar-auto-track: hsl(
        233,
        calc(var(--saturation-factor, 1) * 26%),
        18%
    );
    --scrollbar-auto-scrollbar-color-thumb: #181926;
    --scrollbar-auto-scrollbar-color-track: #232438;
    --elevation-stroke: 0 0 0 1px rgba(4, 4, 5, 0.15);
    --elevation-low: 0 1px 0 rgba(4, 4, 5, 0.2), 0 1.5px 0 rgba(6, 6, 7, 0.05),
        0 2px 0 rgba(4, 4, 5, 0.05);
    --elevation-medium: 0 4px 4px rgba(0, 0, 0, 0.16);
    --elevation-high: 0 8px 16px rgba(0, 0, 0, 0.24);
    --logo-primary: #fff;
    --control-brand-foreground: hsl(
        227,
        calc(var(--saturation-factor, 1) * 57.9%),
        77.6%
    );
    --control-brand-foreground-new: hsl(
        235,
        calc(var(--saturation-factor, 1) * 86.1%),
        77.5%
    );
    --background-mentioned: hsla(
        38,
        calc(var(--saturation-factor, 1) * 95.7%),
        54.1%,
        0.1
    );
    --background-mentioned-hover: hsla(
        38,
        calc(var(--saturation-factor, 1) * 95.7%),
        54.1%,
        0.08
    );
    --background-message-hover: rgba(4, 4, 5, 0.07);
    --channels-default: #8e9297;
    --guild-header-text-shadow: 0 1px 1px rgba(0, 0, 0, 0.4);
    --channeltextarea-background: #317c86;
    --activity-card-background: #181926;
    --textbox-markdown-syntax: #8e9297;
    --deprecated-card-bg: rgba(24, 35, 38, 0.6);
    --deprecated-card-editable-bg: rgba(24, 25, 38, 0.3);
    --deprecated-store-bg: #283d41;
    --deprecated-quickswitcher-input-background: #4f8d8d;
    --deprecated-quickswitcher-input-placeholder: hsla(0, 0%, 100%, 0.3);
    --deprecated-text-input-bg: rgba(0, 0, 0, 0.1);
    --deprecated-text-input-border: rgba(0, 0, 0, 0.3);
    --deprecated-text-input-border-hover: #040405;
    --deprecated-text-input-border-disabled: #181926;
    --deprecated-text-input-prefix: #dcddde;
}
.theme-dark,
.theme-light {
    --text-link: hsl(212, calc(var(--saturation-factor, 1) * 100%), 67%);
    --text-link-low-saturation: hsl(
        212,
        calc(var(--saturation-factor, 1) * 100%),
        72%
    );
    --text-positive: var(--green);
    --text-warning: var(--yellow);
    --text-danger: var(--red);
    --info-positive-background: hsla(
        139,
        calc(var(--saturation-factor, 1) * 47.3%),
        43.9%,
        0.1
    );
    --info-positive-foreground: hsl(
        139,
        calc(var(--saturation-factor, 1) * 47.3%),
        43.9%
    );
    --info-warning-background: hsla(
        38,
        calc(var(--saturation-factor, 1) * 95.7%),
        54.1%,
        0.1
    );
    --info-warning-foreground: hsl(
        38,
        calc(var(--saturation-factor, 1) * 95.7%),
        54.1%
    );
    --info-danger-background: hsla(
        359,
        calc(var(--saturation-factor, 1) * 82.6%),
        59.4%,
        0.1
    );
    --info-danger-foreground: hsl(
        359,
        calc(var(--saturation-factor, 1) * 82.6%),
        59.4%
    );
    --status-positive-background: hsl(
        139,
        calc(var(--saturation-factor, 1) * 47.3%),
        43.9%
    );
    --status-positive-text: #fff;
    --status-warning-background: hsl(
        38,
        calc(var(--saturation-factor, 1) * 95.7%),
        54.1%
    );
    --status-danger-background: hsl(
        359,
        calc(var(--saturation-factor, 1) * 82.6%),
        59.4%
    );
    --status-danger-text: #fff;
    --focus-primary: hsl(197, calc(var(--saturation-factor, 1) * 100%), 47.8%);
}
:root {
    --border-radius-1: 16px;
    --border-radius-2: 10px;
    --border-radius-3: 5px;

    --grey: #99aab5;
    --bronze: #e4953c;

    --usesettingsicons: calc(
        var(--settingsicons, 1) /
            (var(--settingsicons, 1) + 0.00000000000000000000001)
    );
    --settingsiconssize: 20px;
    --settingsiconsgap: 10px;
}
::selection {
    background: #59e9f380;
}

/* ---- Buttons ---- */
button:not(.searchBarComponent-32dTOx):not(.colorPickerSwatch-5GX3Ve):not(.bd-button) {
    border-radius: var(10px) !important;
}
.theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6,
.theme-dark .lookFilled-1Gx00P.colorGrey-2DXtkV,
.iconWrapper-3LVgIo[role="button"] {
    background-color: var(--background-accent) !important;
}
.theme-dark .lookFilled-1Gx00P.colorPrimary-3b3xI6:hover,
.theme-dark .lookFilled-1Gx00P.colorGrey-2DXtkV:hover,
.iconWrapper-3LVgIo[role="button"]:hover {
    background-color: #4a4c73 !important;
}

/* ------------------------------------------------------------ 🌱 HOME ------------------------------------------------------------ */

/* ---- Friends ---- */
.theme-dark .container-1D34oG {
    background-color: var(--background-primary);
}
.peopleListItem-2nzedh,
.actions-1SQwjn,
.actions-1SQwjn .actionButton-uPB8Fs {
    transition: 0.25s;
}

/* ---- Activity Cards ---- */
.theme-dark .outer-1AjyKL {
    transition: ease-out 0.25s;
}
.theme-dark .outer-1AjyKL.active-1xchHY,
.theme-dark .outer-1AjyKL.interactive-3B9GmY:hover {
    background-color: var(--background-floating);
}

/* ------------------------------------------------------------ 🐻 STATUS AND STATUS PICKER ------------------------------------------------------------ */

#status-picker > .scroller-3BxosC > .item-1tOPte,
#status-picker > .scroller-3BxosC > .submenuContainer-2gbm7M > .item-1tOPte {
    border-radius: var(--border-radius-3);
    transition: 0.3s;
}
#status-picker {
    border-radius: var(--border-radius-2);
}

.status-1AY8sU[style*="background-color: hsl(139, calc(var(--saturation-factor, 1) * 47.3%), 43.9%);"],
[mask*="url(#svg-mask-status-online)"],
[mask*="url(#svg-mask-status-online-mobile)"],
[fill="hsl(139, calc(var(--saturation-factor, 1) * 47.3%), 43.9%)"],
[aria-label="Online"] > svg > rect,
.status-1AY8sU[style*="background-color: hsl(38, calc(var(--saturation-factor, 1) * 95.7%), 54.1%);"],
[mask*="url(#svg-mask-status-idle)"],
[fill="hsl(38, calc(var(--saturation-factor, 1) * 95.7%), 54.1%)"],
[aria-label="Idle"] > svg > rect,
.status-1AY8sU[style*="background-color: hsl(359, calc(var(--saturation-factor, 1) * 82.6%), 59.4%)"],
[mask*="url(#svg-mask-status-dnd)"],
[fill="hsl(359, calc(var(--saturation-factor, 1) * 82.6%), 59.4%)"],
[aria-label="Do Not Disturb"] > svg > rect,
[mask*="url(#svg-mask-status-offline)"],
[aria-label="Offline"] > svg > rect,
.wrapper-3t9DeA > svg > svg > rect {
    transition: ease 1s;
}

/* ---- Online ---- */
.status-1AY8sU[style*="background-color: hsl(139, calc(var(--saturation-factor, 1) * 47.3%), 43.9%);"] {
    background-color: var(--green) !important;
}
[mask*="url(#svg-mask-status-online)"],
[mask*="url(#svg-mask-status-online-mobile)"],
[fill="hsl(139, calc(var(--saturation-factor, 1) * 47.3%), 43.9%)"],
[aria-label="Online"] > svg > rect {
    fill: var(--green);
}
.status-1AY8sU[style*="background-color: rgb(59, 165, 92);"] {
    background-color: var(--green) !important;
}
#status-picker-online.colorDefault-2K3EoJ,
#status-picker-online.colorDefault-2K3EoJ.focused-3afm-j {
    color: var(--green);
}
#status-picker-online.focused-3afm-j {
    background-color: var(--green4);
}
/* ---- Idle ---- */
.status-1AY8sU[style*="background-color: hsl(38, calc(var(--saturation-factor, 1) * 95.7%), 54.1%);"] {
    background-color: var(--yellow) !important;
}
[mask*="url(#svg-mask-status-idle)"],
[fill="hsl(38, calc(var(--saturation-factor, 1) * 95.7%), 54.1%)"],
[aria-label="Idle"] > svg > rect {
    fill: var(--yellow);
}
.status-1AY8sU[style*="background-color: rgb(250, 166, 26);"] {
    background-color: var(--yellow) !important;
}
#status-picker-idle.colorDefault-2K3EoJ,
#status-picker-idle.colorDefault-2K3EoJ.focused-3afm-j {
    color: var(--yellow);
}
#status-picker-idle.focused-3afm-j {
    background-color: var(--yellow4);
}
/* ---- Do Not Disturb ---- */
.status-1AY8sU[style*="background-color: hsl(359, calc(var(--saturation-factor, 1) * 82.6%), 59.4%)"] {
    background-color: var(--red) !important;
}
[mask*="url(#svg-mask-status-dnd)"],
[fill="hsl(359, calc(var(--saturation-factor, 1) * 82.6%), 59.4%)"],
[aria-label="Do Not Disturb"] > svg > rect {
    fill: var(--red);
}
.status-1AY8sU[style*="background-color: rgb(237, 66, 69);"] {
    background-color: var(--red) !important;
}
#status-picker-dnd.colorDefault-2K3EoJ,
#status-picker-dnd.colorDefault-2K3EoJ.focused-3afm-j {
    color: var(--red);
}
#status-picker-dnd.focused-3afm-j {
    background-color: var(--red4);
}
/* ---- Invisible ---- */
[mask*="url(#svg-mask-status-offline)"],
[aria-label="Offline"] > svg > rect {
    fill: #99aab5;
}
#status-picker-invisible.colorDefault-2K3EoJ,
#status-picker-invisible.colorDefault-2K3EoJ.focused-3afm-j {
    color: #99aab5;
}
#status-picker-invisible.focused-3afm-j {
    background-color: #97a9b42b;
}
/* ---- Custom ---- */
.customEmojiPlaceholder-37iZ_j {
    background-image: url("https://kaiidoo.github.io/Newcord/icons/others/setAcustomStatus.svg");
}
#status-picker-custom-status.colorDefault-2K3EoJ,
#status-picker-custom-status.colorDefault-2K3EoJ.focused-3afm-j {
    color: #ffcc4d;
}
#status-picker-custom-status.focused-3afm-j {
    background-color: #ffcc4d2b;
}
/* ---- Streaming ---- */
[mask="url(#svg-mask-status-streaming)"],
[aria-label="Streaming"] > svg > rect {
    fill: var(--purple);
}

/* ------------------------------------------------------------ 🍯 PERSONAL SETTINGS ------------------------------------------------------------ */

/* ---- Billing ---- */
/* Transaction History */
.theme-dark .codeRedemptionRedirect-1wVR4b {
    background-color: var(--background-secondary);
    border-color: var(--background-tertiary);
}

/* ---- Voice & Video ---- */
/* Preview Video */
.theme-dark .userSettingsVoice-iwdUCU .previewOverlay-2O7_KC {
    background-color: var(--background-secondary);
    border-color: var(--background-tertiary);
}

/* ---- Activity Status ---- */
/* Add an activity Pop-up */
.theme-dark .addGamePopout-2RY8Ju {
    background-color: var(--background-primary)
}

/* ---- Boost Cards ---- */
.cardWrapper-2Min21 {
    border-radius: var(--border-radius-1);
}
/* Level Circle */
.theme-dark .gemIndicatorContainer-2jdECl {
    background-color: var(--background-secondary);
}

/* ---- Connections ---- */
.connectedAccounts-2-XP1G .inner-2Y6JuD.accountBtnInner-sj5jLs {
    background-size: 30px 30px;
}

/* ---- Scrollbar ---- */
.contentRegion-3nDuYy {
    --scrollbar-auto-thumb: transparent;
    --scrollbar-auto-track: transparent;
}

/* ---- Add phone number ---- */
.theme-dark .popoutList-T9CKZQ {
    background-color: var(--background-primary);
}
.theme-dark .input-3yHnCz {
    background-color: var(--background-accent);
}

/* ---- Custom CSS editor ---- */
.monaco-editor,
.monaco-editor-background,
.monaco-editor .inputarea.ime-input,
.monaco-editor .margin,
.monaco-editor .minimap-decorations-layer,
.monaco-editor .visible.scrollbar.vertical {
    background-color: var(--background-tertiary) !important;
}
.monaco-editor .hover-contents {
    background-color: var(--background-secondary-alt);
}
.monaco-editor .view-lines .mtk4 {
    color: #f95b4f;
}
.monaco-editor .view-lines .mtk5 {
    color: #ec8824;
}
.monaco-editor .view-lines .mtk8 {
    color: #92c6f0;
}

/* ------------------------------------------------------------ 🌿 CHANNEL ------------------------------------------------------------ */

/* ---- Guild Header Popout ---- */
#guild-header-popout {
    border-radius: var(--border-radius-2);
}
#guild-header-popout .labelContainer-1BLJti {
    flex-direction: row-reverse;
}
#guild-header-popout .iconContainer-2-XQPY {
    margin: 0 8px 0 0;
}
.menu-3sdvDG {
    border-radius: var(--border-radius-2);
    overflow: hidden;
}
.scroller-3BxosC .labelContainer-1BLJti {
    margin: 0;
    padding: 8px;
    border-radius: var(--border-radius-3);
    transition: 0.2s;
}

/* Server Boost */
#guild-header-popout-premium-subscribe:hover .icon-LYJorE,
#guild-header-popout-premium-subscribe:active:not(.hideInteraction-1iHO1O)
    .icon-LYJorE {
    color: #73d7ff;
}
#guild-header-popout-premium-subscribe:hover,
#guild-header-popout-premium-subscribe:active:not(.hideInteraction-1iHO1O) {
    background-color: #73ccff2a;
}
/* Invite People */
#guild-header-popout-invite-people:hover .icon-LYJorE,
#guild-header-popout-invite-people:active:not(.hideInteraction-1iHO1O)
    .icon-LYJorE {
    color: #a5b3e7;
}
#guild-header-popout-invite-people:hover,
#guild-header-popout-invite-people:active:not(.hideInteraction-1iHO1O) {
    background-color: #a5b3e72a;
    color: #a5b3e7;
}
/* Server Settings */
#guild-header-popout-settings .icon-LYJorE,
#guild-header-popout-settings:active:not(.hideInteraction-1iHO1O) .icon-LYJorE {
    color: #546e7a;
}
#guild-header-popout-settings:hover,
#guild-header-popout-settings:active:not(.hideInteraction-1iHO1O) {
    background-color: #546e7a2a;
}
/* Server Insights */
#guild-header-popout-insights .icon-LYJorE,
#guild-header-popout-insights:active:not(.hideInteraction-1iHO1O) .icon-LYJorE {
    color: #1abc9c;
}
#guild-header-popout-insights:hover,
#guild-header-popout-insights:active:not(.hideInteraction-1iHO1O) {
    background-color: #1abc9c2a;
}
/* Create Channel */
#guild-header-popout-create-channel .icon-LYJorE,
#guild-header-popout-create-channel:active:not(.hideInteraction-1iHO1O)
    .icon-LYJorE {
    color: #e91e63;
}
#guild-header-popout-create-channel:hover,
#guild-header-popout-create-channel:active:not(.hideInteraction-1iHO1O) {
    background-color: #e91e632a;
}
/* Create Category */
#guild-header-popout-create-category .icon-LYJorE,
#guild-header-popout-create-category:active:not(.hideInteraction-1iHO1O)
    .icon-LYJorE {
    color: #eaa14e;
}
#guild-header-popout-create-category:hover,
#guild-header-popout-create-category:active:not(.hideInteraction-1iHO1O) {
    background-color: #eaa14e2a;
}
/* Notifications */
#guild-header-popout-notifications .icon-LYJorE,
#guild-header-popout-notifications:active:not(.hideInteraction-1iHO1O)
    .icon-LYJorE {
    color: #fcd462;
}
#guild-header-popout-notifications:hover,
#guild-header-popout-notifications:active:not(.hideInteraction-1iHO1O) {
    background-color: #fcd4622a;
}
/* Privacy */
#guild-header-popout-privacy .icon-LYJorE,
#guild-header-popout-privacy:active:not(.hideInteraction-1iHO1O) .icon-LYJorE {
    color: #4a84d4;
}
#guild-header-popout-privacy:hover,
#guild-header-popout-privacy:active:not(.hideInteraction-1iHO1O) {
    background-color: #4a84d42a;
}
/* Nickname */
#guild-header-popout-change-nickname .icon-LYJorE,
#guild-header-popout-change-nickname:active:not(.hideInteraction-1iHO1O)
    .icon-LYJorE {
    color: #57f287;
}
#guild-header-popout-change-nickname:hover,
#guild-header-popout-change-nickname:active:not(.hideInteraction-1iHO1O) {
    background-color: #57f2872a;
}
/* Hide Muted Channels */
#guild-header-popout-hide-muted-channels:hover svg > path:first-child {
    color: #449eba;
}
#guild-header-popout-hide-muted-channels:hover,
#guild-header-popout-hide-muted-channels:active:not(.hideInteraction-1iHO1O) {
    background-color: #44baba5a;
}
#guild-header-popout-hide-muted-channels:hover svg > path:last-child {
    color: white;
}
/* Leave */
#guild-header-popout-leave:hover .icon-LYJorE,
#guild-header-popout-leave:active:not(.hideInteraction-1iHO1O) .icon-LYJorE {
    color: #ed4245;
}
#guild-header-popout-leave:hover,
#guild-header-popout-leave:active:not(.hideInteraction-1iHO1O) {
    background-color: #ed42452a;
    color: #ed4245;
}
/* Label */
.labelContainer-1BLJti.colorDefault-2K3EoJ:hover,
.labelContainer-1BLJti.colorDefault-2K3EoJ.focused-3afm-j,
.labelContainer-1BLJti.colorDefault-2K3EoJ:active:not(.hideInteraction-1iHO1O) {
    background-color: #4499ba5a;
}
.labelContainer-1BLJti.colorDanger-2qLCe1:hover,
.labelContainer-1BLJti.colorDanger-2qLCe1.focused-3afm-j,
.labelContainer-1BLJti.colorDanger-2qLCe1:active:not(.hideInteraction-1iHO1O) {
    background-color: #ed42452a;
}

/* ---- Upload ---- */
.theme-dark .uploadModal-2ifh8j {
    background-color: var(--background-primary);
}
.theme-dark .footer-3mqk7D {
    background-color: var(--background-secondary);
}

/* ---- Channel Topic Popup ---- */
.theme-dark .root-1gCeng {
    background-color: var(--background-primary);
}

/* ---- Channel Header ---- */
/* Buttons and searchBar */
.search-2oPWTC:not(.open-6_Y_aH) .searchBar-3dMhjb {
    width: 27px;
    background-color: transparent;
    transition: 0.25s;
}
.search-2oPWTC:not(.open-6_Y_aH):hover .searchBar-3dMhjb {
    width: 240px;
    transition: 0.25s;
}
.topControls-KKImPZ.controlSection-2h3cS0
    > div
    > div
    > section
    > .toolbar-1t6TWx
    > .button-1xaXFt.iconWrapper-2OrFZ1.clickable-3rdHwn {
    background-color: transparent !important;
}
.topControls-KKImPZ.controlSection-2h3cS0
    > div
    > div
    > section
    > .toolbar-1t6TWx
    > .button-1xaXFt.iconWrapper-2OrFZ1.clickable-3rdHwn
    > svg {
    color: var(--settings-icon-color) !important;
}
.search-36MZv-:not(.open-6_Y_aH) {
    padding: 6px 4.5px 6px 4.5px;
    margin: 1px 1px 1px 1px;
    order: -1;
    border-radius: var(--border-radius-1);
}
.threadSidebar-1o3BTy > section > .toolbar-1t6TWx .clickable-3rdHwn {
    border-radius: var(--border-radius-1);
}
.toolbar-1t6TWx > :first-child:not(.inviteToolbar-3F-l2g) {
    border-radius: var(--border-radius-1) 0px 0px var(--border-radius-1);
}
.toolbar-1t6TWx > :last-child > div,
.toolbar-1t6TWx > :last-child {
    border-radius: 0px var(--border-radius-1) var(--border-radius-1) 0px;
}
.searchBar-3dMhjb .icon-38sknP {
    width: 24px;
    height: 24px;
}
.toolbar-1t6TWx .iconContainer-O4O2CN {
    width: 20px;
    height: 20px;
}

/* ---- SearchBox ---- */
.searchResultsWrap-3-pOjs .scroller-3GIiMh,
.searchResultsWrap-3-pOjs .channelName-1JRO3C {
    background-color: var(--background-tertiary) !important;
}
.react-datepicker,
.react-datepicker__header {
    background-color: var(--background-secondary) !important;
}
.react-datepicker__day:first-of-type {
    border-radius: var(--border-radius-2) 0 0 var(--border-radius-2) !important;
}
.react-datepicker__day--fri {
    border-radius: 0 var(--border-radius-2) var(--border-radius-2) 0;
}
.react-datepicker__day:last-of-type,
.option-96V44q {
    border-radius: var(--border-radius-2) !important;
}
.react-datepicker__day {
    background-color: var(--background-tertiary) !important;
}
.react-datepicker__day--selected:after {
    background-color: var(--accent-color) !important;
}
.datePickerHint-3Q1Udw .hintValue-29ny8Z,
.theme-dark .activeButton-rvKcqq {
    background-color: var(--accent-color) !important;
    color: var(--interactive-selected) !important;
}
.focused-2bY0OD.queryContainer-RKFJW- {
    background-color: var(--background-modifier-hover);
}
.queryContainer-RKFJW- {
    margin: 10px;
    border-radius: var(--border-radius-2);
}
.container-3ayLPN {
    background-color: var(--background-tertiary) !important;
    border-radius: var(--border-radius-2);
    border: 1px solid var(--background-tertiary);
}
.option-96V44q:after {
    display: none;
}
.theme-dark .option-96V44q.selected-rZcOL- {
    background-color: var(--background-modifier-hover);
}

/* ---- Channels Bar ---- */
/* Stream Preview */
.theme-dark .streamPreview-2-WUWT {
    background-color: var(--background-tertiary);
}
.theme-dark .previewContainer-12UlHl {
    background-color: var(--background-secondary-alt);
}
/* Voice Connected Popout */
.theme-dark .container-2x5lvQ section {
    background-color: var(--background-primary);
}
.theme-dark .container-2x5lvQ .header-2C89wJ {
    background-color: var(--background-secondary);
}

/* ---- No Channel ---- */
.noChannel-3LgMRp {
    background-color: var(--background-primary);
}

/* ------------------------------------------------------------ 🦢 MEMBERS ------------------------------------------------------------ */

/* ---- Member Popout ---- */
.userPopout-xaxa6l {
    max-height: calc(100vh - 40px);
}
/* Roles */
.body-3HBlXn .rolesList-1geHY1 .role-2irmRk {
    position: relative;
    border: none;
    margin: 0 6px 6px 0;
    background: transparent;
}
.body-3HBlXn .rolesList-1geHY1 .roleCircle-3xAZ1j::before {
    content: "";
    position: absolute;
    top: 0;
    left: 2px;
    width: 100%;
    height: 100%;
    background: inherit;
    opacity: 0.2;
    pointer-events: none;
    border-radius: 11px;
}
.body-3HBlXn .rolesList-1geHY1 {
    left: -2px;
}
.body-3HBlXn .rolesList-1geHY1 .roleCircle-3xAZ1j {
    height: 14px;
    width: 14px;
}
.body-3HBlXn .rolesList-1geHY1 .roleName-32vpEy {
    color: var(--text-normal);
}
/* "Invisible" Role Color */
.body-3HBlXn
    .rolesList-1geHY1
    .roleCircle-3xAZ1j[style="background-color: rgb(24, 25, 28);"],
.username-1A8OIy[style="background-color: rgb(24, 25, 28);"] {
    background-color: var(--background-floating) !important;
}
/* Note and Message*/
.bodyTitle-1ySSKn.base-1x0h_U.size12-3cLvbJ.muted-3-7c5L.uppercase-3VWUQ9,
.note-1oo11U,
.inputWrapper-31_8H8.quickMessage-3jDbBs {
    display: none;
}

/* ------------------------------------------------------------ 🥭 CHAT ------------------------------------------------------------ */

/* ---- Spoilers ---- */
.theme-dark .spoilerText-3p6IlD.hidden-HHr2R9 {
    background-color: var(--background-tertiary);
}
.theme-dark .spoilerText-3p6IlD.hidden-HHr2R9:hover {
    background-color: #181926cc;
}

/* ---- Slash Commands ---- */
.theme-dark .autocomplete-1vrmpx,
.categoryHeader-O1zU94 {
    background-color: var(--background-secondary);
}
.theme-dark .selected-1Tbx07 {
    background-color: var(--background-primary);
}

/* ---- Emotes Picker ---- */
.sprite-2iCowe {
    filter: var(--colored-emoji) !important;
}
/*  Disabled Emotes */
.emojiItem-14v6tW.emojiItemDisabled-1FvFuF {
    pointer-events: none;
    filter: none;
    opacity: 0.3;
}
.emojiItem-14v6tW .imageLoading-bpSr0M {
    display: none;
}
.unicodeShortcut-15J8Ck {
    background-color: var(--background-secondary-alt);
}
.theme-dark .emptyHintCard-2mUdMe {
    background-color: var(--background-primary);
}

/* ---- Icons and Buttons Colors ---- */
/* Gift */
.button-38aScr .buttonWrapper-1ZmCpA > * {
    color: #ff73fa;
}
/* Gif */
#gif-picker-tab .navButton-2gQCx-,
.button-38aScr .icon-3D60ES {
    color: #58e0f2;
}
#gif-picker-tab .navButtonActive-1MkytQ,
#gif-picker-tab button:hover {
    background-color: #5865f22a;
}
/* Stickers */
#sticker-picker-tab .navButton-2gQCx-,
.button-38aScr .stickerIcon-3TP7EM {
    color: #57f287;
}
#sticker-picker-tab .navButtonActive-1MkytQ,
#sticker-picker-tab button:hover {
    background-color: #57f2872a;
}
/* Emoji Picker */
#emoji-picker-tab .navButton-2gQCx- {
    color: #ffcc4d;
}
#emoji-picker-tab .navButtonActive-1MkytQ,
#emoji-picker-tab button:hover {
    background-color: #ffcc4d2a;
}

/* ---- Images And Videos ---- */
.imageWrapper-2p5ogY img,
.imageWrapper-2p5ogY video,
.embedImage-2W1cML img,
.embedImage-2W1cML video,
.embedThumbnail-2Y84-K img,
.embedThumbnail-2Y84-K video,
.embedVideo-3nf0O9 img,
.embedVideo-3nf0O9 video {
    border-radius: var(--border-radius-2);
}

/* ---- Delete A Message ---- */
.theme-dark .message-2qRu38 {
    background-color: var(--background-primary);
}
.theme-dark .footer-2gL1pp {
    background-color: var(--background-secondary);
}

/* ---- Everyone Warning Pop-up */
.theme-dark .contentWarningPopout-n5JsIs {
    background-color: var(--background-primary);
}

/* ---- Others ---- */
/* Favorite GIF */
.gifFavoriteButton-3Zycl7:hover {
    color: #ffcc4d;
}
/* Nitro and Games' embeds */
.theme-dark .tile-2OwFgW {
    background-color: var(--background-tertiary);
}
.theme-dark .tile-2OwFgW:hover {
    background-color: var(--background-floating);
}
.theme-dark .invalidPoop-pnUbq7 {
    background-color: rgba(62, 98, 101, 0.3);
}

/* ------------------------------------------------------------ 🌷 VOCAL ------------------------------------------------------------ */

/* ---- Watch Stream and Share Screen Button ---- */
.cta-3gK0Pu {
    background-color: var(--background-accent);
}
.cta-3gK0Pu:hover {
    background-color: var(--background-primary);
}

/* ---- Participant and Camera/Share Screen Buttons ---- */
.participantsButton-KYW-IW,
.colorable-1bkp8v.primaryDark-3mSFDl {
    background-color: var(--background-secondary);
}
.participantsButton-KYW-IW:hover,
.colorable-1bkp8v.primaryDark-3mSFDl:hover {
    background-color: var(--background-tertiary);
}

/* ---- Call Tiles ---- */
.videoWrapper-2v09vt,
.tile-2naSqK {
    background-color: var(--background-tertiary);
}

/* ------------------------------------------------------------ 🌱 SERVER SETTINGS ------------------------------------------------------------ */

/* ---- Save Changes Popout ---- */
.container-2VW0UT.elevationHigh-1PneE4[style] {
    background-color: #101019e6 !important;
}

/* ---- Roles ---- */
/* ColorPicker */
.colorPickerSwatch-5GX3Ve {
    border-radius: var(--border-radius-2) !important;
}

/* ---- Emojis ---- */
.card-FDVird::before {
    background-color: var(--background-secondary);
    border-color: var(--background-secondary-alt);
}
.emojiAliasInput-1y-NBz .emojiInput-1aLNse {
    background-color: var(--background-tertiary);
}

/* ---- Welcome Widgets ---- */
.exampleWumpus-1zk2dq .tooltip-1_vJJI {
    background-color: var(--background-floating);
}
.exampleWumpus-1zk2dq .tooltipPointer-1awMxk {
    border-right-color: var(--background-floating);
}
.exampleContainer-25sB-A {
    background-color: #312f66;
}

/* ---- Server Boost and Stickers Status ---- */
/* Bar */
.theme-dark .background-3xPPFc {
    color: var(--background-tertiary);
}
.theme-dark .tierInProgress-3mBoXq.tier-2c9-hT {
    background-color: var(--background-tertiary);
}
/* Level Containers */
.theme-dark .tierHeaderLocked-3S508x,
.theme-dark .tierHeaderUnlocked-3lTDnP {
    background-color: var(--background-tertiary);
}
.theme-dark .tierBody-3aUxuc {
    background-color: var(--background-secondary);
}

/* ---- Boost Page ---- */
/* Background */
.theme-dark .perksModal-fSYqOq {
    background-color: var(--background-primary);
}
/* Bar */
.theme-dark .tierMarkerBackground-3q29am {
    background-color: var(--background-primary);
}
.theme-dark .barBackground-2EEiLw {
    background-color: var(--background-tertiary);
}
.theme-dark .tierMarkerInProgress-24LMzJ.tierMarker-5HkGJ_ {
    background-color: var(--background-secondary) !important;
}
/* Level Containers */
.theme-dark .tierHeaderLocked-1s2JJz {
    background-color: var(--background-tertiary);
}
.theme-dark .tierBody-16Chc9 {
    background-color: var(--background-secondary);
}
/* Text Blocks */
.theme-dark .perk-2WeBWW {
    background-color: var(--background-secondary);
}

/* ------------------------------------------------------------ 🐻 PLUGINS ------------------------------------------------------------ */

/* ---- StaffTag ---- */
/* Admin Crown */
.ownerIcon-2NH9FM.icon-1A2_vz.admin-Kv1Hp_ {
    color: var(--grey);
}
/* Management Crown */
.ownerIcon-2NH9FM.icon-1A2_vz.management-3fF_o8 {
    color: var(--bronze);
}

/* ------------------------------------------------------------ 🍯 NITRO PAGE ------------------------------------------------------------ */

/* ---- Make Discord Yours ---- */
.hero-EvfTTA {
    background-image: url(https://kaiidoo.github.io/Newcord/assets/nitro/makeDiscordYours.svg) !important;
}

/* ---- More Backgrounds ---- */
[src="/assets/317438b1df555820dfaffad6074dbf72.svg"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/moreBackgrounds.svg) !important;
}

/* ---- Multiple Avatars ---- */
[src="/assets/485bd905b34331a9c8ffcf29049b1c97.png"] {
    content: url(https://imgur.com/nrX903e.png)
}

/* ---- Style Your Profile ---- */
[src="/assets/2a7b069c2413090d8e17fedbf1647280.png"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/styleYourProfile.svg) !important;
}

/* ---- Special Stickers Access ---- */
[src="/assets/360ca22059b6b674a018547e8e18acdc.svg"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/specialStickersAccess.svg) !important;
}
.stickers-1O9_W6 .featureTitle-W5O6R1 {
    text-transform: capitalize;
}

/* ---- More Emoji Power ---- */
[src="/assets/8e180c91237bcacc8b7ff5663262c1b7.svg"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/moreEmojiPower.svg) !important;
}

/* ---- Support Your Server ---- */
[src="/assets/46f302822fa43628962d28f50bb33b01.svg"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/supportYourServer.svg) !important;
}

/* ---- Rep Your Status ---- */
[src="/assets/487594776f6ebfe57e3ac89d6b3fe437.png"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/repYourStatus.svg) !important;
}

/* ---- Bigger Uploads ---- */
[src="/assets/0f67189cc579386633ab41a98088cc8e.png"] {
    content: url(https://imgur.com/okPlmip.png) !important;
}

/* ---- Longer Messages ---- */
[src="/assets/afc30837a86d8c6aaee02fdfa2787a11.svg"] {
    content: url(https://kaiidoo.github.io/Newcord/assets/nitro/longerMessages.svg) !important;
}

/* ---- More Servers ---- */
[src="/assets/39a7fb525b2593689d328ad7367ee4b5.png"] {
    content: url(https://imgur.com/N0dRCdy.png) !important;
}

/* ------------------------------------------------------------ 🌿 OTHERS ------------------------------------------------------------ */

/* ---- Explore ---- */
/* Background */
.theme-dark .pageWrapper-1PgVDX {
    background-color: var(--background-primary);
}
/* Main Image */
.searchHeader-2I26nG {
    padding-top: 30px;
}
/* Scrollbar */
.pageWrapper-1PgVDX {
    --scrollbar-auto-thumb: transparent;
    --scrollbar-auto-track: transparent;
}
/* Choose Language */
.css-1a1o7fb-control,
.css-p0ralp-control,
.css-2dw5y-control,
.css-bcsufo-menu {
    background-color: var(--background-tertiary);
}

/* ---- Nitro Tab ---- */
.homeWrapperNormal-2KSUEa .scrollerBase-289Jih {
    margin-bottom: 5px !important;
}

/* ---- Keyboard Combos ---- */
.keyboardShortcutsModal-3piNz7 {
    background-color: var(--background-primary);
}

/* ---- Color Picker ---- */
.theme-dark .colorPickerCustom-2CWBn2 {
    background: var(--background-primary);
    border-color: var(--background-tertiary);
    border-radius: var(--border-radius-3);
}

/* ---- Invite Popup ---- */
.theme-dark .contentWrapper-3WC1ID {
    background-color: var(--background-secondary);
}

/* ---- User Profile ---- */
.focusLock-Ns3yie .top-28JiJ- .item-PXvHYJ {
    border-radius: var(--border-radius-2);
    padding: 0 25px 0 25px;
    height: 30px;
    border: 0;
}
.tabBarItem-3dfX8P.item-PXvHYJ.selected-3s45Ha.themed-OHr7kt[aria-selected="true"] {
    background-color: var(--background-secondary) !important;
    color: var(--text-normal);
}
.body-r6_QPy {
    height: calc(100% - 150px);
}
.listRow-1iDGel {
    margin: 2px 8px;
    border-radius: var(--border-radius-2);
}
.textarea-2r0oV8:focus {
    background-color: var(--background-secondary);
    border-radius: var(--border-radius-3);
}
.lookInverted-2D7oAl .contents-18-Yxp {
    color: var(--interactive-selected);
}
.focusLock-Ns3yie .tabBarContainer-37hZsr {
    padding-right: 20px;
    border: none;
}
.root-3QyAh1,
.profileBanner-33-uE1,
.profileBannerPremium-35utuo,
.bannerOverlayProfile-31VOgt {
    width: 650px;
}
.root-3QyAh1 .tabBar-3nvOPa {
    justify-content: space-between;
}
.root-3QyAh1 .tabBarItem-3dfX8P:first-child:nth-last-child(2) {
    margin-left: 100px;
}
.root-3QyAh1
    .tabBarItem-3dfX8P:first-child:nth-last-child(2)
    ~ .tabBarItem-3dfX8P {
    margin-right: 100px;
}
.profileBanner-33-uE1 {
    height: 90px;
}
.userInfoSection-q_35fn {
    margin-top: -20px !important;
}
.userBio-3tlrzS {
    margin-bottom: 0;
}
.aboutMeSection---MkQa {
    padding-top: 16px;
}
.header-4zuFdR,
.customStatusActivity-nmH3DF {
    margin-left: 8px;
}
.nameTag-ECvD8P {
    margin-left: 24px;
}
.listScroller-3GmIYj {
    margin: 0 12px 12px 12px;
}
.userInfoSectionHeader-3TYk6R {
    margin-top: 8px;
}
.connectedAccounts-QlRa4m {
    padding-top: 12px;
}
.tabBarItem-3dfX8P {
    margin-right: 0px;
}

/* ---- User Accounts ---- */
.body-r6_QPy .userInfoSection-q_35fn {
    border-top: none;
}
.body-r6_QPy .userInfoSection-q_35fn .connectedAccounts-QlRa4m {
    justify-content: flex-start;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0 {
    position: relative;
    width: 110px;
    flex-direction: column;
    overflow: hidden;
    border: none;
    margin: 11px;
    padding: 10px;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg {
    position: relative;
    margin-top: 10px;
    margin-bottom: 10px;
    width: 40px;
    height: 40px;
    z-index: 2;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountNameInner-2q3MVf {
    position: relative;
    z-index: 1;
    width: 100%;
    justify-content: center;
    overflow: visible;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountNameInner-2q3MVf
    .connectedAccountName-E1KzaT {
    text-align: center;
    margin: 0;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountNameInner-2q3MVf
    span {
    display: none;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .anchor-3Z-8Bb {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: 2;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .anchor-3Z-8Bb
    > svg {
    display: none;
}
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg
    + .connectedAccountNameInner-2q3MVf::before {
    content: "";
    position: absolute;
    top: -65px;
    left: -10px;
    z-index: -1;
    width: 130px;
    height: 91px;
    border-radius: var(--border-radius-1);
    opacity: 0.25;
}
/* Twitch */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Twitch logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: var(--purple);
}
/* YouTube */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="YouTube logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: rgb(0, 174, 255);
}
/* Battle.net */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Battle.net logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #148eff;
}
/* Steam */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Steam logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: rgb(12, 57, 65);
}
/* Reddit */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Reddit logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #3796c2;
}
/* Facebook */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Facebook logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #1877f2;
}
/* Twitter */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Twitter logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #1da1f2;
}
/* Spotify */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Spotify logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #1ed7be;
}
/* Xbox Live */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="Xbox Live logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #107c6e;
}
/* GitHub */
.body-r6_QPy
    .userInfoSection-q_35fn
    .connectedAccounts-QlRa4m
    .connectedAccount-2Jb-Z0
    .connectedAccountIcon-3_EQqg[alt="GitHub logo"]
    + .connectedAccountNameInner-2q3MVf::before {
    background-color: #212121;
}

/* ---- Sliders / Switches ---- */
/* Classics */
.container-3auIfb[style*="opacity: 1; background-color: hsl(139, calc(var(--saturation-factor, 1) * 47.3%), 43.9%);"] {
    background-color: var(--green) !important;
}
/* BetterDiscord*/
.bd-switch input:checked + .bd-switch-body {
    --switch-color: var(--green);
}

/* ---- BetterDiscord Buttons ---- */
.bd-button,
.bd-addon-modal-footer .bd-button {
    background-color: var(--brand-experiment);
}
.bd-button:hover,
.bd-addon-modal-footer .bd-button:hover {
    background-color: var(--brand-experiment-560);
}
/* Title and Done */
.bd-button.bd-button-titlen,
.bd-addon-modal-footer .bd-button {
    border-radius: var(--border-radius-1);
}
/* List View */
.bd-button.bd-view-button.selected {
    background-color: var(--brand-experiment);
}
/* Addon */
.bd-controls > .bd-addon-button:first-of-type {
    border-radius: var(--border-radius-3) 0 0 5px;
}
/* Danger */
.bd-button.bd-button-danger {
    background-color: var(--red);
}
.bd-button.bd-button-danger:hover {
    background-color: var(--red2);
}
.bd-controls > .bd-addon-button:last-of-type {
    border-radius: 0 5px 5px 0;
}

/* ---- Close Button ---- */
.theme-dark .closeButton-1tv5uR {
    background-color: var(--background-secondary);
    transition: ease-out 0.25s;
}
.theme-dark .closeButton-1tv5uR:hover {
    background-color: var(--background-secondary-alt);
}
.closeButton-1tv5uR {
    border-color: var(--background-secondary-alt) !important;
}
.closeButton-1tv5uR > svg > path {
    fill: var(--interactive-muted);
    transition: ease-out 0.25s;
}
.closeButton-1tv5uR:hover > svg > path {
    fill: var(--interactive-active);
}
/* Esc */
.closeButton-1tv5uR:active {
    transform: translateY(0);
}
.theme-dark .keybind-KpFkfr {
    color: var(--interactive-muted);
}

/* ---- Servers Column ---- */
#app-mount .listItem-1hlISG,
#app-mount .scroller-1Bvpku .tutorialContainer-2sGCg9 {
    margin-top: 7px
}

/* ---- Select Lists ---- */
.css-3vaxre-menu,
.css-1x99fvh-menu,
.css-dwar6a-menu {
    background-color: var(--background-secondary);
    border-top: none;
    border-color: rgba(0, 0, 0, 0.6);
    box-shadow: none;
}
.css-17e1tep-control,
.css-17e1tep-control:hover,
.css-6fzn47-control,
.css-6fzn47-control:hover,
.css-gvi9bl-control,
.css-gvi9bl-control:hover,
.css-1yz4bi9-option,
.css-1yz4bi9-option:hover,
.css-rzbxvl-option,
.css-rzbxvl-option:hover {
    background-color: var(--background-secondary);
    transition: ease-out 0.25s;
}

/* ---- Cross ---- */
path[d="M7.02799 0.333252C3.346 0.333252 0.361328 3.31792 0.361328 6.99992C0.361328 10.6819 3.346 13.6666 7.02799 13.6666C10.71 13.6666 13.6947 10.6819 13.6947 6.99992C13.6947 3.31792 10.7093 0.333252 7.02799 0.333252ZM10.166 9.19525L9.22333 10.1379L7.02799 7.94325L4.83266 10.1379L3.89 9.19525L6.08466 6.99992L3.88933 4.80459L4.832 3.86259L7.02733 6.05792L9.22266 3.86259L10.1653 4.80459L7.97066 6.99992L10.166 9.19525Z"] {
    fill: var(--red);
}

/* ---- Keyboard Combos Popup ---- */
.theme-dark .keyboardShortcutsModal-3piNz7 {
    background-color: var(--background-primary);
}

/* ---- Help Button ---- */
:root [href="https://support.discord.com"], :root .searchLearnMore-3SQUAj .anchor-3Z-8Bb.anchorUnderlineOnHover-2ESHQB
{
    display: none;
}

/* ---- Verification Page ---- */
.theme-dark .verificationBlock-1Chfpc {
    border-color: var(--background-tertiary);
}
.theme-dark .verificationBlock-1Chfpc:hover {
    background-color: var(--background-tertiary);
}

/* ---- Code ---- */
.theme-dark .markdown-11q6EU code {
    background-color: var(--background-secondary);
}
