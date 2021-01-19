:root {
  --accent-color: #f08080;
  --accent-hover: #ffa3a5;
  --accent-rgb: 255, 130, 132;
  --alt-accent: #ff8284;
  --alert-color: #f04747;
  --alert-hover: #ff4c4c;
  --chat-color: #242424;
  --chat-box-color: #272727;
  --side-color: #1e1e1e;
  --bar-color: #282828;
  /*--button-background: #1a1a1a;*/
  --button-background: rgba(0,0,0,0.2);
  --button-border: 1px solid #b2b2b2;
  --button-border-hover: 1px solid #fff;
  --card-color: rgba(255,255,255,0.05);
  --card-border: var(--bar-color);
  --card-radius: 8px;
  --slider-color: #b3b3b3;
  --slider-background: var(--menu-border-color);
  --popout-color: var(--bar-color);
  --popout-radius: 7px;
  --menu-hover-color: #424242;
  --menu-hover-color-alt: #252525;
  --menu-select-color: #4d4d4d;
  --menu-border-color: #424242;
  --menu-text-color: #b2b2b2;
  --input-bg: #e0e0e0;
  --input-text-color: #222;
  --input-placeholder-color: #444;
  --select-input-color: #363636;
  --textarea-radius: 22px;
  --checkbox-border-checked: transparent;
  --checkbox-border-unchecked: var(--menu-border-color);
  --checkbox-checked: #fff;
  --checkbox-unchecked: #9f9f9f;
  --default-shadow: 0 7px 18px rgba(0,0,0,0.25), 0 6px 10px rgba(0,0,0,0.25), 0 -2px 10px rgba(0,0,0,0.25), 0 0 15px rgba(0,0,0,0.25);
  --scrollbar-track: #1e1e1e;
  --scrollbar-thumb: #535353;
  --scrollbar-thumb-hover: #b3b3b3; 
/* Radial Status */
  --rs-small-spacing: 2px;
  --rs-large-spacing: 3px;
  --rs-width: 2px;
  --rs-avatar-shape: 8%;
  --rs-online-color: #63ffd0;
  --rs-idle-color: #fcf597;
  --rs-dnd-color: #ff8284;
  --rs-offline-color: #636b75;
  --rs-streaming-color: #a8b0ff;
  --rs-invisible-color: #747f8d;}

::selection {
  background: rgba(var(--accent-rgb), 0.3);
  color: #fff !important;
  text-shadow: none; }

#app-mount .wrapper-3t9DeA svg:not(:root) {
  overflow: visible;
}
#app-mount .wrapper-3t9DeA foreignObject {
  -webkit-mask: none;
          mask: none;
}
#app-mount .wrapper-3t9DeA .dots-3Bkt3k circle:nth-child(1) {
  cy: -8 !important;
  cx: -8.5 !important;
}
#app-mount .wrapper-3t9DeA .dots-3Bkt3k circle:nth-child(2) {
  cy: -8 !important;
  cx: -2.25 !important;
}
#app-mount .wrapper-3t9DeA .dots-3Bkt3k circle:nth-child(3) {
  cy: -8 !important;
  cx: 4 !important;
}
#app-mount .wrapper-3t9DeA .mask-1l8v16 > rect[x="22"] {
  x: 0;
  y: 0;
}
#app-mount .wrapper-3t9DeA .cursorDefault-dsQJ1n rect {
  x: -49;
  y: -53;
}
#app-mount .wrapper-3t9DeA .pointerEvents-2zdfdO[x="14.5"] {
  fill: rgba(0, 0, 0, 0.5) !important;
  width: 30px;
  height: 30px;
  x: 1;
  y: 1;
}
#app-mount .wrapper-3t9DeA > svg > foreignObject img {
  border-radius: var(--rs-avatar-shape);
}
#app-mount .wrapper-3t9DeA > svg > foreignObject:not(:only-child) img {
  -webkit-clip-path: inset(calc(var(--rs-small-spacing) + 1px) calc(var(--rs-small-spacing) + 1px) round var(--rs-avatar-shape));
          clip-path: inset(calc(var(--rs-small-spacing) + 1px) calc(var(--rs-small-spacing) + 1px) round var(--rs-avatar-shape));
}
#app-mount .wrapper-3t9DeA svg[width="25"][height="15"] > rect {
  rx: calc(var(--rs-avatar-shape) * 2) !important;
  ry: calc(var(--rs-avatar-shape) * 2) !important;
}
#app-mount .wrapper-3t9DeA rect {
  x: 0;
  y: 0;
  width: 100%;
  height: 100%;
  -webkit-mask: none;
          mask: none;
  display: block !important;
  rx: var(--rs-avatar-shape) !important;
  ry: var(--rs-avatar-shape) !important;
  fill: transparent !important;
  stroke-width: var(--rs-width);
}
#app-mount .wrapper-3t9DeA rect[fill="#43b581"], #app-mount .wrapper-3t9DeA rect[fill="rgba(67, 181, 129, 1)"], #app-mount .wrapper-3t9DeA rect[mask*=online] {
  stroke: var(--rs-online-color);
}
#app-mount .wrapper-3t9DeA rect[fill="#faa61a"], #app-mount .wrapper-3t9DeA rect[fill="rgba(250, 166, 26, 1)"], #app-mount .wrapper-3t9DeA rect[mask*=idle] {
  stroke: var(--rs-idle-color);
}
#app-mount .wrapper-3t9DeA rect[fill="#f04747"], #app-mount .wrapper-3t9DeA rect[fill="rgba(240, 71, 71, 1)"], #app-mount .wrapper-3t9DeA rect[mask*=dnd] {
  stroke: var(--rs-dnd-color);
}
#app-mount .wrapper-3t9DeA rect[fill="#593695"], #app-mount .wrapper-3t9DeA rect[mask*=streaming] {
  stroke: var(--rs-streaming-color);
}
#app-mount .wrapper-3t9DeA rect[fill="#747f8d"], #app-mount .wrapper-3t9DeA rect[mask*=offline], #app-mount .wrapper-3t9DeA rect[fill=NaN] {
  stroke: var(--rs-offline-color);
}
#app-mount .wrapper-3t9DeA rect[mask*=invisible], #app-mount .wrapper-3t9DeA rect[fill="rgba(116, 127, 141, 1)"] {
  stroke: var(--rs-invisible-color);
}
#app-mount .wrapper-3t9DeA rect[x="16"] {
  width: 24px;
  height: 24px;
}
#app-mount .wrapper-3t9DeA rect[x="28"] {
  width: 40px;
  height: 40px;
  overflow: visible;
}
#app-mount .wrapper-3t9DeA[style*="width: 80px;"] {
  position: relative;
  margin-right: 0 !important;
}
#app-mount .wrapper-3t9DeA[style*="width: 80px;"] rect {
  width: 80px;
  height: 80px;
  pointer-events: none;
}
#app-mount .wrapper-3t9DeA[style*="width: 80px;"] img {
  -webkit-clip-path: inset(calc(var(--rs-large-spacing) + 1px) calc(var(--rs-large-spacing) + 1px) round var(--rs-avatar-shape));
          clip-path: inset(calc(var(--rs-large-spacing) + 1px) calc(var(--rs-large-spacing) + 1px) round var(--rs-avatar-shape));
}
#app-mount .wrapper-3t9DeA[style*="width: 80px;"][style*="width:80px;"]:after {
  left: unset;
  right: -2px;
  top: unset;
  bottom: -2px;
  transform: none;
}
#app-mount .wrapper-3t9DeA[style*="width: 32px;"] rect {
  width: 32px;
  height: 32px;
  x: -14.5;
  y: -17;
  position: relative;
  z-index: 0;
}
#app-mount .avatarHint-1qgaV3 foreignObject {
  -webkit-mask: none;
          mask: none;
}
#app-mount .avatarHint-1qgaV3 .avatarHintInner-Dco91E {
  border-radius: var(--rs-avatar-shape) !important;
  padding-top: 0;
  width: calc(100% - var(--rs-width) * 4);
  height: calc(100% - var(--rs-width) * 4);
  margin-top: calc(var(--rs-width) + 2px);
  margin-left: calc(var(--rs-width) + 2px);
}
#app-mount .message-1PNnaP .mask-1l8v16 img {
  -webkit-clip-path: circle(calc(19px - var(--rs-small-spacing)));
          clip-path: circle(calc(19px - var(--rs-small-spacing)));
}
#app-mount .memberOffline-2lN7gt img {
  -webkit-clip-path: none !important;
          clip-path: none !important;
}
#app-mount .header-QKLPzZ .wrapper-3t9DeA {
  margin-right: 20px !important;
}
#app-mount .offline-3nJYBR img {
  -webkit-clip-path: none !important;
          clip-path: none !important;
}

#app-mount .wrapper-3t9DeA foreignObject[mask*=mobile] {
  width: calc(100% + 4px);
}
#app-mount .wrapper-3t9DeA foreignObject[mask*=mobile][width="32"] img {
  width: 32px;
}
#app-mount .wrapper-3t9DeA foreignObject[mask*=mobile][width="80"] img {
  width: 80px;
}
#app-mount .wrapper-3t9DeA foreignObject[mask*=mobile]:after {
  content: "";
  -webkit-mask: url('data:image/svg+xml; utf-8,<svg aria-hidden="true" focusable="false" data-prefix="fas" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path fill="currentColor" d="M272 0H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h224c26.5 0 48-21.5 48-48V48c0-26.5-21.5-48-48-48zM160 480c-17.7 0-32-14.3-32-32s14.3-32 32-32 32 14.3 32 32-14.3 32-32 32zm112-108c0 6.6-5.4 12-12 12H60c-6.6 0-12-5.4-12-12V60c0-6.6 5.4-12 12-12h200c6.6 0 12 5.4 12 12v312z"></path></svg>') center/8px no-repeat;
  display: block;
  position: absolute;
  width: 10px;
  height: 14px;
  top: 50%;
  transform: translateY(-50%);
  right: 0;
  background: var(--rs-online-color);
  z-index: 1;
}

#app-mount .wrapper-3t9DeA:before {
  content: none !important;
}

/*
 *
 *	APP
 *
 */
.appMount-3lHmkl {
  background: var(--chat-color); }

.titleBar-AC4pGV {
  z-index: 1 !important; }

.typeWindows-1za-n7 {
  margin: 0;
  padding: 4px 0 0 0;
  background: #0c0c0c; }

.sidebar-2K8pFh {
  border-radius: 0 !important;
  z-index: 2; }

.closeButton-1tv5uR {
  background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Ik0xOSw2LjQxTDE3LjU5LDVMMTIsMTAuNTlMNi40MSw1TDUsNi40MUwxMC41OSwxMkw1LDE3LjU5TDYuNDEsMTlMMTIsMTMuNDFMMTcuNTksMTlMMTksMTcuNTlMMTMuNDEsMTJMMTksNi40MVoiIC8+Cjwvc3ZnPg==) no-repeat 50%;
  background-size: 60%;
  border: 1px solid #fff !important; }
  .closeButton-1tv5uR:hover {
    background-color: transparent !important;
    transform: scale(1.075); }
  .closeButton-1tv5uR:active, .closeButton-1tv5uR:active:hover {
    transform: scale(1) translateY(0); }
  .closeButton-1tv5uR:active:hover {
    opacity: 0.6; }
  .closeButton-1tv5uR svg {
    display: none; }

/* APP -> LINKS */
a,
.lookLink-9FtZy-.colorLink-35jkBc,
.bda-slist .bda-footer a {
  color: var(--accent-color); }

.anchor-3Z-8Bb {
  color: var(--accent-color) !important; }

/* APP -> LOGIN */
.authBox-hW6HRx {
  border-radius: var(--border-radius-big) !important; }

/*
 *
 *	TITLE BAR
 *
 */
.container-1r6BKw.themed-ANHk51 {
  background: var(--side-color); }

.title-3qD0b- .flex-1xMQg5 {
  position: relative !important; }
  .title-3qD0b- .flex-1xMQg5 div:not([class]) {
    position: relative;
    width: 72px;
    height: 26px;
    margin: 0;
    padding: 0; }
    .title-3qD0b- .flex-1xMQg5 div:not([class]) .iconMargin-2YXk4F {
      position: absolute; }
      .title-3qD0b- .flex-1xMQg5 div:not([class]) .iconMargin-2YXk4F:last-child {
        right: 8px; }

.iconMargin-2YXk4F {
  width: 26px;
  height: 26px;
  margin: 0 2px 0 0;
  border-radius: 50%;
  opacity: 0.6; }
  .iconMargin-2YXk4F:last-child {
    margin: 0; }
  .iconMargin-2YXk4F:hover {
    opacity: 1; }

.icon-1R19_H {
  width: 22px;
  height: 22px;
  margin: 2px 0 0 2px;
  opacity: 1; }
  .icon-1R19_H:hover {
    opacity: 1; }

.iconBadge-2dji3k {
  top: -4px;
  right: -2px;
  background-color: var(--alt-accent);
  border-color: var(--side-color) !important; }

.search-l1Wz-Q {
  margin: 0 8px 0 6px; }

.divider-2PMBlV {
  display: none; }

.children-19S4PO:after {
  display: none; }

/* TITLE BAR -> SEARCH BAR */
.search-bar-icon .icon.visible {
  opacity: 0.75; }

.search .search-bar .search-bar-icon .icon.icon-search-bar-eye-glass {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCI+CiAgPGcgZmlsbD0ibm9uZSIgZmlsbC1ydWxlPSJldmVub2RkIj4KICAgIDxwYXRoIGQ9Ik0wIDBoMTh2MThIMHoiLz4KICAgIDxwYXRoIGZpbGw9IiMwMDAwMDAiIGQ9Ik0zLjYwMDkxNDggNy4yMDI5NzMxM2MwLTEuOTkzMTM4OTQgMS42MDg5MTk0LTMuNjAyMDU4MzIgMy42MDIwNTgzMy0zLjYwMjA1ODMyIDEuOTkzMTM4OTMgMCAzLjYwMjA1ODI3IDEuNjA4OTE5NCAzLjYwMjA1ODI3IDMuNjAyMDU4MzQgMCAxLjk5MzEzODkzLTEuNjA4OTE5MzQgMy42MDIwNTgyNy0zLjYwMjA1ODI3IDMuNjAyMDU4MjctMS45OTMxMzg5NCAwLTMuNjAyMDU4MzItMS42MDg5MTkzMy0zLjYwMjA1ODMyLTMuNjAyMDU4MjZ6bTguNDA0ODAyOCAzLjYwMjA1ODI3aC0uNjMyMzYxNGwtLjIyNDEyODEtLjIxNjEyMzVjLjc4NDQ0ODMtLjkxMjUyMTQgMS4yNTY3MTgyLTIuMDk3MTk4MzUgMS4yNTY3MTgyLTMuMzg1OTM0NzdDMTIuNDA1OTQ2MyA0LjMyOTMzMTA1IDEwLjA3NjYxNTIgMiA3LjIwMjk3MzEzIDIgNC4zMjkzMzEwNSAyIDIgNC4zMjkzMzEwNSAyIDcuMjAyOTczMTNjMCAyLjg3MzY0MjA3IDIuMzI5MzMxMDUgNS4yMDI5NzMxNyA1LjIwMjk3MzEzIDUuMjAyOTczMTcgMS4yODg3MzY0MiAwIDIuNDczNDEzMzgtLjQ3MjI2OTkgMy4zODU5MzQ3Ny0xLjI1NjcxODJsLjIxNjEyMzUuMjI0MTI4MXYuNjMyMzYxNEwxNC44MDczMTg1IDE2IDE2IDE0LjgwNzMxODVsLTMuNzg5NzQ2Mi0zLjc5NzM0MDktLjIwNDUzNjItLjIwNDk0NjJ6Ii8+CiAgPC9nPgo8L3N2Zz4=) !important; }

.search .search-bar .search-bar-icon .icon.icon-search-bar-clear {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxOCIgaGVpZ2h0PSIxOCIgdmlld0JveD0iMCAwIDE4IDE4Ij4KICA8ZyBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPgogICAgPHJlY3Qgd2lkdGg9IjE4IiBoZWlnaHQ9IjE4Ii8+CiAgICA8cGF0aCBmaWxsPSIjMDAwMDAwIiBkPSJNOSwyIEMxMi44NzEsMiAxNiw1LjEyOSAxNiw5IEMxNiwxMi44NzEgMTIuODcxLDE2IDksMTYgQzUuMTI5LDE2IDIsMTIuODcxIDIsOSBDMiw1LjEyOSA1LjEyOSwyIDksMiBMOSwyIFogTTExLjY5MjUsNS4yNSBMOSw3Ljk0MjUgTDYuMzA3NSw1LjI1IEw1LjI1LDYuMzA3NSBMNy45NDI1LDkgTDUuMjUsMTEuNjkyNSBMNi4zMDc1LDEyLjc1IEw5LDEwLjA1NzUgTDExLjY5MjUsMTIuNzUgTDEyLjc1LDExLjY5MjUgTDEwLjA1NzUsOSBMMTIuNzUsNi4zMDc1IEwxMS42OTI1LDUuMjUgWiIvPgogIDwvZz4KPC9zdmc+) !important; }

/* TITLE BAR -> ICONS */
/* TITLE BAR -> ICONS -> VOICE CALL */
.iconWrapper-2OrFZ1[aria-label="Start Voice Call"] .icon-22AiRD path {
  d: path("M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z") !important; }

/* TITLE BAR -> ICONS -> VIDEO CALL */
.iconWrapper-2OrFZ1[aria-label="Start Video Call"] .icon-22AiRD path {
  d: path("M17 10.5V7c0-.55-.45-1-1-1H4c-.55 0-1 .45-1 1v10c0 .55.45 1 1 1h12c.55 0 1-.45 1-1v-3.5l4 4v-11l-4 4z") !important; }

/* TITLE BAR -> ICONS -> PINNED MESSAGES */
.iconWrapper-2OrFZ1[aria-label="Pinned Messages"] .icon-22AiRD path {
  d: path("M16,12V4H17V2H7V4H8V12L6,14V16H11.2V22H12.8V16H18V14L16,12Z") !important; }

/* TITLE BAR -> ICONS -> CREATE GROUP DM */
.icon-22AiRD[name="Nova_ChatNew"] path {
  d: path("M8 10H5V7H3v3H0v2h3v3h2v-3h3v-2zm10 1c1.66 0 2.99-1.34 2.99-3S19.66 5 18 5c-.32 0-.63.05-.91.14.57.81.9 1.79.9 2.86s-.34 2.04-.9 2.86c.28.09.59.14.91.14zm-5 0c1.66 0 2.99-1.34 2.99-3S14.66 5 13 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm6.62 2.16c.83.73 1.38 1.66 1.38 2.84v2h3v-2c0-1.54-2.37-2.49-4.38-2.84zM13 13c-2 0-6 1-6 3v2h12v-2c0-2-4-3-6-3z") !important; }

/* TITLE BAR -> ICONS -> ADD FRIENDS TO DM */
.iconWrapper-2OrFZ1[aria-label="Add Friends to DM"] .icon-22AiRD path {
  d: path("M15 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm-9-2V7H4v3H1v2h3v3h2v-3h3v-2H6zm9 4c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z") !important; }

/* TITLE BAR -> ICONS -> UNMUTED CHANNEL */
.iconWrapper-2OrFZ1[aria-label*="Mute channel"][aria-checked="false"] .icon-22AiRD path {
  d: path("M12 22c1.1 0 2-.9 2-2h-4c0 1.1.89 2 2 2zm6-6v-5c0-3.07-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.63 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2z") !important; }

/* TITLE BAR -> ICONS -> MUTED CHANNEL */
.iconWrapper-2OrFZ1[aria-label*="Mute channel"][aria-checked="true"] .icon-22AiRD path {
  display: none; }

.iconWrapper-2OrFZ1[aria-label*="Mute channel"][aria-checked="true"] .icon-22AiRD path:last-child {
  display: block;
  d: path("M20 18.69L7.84 6.14 5.27 3.49 4 4.76l2.8 2.8v.01c-.52.99-.8 2.16-.8 3.42v5l-2 2v1h13.73l2 2L21 19.72l-1-1.03zM12 22c1.11 0 2-.89 2-2h-4c0 1.11.89 2 2 2zm6-7.32V11c0-3.08-1.64-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68c-.15.03-.29.08-.42.12-.1.03-.2.07-.3.11h-.01c-.01 0-.01 0-.02.01-.23.09-.46.2-.68.31 0 0-.01 0-.01.01L18 14.68z") !important; }

/* TITLE BAR -> ICONS -> MEMBER LIST */
.iconWrapper-2OrFZ1[aria-label="Member List"] .icon-22AiRD path {
  display: none; }

.iconWrapper-2OrFZ1[aria-label="Member List"] .icon-22AiRD path:first-child {
  display: block;
  d: path("M16 11c1.66 0 2.99-1.34 2.99-3S17.66 5 16 5c-1.66 0-3 1.34-3 3s1.34 3 3 3zm-8 0c1.66 0 2.99-1.34 2.99-3S9.66 5 8 5C6.34 5 5 6.34 5 8s1.34 3 3 3zm0 2c-2.33 0-7 1.17-7 3.5V19h14v-2.5c0-2.33-4.67-3.5-7-3.5zm8 0c-.29 0-.62.02-.97.05 1.16.84 1.97 1.97 1.97 3.45V19h6v-2.5c0-2.33-4.67-3.5-7-3.5z") !important; }

/*
 *
 *	SERVERS/GUILD LIST
 *
 */
.wrapper-1Rf91z {
  width: 72px;
  height: calc(100% - 72px);
  background: var(--chat-color) !important; }
  .wrapper-1Rf91z:after {
    position: fixed;
    content: " ";
    width: 100%;
    height: 72px;
    left: 0;
    bottom: 0;
    background: var(--bar-color); }

.scroller-2TZvBN {
  background: transparent; }
  .scroller-2TZvBN::-webkit-scrollbar {
    width: 0px !important; }

.container-2td-dC:nth-child(2) .guildInner-3DSoA4 {
  background: transparent;
  border-radius: 0 !important; }
  .container-2td-dC:nth-child(2) .guildInner-3DSoA4 a {
    height: 20px; }
    .container-2td-dC:nth-child(2) .guildInner-3DSoA4 a div {
      font-weight: 500;
      font-size: 10px !important;
      text-transform: uppercase;
      color: rgba(255, 255, 255, 0.3); }
.container-2td-dC:nth-child(2):hover .guildInner-3DSoA4 {
  background: var(--menu-hover-color); }

.wrapper-1BJsBx.selected-bZ3Lue .childWrapper-anI2G9,
.wrapper-1BJsBx:hover .childWrapper-anI2G9 {
  background-color: var(--accent-color); }

.container-2td-dC.selected-nT-gM3:before {
  height: 75%;
  top: 0;
  bottom: 0;
  margin: auto 0;
  background: var(--accent-color) !important;
  opacity: 1 !important; }

.dragPlaceholder-D9-haY {
  background: var(--card-border) !important;
  border: none !important; }

.audio-2KA0-x:after,
.video-2jNDI4:after {
  top: 0;
  right: 0;
  background-color: var(--accent-color) !important;
  box-shadow: var(--default-shadow); }

.guildsError-3cFMtY.anchor-3Z-8Bb {
  color: var(--alert-color) !important;
  transition: none; }

.guildsError-3cFMtY.anchor-3Z-8Bb:hover {
  color: #fff !important; }

.wrapper-232cHJ,
.mention-1f5kbO {
  background-color: var(--alt-accent); }

.numberBadge-2s8kKX {
  background-color: var(--alt-accent) !important; }

/* SERVERS/GUILD LIST -> SERVER FOLDERS */
.folderIconWrapper-226oVY[style="background-color: rgba(114, 137, 218, 0.4);"] {
  background-color: rgba(var(--accent-rgb), 0.3) !important; }

.expandedFolderBackground-2sPsd- {
  /*background-color: rgba(var(--accent-rgb),0.3);*/
  border-radius: 16px 16px 24px 24px; }

.folder-21wGz3,
.folder-21wGz3.hover-2ji_A7 {
  background-color: transparent; }

/* SERVERS/GUILD LIST -> ADD SERVER */
.createJoinContainer-2Av064 {
  position: relative;
  margin: 20px 0 0 0; }
  .createJoinContainer-2Av064:before {
    position: absolute;
    content: " ";
    width: 30px;
    height: 2px;
    top: -10px;
    left: 10px;
    background: #2f3136; }
  .createJoinContainer-2Av064 .circleIconButton-jET_ig {
    position: absolute;
    background: var(--button-background);
    border: 1px solid #fff;
    color: #fff; }
    .createJoinContainer-2Av064 .circleIconButton-jET_ig:hover {
      transform: scale(1.075); }
    .createJoinContainer-2Av064 .circleIconButton-jET_ig.selected-ugP_am {
      background-color: var(--accent-color); }

.circleIconButton-jET_ig {
  color: var(--accent-color); }

/* SERVERS/GUILD LIST -> SERVER DISCOVERY */
.container-11WMXy {
  position: fixed;
  width: 72px;
  height: 72px;
  bottom: 0;
  left: 0;
  margin: 0 !important;
  background: var(--bar-color) !important;
  border-radius: 0;
  border: none; }
  .container-11WMXy .circleIconButton-jET_ig {
    position: relative;
    display: block;
    width: 50px;
    height: 50px;
    top: 10px;
    bottom: 0;
    margin: auto;
    background: var(--button-background);
    line-height: 44px;
    border-radius: 50%;
    border: 1px solid #fff;
    color: #fff;
    font-size: 1em; }
    .container-11WMXy .circleIconButton-jET_ig:hover {
      transform: scale(1.075); }
    .container-11WMXy .circleIconButton-jET_ig svg {
      position: absolute;
      width: 24px;
      height: 24px;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      margin: auto; }

/* SERVERS/GUILD LIST -> SERVER DISCOVERY */
.guildsDiscover-oiBX_l {
  position: relative;
  width: 50px;
  height: 50px;
  margin: 8px 0 0 0 !important;
  background: #2f3136 !important;
  border-radius: 25px;
  transition: 250ms ease all; }

@keyframes server-hover {
  0% {
    border-radius: 25px; }
  35% {
    border-radius: 12px; }
  55% {
    border-radius: 16px; }
  90% {
    border-radius: 14px; }
  100% {
    border-radius: 15px; } }
.guildsDiscover-oiBX_l:not(.selected-ML3OIq):hover {
  animation: server-hover 600ms cubic-bezier(0.4, 0, 0.2, 1);
  border-radius: 15px; }

.guildsDiscover-oiBX_l.selected-ML3OIq {
  border-radius: 15px; }

.guildsDiscoverInner-wC7iEN path {
  fill: #fff !important; }

/*
 *
 *	CREATE/JOIN SERVER
 *
 */
/* CREATE/JOIN SERVER -> CREATE SERVER */
.theme-light {
  --header-primary: #fff;
  --header-secondary: #b9bbbe;
  --text-normal: #dcddde;
  --text-muted: #b9bbbe;
  --interactive-normal: #b9bbbe;
  --channels-default: #8e9297; }

.container-1CE3eW .header-1TKi98 {
  padding: 12px 21px 0; }

.container-UC8Ug1 {
  background-color: var(--menu-hover-color);
  border-radius: var(--popout-radius); }
  .container-UC8Ug1:hover {
    background-color: var(--menu-select-color); }

.input--jS-j2 {
  background-color: transparent; }

.container-1CE3eW .lookBlank-3eh9lL {
  color: var(--text-normal); }

/* CREATE/JOIN SERVER -> CREATE SERVER -> SELECT REGION */
.regionSelectModal-12e-57 .regionSelectModalHeader-21khC1 {
  color: var(--accent-color); }

.regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3 {
  background: transparent;
  border-radius: var(--popout-radius);
  border: 1px solid #444; }
  .regionSelectModal-12e-57 .regionSelectModalOption-2DSIZ3:hover {
    border-color: var(--accent-color); }

/*
 *
 *	SERVER OPTIONS
 *
 */
.menu-3sdvDG {
  padding: 6px 0;
  background: var(--popout-color);
  border-radius: 0;
  box-shadow: var(--default-shadow); }
  .menu-3sdvDG .scroller-3BxosC {
    padding: 0; }
    .menu-3sdvDG .scroller-3BxosC::-webkit-scrollbar {
      width: 0; }

/* SERVER OPTIONS -> OPTION */
.scroller-3BxosC::-webkit-scrollbar {
  width: 0 !important; }

.item-1tOPte {
  position: relative;
  margin: 0;
  padding: 6px 11px;
  border-radius: 0;
  font-size: 14px;
  color: var(--menu-text-color);
  font-weight: 400; }
  .item-1tOPte:hover:not(.hideInteraction-1iHO1O) {
    background-color: var(--menu-hover-color); }
  .item-1tOPte.focused-3afm-j {
    background: transparent;
    color: var(--menu-text-color); }

.separator-2I32lJ {
  width: 100%;
  margin: 4px 0;
  border-color: var(--menu-border-color); }

.menu-3sdvDG .label-22pbtT {
  margin-left: 23px; }

.iconContainer-2-XQPY {
  position: absolute;
  transform: scale(0.889);
  margin: 0; }

/*
 *
 *	CHANNELS LIST
 *
 */
.container-3w7J-x,
.channels-Ie2l6A {
  background: var(--side-color) !important; }

.header-2V-4Sw {
  box-shadow: none; }

.content-yTz4x3:before {
  display: none; }

.chatContent-a9vAAp:before {
  position: absolute;
  content: " ";
  top: 0;
  left: 0;
  width: 100%;
  height: 1px;
  background-color: var(--card-border);
  z-index: 2; }

.clickable-25tGDB .header-2V-4Sw:hover,
.selected-31Nl7x .header-2V-4Sw {
  background-color: transparent; }

.channelNotices-41mJbj .channelNotice-1-XFjC.invite-OjTXrW,
.channelNotices-3AUnoM .channelNotice-cQsVXw.lfg-3h9KFj,
.channelNotices-3AUnoM .channelNotice-cQsVXw.quickswitcher-3-ck0i,
.channelNotices-41mJbj .channelNotice-1-XFjC.quickswitcher-35bYg4 {
  border-bottom: 1px solid var(--card-border) !important; }

.channelNotices-41mJbj .channelNotice-1-XFjC.invite-OjTXrW,
.channelNotices-3AUnoM .channelNotice-cQsVXw.lfg-3h9KFj {
  background: var(--side-color) url(https://discordapp.com/assets/bf625d222187f542b9d7179109422e2c.svg) no-repeat center 20px !important; }

.channelNotices-3AUnoM .channelNotice-cQsVXw.quickswitcher-3-ck0i,
.channelNotices-41mJbj .channelNotice-1-XFjC.quickswitcher-35bYg4 {
  background: var(--side-color) url(https://discordapp.com/assets/8fdb69b7684b8e1ecb3fdde909daca41.svg) no-repeat center 35px !important; }

.containerDefault--pIXnN.selected-3LIHYU .content-1x5b-n,
.wrapper-2jXpOf:hover .content-1x5b-n {
  background-color: transparent !important; }

.contentSelectedText-3wUhMi:active {
  margin: 1px 0;
  padding: 0 8px 0 16px; }

.contentSelectedText-3wUhMi:active:before {
  height: calc(65% + 2px); }

.contentSelectedText-3wUhMi:before,
.selected-aXhQR6.container-2Pjhx-:before,
.containerDefault--pIXnN.selected-3LIHYU .content-1x5b-n:before {
  content: " ";
  position: absolute;
  width: 4px;
  height: 65%;
  top: 0;
  left: -8px;
  bottom: 0;
  margin: auto 0;
  background: var(--accent-color); }

.wrapper-2jXpOf.modeUnread-1zpFdA .name-3_Dsmg {
  color: #eee !important; }

.wrapper-2jXpOf.modeSelected-1zApJ_ .name-3_Dsmg,
.wrapper-2jXpOf:hover .name-3_Dsmg,
.nameHoveredText-1uO31y {
  color: #fff !important; }

.wrapper-2NJDcI {
  margin: 0 0 0 6px;
  background: var(--alt-accent);
  border-radius: 8px;
  color: #fff;
  font-family: sans-serif; }

.unread-1xRYoj {
  background-color: var(--accent-color); }

/* CHANNELS LIST -> VOICE CONNECTED */
.container-1UB9sr,
.container-1giJp5 {
  position: relative;
  background: #141414 !important;
  border: none; }

.panel-24C3ux {
  background: #141414 !important;
  border-bottom: none; }

.container-1giJp5 + .panel-24C3ux {
  border-top: 1px solid var(--card-border); }

.container-1giJp5 .actionButtons-14eAc_ .lookFilled-1Gx00P.colorBrand-3pXr91 {
  padding: 0 !important; }

/* CHANNELS LIST -> VOICE CONNECTED -> ACTIVITY HOVER */
.container-3JTnYm {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

/* CHANNELS LIST -> VOICE CONNECTED -> NOISE SUPPRESSION */
.noiseCancellationPopout-iRK2A0 {
  background: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

.noiseCancellationPopout-iRK2A0 .lookFilled-1Gx00P.colorGrey-2DXtkV {
  padding: 0 !important; }

/* CHANNELS LIST -> VOICE CONNECTED -> LISTENING TO SPOTIFY */
.container-2dqNWc {
  background-color: var(--popout-color);
  border-radius: 0;
  box-shadow: var(--default-shadow); }

/* CHANNELS LIST -> EDIT CHANNEL */
/* CHANNELS LIST -> EDIT CHANNEL -> PERMISSIONS */
.card-4s8auQ {
  padding: 0 0 16px; }

.advancedModeDivider-GJCGg1 {
  margin: 20px 0; }

.settingCard-3w2mVL.active-1ytUzX {
  background-color: transparent; }
.settingCard-3w2mVL .cardContent-qqqwo8 {
  padding: 0;
  padding-top: 16px; }
.settingCard-3w2mVL .cardFolder-28dwxo {
  background-color: transparent; }
.settingCard-3w2mVL .adminWarning-3Ie8tf,
.settingCard-3w2mVL .folderHeader-3eAh2M {
  padding: 16px 0; }
.settingCard-3w2mVL .roleMemberList-3aPmJW {
  padding: 0 0 16px;
  padding-right: 0 !important; }
.settingCard-3w2mVL .divider-3573oO {
  margin-bottom: 16px;
  padding-bottom: 0; }

/*
 *
 *	MEMBERS LIST
 *
 */
.member-3W1lQa {
  margin: 1px 0;
  border-radius: 0; }
  .member-3W1lQa:hover .content-OzHfo4, .member-3W1lQa.popout-open .content-OzHfo4, .member-3W1lQa.popout-open:hover .content-OzHfo4 {
    background: transparent !important; }
  .member-3W1lQa .content-OzHfo4 {
    position: relative;
    padding: 0 16px; }
  .member-3W1lQa.memberOffline-2lN7gt {
    filter: grayscale(1);
    opacity: 0.75; }
    .member-3W1lQa.memberOffline-2lN7gt.popout-open {
      filter: grayscale(0); }
  .member-3W1lQa.popout-open .content-OzHfo4:after {
    content: " ";
    position: absolute;
    width: 4px;
    height: 90%;
    background: var(--accent-color);
    top: 0;
    left: 0;
    bottom: 0;
    margin: auto 0; }

.member-3W1lQa .status-oxiHuE,
.privateChannels-1nO12o .avatar-small .status,
.channel-2QD9_O .status-1ibiUI {
  border-color: var(--side-color) !important; }

.ownerIcon-uZ6mE7 path {
  fill: #ccc; }

/*
 *
 *	MAIN CHAT/MESSAGES AREA
 *
 */
.content-yTz4x3,
.messagesWrapper-3lZDfY {
  background: var(--chat-color) !important; }

.chat-3bRxxu .messages-3amgkR {
  margin-bottom: -8px; }

.wrapper-3vR61M,
.wrapper-1F5TKx {
  background-color: transparent; }

.attachment-2p5mHK,
.avatar-2daVqv,
.blob-2w7iIK {
  background-color: #fff; }

/* MAIN CHAT/MESSAGES AREA -> NEW MESSAGES BAR */
.newMessagesBar-265mhP {
  left: 0;
  right: 0;
  background: var(--accent-color) !important;
  box-shadow: var(--default-shadow);
  border-radius: 0;
  opacity: 1;
  color: #fff; }
  .newMessagesBar-265mhP button {
    color: #fff !important; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES */
.messages-3amgkR {
  padding: 0 0 12px 0; }

.dividerEnabled-2TTlcf {
  border-bottom-color: var(--popout-color) !important; }

.isLocalBot-38G0P0 {
  margin: 0 6px 0 20px;
  background: var(--card-color) !important;
  box-shadow: none !important; }

.botTagRegular-2HEhHi {
  background: var(--accent-color);
  font-weight: 700; }

.invite-18yqGF,
.embedInner-1-fpTo,
.embedFull-2tM8--,
.spoilerText-3p6IlD {
  border-radius: 0;
  background-color: var(--chat-box-color) !important; }

.embedFull-2tM8-- {
  background-color: var(--menu-hover-color-alt) !important; }

.embedPill-1Zntps {
  border-radius: 0; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> NEW MESSAGES/DATE DIVIDER */
.divider-3gKybi {
  position: relative;
  width: calc(100% - 46px);
  margin: 0 20px;
  padding: 0;
  background: transparent; }
  .divider-3gKybi > span {
    height: 28px;
    line-height: 28px;
    border-radius: 14px;
    background: var(--menu-hover-color-alt) !important;
    color: #fff !important; }
  .divider-3gKybi.dividerRed-MKoLlr > span {
    background: var(--accent-color) !important; }
  .divider-3gKybi.dividerRed-MKoLlr > span, .divider-3gKybi:not(.red-1YQ4s7) span {
    display: inline-block;
    width: auto;
    padding: 0 12px !important;
    line-height: 28px; }

.dividerContent-2L12VI:before,
.dividerContent-2L12VI:after {
  content: " ";
  position: absolute;
  width: calc(50% - 60px);
  height: 1px;
  top: 50%;
  background: var(--menu-hover-color-alt) !important;
  border: none; }

.divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:before,
.divider-3gKybi.dividerRed-MKoLlr .dividerContent-2L12VI:after {
  background: var(--accent-color) !important;
  border: none !important; }

.dividerContent-2L12VI:before {
  left: 0; }

.dividerContent-2L12VI:after {
  left: auto;
  right: 0; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> MARKUP */
.markup-2BOw-j a {
  color: var(--accent-color) !important; }

.markup-2BOw-j pre,
.markup-2BOw-j code {
  background: var(--chat-box-color) !important;
  border-radius: 0 !important;
  border: none !important; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> MENTIONS */
.wrapper-3WhCwL {
  background-color: rgba(var(--accent-rgb), 0.3) !important;
  color: #fff !important;
  border-radius: 3px; }

.mentioned-xhSam7,
.isMentioned-N-h9aa {
  background-color: rgba(var(--accent-rgb), 0.15) !important; }

.mentioned-xhSam7:before {
  background-color: var(--accent-color); }

.isMentionedCozy-3isp7y:after {
  display: none; }

.isMentionedCozy-3isp7y {
  border-radius: 3px; }

.divider-JfaTT5 {
  border-color: var(--menu-hover-color); }

.content-1o0f9g {
  padding: 6px 10px;
  background: var(--menu-hover-color);
  border-radius: 13px;
  font-size: 14px;
  color: #fff; }

.isUnread-3Ef-o9 {
  border-color: var(--accent-color); }

.unreadPill-2HyYtt,
.divider-3_HH5L.isUnread-3Ef-o9 .content-1o0f9g {
  background-color: var(--accent-color);
  color: #fff; }

.unreadPillCapStroke-7rkHbg {
  color: var(--accent-color);
  fill: var(--accent-color); }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> ACTIONS */
.mouse-mode .message-2qnXI6:hover {
  background-color: rgba(255, 255, 255, 0.015); }

.timestampCompact-29LLPQ {
  color: #aaa; }

.wrapper-2aW0bm {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow) !important;
  border: none; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Pencil"],
.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="BlockQuote"],
.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Nova_Pin"],
.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="MarkUnread"],
.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Nova_Trash"] {
  position: absolute;
  top: 6px;
  left: 8px; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Pencil"] path {
  d: path("M3 17.25V21h3.75L17.81 9.94l-3.75-3.75L3 17.25zM20.71 7.04c.39-.39.39-1.02 0-1.41l-2.34-2.34c-.39-.39-1.02-.39-1.41 0l-1.83 1.83 3.75 3.75 1.83-1.83z") !important; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="BlockQuote"] path {
  d: path("M6 17h3l2-4V7H5v6h3zm8 0h3l2-4V7h-6v6h3z") !important; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Nova_Pin"] {
  transform: rotate(45deg); }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Nova_Pin"] path {
  d: path("M16,12V4H17V2H7V4H8V12L6,14V16H11.2V22H12.8V16H18V14L16,12Z") !important; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="MarkUnread"] path {
  d: path("M11.83,9L15,12.16C15,12.11 15,12.05 15,12A3,3 0 0,0 12,9C11.94,9 11.89,9 11.83,9M7.53,9.8L9.08,11.35C9.03,11.56 9,11.77 9,12A3,3 0 0,0 12,15C12.22,15 12.44,14.97 12.65,14.92L14.2,16.47C13.53,16.8 12.79,17 12,17A5,5 0 0,1 7,12C7,11.21 7.2,10.47 7.53,9.8M2,4.27L4.28,6.55L4.73,7C3.08,8.3 1.78,10 1,12C2.73,16.39 7,19.5 12,19.5C13.55,19.5 15.03,19.2 16.38,18.66L16.81,19.08L19.73,22L21,20.73L3.27,3M12,7A5,5 0 0,1 17,12C17,12.64 16.87,13.26 16.64,13.82L19.57,16.75C21.07,15.5 22.27,13.86 23,12C21.27,7.61 17,4.5 12,4.5C10.6,4.5 9.26,4.75 8,5.2L10.17,7.35C10.74,7.13 11.35,7 12,7Z") !important; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Nova_Trash"] path:first-of-type {
  d: path("M6 19c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V7H6v12zM19 4h-3.5l-1-1h-5l-1 1H5v2h14V4z") !important; }

.item-1Yvehc .hint-22uc-R .icon-3Gkjwa[name="Nova_Trash"] path:last-of-type {
  display: none; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> OPTION POPOUT */
.container-3cGP6G {
  padding: 8px 0;
  background: var(--popout-color) !important;
  box-shadow: var(--default-shadow) !important;
  border-radius: 0; }

.container-3cGP6G .button-38aScr {
  justify-content: flex-start; }

.item-2J1YMK {
  width: 100%;
  height: 32px;
  margin: 0;
  padding: 0 12px;
  border-radius: 0;
  font-size: 0.8em;
  font-weight: 400;
  text-align: left; }
  .item-2J1YMK:hover {
    background: var(--menu-hover-color) !important; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> EDIT MESSAGE */
.container-1YxwTf .channelTextArea-1LDbYG {
  margin: 4px 0 0 0; }
.container-1YxwTf .inner-zqa7da {
  min-height: 34px;
  border-radius: 17px; }
  .container-1YxwTf .inner-zqa7da .pickerButtons-v-PPYK {
    width: 30px;
    height: 34px; }
  .container-1YxwTf .inner-zqa7da .emojiButtonNormal-TdumYh,
  .container-1YxwTf .inner-zqa7da .emojiButtonHovered-1rWNal {
    margin: 0; }
.container-1YxwTf .textArea-2Spzkt {
  padding: 10px 10px 10px 15px; }
.container-1YxwTf .emojiButton-2wRZts {
  width: 34px;
  height: 34px;
  top: 0;
  right: 4px;
  margin: 0; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> DELETE MESSAGE */
.message-2qRu38 {
  margin: 0 0 20px 0;
  background: var(--menu-hover-color) !important;
  border-radius: 0;
  box-shadow: none !important; }
  .message-2qRu38 .containerCozy-jafyvG {
    padding: 10px 0; }

/* MAIN CHAT/MESSAGES AREA -> MESSAGES -> EMOJI INFO */
.popoutContainer-1MXdqN {
  background-color: var(--popout-color);
  border-radius: 0;
  box-shadow: var(--default-shadow); }

.emojiSection-3Fb9ix,
.guildSection-1EoFKd {
  background-color: transparent; }

/* MAIN CHAT/MESSAGES AREA -> JUMP TO PRESENT */
.jumpToPresentBar-G1R9s6 {
  position: absolute;
  width: 42px;
  height: 42px;
  left: auto;
  bottom: 26px;
  right: 30px;
  padding: 0;
  background: transparent;
  border-radius: 50%;
  opacity: 1; }
  .jumpToPresentBar-G1R9s6:before {
    content: " ";
    position: absolute;
    width: 42px;
    height: 42px;
    top: 0;
    left: 0;
    background: var(--accent-color) url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Ik03LjQxLDguNThMMTIsMTMuMTdMMTYuNTksOC41OEwxOCwxMEwxMiwxNkw2LDEwTDcuNDEsOC41OFoiIC8+Cjwvc3ZnPg==) no-repeat 50%;
    border-radius: 50%;
    box-shadow: var(--default-shadow); }
  .jumpToPresentBar-G1R9s6:hover {
    transform: scale(1.075); }
  .jumpToPresentBar-G1R9s6:active {
    margin: 0; }
  .jumpToPresentBar-G1R9s6 button {
    opacity: 0;
    z-index: 2; }
    .jumpToPresentBar-G1R9s6 button:first-child {
      width: 42px;
      height: 42px; }
    .jumpToPresentBar-G1R9s6 button:last-child {
      display: none; }

/* MAIN CHAT/MESSAGES AREA -> CREATE A GROUP */
.divider-drYsXG {
  display: none; }

.listingsLabel-3a6CEF {
  margin: 0;
  padding: 20px 20px 12px;
  border-bottom: 1px solid var(--card-border); }

.listings-3rchv- {
  margin: 0 0 72px 0; }

/* MAIN CHAT/MESSAGES AREA -> SERVER/SPOTIFY INVITE */
.wrapper-35wsBm,
.content-35aVm0 {
  padding: 15px 10px;
  background: var(--chat-box-color) !important;
  border-radius: 0;
  border: none; }

.invite-18yqGF {
  border: none; }

.wrapper-35wsBm {
  min-width: 400px;
  max-width: 100%;
  width: auto; }

.wrapper-35wsBm .button-3To2tQ .buttonInner-1IRxqd .buttonIcon-1pYT18 {
  display: none; }

/* MAIN CHAT/MESSAGES AREA -> ATTACHMENTS */
.attachment-33OFj0,
.wrapperAudio-1jDe0Q {
  background: var(--chat-box-color) !important;
  border-radius: 0;
  border: none !important; }

/* MAIN CHAT/MESSAGES AREA -> NSFW WARNING */
/*.chat-3bRxxu .content-yTz4x3 .horizontal-1ae9ci>.flex-1xMQg5:last-child {
	margin: 0 0 72px 0;
}*/
/*
 *
 *	SEARCH RESULTS
 *
 */
.searchResultsWrap-3-pOjs {
  padding: 0 0 72px 0;
  background: var(--side-color) !important; }

.searchHeader-1EzJGH {
  background: transparent !important;
  box-shadow: none !important;
  border-bottom: 1px solid #333; }

.searchResultsWrap-2DKFzt .searchHeader-1l-wpR .totalResults-gxvzgw {
  opacity: 1; }

.channelName-1JRO3C {
  background-color: var(--side-color) !important; }

.searchResultMessage-1fxgXh.hit-1fVM9e,
.searchResult-9tQ1uo.expanded-ovgtuV {
  background-color: transparent;
  border-radius: 0;
  border: none !important; }

.searchResultMessage-1fxgXh.hit-1fVM9e {
  margin-top: 3px;
  box-shadow: 0 0 10px 6px var(--side-color); }

.searchResultMessage-1fxgXh.hit-1fVM9e,
.expanded-w_LCGl .searchResultMessage-1fxgXh.hit-1fVM9e {
  background-color: var(--menu-hover-color-alt); }

.searchResult-9tQ1uo,
.searchResult-9tQ1uo.expanded-w_LCGl {
  margin-bottom: 24px;
  padding-bottom: 24px;
  background-color: transparent;
  border: none;
  border-bottom: 3px solid var(--card-border) !important;
  border-radius: 0; }

.searchResult-9tQ1uo:before {
  background-image: linear-gradient(0deg, transparent, var(--side-color)); }

.searchResult-9tQ1uo:after {
  background-image: linear-gradient(180deg, transparent, var(--side-color)); }

.searchResult-3pzFAB .searchResultMessage-2VxO12.before-1x1q5S {
  opacity: 0.15 !important; }

.searchResult-3pzFAB .hit-NLlWXA {
  box-shadow: none !important; }

.searchBarIcon-1J6sKG {
  margin: 6px 0 !important; }

.searchBarIcon-1J6sKG .icon-3cZ1F_.iconSearchBarEyeGlass-2n38zb,
.searchBarIcon-1J6sKG .icon-3cZ1F_.iconSearchBarClear-2DW-Kr {
  background-position: 50%;
  background-size: 100%; }

.searchBarIcon-1J6sKG .icon-3cZ1F_.visible-3V0mGj {
  opacity: 1; }

.searchBarIcon-1J6sKG .icon-3cZ1F_.iconSearchBarEyeGlass-2n38zb {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiMzMzMzMzMiIGQ9Ik05LjUsM0E2LjUsNi41IDAgMCwxIDE2LDkuNUMxNiwxMS4xMSAxNS40MSwxMi41OSAxNC40NCwxMy43M0wxNC43MSwxNEgxNS41TDIwLjUsMTlMMTksMjAuNUwxNCwxNS41VjE0LjcxTDEzLjczLDE0LjQ0QzEyLjU5LDE1LjQxIDExLjExLDE2IDkuNSwxNkE2LjUsNi41IDAgMCwxIDMsOS41QTYuNSw2LjUgMCAwLDEgOS41LDNNOS41LDVDNyw1IDUsNyA1LDkuNUM1LDEyIDcsMTQgOS41LDE0QzEyLDE0IDE0LDEyIDE0LDkuNUMxNCw3IDEyLDUgOS41LDVaIiAvPgo8L3N2Zz4=); }

.searchBarIcon-1J6sKG .icon-3cZ1F_.iconSearchBarClear-2DW-Kr {
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiMzMzMzMzMiIGQ9Ik0xMiwyQzE3LjUzLDIgMjIsNi40NyAyMiwxMkMyMiwxNy41MyAxNy41MywyMiAxMiwyMkM2LjQ3LDIyIDIsMTcuNTMgMiwxMkMyLDYuNDcgNi40NywyIDEyLDJNMTUuNTksN0wxMiwxMC41OUw4LjQxLDdMNyw4LjQxTDEwLjU5LDEyTDcsMTUuNTlMOC40MSwxN0wxMiwxMy40MUwxNS41OSwxN0wxNywxNS41OUwxMy40MSwxMkwxNyw4LjQxTDE1LjU5LDdaIiAvPgo8L3N2Zz4=); }

/*
 *
 *	EMOJI PICKER
 *
 */
.buttons-3JBrkn,
.pickerButtons-v-PPYK {
  width: auto; }

.webkit-26NYEN .buttons-205you,
.buttons-3JBrkn {
  margin: 0;
  right: 8px; }

.buttons-3JBrkn .buttonWrapper-1ZmCpA .button-3AYNKb {
  opacity: 1; }

.buttons-3JBrkn .buttonWrapper-1ZmCpA .icon-3D60ES:hover {
  transform: scale(1.1); }

.buttons-3JBrkn .button-3AYNKb {
  color: #444; }

.buttons-3JBrkn .button-3AYNKb:hover,
.buttonWrapper-1ZmCpA:hover .icon-3D60ES {
  color: #5f5f5f; }

.buttonContainer-28fw2U.send-button .icon-3D60ES path:first-child {
  fill: none; }

/* EMOJI PICKER -> PICKER */
.contentWrapper-SvZHNd,
.emojiPicker-3PwZFl {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

.drawerSizingWrapper-27qFHb {
  min-width: 436px; }

/* EMOJI PICKER -> PICKER -> HEADER */
.header-8ilj5e,
.header-2k4I2o {
  box-shadow: none;
  border-bottom: 1px solid #444; }

.diversitySelectorPopout-3FiGaM {
  border-radius: 16px;
  border: none;
  box-shadow: var(--default-shadow); }

/* EMOJI PICKER -> PICKER -> HEADER -> SEARCH BAR */
.container-2XeR5Z {
  background-color: var(--input-bg);
  border-radius: 17px; }
  .container-2XeR5Z .input-1Rv96N {
    color: var(--input-text-color) !important; }
    .container-2XeR5Z .input-1Rv96N::-webkit-input-placeholder {
      color: var(--input-placeholder-color) !important; }

/* EMOJI PICKER -> PICKER -> CATEGORIES */
.categoryList-2Kzf65,
.wrapper-2Gsate {
  background-color: var(--menu-hover-color-alt); }

.categoryList-2Kzf65 .scroller-3gAZLs::-webkit-scrollbar,
.wrapper-2Gsate .scroller-3gAZLs::-webkit-scrollbar {
  width: 0 !important; }

.unicodeShortcut-15J8Ck {
  height: 47px;
  border-top: 1px solid #444; }

/* EMOJI PICKER -> PICKER -> EMOJIS */
[class*="theme-"] .wrapper-1-Fsb8 {
  background-color: var(--popout-color); }

.emojiItem-14v6tW.emojiItemSelected-1aLkfV {
  background-color: var(--menu-hover-color); }

.inspector-S2gM3e {
  background-color: var(--menu-hover-color-alt);
  border-top: 1px solid #444; }

.content-ySCtCx .scroller-2FKFPG::-webkit-scrollbar {
  width: 8px !important; }

.emojiListRowMediumSize-M_K7-z {
  grid-template-columns: repeat(auto-fill, 38px);
  height: 38px; }

/*
 *
 *	GIF PICKER
 *
 */
.header-1TOWci {
  border-bottom: 1px solid #444; }

[class*="theme-"] .header-1TOWci {
  box-shadow: none; }

.container-cMG81i {
  background: var(--input-bg);
  border-radius: 18px; }

.inner-2P4tQO {
  padding: 0; }

.medium-1LLV3p.iconLayout-3OgqU3 {
  width: 34px;
  height: 34px;
  margin-right: 8px; }

.iconLayout-3OgqU3 .icon-1S6UIr {
  color: #444; }

.container-2jxBbw {
  overflow-x: hidden !important; }

/*
 *
 *	FRIENDS
 *
 */
.container-3gCOGc,
.container-3Mxszk {
  position: relative;
  padding: 0 0 72px 0;
  background: var(--chat-color) !important; }

.headerBar-UHpsPw {
  background: var(--side-color) !important; }

.privateChannels-1nO12o,
.scroller-1JbKMe {
  background: var(--side-color); }

/* FRIENDS -> SEARCH BAR */
.searchBar-6Kv8R2 {
  box-shadow: 0 1px 0 rgba(0, 0, 0, 0.2) !important; }

.searchBar-2_Yu-C,
.searchBar-2_Yu-C .searchBarInner-1_Tg2R {
  background: transparent;
  border: none; }

/* FRIENDS -> TAB BAR */
.topPill-30KHOu {
  height: 100%; }
  .topPill-30KHOu .item-PXvHYJ {
    height: 100%;
    line-height: 45px;
    background: transparent !important;
    color: #777 !important; }
    .topPill-30KHOu .item-PXvHYJ:hover {
      color: #bbb !important; }
  .topPill-30KHOu .itemSelected-1qLhcL,
  .topPill-30KHOu .item-PXvHYJ.selected-3s45Ha,
  .topPill-30KHOu .item-PXvHYJ[style*="background-color: rgba(67, 181, 129, 0.2); color: rgb(67, 181, 129);"] {
    color: #fff !important; }
  .topPill-30KHOu .separator-gCa7yv {
    display: none; }

#friends .tab-bar .tab-bar-item:hover,
#friends .tab-bar .tab-bar-item.selected,
#friends .tab-bar .tab-bar-item.tab-bar-item-primary {
  background: transparent !important; }

/* FRIENDS -> FRIENDS LIST */
.tabBody-3YRQ8W {
  position: relative;
  padding: 0 0 72px 0; }

.container-1D34oG {
  background-color: var(--chat-color) !important; }

.title-30qZAO {
  margin: 0 0 12px 0;
  padding: 8px 32px;
  border-bottom: 1px solid var(--menu-hover-color); }

.peopleListItem-2nzedh {
  border-top: 1px solid var(--menu-hover-color);
  border-radius: 0; }
  .peopleListItem-2nzedh:hover {
    background: var(--menu-hover-color-alt);
    border-radius: 0; }
  .peopleListItem-2nzedh:first-of-type {
    border-top: none; }

.actionButton-uPB8Fs {
  background-color: var(--button-background) !important;
  border: var(--button-border); }
  .actionButton-uPB8Fs:hover {
    border: var(--button-border-hover);
    transform: scale(1.05); }
  .actionButton-uPB8Fs:active:hover {
    transform: scale(1);
    opacity: 0.5 !important; }

/* FRIENDS -> FRIENDS LIST -> NOW PLAYING */
.nowPlayingColumn-2sl4cE {
  background-color: var(--side-color); }

.itemCard-v9viV7 {
  padding: 16px 0;
  background-color: transparent !important;
  border-radius: 0;
  border-bottom: 1px solid var(--menu-hover-color); }
  .itemCard-v9viV7.active-1xchHY {
    background-color: var(--card-color) !important;
    border-color: transparent; }

.inset-3sAvek {
  background-color: var(--menu-hover-color-alt) !important;
  border-radius: 0; }

.popout-38lTFE,
.popout-13LQ_3 {
  left: -184px;
  padding: 6px 0;
  background-color: var(--popout-color) !important;
  border-radius: 0;
  box-shadow: var(--default-shadow) !important; }

.memberListHeader-543n-J {
  margin: 16px 8px 12px 8px; }

.wrapper-3Rixsz,
.memberListItem-2ZX2pl,
.memberListItem-31QoHj {
  margin: 0;
  padding: 8px 12px;
  border-radius: 0; }

.wrapper-3Rixsz {
  padding-left: 34px; }
  .wrapper-3Rixsz:last-child {
    margin-bottom: 4px; }

.memberListItem-2ZX2pl,
.memberListItem-31QoHj {
  padding: 7px 12px 7px 8px; }

.memberListItem-31QoHj:last-child {
  margin-bottom: 0; }

.enabled-1t_Gxm:hover,
.memberListItem-31QoHj:not(.popoutDisabled-2RK7MF):hover {
  background-color: var(--menu-hover-color) !important; }

.memberListContainer-13tNU9 {
  margin-top: 4px; }

.nameTag-m8r81H .username-3GVY1Y {
  font-weight: 400 !important; }

.separator-XqIyoz {
  background-color: var(--menu-border-color) !important; }

.channel-2QD9_O {
  margin: 0; }

.layout-2DM8Md {
  margin: 0;
  padding: 0 0 0 16px;
  border-radius: 0; }

.channel-2QD9_O,
.layout-2DM8Md {
  background: transparent !important; }

.channel-2QD9_O.selected-aXhQR6 {
  position: relative;
  background: transparent; }

.channel-2QD9_O.selected-aXhQR6:before {
  content: " ";
  position: absolute;
  width: 4px;
  height: 65%;
  top: 0;
  left: 0;
  bottom: 0;
  margin: auto 0;
  background: var(--accent-color); }

.channel-2QD9_O .name-uJV0GL {
  color: #9f9f9f;
  opacity: 1; }

.channel-2QD9_O:hover .name-uJV0GL,
.channel-2QD9_O.selected-aXhQR6 .name-uJV0GL {
  color: #fff; }

.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/e1fb24a120bdd003a84e021b16ec3bef.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/1531b79c2f2927945582023e1edaaa11.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/b3150d5cef84b9e82128a1131684f287.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/773616c3c8a7e21f8a774eb0d5625436.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/485a854d5171c8dc98088041626e6fea.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/f810dc5fedb7175c43a3389aa890534f.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/b8912961ea6ab32f0655d583bbc26b4f.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/b8912961ea6ab32f0655d583bbc26b4f.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/861ab526aa1fabb04c6b7da8074e3e21.png"],
.avatar-3uk_u9 .wrapper-3t9DeA img[src="/assets/e1fb24a120bdd003a84e021b16ec3bef.png"],
.wrapper-1BJsBx img[src="/assets/e1fb24a120bdd003a84e021b16ec3bef.png"],
.wrapper-1BJsBx img[src="/assets/1531b79c2f2927945582023e1edaaa11.png"],
.wrapper-1BJsBx img[src="/assets/b3150d5cef84b9e82128a1131684f287.png"],
.wrapper-1BJsBx img[src="/assets/773616c3c8a7e21f8a774eb0d5625436.png"],
.wrapper-1BJsBx img[src="/assets/485a854d5171c8dc98088041626e6fea.png"],
.wrapper-1BJsBx img[src="/assets/f810dc5fedb7175c43a3389aa890534f.png"],
.wrapper-1BJsBx img[src="/assets/b8912961ea6ab32f0655d583bbc26b4f.png"],
.wrapper-1BJsBx img[src="/assets/b8912961ea6ab32f0655d583bbc26b4f.png"],
.wrapper-1BJsBx img[src="/assets/861ab526aa1fabb04c6b7da8074e3e21.png"],
.wrapper-1BJsBx img[src="/assets/e1fb24a120bdd003a84e021b16ec3bef.png"] {
  content: url("https://capnkitten.github.io/BetterDiscord/Spotify-Discord/img/group_icon.png") !important; }

/* FRIENDS -> ADD FRIEND */
.wrapper-1cBijl {
  margin: 0;
  padding: 0;
  background: transparent;
  border: none; }
  .wrapper-1cBijl .addFriendHint-3Y70FX {
    left: 12px;
    font-size: 14px !important;
    font-weight: 500 !important;
    color: #444 !important;
    opacity: 0.6;
    z-index: 1; }

.sectionHeader-20RGqu {
  border-bottom: 1px solid var(--card-border) !important; }

/* FRIENDS -> MESSAGES */
/* FRIENDS -> MESSAGES -> SEARCH BAR */
.search-2oPWTC .DraftEditor-root {
  padding: 0;
  line-height: 32px;
  color: var(--input-text-color); }

.searchBar-3dMhjb .icon-38sknP {
  height: 28px;
  margin: 0 -5px 0 0; }

/* FRIENDS -> MESSAGES -> VOICE AND VIDEO CALL */
.wrapper-2qzCYF.minimum-28Z35l,
.wrapper-2qzCYF {
  background-color: var(--chat-color);
  box-shadow: var(--default-shadow); }

.videoControls-24w7Xp {
  padding: 0px 16px 16px; }

.quickSelect-3BxO0K {
  margin-top: 8px; }

.regionSelectPopout-p9-0_W {
  padding: 8px 0;
  background: var(--popout-color) !important;
  border-radius: 0;
  box-shadow: var(--default-shadow); }

.quickSelectPopoutOption-opKBx9:hover {
  background-color: var(--menu-hover-color) !important; }

.quickSelectPopoutOption-opKBx9.selected {
  background-color: var(--menu-select-color) !important; }

.centerButton-3CaNcJ {
  background: var(--menu-hover-color); }

.centerButton-3CaNcJ:hover {
  background: var(--menu-select-color); }

.titleCall-_b9o8P {
  background: var(--side-color) !important;
  box-shadow: 0 1px 0 rgba(0, 0, 0, 0.2), 0 2px 0 rgba(0, 0, 0, 0.06); }

.video-1FfuMD {
  background-color: var(--chat-color) !important;
  border-bottom: 1px solid var(--card-border); }

.wrapper-29NfPK .iconsWrapper-1RelE3 {
  height: 42px;
  background: var(--chat-box-color) !important;
  border-radius: 21px;
  border: none !important; }

#friends .friends-table .friends-table-header .friends-column {
  color: var(--menu-text-color) !important; }

#friends .friends-table .friends-table-header .friends-column-separator {
  opacity: 0; }

/* FRIENDS -> MESSAGES -> VOICE AND VIDEO CALL -> INCOMING CALL */
.incomingCall-14zLcL {
  box-shadow: var(--default-shadow) !important; }

.incomingCallInner-2VmFiR {
  background: var(--popout-color) !important;
  border-radius: var(--popout-radius) !important;
  border: none !important; }

/* FRIENDS -> MESSAGES -> VOICE AND VIDEO CALL -> SCREEN SHARING */
.callAvatarBorder-1D_KaE.video-3GgX2M.selected-2esnyn:not(.speaking-oCqYMI):not(.soundsharing-102bS9) {
  border: 2px solid var(--accent-color);
  box-shadow: none; }

.item-3T2z1R {
  border-color: #555 !important; }

.selectorButtonSelected-1j4DmC {
  background-color: var(--accent-color); }

.item-3T2z1R svg[name="Nitro"] path {
  fill: var(--accent-color) !important; }

.tiles-2aXG_k {
  background: rgba(0, 0, 0, 0.25) !important;
  border-radius: 0;
  box-shadow: none !important; }

.imageSelected-4Kl81J {
  border: 2px solid var(--accent-color); }

.titleWrap-15Rh6M {
  color: #888 !important; }

.titleSelected-1UkXLp {
  color: #fff !important; }

/* FRIENDS -> SEARCH */
.quickswitcher-3JagVE {
  padding: 0; }

.input-2VB9rf {
  margin: 12px; }

.scrollerOuter-3FLELE {
  margin: 0 12px; }

.result-oB0z-- {
  border-radius: 0; }

.resultFocused-3aIoYe {
  background: var(--menu-hover-color) !important; }

.tipsWithoutResults-lGY-De,
.tipsWithResults-HhTE9b {
  padding: 12px; }

/*
 *
 *	ACTIVITY
 *
 */
/*
 *
 *	LIBRARY
 *
 */
.gameLibrary-TTDw4Y {
  position: relative;
  padding: 0 0 72px 0;
  background: var(--chat-color) !important; }

.libraryHeader-3g95kE + div + .container-19hC9u .scroller-1IIF0A,
.libraryHeader-3g95kE + .scrollerWrap-2lJEkd .scroller-2FKFPG {
  background: var(--chat-color) !important; }

.gameLibrary-TTDw4Y .scroller-2FKFPG {
  margin: 35px 0 0 0; }

.table-1tDS6w {
  margin: 0 0 0 0; }

/* LIBRARY -> HEADER */
.header-39GIC8 {
  width: 100%;
  margin: 0 0 12px 0;
  padding: 8px 32px;
  background: var(--chat-color) !important;
  border-bottom: 1px solid var(--menu-hover-color); }

.headerCell-3L6rFG {
  border: none; }

.headerCellContent-1pLtOr {
  font-weight: 500; }

/* LIBRARY -> ROWS */
.rowWrapper-2fB6P0,
.rowBackground-3MeNoN {
  border-radius: 0; }

.rowWrapperActive-2L7i9f {
  background: var(--card-color) !important;
  box-shadow: none !important; }

.rowWrapperActive-2L7i9f .lookFilled-1Gx00P.colorGreen-29iAKY {
  background: transparent !important;
  border: var(--button-border) !important; }

.rowWrapper-2fB6P0 .lookFilled-1Gx00P.colorPrimary-3b3xI6.playButton-1fMNjH,
.rowWrapperActive-2L7i9f .lookFilled-1Gx00P.colorPrimary-3b3xI6.playButton-1fMNjH,
.rowWrapperActive-2L7i9f .lookFilled-1Gx00P.colorGreen-29iAKY.playButton-1fMNjH {
  background-color: var(--accent-color) !important;
  border: 1px solid var(--accent-color) !important; }

.rowWrapper-2fB6P0 .lookFilled-1Gx00P.colorPrimary-3b3xI6:not(.playButton-1fMNjH):hover,
.rowWrapperActive-2L7i9f .lookFilled-1Gx00P.colorPrimary-3b3xI6:not(.playButton-1fMNjH):hover,
.rowWrapperActive-2L7i9f .lookFilled-1Gx00P.colorGreen-29iAKY.playButton-1fMNjH:not(.playButton-1fMNjH):hover {
  border: var(--button-border-hover) !important; }

.bodyCell-9xKjWE {
  padding: 8px 0 8px 0; }

.bodyCell-9xKjWE.platformCell-XyBBs6,
.bodyCell-9xKjWE.lastPlayedCell-2arbtc {
  padding: 8px 8px 8px 15px; }

/* LIBRARY -> DOWNLOADING GAME */
.gameUpdates-2GPqBU {
  background: var(--chat-color);
  border-bottom: 1px solid var(--background-modifier-accent); }

.actionsCell-31fBWo .lookFilled-1Gx00P.colorGrey-2DXtkV {
  padding: 0 3px !important; }

/* LIBRARY -> NITRO GAMES */
/* LIBRARY -> GIFT INVENTORY */
.root-1BQpZw {
  background: var(--chat-color) !important;
  margin: 0 0 70px 0; }

/* LIBRARY -> SETTINGS */
.scroller-2XE8rp {
  background-color: var(--chat-color); }

[class*="theme-"] .installationPath-3cStrB {
  box-shadow: 0 1px 0 0 var(--card-border); }

/*
 *
 *	STORE
 *
 */
.applicationStore-1pNvnv {
  position: relative;
  padding: 0 0 72px 0;
  background: var(--chat-color) !important; }

.distributionApplicationsSort-2_uq5y {
  border: none; }

.browseSearch-e9jF-f,
.libraryFilter-31ZUa2 {
  width: auto;
  height: 28px;
  margin: 0 8px 0 0;
  background: var(--input-bg) !important;
  border-radius: 14px; }

.browseSearch-e9jF-f .browseSearchInput-Jt8kg0,
.browseSearch-e9jF-f .searchBar-s2JxlI,
.libraryFilter-31ZUa2 .libraryFilterInput-3JzqZD,
.libraryFilter-31ZUa2 .searchBar-TUoVPN {
  width: 144px;
  height: 28px !important;
  background: transparent !important;
  font-weight: 700 !important;
  transition: 250ms ease all; }

.browseSearch-e9jF-f .searchBar-s2JxlI .inner-2P4tQO,
.libraryFilter-31ZUa2 .searchBar-TUoVPN .inner-2P4tQO {
  padding: 0; }

.browseSearch-e9jF-f .searchBar-s2JxlI input,
.libraryFilter-31ZUa2 .searchBar-TUoVPN input {
  height: 28px !important;
  margin: 0;
  padding: 0 0 0 12px; }

.browseSearch-e9jF-f .searchBar-s2JxlI .iconLayout-3OgqU3,
.libraryFilter-31ZUa2 .searchBar-TUoVPN .iconLayout-3OgqU3 {
  height: 28px;
  margin: 0 8px 0 0; }

.browseSearch-e9jF-f .browseSearchInput-Jt8kg0:focus,
.libraryFilter-31ZUa2 .libraryFilterInput-3JzqZD:focus {
  width: 244px; }

.browseSearch-e9jF-f .browseSearchInput-Jt8kg0,
.browseSearch-e9jF-f .browseSearchInput-Jt8kg0:focus,
.libraryFilter-31ZUa2 .libraryFilterInput-3JzqZD,
.libraryFilter-31ZUa2 .libraryFilterInput-3JzqZD:focus {
  border: none !important; }

/*
 *
 * SERVER DISCOVERY
 *
 */
.pageWrapper-1PgVDX {
  margin-bottom: 72px;
  background-color: var(--chat-color) !important; }

.bg-AYqtMd {
  -webkit-mask-image: linear-gradient(to top, transparent 0%, var(--chat-box-color) 50%); }

.viewButton-3jDZqV {
  opacity: 0 !important; }

/* SERVER DISCOVERY -> SIDEBAR */
.sidebar-2K8pFh {
  background: var(--side-color); }

.sidebar-2K8pFh .selected-aXhQR6.container-2Pjhx- {
  position: relative; }

.sidebar-2K8pFh .selected-aXhQR6.container-2Pjhx-:before {
  left: 0; }

.categoryItem-3zFJns {
  margin-left: 0; }

/* SERVER DISCOVERY -> SEARCH BAR */
.search-1iTphC .searchBox-2_mAlO {
  border-radius: 21px;
  border: none;
  transition: 250ms ease box-shadow; }

.search-1iTphC .searchBox-2_mAlO:focus-within {
  box-shadow: 0 4px 10px 0 rgba(0, 0, 0, 0.42); }

.search-1iTphC .searchBox-2_mAlO .searchBoxInput-K6mkng {
  height: 42px !important; }

/* SERVER DISCOVERY -> CARDS */
.card-3DjzTQ {
  background-color: transparent !important;
  border-radius: 0;
  border-bottom: 4px solid var(--card-border); }
  .card-3DjzTQ:hover {
    box-shadow: none;
    transform: translateY(0); }
    .card-3DjzTQ:hover .viewButton-3jDZqV {
      opacity: 1 !important; }

.iconMask-3b8GzQ {
  height: 40px;
  background-color: var(--chat-color) !important; }

.iconMask-3b8GzQ,
.avatar-22otdK {
  border-radius: 50%; }

/*
 *
 *	SERVER BOOST
 *
 */
[class*="theme-"] .perksModal-fSYqOq {
  background-color: var(--chat-color); }

/*
 *
 *	BOTTOM BAR
 *
 */
/* BOTTOM BAR -> ADD BAR */
.membersWrap-2h-GB4:after,
.searchResultsWrap-2DKFzt:after,
.activityFeed-1C0EmJ:after,
.activityFeed-28jde9:after,
.gameLibrary-TTDw4Y:after,
.container-3gCOGc:after,
.content-yTz4x3:after,
.applicationStore-1pNvnv:after,
.root-26DmKJ .scroller-2FKFPG:after,
.root-1BQpZw:after,
.container-3Mxszk:after,
.tabBody-3YRQ8W:after,
.pageWrapper-1PgVDX:after {
  content: " ";
  position: fixed;
  width: 100%;
  height: 72px;
  right: 0;
  bottom: 0;
  background: var(--bar-color); }

/* BOTTOM BAR -> STATUS BAR */
.base-3dtUhz,
.platform-win .sidebar-2K8pFh {
  overflow: visible; }

.container-3baos1 {
  position: relative;
  height: 71px;
  padding: 0 4px 0 8px;
  background: var(--bar-color) !important; }

.button-2b6hmh {
  border-radius: 50%;
  opacity: 0.6; }
  .button-2b6hmh:hover {
    background-color: transparent !important; }

.status-2kJpnA {
  border-color: var(--bar-color) !important; }

/* BOTTOM BAR -> STATUS BAR -> STATUS PICKER */
.statusItem-33LqPf {
  padding: 0; }

/* BOTTOM BAR -> STATUS BAR -> ICONS */
/* BOTTOM BAR -> STATUS BAR -> ICONS -> MUTE */
.button-14-BFJ[aria-label="Mute"][aria-checked="false"] .contents-18-Yxp path,
.button-14-BFJ[aria-label="Mute"][aria-checked="true"] .contents-18-Yxp path {
  display: none; }

.button-14-BFJ[aria-label="Mute"][aria-checked="false"] .contents-18-Yxp path:first-child,
.button-14-BFJ[aria-label="Mute"][aria-checked="true"] .contents-18-Yxp path:first-child {
  display: block; }

.button-14-BFJ[aria-label="Mute"][aria-checked="false"] .contents-18-Yxp path {
  d: path("M12,2A3,3 0 0,1 15,5V11A3,3 0 0,1 12,14A3,3 0 0,1 9,11V5A3,3 0 0,1 12,2M19,11C19,14.53 16.39,17.44 13,17.93V21H11V17.93C7.61,17.44 5,14.53 5,11H7A5,5 0 0,0 12,16A5,5 0 0,0 17,11H19Z") !important; }

.button-14-BFJ[aria-label="Mute"][aria-checked="true"] .contents-18-Yxp path {
  d: path("M19,11C19,12.19 18.66,13.3 18.1,14.28L16.87,13.05C17.14,12.43 17.3,11.74 17.3,11H19M15,11.16L9,5.18V5A3,3 0 0,1 12,2A3,3 0 0,1 15,5V11L15,11.16M4.27,3L21,19.73L19.73,21L15.54,16.81C14.77,17.27 13.91,17.58 13,17.72V21H11V17.72C7.72,17.23 5,14.41 5,11H6.7C6.7,14 9.24,16.1 12,16.1C12.81,16.1 13.6,15.91 14.31,15.58L12.65,13.92L12,14A3,3 0 0,1 9,11V10.28L3,4.27L4.27,3Z") !important; }

/* BOTTOM BAR -> STATUS BAR -> ICONS -> DEAFEN */
.button-14-BFJ[aria-label="Deafen"][aria-checked="false"] .contents-18-Yxp path {
  d: path("M14,3.23V5.29C16.89,6.15 19,8.83 19,12C19,15.17 16.89,17.84 14,18.7V20.77C18,19.86 21,16.28 21,12C21,7.72 18,4.14 14,3.23M16.5,12C16.5,10.23 15.5,8.71 14,7.97V16C15.5,15.29 16.5,13.76 16.5,12M3,9V15H7L12,20V4L7,9H3Z") !important; }

.button-14-BFJ[aria-label="Deafen"][aria-checked="true"] .contents-18-Yxp path {
  d: path("M12,4L9.91,6.09L12,8.18M4.27,3L3,4.27L7.73,9H3V15H7L12,20V13.27L16.25,17.53C15.58,18.04 14.83,18.46 14,18.7V20.77C15.38,20.45 16.63,19.82 17.68,18.96L19.73,21L21,19.73L12,10.73M19,12C19,12.94 18.8,13.82 18.46,14.64L19.97,16.15C20.62,14.91 21,13.5 21,12C21,7.72 18,4.14 14,3.23V5.29C16.89,6.15 19,8.83 19,12M16.5,12C16.5,10.23 15.5,8.71 14,7.97V10.18L16.45,12.63C16.5,12.43 16.5,12.21 16.5,12Z") !important; }

.button-14-BFJ[aria-label="Deafen"][aria-checked="true"] .contents-18-Yxp path {
  display: none; }

.button-14-BFJ[aria-label="Deafen"][aria-checked="true"] .contents-18-Yxp path:first-child {
  display: block; }

/* BOTTOM BAR -> STATUS BAR -> ICONS -> SETTINGS */
.button-14-BFJ[aria-label="User Settings"] svg path {
  d: path("M15.95 10.78c.03-.25.05-.51.05-.78s-.02-.53-.06-.78l1.69-1.32c.15-.12.19-.34.1-.51l-1.6-2.77c-.1-.18-.31-.24-.49-.18l-1.99.8c-.42-.32-.86-.58-1.35-.78L12 2.34c-.03-.2-.2-.34-.4-.34H8.4c-.2 0-.36.14-.39.34l-.3 2.12c-.49.2-.94.47-1.35.78l-1.99-.8c-.18-.07-.39 0-.49.18l-1.6 2.77c-.1.18-.06.39.1.51l1.69 1.32c-.04.25-.07.52-.07.78s.02.53.06.78L2.37 12.1c-.15.12-.19.34-.1.51l1.6 2.77c.1.18.31.24.49.18l1.99-.8c.42.32.86.58 1.35.78l.3 2.12c.04.2.2.34.4.34h3.2c.2 0 .37-.14.39-.34l.3-2.12c.49-.2.94-.47 1.35-.78l1.99.8c.18.07.39 0 .49-.18l1.6-2.77c.1-.18.06-.39-.1-.51l-1.67-1.32zM10 13c-1.65 0-3-1.35-3-3s1.35-3 3-3 3 1.35 3 3-1.35 3-3 3z") !important;
  transform: scale(1.25); }

/* BOTTOM BAR -> CHAT FORM */
.form-2fGMdU {
  z-index: 2; }
  .form-2fGMdU:before {
    display: none; }

.chat-3bRxxu .messagesWrapper-1sRNjr + .form-2fGMdU {
  min-height: 72px;
  margin: 0;
  padding: 0 16px;
  background-color: var(--bar-color);
  border: none;
  z-index: 2; }

.channelTextArea-rNsIhG,
.channelTextArea-1LDbYG {
  margin: 14px 0;
  background: transparent; }

.channelTextArea-rNsIhG .sansAttachButton-td2irx {
  padding-left: 0; }

.activityInviteEducation-8C0Czp {
  top: -6px;
  bottom: auto;
  overflow: visible; }

.activityInviteEducationArrow-3DEpKU {
  width: 16px;
  height: 32px;
  margin: 0 0 0 11px;
  padding-left: 8px;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgd2lkdGg9IjI0Ij48cGF0aCBkPSJNMCAwaDI0djI0SDBWMHoiIGZpbGw9Im5vbmUiLz48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMTkgMTVsLTYgNi0xLjQyLTEuNDJMMTUuMTcgMTZINFY0aDJ2MTBoOS4xN2wtMy41OS0zLjU4TDEzIDlsNiA2eiIvPjwvc3ZnPg==) !important;
  background-position: center;
  background-size: 67.5%;
  transform: rotate(90deg);
  border-bottom-left-radius: var(--popout-radius);
  border-bottom-right-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

.activityInviteEducation-8C0Czp span {
  margin-left: 4px;
  padding: 0 8px 0 0;
  border-top-right-radius: var(--popout-radius);
  border-bottom-right-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

.activityInviteEducationArrow-3DEpKU,
.activityInviteEducation-8C0Czp span {
  background-color: var(--popout-color); }

.activityInviteEducationArrow-3DEpKU {
  box-shadow: 0 7px 18px rgba(0, 0, 0, 0.25), 0 6px 10px rgba(0, 0, 0, 0.25); }

.scrollableContainer-2NUZem {
  max-height: 45vh;
  background-color: var(--input-bg);
  border-radius: var(--textarea-radius); }

.scrollableContainer-2NUZem::-webkit-scrollbar {
  width: 8px !important; }

.container-2fRDfG {
  background-color: var(--input-bg);
  border-radius: var(--textarea-radius) var(--textarea-radius) 0 0;
  border-bottom: 1px solid #ccc; }

.charCounterAdded-zz9O4t .container-2fRDfG {
  border-radius: 0; }

.container-2fRDfG .colorHeaderSecondary-3Sp3Ft {
  color: var(--input-text-color); }

.closeButton-37O8QC {
  color: #666; }
  .closeButton-37O8QC:hover {
    color: #444; }

.scrollableContainer-2NUZem.hasReply-16cIUP {
  border-radius: 0 0 var(--textarea-radius) var(--textarea-radius); }

.container-9gOVw0 {
  border-radius: var(--textarea-radius) var(--textarea-radius) 0 0;
  background-color: var(--input-bg);
  border-bottom: 1px solid #ccc; }

.container-9gOVw0 .colorHeaderSecondary-3Sp3Ft,
.closeButton-3JbGDk {
  color: #333;
  font-weight: 600; }

.closeButton-3JbGDk:hover {
  color: #111; }

/*.scrollableContainer-2NUZem .textArea-12jD-V,
.scrollableContainer-2NUZem .textArea-12jD-V::-webkit-input-placeholder {
	color: #222 !important;
}*/
.placeholder-37qJjk {
  color: var(--input-placeholder-color) !important; }

.scrollableContainer-2NUZem .markup-2BOw-j {
  color: var(--input-text-color) !important;
  font-weight: 500; }

.scrollableContainer-2NUZem .markup-2BOw-j .wrapper-3WhCwL {
  background-color: rgba(var(--accent-rgb), 0.3) !important;
  border-radius: 3px;
  color: var(--input-text-color) !important; }

.fakeLink-26oLcc {
  color: var(--accent-color); }

.after_inlineCode-1KfVgj,
.before_inlineCode-1G9rTK,
.inlineCode-2ngu6Y {
  color: #ccc; }

.slateTextArea-1Mkdgw {
  caret-color: var(--input-text-color) !important; }

.placeholder-37qJjk,
.scrollableContainer-2NUZem .markup-2BOw-j {
  margin-left: 8px; }

.channelTextAreaDisabled-rZtG8r {
  opacity: 1; }

.attachWrapper-2TRKBi,
.attachWrapper-1_D-pj {
  border: none; }

.attachButton-2WznTc,
.attachButton-1UjEWA {
  width: 44px;
  height: 44px;
  margin: 0 -15px 0 0;
  padding: 0; }

.attachButtonPlus-jWVFah,
.attachButtonPlus-rUdX-B {
  fill: var(--accent-color) !important;
  opacity: 1; }

.attachButton-2WznTc:hover .attachButtonPlus-jWVFah,
.attachButton-1UjEWA:hover .attachButtonPlus-rUdX-B {
  transform: scale(1.1); }

.attachButtonDivider-3Glu60 {
  display: none; }

.textArea-12jD-V,
.textArea-2Spzkt {
  margin: 0 6px;
  padding: 0 10px 0 15px; }

.textArea-12jD-V,
.textArea-12jD-V::-webkit-input-placeholder {
  color: #444 !important;
  font-weight: 500 !important; }

.textArea-12jD-V::-webkit-scrollbar,
.textArea-2Spzkt::-webkit-scrollbar {
  width: 6px !important; }

.emojiButtonNormal-TdumYh,
.emojiButtonHovered-1rWNal {
  top: 0;
  right: 0;
  margin: 0;
  opacity: 1 !important; }

.spriteNormal-1wvG5n {
  opacity: 1;
  filter: none; }

.typing-2GQL18 {
  top: -24px;
  left: 0;
  padding: 0 4px;
  background: rgba(38, 38, 38, 0.85) !important;
  transition: 200ms ease-in-out; }
  .typing-2GQL18:hover {
    background: #262626 !important; }
  .typing-2GQL18 .cooldownWrapper-3joyFc {
    position: relative;
    right: 24px; }

.hasAutocomplete-2vGV2Z .scrollableContainer-2NUZem {
  border-radius: var(--textarea-radius); }

.autocomplete-3l_oCd {
  left: 0;
  bottom: calc(100% + 28px);
  background: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow) !important; }

.autocompleteRowVertical-q1K4ky {
  padding: 0; }

.selector-2IcQBU,
.base-1pYU8j {
  padding: 8px 0;
  border-radius: 0; }

.selectorSelected-1_M1WV,
[class*="theme-"] .selected-1Tbx07 {
  background: var(--menu-hover-color) !important; }

.content-Qb0rXO,
.contentTitle-2tG_sM {
  padding: 0 12px; }

.description-11DmNu,
.descriptionUsername-J_75O8,
.descriptionDiscriminator-3vUOCc {
  color: #aaa !important; }

.wrapper-39oAo3 {
  height: 72px;
  margin: 0;
  padding: 0;
  background: transparent;
  border-radius: 0; }

/* BOTTOM BAR -> CHAT FORM -> FORMAT TOOLBAR */
.toolbar-2bjZV7 {
  height: 36px;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow) !important; }
  .toolbar-2bjZV7:before {
    display: none; }
  .toolbar-2bjZV7 .button-qqmJ7w {
    transition: 0ms; }
    .toolbar-2bjZV7 .button-qqmJ7w:hover {
      background-color: var(--menu-hover-color); }
    .toolbar-2bjZV7 .button-qqmJ7w.active-2HPddW {
      background-color: var(--menu-select-color); }
    .toolbar-2bjZV7 .button-qqmJ7w:first-of-type {
      border-radius: var(--popout-radius) 0 0 var(--popout-radius); }
    .toolbar-2bjZV7 .button-qqmJ7w:last-of-type {
      border-radius: 0 var(--popout-radius) var(--popout-radius) 0; }

[class*="theme-"] .container-Qj4uIL {
  box-shadow: var(--default-shadow); }

.containerBackground-3PNziK {
  background-color: var(--popout-color);
  border-radius: 0;
  border: none; }
  .containerBackground-3PNziK:after {
    border-top-color: var(--popout-color); }

/*
 *
 *	SERVER USERS LIST
 *
 */
.membersWrap-2h-GB4 {
  position: relative;
  margin: 0 0 72px 0; }
  .membersWrap-2h-GB4:after {
    bottom: -72px; }

.members-1998pB,
.members-1998pB > div {
  background: var(--side-color) !important; }

/*
 *
 *	USER/SERVER SETTINGS
 *
 */
/* USER/SERVER SETTINGS -> MAIN VIEW */
.sidebarRegionScroller-3MXcoP {
  background: var(--side-color) !important; }

.contentRegionScroller-26nc1e,
.contentRegion-3nDuYy {
  background: var(--chat-color) !important; }

/* USER/SERVER SETTINGS -> SIDEBAR */
.side-8zPYf6 .item-PXvHYJ,
.side-8zPYf6 .item-PXvHYJ[style*="color: rgb(114, 137, 218)"],
#bd-settings-sidebar .ui-tab-bar-item,
#pubslayer .ui-tab-bar-item {
  background-color: transparent !important;
  border-radius: 0;
  color: #9f9f9f !important; }

.side-8zPYf6 .item-PXvHYJ:hover,
.side-8zPYf6 .itemHover-EnbcjT:hover,
#bd-settings-sidebar .ui-tab-bar-item:hover,
#pubslayer .ui-tab-bar-item:hover {
  background: transparent !important;
  color: #fff !important; }

.side-8zPYf6 .item-PXvHYJ.selected-3s45Ha,
.side-8zPYf6 .item-PXvHYJ[aria-selected="true"],
#bd-settings-sidebar .ui-tab-bar-item.selected,
#pubslayer .ui-tab-bar-item.selected {
  position: relative;
  background: transparent !important;
  color: #fff !important; }

.side-8zPYf6 .item-PXvHYJ.selected-3s45Ha:after,
.side-8zPYf6 .item-PXvHYJ[aria-selected="true"]:after,
#bd-settings-sidebar .ui-tab-bar-item.selected:after,
#pubslayer .ui-tab-bar-item.selected:after,
.side-8zPYf6 .item-PXvHYJ.role-3wi9Tf[style*="color: rgb(255, 255, 255);"]:after {
  content: " ";
  position: absolute;
  width: 4px;
  height: 80%;
  background: var(--accent-color);
  top: 0;
  left: 0;
  bottom: 0;
  margin: auto 0; }

.side-8zPYf6 .item-PXvHYJ.role-3wi9Tf[style*="color: rgb(255, 255, 255);"] {
  background-color: transparent !important;
  color: #fff !important; }

#bd-settings-sidebar .ui-tab-bar-header,
#pubslayer .ui-tab-bar-header {
  font-size: 12px;
  font-weight: 700;
  line-height: 16px;
  text-transform: uppercase; }

/*
 *
 *	USER SETTINGS
 *
 */
/* USER SETTINGS -> MY ACCOUNT */
.background-1QDuV2 {
  padding: 0;
  background-color: transparent; }

.fieldList-21DyL8 {
  background-color: transparent;
  border-radius: 0; }

.title-33m_XM,
.title-2HFmAi {
  margin-top: 16px; }

.subtitle-1DRiTc,
.subtitle-8DQCLU {
  margin-top: 0; }

.phoneField-38N1bJ {
  background-color: var(--input-bg);
  border-radius: var(--textarea-radius);
  border: none; }

.phoneField-38N1bJ .inputField-aNPXsv {
  background-color: transparent;
  color: var(--input-text-color); }

.phoneField-38N1bJ .inputField-aNPXsv::-webkit-input-placeholder {
  color: var(--input-text-color); }

.multiInputLast-33BbRU:before {
  display: none; }

.questionMark-3qBhGj {
  width: 24px;
  height: 24px;
  background-color: var(--accent-color);
  border-radius: 50%; }

.userSettingsAccount-2eMFVR .userInfoEditing-1CEzdT,
.userSettingsAccount-2eMFVR .userInfoViewing-16kqK3 {
  padding: 20px 0; }

.inputWrapper-31_8H8 {
  position: relative; }

.multiInputLast-1aQ3YA input {
  width: 50px;
  padding: 0 !important;
  color: #444 !important; }

.inputPrefix-2VAOGg {
  top: -4px;
  left: -36px;
  color: #444 !important;
  opacity: 1 !important; }

.questionMark-CWEQZn {
  width: 24px;
  height: 24px;
  margin: 0 -6px 0 0;
  background: transparent !important;
  border-radius: 50%;
  border: 1px solid #666; }

.questionMark-CWEQZn .icon-3a_Jgd {
  color: #666 !important; }

/* USER SETTINGS -> PRIVACY & SAFETY */
.checked-3_4uQ9[style*="border-color: rgb(67, 181, 129)"] {
  background-color: #43b581 !important; }

.checked-3_4uQ9[style*="border-color: rgb(250, 166, 26)"] {
  background-color: #faa61a !important; }

.checked-3_4uQ9[style*="border-color: rgb(240, 71, 71)"] {
  background-color: #f04747 !important; }

.checked-3_4uQ9[style*="border-color: rgb(67, 181, 129)"] path,
.checked-3_4uQ9[style*="border-color: rgb(250, 166, 26)"] path,
.checked-3_4uQ9[style*="border-color: rgb(240, 71, 71)"] path {
  fill: #fff !important; }

/* USER SETTINGS -> AUTHORIZED APPS */
.authedApp-mj2Hmd {
  padding: 20px 0; }

/* USER SETTINGS -> CONNECTIONS */
.inner-2Y6JuD {
  background-color: transparent !important;
  border-radius: var(--card-radius);
  border: none;
  transition: none; }
  .inner-2Y6JuD:hover {
    background-color: var(--menu-hover-color) !important; }

.accountList-33MS45 {
  padding: 0 0 20px 0;
  background-color: transparent !important;
  border-radius: 0;
  border: none;
  transition: none; }

.connection-1fbD7X,
.connectionHeader-2MDqhu {
  background-color: transparent; }

.connection-1fbD7X {
  border-radius: 0;
  border-bottom: 3px solid var(--card-border); }

.connectionHeader-2MDqhu {
  padding: 20px 0; }

.connectionOptionsWrapper-3KIj1Z {
  padding: 10px 0 0; }

.connectionOptionSwitch-3KNn-E {
  padding: 0; }

.connectionDelete-2Odoln {
  width: 24px;
  height: 24px;
  border-radius: 50%;
  border: var(--button-border);
  text-align: center;
  line-height: 26px; }

.connectionDelete-2Odoln:hover {
  border: var(--button-border-hover);
  transform: scale(1.075); }

.connectedAccountSeparator-2EgLhW {
  margin-left: 0;
  margin-right: 0; }

.integrationsWrapper-VkM_zO {
  padding: 20px 0; }

.integration-3kMeY4 {
  background: rgba(0, 0, 0, 0.35) !important;
  border: none; }

.integration-3kMeY4 .lookGhost-2Fn_0-.colorWhite-rEQuAQ {
  background: transparent !important; }

.integrationsWrapper-VkM_zO a {
  font-weight: 600;
  color: #999 !important; }

.lookGhost-2Fn_0-.colorWhite-rEQuAQ {
  transition: none; }

/* USER SETTINGS -> BILLING */
.card-VoqMMK form div:not([class]):first-child {
  padding: 0 0 10px 0 !important;
  border-bottom: 1px solid var(--card-border) !important; }

.card-VoqMMK form .lookFilled-1Gx00P.colorGreen-29iAKY:last-child {
  margin: 0 0 0 12px; }

.form-77IDep {
  min-height: 160px; }

.form-77IDep .content-2BXhLs {
  padding: 0 0 12px 0; }

.form-77IDep .content-2BXhLs .scroller-2FKFPG div:not([class]):first-child,
.measurement-36xDqs {
  overflow: visible !important; }

.form-77IDep .footer-2yfCgX button:first-child {
  margin: 0; }

.divider-3WKGWk {
  margin: 0 12px 12px;
  border-color: #424242 !important; }

.measurement-36xDqs .inputWrapper-2YCfto .cardIconSmall-2gJ6xX {
  top: 5px;
  left: 6px; }

.measurement-36xDqs .cardIconSmall-2gJ6xX + .inputWrapper-31_8H8 .input-cIJ7To {
  padding: 0 0 0 42px !important; }

.measurement-36xDqs .lookFilled-1Gx00P.colorBrand-3pXr91 {
  background: transparent !important;
  border: var(--button-border) !important; }

.codeRedemptionRedirect-1wVR4b {
  padding: 16px 0; }

/* USER SETTINGS -> DISCORD NITRO */
.subscriptionDuration-VRc7oX {
  opacity: 1; }

.viewAllIcon-3lQE_E {
  display: none; }

.lookLink-9FtZy-.colorPrimary-3b3xI6.giftButton-3hOWFt {
  margin: 0; }

.tier1Banner-1B_WXY {
  background-color: var(--chat-box-color) !important;
  border-radius: 0; }

.verticalButtons-3jkiMb .newSubscriptionButton-eMLHPG + .newSubscriptionButton-eMLHPG {
  margin: 12px 0 0 0; }

/* USER SETTINGS -> SUBSCRIPTIONS */
.detailsBlock-FoDTGA {
  padding: 0;
  background-color: transparent; }

[class*="theme-"] .feature-2w65J5,
.featureStickers-Pc_FBx .stickerImageSection-7EUs8E {
  background-color: var(--card-color);
  border-radius: var(--card-radius); }

.feature-2w65J5.featureStickers-Pc_FBx {
  padding: 16px 0 0;
  background-color: transparent; }

/* USER SETTINGS -> VOICE AND VIDEO */
.micTestButton-3lpP11 {
  width: 160px !important;
  min-width: 160px !important;
  max-width: 160px !important; }

.micTestCaption-r5_z_T {
  left: 168px; }

.wrapper-3Z-vWm {
  height: 4px; }

.wrapper-3Z-vWm .container-3PXSwK {
  width: 100% !important; }

.container-3PXSwK[style*='background: linear-gradient(to right, rgb(251, 184, 72), rgb(67, 181, 129));'] {
  background: var(--slider-color) !important;
  border-radius: 2px; }

.progress-1IcQ3A {
  background-color: var(--slider-background) !important;
  border-radius: 2px; }

.notches-1sAcEM {
  background-image: none !important; }

/* USER SETTINGS -> OVERLAY */
.wrapper-3jrx9n {
  border: 1px solid var(--accent-color); }

.option-n0icdO:hover,
.selected-mKYnfr.option-n0icdO {
  background-color: var(--accent-color); }

/* USER SETTINGS -> NOTIFICATIONS */
.notificationsSound-27jFSh {
  border-bottom: 1px solid var(--card-border) !important;
  box-shadow: none !important; }

.notificationsSound-27jFSh:last-child {
  border-bottom: none !important; }

/* USER SETTINGS -> GAMES ACTIVITY */
.notDetected-33MY4s,
.nowPlaying-284llR {
  padding: 16px 0; }

.card-FDVird:before {
  background-color: var(--menu-hover-color) !important;
  border-radius: 0;
  border: none; }

.game-1ipmAa {
  box-shadow: 0 1px 0 0 var(--card-border) !important; }

.game-1ipmAa:hover {
  box-shadow: none !important; }

.user-settings-games .overlay-warning-icon {
  z-index: 2; }

.game-1ipmAa .removeGame-2JFGPn {
  background-color: var(--chat-color) !important;
  background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Ik0xOSw2LjQxTDE3LjU5LDVMMTIsMTAuNTlMNi40MSw1TDUsNi40MUwxMC41OSwxMkw1LDE3LjU5TDYuNDEsMTlMMTIsMTMuNDFMMTcuNTksMTlMMTksMTcuNTlMMTMuNDEsMTJMMTksNi40MVoiIC8+Cjwvc3ZnPg==) !important;
  background-size: 75%;
  box-shadow: none !important;
  border: 1px solid #fff;
  transition: none; }

.game-1ipmAa .removeGame-2JFGPn:hover {
  transform: scale(1.075); }

.addGamePopout-2RY8Ju {
  border-radius: 0;
  background: var(--popout-color) !important; }

.elevationBorderHigh-2WYJ09 {
  box-shadow: var(--default-shadow) !important; }

.addGamePopout-2RY8Ju .lookFilled-1Gx00P.colorBrand-3pXr91 {
  margin: 0 0 0 12px; }

/* USER SETTINGS -> GAME LIBRARY */
.foreground-2aE44H {
  stroke: var(--accent-color) !important; }

/* USER SETTINGS -> APPEARANCE */
.preview-2nSL_2 {
  background-color: var(--chat-color);
  border-radius: 0;
  border-color: var(--card-border); }

.bar-2Qqk5Z {
  height: 4px;
  background: var(--slider-background) !important;
  border-radius: 3px; }

.barFill-23-gu-,
.userSettingsVoice-iwdUCU .inputSensitivityToggle-2LKb8o.manual-36Evg9 .microphone-2rtdHw .fill-3eUagR {
  background: var(--slider-color);
  border-radius: 2px; }

.grabber-3mFHz2 {
  width: 12px;
  height: 12px;
  top: 25px;
  border-radius: 6px;
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.35);
  border: none;
  opacity: 0; }

.slider-1PF9SW:hover .barFill-23-gu-,
.slider-1PF9SW:hover .userSettingsVoice-iwdUCU .inputSensitivityToggle-2LKb8o.manual-36Evg9 .microphone-2rtdHw .fill-3eUagR {
  background: var(--accent-color) !important; }

.slider-1PF9SW:hover .grabber-3mFHz2 {
  opacity: 1; }

.mark-1xjQqt {
  height: 34px; }

/* USER SETTINGS -> OVERLAY */
.container-CpszHS .input-1UhAnY {
  padding: 0 16px !important;
  background: transparent !important;
  border-radius: 0 !important; }

.container-CpszHS .lookGhost-2Fn_0-.colorGrey-2DXtkV {
  padding: 0 18px !important; }

.container-CpszHS .editIcon-13gaox {
  background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Ik0xOSwxMEgxN1Y4SDE5TTE5LDEzSDE3VjExSDE5TTE2LDEwSDE0VjhIMTZNMTYsMTNIMTRWMTFIMTZNMTYsMTdIOFYxNUgxNk03LDEwSDVWOEg3TTcsMTNINVYxMUg3TTgsMTFIMTBWMTNIOE04LDhIMTBWMTBIOE0xMSwxMUgxM1YxM0gxMU0xMSw4SDEzVjEwSDExTTIwLDVINEMyLjg5LDUgMiw1Ljg5IDIsN1YxN0EyLDIgMCAwLDAgNCwxOUgyMEEyLDIgMCAwLDAgMjIsMTdWN0MyMiw1Ljg5IDIxLjEsNSAyMCw1WiIgLz4KPC9zdmc+); }

.container-CpszHS.recording-1H2dS7 {
  border-color: rgba(var(--accent-rgb), 0.9);
  box-shadow: 0 0 9px rgba(var(--accent-rgb), 0.6);
  color: #fff;
  animation: shadowPulse-2kjgqQ 1s ease-in infinite; }

@keyframes shadowPulse-2kjgqQ {
  0% {
    box-shadow: 0 0 9px rgba(var(--accent-rgb), 0.6); }
  50% {
    box-shadow: 0 0 13px rgba(var(--accent-rgb), 0.9); }
  to {
    box-shadow: 0 0 9px rgba(var(--accent-rgb), 0.6); } }
/*
 *
 *	SERVER SETTINGS
 *
 */
/* SERVER SETTINGS -> AUDIT LOG */
.auditLog-3jNbM6 {
  background: transparent !important;
  border-radius: 0;
  box-shadow: none !important;
  border: none !important;
  border-bottom: 1px solid var(--card-border) !important; }

.headerClickable-2IVFo9,
.headerDefault-1wrJcN,
.headerExpanded-CUEwZ5 {
  padding: 10px 0;
  background: transparent !important; }

.divider-1pnAR2 {
  display: none; }

.changeDetails-bk98pu {
  background: transparent !important; }

/* SERVER SETTINGS -> ROLES */
.cardWarning-2yPNAa {
  background-color: var(--accent-color);
  border: none; }

.scroller-305q3I {
  background-color: transparent; }

/* SERVER SETTINGS -> WIDGET */
.inputDefault-A2ud2y,
.inputError-reIyaS {
  color: #444 !important;
  font-weight: 500 !important; }

.button-38qaLQ {
  margin: 4px 7px 4px 0; }

/*
 *
 *	VOICE AND VIDEO CHAT/SCREENSHARING
 *
 */
.header-3po9qd {
  padding-top: 0; }

.tile-2silOL {
  padding: 0; }

.streamPreview-2-WUWT {
  background-color: var(--popout-color) !important;
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

/* VOICE AND VIDEO CHAT/SCREENSHARING -> PiP */
.topControls-1PHLxx .container-1r6BKw {
  background: transparent !important; }

/*
 *
 *	CARDS
 *
 */
.cardPrimary-1Hv-to,
.cardPrimaryEditable-3KtE4g,
.card-7JP0BX,
.authedApp-mj2Hmd,
.notDetected-33MY4s,
.nowPlaying-284llR,
.codeRedemptionRedirect-1wVR4b,
.bda-slist li {
  background: transparent !important;
  border-radius: 0 !important;
  border: none !important;
  border-bottom: 3px solid var(--card-border) !important; }

.cardPrimary-1Hv-to.formNotice-2_hHWR,
.cardPrimaryEditable-3KtE4g[style*="padding: 10px"] {
  padding: 20px 0 !important; }

.card-VoqMMK {
  padding: 0 0 20px 0 !important; }

.card-7JP0BX {
  background: transparent !important; }

.divider-3573oO {
  background: var(--card-border) !important;
  border: none; }

.divider-3573oO.marginBottom40-2vIwTv {
  margin-bottom: 20px; }

.marginTop40-i-78cZ {
  margin-top: 30px; }

.marginTop60-3PGbtK {
  margin-top: 40px; }

.bda-slist li {
  max-height: 250px;
  margin: 0 0 30px 0;
  padding: 12px 0;
  overflow: visible; }

.bda-slist li:first-child {
  margin: 20px 0 30px 0; }

.bda-slist li.settings-open {
  overflow-y: auto !important; }

.bda-slist li * {
  color: #b2b2b2; }

.bda-slist li .titleDefault-a8-ZSr.size18-3EXdSj {
  width: 100%;
  margin: 0 0 16px 0 !important;
  padding: 0 0 8px 0;
  border-bottom: 1px solid var(--card-border);
  font-weight: 700;
  color: #b2b2b2; }

.settings-open {
  position: relative; }

.settings-open div[style="float: right; cursor: pointer;"] {
  position: absolute;
  top: 14px;
  right: 0;
  float: none !important; }

/*#bd-settingspane-container .ui-switch-item {
	border-bottom: 3px solid var(--card-border) !important;
	overflow: visible;
}*/
.bda-slist .bda-header {
  padding: 0 0 8px 0;
  font-size: 16px; }

.bda-slist .bda-header .bda-controls button {
  padding: 0 3px !important; }

.bda-slist .bda-header .bda-controls button .icon-GhnIRB {
  transform: scale(0.8) translateY(3px); }

.bda-slist .bda-description-wrap {
  padding: 8px 0; }

.bda-slist .bda-header,
.bda-slist .bda-footer {
  border-color: var(--card-border); }

.bda-slist .bda-footer {
  padding: 12px 0 0 0;
  overflow: visible; }

#bd-settingspane-container .ui-switch-item .style-description {
  margin: -1px 0 20px 0;
  padding: 0 0 15px 0;
  border-bottom: 1px solid var(--card-border); }

/* CARDS -> PUBLIC SERVERS */
.bd-server-card {
  margin: 0 0 40px 0 !important;
  border-color: var(--card-border) !important; }

.bd-server-card.bd-server-card-pinned:after {
  display: none; }

.bd-server-content {
  padding: 0 0 0 12px; }

.bd-server-header {
  height: 24px; }

.bd-server-description-container {
  border-top: 1px solid var(--card-border);
  border-bottom: 1px solid var(--card-border); }

.bd-server-footer {
  padding: 8px 0; }

.bd-server-card .bd-server-tags {
  line-height: 32px; }

#pubslayer button {
  margin: 0 !important; }

/*
 *
 *	BUTTONS
 *
 */
.lookFilled-1Gx00P.colorPrimary-3b3xI6,
.lookFilled-1Gx00P.colorBrand-3pXr91,
.lookFilled-1Gx00P.colorGreen-29iAKY,
.lookFilled-1Gx00P.colorRed-1TFJan,
.lookFilled-1Gx00P.colorGrey-2DXtkV,
.lookFilled-1Gx00P.colorWhite-rEQuAQ,
.lookFilled-1Gx00P.colorTransparent-1ewNp9,
.lookOutlined-3sRXeN.colorPrimary-3b3xI6,
.lookOutlined-3sRXeN.colorBrand-3pXr91,
.lookOutlined-3sRXeN.colorGreen-29iAKY,
.lookOutlined-3sRXeN.colorRed-1TFJan,
.lookOutlined-3sRXeN.colorGrey-2DXtkV,
.lookOutlined-3sRXeN.colorWhite-rEQuAQ,
.lookOutlined-3sRXeN.colorTransparent-1ewNp9,
.lookLink-9FtZy-.colorPrimary-3b3xI6,
.lookLink-9FtZy-.colorBrand-3pXr91,
.lookLink-9FtZy-.colorWhite-rEQuAQ,
.lookLink-9FtZy-.colorGrey-2DXtkV,
.lookInverted-2D7oAl.colorBrand-3pXr91,
.lookInverted-2D7oAl.colorGreen-29iAKY,
.lookGhost-2Fn_0-.colorWhite-rEQuAQ,
.copyInput-2rOSt7 .lookGhost-2Fn_0-.colorGrey-2DXtkV,
.streamerModeEnabledBtn-2ZJ2eq,
.channelNotices-41mJbj .channelNotice-1-XFjC .message-3SOT5P .btn-11C5_u,
.headerButtonColor-G7_f-V,
.disabledButtonColor-RDvfEC,
.disabledButton-3apIHo,
.hasMore-3e72_v,
.searchQuery-1B7rtx .keybindShortcut-1BD6Z1 span,
.action-yrVND8,
.learnMoreButton-1OUyxs,
.header-1RC2Wb .button-38aScr,
.actionButton-2PeQbJ,
.cancelButton-RGXhAE,
.backButton-25HgIF,
.shareButton-3w0M74,
.watchButton-2SbJEo,
.button-3tQuzi,
.button-1MICoQ,
.button,
.keybindShortcutSearchPopout-1MAfqq,
.bd-pfbtn,
.bda-slist .bda-footer button,
#pubslayer button[style*="background-color: rgb(58, 193, 92)"],
.pluginrepo-modal .pluginEntry.downloadable .btn-download,
.bda-slist li button,
.plugin-settings .lookFilled-1Gx00P.colorBrand-3pXr91,
.plugin-settings .lookFilled-1Gx00P.colorRed-1TFJan,
.dc-button,
.smalltalk button,
.form-deprecated .btn-primary,
.form.deprecated .btn-primary,
.create-guild-container.deprecated .form-actions .btn-default,
.regionSelect-3lf4eE button {
  height: 32px !important;
  min-height: 32px !important;
  max-height: 32px !important;
  padding: 0 30px !important;
  line-height: 24px !important;
  background: var(--button-background) !important;
  border-radius: 16px !important;
  border: var(--button-border) !important;
  font-size: 14px !important;
  font-weight: 400 !important;
  color: #fff !important;
  text-transform: uppercase !important;
  transition: border 0ms ease !important; }

/* BUTTONS -> HOVER */
.lookFilled-1Gx00P.colorPrimary-3b3xI6:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.lookFilled-1Gx00P.colorGreen-29iAKY:hover,
.lookFilled-1Gx00P.colorRed-1TFJan:hover,
.lookFilled-1Gx00P.colorGrey-2DXtkV:hover,
.lookFilled-1Gx00P.colorWhite-rEQuAQ:hover,
.lookFilled-1Gx00P.colorTransparent-1ewNp9:hover,
.lookOutlined-3sRXeN.colorPrimary-3b3xI6:hover,
.lookOutlined-3sRXeN.colorBrand-3pXr91:hover,
.lookOutlined-3sRXeN.colorGreen-29iAKY:hover,
.lookOutlined-3sRXeN.colorWhite-rEQuAQ:hover,
.lookOutlined-3sRXeN.colorRed-1TFJan:hover,
.lookOutlined-3sRXeN.colorTransparent-1ewNp9:hover,
.lookLink-9FtZy-.colorPrimary-3b3xI6:hover,
.lookLink-9FtZy-.colorBrand-3pXr91:hover,
.lookLink-9FtZy-.colorWhite-rEQuAQ:hover,
.lookLink-9FtZy-.colorGrey-2DXtkV:hover,
.lookInverted-2D7oAl.colorBrand-3pXr91:hover,
.lookInverted-2D7oAl.colorGreen-29iAKY:hover,
.lookGhost-2Fn_0-.colorWhite-rEQuAQ:hover,
.copyInput-2rOSt7 .lookGhost-2Fn_0-.colorGrey-2DXtkV:hover,
.streamerModeEnabledBtn-2ZJ2eq:hover,
.channelNotices-41mJbj .channelNotice-1-XFjC .message-3SOT5P .btn-11C5_u:hover,
.headerButtonColor-G7_f-V:hover,
.disabledButtonColor-RDvfEC:hover,
.searchQuery-1B7rtx .keybindShortcut-1BD6Z1 span:hover,
.action-yrVND8:hover,
.header-1RC2Wb .button-38aScr:hover,
.actionButton-2PeQbJ:hover,
.cancelButton-RGXhAE:hover,
.backButton-25HgIF:hover,
.shareButton-3w0M74:hover,
.hasMore-3e72_v:hover,
.watchButton-2SbJEo:hover,
.button-3tQuzi:hover,
.button-1MICoQ:hover,
.button:hover,
.dismiss-SCAH9H:hover,
.learnMoreButton-1OUyxs:hover,
.bd-pfbtn:hover,
.bda-slist .bda-footer button:hover,
.pluginrepo-modal .pluginEntry.downloadable .btn-download:hover,
.bda-slist li button:hover,
.dc-button:hover,
.smalltalk button:hover,
.form-deprecated .btn-primary:hover,
.form.deprecated .btn-primary:hover,
.create-guild-container.deprecated .form-actions .btn-default:hover,
.regionSelect-3lf4eE button:hover {
  transform: scale(1.05);
  border: var(--button-border-hover) !important;
  box-shadow: none; }

.lookFilled-1Gx00P.colorPrimary-3b3xI6:active:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:active:hover,
.lookFilled-1Gx00P.colorGreen-29iAKY:active:hover,
.lookFilled-1Gx00P.colorRed-1TFJan:active:hover,
.lookFilled-1Gx00P.colorGrey-2DXtkV:active:hover,
.lookFilled-1Gx00P.colorTransparent-1ewNp9:active:hover,
.lookOutlined-3sRXeN.colorPrimary-3b3xI6:active:hover,
.lookOutlined-3sRXeN.colorBrand-3pXr91:active:hover,
.lookOutlined-3sRXeN.colorGreen-29iAKY:active:hover,
.lookOutlined-3sRXeN.colorWhite-rEQuAQ:active:hover,
.lookOutlined-3sRXeN.colorRed-1TFJan:active:hover,
.lookFilled-1Gx00P.colorWhite-rEQuAQ:active:hover,
.lookOutlined-3sRXeN.colorTransparent-1ewNp9:active:hover,
.lookLink-9FtZy-.colorPrimary-3b3xI6:active:hover,
.lookLink-9FtZy-.colorBrand-3pXr91:active:hover,
.lookLink-9FtZy-.colorWhite-rEQuAQ:active:hover,
.lookLink-9FtZy-.colorGrey-2DXtkV:active:hover,
.lookInverted-2D7oAl.colorBrand-3pXr91:active:hover,
.lookInverted-2D7oAl.colorGreen-29iAKY:active:hover,
.lookGhost-2Fn_0-.colorWhite-rEQuAQ:active:hover,
.copyInput-2rOSt7 .lookGhost-2Fn_0-.colorGrey-2DXtkV:active:hover,
.streamerModeEnabledBtn-2ZJ2eq:active:hover,
.channelNotices-41mJbj .channelNotice-1-XFjC .message-3SOT5P .btn-11C5_u:active,
.headerButtonColor-G7_f-V:active:hover,
.disabledButtonColor-RDvfEC:active:hover,
.searchQuery-1B7rtx .keybindShortcut-1BD6Z1 span:active:hover,
.action-yrVND8:active:hover,
.header-1RC2Wb .button-38aScr:active:hover,
.actionButton-2PeQbJ:active:hover,
.cancelButton-RGXhAE:active:hover,
.backButton-25HgIF:active:hover,
.shareButton-3w0M74:active:hover,
.hasMore-3e72_v:active:hover,
.watchButton-2SbJEo:active:hover,
.button-3tQuzi:active:hover,
.button-1MICoQ:active:hover,
.button:active:hover,
.dismiss-SCAH9H:active:hover,
.learnMoreButton-1OUyxs:active:hover,
.bd-pfbtn:active:hover,
.bda-slist .bda-footer button:active:hover,
.pluginrepo-modal .pluginEntry.downloadable .btn-download:active:hover,
.bda-slist li button:active:hover,
.dc-button:active:hover,
.smalltalk button:active:hover,
.form-deprecated .btn-primary:active:hover,
.form.deprecated .btn-primary:active:hover,
.create-guild-container.deprecated .form-actions .btn-default:active:hover,
.regionSelect-3lf4eE button:active:hover {
  transform: scale(1);
  opacity: 0.5 !important; }

.shareButton-3w0M74:hover {
  transform: scale(1.05) !important; }

.shareButton-3w0M74:active,
.shareButton-3w0M74:active:hover {
  transform: scale(1) !important;
  opacity: 1 !important; }

/* BUTTONS -> DISABLED */
.lookFilled-1Gx00P.colorBrand-3pXr91:disabled,
.lookFilled-1Gx00P.colorGreen-29iAKY:disabled,
.lookFilled-1Gx00P.colorGrey-2DXtkV:disabled,
.lookOutlined-3sRXeN.colorWhite-rEQuAQ:disabled,
.disabledButtonColor-RDvfEC,
.button-1YfofB.buttonColor-7qQbGO.fauxDisabled-2ik0Vw,
.bda-slist .bda-footer button:disabled,
#pubslayer button[style*="background-color: rgb(58, 193, 92)"] {
  transform: scale(1);
  cursor: not-allowed;
  opacity: 0.4 !important; }

/* BUTTONS -> CONTENTS */
.button-38aScr .contents-18-Yxp {
  margin: 0 !important;
  font-size: 12px;
  font-weight: 600; }

/* BUTTONS -> CONTENTS -> REMOVE CONTENTS HOVER */
.lookLink-9FtZy-.colorPrimary-3b3xI6:hover .contents-18-Yxp,
.lookLink-9FtZy-.colorBrand-3pXr91:hover .contents-18-Yxp,
.lookLink-9FtZy-.colorWhite-rEQuAQ:hover .contents-18-Yxp,
.lookLink-9FtZy-.colorGrey-2DXtkV:hover .contents-18-Yxp,
.uploadModal-2ifh8j .footer-3mqk7D .button:hover,
.buttonText-13IoY7,
.header-1RC2Wb .button-38aScr .buttonText-2DJbpf {
  padding: 0 !important;
  background: transparent !important;
  border-bottom: none !important;
  text-decoration: none !important; }

.backButton-25HgIF:hover {
  text-decoration: none !important; }

/* BUTTONS -> RESIZE LARGE BUTTONS */
.sizeLarge-1vSeWK,
.sizeXlarge-2yFAlZ {
  min-width: 32px;
  flex: 0 1 auto; }

/* BUTTONS -> ACCENT */
.lookFilled-1Gx00P.colorGreen-29iAKY,
.lookFilled-1Gx00P.colorBrand-3pXr91,
.copyInput-2rOSt7 .lookGhost-2Fn_0-.colorGrey-2DXtkV,
.button-3tQuzi,
.uploadModal-2ifh8j .footer-3mqk7D .button-primary,
.uploadModal-2ifh8j .footer-3mqk7D .button-primary:hover,
.create-guild-container.deprecated .form-actions .btn + .btn,
.hasMore-3e72_v,
#dc-unlock-database-btn.dc-button,
.header-1RC2Wb .button-38aScr:not(:disabled) {
  background: var(--accent-color) !important;
  background-color: var(--accent-color) !important;
  border: 1px solid var(--accent-color) !important;
  font-weight: 500 !important;
  opacity: 1; }

.lookFilled-1Gx00P.colorGreen-29iAKY:hover,
.lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.copyInput-2rOSt7 .lookGhost-2Fn_0-.colorGrey-2DXtkV:hover,
.button-3tQuzi:hover,
.uploadModal-2ifh8j .footer-3mqk7D .button-primary:hover,
.uploadModal-2ifh8j .footer-3mqk7D .button-primary:hover,
.create-guild-container.deprecated .form-actions .btn + .btn:hover,
.hasMore-3e72_v:hover,
#dc-unlock-database-btn.dc-button:hover,
.header-1RC2Wb .button-38aScr:not(:disabled):hover {
  background: var(--accent-hover) !important;
  border: 1px solid var(--accent-hover) !important; }

/* BUTTONS -> ALERT/ERROR */
.lookFilled-1Gx00P.colorRed-1TFJan,
.lookOutlined-3sRXeN.colorRed-1TFJan,
.actionButtons-3P85gM .lookFilled-1Gx00P.colorTransparent-1ewNp9 {
  background: var(--alert-color) !important;
  border: 1px solid var(--alert-color) !important;
  /*border: 1px solid var(--alert-color) !important;
  color: var(--alert-color) !important;*/ }

.lookFilled-1Gx00P.colorRed-1TFJan:hover,
.lookOutlined-3sRXeN.colorRed-1TFJan:hover {
  background: var(--alert-hover) !important;
  border: 1px solid var(--alert-hover) !important; }

.lookFilled-1Gx00P.colorRed-1TFJan,
.actionRed-gYn8D3 {
  background: var(--alert-color) !important;
  border: 1px solid var(--alert-color) !important;
  color: #fff !important; }

/* BUTTONS -> NORMAL COLOR */
.userSettingsAccount-2eMFVR .lookFilled-1Gx00P.colorBrand-3pXr91,
.userSettingsAccount-2eMFVR .lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.userSettingsSecurity-3IYeMF .lookFilled-1Gx00P.colorBrand-3pXr91,
.userSettingsSecurity-3IYeMF .lookFilled-1Gx00P.colorBrand-3pXr9:hover,
.headerActions-2l3Hou .button-38aScr:not(:disabled) + .button-38aScr {
  background: var(--button-background) !important;
  border: var(--button-border) !important;
  font-weight: 400 !important; }

.userSettingsAccount-2eMFVR .lookFilled-1Gx00P.colorBrand-3pXr91:hover,
.userSettingsSecurity-3IYeMF .lookFilled-1Gx00P.colorBrand-3pXr91:hover {
  border: var(--button-border-hover) !important; }

/* BUTTONS -> NOTICE BAR BUTTONS */
.button-1MICoQ {
  height: 24px !important;
  min-height: 24px !important; }

.dismiss-SCAH9H {
  height: 24px;
  width: 24px;
  top: 5px;
  right: 5px;
  background: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHhtbG5zOnhsaW5rPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5L3hsaW5rIiB2ZXJzaW9uPSIxLjEiICB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCI+CiAgIDxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Ik0xOSw2LjQxTDE3LjU5LDVMMTIsMTAuNTlMNi40MSw1TDUsNi40MUwxMC41OSwxMkw1LDE3LjU5TDYuNDEsMTlMMTIsMTMuNDFMMTcuNTksMTlMMTksMTcuNTlMMTMuNDEsMTJMMTksNi40MVoiIC8+Cjwvc3ZnPg==) no-repeat 50%;
  background-size: 60%;
  border-radius: 50%;
  border: 1px solid #fff;
  opacity: 1; }

.button-3tQuzi,
.copyInput-2rOSt7 .lookGhost-2Fn_0-.colorGrey-2DXtkV {
  height: 24px !important;
  min-height: 24px !important;
  margin: 4px 8px 4px 0 !important; }

/* BUTTONS -> REMOVE STYLING */
.lookFilled-1Gx00P.colorGreen-29iAKY.btn-enableall,
.lookFilled-1Gx00P.colorRed-1TFJan.btn-disableall,
.lookLink-9FtZy-.colorPrimary-3b3xI6.giftButton-3hOWFt {
  padding: 0 !important;
  background: transparent !important;
  border-color: transparent !important; }

.lookFilled-1Gx00P.colorGreen-29iAKY.btn-enableall:hover,
.lookFilled-1Gx00P.colorRed-1TFJan.btn-disableall:hover,
.lookLink-9FtZy-.colorPrimary-3b3xI6.giftButton-3hOWFt:hover {
  transform: scale(1); }

/* BUTTONS -> LOAD MORE MESSAGES */
.hasMore-3e72_v {
  margin: 46px 14px 6px 20px;
  border: none !important;
  line-height: 32px !important; }

.hasMore-3e72_v:hover {
  border: none !important;
  transform: scale(1.025) !important; }

/* BUTTONS -> BETTERDISCORD BUTTONS */
.plugin-settings .lookFilled-1Gx00P.colorBrand-3pXr91 .contents-18-Yxp,
.plugin-settings .lookFilled-1Gx00P.colorRed-1TFJan .contents-18-Yxp {
  color: #fff !important; }

.plugin-settings .flex-1O1GKY.flex-1xMQg5.horizontal-1ae9ci.horizontal-2EEEnY button:last-child {
  margin: 0 0 0 12px !important; }

.bda-slist li button:not(.bda-settings-button) {
  margin: 0 12px 0 0; }

/*
 *
 *	INPUTS & TEXTAREAS
 *
 */
.input-cIJ7To,
.input-3Xdcic,
.input-1UhAnY,
.container-CpszHS,
.container-1s4HBn,
.search .search-bar,
.searchBar-1MOL6S,
.header-1R_AjF .search-bar,
.quickMessage-2XpSaN,
.wrapper-1cBijl .addFriendInput-4bcerK,
.input-2VB9rf,
.copyInput-2rOSt7,
#pubslayer input,
.bda-slist li input:not([type="range"]),
.search-2oPWTC .searchBar-3dMhjb,
.searchBar-2_Yu-C input,
.form.deprecated .control-group input[type=text],
.dc-password-field,
.searchBar-6Kv8R2 .searchBarComponent-32dTOx input {
  height: 32px !important;
  padding: 0 12px !important;
  background: var(--input-bg) !important;
  box-shadow: none !important;
  border-radius: var(--textarea-radius) !important;
  border: none !important;
  font-weight: 500 !important;
  font-size: 14px !important;
  color: var(--input-text-color) !important; }

.input-3Xdcic::-webkit-input-placeholder,
.input-cIJ7To::-webkit-input-placeholder,
.input-1UhAnY,
.header-1R_AjF .search-bar input::-webkit-input-placeholder,
.quickMessage-2XpSaN::-webkit-input-placeholder,
.wrapper-1cBijl .addFriendInput-4bcerK::-webkit-input-placeholder,
.input-2VB9rf::-webkit-input-placeholder,
.copyInput-2rOSt7::-webkit-input-placeholder,
#pubslayer input::-webkit-input-placeholder,
.bda-slist li input:not([type="range"])::-webkit-input-placeholder,
.form.deprecated .control-group input[type=text]::-webkit-input-placeholder,
.search-2oPWTC .searchBar-3dMhjb::-webkit-input-placeholder,
.searchBar-2_Yu-C input::-webkit-input-placeholder,
.searchBar-1MOL6S .input-3Xdcic::-webkit-input-placeholder,
.searchBar-6Kv8R2 .searchBarComponent-32dTOx input::-webkit-input-placeholder {
  height: 100% !important;
  line-height: 32px !important;
  font-size: 14px !important;
  font-weight: 500 !important;
  color: var(--input-placeholder-color) !important; }

.search-2oPWTC .searchBar-3dMhjb,
.search-2oPWTC .DraftEditor-root .DraftEditor-editorContainer,
.search-2oPWTC .DraftEditor-root .public-DraftStyleDefault-block,
.search-2oPWTC .DraftEditor-root .public-DraftEditorPlaceholder-root {
  height: 28px !important;
  line-height: 28px !important; }

.search-2oPWTC .DraftEditor-root,
.search-2oPWTC .searchBar-3dMhjb,
.search-2oPWTC .DraftEditor-root .public-DraftEditorPlaceholder-root {
  color: var(--input-text-color) !important; }

.search-2oPWTC .DraftEditor-root .public-DraftEditorPlaceholder-root {
  padding-bottom: 0; }

.search-2oPWTC .DraftEditor-root .public-DraftStyleDefault-block span {
  height: 24px;
  /*padding: 0 3px;*/
  line-height: 24px; }

.inputPrefix-1gzNds {
  top: 8px;
  color: var(--input-text-color); }

.inputPrefix-1gzNds + .input-cIJ7To {
  padding: 0 12px 0 28px !important; }

.searchFilter-2ESiM3,
.searchFilter-2ESiM3 + span[data-offset-key],
.searchAnswer-3Dz2-q span[data-offset-key] {
  background: var(--menu-select-color) !important; }

.searchAnswer-3Dz2-q {
  background: transparent !important; }

.searchFilter-2ESiM3 {
  margin: 0;
  padding: 0 4px 0 8px;
  border-radius: 11px 0 0 11px; }

.searchFilter-2ESiM3:only-child {
  padding: 0 8px;
  border-radius: 11px; }

.searchFilter-2ESiM3 + span[data-offset-key],
.searchAnswer-3Dz2-q span[data-offset-key] {
  display: inline-block;
  height: 20px;
  margin: 0 2px 0 0;
  padding: 0px 8px 0px 0;
  border-radius: 0 11px 11px 0;
  color: #fff; }

.clear-1pMieT .icon-3cZ1F_ {
  color: #444; }

.input-cIJ7To .input-cIJ7To {
  padding: 0 !important; }

.searchBar-6Kv8R2 .search-bar,
.searchBar-6Kv8R2 .search-bar-inner {
  background: transparent !important; }

.search .search-bar {
  height: 28px !important;
  padding: 0 4px !important; }

.search .DraftEditor-root,
.search .public-DraftEditorPlaceholder-root,
.searchBar-1MOL6S .input-3Xdcic {
  line-height: 22px;
  color: #444 !important; }

.searchBar-1MOL6S .input-3Xdcic {
  padding: 0; }

textarea.input-cIJ7To {
  height: auto !important;
  min-height: 32px !important;
  max-height: 400px !important;
  padding: 8px 12px !important;
  line-height: 16px !important; }

textarea.input-cIJ7To::-webkit-input-placeholder {
  line-height: 16px !important; }

.searchBar-6Kv8R2 .searchBarComponent-32dTOx {
  height: 32px;
  padding: 0 12px;
  background: var(--input-bg);
  border-radius: 16px;
  color: var(--input-text-color); }

.searchBar-6Kv8R2 .searchBarComponent-32dTOx input {
  margin: 0; }

.searchBar-6Kv8R2 .searchBarComponent-32dTOx .inner-3ErfOT {
  padding: 0; }

/* INPUTS & TEXTAREAS -> SELECT OPTION */
.lookFilled-22uAsw.select-2fjwPw,
.css-1a8reka-control,
.css-2yldzf-control,
.css-1yegjoj-control,
.css-17yssst-control,
.css-gd8if9-control,
.css-gvi9bl-control,
.css-6fzn47-control,
.css-17e1tep-control,
.css-118dehu-control {
  min-height: 32px;
  height: 32px;
  background: var(--select-input-color);
  border-radius: 0;
  border: none; }

.searchable-1Zl-ns {
  padding-top: 0;
  padding-bottom: 0; }

.css-118dehu-control {
  opacity: 0.4; }

.css-2yldzf-control {
  opacity: 0.65; }

.css-1hwfws3 {
  height: 100%;
  padding: 0 8px; }

.css-1fhf191 {
  height: 100%; }

.css-12qlrak-indicatorContainer,
.css-1flfamv-indicatorContainer,
.css-95pa8n-indicatorContainer {
  height: 100%;
  padding: 6px 8px; }

.popout-VcNcHB,
.css-n57xjs-menu,
.css-3vaxre-menu {
  background: var(--select-input-color) !important;
  box-shadow: var(--default-shadow) !important;
  border: none; }

.option-3KoAJB.focused-1T6PE5,
.css-12o7ek3-option,
.css-1ba14n5-option {
  background-color: var(--menu-select-color) !important; }

.option-3KoAJB:focus,
.option-3KoAJB:hover,
.css-1gnr91b-option,
.css-1gnr91b-option:active,
.css-rzbxvl-option,
.css-rzbxvl-option:active {
  background-color: var(--menu-hover-color) !important; }

/* INPUTS & TEXTAREAS -> RADIOS */
div[role="radiogroup"] {
  background-color: var(--card-color);
  border-radius: var(--card-radius); }

.item-26Dhrx {
  background-color: transparent;
  border-radius: 0;
  overflow: hidden; }
  .item-26Dhrx[aria-checked=true] {
    background-color: var(--menu-hover-color);
    color: var(--accent-color); }
    .item-26Dhrx[aria-checked=true] .info-3LOr12 {
      color: var(--interactive-active); }
  .item-26Dhrx:first-child {
    border-radius: var(--card-radius) var(--card-radius) 0 0; }
  .item-26Dhrx:last-child {
    border-radius: 0 0 var(--card-radius) var(--card-radius); }
  .item-26Dhrx:only-child {
    border-radius: var(--card-radius); }
  .item-26Dhrx .radioBar-bMNUI- {
    border-radius: 0; }

.radioIconForeground-XwlXQN {
  color: var(--accent-color); }

/*
 *
 *	CHECKBOXES
 *
 */
.checkbox-3kaeSU .checkboxInner-3yjcPe .checkboxElement-1qV33p:checked + span,
.checkbox .checkbox-inner input[type=checkbox]:checked + span,
.checkbox-1ix_J3[style*="border-color: rgb(114, 137, 218)"] {
  background-color: var(--accent-color) !important;
  border-color: var(--accent-color) !important;
  transition: 300ms ease all !important; }

.checkbox-1ix_J3[style*="border-color: rgb(114, 137, 218)"] path {
  fill: #fff !important; }

.checkbox-1ix_J3[style*="border-color: rgb(114, 137, 218)"] polyline {
  stroke: #fff !important; }

.item-26Dhrx {
  margin: 0; }

/*.item-26Dhrx:last-child {
	border-bottom: 1px solid var(--card-border);
}*/
/* CHECKBOXES -> SWITCHES */
/* NEW SWITCHES */
.container-3auIfb[style*="background-color: rgb(67"],
.bd-switch-checked {
  background-color: var(--accent-color) !important; }

.container-3auIfb[style*="background-color: rgb(67"] svg path {
  fill: var(--accent-color) !important; }

/* */
.sizeDefault-2YlOZr.themeDefault-24hCdX,
.themeDefault-24hCdX.sizeDefault-2YlOZr,
.themeClear-1EjkE4.sizeDefault-2YlOZr,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch {
  position: relative;
  width: 40px !important;
  height: 22px !important;
  background-color: transparent;
  box-shadow: none !important;
  transition: 300ms ease all;
  overflow: visible; }

.connection-1fbD7X .sizeDefault-2YlOZr {
  background-color: transparent !important; }

.switchItem-2hKKKK .themeDefault-24hCdX.sizeDefault-2YlOZr,
.switchItem-2hKKKK .themeClear-1EjkE4.sizeDefault-2YlOZr {
  width: 36px;
  height: 18px; }

.switchEnabled-V2WDBB:before,
.themeDefault-24hCdX:before,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch {
  position: absolute;
  content: " ";
  width: 36px;
  height: 18px;
  margin: 0;
  background-color: #000;
  border-radius: 12px;
  border: 2px solid;
  opacity: 1;
  transition: 300ms ease all; }

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper {
  width: 40px;
  height: 22px; }

.switchEnabled-V2WDBB:active:before {
  opacity: 1; }

.themeDefault-24hCdX.valueUnchecked-2lU_20:before,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch {
  border-color: var(--checkbox-border-unchecked);
  transition: 300ms ease all; }

.connection-1fbD7X .valueUnchecked-2lU_20:before {
  background-color: rgba(0, 0, 0, 0.35);
  border-color: transparent; }

.themeDefault-24hCdX.valueChecked-m-4IJZ:before,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked {
  background-color: var(--accent-color);
  border-color: var(--checkbox-border-checked);
  transition: 300ms ease all; }

.connection-1fbD7X .valueChecked-m-4IJZ:before {
  background-color: rgba(255, 255, 255, 0.25);
  border-color: transparent; }

.sizeDefault-2YlOZr:after,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch:before {
  width: 22px;
  height: 22px;
  top: 0;
  left: 0;
  margin: 0;
  border-radius: 11px;
  box-shadow: 0 1px 2px rgba(0, 0, 0, 0.5);
  transition: 300ms ease all; }

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch:before {
  top: -2px;
  left: -2px; }

.valueChecked-m-4IJZ.sizeDefault-2YlOZr:after,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked:before {
  background: var(--checkbox-checked) !important; }

.valueUnchecked-2lU_20.sizeDefault-2YlOZr:after,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch:before {
  background: var(--checkbox-unchecked) !important; }

.connection-1fbD7X .valueUnchecked-2lU_20.sizeDefault-2YlOZr:after {
  background: rgba(255, 255, 255, 0.4) !important; }

.valueUnchecked-2lU_20.sizeDefault-2YlOZr:hover:after,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper:hover .ui-switch:before {
  background: #fff !important; }

.valueChecked-m-4IJZ.sizeDefault-2YlOZr:active:after,
#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch:active:before {
  left: 0; }

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper:active .ui-switch:before {
  width: 26px !important;
  left: -2px !important; }

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper input {
  width: 36px;
  height: 16px; }

#bd-settingspane-container .ui-switch-item .ui-switch-wrapper .ui-switch.checked:before {
  transform: translateX(18px); }

/*
 *
 *	NOTIFICATION BAR
 *
 */
.notice-2FJMB4 {
  border-radius: 0; }

.notice-2FJMB4 .button-1MICoQ {
  background: var(--button-background) !important;
  border-color: #fff !important; }

.notice-2FJMB4 .dismiss-SCAH9H {
  height: 24px !important;
  width: 36px !important;
  background-color: var(--button-background);
  transform: scale(0.7); }

.notice-2FJMB4 .dismiss-SCAH9H:hover {
  transform: scale(0.75); }

/*
 *
 *	MODALS
 *
 */
.modal-3HD5ck,
.modal-1UGdnR,
.modal-yWgWj- {
  z-index: 999999; }

.modal-3HD5ck,
.modal-1UGdnR,
.modal-yWgWj-,
.root-SR8cQa,
.root-1gCeng,
.authBox-hW6HRx,
.uploadModal-2ifh8j,
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .bgScale-1otPtc,
.gamePreview-9weYR2,
.create-guild-container.deprecated,
.create-guild-container.deprecated .create-or-join .form-inner,
.regionSelectModal-12e-57,
.quickswitcher-3JagVE,
.dc-overlay-main,
.dc-overlay-centerfield,
.smalltalk .page {
  box-shadow: var(--default-shadow) !important; }

.modal-3HD5ck,
.modal-yWgWj-,
.root-SR8cQa,
.root-1gCeng,
.authBox-hW6HRx,
.body-3ND3kc,
.uploadModal-2ifh8j,
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc,
.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .bgScale-1otPtc,
.gamePreview-9weYR2,
.create-guild-container.deprecated,
.create-guild-container.deprecated .create-or-join .form-inner,
.regionSelectModal-12e-57,
.header-1R_AjF,
.content-2BXhLs,
.footer-2yfCgX,
.ui-standard-sidebar-view,
.quickswitcher-3JagVE,
.dc-overlay-main,
.dc-overlay-centerfield,
.smalltalk .page {
  background: var(--popout-color) !important;
  border-radius: var(--popout-radius) !important; }

.small-3iVZYw {
  min-height: 100px; }

.topSectionNormal-2-vo2m {
  background: rgba(0, 0, 0, 0.2) !important; }

/* MODAL -> HEADERS */
.header-1R_AjF,
.header-2tA9Os,
.header-ykumBX,
.header-1TKi9 {
  position: relative;
  min-height: 78px;
  max-height: 78px;
  margin: 0 0 0 0;
  padding: 0 21px;
  background: transparent !important;
  line-height: 38px;
  border-bottom: none;
  box-shadow: none !important;
  text-align: center; }

.header-ykumBX .wrapper-1sSZUt {
  line-height: 78px; }

/*.header-1TKi98 {
	padding: 21px;
}*/
.h4-AQvcAz,
.h5-18_1nd {
  text-transform: none; }

.header-1R_AjF .h4-AQvcAz {
  font-size: 16px;
  font-weight: 400;
  text-transform: none;
  text-align: center;
  color: #fff; }

.wrapper-1sSZUt,
.header-1TKi98 .h4-AQvcAz,
.header-2tA9Os .h4-AQvcAz,
.themedPopout-1TrfdI .header-2Kf7Yu .title-2-NHs5 {
  font-size: 18px;
  font-weight: 600;
  color: #fff;
  text-transform: none; }

.modal-3HD5ck h2.title-3sZWYQ {
  margin: 0;
  padding: 12px 0;
  text-align: left; }

.header-1R_AjF .small-29zrCQ {
  position: absolute;
  height: 38px;
  top: 0;
  line-height: 44px; }

.close-1kwMUs {
  position: absolute;
  width: 16px;
  height: 16px;
  top: 21px;
  right: 21px;
  padding: 0; }

.close-1kwMUs svg path {
  width: 22px !important;
  height: 22px !important;
  transform: scale(1) translate(-2px, -2px); }

/* MODAL -> BODIES/CONTENT */
.content-KhOrDM,
.inner-3wn6Q5 {
  padding: 0 12px; }

.body-3ND3kc {
  height: auto !important; }

.bda-slist {
  width: 100%; }

.scroller-2FKFPG {
  overflow-y: auto !important; }

.modal-3HD5ck .body-Mj9Oxz {
  text-align: left; }

/* MODAL -> FOOTERS */
.footer-3rDWdC,
.footer-2yfCgX,
.footer-1eyGBa,
.footer-2gL1pp {
  padding: 12px;
  background: var(--popout-color) !important;
  border-radius: 0 0 var(--popout-radius) var(--popout-radius);
  border-top: none;
  box-shadow: none !important; }

.footer-3rDWdC .button-38aScr,
.footer-2yfCgX button:first-child,
.footer-2gL1pp button:first-child,
.uploadModal-2ifh8j .footer-3mqk7D .button-primary {
  margin: 0 0 0 12px; }

.footer-2yfCgX .sizeXlarge-2yFAlZ:first-child {
  margin: 0; }

.minorAction-OVxOke {
  width: auto;
  height: 32px;
  margin: 0;
  line-height: 32px; }

/* MODALS -> ATTACHMENT */
.uploadModal-2ifh8j {
  min-height: 200px; }

.uploadModalIn-1z07Bv .uploadDropModal-2kTwbc .inner-3nWsbo {
  border: none; }

.uploadModal-2ifh8j .inner-3nWsbo {
  /*height: 160px !important;
  min-height: 160px !important;
  max-height: 160px !important;*/
  margin: 0;
  padding: 0 12px;
  border-radius: 0;
  border: none; }

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K {
  height: 90px; }

.uploadModal-2ifh8j .inner-3nWsbo .file-34mY5K .icon-kyxXVr.image-2yrs5j {
  border: 2px solid var(--accent-color); }

.uploadModal-2ifh8j .inner-3nWsbo .comment-4IWttf {
  margin: 0; }

.uploadModal-2ifh8j .footer-3mqk7D {
  background: transparent;
  border-radius: 0;
  box-shadow: none; }

.uploadModal-2ifh8j .footer-3mqk7D .button-38aScr:last-child {
  margin-left: 8px; }

.textAreaWithoutAttachmentButton-qiaiTB {
  padding-left: 0; }

/* MODALS -> GIFT NITRO */
.inner-1JeGVc div:first-child:not([class]) .modal-3HD5ck {
  height: auto !important;
  min-height: 10vh !important;
  max-height: 80vh !important; }

.content-PS26MV {
  padding: 10px 0; }

.content-PS26MV,
.selectPlan-GQ6nvu {
  margin: 0; }

.selectPlan-GQ6nvu,
.content-PS26MV div:not([class]) {
  overflow: visible !important; }

.option-1l2vXE {
  margin: 0;
  padding: 10px 0;
  background: transparent !important;
  border-radius: 0;
  border-bottom: 1px solid var(--menu-hover-color);
  overflow: visible; }

.option-1l2vXE:last-child {
  margin: 0;
  border-bottom: none; }

.form-2d3M9m .header-1R_AjF {
  margin: 0; }

.form-2d3M9m .divider-1que2t {
  display: none; }

.lookFilled-1h1y05.select-1Pkeg4 {
  height: 34px !important;
  min-height: 34px !important;
  max-height: 34px !important;
  padding: 0 8px;
  background: var(--select-input-color) !important;
  border-radius: 0;
  border: none !important; }

/*.content-PS26MV div div[style*='height: auto; opacity: 1; overflow: auto; transform: translateX(0%);'] {
	overflow: hidden !important;
}*/
.popout-3sVMXz.popoutBottom-1YbShG.noShadow-321ZPm[style*="transform: translateX(-50%) translateY(0%) translateZ(0px)"] {
  z-index: 9999999 !important; }

.sizeMedium-6vZ9JV.popout-2sKjHu[style*='max-height: 64px'] {
  max-height: 82px !important; }

.optionLabel-2CkCZx .paymentSourceLabel-1lo4Ca {
  line-height: 32px; }

.form-2d3M9m .footer-2yfCgX {
  position: relative;
  height: 32px; }

.form-2d3M9m .footer-2yfCgX .backButton-25HgIF {
  position: absolute;
  margin: 0 !important;
  right: 12px; }

/*
 *
 *	POPOUT MENUS
 *
 */
.popout-3sVMXz.popoutBottom-1YbShG,
.popout-3sVMXz.popoutBottomLeft-JehOp2,
.popout-3sVMXz.popoutBottomRight-2JrySt,
.popout-3sVMXz.popoutTop-3uu9vG,
.popout-3sVMXz.popoutTopLeft-b5Eb3O,
.popout-3sVMXz.popoutTopRight-3BzFIE,
.popout-3sVMXz.popout-bottom,
.popout-3sVMXz.popout-bottom-left,
.popout-3sVMXz.popout-bottom-right,
.popout-3sVMXz.popout-top
.popout-3sVMXz.popout-top-left,
.popout-3sVMXz.popout-top-right {
  width: auto !important;
  transition: 0ms ease !important; }

.popout-3sVMXz.popoutTopLeft-b5Eb3O,
.popout-3sVMXz.popout-top-left {
  z-index: 99 !important; }

.popout-3sVMXz.popoutBottomRight-2JrySt.noShadow-321ZPm[style*="z-index: 1100;"] {
  z-index: 9999999 !important; }

.popout-3sVMXz,
.popout-2iWAc- {
  box-shadow: var(--default-shadow) !important;
  border-radius: 0;
  border: none; }

.menu-Sp6bN1,
.searchPopout-1vUlP3,
.container-3ayLPN,
.messagesPopoutWrap-1MQ1bW,
.userPopout-3XzG_A {
  background: var(--popout-color) !important;
  box-shadow: var(--default-shadow) !important;
  border-radius: var(--popout-radius) !important;
  border: none !important; }

.container-3ayLPN,
.messagesPopoutWrap-1MQ1bW {
  box-shadow: var(--default-shadow) !important; }

.backdrop-1wrmKB {
  /*z-index: 999999;*/ }

/* POPOUT MENUS -> SERVER SETTINGS */
.menu-Sp6bN1 {
  padding: 8px 0;
  box-shadow: var(--default-shadow) !important; }

.item-1GzJrl {
  position: relative;
  height: 32px;
  line-height: 32px;
  margin: 0;
  padding: 0;
  border-radius: 0;
  color: #b2b2b2 !important; }

.item-1GzJrl:hover {
  background: var(--menu-hover-color) !important;
  color: #fff !important; }

.iconContainer-2ZxvJk,
.icon-2doZ3q {
  width: 16px;
  height: 16px; }

.iconContainer-2ZxvJk {
  position: absolute;
  top: 0;
  bottom: 0;
  margin: auto 0 auto 12px; }

/*.iconContainer-2ZxvJk .icon-2doZ3q path {
	transform: scale(1.14) translate(-2px, -1px);
}*/
/* POPOUT MENUS -> SERVER SETTINGS -> ICONS */
/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> INVITE */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Nova_UserAdd"] path {
  d: path("M19 17V19H7V17S7 13 13 13 19 17 19 17M16 8A3 3 0 1 0 13 11A3 3 0 0 0 16 8M19.2 13.06A5.6 5.6 0 0 1 21 17V19H24V17S24 13.55 19.2 13.06M18 5A2.91 2.91 0 0 0 17.11 5.14A5 5 0 0 1 17.11 10.86A2.91 2.91 0 0 0 18 11A3 3 0 0 0 18 5M8 10H5V7H3V10H0V12H3V15H5V12H8Z") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> SETTINGS */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Gear"] path {
  d: path("M12,15.5A3.5,3.5 0 0,1 8.5,12A3.5,3.5 0 0,1 12,8.5A3.5,3.5 0 0,1 15.5,12A3.5,3.5 0 0,1 12,15.5M19.43,12.97C19.47,12.65 19.5,12.33 19.5,12C19.5,11.67 19.47,11.34 19.43,11L21.54,9.37C21.73,9.22 21.78,8.95 21.66,8.73L19.66,5.27C19.54,5.05 19.27,4.96 19.05,5.05L16.56,6.05C16.04,5.66 15.5,5.32 14.87,5.07L14.5,2.42C14.46,2.18 14.25,2 14,2H10C9.75,2 9.54,2.18 9.5,2.42L9.13,5.07C8.5,5.32 7.96,5.66 7.44,6.05L4.95,5.05C4.73,4.96 4.46,5.05 4.34,5.27L2.34,8.73C2.21,8.95 2.27,9.22 2.46,9.37L4.57,11C4.53,11.34 4.5,11.67 4.5,12C4.5,12.33 4.53,12.65 4.57,12.97L2.46,14.63C2.27,14.78 2.21,15.05 2.34,15.27L4.34,18.73C4.46,18.95 4.73,19.03 4.95,18.95L7.44,17.94C7.96,18.34 8.5,18.68 9.13,18.93L9.5,21.58C9.54,21.82 9.75,22 10,22H14C14.25,22 14.46,21.82 14.5,21.58L14.87,18.93C15.5,18.67 16.04,18.34 16.56,17.94L19.05,18.95C19.27,19.03 19.54,18.95 19.66,18.73L21.66,15.27C21.78,15.05 21.73,14.78 21.54,14.63L19.43,12.97Z") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> CREATE CHANNEL */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Nova_CircleAdd"] path {
  d: path("M17,13H13V17H11V13H7V11H11V7H13V11H17M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2Z") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> CREATE CATEGORY */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Nova_FolderAdd"] path {
  d: path("M2,16H10V14H2M18,14V10H16V14H12V16H16V20H18V16H22V14M14,6H2V8H14M14,10H2V12H14V10Z") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> NOTIFICATION */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Nova_Bell"] path {
  d: path("M21,19V20H3V19L5,17V11C5,7.9 7.03,5.17 10,4.29C10,4.19 10,4.1 10,4A2,2 0 0,1 12,2A2,2 0 0,1 14,4C14,4.1 14,4.19 14,4.29C16.97,5.17 19,7.9 19,11V17L21,19M14,21A2,2 0 0,1 12,23A2,2 0 0,1 10,21") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> PRIVACY */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Nova_ShieldStar"] path {
  d: path("M10,17L6,13L7.41,11.59L10,14.17L16.59,7.58L18,9M12,1L3,5V11C3,16.55 6.84,21.74 12,23C17.16,21.74 21,16.55 21,11V5L12,1Z") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> CHANGE NICKNAME */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Pencil"] path {
  d: path("M20.71,7.04C21.1,6.65 21.1,6 20.71,5.63L18.37,3.29C18,2.9 17.35,2.9 16.96,3.29L15.12,5.12L18.87,8.87M3,17.25V21H6.75L17.81,9.93L14.06,6.18L3,17.25Z") !important; }

/* POPOUT MENUS -> SERVER SETTINGS -> ICONS -> LEAVE SERVER */
.iconContainer-2ZxvJk .icon-2doZ3q[name="Nova_Exit"] path {
  d: path("M19,3H5C3.89,3 3,3.89 3,5V9H5V5H19V19H5V15H3V19A2,2 0 0,0 5,21H19A2,2 0 0,0 21,19V5C21,3.89 20.1,3 19,3M10.08,15.58L11.5,17L16.5,12L11.5,7L10.08,8.41L12.67,11H3V13H12.67L10.08,15.58Z") !important; }

.label-1Y-LW5 {
  margin-left: 34px; }

.separator-2zcjq8 {
  position: relative;
  height: 9px;
  margin: 0px 0;
  padding: 0;
  border: none; }

.separator-2zcjq8:before {
  content: " ";
  position: absolute;
  width: 100%;
  height: 1px;
  background: var(--menu-border-color);
  top: 0;
  bottom: 0;
  margin: auto 0; }

/* POPOUT MENUS -> USER STATUS */
.itemBase-1Qj4z6 {
  height: auto;
  min-height: 32px;
  margin: 0;
  padding: 0;
  line-height: 16px;
  border-radius: 0; }

.itemBase-1Qj4z6:hover {
  background: var(--menu-hover-color); }

.itemBase-1Qj4z6 .checkbox-1wLOv4 {
  position: absolute;
  left: 10px; }

.statusIconText-3b4TkH {
  min-height: 32px; }

.status-3Kz6VS,
.customStatusEmoji-2NpCsS {
  width: 16px !important;
  height: 16px !important;
  margin: 0 7px 0 12px; }

.customStatus-1KPfFb .customStatusEmoji-2NpCsS {
  margin: 0 7px 0 0; }

.itemBase-1Qj4z6 .helper-2c73HK {
  margin: 0 8px 4px 34px;
  padding-bottom: 8px; }

.itemBase-1Qj4z6 .helper-2c73HK:empty {
  display: none; }

.itemBase-1Qj4z6:last-child .helper-2c73HK {
  margin-bottom: 0; }

/* POPOUT MENUS -> USER STATUS -> CUSTOM STATUS */
.customStatus-1KPfFb {
  margin-left: 12px; }

.clearStatus-2hmUqc {
  margin-right: 12px; }

.header-3C6qT5 {
  padding-top: 0; }

.art-347BZj {
  display: none; }

.emojiButtonContainer-3d6DFV {
  z-index: 2; }

.emojiButtonContainer-3d6DFV + .inputWrapper-31_8H8 .input-cIJ7To {
  padding: 0 12px 0 40px !important; }

/* POPOUT MENUS -> USER STATUS -> SPOTIFY LISTEN ALONG */
.listeningAlong-30wH70 {
  background: var(--popout-color) !important;
  border-bottom: none !important; }

/* POPOUT MENUS -> PINNED MESSAGES */
.messagesPopoutWrap-1MQ1bW {
  max-height: 85vh !important; }

.messagesPopout-24nkyi,
.themedPopout-1TrfdI .footer-1K57q_ {
  background-color: transparent !important; }

.themedPopout-1TrfdI .header-2Kf7Yu {
  box-shadow: none;
  border-radius: 0; }

.themedPopout-1TrfdI .header-2Kf7Yu + :after {
  display: none; }

.themedPopout-25DgLi .header-SsaQ8X .title-23FrqZ {
  color: #b2b2b2; }

.messageGroupWrapper-o-Zw7G {
  background: transparent !important;
  border-radius: 0;
  border: none !important;
  border-bottom: 1px solid #444 !important; }

/* POPOUT MENUS -> MENTIONS & UNREADS */
.recentMentionsPopout-3rCiI6 {
  max-height: 80vh !important;
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

/* POPOUT MENUS -> MENTIONS & UNREADS -> HEADER */
.recentMentionsPopout-3rCiI6 .header-2-Imhb {
  height: 78px;
  min-height: 78px;
  padding: 0 21px; }

.recentMentionsPopout-3rCiI6 .header-2-Imhb .topPill-30KHOu {
  height: auto; }

.recentMentionsPopout-3rCiI6 .header-2-Imhb .tabBar-1kuXvJ .tab-ck0077 {
  height: auto;
  margin-top: 14px;
  margin-bottom: 14px; }

.recentMentionsPopout-3rCiI6 .header-2-Imhb .button-1-5Aqk {
  position: absolute;
  top: 0;
  right: 21px;
  bottom: 0;
  margin: auto 0;
  padding: 0; }

/* POPOUT MENUS -> MENTIONS & UNREADS -> MESSAGES */
.container-3iAQ-0 {
  padding: 0 9px 8px 21px; }

.channel-2RlVpW {
  padding: 0 9px 0 21px; }

.channelHeader-3Gd2xq {
  padding: 12px 16px;
  background-color: #191919;
  border-radius: 8px 8px 0 0;
  border-bottom: 1px solid #333; }

.channelHeader-3Gd2xq:only-child {
  border-radius: 8px;
  border-bottom: none; }

.channel-2RlVpW .channelHeader-3Gd2xq {
  padding: 12px 16px 12px 42px; }

.collapseButton-3V3Cqh {
  left: 12px;
  cursor: pointer; }

.channelHeader-3Gd2xq .button-1-5Aqk,
.recentMentionsPopout-3rCiI6 .header-2-Imhb .button-1-5Aqk {
  background-color: var(--menu-hover-color);
  color: #fff; }

.channelHeader-3Gd2xq .button-1-5Aqk:hover,
.recentMentionsPopout-3rCiI6 .header-2-Imhb .button-1-5Aqk:hover {
  background-color: var(--menu-select-color); }

.messageContainer-gbhlwo,
.messages-3G3erD {
  background-color: #191919;
  border-radius: 0 0 8px 8px; }

/* POPOUT MENUS -> SEARCH OPTIONS */
.popout-3sVMXz.popoutBottom-1YbShG.noShadow-321ZPm[style*="transform: translateX(-50%) translateY(0%) translateZ(0px)"] {
  /*transform: translateX(-54%) !important;*/ }

.queryContainer-RKFJW- {
  background: transparent !important; }

.keybindShortcutSearchPopout-1MAfqq span {
  background: transparent !important;
  border: none !important;
  box-shadow: none !important; }

.searchQuery-1B7rtx {
  padding: 12px !important; }

.searchQuery-1B7rtx .searchFor-3W5Vad {
  margin: 4px 0;
  color: #b2b2b2; }

.searchQuery-1B7rtx .searchFor-3W5Vad strong {
  color: #fff !important; }

.searchQuery-1B7rtx .keybindShortcut-1BD6Z1 span {
  padding: 0 15px !important;
  box-shadow: none !important;
  text-transform: capitalize;
  line-height: 28px !important; }

.resultsGroup-r_nuzN .header-2N-gMV {
  padding: 6px 12px 12px; }

.resultsGroup-r_nuzN {
  padding: 8px 0; }

.resultsGroup-r_nuzN:before {
  margin: 0;
  border-top-color: var(--menu-border-color) !important; }

.searchPopout-1vUlP3 .resultsGroup-r_nuzN:nth-child(2):before {
  display: none; }

.option-96V44q {
  margin: 0;
  padding: 0 12px;
  border-radius: 0; }

.option-96V44q:after {
  position: absolute;
  content: " ";
  width: 50px;
  height: 100%;
  background: -webkit-linear-gradient(left, rgba(44, 44, 44, 0) 0%, #2c2c2c 80%, #2c2c2c 100%) !important;
  pointer-events: none; }

.option-96V44q.selected-rZcOL- {
  background-color: var(--menu-hover-color) !important; }

.option-96V44q.selected-rZcOL-:after {
  background: -webkit-linear-gradient(left, rgba(66, 66, 66, 0) 0%, #424242 80%, #424242 100%) !important; }

.option-96V44q.selected-rZcOL-:before {
  right: 8px; }

.option-96V44q.selected-rZcOL- .filter-3Y_im- {
  color: #fff !important; }

.option-96V44q.selected-rZcOL- .answer-1n6g43 {
  color: #b2b2b2 !important; }

/* POPOUT MENU -> ATTACHMENT */
.attachPopout-36hjtN {
  padding: 8px 0;
  background: var(--popout-color) !important;
  border-radius: 0;
  transition: none !important; }

.attachPopoutRow-3iqqu1 {
  height: 32px;
  padding: 0 8px;
  line-height: 32px;
  border-radius: 0;
  transition: none !important; }

.attachPopoutRow-3iqqu1:hover {
  background: var(--menu-hover-color) !important; }

.attachPopoutRowText-2R5RC2 {
  color: var(--menu-text-color) !important; }

.attachPopoutIcon-1QXhWW path {
  fill: var(--menu-text-color) !important; }

.attachPopoutRow-3iqqu1:hover .attachPopoutRowText-2R5RC2 {
  color: #fff !important; }

.attachPopoutRow-3iqqu1:hover .attachPopoutIcon-1QXhWW path {
  fill: #fff !important; }

/* POPOUT MENUS -> SIDEBAR USER POPOUT */
.popout-3sVMXz.popoutLeft-30WmrD.noArrow-3BYQ0Z.noShadow-321ZPm,
.popout-3sVMXz.popout-left.noArrow-3BYQ0Z.noShadow-321ZPm {
  transform: translateX(-110%) !important; }

.userPopout-3XzG_A {
  position: relative !important;
  width: 260px !important;
  max-height: 95vh !important;
  z-index: 99999999 !important; }

.headerNormal-T_seeN {
  background: rgba(0, 0, 0, 0.2) !important; }

.body-3iLsc4 {
  position: relative !important;
  max-height: 30vh !important;
  overflow-y: auto !important; }

.body-3iLsc4,
.bodyInner-245q0L,
.footer-1fjuF6 {
  background: transparent !important; }

.footer-1fjuF6 {
  padding-top: 8px; }

.activity-11LB_k .anchor-3Z-8Bb,
.activity-1ythUs .anchor-3Z-8Bb {
  color: #fff !important; }

/*.activity-1ythUs .lookOutlined-3sRXeN.colorWhite-rEQuAQ {
	padding: 0 30px !important;
}*/
.activity-11LB_k .lookOutlined-3sRXeN.colorWhite-rEQuAQ,
.activity-1ythUs .iconButtonSize-3s24uQ {
  padding: 0 !important; }

.listeningActionsProfile-1fYwru .buttonSize-2Pmk-w:not(:first-child) .lookOutlined-3sRXeN.colorWhite-rEQuAQ,
.listeningActionsProfile-1fYwru .buttonSize-2Pmk-w:not(:first-child).lookOutlined-3sRXeN.colorWhite-rEQuAQ {
  padding: 0 !important; }

.activity-11LB_k .lookOutlined-3sRXeN.colorWhite-rEQuAQ:disabled {
  margin: 0 !important; }

.activity-11LB_k .lookOutlined-3sRXeN.colorWhite-rEQuAQ {
  background: var(--button-background) !important;
  border: 1px solid #fff !important; }

.activity-11LB_k .lookOutlined-3sRXeN.colorWhite-rEQuAQ:disabled {
  background: transparent !important; }

.iconButtonSize-U9SCYe {
  margin: 0 0 0 12px !important; }

/* POPOUT MENUS -> USER POPOUT */
.root-SR8cQa {
  overflow-y: auto; }

.root-SR8cQa .scroller-2FKFPG {
  overflow: hidden !important; }

.userInfoSection-2acyCx {
  margin: 0 12px; }

.additionalActionsIcon-1FoUlE {
  height: 32px;
  width: 32px;
  background-color: var(--button-background);
  border-radius: 50%;
  border: var(--button-border);
  opacity: 1; }

.additionalActionsIcon-1FoUlE:hover {
  transform: scale(1.075); }

.additionalActionsIcon-1FoUlE:active:hover {
  transform: scale(1);
  opacity: 0.6; }

.additionalActionsIcon-1FoUlE path[fill="currentColor"] {
  fill: #fff;
  transform: scale(0.75) rotate(90deg) translate(4px, -28px); }

.connectedAccount-36nQx7,
.userInfoSection-2acyCx + .userInfoSection-2acyCx {
  border-radius: 0;
  border-color: #444 !important; }

.userInfoSection-2acyCx + .userInfoSection-2acyCx {
  margin: 0; }

/* POPOUT MENUS -> GAME MENU */
.players-1zg2l8,
.emptyPlayers-dx3qig,
.footer-3J5oP4 {
  background: var(--popout-color) !important; }

.footer-3J5oP4 {
  border-top: 1px solid var(--menu-border-color); }

.footer-3J5oP4 .button-3aO-jY {
  padding: 0 15px !important; }

/* POPOUT MENUS -> RTC CONNECTION */
.popout-3sVMXz header,
.popout-3sVMXz section {
  border-radius: 0 !important; }

.container-2x5lvQ header {
  border-bottom: 1px solid var(--menu-border-color); }

.container-2x5lvQ header,
.container-2x5lvQ section {
  background: var(--popout-color) !important; }

.container-2x5lvQ section:after {
  border-top-color: var(--popout-color) !important; }

/* POPOUT MENUS -> AUTOCOMPLETE */
[class*="theme-"] .autocomplete-1vrmpx {
  background-color: var(--popout-color);
  border-radius: 0;
  box-shadow: var(--default-shadow); }
  [class*="theme-"] .autocomplete-1vrmpx .base-1pYU8j {
    padding: 8px; }

#autocomplete-popout {
  background: var(--popout-color) !important;
  border-radius: 0; }

#autocomplete-popout .autocomplete-shadow {
  border-radius: 0;
  box-shadow: none !important; }

#autocomplete-popout header {
  padding: 0 12px;
  background: rgba(0, 0, 0, 0.25) !important; }

#autocomplete-popout .autocomplete-header-background {
  background: transparent !important;
  border-radius: 0; }

#autocomplete-popout h3,
#autocomplete-popout input[type=text],
#autocomplete-popout input[type=text]::-webkit-input-placeholder {
  color: #b2b2b2 !important; }

#autocomplete-popout input[type=text],
#autocomplete-popout input[type=text]::-webkit-input-placeholder {
  font-weight: 500 !important; }

#autocomplete-popout section {
  background: transparent !important; }

#autocomplete-popout .row {
  padding: 0 12px; }

#autocomplete-popout .row.selected {
  background: var(--menu-hover-color) !important; }

/* POPOUT MENUS -> ADD FRIENDS TO DM */
.searchBar-1Vaz-O .searchBarComponent-yxeVIL {
  padding: 0 2px;
  background: var(--input-bg) !important;
  border-radius: 17px; }

.header-1R_AjF .search-bar .search-bar-inner {
  height: 100%;
  padding: 0;
  border-radius: 0;
  border: none; }

.header-1R_AjF .inner-3ErfOT {
  height: auto !important;
  min-height: 32px !important;
  max-height: 64px !important;
  padding: 0; }

.header-1R_AjF .input-1Rv96N {
  height: 32px;
  margin: 0;
  padding: 0 8px;
  font-size: 14px;
  font-weight: 500;
  color: #444; }

.friendWrapper-LdKLp8 {
  margin: 0; }

.friend-2E0q2S {
  border-radius: 0; }

.friendSelected-3J_Uh8 {
  background-color: var(--menu-hover-color) !important; }

.tag-2gHSR7 {
  margin: 1px 4px 0 0;
  padding: 0 15px;
  background: var(--popout-color);
  border-radius: 15px; }

/*
 *
 *	BETTER DISCORD SETTINGS
 *
 */
.bd-addon-list {
  margin: 24px 0 0 0; }

.theme-dark .bd-addon-list .bd-addon-card {
  margin-bottom: 36px;
  padding: 4px 0;
  background: transparent;
  border-radius: 0;
  border: none;
  border-bottom: 4px solid var(--card-border);
  overflow: visible; }

.theme-dark .bd-addon-list .bd-card-footer {
  padding: 12px 0 6px 0; }

/*
 *
 *	CONTEXT/RIGHT CLICK MENU
 *
 */
.contextMenu-HLZMGh,
.submenu-2-ysNh {
  padding: 6px 0;
  background: var(--popout-color) !important;
  border-radius: 0;
  box-shadow: var(--default-shadow) !important;
  z-index: 9999999 !important; }

.itemGroup-1tL0uz {
  padding: 2px 0;
  border-top: 1px solid var(--menu-border-color) !important; }

.itemGroup-1tL0uz:empty,
.item-1Yvehc:empty,
.itemSubMenu-1vN_Yn:empty {
  display: none !important; }

.itemGroup-1tL0uz:first-child {
  padding: 0 0 2px 0 !important;
  border-top: none !important; }

.itemGroup-1tL0uz:last-child {
  padding: 2px 0 0 0 !important; }

.itemGroup-1tL0uz:only-child {
  padding: 0 !important; }

.itemGroup-1tL0uz .itemGroup-1tL0uz {
  padding: 0 !important;
  border-top: none !important; }

.item-1Yvehc {
  min-height: 32px;
  padding: 0 34px;
  line-height: 32px;
  border-radius: 0;
  font-size: 14px;
  font-weight: 400;
  color: var(--menu-text-color); }

.itemSubMenu-1vN_Yn {
  padding-left: 34px;
  font-weight: 400; }

.submenuPaddingContainer-fiOCHc {
  position: relative;
  margin-left: -4px;
  margin-right: -4px; }

.item-1Yvehc:hover {
  background: var(--menu-hover-color) !important;
  color: #fff; }

.item-1Yvehc.itemSubMenu-1vN_Yn {
  background: transparent url(https://discordapp.com/assets/1988164a7c55346d32117b151f4e319d.svg) no-repeat 155px 50% !important; }

.item-1Yvehc.itemSubMenu-1vN_Yn:hover {
  background: var(--menu-hover-color) url(https://discordapp.com/assets/e4afe52f6863408a35654a6e5fd69ba9.svg) no-repeat 155px 50% !important; }

.item-1Yvehc .hint-22uc-R,
.item-1Yvehc .image-1ehFEp,
.item-1Yvehc .checkbox-3kaeSU {
  position: absolute;
  left: 12px; }

.item-1Yvehc .checkbox-3kaeSU {
  float: none;
  left: 4px; }

.item-1Yvehc .hint-22uc-R {
  float: none;
  left: 6px; }

.subMenuContext-2n_9YM {
  z-index: 9999999; }

.itemSlider-FZeYw0 {
  padding: 8px 34px; }

.itemSlider-FZeYw0:hover {
  background-color: transparent; }

.itemSlider-FZeYw0 .label-JWQiNe {
  margin: 0 0 -10px 0; }

.itemSlider-FZeYw0 .mini-dmm9yo {
  margin: 8px 0 0 0; }

.mini-dmm9yo .bar-2Qqk5Z {
  height: 4px; }

.mini-dmm9yo .grabber-3mFHz2 {
  width: 10px;
  height: 10px;
  top: 13px;
  margin: 0 0 0 -7px; }

.itemToggle-S7XGOQ .checkbox {
  position: relative;
  margin: 0 -22px 0 4px; }

/* CONTEXT/RIGHT CLICK MENU -> ADD REACTION */
.button-1I8KM5 {
  background-color: var(--menu-hover-color); }

.button-1I8KM5:hover {
  background-color: var(--menu-select-color); }

/*
 *
 *	TOOLTIPS
 *
 */
.tooltip-2QfLtc,
.dc-tooltip .dc-tooltip-text {
  padding: 8px 12px !important;
  background: var(--popout-color) !important;
  border-radius: 0 !important;
  box-shadow: var(--default-shadow) !important;
  font-weight: 500 !important;
  font-size: 14px !important;
  color: #b2b2b2 !important;
  animation: opacity 250ms ease;
  z-index: 9999999; }

.tooltipContent-bqVLWK {
  padding: 0; }

.tooltipBlack-PPG47z .tooltipPointer-3ZfirK {
  border-top-color: var(--popout-color) !important; }

/*
 *
 *	SCROLLBARS
 *
 */
.scroller-1IIF0A,
.scroller-9moviB,
.scroller-2FKFPG {
  background-color: transparent; }

::-webkit-scrollbar {
  position: absolute;
  width: 16px !important;
  background: transparent; }

::-webkit-scrollbar-track {
  background: rgba(0, 0, 0, 0) !important;
  border-radius: 0 !important; }

::-webkit-scrollbar-track-piece {
  margin: 0;
  background-color: transparent !important;
  border: 0 solid transparent !important;
  border-radius: 0 !important; }

::-webkit-scrollbar-thumb {
  display: initial;
  background-color: var(--scrollbar-thumb) !important;
  border: 0 solid transparent !important;
  border-radius: 0 !important; }

::-webkit-scrollbar-thumb:hover,
::-webkit-scrollbar-thumb:active {
  background-color: var(--scrollbar-thumb-hover) !important; }

::-webkit-scrollbar-thumb:active {
  display: initial; }

/*
 *
 *	SUPPORTED PLUGINS
 *
 */
/* SUPPORTED PLUGINS -> CharCounter */
.charCounterAdded-zz9O4t {
  margin-top: calc(var(--textarea-radius) + 14px); }

.messagesWrapper-1sRNjr + .form-2fGMdU .charCounterAdded-zz9O4t {
  /*margin-top: 14px;*/
  margin-top: 25px; }

.channelTextArea-rNsIhG.charCounterAdded-zz9O4t {
  margin: 0; }

.charCounter-7fw40k {
  z-index: 1; }

.counter-uAzbKp {
  width: 100%;
  height: var(--textarea-radius);
  top: calc(var(--textarea-radius) * -1);
  bottom: auto;
  padding: 0 20px;
  line-height: var(--textarea-radius);
  background-color: var(--input-bg);
  border-bottom: 1px solid #ccc;
  border-radius: var(--textarea-radius) var(--textarea-radius) 0 0;
  box-sizing: border-box;
  text-align: right;
  color: var(--input-text-color) !important;
  font-weight: 500; }

.charCounterAdded-zz9O4t .inputWrapper-31_8H8 + .counter-uAzbKp,
.charCounterAdded-zz9O4t .clearButton-13g8ju + .counter-uAzbKp {
  width: auto;
  padding: 0;
  background-color: transparent;
  border-bottom: none;
  color: var(--channels-default) !important; }

.charCounterAdded-zz9O4t .scrollableContainer-2NUZem,
.charCounterAdded-zz9O4t .scrollableContainer-2NUZem.hasReply-16cIUP,
.charCounterAdded-zz9O4t textarea.input-cIJ7To:focus {
  border-radius: 0 0 var(--textarea-radius) var(--textarea-radius) !important; }

.popoutNoteCounter-62U4Rh {
  right: 0 !important; }

.charCounterAdded-zz9O4t .container-9gOVw0 {
  border-radius: 0; }

/* SUPPORTED PLUGINS -> HideChannels */
.sidebar-2K8pFh.hideElement .container-3baos1 {
  height: 72px;
  padding: 0 4px 0 8px; }

.sidebar-2K8pFh + .chat-3bRxxu .typing-2GQL18 {
  width: calc(100% - 24px);
  left: 0; }

.sidebar-2K8pFh.hideElement + .chat-3bRxxu .typing-2GQL18 {
  width: calc(100% + 224px - 8px);
  left: -240px; }

/* SUPPORTED PLUGINS -> SpotifyControls */
.container-6sXIoE.withTimeline-824fT_ {
  margin-bottom: 0;
  background-color: #141414;
  border-bottom: none; }

.container-1giJp5 + .container-6sXIoE.withTimeline-824fT_ {
  border-top: 1px solid var(--card-border); }

.bar-g2ZMIm,
.volumeSlider-sR5g00 {
  cursor: pointer; }

.grabber-7sd5f5 {
  cursor: ew-resize; }

.barFill-Dhkah7 {
  background: #b3b3b3; }

.barFill-23-gu- {
  background-color: var(--slider-color) !important; }

[class*="theme-"] .themedPopout-1TrfdI {
  background-color: var(--popout-color);
  border-radius: var(--popout-radius);
  box-shadow: var(--default-shadow); }

.volumeSlider-sR5g00 .grabber-3mFHz2 {
  width: 12px;
  height: 12px;
  top: 6px; }

/* SUPPORTED PLUGINS -> ThemeRepo & PluginRepo */
#bd-settingspane-container .bd-pfbtn + .horizontal-1ae9ci .container-cMG81i .iconLayout-3OgqU3 {
  height: 34px;
  margin: 0 8px 0 0; }

#bd-settingspane-container .bd-pfbtn + .horizontal-1ae9ci .button-38aScr {
  padding: 0 !important;
  background: transparent !important;
  border: none !important;
  text-transform: none !important; }

#bd-settingspane-container .bd-pfbtn + .horizontal-1ae9ci .button-38aScr:hover {
  transform: scale(1) !important; }

/* SUPPORTED PLUGINS -> DiscordCrypt */
.dc-overlay-centerfield {
  border: none !important; }

#dc-header-master-msg {
  display: block;
  width: 480px;
  height: 20px;
  margin: 0 0 12px 0;
  font-size: 0; }

#dc-header-master-msg:after {
  position: relative;
  display: block;
  content: "Database is locked";
  width: 100%;
  height: 100%;
  line-height: 20px;
  font-weight: 700;
  font-size: 16px;
  font-family: sans-serif;
  color: #fff; }

#dc-prompt-master-msg {
  font-weight: 700 !important;
  font-size: 11px !important;
  font-family: sans-serif !important;
  color: #b2b2b2 !important; }

.dc-overlay-centerfield br {
  display: none; }

.dc-overlay-centerfield span,
.dc-overlay-centerfield strong {
  font-family: sans-serif !important; }

.dc-password-field {
  margin: 7px 0 0 0 !important; }

.stat-bar {
  height: 4px !important;
  padding: 0 !important;
  background: var(--slider-background) !important;
  border-radius: 2px !important;
  box-shadow: none !important; }

.stat-bar-rating {
  background: var(--accent-color) !important;
  box-shadow: none !important; }

.dc-ruler-align {
  display: inline-block !important;
  margin: 0 !important; }

.dc-button {
  margin: 0 !important; }

.smalltalk {
  background: rgba(0, 0, 0, 0.75); }

.smalltalk .page {
  width: 500px; }

.smalltalk .page header,
.smalltalk .page .action-area {
  padding: 12px !important; }

.smalltalk .page .content-area {
  padding: 0 12px !important; }

.smalltalk button {
  box-shadow: none !important;
  text-shadow: none !important; }

.dc-textarea {
  background: #171717 !important;
  border: none !important; }

.dc-button {
  display: block !important;
  width: 100% !important; }

#dc-toolbar {
  width: auto !important; }

.dc-tooltip .dc-tooltip-text {
  font-size: 12px !important;
  font-weight: 700 !important; }

.dc-tooltip .dc-tooltip-text::after {
  border-bottom-color: var(--popout-color) !important; }
