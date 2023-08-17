# Studies on Contract farming in India
One of the first attempt to use evidence gap map to show the categorise the studies on contract farming in India
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <title>EPPI-Mapper</title>
  <style>
    *, *:before, *:after {
  box-sizing: border-box;
}
html {
  box-sizing: border-box;
  font-family: 'Roboto', sans-serif;
  font-size: 14px;
  text-rendering: optimizeLegibility;
  -moz-osx-font-smoothing: grayscale;
  line-height: 1.5;
}
body {
  background-color: #ffffff;
  margin: 0;
  overflow: hidden;
}
a {
  color: #0275d8;
}
a:active, a:hover {
  outline-width: 0;
}
.clearfix:after {
  visibility: hidden;
  display: block;
  font-size: 0;
  content: " ";
  clear: both;
  height: 0;
}
* html .clearfix {
  zoom: 1;
}
*:first-child + html .clearfix {
  zoom: 1;
}
.loader {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background: #0275d8;
  z-index: 1000;
  transition: all 2s ease;
}
.loader span.spinner {
  animation: spin 1.2s linear infinite;
  border: 5px solid #ffffff;
  border-bottom-color: #0275d8;
  border-top-color: #0275d8;
  border-radius: 100%;
  display: inline-block;
  width: 40px;
  height: 40px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.header {
  padding: 0 18px;
}
.header-basic {
  background: #ffffff;
  padding: 0 18px;
  display: flex;
  font-size: 1.5rem;
  font-weight: bold;
  height: 108px;
  padding: 8px 8px 0;
  text-align: center;
}
.header-basic .header-title {
  flex-grow: 1;
}
.header-basic .header-title span {
  position: relative;
  top: 30%;
}
.header-basic img {
  height: 100px;
}
.header-basic img:nth-child(1) {
  float: left;
}
.header-basic img:nth-child(2) {
  float: right;
}
.wrapper {
  margin: 8px;
}
.pivot-table {
  font-size: 11px;
  font-weight: normal;
  width: 100%;
}
.pivot-table .top-head, .pivot-table .side-head, .pivot-table .body {
  display: inline-block;
  overflow: hidden;
}
.pivot-table .side-head, .pivot-table .body {
  float: left;
}
.pivot-table table {
  border: 0;
  border-collapse: collapse;
}
.pivot-table table thead th {
  border: 1px solid #ffffff;
  color: #ffffff;
  font-weight: normal;
  max-width: 103px;
  min-width: 103px;
  width: 103px;
  padding: 4px;
  overflow: hidden;
  text-overflow: ellipsis;
  vertical-align: top;
  text-align: left;
}
.pivot-table table tbody th, .pivot-table table tbody td {
  border: 1px solid #fff;
}
.pivot-table table tbody th {
  color: #ffffff;
  font-weight: normal;
  min-height: 103px;
  height: 103px;
  max-width: 103px;
  min-width: 0;
  width: 0;
  padding: 4px;
  overflow: hidden;
  text-overflow: ellipsis;
  vertical-align: top;
  text-align: left;
}
.pivot-table table tbody td {
  min-width: 103px;
  width: 103px;
  min-height: 103px;
  height: 103px;
}
.body table tbody td.cell div.data-wrapper {
  position: relative;
  background-color: #eeeeee;
  cursor: pointer;
  justify-items: center;
  align-items: center;
  width: 100%;
  height: 100%;
  overflow: hidden;
  -webkit-transition: all 0.5s;
  -moz-transition: all 0.5s;
  -moz-transition: all 0.5s;
  -ms-transition: all 0.5s;
  -o-transition: all 0.5s;
  transition: all 0.5s;
  flex-wrap: wrap;
  align-items: center;
  justify-content: space-around;
}
.body table tbody td.cell div.data-wrapper div.break {
  flex-basis: 100%;
  height: 0;
}
.body table tbody td.cell div.pie-wrapper {
  position: relative;
  background-color: #eeeeee;
  cursor: pointer;
  display: none;
  width: 100%;
  height: 100%;
  overflow: hidden;
}
.body table tbody td.cell div.mosaic-wrapper {
  position: relative;
  background-color: #eeeeee;
  cursor: pointer;
  display: none;
  width: 100px;
  height: 100px;
  max-width: 100px;
  max-height: 100px;
  overflow: hidden;
}
.body table tbody td.cell div.pie-wrapper div.pie,
.body table tbody td.cell div.pie-wrapper div.pie-hole{
  position: absolute;
  top: 50%;
  left: 50%;
  background-size: cover;
  border-radius: 100%;
  transform: translate(-50%, -50%);
}
.body table tbody td.cell div.pie-wrapper div.pie-hole{
  background-color: #dddddd;
}
.body table tbody td.cell.none div.data-wrapper,
.body table tbody td.cell.none div.pie-wrapper,
.body table tbody td.cell.none div.mosaic-wrapper {
  cursor: not-allowed !important;
}
.controls {
  display: inline-block;
  position: absolute;
}
.ui-segment {
  background-color: #ffffff;
  color: #0275d8;
  border: 1px solid #0275d8;
  border-radius: 4px;
  display: inline-block;
}
.ui-segment span.option.active {
  background-color: #0275d8;
  color: #ffffff;
}
.ui-segment span.option {
  font-size: 13px;
  padding-left: 23px;
  padding-right: 23px;
  height: 25px;
  text-align: center;
  display: inline-block;
  line-height: 25px;
  margin: 0;
  float: left;
  cursor: pointer;
  border-right: 1px solid #0275d8;
  transition: all 0.5s ease;
}
.ui-segment span.option:last-child {
  border-right: none;
}
.segment-select{
  display: none;
}
.footer {
  position: absolute;
  bottom: 0;
  background-color: #ffffff;
  color: rgba(0, 0, 0, 0.87);
  height: 36px;
  min-height: 36px;
  padding: 16px;
  width: 100%;
  -webkit-box-align: center;
  -ms-flex-align: center;
  align-items: center;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-flex: 0 !important;
  -ms-flex: 0 1 auto !important;
  flex: 0 1 auto !important;
}
.footer .inner svg {
  display: inline-block;
  vertical-align: middle;
}
.footer .legend .dot {
  border-radius: 100%;
  display: inline-block;
  height: 10px;
  width: 10px;
  margin: 2px 3px 0 6px;
}
.footer .legend .label {
  font-size: 1.0em;
}
.legend-tooltip {
  border: 1px solid #cccccc;
  display: block;
  position: absolute;
  width: 300px;
  background: #ffffff;
  color: #000000;
  padding: 6px 8px;
  border-radius: 4px;
  -webkit-box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  -moz-box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  z-index: 2;
}
.spacer {
  -webkit-box-flex: 1 !important;
  -ms-flex-positive: 1 !important;
  flex-grow: 1 !important;
}
.hide {
  display: none;
}
.tooltip {
  display: none;
  position: absolute;
  border: 1px solid #cccccc;
  background-color: #ffffff;
  border-radius: 3px;
  padding: 3px 6px 2px;
  -webkit-box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  -moz-box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  z-index: 2;
}
.tooltip .count {
  color: #0275d8;
  margin: 2px 3px;
}
.tooltip .count span {
  background-color: #0275d8;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  color: #ffffff;
  padding: 2px 4px;
}
.refs {
  font-size:  12px;
  color:  lightgrey;
  margin:  0;
  padding: 0 0 0 20px;
}
.veil {
  background: rgba(0, 0, 0, 0.7);
  display: none;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 99;
}
.veil.open {
  display: block;
}
.settings {
  position: absolute;
  top: 0;
  left: -600px;
  bottom: 0;
  background: #fff;
  color: #888;
  padding: 0;
  transition: all 0.5s ease;
  width: 600px;
  z-index: 100;
}
.settings.open {
  left: 0;
}
.settings > div.title {
  background-color: #0275d8;
  color: #ffffff;
  font-size: 22px;
  padding: 20px;
  margin: 0 0 10px 0;
}
.settings > div.title > a.btnSettings {
  -webkit-border-radius: 36px;
  -moz-border-radius: 36px;
  border-radius: 36px;
  background-color: #0275d8;
  color: #ffffff;
  display: inline-block;
  float: right;
  height: 36px;
  transition: all 0.25s ease;
  text-align: center;
  line-height: 36px;
  padding: 0 12px;
}
.settings > div.title > a.btnSettings:hover {
  background-color: #005cab;
  cursor: pointer;
}
.settings > div.title > a.btnSettings.busy{
  border: 3px solid #005cab !important;
  border-top-color: #ffffff !important;
  border-bottom-color: #ffffff !important;
  text-indent: -99999px;
  width: 36px;
  border-radius: 36px;
  animation: spin 1.2s linear infinite;
}
.settings > div.title > a.disabled {
  background-color: #005cab;
  cursor: not-allowed;
  opacity: 0.5;
  text-decoration: none;
}
.settings > div.title > a.right {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
  margin-left: 2px;
}
.settings > div.title > a.left {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.settings div.filter-type-wrapper {
  background-color: #efefef;
  position: absolute;
  top: 76px;
  overflow: auto;
  padding: 0 10px 0 0;
  width: 60%;
}
.settings div.filter-wrapper {
  background-color: #efefef;
  position: absolute;
  top: 226px;
  bottom: 0;
  overflow: auto;
  padding: 0 10px 0 0;
  width: 60%;
}
.settings div.filter-type-wrapper h2,
.settings div.filter-wrapper h2 {
  margin-left: 20px;
  margin-bottom: 10px;
}
.settings div.filter-type-wrapper ul,
.settings div.filter-wrapper ul {
  list-style: none;
  margin: 0 0 0 16px;
  padding: 0;
}
.settings div.filter-type-wrapper ul li,
.settings div.filter-wrapper ul li {
  margin: 0;
  padding: 3px 5px;
}
.settings div.filter-type-wrapper ul li:hover,
.settings div.filter-wrapper ul li:hover {
  cursor: pointer;
}
.settings div.filter-type-wrapper ul li span,
.settings div.filter-type-wrapper ul li svg,
.settings div.filter-wrapper ul li span,
.settings div.filter-wrapper ul li svg {
  display: inline-block;
  vertical-align: middle;
}
.settings div.filter-type-wrapper ul li svg,
.settings div.filter-wrapper ul li svg {
  display: none;
}
.settings div.filter-type-wrapper ul li.checked svg#checked,
.settings div.filter-wrapper ul li.checked svg#checked {
  display: inline-block;
}
.settings div.filter-type-wrapper ul li.unchecked svg#unchecked,
.settings div.filter-wrapper ul li.unchecked svg#unchecked {
  display: inline-block;
}
.settings div.filter-type-wrapper ul li.indeterminate svg#indeterminate,
.settings div.filter-wrapper ul li.indeterminate svg#indeterminate {
  display: inline-block;
}
.settings div.style-wrapper {
  position: absolute;
  top: 76px;
  right: 0;
  bottom: 0;
  overflow: auto;
  padding: 0 20px 0 10px;
  width: 40%;
}
.settings div.style-wrapper h2 {
  margin-bottom: 10px;
}
.settings div.style-wrapper ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
.settings div.style-wrapper ul li {
  margin: 0;
  padding: 3px 5px;
}
.settings div.style-wrapper ul li:hover {
  cursor: pointer;
}
.settings div.style-wrapper ul li span,
.settings div.style-wrapper ul li svg {
  display: inline-block;
  vertical-align: middle;
}
.settings div.style-wrapper ul li svg {
  display: none;
}
.settings div.style-wrapper ul li.checked svg#checked {
  display: inline-block;
}
.settings div.style-wrapper ul li.unchecked svg#unchecked {
  display: inline-block;
}
.reader {
  position: absolute;
  top: 0;
  right: -1000px;
  bottom: 0;
  background: #fff;
  color: #000;
  padding: 0;
  transition: all 0.5s ease;
  width: 1000px;
  z-index: 100;
}
.reader.open {
  right: 0;
}
.reader > div.title {
  background-color: #0275d8;
  color: #ffffff;
  font-size: 22px;
  padding: 20px;
}
.reader > div.title > a.close {
  -webkit-border-radius: 100%;
  -moz-border-radius: 100%;
  border-radius: 100%;
  color: #ffffff;
  display: inline-block;
  width: 36px;
  height: 36px;
  transition: all 0.25s ease;
  text-align: center;
  line-height: 36px;
  margin-right: 20px;
}
.reader > div.title > a.close:hover {
  background-color: #0275d8;
  cursor: pointer;
}
.reader > div.title > input {
  border: 1px solid #96c9fb;
  background: #0275d8;
  padding: 6px;
  color: #96c9fb;
  float: right;
  font-size: 16px;
  transition: all 0.5s ease;
}
.reader > div.title > input:focus {
  background: #96c9fb;
  color: #1f5286;
}
.reader > div.title > input::-webkit-input-placeholder { /* Chrome/Opera/Safari */
  color: #96c9fb;
}
.reader > div.title > input::-moz-placeholder { /* Firefox 19+ */
  color: #96c9fb;
}
.reader > div.title > input:-ms-input-placeholder { /* IE 10+ */
  color: #96c9fb;
}
.reader > div.title > input:-moz-placeholder { /* Firefox 18- */
  color: #96c9fb;
}
.reader > div.title > select {
  border: 1px solid #96c9fb;
  background: #0275d8;
  padding: 6px;
  color: #96c9fb;
  float: right;
  font-size: 15px;
  transition: all 0.5s ease;
}
.reader > div.title > button {
  float: right;
  color: #96c9fb;
  border: 1px solid #96c9fb;
  margin-left: 5px;
}

.reader > div.content {
  background: #ffffff;
  display: flex;
  align-content: stretch;
  align-items: stretch;
  height: 92.4%;
}
.reader > div.content > div.reader-filter {
  background-color: #efefef;
  border-right: 1px solid #ffffff;
  overflow: auto;
  width: 200px;
  min-width: 200px;
  max-width: 200px;
}
.reader > div.content > div.filter-opts {
  background-color: #efefef;
  border-right: 1px solid #ffffff;
  overflow: auto;
  width: 200px;
  min-width: 200px;
  max-width: 200px;
  float: right;
}
.settings > div.filter-wrapper > div.controlTainer {
  align-content: center;
  padding: 10px;
}
.reader > div.content > div.reader-filter ul {
  list-style: none;
  margin: 0;
  padding: 0;
  width: 100%;
  overflow: hidden;
}
.reader > div.content > div.reader-filter > ul > ul {
  padding: 0 0 0 12px;
 }
.reader > div.content > div.reader-filter ul li:hover {
  cursor: pointer;
}
.reader > div.content > div.reader-filter ul li {
  padding: 3px 6px 2px;
  display: inline-flex;
  align-items: end;
  width: 100%;
}
.reader > div.content > div.reader-filter ul li span,
.reader > div.content > div.reader-filter ul li svg {
  display: inline-block;
  vertical-align: middle;
}
.reader > div.content > div.reader-filter ul li svg {
  display: none;
  width: 24px;
  min-width: 24px;
}
.reader > div.content > div.reader-filter ul li span {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.reader > div.content > div.reader-filter ul li.checked svg#checked {
  display: inline-block;
}
.reader > div.content > div.reader-filter ul li.unchecked svg#unchecked{
  display: inline-block;
}
.reader > div.content > div.reader-filter ul li.indeterminate svg#indeterminate {
  display: inline-block;
}
.reader > div.content > div.nav {
  background-color: #efefef;
  border-right: 1px solid #ffffff;
  overflow: auto;
  width: 280px;
  min-width: 280px;
  max-width: 280px;
}
.reader > div.content > div.navTainer {
  background-color: #efefef;
  border-right: 1px solid #ffffff;
  overflow: auto;
  width: 280px;
  min-width: 280px;
  max-width: 280px;
}
.reader > div.content > div.navTainer .navGroupSelect {
  color: #0275d8;
  border-top: 1px solid #0275d8;
  padding: 6px 10px 4px;
}
.reader > div.content > div.navTainer .ref-sort-order {
  color: #0275d8;
  border-top: 1px solid #0275d8;
  border-bottom: 1px solid #0275d8;
  padding: 6px 10px 4px;
}
.reader > div.content > div.navTainer > div > ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
.reader > div.content > div.nav > ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
.reader > div.content > div.nav > ul > li {
  border-bottom: 1px solid #ffffff;
  padding: 6px 10px 8px;
  transition: all 0.5s ease;
}
.reader > div.content div.nav > ul li,
.reader > div.content > div.navTainer > div > ul > li > ul > li {
  padding: 6px 10px 8px;
}
.reader > div.content div.nav > ul.segmented > li {
  padding: 0;
}
.reader > div.content div.nav > ul.segmented > li > ul {
  list-style: none;
  margin: 0;
  padding: 0;
}
.reader > div.content div.nav > ul.segmented > li > ul > li {
  padding: 6px 10px 8px;
}
.reader > div.content div.nav > ul.segmented > li > div.segment-title {
  color: #000000;
  font-weight: bold;
  padding: 6px 10px 8px;
  width: 100%;
}
.reader > div.content > div.navTainer > div > ul > li > ul > li.selected:hover {
  background-color: silver;
  cursor: pointer;
}
.reader > div.content > div.navTainer > div > ul > li[segmented=no]:hover {
  background-color: #ffffff;
  cursor: pointer;
}
.reader > div.content > div.navTainer > div > ul > li[segmented=no].selected:hover {
  background-color: silver;
  cursor: pointer;
}
.reader > div.content div.nav > ul li.selected {
  background-color: #aaaaaa;
  color: #ffffff;
}
.reader > div.content div.nav > ul li > div {
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}
.reader > div.content div.nav > ul li > div.title {
  font-weight: bold;
}
.reader > div.content div.nav > ul li > div.auth,
.reader > div.content div.nav > ul li > div.date {
  color: #666666;
}
.reader > div.content div.nav > ul li.selected > div.auth,
.reader > div.content div.nav > ul li.selected > div.date {
  color: #ffffff;
}
.reader > div.content div.nav > ul li > div.auth {
  font-style: italic;
}
.reader > div.content > div.read {
  flex-grow: 1;
  overflow: auto;
  padding: 10px 18px;
}
.reader > div.content > div.read > h2 {
  margin-top: 0;
}
.reader > div.content > div.read > hr {
  background-color: #efefef;
  border: 0;
  height: 1px;
}
.reader > div.content > div.read > p {
  font-size: 1.3rem;
}
.reader > div.content > div.read > div.meta-data {
  margin-top: 16px;
}
.reader > div.content > div.read > div.meta-data > div.meta-data-item > label {
  color: #aaaaaa;
  display: block;
  float: left;
  width: 140px;
  margin: 0 0 3px 0;
  padding: 3px 6px;
}
.reader > div.content > div.read > div.meta-data > div.meta-data-item > span {
  border: 1px solid #eeeeee;
  display: block;
  float: left;
  margin: 0 0 3px -140px;
  padding: 2px 4px 2px 144px;
  width: 100%;
}
.ref-sort-order {
  padding: 4px 8px;
}
.menu {
  background-color: #ffffff;
  border-bottom: 1px solid #eeeeee;
  display: block;
  list-style: none;
  margin: 0;
  padding: 0;
}
.menu:after {
  content: "";
  display: table;
  clear: both;
}
.menu .menu-item {
  background-color: #ffffff;
  color: #555555;
  display: flex;
  padding: 8px 12px;
  transition: all 0.25s ease-in-out;
  cursor: pointer;
  float: left;
}
.menu .menu-item:hover {
  background-color: #f1f1f1;
  color: #000000;
}
.menu .menu-item:hover svg {
  fill: #000000;
}
.menu .menu-item span {
  margin-left: 4px;
  overflow: hidden;
  word-break: keep-all;
  transition: all 500ms ease-in-out;
}
.menu .menu-item svg {
  fill: #555555;
  display: inline-block;
  margin: 0 0 0 4px;
}
.menu .menu-item span.active-text,
.menu .menu-item svg.active-svg {
  display: none;
}
.menu .menu-item.active span.inactive-text,
.menu .menu-item.active svg.inactive-svg {
  display: none;
}
.menu .menu-item.active span.active-text,
.menu .menu-item.active svg.active-svg {
  display: block;
}
.refMenuItemLegend {
  -webkit-border-radius: 100%;
  -moz-border-radius: 100%;
  border: 1px solid #ffffff;
  border-radius: 100%;
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 6px 3px 0;
  float: right;
}
.clickable-row,
.clickable-col {
  cursor: pointer;
}
.top-head th div,
.side-head th div {
  position: relative;
  width: 100%;
  height: 100%;
}
.top-head th div svg,
.side-head th div svg {
  display: none;
  background: rgba(255, 255, 255, 0.8);
}
.top-head th div svg,
.side-head th div svg {
  position: absolute;
  top: -4px;
  right: -4px;
}
.top-head th:not(.collapsed) div svg#arrowLeft,
.side-head th:not(.collapsed) div svg#arrowUp {
  cursor: pointer;
  display: inline-block;
}
.top-head th.collapsed div svg#arrowRight,
.side-head th.collapsed div svg#arrowDown {
  cursor: pointer;
  display: inline-block;
}
.top-head th.busy div svg#refresh,
.side-head th.busy div svg#refresh {
  border-radius: 100%;
  cursor: pointer;
  display: inline-block;
  animation: spin 1s linear infinite;
}
.btnColCollapse,
.btnRowCollapse {
  opacity: 40%;
}
.top-head th.collapsed {
  min-width: 0;
  max-width: 0;
  width: 0;
  padding: 4px 0;
}
.top-head th.collapsed.level-1 {
  min-width: 103px;
  width: 103px;
  padding: 4px;
}
.side-head th.collapsed {
  min-height: 0;
  max-height: 0;
  height: 0;
  padding: 0 4px;
}
.side-head th.collapsed.level-1 {
  min-height: 103px;
  height: 103px;
  padding: 4px;
}
.body td.collapsed-col {
  min-width: 18px;
  width: 18px;
}
.body td.collapsed-row {
  min-height: 18px;
  height: 18px !important;
}
.body td.collapsed-col,
.body td.collapsed-row {
  background: rgba(0, 0, 0, 0.2);
}
.body td.collapsed-col .mosaic-wrapper,
.body td.collapsed-row .mosaic-wrapper {
  width: auto !important;
  height: auto !important;
}
.body td.collapsed-col svg,
.body td.collapsed-row svg {
  display: none;
}
.body td.collapsed-col .pie-wrapper,
.body td.collapsed-col .mosaic-wrapper,
.body td.collapsed-col .data-wrapper,
.body td.collapsed-row .pie-wrapper,
.body td.collapsed-row .mosaic-wrapper,
.body td.collapsed-row .data-wrapper {
  opacity: 0 !important;
}
.top-head th.collapsed:not(.level-1) span,
.side-head th.collapsed:not(.level-1) span {
  display: none;
}
.top-head th.collapsed:not(.level-1),
.side-head th.collapsed:not(.level-1) {
  border-width: 0;
}
.top-head th.collapsed.first:not(.level-1) {
  border-left: 1px solid #ffffff !important;
}
.top-head th.collapsed.last:not(.level-1) {
  border-right: 1px solid #ffffff !important;
}
.side-head th.collapsed.first:not(.level-1) {
  border-top: 1px solid #ffffff !important;
}
.side-head th.collapsed.last:not(.level-1) {
  border-bottom: 1px solid #ffffff !important;
}
@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
.attribute-tooltip {
  position: absolute;
  border: 1px solid #cccccc;
  background-color: #ffffff;
  border-radius: 3px;
  display: none;
  padding: 3px 6px 2px;
  text-overflow: ellipsis;
  max-width: 350px !important;
  min-width: 200px !important;
  -webkit-box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  -moz-box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  box-shadow: 0 2px 10px 2px rgba(0, 0, 0, 0.3);
  z-index: 2;
}
.attribute-tooltip.show {
  display: block;
}
.attribute-tooltip .close-tooltip {
  cursor: pointer;
  float: right;
}
.attribute-tooltip .content {
  margin: 0 0 12px 0;
}
.attribute-tooltip h4 {
  margin: 0 0 8px 0;
}
.text-center {
  text-align: center;
}
.text-muted {
  color: #6c757d !important;
  font-size: 11px;
  margin: 10px 0 0 0;
}
#filterClearButton,
#codeFilterClearButton {
  float: right;
}
#codeFilterClearButton {
  width: 100%;
}
.btn {
  background-color: transparent;
  border: 1px solid #0275d8;
  color: #0275d8;
  display: block;
  font-weight: 400;
  padding: .375rem .75rem;
  font-size: 1rem;
  line-height: 1.5;
  transition: color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out;
}
.btn:hover {
  color: #fff;
  background-color: #0275d8;
  border-color: #0275d8;
  cursor: pointer;
}

@keyframes spin {
  from {transform:rotate(0deg);}
  to {transform:rotate(360deg);}
}

  </style>
  <script type="text/javascript">
    var isIE = false || !!document.documentMode;

    if (isIE === true) {
      alert("Unfortunately this map cannot be used in Internet Explorer. You will need to use Microsoft Edge, Firefox or Google Chrome.");
    }
  </script>
</head>
<body>
  <div class="attribute-tooltip">
    <span class="close-tooltip">X</span>
    <div class="content"></div>
  </div>
  <div class="loader">
    <span class="spinner"></span>
  </div>
  <div class="veil"></div>
  <div class="settings"></div>
  <div class="reader"></div>
  <ul class="menu">
    <li class="menu-item menu-settings">
      <svg xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M0 0h24v24H0z" fill="none"/>
        <path d="M19.43 12.98c.04-.32.07-.64.07-.98s-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46c-.12-.22-.39-.3-.61-.22l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65C14.46 2.18 14.25 2 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1c-.23-.09-.49 0-.61.22l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98s.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46c.12.22.39.3.61.22l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.23.09.49 0 .61-.22l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zM12 15.5c-1.93 0-3.5-1.57-3.5-3.5s1.57-3.5 3.5-3.5 3.5 1.57 3.5 3.5-1.57 3.5-3.5 3.5z"/>
      </svg>
      <span>Filters</span>
    </li>
    <li class="menu-item menu-expand">
      <svg class="inactive-svg" xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M15 21h2v-2h-2v2zm4 0h2v-2h-2v2zM7 21h2v-2H7v2zm4 0h2v-2h-2v2zm8-4h2v-2h-2v2zm0-4h2v-2h-2v2zM3 3v18h2V5h16V3H3zm16 6h2V7h-2v2z"/>
        <path d="M0 0h24v24H0z" fill="none"/>
      </svg>
      <svg class="active-svg" xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M13 7h-2v2h2V7zm0 4h-2v2h2v-2zm4 0h-2v2h2v-2zM3 3v18h18V3H3zm16 16H5V5h14v14zm-6-4h-2v2h2v-2zm-4-4H7v2h2v-2z"/>
        <path d="M0 0h24v24H0z" fill="none"/>
      </svg>
      <span class="inactive-text">Hide Headers</span>
      <span class="active-text">Show Headers</span>
    </li>
    <li class="menu-item menu-fullscreen">
      <svg class="inactive-svg" xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M0 0h24v24H0z" fill="none"/><path d="M7 14H5v5h5v-2H7v-3zm-2-4h2V7h3V5H5v5zm12 7h-3v2h5v-5h-2v3zM14 5v2h3v3h2V5h-5z"/>
      </svg>
      <svg class="active-svg" xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M0 0h24v24H0z" fill="none"/><path d="M5 16h3v3h2v-5H5v2zm3-8H5v2h5V5H8v3zm6 11h2v-3h3v-2h-5v5zm2-11V5h-2v5h5V8h-3z"/>
      </svg>
      <span class="inactive-text">Fullscreen</span>
      <span class="active-text">Exit Fullscreen</span>
    </li>
    <li class="menu-item menu-about">
      <svg xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M0 0h24v24H0z" fill="none"/>
        <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z"/>
      </svg>
      <span>About</span>
    </li>
    <li class="menu-item menu-studysubmit">
      <svg xlmns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path d="M0 0h24v24H0z" fill="none"/>
        <path d="M8.016 15l3.984-3.984 3.984 3.984-1.406 1.453-1.594-1.594v4.125h-1.969v-4.125l-1.594 1.547zM18 20.016v-11.016h-5.016v-5.016h-6.984v16.031h12zM14.016 2.016l6 6v12q0 0.797-0.609 1.383t-1.406 0.586h-12q-0.797 0-1.406-0.586t-0.609-1.383l0.047-16.031q0-0.797 0.586-1.383t1.383-0.586h8.016z"></path>
      </svg>
      <span>Submit a Study</span>
    </li>
    <li class="menu-item menu-reader">
      <svg xmlns="http://www.w3.org/2000/svg" fill="#eeeeee" width="18" height="18" viewBox="0 0 24 24">
        <path fill="none" d="M-74 29h48v48h-48V29zM0 0h24v24H0V0zm0 0h24v24H0V0z"/>
        <path d="M13 12h7v1.5h-7zm0-2.5h7V11h-7zm0 5h7V16h-7zM21 4H3c-1.1 0-2 .9-2 2v13c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 15h-9V6h9v13z"/>
      </svg>
      <span>View Records<span class="record-count"></span></span>
    </li>
  </ul>
  <div class="header clearfix">
    <p>One of the first attempt to use evidence gap map to show the categorise the studies on contract farming in India</p>
  </div>
  <div class="wrapper">
    <div class="pivot-table clearfix">
      <div class="top-head-wrapper">
        <div class="top-head">
          <table>
            <thead>
            </thead>
          </table>
        </div>
      </div>
      <div class="side-head">
        <table>
          <tbody>
          </tbody>
        </table>
      </div>
      <div class="body">
        <table>
          <tbody>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="footer">
    <div class="legend"></div>
    <div class="spacer"></div>
    <div class="inner">
      Generated using v.2.2.4 of the EPPI-Mapper
      powered by <a href="https://eppi.ioe.ac.uk/cms/Default.aspx?tabid=2914" target="_blank">EPPI Reviewer</a>
      and created with
      <svg fill="#c62828" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg">
        <path d="M0 0h24v24H0z" fill="none"/>
        <path d="M12 21.35l-1.45-1.32C5.4 15.36 2 12.28 2 8.5 2 5.42 4.42 3 7.5 3c1.74 0 3.41.81 4.5 2.09C13.09 3.81 14.76 3 16.5 3 19.58 3 22 5.42 22 8.5c0 3.78-3.4 6.86-8.55 11.54L12 21.35z"/>
      </svg>
      by the
      <a href="http://www.digitalsolutionfoundry.co.za/" target="_blank">Digital Solution Foundry</a> team.
    </div>
  </div>
  <script type="text/javascript">/*! jQuery v3.3.1 | (c) JS Foundation and other contributors | jquery.org/license */
!function(e,t){"use strict";"object"==typeof module&&"object"==typeof module.exports?module.exports=e.document?t(e,!0):function(e){if(!e.document)throw new Error("jQuery requires a window with a document");return t(e)}:t(e)}("undefined"!=typeof window?window:this,function(e,t){"use strict";var n=[],r=e.document,i=Object.getPrototypeOf,o=n.slice,a=n.concat,s=n.push,u=n.indexOf,l={},c=l.toString,f=l.hasOwnProperty,p=f.toString,d=p.call(Object),h={},g=function e(t){return"function"==typeof t&&"number"!=typeof t.nodeType},y=function e(t){return null!=t&&t===t.window},v={type:!0,src:!0,noModule:!0};function m(e,t,n){var i,o=(t=t||r).createElement("script");if(o.text=e,n)for(i in v)n[i]&&(o[i]=n[i]);t.head.appendChild(o).parentNode.removeChild(o)}function x(e){return null==e?e+"":"object"==typeof e||"function"==typeof e?l[c.call(e)]||"object":typeof e}var b="3.3.1",w=function(e,t){return new w.fn.init(e,t)},T=/^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;w.fn=w.prototype={jquery:"3.3.1",constructor:w,length:0,toArray:function(){return o.call(this)},get:function(e){return null==e?o.call(this):e<0?this[e+this.length]:this[e]},pushStack:function(e){var t=w.merge(this.constructor(),e);return t.prevObject=this,t},each:function(e){return w.each(this,e)},map:function(e){return this.pushStack(w.map(this,function(t,n){return e.call(t,n,t)}))},slice:function(){return this.pushStack(o.apply(this,arguments))},first:function(){return this.eq(0)},last:function(){return this.eq(-1)},eq:function(e){var t=this.length,n=+e+(e<0?t:0);return this.pushStack(n>=0&&n<t?[this[n]]:[])},end:function(){return this.prevObject||this.constructor()},push:s,sort:n.sort,splice:n.splice},w.extend=w.fn.extend=function(){var e,t,n,r,i,o,a=arguments[0]||{},s=1,u=arguments.length,l=!1;for("boolean"==typeof a&&(l=a,a=arguments[s]||{},s++),"object"==typeof a||g(a)||(a={}),s===u&&(a=this,s--);s<u;s++)if(null!=(e=arguments[s]))for(t in e)n=a[t],a!==(r=e[t])&&(l&&r&&(w.isPlainObject(r)||(i=Array.isArray(r)))?(i?(i=!1,o=n&&Array.isArray(n)?n:[]):o=n&&w.isPlainObject(n)?n:{},a[t]=w.extend(l,o,r)):void 0!==r&&(a[t]=r));return a},w.extend({expando:"jQuery"+("3.3.1"+Math.random()).replace(/\D/g,""),isReady:!0,error:function(e){throw new Error(e)},noop:function(){},isPlainObject:function(e){var t,n;return!(!e||"[object Object]"!==c.call(e))&&(!(t=i(e))||"function"==typeof(n=f.call(t,"constructor")&&t.constructor)&&p.call(n)===d)},isEmptyObject:function(e){var t;for(t in e)return!1;return!0},globalEval:function(e){m(e)},each:function(e,t){var n,r=0;if(C(e)){for(n=e.length;r<n;r++)if(!1===t.call(e[r],r,e[r]))break}else for(r in e)if(!1===t.call(e[r],r,e[r]))break;return e},trim:function(e){return null==e?"":(e+"").replace(T,"")},makeArray:function(e,t){var n=t||[];return null!=e&&(C(Object(e))?w.merge(n,"string"==typeof e?[e]:e):s.call(n,e)),n},inArray:function(e,t,n){return null==t?-1:u.call(t,e,n)},merge:function(e,t){for(var n=+t.length,r=0,i=e.length;r<n;r++)e[i++]=t[r];return e.length=i,e},grep:function(e,t,n){for(var r,i=[],o=0,a=e.length,s=!n;o<a;o++)(r=!t(e[o],o))!==s&&i.push(e[o]);return i},map:function(e,t,n){var r,i,o=0,s=[];if(C(e))for(r=e.length;o<r;o++)null!=(i=t(e[o],o,n))&&s.push(i);else for(o in e)null!=(i=t(e[o],o,n))&&s.push(i);return a.apply([],s)},guid:1,support:h}),"function"==typeof Symbol&&(w.fn[Symbol.iterator]=n[Symbol.iterator]),w.each("Boolean Number String Function Array Date RegExp Object Error Symbol".split(" "),function(e,t){l["[object "+t+"]"]=t.toLowerCase()});function C(e){var t=!!e&&"length"in e&&e.length,n=x(e);return!g(e)&&!y(e)&&("array"===n||0===t||"number"==typeof t&&t>0&&t-1 in e)}var E=function(e){var t,n,r,i,o,a,s,u,l,c,f,p,d,h,g,y,v,m,x,b="sizzle"+1*new Date,w=e.document,T=0,C=0,E=ae(),k=ae(),S=ae(),D=function(e,t){return e===t&&(f=!0),0},N={}.hasOwnProperty,A=[],j=A.pop,q=A.push,L=A.push,H=A.slice,O=function(e,t){for(var n=0,r=e.length;n<r;n++)if(e[n]===t)return n;return-1},P="checked|selected|async|autofocus|autoplay|controls|defer|disabled|hidden|ismap|loop|multiple|open|readonly|required|scoped",M="[\\x20\\t\\r\\n\\f]",R="(?:\\\\.|[\\w-]|[^\0-\\xa0])+",I="\\["+M+"*("+R+")(?:"+M+"*([*^$|!~]?=)"+M+"*(?:'((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\"|("+R+"))|)"+M+"*\\]",W=":("+R+")(?:\\((('((?:\\\\.|[^\\\\'])*)'|\"((?:\\\\.|[^\\\\\"])*)\")|((?:\\\\.|[^\\\\()[\\]]|"+I+")*)|.*)\\)|)",$=new RegExp(M+"+","g"),B=new RegExp("^"+M+"+|((?:^|[^\\\\])(?:\\\\.)*)"+M+"+$","g"),F=new RegExp("^"+M+"*,"+M+"*"),_=new RegExp("^"+M+"*([>+~]|"+M+")"+M+"*"),z=new RegExp("="+M+"*([^\\]'\"]*?)"+M+"*\\]","g"),X=new RegExp(W),U=new RegExp("^"+R+"$"),V={ID:new RegExp("^#("+R+")"),CLASS:new RegExp("^\\.("+R+")"),TAG:new RegExp("^("+R+"|[*])"),ATTR:new RegExp("^"+I),PSEUDO:new RegExp("^"+W),CHILD:new RegExp("^:(only|first|last|nth|nth-last)-(child|of-type)(?:\\("+M+"*(even|odd|(([+-]|)(\\d*)n|)"+M+"*(?:([+-]|)"+M+"*(\\d+)|))"+M+"*\\)|)","i"),bool:new RegExp("^(?:"+P+")$","i"),needsContext:new RegExp("^"+M+"*[>+~]|:(even|odd|eq|gt|lt|nth|first|last)(?:\\("+M+"*((?:-\\d)?\\d*)"+M+"*\\)|)(?=[^-]|$)","i")},G=/^(?:input|select|textarea|button)$/i,Y=/^h\d$/i,Q=/^[^{]+\{\s*\[native \w/,J=/^(?:#([\w-]+)|(\w+)|\.([\w-]+))$/,K=/[+~]/,Z=new RegExp("\\\\([\\da-f]{1,6}"+M+"?|("+M+")|.)","ig"),ee=function(e,t,n){var r="0x"+t-65536;return r!==r||n?t:r<0?String.fromCharCode(r+65536):String.fromCharCode(r>>10|55296,1023&r|56320)},te=/([\0-\x1f\x7f]|^-?\d)|^-$|[^\0-\x1f\x7f-\uFFFF\w-]/g,ne=function(e,t){return t?"\0"===e?"\ufffd":e.slice(0,-1)+"\\"+e.charCodeAt(e.length-1).toString(16)+" ":"\\"+e},re=function(){p()},ie=me(function(e){return!0===e.disabled&&("form"in e||"label"in e)},{dir:"parentNode",next:"legend"});try{L.apply(A=H.call(w.childNodes),w.childNodes),A[w.childNodes.length].nodeType}catch(e){L={apply:A.length?function(e,t){q.apply(e,H.call(t))}:function(e,t){var n=e.length,r=0;while(e[n++]=t[r++]);e.length=n-1}}}function oe(e,t,r,i){var o,s,l,c,f,h,v,m=t&&t.ownerDocument,T=t?t.nodeType:9;if(r=r||[],"string"!=typeof e||!e||1!==T&&9!==T&&11!==T)return r;if(!i&&((t?t.ownerDocument||t:w)!==d&&p(t),t=t||d,g)){if(11!==T&&(f=J.exec(e)))if(o=f[1]){if(9===T){if(!(l=t.getElementById(o)))return r;if(l.id===o)return r.push(l),r}else if(m&&(l=m.getElementById(o))&&x(t,l)&&l.id===o)return r.push(l),r}else{if(f[2])return L.apply(r,t.getElementsByTagName(e)),r;if((o=f[3])&&n.getElementsByClassName&&t.getElementsByClassName)return L.apply(r,t.getElementsByClassName(o)),r}if(n.qsa&&!S[e+" "]&&(!y||!y.test(e))){if(1!==T)m=t,v=e;else if("object"!==t.nodeName.toLowerCase()){(c=t.getAttribute("id"))?c=c.replace(te,ne):t.setAttribute("id",c=b),s=(h=a(e)).length;while(s--)h[s]="#"+c+" "+ve(h[s]);v=h.join(","),m=K.test(e)&&ge(t.parentNode)||t}if(v)try{return L.apply(r,m.querySelectorAll(v)),r}catch(e){}finally{c===b&&t.removeAttribute("id")}}}return u(e.replace(B,"$1"),t,r,i)}function ae(){var e=[];function t(n,i){return e.push(n+" ")>r.cacheLength&&delete t[e.shift()],t[n+" "]=i}return t}function se(e){return e[b]=!0,e}function ue(e){var t=d.createElement("fieldset");try{return!!e(t)}catch(e){return!1}finally{t.parentNode&&t.parentNode.removeChild(t),t=null}}function le(e,t){var n=e.split("|"),i=n.length;while(i--)r.attrHandle[n[i]]=t}function ce(e,t){var n=t&&e,r=n&&1===e.nodeType&&1===t.nodeType&&e.sourceIndex-t.sourceIndex;if(r)return r;if(n)while(n=n.nextSibling)if(n===t)return-1;return e?1:-1}function fe(e){return function(t){return"input"===t.nodeName.toLowerCase()&&t.type===e}}function pe(e){return function(t){var n=t.nodeName.toLowerCase();return("input"===n||"button"===n)&&t.type===e}}function de(e){return function(t){return"form"in t?t.parentNode&&!1===t.disabled?"label"in t?"label"in t.parentNode?t.parentNode.disabled===e:t.disabled===e:t.isDisabled===e||t.isDisabled!==!e&&ie(t)===e:t.disabled===e:"label"in t&&t.disabled===e}}function he(e){return se(function(t){return t=+t,se(function(n,r){var i,o=e([],n.length,t),a=o.length;while(a--)n[i=o[a]]&&(n[i]=!(r[i]=n[i]))})})}function ge(e){return e&&"undefined"!=typeof e.getElementsByTagName&&e}n=oe.support={},o=oe.isXML=function(e){var t=e&&(e.ownerDocument||e).documentElement;return!!t&&"HTML"!==t.nodeName},p=oe.setDocument=function(e){var t,i,a=e?e.ownerDocument||e:w;return a!==d&&9===a.nodeType&&a.documentElement?(d=a,h=d.documentElement,g=!o(d),w!==d&&(i=d.defaultView)&&i.top!==i&&(i.addEventListener?i.addEventListener("unload",re,!1):i.attachEvent&&i.attachEvent("onunload",re)),n.attributes=ue(function(e){return e.className="i",!e.getAttribute("className")}),n.getElementsByTagName=ue(function(e){return e.appendChild(d.createComment("")),!e.getElementsByTagName("*").length}),n.getElementsByClassName=Q.test(d.getElementsByClassName),n.getById=ue(function(e){return h.appendChild(e).id=b,!d.getElementsByName||!d.getElementsByName(b).length}),n.getById?(r.filter.ID=function(e){var t=e.replace(Z,ee);return function(e){return e.getAttribute("id")===t}},r.find.ID=function(e,t){if("undefined"!=typeof t.getElementById&&g){var n=t.getElementById(e);return n?[n]:[]}}):(r.filter.ID=function(e){var t=e.replace(Z,ee);return function(e){var n="undefined"!=typeof e.getAttributeNode&&e.getAttributeNode("id");return n&&n.value===t}},r.find.ID=function(e,t){if("undefined"!=typeof t.getElementById&&g){var n,r,i,o=t.getElementById(e);if(o){if((n=o.getAttributeNode("id"))&&n.value===e)return[o];i=t.getElementsByName(e),r=0;while(o=i[r++])if((n=o.getAttributeNode("id"))&&n.value===e)return[o]}return[]}}),r.find.TAG=n.getElementsByTagName?function(e,t){return"undefined"!=typeof t.getElementsByTagName?t.getElementsByTagName(e):n.qsa?t.querySelectorAll(e):void 0}:function(e,t){var n,r=[],i=0,o=t.getElementsByTagName(e);if("*"===e){while(n=o[i++])1===n.nodeType&&r.push(n);return r}return o},r.find.CLASS=n.getElementsByClassName&&function(e,t){if("undefined"!=typeof t.getElementsByClassName&&g)return t.getElementsByClassName(e)},v=[],y=[],(n.qsa=Q.test(d.querySelectorAll))&&(ue(function(e){h.appendChild(e).innerHTML="<a id='"+b+"'></a><select id='"+b+"-\r\\' msallowcapture=''><option selected=''></option></select>",e.querySelectorAll("[msallowcapture^='']").length&&y.push("[*^$]="+M+"*(?:''|\"\")"),e.querySelectorAll("[selected]").length||y.push("\\["+M+"*(?:value|"+P+")"),e.querySelectorAll("[id~="+b+"-]").length||y.push("~="),e.querySelectorAll(":checked").length||y.push(":checked"),e.querySelectorAll("a#"+b+"+*").length||y.push(".#.+[+~]")}),ue(function(e){e.innerHTML="<a href='' disabled='disabled'></a><select disabled='disabled'><option/></select>";var t=d.createElement("input");t.setAttribute("type","hidden"),e.appendChild(t).setAttribute("name","D"),e.querySelectorAll("[name=d]").length&&y.push("name"+M+"*[*^$|!~]?="),2!==e.querySelectorAll(":enabled").length&&y.push(":enabled",":disabled"),h.appendChild(e).disabled=!0,2!==e.querySelectorAll(":disabled").length&&y.push(":enabled",":disabled"),e.querySelectorAll("*,:x"),y.push(",.*:")})),(n.matchesSelector=Q.test(m=h.matches||h.webkitMatchesSelector||h.mozMatchesSelector||h.oMatchesSelector||h.msMatchesSelector))&&ue(function(e){n.disconnectedMatch=m.call(e,"*"),m.call(e,"[s!='']:x"),v.push("!=",W)}),y=y.length&&new RegExp(y.join("|")),v=v.length&&new RegExp(v.join("|")),t=Q.test(h.compareDocumentPosition),x=t||Q.test(h.contains)?function(e,t){var n=9===e.nodeType?e.documentElement:e,r=t&&t.parentNode;return e===r||!(!r||1!==r.nodeType||!(n.contains?n.contains(r):e.compareDocumentPosition&&16&e.compareDocumentPosition(r)))}:function(e,t){if(t)while(t=t.parentNode)if(t===e)return!0;return!1},D=t?function(e,t){if(e===t)return f=!0,0;var r=!e.compareDocumentPosition-!t.compareDocumentPosition;return r||(1&(r=(e.ownerDocument||e)===(t.ownerDocument||t)?e.compareDocumentPosition(t):1)||!n.sortDetached&&t.compareDocumentPosition(e)===r?e===d||e.ownerDocument===w&&x(w,e)?-1:t===d||t.ownerDocument===w&&x(w,t)?1:c?O(c,e)-O(c,t):0:4&r?-1:1)}:function(e,t){if(e===t)return f=!0,0;var n,r=0,i=e.parentNode,o=t.parentNode,a=[e],s=[t];if(!i||!o)return e===d?-1:t===d?1:i?-1:o?1:c?O(c,e)-O(c,t):0;if(i===o)return ce(e,t);n=e;while(n=n.parentNode)a.unshift(n);n=t;while(n=n.parentNode)s.unshift(n);while(a[r]===s[r])r++;return r?ce(a[r],s[r]):a[r]===w?-1:s[r]===w?1:0},d):d},oe.matches=function(e,t){return oe(e,null,null,t)},oe.matchesSelector=function(e,t){if((e.ownerDocument||e)!==d&&p(e),t=t.replace(z,"='$1']"),n.matchesSelector&&g&&!S[t+" "]&&(!v||!v.test(t))&&(!y||!y.test(t)))try{var r=m.call(e,t);if(r||n.disconnectedMatch||e.document&&11!==e.document.nodeType)return r}catch(e){}return oe(t,d,null,[e]).length>0},oe.contains=function(e,t){return(e.ownerDocument||e)!==d&&p(e),x(e,t)},oe.attr=function(e,t){(e.ownerDocument||e)!==d&&p(e);var i=r.attrHandle[t.toLowerCase()],o=i&&N.call(r.attrHandle,t.toLowerCase())?i(e,t,!g):void 0;return void 0!==o?o:n.attributes||!g?e.getAttribute(t):(o=e.getAttributeNode(t))&&o.specified?o.value:null},oe.escape=function(e){return(e+"").replace(te,ne)},oe.error=function(e){throw new Error("Syntax error, unrecognized expression: "+e)},oe.uniqueSort=function(e){var t,r=[],i=0,o=0;if(f=!n.detectDuplicates,c=!n.sortStable&&e.slice(0),e.sort(D),f){while(t=e[o++])t===e[o]&&(i=r.push(o));while(i--)e.splice(r[i],1)}return c=null,e},i=oe.getText=function(e){var t,n="",r=0,o=e.nodeType;if(o){if(1===o||9===o||11===o){if("string"==typeof e.textContent)return e.textContent;for(e=e.firstChild;e;e=e.nextSibling)n+=i(e)}else if(3===o||4===o)return e.nodeValue}else while(t=e[r++])n+=i(t);return n},(r=oe.selectors={cacheLength:50,createPseudo:se,match:V,attrHandle:{},find:{},relative:{">":{dir:"parentNode",first:!0}," ":{dir:"parentNode"},"+":{dir:"previousSibling",first:!0},"~":{dir:"previousSibling"}},preFilter:{ATTR:function(e){return e[1]=e[1].replace(Z,ee),e[3]=(e[3]||e[4]||e[5]||"").replace(Z,ee),"~="===e[2]&&(e[3]=" "+e[3]+" "),e.slice(0,4)},CHILD:function(e){return e[1]=e[1].toLowerCase(),"nth"===e[1].slice(0,3)?(e[3]||oe.error(e[0]),e[4]=+(e[4]?e[5]+(e[6]||1):2*("even"===e[3]||"odd"===e[3])),e[5]=+(e[7]+e[8]||"odd"===e[3])):e[3]&&oe.error(e[0]),e},PSEUDO:function(e){var t,n=!e[6]&&e[2];return V.CHILD.test(e[0])?null:(e[3]?e[2]=e[4]||e[5]||"":n&&X.test(n)&&(t=a(n,!0))&&(t=n.indexOf(")",n.length-t)-n.length)&&(e[0]=e[0].slice(0,t),e[2]=n.slice(0,t)),e.slice(0,3))}},filter:{TAG:function(e){var t=e.replace(Z,ee).toLowerCase();return"*"===e?function(){return!0}:function(e){return e.nodeName&&e.nodeName.toLowerCase()===t}},CLASS:function(e){var t=E[e+" "];return t||(t=new RegExp("(^|"+M+")"+e+"("+M+"|$)"))&&E(e,function(e){return t.test("string"==typeof e.className&&e.className||"undefined"!=typeof e.getAttribute&&e.getAttribute("class")||"")})},ATTR:function(e,t,n){return function(r){var i=oe.attr(r,e);return null==i?"!="===t:!t||(i+="","="===t?i===n:"!="===t?i!==n:"^="===t?n&&0===i.indexOf(n):"*="===t?n&&i.indexOf(n)>-1:"$="===t?n&&i.slice(-n.length)===n:"~="===t?(" "+i.replace($," ")+" ").indexOf(n)>-1:"|="===t&&(i===n||i.slice(0,n.length+1)===n+"-"))}},CHILD:function(e,t,n,r,i){var o="nth"!==e.slice(0,3),a="last"!==e.slice(-4),s="of-type"===t;return 1===r&&0===i?function(e){return!!e.parentNode}:function(t,n,u){var l,c,f,p,d,h,g=o!==a?"nextSibling":"previousSibling",y=t.parentNode,v=s&&t.nodeName.toLowerCase(),m=!u&&!s,x=!1;if(y){if(o){while(g){p=t;while(p=p[g])if(s?p.nodeName.toLowerCase()===v:1===p.nodeType)return!1;h=g="only"===e&&!h&&"nextSibling"}return!0}if(h=[a?y.firstChild:y.lastChild],a&&m){x=(d=(l=(c=(f=(p=y)[b]||(p[b]={}))[p.uniqueID]||(f[p.uniqueID]={}))[e]||[])[0]===T&&l[1])&&l[2],p=d&&y.childNodes[d];while(p=++d&&p&&p[g]||(x=d=0)||h.pop())if(1===p.nodeType&&++x&&p===t){c[e]=[T,d,x];break}}else if(m&&(x=d=(l=(c=(f=(p=t)[b]||(p[b]={}))[p.uniqueID]||(f[p.uniqueID]={}))[e]||[])[0]===T&&l[1]),!1===x)while(p=++d&&p&&p[g]||(x=d=0)||h.pop())if((s?p.nodeName.toLowerCase()===v:1===p.nodeType)&&++x&&(m&&((c=(f=p[b]||(p[b]={}))[p.uniqueID]||(f[p.uniqueID]={}))[e]=[T,x]),p===t))break;return(x-=i)===r||x%r==0&&x/r>=0}}},PSEUDO:function(e,t){var n,i=r.pseudos[e]||r.setFilters[e.toLowerCase()]||oe.error("unsupported pseudo: "+e);return i[b]?i(t):i.length>1?(n=[e,e,"",t],r.setFilters.hasOwnProperty(e.toLowerCase())?se(function(e,n){var r,o=i(e,t),a=o.length;while(a--)e[r=O(e,o[a])]=!(n[r]=o[a])}):function(e){return i(e,0,n)}):i}},pseudos:{not:se(function(e){var t=[],n=[],r=s(e.replace(B,"$1"));return r[b]?se(function(e,t,n,i){var o,a=r(e,null,i,[]),s=e.length;while(s--)(o=a[s])&&(e[s]=!(t[s]=o))}):function(e,i,o){return t[0]=e,r(t,null,o,n),t[0]=null,!n.pop()}}),has:se(function(e){return function(t){return oe(e,t).length>0}}),contains:se(function(e){return e=e.replace(Z,ee),function(t){return(t.textContent||t.innerText||i(t)).indexOf(e)>-1}}),lang:se(function(e){return U.test(e||"")||oe.error("unsupported lang: "+e),e=e.replace(Z,ee).toLowerCase(),function(t){var n;do{if(n=g?t.lang:t.getAttribute("xml:lang")||t.getAttribute("lang"))return(n=n.toLowerCase())===e||0===n.indexOf(e+"-")}while((t=t.parentNode)&&1===t.nodeType);return!1}}),target:function(t){var n=e.location&&e.location.hash;return n&&n.slice(1)===t.id},root:function(e){return e===h},focus:function(e){return e===d.activeElement&&(!d.hasFocus||d.hasFocus())&&!!(e.type||e.href||~e.tabIndex)},enabled:de(!1),disabled:de(!0),checked:function(e){var t=e.nodeName.toLowerCase();return"input"===t&&!!e.checked||"option"===t&&!!e.selected},selected:function(e){return e.parentNode&&e.parentNode.selectedIndex,!0===e.selected},empty:function(e){for(e=e.firstChild;e;e=e.nextSibling)if(e.nodeType<6)return!1;return!0},parent:function(e){return!r.pseudos.empty(e)},header:function(e){return Y.test(e.nodeName)},input:function(e){return G.test(e.nodeName)},button:function(e){var t=e.nodeName.toLowerCase();return"input"===t&&"button"===e.type||"button"===t},text:function(e){var t;return"input"===e.nodeName.toLowerCase()&&"text"===e.type&&(null==(t=e.getAttribute("type"))||"text"===t.toLowerCase())},first:he(function(){return[0]}),last:he(function(e,t){return[t-1]}),eq:he(function(e,t,n){return[n<0?n+t:n]}),even:he(function(e,t){for(var n=0;n<t;n+=2)e.push(n);return e}),odd:he(function(e,t){for(var n=1;n<t;n+=2)e.push(n);return e}),lt:he(function(e,t,n){for(var r=n<0?n+t:n;--r>=0;)e.push(r);return e}),gt:he(function(e,t,n){for(var r=n<0?n+t:n;++r<t;)e.push(r);return e})}}).pseudos.nth=r.pseudos.eq;for(t in{radio:!0,checkbox:!0,file:!0,password:!0,image:!0})r.pseudos[t]=fe(t);for(t in{submit:!0,reset:!0})r.pseudos[t]=pe(t);function ye(){}ye.prototype=r.filters=r.pseudos,r.setFilters=new ye,a=oe.tokenize=function(e,t){var n,i,o,a,s,u,l,c=k[e+" "];if(c)return t?0:c.slice(0);s=e,u=[],l=r.preFilter;while(s){n&&!(i=F.exec(s))||(i&&(s=s.slice(i[0].length)||s),u.push(o=[])),n=!1,(i=_.exec(s))&&(n=i.shift(),o.push({value:n,type:i[0].replace(B," ")}),s=s.slice(n.length));for(a in r.filter)!(i=V[a].exec(s))||l[a]&&!(i=l[a](i))||(n=i.shift(),o.push({value:n,type:a,matches:i}),s=s.slice(n.length));if(!n)break}return t?s.length:s?oe.error(e):k(e,u).slice(0)};function ve(e){for(var t=0,n=e.length,r="";t<n;t++)r+=e[t].value;return r}function me(e,t,n){var r=t.dir,i=t.next,o=i||r,a=n&&"parentNode"===o,s=C++;return t.first?function(t,n,i){while(t=t[r])if(1===t.nodeType||a)return e(t,n,i);return!1}:function(t,n,u){var l,c,f,p=[T,s];if(u){while(t=t[r])if((1===t.nodeType||a)&&e(t,n,u))return!0}else while(t=t[r])if(1===t.nodeType||a)if(f=t[b]||(t[b]={}),c=f[t.uniqueID]||(f[t.uniqueID]={}),i&&i===t.nodeName.toLowerCase())t=t[r]||t;else{if((l=c[o])&&l[0]===T&&l[1]===s)return p[2]=l[2];if(c[o]=p,p[2]=e(t,n,u))return!0}return!1}}function xe(e){return e.length>1?function(t,n,r){var i=e.length;while(i--)if(!e[i](t,n,r))return!1;return!0}:e[0]}function be(e,t,n){for(var r=0,i=t.length;r<i;r++)oe(e,t[r],n);return n}function we(e,t,n,r,i){for(var o,a=[],s=0,u=e.length,l=null!=t;s<u;s++)(o=e[s])&&(n&&!n(o,r,i)||(a.push(o),l&&t.push(s)));return a}function Te(e,t,n,r,i,o){return r&&!r[b]&&(r=Te(r)),i&&!i[b]&&(i=Te(i,o)),se(function(o,a,s,u){var l,c,f,p=[],d=[],h=a.length,g=o||be(t||"*",s.nodeType?[s]:s,[]),y=!e||!o&&t?g:we(g,p,e,s,u),v=n?i||(o?e:h||r)?[]:a:y;if(n&&n(y,v,s,u),r){l=we(v,d),r(l,[],s,u),c=l.length;while(c--)(f=l[c])&&(v[d[c]]=!(y[d[c]]=f))}if(o){if(i||e){if(i){l=[],c=v.length;while(c--)(f=v[c])&&l.push(y[c]=f);i(null,v=[],l,u)}c=v.length;while(c--)(f=v[c])&&(l=i?O(o,f):p[c])>-1&&(o[l]=!(a[l]=f))}}else v=we(v===a?v.splice(h,v.length):v),i?i(null,a,v,u):L.apply(a,v)})}function Ce(e){for(var t,n,i,o=e.length,a=r.relative[e[0].type],s=a||r.relative[" "],u=a?1:0,c=me(function(e){return e===t},s,!0),f=me(function(e){return O(t,e)>-1},s,!0),p=[function(e,n,r){var i=!a&&(r||n!==l)||((t=n).nodeType?c(e,n,r):f(e,n,r));return t=null,i}];u<o;u++)if(n=r.relative[e[u].type])p=[me(xe(p),n)];else{if((n=r.filter[e[u].type].apply(null,e[u].matches))[b]){for(i=++u;i<o;i++)if(r.relative[e[i].type])break;return Te(u>1&&xe(p),u>1&&ve(e.slice(0,u-1).concat({value:" "===e[u-2].type?"*":""})).replace(B,"$1"),n,u<i&&Ce(e.slice(u,i)),i<o&&Ce(e=e.slice(i)),i<o&&ve(e))}p.push(n)}return xe(p)}function Ee(e,t){var n=t.length>0,i=e.length>0,o=function(o,a,s,u,c){var f,h,y,v=0,m="0",x=o&&[],b=[],w=l,C=o||i&&r.find.TAG("*",c),E=T+=null==w?1:Math.random()||.1,k=C.length;for(c&&(l=a===d||a||c);m!==k&&null!=(f=C[m]);m++){if(i&&f){h=0,a||f.ownerDocument===d||(p(f),s=!g);while(y=e[h++])if(y(f,a||d,s)){u.push(f);break}c&&(T=E)}n&&((f=!y&&f)&&v--,o&&x.push(f))}if(v+=m,n&&m!==v){h=0;while(y=t[h++])y(x,b,a,s);if(o){if(v>0)while(m--)x[m]||b[m]||(b[m]=j.call(u));b=we(b)}L.apply(u,b),c&&!o&&b.length>0&&v+t.length>1&&oe.uniqueSort(u)}return c&&(T=E,l=w),x};return n?se(o):o}return s=oe.compile=function(e,t){var n,r=[],i=[],o=S[e+" "];if(!o){t||(t=a(e)),n=t.length;while(n--)(o=Ce(t[n]))[b]?r.push(o):i.push(o);(o=S(e,Ee(i,r))).selector=e}return o},u=oe.select=function(e,t,n,i){var o,u,l,c,f,p="function"==typeof e&&e,d=!i&&a(e=p.selector||e);if(n=n||[],1===d.length){if((u=d[0]=d[0].slice(0)).length>2&&"ID"===(l=u[0]).type&&9===t.nodeType&&g&&r.relative[u[1].type]){if(!(t=(r.find.ID(l.matches[0].replace(Z,ee),t)||[])[0]))return n;p&&(t=t.parentNode),e=e.slice(u.shift().value.length)}o=V.needsContext.test(e)?0:u.length;while(o--){if(l=u[o],r.relative[c=l.type])break;if((f=r.find[c])&&(i=f(l.matches[0].replace(Z,ee),K.test(u[0].type)&&ge(t.parentNode)||t))){if(u.splice(o,1),!(e=i.length&&ve(u)))return L.apply(n,i),n;break}}}return(p||s(e,d))(i,t,!g,n,!t||K.test(e)&&ge(t.parentNode)||t),n},n.sortStable=b.split("").sort(D).join("")===b,n.detectDuplicates=!!f,p(),n.sortDetached=ue(function(e){return 1&e.compareDocumentPosition(d.createElement("fieldset"))}),ue(function(e){return e.innerHTML="<a href='#'></a>","#"===e.firstChild.getAttribute("href")})||le("type|href|height|width",function(e,t,n){if(!n)return e.getAttribute(t,"type"===t.toLowerCase()?1:2)}),n.attributes&&ue(function(e){return e.innerHTML="<input/>",e.firstChild.setAttribute("value",""),""===e.firstChild.getAttribute("value")})||le("value",function(e,t,n){if(!n&&"input"===e.nodeName.toLowerCase())return e.defaultValue}),ue(function(e){return null==e.getAttribute("disabled")})||le(P,function(e,t,n){var r;if(!n)return!0===e[t]?t.toLowerCase():(r=e.getAttributeNode(t))&&r.specified?r.value:null}),oe}(e);w.find=E,w.expr=E.selectors,w.expr[":"]=w.expr.pseudos,w.uniqueSort=w.unique=E.uniqueSort,w.text=E.getText,w.isXMLDoc=E.isXML,w.contains=E.contains,w.escapeSelector=E.escape;var k=function(e,t,n){var r=[],i=void 0!==n;while((e=e[t])&&9!==e.nodeType)if(1===e.nodeType){if(i&&w(e).is(n))break;r.push(e)}return r},S=function(e,t){for(var n=[];e;e=e.nextSibling)1===e.nodeType&&e!==t&&n.push(e);return n},D=w.expr.match.needsContext;function N(e,t){return e.nodeName&&e.nodeName.toLowerCase()===t.toLowerCase()}var A=/^<([a-z][^\/\0>:\x20\t\r\n\f]*)[\x20\t\r\n\f]*\/?>(?:<\/\1>|)$/i;function j(e,t,n){return g(t)?w.grep(e,function(e,r){return!!t.call(e,r,e)!==n}):t.nodeType?w.grep(e,function(e){return e===t!==n}):"string"!=typeof t?w.grep(e,function(e){return u.call(t,e)>-1!==n}):w.filter(t,e,n)}w.filter=function(e,t,n){var r=t[0];return n&&(e=":not("+e+")"),1===t.length&&1===r.nodeType?w.find.matchesSelector(r,e)?[r]:[]:w.find.matches(e,w.grep(t,function(e){return 1===e.nodeType}))},w.fn.extend({find:function(e){var t,n,r=this.length,i=this;if("string"!=typeof e)return this.pushStack(w(e).filter(function(){for(t=0;t<r;t++)if(w.contains(i[t],this))return!0}));for(n=this.pushStack([]),t=0;t<r;t++)w.find(e,i[t],n);return r>1?w.uniqueSort(n):n},filter:function(e){return this.pushStack(j(this,e||[],!1))},not:function(e){return this.pushStack(j(this,e||[],!0))},is:function(e){return!!j(this,"string"==typeof e&&D.test(e)?w(e):e||[],!1).length}});var q,L=/^(?:\s*(<[\w\W]+>)[^>]*|#([\w-]+))$/;(w.fn.init=function(e,t,n){var i,o;if(!e)return this;if(n=n||q,"string"==typeof e){if(!(i="<"===e[0]&&">"===e[e.length-1]&&e.length>=3?[null,e,null]:L.exec(e))||!i[1]&&t)return!t||t.jquery?(t||n).find(e):this.constructor(t).find(e);if(i[1]){if(t=t instanceof w?t[0]:t,w.merge(this,w.parseHTML(i[1],t&&t.nodeType?t.ownerDocument||t:r,!0)),A.test(i[1])&&w.isPlainObject(t))for(i in t)g(this[i])?this[i](t[i]):this.attr(i,t[i]);return this}return(o=r.getElementById(i[2]))&&(this[0]=o,this.length=1),this}return e.nodeType?(this[0]=e,this.length=1,this):g(e)?void 0!==n.ready?n.ready(e):e(w):w.makeArray(e,this)}).prototype=w.fn,q=w(r);var H=/^(?:parents|prev(?:Until|All))/,O={children:!0,contents:!0,next:!0,prev:!0};w.fn.extend({has:function(e){var t=w(e,this),n=t.length;return this.filter(function(){for(var e=0;e<n;e++)if(w.contains(this,t[e]))return!0})},closest:function(e,t){var n,r=0,i=this.length,o=[],a="string"!=typeof e&&w(e);if(!D.test(e))for(;r<i;r++)for(n=this[r];n&&n!==t;n=n.parentNode)if(n.nodeType<11&&(a?a.index(n)>-1:1===n.nodeType&&w.find.matchesSelector(n,e))){o.push(n);break}return this.pushStack(o.length>1?w.uniqueSort(o):o)},index:function(e){return e?"string"==typeof e?u.call(w(e),this[0]):u.call(this,e.jquery?e[0]:e):this[0]&&this[0].parentNode?this.first().prevAll().length:-1},add:function(e,t){return this.pushStack(w.uniqueSort(w.merge(this.get(),w(e,t))))},addBack:function(e){return this.add(null==e?this.prevObject:this.prevObject.filter(e))}});function P(e,t){while((e=e[t])&&1!==e.nodeType);return e}w.each({parent:function(e){var t=e.parentNode;return t&&11!==t.nodeType?t:null},parents:function(e){return k(e,"parentNode")},parentsUntil:function(e,t,n){return k(e,"parentNode",n)},next:function(e){return P(e,"nextSibling")},prev:function(e){return P(e,"previousSibling")},nextAll:function(e){return k(e,"nextSibling")},prevAll:function(e){return k(e,"previousSibling")},nextUntil:function(e,t,n){return k(e,"nextSibling",n)},prevUntil:function(e,t,n){return k(e,"previousSibling",n)},siblings:function(e){return S((e.parentNode||{}).firstChild,e)},children:function(e){return S(e.firstChild)},contents:function(e){return N(e,"iframe")?e.contentDocument:(N(e,"template")&&(e=e.content||e),w.merge([],e.childNodes))}},function(e,t){w.fn[e]=function(n,r){var i=w.map(this,t,n);return"Until"!==e.slice(-5)&&(r=n),r&&"string"==typeof r&&(i=w.filter(r,i)),this.length>1&&(O[e]||w.uniqueSort(i),H.test(e)&&i.reverse()),this.pushStack(i)}});var M=/[^\x20\t\r\n\f]+/g;function R(e){var t={};return w.each(e.match(M)||[],function(e,n){t[n]=!0}),t}w.Callbacks=function(e){e="string"==typeof e?R(e):w.extend({},e);var t,n,r,i,o=[],a=[],s=-1,u=function(){for(i=i||e.once,r=t=!0;a.length;s=-1){n=a.shift();while(++s<o.length)!1===o[s].apply(n[0],n[1])&&e.stopOnFalse&&(s=o.length,n=!1)}e.memory||(n=!1),t=!1,i&&(o=n?[]:"")},l={add:function(){return o&&(n&&!t&&(s=o.length-1,a.push(n)),function t(n){w.each(n,function(n,r){g(r)?e.unique&&l.has(r)||o.push(r):r&&r.length&&"string"!==x(r)&&t(r)})}(arguments),n&&!t&&u()),this},remove:function(){return w.each(arguments,function(e,t){var n;while((n=w.inArray(t,o,n))>-1)o.splice(n,1),n<=s&&s--}),this},has:function(e){return e?w.inArray(e,o)>-1:o.length>0},empty:function(){return o&&(o=[]),this},disable:function(){return i=a=[],o=n="",this},disabled:function(){return!o},lock:function(){return i=a=[],n||t||(o=n=""),this},locked:function(){return!!i},fireWith:function(e,n){return i||(n=[e,(n=n||[]).slice?n.slice():n],a.push(n),t||u()),this},fire:function(){return l.fireWith(this,arguments),this},fired:function(){return!!r}};return l};function I(e){return e}function W(e){throw e}function $(e,t,n,r){var i;try{e&&g(i=e.promise)?i.call(e).done(t).fail(n):e&&g(i=e.then)?i.call(e,t,n):t.apply(void 0,[e].slice(r))}catch(e){n.apply(void 0,[e])}}w.extend({Deferred:function(t){var n=[["notify","progress",w.Callbacks("memory"),w.Callbacks("memory"),2],["resolve","done",w.Callbacks("once memory"),w.Callbacks("once memory"),0,"resolved"],["reject","fail",w.Callbacks("once memory"),w.Callbacks("once memory"),1,"rejected"]],r="pending",i={state:function(){return r},always:function(){return o.done(arguments).fail(arguments),this},"catch":function(e){return i.then(null,e)},pipe:function(){var e=arguments;return w.Deferred(function(t){w.each(n,function(n,r){var i=g(e[r[4]])&&e[r[4]];o[r[1]](function(){var e=i&&i.apply(this,arguments);e&&g(e.promise)?e.promise().progress(t.notify).done(t.resolve).fail(t.reject):t[r[0]+"With"](this,i?[e]:arguments)})}),e=null}).promise()},then:function(t,r,i){var o=0;function a(t,n,r,i){return function(){var s=this,u=arguments,l=function(){var e,l;if(!(t<o)){if((e=r.apply(s,u))===n.promise())throw new TypeError("Thenable self-resolution");l=e&&("object"==typeof e||"function"==typeof e)&&e.then,g(l)?i?l.call(e,a(o,n,I,i),a(o,n,W,i)):(o++,l.call(e,a(o,n,I,i),a(o,n,W,i),a(o,n,I,n.notifyWith))):(r!==I&&(s=void 0,u=[e]),(i||n.resolveWith)(s,u))}},c=i?l:function(){try{l()}catch(e){w.Deferred.exceptionHook&&w.Deferred.exceptionHook(e,c.stackTrace),t+1>=o&&(r!==W&&(s=void 0,u=[e]),n.rejectWith(s,u))}};t?c():(w.Deferred.getStackHook&&(c.stackTrace=w.Deferred.getStackHook()),e.setTimeout(c))}}return w.Deferred(function(e){n[0][3].add(a(0,e,g(i)?i:I,e.notifyWith)),n[1][3].add(a(0,e,g(t)?t:I)),n[2][3].add(a(0,e,g(r)?r:W))}).promise()},promise:function(e){return null!=e?w.extend(e,i):i}},o={};return w.each(n,function(e,t){var a=t[2],s=t[5];i[t[1]]=a.add,s&&a.add(function(){r=s},n[3-e][2].disable,n[3-e][3].disable,n[0][2].lock,n[0][3].lock),a.add(t[3].fire),o[t[0]]=function(){return o[t[0]+"With"](this===o?void 0:this,arguments),this},o[t[0]+"With"]=a.fireWith}),i.promise(o),t&&t.call(o,o),o},when:function(e){var t=arguments.length,n=t,r=Array(n),i=o.call(arguments),a=w.Deferred(),s=function(e){return function(n){r[e]=this,i[e]=arguments.length>1?o.call(arguments):n,--t||a.resolveWith(r,i)}};if(t<=1&&($(e,a.done(s(n)).resolve,a.reject,!t),"pending"===a.state()||g(i[n]&&i[n].then)))return a.then();while(n--)$(i[n],s(n),a.reject);return a.promise()}});var B=/^(Eval|Internal|Range|Reference|Syntax|Type|URI)Error$/;w.Deferred.exceptionHook=function(t,n){e.console&&e.console.warn&&t&&B.test(t.name)&&e.console.warn("jQuery.Deferred exception: "+t.message,t.stack,n)},w.readyException=function(t){e.setTimeout(function(){throw t})};var F=w.Deferred();w.fn.ready=function(e){return F.then(e)["catch"](function(e){w.readyException(e)}),this},w.extend({isReady:!1,readyWait:1,ready:function(e){(!0===e?--w.readyWait:w.isReady)||(w.isReady=!0,!0!==e&&--w.readyWait>0||F.resolveWith(r,[w]))}}),w.ready.then=F.then;function _(){r.removeEventListener("DOMContentLoaded",_),e.removeEventListener("load",_),w.ready()}"complete"===r.readyState||"loading"!==r.readyState&&!r.documentElement.doScroll?e.setTimeout(w.ready):(r.addEventListener("DOMContentLoaded",_),e.addEventListener("load",_));var z=function(e,t,n,r,i,o,a){var s=0,u=e.length,l=null==n;if("object"===x(n)){i=!0;for(s in n)z(e,t,s,n[s],!0,o,a)}else if(void 0!==r&&(i=!0,g(r)||(a=!0),l&&(a?(t.call(e,r),t=null):(l=t,t=function(e,t,n){return l.call(w(e),n)})),t))for(;s<u;s++)t(e[s],n,a?r:r.call(e[s],s,t(e[s],n)));return i?e:l?t.call(e):u?t(e[0],n):o},X=/^-ms-/,U=/-([a-z])/g;function V(e,t){return t.toUpperCase()}function G(e){return e.replace(X,"ms-").replace(U,V)}var Y=function(e){return 1===e.nodeType||9===e.nodeType||!+e.nodeType};function Q(){this.expando=w.expando+Q.uid++}Q.uid=1,Q.prototype={cache:function(e){var t=e[this.expando];return t||(t={},Y(e)&&(e.nodeType?e[this.expando]=t:Object.defineProperty(e,this.expando,{value:t,configurable:!0}))),t},set:function(e,t,n){var r,i=this.cache(e);if("string"==typeof t)i[G(t)]=n;else for(r in t)i[G(r)]=t[r];return i},get:function(e,t){return void 0===t?this.cache(e):e[this.expando]&&e[this.expando][G(t)]},access:function(e,t,n){return void 0===t||t&&"string"==typeof t&&void 0===n?this.get(e,t):(this.set(e,t,n),void 0!==n?n:t)},remove:function(e,t){var n,r=e[this.expando];if(void 0!==r){if(void 0!==t){n=(t=Array.isArray(t)?t.map(G):(t=G(t))in r?[t]:t.match(M)||[]).length;while(n--)delete r[t[n]]}(void 0===t||w.isEmptyObject(r))&&(e.nodeType?e[this.expando]=void 0:delete e[this.expando])}},hasData:function(e){var t=e[this.expando];return void 0!==t&&!w.isEmptyObject(t)}};var J=new Q,K=new Q,Z=/^(?:\{[\w\W]*\}|\[[\w\W]*\])$/,ee=/[A-Z]/g;function te(e){return"true"===e||"false"!==e&&("null"===e?null:e===+e+""?+e:Z.test(e)?JSON.parse(e):e)}function ne(e,t,n){var r;if(void 0===n&&1===e.nodeType)if(r="data-"+t.replace(ee,"-{{ jquery }}").toLowerCase(),"string"==typeof(n=e.getAttribute(r))){try{n=te(n)}catch(e){}K.set(e,t,n)}else n=void 0;return n}w.extend({hasData:function(e){return K.hasData(e)||J.hasData(e)},data:function(e,t,n){return K.access(e,t,n)},removeData:function(e,t){K.remove(e,t)},_data:function(e,t,n){return J.access(e,t,n)},_removeData:function(e,t){J.remove(e,t)}}),w.fn.extend({data:function(e,t){var n,r,i,o=this[0],a=o&&o.attributes;if(void 0===e){if(this.length&&(i=K.get(o),1===o.nodeType&&!J.get(o,"hasDataAttrs"))){n=a.length;while(n--)a[n]&&0===(r=a[n].name).indexOf("data-")&&(r=G(r.slice(5)),ne(o,r,i[r]));J.set(o,"hasDataAttrs",!0)}return i}return"object"==typeof e?this.each(function(){K.set(this,e)}):z(this,function(t){var n;if(o&&void 0===t){if(void 0!==(n=K.get(o,e)))return n;if(void 0!==(n=ne(o,e)))return n}else this.each(function(){K.set(this,e,t)})},null,t,arguments.length>1,null,!0)},removeData:function(e){return this.each(function(){K.remove(this,e)})}}),w.extend({queue:function(e,t,n){var r;if(e)return t=(t||"fx")+"queue",r=J.get(e,t),n&&(!r||Array.isArray(n)?r=J.access(e,t,w.makeArray(n)):r.push(n)),r||[]},dequeue:function(e,t){t=t||"fx";var n=w.queue(e,t),r=n.length,i=n.shift(),o=w._queueHooks(e,t),a=function(){w.dequeue(e,t)};"inprogress"===i&&(i=n.shift(),r--),i&&("fx"===t&&n.unshift("inprogress"),delete o.stop,i.call(e,a,o)),!r&&o&&o.empty.fire()},_queueHooks:function(e,t){var n=t+"queueHooks";return J.get(e,n)||J.access(e,n,{empty:w.Callbacks("once memory").add(function(){J.remove(e,[t+"queue",n])})})}}),w.fn.extend({queue:function(e,t){var n=2;return"string"!=typeof e&&(t=e,e="fx",n--),arguments.length<n?w.queue(this[0],e):void 0===t?this:this.each(function(){var n=w.queue(this,e,t);w._queueHooks(this,e),"fx"===e&&"inprogress"!==n[0]&&w.dequeue(this,e)})},dequeue:function(e){return this.each(function(){w.dequeue(this,e)})},clearQueue:function(e){return this.queue(e||"fx",[])},promise:function(e,t){var n,r=1,i=w.Deferred(),o=this,a=this.length,s=function(){--r||i.resolveWith(o,[o])};"string"!=typeof e&&(t=e,e=void 0),e=e||"fx";while(a--)(n=J.get(o[a],e+"queueHooks"))&&n.empty&&(r++,n.empty.add(s));return s(),i.promise(t)}});var re=/[+-]?(?:\d*\.|)\d+(?:[eE][+-]?\d+|)/.source,ie=new RegExp("^(?:([+-])=|)("+re+")([a-z%]*)$","i"),oe=["Top","Right","Bottom","Left"],ae=function(e,t){return"none"===(e=t||e).style.display||""===e.style.display&&w.contains(e.ownerDocument,e)&&"none"===w.css(e,"display")},se=function(e,t,n,r){var i,o,a={};for(o in t)a[o]=e.style[o],e.style[o]=t[o];i=n.apply(e,r||[]);for(o in t)e.style[o]=a[o];return i};function ue(e,t,n,r){var i,o,a=20,s=r?function(){return r.cur()}:function(){return w.css(e,t,"")},u=s(),l=n&&n[3]||(w.cssNumber[t]?"":"px"),c=(w.cssNumber[t]||"px"!==l&&+u)&&ie.exec(w.css(e,t));if(c&&c[3]!==l){u/=2,l=l||c[3],c=+u||1;while(a--)w.style(e,t,c+l),(1-o)*(1-(o=s()/u||.5))<=0&&(a=0),c/=o;c*=2,w.style(e,t,c+l),n=n||[]}return n&&(c=+c||+u||0,i=n[1]?c+(n[1]+1)*n[2]:+n[2],r&&(r.unit=l,r.start=c,r.end=i)),i}var le={};function ce(e){var t,n=e.ownerDocument,r=e.nodeName,i=le[r];return i||(t=n.body.appendChild(n.createElement(r)),i=w.css(t,"display"),t.parentNode.removeChild(t),"none"===i&&(i="block"),le[r]=i,i)}function fe(e,t){for(var n,r,i=[],o=0,a=e.length;o<a;o++)(r=e[o]).style&&(n=r.style.display,t?("none"===n&&(i[o]=J.get(r,"display")||null,i[o]||(r.style.display="")),""===r.style.display&&ae(r)&&(i[o]=ce(r))):"none"!==n&&(i[o]="none",J.set(r,"display",n)));for(o=0;o<a;o++)null!=i[o]&&(e[o].style.display=i[o]);return e}w.fn.extend({show:function(){return fe(this,!0)},hide:function(){return fe(this)},toggle:function(e){return"boolean"==typeof e?e?this.show():this.hide():this.each(function(){ae(this)?w(this).show():w(this).hide()})}});var pe=/^(?:checkbox|radio)$/i,de=/<([a-z][^\/\0>\x20\t\r\n\f]+)/i,he=/^$|^module$|\/(?:java|ecma)script/i,ge={option:[1,"<select multiple='multiple'>","</select>"],thead:[1,"<table>","</table>"],col:[2,"<table><colgroup>","</colgroup></table>"],tr:[2,"<table><tbody>","</tbody></table>"],td:[3,"<table><tbody><tr>","</tr></tbody></table>"],_default:[0,"",""]};ge.optgroup=ge.option,ge.tbody=ge.tfoot=ge.colgroup=ge.caption=ge.thead,ge.th=ge.td;function ye(e,t){var n;return n="undefined"!=typeof e.getElementsByTagName?e.getElementsByTagName(t||"*"):"undefined"!=typeof e.querySelectorAll?e.querySelectorAll(t||"*"):[],void 0===t||t&&N(e,t)?w.merge([e],n):n}function ve(e,t){for(var n=0,r=e.length;n<r;n++)J.set(e[n],"globalEval",!t||J.get(t[n],"globalEval"))}var me=/<|&#?\w+;/;function xe(e,t,n,r,i){for(var o,a,s,u,l,c,f=t.createDocumentFragment(),p=[],d=0,h=e.length;d<h;d++)if((o=e[d])||0===o)if("object"===x(o))w.merge(p,o.nodeType?[o]:o);else if(me.test(o)){a=a||f.appendChild(t.createElement("div")),s=(de.exec(o)||["",""])[1].toLowerCase(),u=ge[s]||ge._default,a.innerHTML=u[1]+w.htmlPrefilter(o)+u[2],c=u[0];while(c--)a=a.lastChild;w.merge(p,a.childNodes),(a=f.firstChild).textContent=""}else p.push(t.createTextNode(o));f.textContent="",d=0;while(o=p[d++])if(r&&w.inArray(o,r)>-1)i&&i.push(o);else if(l=w.contains(o.ownerDocument,o),a=ye(f.appendChild(o),"script"),l&&ve(a),n){c=0;while(o=a[c++])he.test(o.type||"")&&n.push(o)}return f}!function(){var e=r.createDocumentFragment().appendChild(r.createElement("div")),t=r.createElement("input");t.setAttribute("type","radio"),t.setAttribute("checked","checked"),t.setAttribute("name","t"),e.appendChild(t),h.checkClone=e.cloneNode(!0).cloneNode(!0).lastChild.checked,e.innerHTML="<textarea>x</textarea>",h.noCloneChecked=!!e.cloneNode(!0).lastChild.defaultValue}();var be=r.documentElement,we=/^key/,Te=/^(?:mouse|pointer|contextmenu|drag|drop)|click/,Ce=/^([^.]*)(?:\.(.+)|)/;function Ee(){return!0}function ke(){return!1}function Se(){try{return r.activeElement}catch(e){}}function De(e,t,n,r,i,o){var a,s;if("object"==typeof t){"string"!=typeof n&&(r=r||n,n=void 0);for(s in t)De(e,s,n,r,t[s],o);return e}if(null==r&&null==i?(i=n,r=n=void 0):null==i&&("string"==typeof n?(i=r,r=void 0):(i=r,r=n,n=void 0)),!1===i)i=ke;else if(!i)return e;return 1===o&&(a=i,(i=function(e){return w().off(e),a.apply(this,arguments)}).guid=a.guid||(a.guid=w.guid++)),e.each(function(){w.event.add(this,t,i,r,n)})}w.event={global:{},add:function(e,t,n,r,i){var o,a,s,u,l,c,f,p,d,h,g,y=J.get(e);if(y){n.handler&&(n=(o=n).handler,i=o.selector),i&&w.find.matchesSelector(be,i),n.guid||(n.guid=w.guid++),(u=y.events)||(u=y.events={}),(a=y.handle)||(a=y.handle=function(t){return"undefined"!=typeof w&&w.event.triggered!==t.type?w.event.dispatch.apply(e,arguments):void 0}),l=(t=(t||"").match(M)||[""]).length;while(l--)d=g=(s=Ce.exec(t[l])||[])[1],h=(s[2]||"").split(".").sort(),d&&(f=w.event.special[d]||{},d=(i?f.delegateType:f.bindType)||d,f=w.event.special[d]||{},c=w.extend({type:d,origType:g,data:r,handler:n,guid:n.guid,selector:i,needsContext:i&&w.expr.match.needsContext.test(i),namespace:h.join(".")},o),(p=u[d])||((p=u[d]=[]).delegateCount=0,f.setup&&!1!==f.setup.call(e,r,h,a)||e.addEventListener&&e.addEventListener(d,a)),f.add&&(f.add.call(e,c),c.handler.guid||(c.handler.guid=n.guid)),i?p.splice(p.delegateCount++,0,c):p.push(c),w.event.global[d]=!0)}},remove:function(e,t,n,r,i){var o,a,s,u,l,c,f,p,d,h,g,y=J.hasData(e)&&J.get(e);if(y&&(u=y.events)){l=(t=(t||"").match(M)||[""]).length;while(l--)if(s=Ce.exec(t[l])||[],d=g=s[1],h=(s[2]||"").split(".").sort(),d){f=w.event.special[d]||{},p=u[d=(r?f.delegateType:f.bindType)||d]||[],s=s[2]&&new RegExp("(^|\\.)"+h.join("\\.(?:.*\\.|)")+"(\\.|$)"),a=o=p.length;while(o--)c=p[o],!i&&g!==c.origType||n&&n.guid!==c.guid||s&&!s.test(c.namespace)||r&&r!==c.selector&&("**"!==r||!c.selector)||(p.splice(o,1),c.selector&&p.delegateCount--,f.remove&&f.remove.call(e,c));a&&!p.length&&(f.teardown&&!1!==f.teardown.call(e,h,y.handle)||w.removeEvent(e,d,y.handle),delete u[d])}else for(d in u)w.event.remove(e,d+t[l],n,r,!0);w.isEmptyObject(u)&&J.remove(e,"handle events")}},dispatch:function(e){var t=w.event.fix(e),n,r,i,o,a,s,u=new Array(arguments.length),l=(J.get(this,"events")||{})[t.type]||[],c=w.event.special[t.type]||{};for(u[0]=t,n=1;n<arguments.length;n++)u[n]=arguments[n];if(t.delegateTarget=this,!c.preDispatch||!1!==c.preDispatch.call(this,t)){s=w.event.handlers.call(this,t,l),n=0;while((o=s[n++])&&!t.isPropagationStopped()){t.currentTarget=o.elem,r=0;while((a=o.handlers[r++])&&!t.isImmediatePropagationStopped())t.rnamespace&&!t.rnamespace.test(a.namespace)||(t.handleObj=a,t.data=a.data,void 0!==(i=((w.event.special[a.origType]||{}).handle||a.handler).apply(o.elem,u))&&!1===(t.result=i)&&(t.preventDefault(),t.stopPropagation()))}return c.postDispatch&&c.postDispatch.call(this,t),t.result}},handlers:function(e,t){var n,r,i,o,a,s=[],u=t.delegateCount,l=e.target;if(u&&l.nodeType&&!("click"===e.type&&e.button>=1))for(;l!==this;l=l.parentNode||this)if(1===l.nodeType&&("click"!==e.type||!0!==l.disabled)){for(o=[],a={},n=0;n<u;n++)void 0===a[i=(r=t[n]).selector+" "]&&(a[i]=r.needsContext?w(i,this).index(l)>-1:w.find(i,this,null,[l]).length),a[i]&&o.push(r);o.length&&s.push({elem:l,handlers:o})}return l=this,u<t.length&&s.push({elem:l,handlers:t.slice(u)}),s},addProp:function(e,t){Object.defineProperty(w.Event.prototype,e,{enumerable:!0,configurable:!0,get:g(t)?function(){if(this.originalEvent)return t(this.originalEvent)}:function(){if(this.originalEvent)return this.originalEvent[e]},set:function(t){Object.defineProperty(this,e,{enumerable:!0,configurable:!0,writable:!0,value:t})}})},fix:function(e){return e[w.expando]?e:new w.Event(e)},special:{load:{noBubble:!0},focus:{trigger:function(){if(this!==Se()&&this.focus)return this.focus(),!1},delegateType:"focusin"},blur:{trigger:function(){if(this===Se()&&this.blur)return this.blur(),!1},delegateType:"focusout"},click:{trigger:function(){if("checkbox"===this.type&&this.click&&N(this,"input"))return this.click(),!1},_default:function(e){return N(e.target,"a")}},beforeunload:{postDispatch:function(e){void 0!==e.result&&e.originalEvent&&(e.originalEvent.returnValue=e.result)}}}},w.removeEvent=function(e,t,n){e.removeEventListener&&e.removeEventListener(t,n)},w.Event=function(e,t){if(!(this instanceof w.Event))return new w.Event(e,t);e&&e.type?(this.originalEvent=e,this.type=e.type,this.isDefaultPrevented=e.defaultPrevented||void 0===e.defaultPrevented&&!1===e.returnValue?Ee:ke,this.target=e.target&&3===e.target.nodeType?e.target.parentNode:e.target,this.currentTarget=e.currentTarget,this.relatedTarget=e.relatedTarget):this.type=e,t&&w.extend(this,t),this.timeStamp=e&&e.timeStamp||Date.now(),this[w.expando]=!0},w.Event.prototype={constructor:w.Event,isDefaultPrevented:ke,isPropagationStopped:ke,isImmediatePropagationStopped:ke,isSimulated:!1,preventDefault:function(){var e=this.originalEvent;this.isDefaultPrevented=Ee,e&&!this.isSimulated&&e.preventDefault()},stopPropagation:function(){var e=this.originalEvent;this.isPropagationStopped=Ee,e&&!this.isSimulated&&e.stopPropagation()},stopImmediatePropagation:function(){var e=this.originalEvent;this.isImmediatePropagationStopped=Ee,e&&!this.isSimulated&&e.stopImmediatePropagation(),this.stopPropagation()}},w.each({altKey:!0,bubbles:!0,cancelable:!0,changedTouches:!0,ctrlKey:!0,detail:!0,eventPhase:!0,metaKey:!0,pageX:!0,pageY:!0,shiftKey:!0,view:!0,"char":!0,charCode:!0,key:!0,keyCode:!0,button:!0,buttons:!0,clientX:!0,clientY:!0,offsetX:!0,offsetY:!0,pointerId:!0,pointerType:!0,screenX:!0,screenY:!0,targetTouches:!0,toElement:!0,touches:!0,which:function(e){var t=e.button;return null==e.which&&we.test(e.type)?null!=e.charCode?e.charCode:e.keyCode:!e.which&&void 0!==t&&Te.test(e.type)?1&t?1:2&t?3:4&t?2:0:e.which}},w.event.addProp),w.each({mouseenter:"mouseover",mouseleave:"mouseout",pointerenter:"pointerover",pointerleave:"pointerout"},function(e,t){w.event.special[e]={delegateType:t,bindType:t,handle:function(e){var n,r=this,i=e.relatedTarget,o=e.handleObj;return i&&(i===r||w.contains(r,i))||(e.type=o.origType,n=o.handler.apply(this,arguments),e.type=t),n}}}),w.fn.extend({on:function(e,t,n,r){return De(this,e,t,n,r)},one:function(e,t,n,r){return De(this,e,t,n,r,1)},off:function(e,t,n){var r,i;if(e&&e.preventDefault&&e.handleObj)return r=e.handleObj,w(e.delegateTarget).off(r.namespace?r.origType+"."+r.namespace:r.origType,r.selector,r.handler),this;if("object"==typeof e){for(i in e)this.off(i,t,e[i]);return this}return!1!==t&&"function"!=typeof t||(n=t,t=void 0),!1===n&&(n=ke),this.each(function(){w.event.remove(this,e,n,t)})}});var Ne=/<(?!area|br|col|embed|hr|img|input|link|meta|param)(([a-z][^\/\0>\x20\t\r\n\f]*)[^>]*)\/>/gi,Ae=/<script|<style|<link/i,je=/checked\s*(?:[^=]|=\s*.checked.)/i,qe=/^\s*<!(?:\[CDATA\[|--)|(?:\]\]|--)>\s*$/g;function Le(e,t){return N(e,"table")&&N(11!==t.nodeType?t:t.firstChild,"tr")?w(e).children("tbody")[0]||e:e}function He(e){return e.type=(null!==e.getAttribute("type"))+"/"+e.type,e}function Oe(e){return"true/"===(e.type||"").slice(0,5)?e.type=e.type.slice(5):e.removeAttribute("type"),e}function Pe(e,t){var n,r,i,o,a,s,u,l;if(1===t.nodeType){if(J.hasData(e)&&(o=J.access(e),a=J.set(t,o),l=o.events)){delete a.handle,a.events={};for(i in l)for(n=0,r=l[i].length;n<r;n++)w.event.add(t,i,l[i][n])}K.hasData(e)&&(s=K.access(e),u=w.extend({},s),K.set(t,u))}}function Me(e,t){var n=t.nodeName.toLowerCase();"input"===n&&pe.test(e.type)?t.checked=e.checked:"input"!==n&&"textarea"!==n||(t.defaultValue=e.defaultValue)}function Re(e,t,n,r){t=a.apply([],t);var i,o,s,u,l,c,f=0,p=e.length,d=p-1,y=t[0],v=g(y);if(v||p>1&&"string"==typeof y&&!h.checkClone&&je.test(y))return e.each(function(i){var o=e.eq(i);v&&(t[0]=y.call(this,i,o.html())),Re(o,t,n,r)});if(p&&(i=xe(t,e[0].ownerDocument,!1,e,r),o=i.firstChild,1===i.childNodes.length&&(i=o),o||r)){for(u=(s=w.map(ye(i,"script"),He)).length;f<p;f++)l=i,f!==d&&(l=w.clone(l,!0,!0),u&&w.merge(s,ye(l,"script"))),n.call(e[f],l,f);if(u)for(c=s[s.length-1].ownerDocument,w.map(s,Oe),f=0;f<u;f++)l=s[f],he.test(l.type||"")&&!J.access(l,"globalEval")&&w.contains(c,l)&&(l.src&&"module"!==(l.type||"").toLowerCase()?w._evalUrl&&w._evalUrl(l.src):m(l.textContent.replace(qe,""),c,l))}return e}function Ie(e,t,n){for(var r,i=t?w.filter(t,e):e,o=0;null!=(r=i[o]);o++)n||1!==r.nodeType||w.cleanData(ye(r)),r.parentNode&&(n&&w.contains(r.ownerDocument,r)&&ve(ye(r,"script")),r.parentNode.removeChild(r));return e}w.extend({htmlPrefilter:function(e){return e.replace(Ne,"<$1></$2>")},clone:function(e,t,n){var r,i,o,a,s=e.cloneNode(!0),u=w.contains(e.ownerDocument,e);if(!(h.noCloneChecked||1!==e.nodeType&&11!==e.nodeType||w.isXMLDoc(e)))for(a=ye(s),r=0,i=(o=ye(e)).length;r<i;r++)Me(o[r],a[r]);if(t)if(n)for(o=o||ye(e),a=a||ye(s),r=0,i=o.length;r<i;r++)Pe(o[r],a[r]);else Pe(e,s);return(a=ye(s,"script")).length>0&&ve(a,!u&&ye(e,"script")),s},cleanData:function(e){for(var t,n,r,i=w.event.special,o=0;void 0!==(n=e[o]);o++)if(Y(n)){if(t=n[J.expando]){if(t.events)for(r in t.events)i[r]?w.event.remove(n,r):w.removeEvent(n,r,t.handle);n[J.expando]=void 0}n[K.expando]&&(n[K.expando]=void 0)}}}),w.fn.extend({detach:function(e){return Ie(this,e,!0)},remove:function(e){return Ie(this,e)},text:function(e){return z(this,function(e){return void 0===e?w.text(this):this.empty().each(function(){1!==this.nodeType&&11!==this.nodeType&&9!==this.nodeType||(this.textContent=e)})},null,e,arguments.length)},append:function(){return Re(this,arguments,function(e){1!==this.nodeType&&11!==this.nodeType&&9!==this.nodeType||Le(this,e).appendChild(e)})},prepend:function(){return Re(this,arguments,function(e){if(1===this.nodeType||11===this.nodeType||9===this.nodeType){var t=Le(this,e);t.insertBefore(e,t.firstChild)}})},before:function(){return Re(this,arguments,function(e){this.parentNode&&this.parentNode.insertBefore(e,this)})},after:function(){return Re(this,arguments,function(e){this.parentNode&&this.parentNode.insertBefore(e,this.nextSibling)})},empty:function(){for(var e,t=0;null!=(e=this[t]);t++)1===e.nodeType&&(w.cleanData(ye(e,!1)),e.textContent="");return this},clone:function(e,t){return e=null!=e&&e,t=null==t?e:t,this.map(function(){return w.clone(this,e,t)})},html:function(e){return z(this,function(e){var t=this[0]||{},n=0,r=this.length;if(void 0===e&&1===t.nodeType)return t.innerHTML;if("string"==typeof e&&!Ae.test(e)&&!ge[(de.exec(e)||["",""])[1].toLowerCase()]){e=w.htmlPrefilter(e);try{for(;n<r;n++)1===(t=this[n]||{}).nodeType&&(w.cleanData(ye(t,!1)),t.innerHTML=e);t=0}catch(e){}}t&&this.empty().append(e)},null,e,arguments.length)},replaceWith:function(){var e=[];return Re(this,arguments,function(t){var n=this.parentNode;w.inArray(this,e)<0&&(w.cleanData(ye(this)),n&&n.replaceChild(t,this))},e)}}),w.each({appendTo:"append",prependTo:"prepend",insertBefore:"before",insertAfter:"after",replaceAll:"replaceWith"},function(e,t){w.fn[e]=function(e){for(var n,r=[],i=w(e),o=i.length-1,a=0;a<=o;a++)n=a===o?this:this.clone(!0),w(i[a])[t](n),s.apply(r,n.get());return this.pushStack(r)}});var We=new RegExp("^("+re+")(?!px)[a-z%]+$","i"),$e=function(t){var n=t.ownerDocument.defaultView;return n&&n.opener||(n=e),n.getComputedStyle(t)},Be=new RegExp(oe.join("|"),"i");!function(){function t(){if(c){l.style.cssText="position:absolute;left:-11111px;width:60px;margin-top:1px;padding:0;border:0",c.style.cssText="position:relative;display:block;box-sizing:border-box;overflow:scroll;margin:auto;border:1px;padding:1px;width:60%;top:1%",be.appendChild(l).appendChild(c);var t=e.getComputedStyle(c);i="1%"!==t.top,u=12===n(t.marginLeft),c.style.right="60%",s=36===n(t.right),o=36===n(t.width),c.style.position="absolute",a=36===c.offsetWidth||"absolute",be.removeChild(l),c=null}}function n(e){return Math.round(parseFloat(e))}var i,o,a,s,u,l=r.createElement("div"),c=r.createElement("div");c.style&&(c.style.backgroundClip="content-box",c.cloneNode(!0).style.backgroundClip="",h.clearCloneStyle="content-box"===c.style.backgroundClip,w.extend(h,{boxSizingReliable:function(){return t(),o},pixelBoxStyles:function(){return t(),s},pixelPosition:function(){return t(),i},reliableMarginLeft:function(){return t(),u},scrollboxSize:function(){return t(),a}}))}();function Fe(e,t,n){var r,i,o,a,s=e.style;return(n=n||$e(e))&&(""!==(a=n.getPropertyValue(t)||n[t])||w.contains(e.ownerDocument,e)||(a=w.style(e,t)),!h.pixelBoxStyles()&&We.test(a)&&Be.test(t)&&(r=s.width,i=s.minWidth,o=s.maxWidth,s.minWidth=s.maxWidth=s.width=a,a=n.width,s.width=r,s.minWidth=i,s.maxWidth=o)),void 0!==a?a+"":a}function _e(e,t){return{get:function(){if(!e())return(this.get=t).apply(this,arguments);delete this.get}}}var ze=/^(none|table(?!-c[ea]).+)/,Xe=/^--/,Ue={position:"absolute",visibility:"hidden",display:"block"},Ve={letterSpacing:"0",fontWeight:"400"},Ge=["Webkit","Moz","ms"],Ye=r.createElement("div").style;function Qe(e){if(e in Ye)return e;var t=e[0].toUpperCase()+e.slice(1),n=Ge.length;while(n--)if((e=Ge[n]+t)in Ye)return e}function Je(e){var t=w.cssProps[e];return t||(t=w.cssProps[e]=Qe(e)||e),t}function Ke(e,t,n){var r=ie.exec(t);return r?Math.max(0,r[2]-(n||0))+(r[3]||"px"):t}function Ze(e,t,n,r,i,o){var a="width"===t?1:0,s=0,u=0;if(n===(r?"border":"content"))return 0;for(;a<4;a+=2)"margin"===n&&(u+=w.css(e,n+oe[a],!0,i)),r?("content"===n&&(u-=w.css(e,"padding"+oe[a],!0,i)),"margin"!==n&&(u-=w.css(e,"border"+oe[a]+"Width",!0,i))):(u+=w.css(e,"padding"+oe[a],!0,i),"padding"!==n?u+=w.css(e,"border"+oe[a]+"Width",!0,i):s+=w.css(e,"border"+oe[a]+"Width",!0,i));return!r&&o>=0&&(u+=Math.max(0,Math.ceil(e["offset"+t[0].toUpperCase()+t.slice(1)]-o-u-s-.5))),u}function et(e,t,n){var r=$e(e),i=Fe(e,t,r),o="border-box"===w.css(e,"boxSizing",!1,r),a=o;if(We.test(i)){if(!n)return i;i="auto"}return a=a&&(h.boxSizingReliable()||i===e.style[t]),("auto"===i||!parseFloat(i)&&"inline"===w.css(e,"display",!1,r))&&(i=e["offset"+t[0].toUpperCase()+t.slice(1)],a=!0),(i=parseFloat(i)||0)+Ze(e,t,n||(o?"border":"content"),a,r,i)+"px"}w.extend({cssHooks:{opacity:{get:function(e,t){if(t){var n=Fe(e,"opacity");return""===n?"1":n}}}},cssNumber:{animationIterationCount:!0,columnCount:!0,fillOpacity:!0,flexGrow:!0,flexShrink:!0,fontWeight:!0,lineHeight:!0,opacity:!0,order:!0,orphans:!0,widows:!0,zIndex:!0,zoom:!0},cssProps:{},style:function(e,t,n,r){if(e&&3!==e.nodeType&&8!==e.nodeType&&e.style){var i,o,a,s=G(t),u=Xe.test(t),l=e.style;if(u||(t=Je(s)),a=w.cssHooks[t]||w.cssHooks[s],void 0===n)return a&&"get"in a&&void 0!==(i=a.get(e,!1,r))?i:l[t];"string"==(o=typeof n)&&(i=ie.exec(n))&&i[1]&&(n=ue(e,t,i),o="number"),null!=n&&n===n&&("number"===o&&(n+=i&&i[3]||(w.cssNumber[s]?"":"px")),h.clearCloneStyle||""!==n||0!==t.indexOf("background")||(l[t]="inherit"),a&&"set"in a&&void 0===(n=a.set(e,n,r))||(u?l.setProperty(t,n):l[t]=n))}},css:function(e,t,n,r){var i,o,a,s=G(t);return Xe.test(t)||(t=Je(s)),(a=w.cssHooks[t]||w.cssHooks[s])&&"get"in a&&(i=a.get(e,!0,n)),void 0===i&&(i=Fe(e,t,r)),"normal"===i&&t in Ve&&(i=Ve[t]),""===n||n?(o=parseFloat(i),!0===n||isFinite(o)?o||0:i):i}}),w.each(["height","width"],function(e,t){w.cssHooks[t]={get:function(e,n,r){if(n)return!ze.test(w.css(e,"display"))||e.getClientRects().length&&e.getBoundingClientRect().width?et(e,t,r):se(e,Ue,function(){return et(e,t,r)})},set:function(e,n,r){var i,o=$e(e),a="border-box"===w.css(e,"boxSizing",!1,o),s=r&&Ze(e,t,r,a,o);return a&&h.scrollboxSize()===o.position&&(s-=Math.ceil(e["offset"+t[0].toUpperCase()+t.slice(1)]-parseFloat(o[t])-Ze(e,t,"border",!1,o)-.5)),s&&(i=ie.exec(n))&&"px"!==(i[3]||"px")&&(e.style[t]=n,n=w.css(e,t)),Ke(e,n,s)}}}),w.cssHooks.marginLeft=_e(h.reliableMarginLeft,function(e,t){if(t)return(parseFloat(Fe(e,"marginLeft"))||e.getBoundingClientRect().left-se(e,{marginLeft:0},function(){return e.getBoundingClientRect().left}))+"px"}),w.each({margin:"",padding:"",border:"Width"},function(e,t){w.cssHooks[e+t]={expand:function(n){for(var r=0,i={},o="string"==typeof n?n.split(" "):[n];r<4;r++)i[e+oe[r]+t]=o[r]||o[r-2]||o[0];return i}},"margin"!==e&&(w.cssHooks[e+t].set=Ke)}),w.fn.extend({css:function(e,t){return z(this,function(e,t,n){var r,i,o={},a=0;if(Array.isArray(t)){for(r=$e(e),i=t.length;a<i;a++)o[t[a]]=w.css(e,t[a],!1,r);return o}return void 0!==n?w.style(e,t,n):w.css(e,t)},e,t,arguments.length>1)}});function tt(e,t,n,r,i){return new tt.prototype.init(e,t,n,r,i)}w.Tween=tt,tt.prototype={constructor:tt,init:function(e,t,n,r,i,o){this.elem=e,this.prop=n,this.easing=i||w.easing._default,this.options=t,this.start=this.now=this.cur(),this.end=r,this.unit=o||(w.cssNumber[n]?"":"px")},cur:function(){var e=tt.propHooks[this.prop];return e&&e.get?e.get(this):tt.propHooks._default.get(this)},run:function(e){var t,n=tt.propHooks[this.prop];return this.options.duration?this.pos=t=w.easing[this.easing](e,this.options.duration*e,0,1,this.options.duration):this.pos=t=e,this.now=(this.end-this.start)*t+this.start,this.options.step&&this.options.step.call(this.elem,this.now,this),n&&n.set?n.set(this):tt.propHooks._default.set(this),this}},tt.prototype.init.prototype=tt.prototype,tt.propHooks={_default:{get:function(e){var t;return 1!==e.elem.nodeType||null!=e.elem[e.prop]&&null==e.elem.style[e.prop]?e.elem[e.prop]:(t=w.css(e.elem,e.prop,""))&&"auto"!==t?t:0},set:function(e){w.fx.step[e.prop]?w.fx.step[e.prop](e):1!==e.elem.nodeType||null==e.elem.style[w.cssProps[e.prop]]&&!w.cssHooks[e.prop]?e.elem[e.prop]=e.now:w.style(e.elem,e.prop,e.now+e.unit)}}},tt.propHooks.scrollTop=tt.propHooks.scrollLeft={set:function(e){e.elem.nodeType&&e.elem.parentNode&&(e.elem[e.prop]=e.now)}},w.easing={linear:function(e){return e},swing:function(e){return.5-Math.cos(e*Math.PI)/2},_default:"swing"},w.fx=tt.prototype.init,w.fx.step={};var nt,rt,it=/^(?:toggle|show|hide)$/,ot=/queueHooks$/;function at(){rt&&(!1===r.hidden&&e.requestAnimationFrame?e.requestAnimationFrame(at):e.setTimeout(at,w.fx.interval),w.fx.tick())}function st(){return e.setTimeout(function(){nt=void 0}),nt=Date.now()}function ut(e,t){var n,r=0,i={height:e};for(t=t?1:0;r<4;r+=2-t)i["margin"+(n=oe[r])]=i["padding"+n]=e;return t&&(i.opacity=i.width=e),i}function lt(e,t,n){for(var r,i=(pt.tweeners[t]||[]).concat(pt.tweeners["*"]),o=0,a=i.length;o<a;o++)if(r=i[o].call(n,t,e))return r}function ct(e,t,n){var r,i,o,a,s,u,l,c,f="width"in t||"height"in t,p=this,d={},h=e.style,g=e.nodeType&&ae(e),y=J.get(e,"fxshow");n.queue||(null==(a=w._queueHooks(e,"fx")).unqueued&&(a.unqueued=0,s=a.empty.fire,a.empty.fire=function(){a.unqueued||s()}),a.unqueued++,p.always(function(){p.always(function(){a.unqueued--,w.queue(e,"fx").length||a.empty.fire()})}));for(r in t)if(i=t[r],it.test(i)){if(delete t[r],o=o||"toggle"===i,i===(g?"hide":"show")){if("show"!==i||!y||void 0===y[r])continue;g=!0}d[r]=y&&y[r]||w.style(e,r)}if((u=!w.isEmptyObject(t))||!w.isEmptyObject(d)){f&&1===e.nodeType&&(n.overflow=[h.overflow,h.overflowX,h.overflowY],null==(l=y&&y.display)&&(l=J.get(e,"display")),"none"===(c=w.css(e,"display"))&&(l?c=l:(fe([e],!0),l=e.style.display||l,c=w.css(e,"display"),fe([e]))),("inline"===c||"inline-block"===c&&null!=l)&&"none"===w.css(e,"float")&&(u||(p.done(function(){h.display=l}),null==l&&(c=h.display,l="none"===c?"":c)),h.display="inline-block")),n.overflow&&(h.overflow="hidden",p.always(function(){h.overflow=n.overflow[0],h.overflowX=n.overflow[1],h.overflowY=n.overflow[2]})),u=!1;for(r in d)u||(y?"hidden"in y&&(g=y.hidden):y=J.access(e,"fxshow",{display:l}),o&&(y.hidden=!g),g&&fe([e],!0),p.done(function(){g||fe([e]),J.remove(e,"fxshow");for(r in d)w.style(e,r,d[r])})),u=lt(g?y[r]:0,r,p),r in y||(y[r]=u.start,g&&(u.end=u.start,u.start=0))}}function ft(e,t){var n,r,i,o,a;for(n in e)if(r=G(n),i=t[r],o=e[n],Array.isArray(o)&&(i=o[1],o=e[n]=o[0]),n!==r&&(e[r]=o,delete e[n]),(a=w.cssHooks[r])&&"expand"in a){o=a.expand(o),delete e[r];for(n in o)n in e||(e[n]=o[n],t[n]=i)}else t[r]=i}function pt(e,t,n){var r,i,o=0,a=pt.prefilters.length,s=w.Deferred().always(function(){delete u.elem}),u=function(){if(i)return!1;for(var t=nt||st(),n=Math.max(0,l.startTime+l.duration-t),r=1-(n/l.duration||0),o=0,a=l.tweens.length;o<a;o++)l.tweens[o].run(r);return s.notifyWith(e,[l,r,n]),r<1&&a?n:(a||s.notifyWith(e,[l,1,0]),s.resolveWith(e,[l]),!1)},l=s.promise({elem:e,props:w.extend({},t),opts:w.extend(!0,{specialEasing:{},easing:w.easing._default},n),originalProperties:t,originalOptions:n,startTime:nt||st(),duration:n.duration,tweens:[],createTween:function(t,n){var r=w.Tween(e,l.opts,t,n,l.opts.specialEasing[t]||l.opts.easing);return l.tweens.push(r),r},stop:function(t){var n=0,r=t?l.tweens.length:0;if(i)return this;for(i=!0;n<r;n++)l.tweens[n].run(1);return t?(s.notifyWith(e,[l,1,0]),s.resolveWith(e,[l,t])):s.rejectWith(e,[l,t]),this}}),c=l.props;for(ft(c,l.opts.specialEasing);o<a;o++)if(r=pt.prefilters[o].call(l,e,c,l.opts))return g(r.stop)&&(w._queueHooks(l.elem,l.opts.queue).stop=r.stop.bind(r)),r;return w.map(c,lt,l),g(l.opts.start)&&l.opts.start.call(e,l),l.progress(l.opts.progress).done(l.opts.done,l.opts.complete).fail(l.opts.fail).always(l.opts.always),w.fx.timer(w.extend(u,{elem:e,anim:l,queue:l.opts.queue})),l}w.Animation=w.extend(pt,{tweeners:{"*":[function(e,t){var n=this.createTween(e,t);return ue(n.elem,e,ie.exec(t),n),n}]},tweener:function(e,t){g(e)?(t=e,e=["*"]):e=e.match(M);for(var n,r=0,i=e.length;r<i;r++)n=e[r],pt.tweeners[n]=pt.tweeners[n]||[],pt.tweeners[n].unshift(t)},prefilters:[ct],prefilter:function(e,t){t?pt.prefilters.unshift(e):pt.prefilters.push(e)}}),w.speed=function(e,t,n){var r=e&&"object"==typeof e?w.extend({},e):{complete:n||!n&&t||g(e)&&e,duration:e,easing:n&&t||t&&!g(t)&&t};return w.fx.off?r.duration=0:"number"!=typeof r.duration&&(r.duration in w.fx.speeds?r.duration=w.fx.speeds[r.duration]:r.duration=w.fx.speeds._default),null!=r.queue&&!0!==r.queue||(r.queue="fx"),r.old=r.complete,r.complete=function(){g(r.old)&&r.old.call(this),r.queue&&w.dequeue(this,r.queue)},r},w.fn.extend({fadeTo:function(e,t,n,r){return this.filter(ae).css("opacity",0).show().end().animate({opacity:t},e,n,r)},animate:function(e,t,n,r){var i=w.isEmptyObject(e),o=w.speed(t,n,r),a=function(){var t=pt(this,w.extend({},e),o);(i||J.get(this,"finish"))&&t.stop(!0)};return a.finish=a,i||!1===o.queue?this.each(a):this.queue(o.queue,a)},stop:function(e,t,n){var r=function(e){var t=e.stop;delete e.stop,t(n)};return"string"!=typeof e&&(n=t,t=e,e=void 0),t&&!1!==e&&this.queue(e||"fx",[]),this.each(function(){var t=!0,i=null!=e&&e+"queueHooks",o=w.timers,a=J.get(this);if(i)a[i]&&a[i].stop&&r(a[i]);else for(i in a)a[i]&&a[i].stop&&ot.test(i)&&r(a[i]);for(i=o.length;i--;)o[i].elem!==this||null!=e&&o[i].queue!==e||(o[i].anim.stop(n),t=!1,o.splice(i,1));!t&&n||w.dequeue(this,e)})},finish:function(e){return!1!==e&&(e=e||"fx"),this.each(function(){var t,n=J.get(this),r=n[e+"queue"],i=n[e+"queueHooks"],o=w.timers,a=r?r.length:0;for(n.finish=!0,w.queue(this,e,[]),i&&i.stop&&i.stop.call(this,!0),t=o.length;t--;)o[t].elem===this&&o[t].queue===e&&(o[t].anim.stop(!0),o.splice(t,1));for(t=0;t<a;t++)r[t]&&r[t].finish&&r[t].finish.call(this);delete n.finish})}}),w.each(["toggle","show","hide"],function(e,t){var n=w.fn[t];w.fn[t]=function(e,r,i){return null==e||"boolean"==typeof e?n.apply(this,arguments):this.animate(ut(t,!0),e,r,i)}}),w.each({slideDown:ut("show"),slideUp:ut("hide"),slideToggle:ut("toggle"),fadeIn:{opacity:"show"},fadeOut:{opacity:"hide"},fadeToggle:{opacity:"toggle"}},function(e,t){w.fn[e]=function(e,n,r){return this.animate(t,e,n,r)}}),w.timers=[],w.fx.tick=function(){var e,t=0,n=w.timers;for(nt=Date.now();t<n.length;t++)(e=n[t])()||n[t]!==e||n.splice(t--,1);n.length||w.fx.stop(),nt=void 0},w.fx.timer=function(e){w.timers.push(e),w.fx.start()},w.fx.interval=13,w.fx.start=function(){rt||(rt=!0,at())},w.fx.stop=function(){rt=null},w.fx.speeds={slow:600,fast:200,_default:400},w.fn.delay=function(t,n){return t=w.fx?w.fx.speeds[t]||t:t,n=n||"fx",this.queue(n,function(n,r){var i=e.setTimeout(n,t);r.stop=function(){e.clearTimeout(i)}})},function(){var e=r.createElement("input"),t=r.createElement("select").appendChild(r.createElement("option"));e.type="checkbox",h.checkOn=""!==e.value,h.optSelected=t.selected,(e=r.createElement("input")).value="t",e.type="radio",h.radioValue="t"===e.value}();var dt,ht=w.expr.attrHandle;w.fn.extend({attr:function(e,t){return z(this,w.attr,e,t,arguments.length>1)},removeAttr:function(e){return this.each(function(){w.removeAttr(this,e)})}}),w.extend({attr:function(e,t,n){var r,i,o=e.nodeType;if(3!==o&&8!==o&&2!==o)return"undefined"==typeof e.getAttribute?w.prop(e,t,n):(1===o&&w.isXMLDoc(e)||(i=w.attrHooks[t.toLowerCase()]||(w.expr.match.bool.test(t)?dt:void 0)),void 0!==n?null===n?void w.removeAttr(e,t):i&&"set"in i&&void 0!==(r=i.set(e,n,t))?r:(e.setAttribute(t,n+""),n):i&&"get"in i&&null!==(r=i.get(e,t))?r:null==(r=w.find.attr(e,t))?void 0:r)},attrHooks:{type:{set:function(e,t){if(!h.radioValue&&"radio"===t&&N(e,"input")){var n=e.value;return e.setAttribute("type",t),n&&(e.value=n),t}}}},removeAttr:function(e,t){var n,r=0,i=t&&t.match(M);if(i&&1===e.nodeType)while(n=i[r++])e.removeAttribute(n)}}),dt={set:function(e,t,n){return!1===t?w.removeAttr(e,n):e.setAttribute(n,n),n}},w.each(w.expr.match.bool.source.match(/\w+/g),function(e,t){var n=ht[t]||w.find.attr;ht[t]=function(e,t,r){var i,o,a=t.toLowerCase();return r||(o=ht[a],ht[a]=i,i=null!=n(e,t,r)?a:null,ht[a]=o),i}});var gt=/^(?:input|select|textarea|button)$/i,yt=/^(?:a|area)$/i;w.fn.extend({prop:function(e,t){return z(this,w.prop,e,t,arguments.length>1)},removeProp:function(e){return this.each(function(){delete this[w.propFix[e]||e]})}}),w.extend({prop:function(e,t,n){var r,i,o=e.nodeType;if(3!==o&&8!==o&&2!==o)return 1===o&&w.isXMLDoc(e)||(t=w.propFix[t]||t,i=w.propHooks[t]),void 0!==n?i&&"set"in i&&void 0!==(r=i.set(e,n,t))?r:e[t]=n:i&&"get"in i&&null!==(r=i.get(e,t))?r:e[t]},propHooks:{tabIndex:{get:function(e){var t=w.find.attr(e,"tabindex");return t?parseInt(t,10):gt.test(e.nodeName)||yt.test(e.nodeName)&&e.href?0:-1}}},propFix:{"for":"htmlFor","class":"className"}}),h.optSelected||(w.propHooks.selected={get:function(e){var t=e.parentNode;return t&&t.parentNode&&t.parentNode.selectedIndex,null},set:function(e){var t=e.parentNode;t&&(t.selectedIndex,t.parentNode&&t.parentNode.selectedIndex)}}),w.each(["tabIndex","readOnly","maxLength","cellSpacing","cellPadding","rowSpan","colSpan","useMap","frameBorder","contentEditable"],function(){w.propFix[this.toLowerCase()]=this});function vt(e){return(e.match(M)||[]).join(" ")}function mt(e){return e.getAttribute&&e.getAttribute("class")||""}function xt(e){return Array.isArray(e)?e:"string"==typeof e?e.match(M)||[]:[]}w.fn.extend({addClass:function(e){var t,n,r,i,o,a,s,u=0;if(g(e))return this.each(function(t){w(this).addClass(e.call(this,t,mt(this)))});if((t=xt(e)).length)while(n=this[u++])if(i=mt(n),r=1===n.nodeType&&" "+vt(i)+" "){a=0;while(o=t[a++])r.indexOf(" "+o+" ")<0&&(r+=o+" ");i!==(s=vt(r))&&n.setAttribute("class",s)}return this},removeClass:function(e){var t,n,r,i,o,a,s,u=0;if(g(e))return this.each(function(t){w(this).removeClass(e.call(this,t,mt(this)))});if(!arguments.length)return this.attr("class","");if((t=xt(e)).length)while(n=this[u++])if(i=mt(n),r=1===n.nodeType&&" "+vt(i)+" "){a=0;while(o=t[a++])while(r.indexOf(" "+o+" ")>-1)r=r.replace(" "+o+" "," ");i!==(s=vt(r))&&n.setAttribute("class",s)}return this},toggleClass:function(e,t){var n=typeof e,r="string"===n||Array.isArray(e);return"boolean"==typeof t&&r?t?this.addClass(e):this.removeClass(e):g(e)?this.each(function(n){w(this).toggleClass(e.call(this,n,mt(this),t),t)}):this.each(function(){var t,i,o,a;if(r){i=0,o=w(this),a=xt(e);while(t=a[i++])o.hasClass(t)?o.removeClass(t):o.addClass(t)}else void 0!==e&&"boolean"!==n||((t=mt(this))&&J.set(this,"__className__",t),this.setAttribute&&this.setAttribute("class",t||!1===e?"":J.get(this,"__className__")||""))})},hasClass:function(e){var t,n,r=0;t=" "+e+" ";while(n=this[r++])if(1===n.nodeType&&(" "+vt(mt(n))+" ").indexOf(t)>-1)return!0;return!1}});var bt=/\r/g;w.fn.extend({val:function(e){var t,n,r,i=this[0];{if(arguments.length)return r=g(e),this.each(function(n){var i;1===this.nodeType&&(null==(i=r?e.call(this,n,w(this).val()):e)?i="":"number"==typeof i?i+="":Array.isArray(i)&&(i=w.map(i,function(e){return null==e?"":e+""})),(t=w.valHooks[this.type]||w.valHooks[this.nodeName.toLowerCase()])&&"set"in t&&void 0!==t.set(this,i,"value")||(this.value=i))});if(i)return(t=w.valHooks[i.type]||w.valHooks[i.nodeName.toLowerCase()])&&"get"in t&&void 0!==(n=t.get(i,"value"))?n:"string"==typeof(n=i.value)?n.replace(bt,""):null==n?"":n}}}),w.extend({valHooks:{option:{get:function(e){var t=w.find.attr(e,"value");return null!=t?t:vt(w.text(e))}},select:{get:function(e){var t,n,r,i=e.options,o=e.selectedIndex,a="select-one"===e.type,s=a?null:[],u=a?o+1:i.length;for(r=o<0?u:a?o:0;r<u;r++)if(((n=i[r]).selected||r===o)&&!n.disabled&&(!n.parentNode.disabled||!N(n.parentNode,"optgroup"))){if(t=w(n).val(),a)return t;s.push(t)}return s},set:function(e,t){var n,r,i=e.options,o=w.makeArray(t),a=i.length;while(a--)((r=i[a]).selected=w.inArray(w.valHooks.option.get(r),o)>-1)&&(n=!0);return n||(e.selectedIndex=-1),o}}}}),w.each(["radio","checkbox"],function(){w.valHooks[this]={set:function(e,t){if(Array.isArray(t))return e.checked=w.inArray(w(e).val(),t)>-1}},h.checkOn||(w.valHooks[this].get=function(e){return null===e.getAttribute("value")?"on":e.value})}),h.focusin="onfocusin"in e;var wt=/^(?:focusinfocus|focusoutblur)$/,Tt=function(e){e.stopPropagation()};w.extend(w.event,{trigger:function(t,n,i,o){var a,s,u,l,c,p,d,h,v=[i||r],m=f.call(t,"type")?t.type:t,x=f.call(t,"namespace")?t.namespace.split("."):[];if(s=h=u=i=i||r,3!==i.nodeType&&8!==i.nodeType&&!wt.test(m+w.event.triggered)&&(m.indexOf(".")>-1&&(m=(x=m.split(".")).shift(),x.sort()),c=m.indexOf(":")<0&&"on"+m,t=t[w.expando]?t:new w.Event(m,"object"==typeof t&&t),t.isTrigger=o?2:3,t.namespace=x.join("."),t.rnamespace=t.namespace?new RegExp("(^|\\.)"+x.join("\\.(?:.*\\.|)")+"(\\.|$)"):null,t.result=void 0,t.target||(t.target=i),n=null==n?[t]:w.makeArray(n,[t]),d=w.event.special[m]||{},o||!d.trigger||!1!==d.trigger.apply(i,n))){if(!o&&!d.noBubble&&!y(i)){for(l=d.delegateType||m,wt.test(l+m)||(s=s.parentNode);s;s=s.parentNode)v.push(s),u=s;u===(i.ownerDocument||r)&&v.push(u.defaultView||u.parentWindow||e)}a=0;while((s=v[a++])&&!t.isPropagationStopped())h=s,t.type=a>1?l:d.bindType||m,(p=(J.get(s,"events")||{})[t.type]&&J.get(s,"handle"))&&p.apply(s,n),(p=c&&s[c])&&p.apply&&Y(s)&&(t.result=p.apply(s,n),!1===t.result&&t.preventDefault());return t.type=m,o||t.isDefaultPrevented()||d._default&&!1!==d._default.apply(v.pop(),n)||!Y(i)||c&&g(i[m])&&!y(i)&&((u=i[c])&&(i[c]=null),w.event.triggered=m,t.isPropagationStopped()&&h.addEventListener(m,Tt),i[m](),t.isPropagationStopped()&&h.removeEventListener(m,Tt),w.event.triggered=void 0,u&&(i[c]=u)),t.result}},simulate:function(e,t,n){var r=w.extend(new w.Event,n,{type:e,isSimulated:!0});w.event.trigger(r,null,t)}}),w.fn.extend({trigger:function(e,t){return this.each(function(){w.event.trigger(e,t,this)})},triggerHandler:function(e,t){var n=this[0];if(n)return w.event.trigger(e,t,n,!0)}}),h.focusin||w.each({focus:"focusin",blur:"focusout"},function(e,t){var n=function(e){w.event.simulate(t,e.target,w.event.fix(e))};w.event.special[t]={setup:function(){var r=this.ownerDocument||this,i=J.access(r,t);i||r.addEventListener(e,n,!0),J.access(r,t,(i||0)+1)},teardown:function(){var r=this.ownerDocument||this,i=J.access(r,t)-1;i?J.access(r,t,i):(r.removeEventListener(e,n,!0),J.remove(r,t))}}});var Ct=e.location,Et=Date.now(),kt=/\?/;w.parseXML=function(t){var n;if(!t||"string"!=typeof t)return null;try{n=(new e.DOMParser).parseFromString(t,"text/xml")}catch(e){n=void 0}return n&&!n.getElementsByTagName("parsererror").length||w.error("Invalid XML: "+t),n};var St=/\[\]$/,Dt=/\r?\n/g,Nt=/^(?:submit|button|image|reset|file)$/i,At=/^(?:input|select|textarea|keygen)/i;function jt(e,t,n,r){var i;if(Array.isArray(t))w.each(t,function(t,i){n||St.test(e)?r(e,i):jt(e+"["+("object"==typeof i&&null!=i?t:"")+"]",i,n,r)});else if(n||"object"!==x(t))r(e,t);else for(i in t)jt(e+"["+i+"]",t[i],n,r)}w.param=function(e,t){var n,r=[],i=function(e,t){var n=g(t)?t():t;r[r.length]=encodeURIComponent(e)+"="+encodeURIComponent(null==n?"":n)};if(Array.isArray(e)||e.jquery&&!w.isPlainObject(e))w.each(e,function(){i(this.name,this.value)});else for(n in e)jt(n,e[n],t,i);return r.join("&")},w.fn.extend({serialize:function(){return w.param(this.serializeArray())},serializeArray:function(){return this.map(function(){var e=w.prop(this,"elements");return e?w.makeArray(e):this}).filter(function(){var e=this.type;return this.name&&!w(this).is(":disabled")&&At.test(this.nodeName)&&!Nt.test(e)&&(this.checked||!pe.test(e))}).map(function(e,t){var n=w(this).val();return null==n?null:Array.isArray(n)?w.map(n,function(e){return{name:t.name,value:e.replace(Dt,"\r\n")}}):{name:t.name,value:n.replace(Dt,"\r\n")}}).get()}});var qt=/%20/g,Lt=/#.*$/,Ht=/([?&])_=[^&]*/,Ot=/^(.*?):[ \t]*([^\r\n]*)$/gm,Pt=/^(?:about|app|app-storage|.+-extension|file|res|widget):$/,Mt=/^(?:GET|HEAD)$/,Rt=/^\/\//,It={},Wt={},$t="*/".concat("*"),Bt=r.createElement("a");Bt.href=Ct.href;function Ft(e){return function(t,n){"string"!=typeof t&&(n=t,t="*");var r,i=0,o=t.toLowerCase().match(M)||[];if(g(n))while(r=o[i++])"+"===r[0]?(r=r.slice(1)||"*",(e[r]=e[r]||[]).unshift(n)):(e[r]=e[r]||[]).push(n)}}function _t(e,t,n,r){var i={},o=e===Wt;function a(s){var u;return i[s]=!0,w.each(e[s]||[],function(e,s){var l=s(t,n,r);return"string"!=typeof l||o||i[l]?o?!(u=l):void 0:(t.dataTypes.unshift(l),a(l),!1)}),u}return a(t.dataTypes[0])||!i["*"]&&a("*")}function zt(e,t){var n,r,i=w.ajaxSettings.flatOptions||{};for(n in t)void 0!==t[n]&&((i[n]?e:r||(r={}))[n]=t[n]);return r&&w.extend(!0,e,r),e}function Xt(e,t,n){var r,i,o,a,s=e.contents,u=e.dataTypes;while("*"===u[0])u.shift(),void 0===r&&(r=e.mimeType||t.getResponseHeader("Content-Type"));if(r)for(i in s)if(s[i]&&s[i].test(r)){u.unshift(i);break}if(u[0]in n)o=u[0];else{for(i in n){if(!u[0]||e.converters[i+" "+u[0]]){o=i;break}a||(a=i)}o=o||a}if(o)return o!==u[0]&&u.unshift(o),n[o]}function Ut(e,t,n,r){var i,o,a,s,u,l={},c=e.dataTypes.slice();if(c[1])for(a in e.converters)l[a.toLowerCase()]=e.converters[a];o=c.shift();while(o)if(e.responseFields[o]&&(n[e.responseFields[o]]=t),!u&&r&&e.dataFilter&&(t=e.dataFilter(t,e.dataType)),u=o,o=c.shift())if("*"===o)o=u;else if("*"!==u&&u!==o){if(!(a=l[u+" "+o]||l["* "+o]))for(i in l)if((s=i.split(" "))[1]===o&&(a=l[u+" "+s[0]]||l["* "+s[0]])){!0===a?a=l[i]:!0!==l[i]&&(o=s[0],c.unshift(s[1]));break}if(!0!==a)if(a&&e["throws"])t=a(t);else try{t=a(t)}catch(e){return{state:"parsererror",error:a?e:"No conversion from "+u+" to "+o}}}return{state:"success",data:t}}w.extend({active:0,lastModified:{},etag:{},ajaxSettings:{url:Ct.href,type:"GET",isLocal:Pt.test(Ct.protocol),global:!0,processData:!0,async:!0,contentType:"application/x-www-form-urlencoded; charset=UTF-8",accepts:{"*":$t,text:"text/plain",html:"text/html",xml:"application/xml, text/xml",json:"application/json, text/javascript"},contents:{xml:/\bxml\b/,html:/\bhtml/,json:/\bjson\b/},responseFields:{xml:"responseXML",text:"responseText",json:"responseJSON"},converters:{"* text":String,"text html":!0,"text json":JSON.parse,"text xml":w.parseXML},flatOptions:{url:!0,context:!0}},ajaxSetup:function(e,t){return t?zt(zt(e,w.ajaxSettings),t):zt(w.ajaxSettings,e)},ajaxPrefilter:Ft(It),ajaxTransport:Ft(Wt),ajax:function(t,n){"object"==typeof t&&(n=t,t=void 0),n=n||{};var i,o,a,s,u,l,c,f,p,d,h=w.ajaxSetup({},n),g=h.context||h,y=h.context&&(g.nodeType||g.jquery)?w(g):w.event,v=w.Deferred(),m=w.Callbacks("once memory"),x=h.statusCode||{},b={},T={},C="canceled",E={readyState:0,getResponseHeader:function(e){var t;if(c){if(!s){s={};while(t=Ot.exec(a))s[t[1].toLowerCase()]=t[2]}t=s[e.toLowerCase()]}return null==t?null:t},getAllResponseHeaders:function(){return c?a:null},setRequestHeader:function(e,t){return null==c&&(e=T[e.toLowerCase()]=T[e.toLowerCase()]||e,b[e]=t),this},overrideMimeType:function(e){return null==c&&(h.mimeType=e),this},statusCode:function(e){var t;if(e)if(c)E.always(e[E.status]);else for(t in e)x[t]=[x[t],e[t]];return this},abort:function(e){var t=e||C;return i&&i.abort(t),k(0,t),this}};if(v.promise(E),h.url=((t||h.url||Ct.href)+"").replace(Rt,Ct.protocol+"//"),h.type=n.method||n.type||h.method||h.type,h.dataTypes=(h.dataType||"*").toLowerCase().match(M)||[""],null==h.crossDomain){l=r.createElement("a");try{l.href=h.url,l.href=l.href,h.crossDomain=Bt.protocol+"//"+Bt.host!=l.protocol+"//"+l.host}catch(e){h.crossDomain=!0}}if(h.data&&h.processData&&"string"!=typeof h.data&&(h.data=w.param(h.data,h.traditional)),_t(It,h,n,E),c)return E;(f=w.event&&h.global)&&0==w.active++&&w.event.trigger("ajaxStart"),h.type=h.type.toUpperCase(),h.hasContent=!Mt.test(h.type),o=h.url.replace(Lt,""),h.hasContent?h.data&&h.processData&&0===(h.contentType||"").indexOf("application/x-www-form-urlencoded")&&(h.data=h.data.replace(qt,"+")):(d=h.url.slice(o.length),h.data&&(h.processData||"string"==typeof h.data)&&(o+=(kt.test(o)?"&":"?")+h.data,delete h.data),!1===h.cache&&(o=o.replace(Ht,"$1"),d=(kt.test(o)?"&":"?")+"_="+Et+++d),h.url=o+d),h.ifModified&&(w.lastModified[o]&&E.setRequestHeader("If-Modified-Since",w.lastModified[o]),w.etag[o]&&E.setRequestHeader("If-None-Match",w.etag[o])),(h.data&&h.hasContent&&!1!==h.contentType||n.contentType)&&E.setRequestHeader("Content-Type",h.contentType),E.setRequestHeader("Accept",h.dataTypes[0]&&h.accepts[h.dataTypes[0]]?h.accepts[h.dataTypes[0]]+("*"!==h.dataTypes[0]?", "+$t+"; q=0.01":""):h.accepts["*"]);for(p in h.headers)E.setRequestHeader(p,h.headers[p]);if(h.beforeSend&&(!1===h.beforeSend.call(g,E,h)||c))return E.abort();if(C="abort",m.add(h.complete),E.done(h.success),E.fail(h.error),i=_t(Wt,h,n,E)){if(E.readyState=1,f&&y.trigger("ajaxSend",[E,h]),c)return E;h.async&&h.timeout>0&&(u=e.setTimeout(function(){E.abort("timeout")},h.timeout));try{c=!1,i.send(b,k)}catch(e){if(c)throw e;k(-1,e)}}else k(-1,"No Transport");function k(t,n,r,s){var l,p,d,b,T,C=n;c||(c=!0,u&&e.clearTimeout(u),i=void 0,a=s||"",E.readyState=t>0?4:0,l=t>=200&&t<300||304===t,r&&(b=Xt(h,E,r)),b=Ut(h,b,E,l),l?(h.ifModified&&((T=E.getResponseHeader("Last-Modified"))&&(w.lastModified[o]=T),(T=E.getResponseHeader("etag"))&&(w.etag[o]=T)),204===t||"HEAD"===h.type?C="nocontent":304===t?C="notmodified":(C=b.state,p=b.data,l=!(d=b.error))):(d=C,!t&&C||(C="error",t<0&&(t=0))),E.status=t,E.statusText=(n||C)+"",l?v.resolveWith(g,[p,C,E]):v.rejectWith(g,[E,C,d]),E.statusCode(x),x=void 0,f&&y.trigger(l?"ajaxSuccess":"ajaxError",[E,h,l?p:d]),m.fireWith(g,[E,C]),f&&(y.trigger("ajaxComplete",[E,h]),--w.active||w.event.trigger("ajaxStop")))}return E},getJSON:function(e,t,n){return w.get(e,t,n,"json")},getScript:function(e,t){return w.get(e,void 0,t,"script")}}),w.each(["get","post"],function(e,t){w[t]=function(e,n,r,i){return g(n)&&(i=i||r,r=n,n=void 0),w.ajax(w.extend({url:e,type:t,dataType:i,data:n,success:r},w.isPlainObject(e)&&e))}}),w._evalUrl=function(e){return w.ajax({url:e,type:"GET",dataType:"script",cache:!0,async:!1,global:!1,"throws":!0})},w.fn.extend({wrapAll:function(e){var t;return this[0]&&(g(e)&&(e=e.call(this[0])),t=w(e,this[0].ownerDocument).eq(0).clone(!0),this[0].parentNode&&t.insertBefore(this[0]),t.map(function(){var e=this;while(e.firstElementChild)e=e.firstElementChild;return e}).append(this)),this},wrapInner:function(e){return g(e)?this.each(function(t){w(this).wrapInner(e.call(this,t))}):this.each(function(){var t=w(this),n=t.contents();n.length?n.wrapAll(e):t.append(e)})},wrap:function(e){var t=g(e);return this.each(function(n){w(this).wrapAll(t?e.call(this,n):e)})},unwrap:function(e){return this.parent(e).not("body").each(function(){w(this).replaceWith(this.childNodes)}),this}}),w.expr.pseudos.hidden=function(e){return!w.expr.pseudos.visible(e)},w.expr.pseudos.visible=function(e){return!!(e.offsetWidth||e.offsetHeight||e.getClientRects().length)},w.ajaxSettings.xhr=function(){try{return new e.XMLHttpRequest}catch(e){}};var Vt={0:200,1223:204},Gt=w.ajaxSettings.xhr();h.cors=!!Gt&&"withCredentials"in Gt,h.ajax=Gt=!!Gt,w.ajaxTransport(function(t){var n,r;if(h.cors||Gt&&!t.crossDomain)return{send:function(i,o){var a,s=t.xhr();if(s.open(t.type,t.url,t.async,t.username,t.password),t.xhrFields)for(a in t.xhrFields)s[a]=t.xhrFields[a];t.mimeType&&s.overrideMimeType&&s.overrideMimeType(t.mimeType),t.crossDomain||i["X-Requested-With"]||(i["X-Requested-With"]="XMLHttpRequest");for(a in i)s.setRequestHeader(a,i[a]);n=function(e){return function(){n&&(n=r=s.onload=s.onerror=s.onabort=s.ontimeout=s.onreadystatechange=null,"abort"===e?s.abort():"error"===e?"number"!=typeof s.status?o(0,"error"):o(s.status,s.statusText):o(Vt[s.status]||s.status,s.statusText,"text"!==(s.responseType||"text")||"string"!=typeof s.responseText?{binary:s.response}:{text:s.responseText},s.getAllResponseHeaders()))}},s.onload=n(),r=s.onerror=s.ontimeout=n("error"),void 0!==s.onabort?s.onabort=r:s.onreadystatechange=function(){4===s.readyState&&e.setTimeout(function(){n&&r()})},n=n("abort");try{s.send(t.hasContent&&t.data||null)}catch(e){if(n)throw e}},abort:function(){n&&n()}}}),w.ajaxPrefilter(function(e){e.crossDomain&&(e.contents.script=!1)}),w.ajaxSetup({accepts:{script:"text/javascript, application/javascript, application/ecmascript, application/x-ecmascript"},contents:{script:/\b(?:java|ecma)script\b/},converters:{"text script":function(e){return w.globalEval(e),e}}}),w.ajaxPrefilter("script",function(e){void 0===e.cache&&(e.cache=!1),e.crossDomain&&(e.type="GET")}),w.ajaxTransport("script",function(e){if(e.crossDomain){var t,n;return{send:function(i,o){t=w("<script>").prop({charset:e.scriptCharset,src:e.url}).on("load error",n=function(e){t.remove(),n=null,e&&o("error"===e.type?404:200,e.type)}),r.head.appendChild(t[0])},abort:function(){n&&n()}}}});var Yt=[],Qt=/(=)\?(?=&|$)|\?\?/;w.ajaxSetup({jsonp:"callback",jsonpCallback:function(){var e=Yt.pop()||w.expando+"_"+Et++;return this[e]=!0,e}}),w.ajaxPrefilter("json jsonp",function(t,n,r){var i,o,a,s=!1!==t.jsonp&&(Qt.test(t.url)?"url":"string"==typeof t.data&&0===(t.contentType||"").indexOf("application/x-www-form-urlencoded")&&Qt.test(t.data)&&"data");if(s||"jsonp"===t.dataTypes[0])return i=t.jsonpCallback=g(t.jsonpCallback)?t.jsonpCallback():t.jsonpCallback,s?t[s]=t[s].replace(Qt,"$1"+i):!1!==t.jsonp&&(t.url+=(kt.test(t.url)?"&":"?")+t.jsonp+"="+i),t.converters["script json"]=function(){return a||w.error(i+" was not called"),a[0]},t.dataTypes[0]="json",o=e[i],e[i]=function(){a=arguments},r.always(function(){void 0===o?w(e).removeProp(i):e[i]=o,t[i]&&(t.jsonpCallback=n.jsonpCallback,Yt.push(i)),a&&g(o)&&o(a[0]),a=o=void 0}),"script"}),h.createHTMLDocument=function(){var e=r.implementation.createHTMLDocument("").body;return e.innerHTML="<form></form><form></form>",2===e.childNodes.length}(),w.parseHTML=function(e,t,n){if("string"!=typeof e)return[];"boolean"==typeof t&&(n=t,t=!1);var i,o,a;return t||(h.createHTMLDocument?((i=(t=r.implementation.createHTMLDocument("")).createElement("base")).href=r.location.href,t.head.appendChild(i)):t=r),o=A.exec(e),a=!n&&[],o?[t.createElement(o[1])]:(o=xe([e],t,a),a&&a.length&&w(a).remove(),w.merge([],o.childNodes))},w.fn.load=function(e,t,n){var r,i,o,a=this,s=e.indexOf(" ");return s>-1&&(r=vt(e.slice(s)),e=e.slice(0,s)),g(t)?(n=t,t=void 0):t&&"object"==typeof t&&(i="POST"),a.length>0&&w.ajax({url:e,type:i||"GET",dataType:"html",data:t}).done(function(e){o=arguments,a.html(r?w("<div>").append(w.parseHTML(e)).find(r):e)}).always(n&&function(e,t){a.each(function(){n.apply(this,o||[e.responseText,t,e])})}),this},w.each(["ajaxStart","ajaxStop","ajaxComplete","ajaxError","ajaxSuccess","ajaxSend"],function(e,t){w.fn[t]=function(e){return this.on(t,e)}}),w.expr.pseudos.animated=function(e){return w.grep(w.timers,function(t){return e===t.elem}).length},w.offset={setOffset:function(e,t,n){var r,i,o,a,s,u,l,c=w.css(e,"position"),f=w(e),p={};"static"===c&&(e.style.position="relative"),s=f.offset(),o=w.css(e,"top"),u=w.css(e,"left"),(l=("absolute"===c||"fixed"===c)&&(o+u).indexOf("auto")>-1)?(a=(r=f.position()).top,i=r.left):(a=parseFloat(o)||0,i=parseFloat(u)||0),g(t)&&(t=t.call(e,n,w.extend({},s))),null!=t.top&&(p.top=t.top-s.top+a),null!=t.left&&(p.left=t.left-s.left+i),"using"in t?t.using.call(e,p):f.css(p)}},w.fn.extend({offset:function(e){if(arguments.length)return void 0===e?this:this.each(function(t){w.offset.setOffset(this,e,t)});var t,n,r=this[0];if(r)return r.getClientRects().length?(t=r.getBoundingClientRect(),n=r.ownerDocument.defaultView,{top:t.top+n.pageYOffset,left:t.left+n.pageXOffset}):{top:0,left:0}},position:function(){if(this[0]){var e,t,n,r=this[0],i={top:0,left:0};if("fixed"===w.css(r,"position"))t=r.getBoundingClientRect();else{t=this.offset(),n=r.ownerDocument,e=r.offsetParent||n.documentElement;while(e&&(e===n.body||e===n.documentElement)&&"static"===w.css(e,"position"))e=e.parentNode;e&&e!==r&&1===e.nodeType&&((i=w(e).offset()).top+=w.css(e,"borderTopWidth",!0),i.left+=w.css(e,"borderLeftWidth",!0))}return{top:t.top-i.top-w.css(r,"marginTop",!0),left:t.left-i.left-w.css(r,"marginLeft",!0)}}},offsetParent:function(){return this.map(function(){var e=this.offsetParent;while(e&&"static"===w.css(e,"position"))e=e.offsetParent;return e||be})}}),w.each({scrollLeft:"pageXOffset",scrollTop:"pageYOffset"},function(e,t){var n="pageYOffset"===t;w.fn[e]=function(r){return z(this,function(e,r,i){var o;if(y(e)?o=e:9===e.nodeType&&(o=e.defaultView),void 0===i)return o?o[t]:e[r];o?o.scrollTo(n?o.pageXOffset:i,n?i:o.pageYOffset):e[r]=i},e,r,arguments.length)}}),w.each(["top","left"],function(e,t){w.cssHooks[t]=_e(h.pixelPosition,function(e,n){if(n)return n=Fe(e,t),We.test(n)?w(e).position()[t]+"px":n})}),w.each({Height:"height",Width:"width"},function(e,t){w.each({padding:"inner"+e,content:t,"":"outer"+e},function(n,r){w.fn[r]=function(i,o){var a=arguments.length&&(n||"boolean"!=typeof i),s=n||(!0===i||!0===o?"margin":"border");return z(this,function(t,n,i){var o;return y(t)?0===r.indexOf("outer")?t["inner"+e]:t.document.documentElement["client"+e]:9===t.nodeType?(o=t.documentElement,Math.max(t.body["scroll"+e],o["scroll"+e],t.body["offset"+e],o["offset"+e],o["client"+e])):void 0===i?w.css(t,n,s):w.style(t,n,i,s)},t,a?i:void 0,a)}})}),w.each("blur focus focusin focusout resize scroll click dblclick mousedown mouseup mousemove mouseover mouseout mouseenter mouseleave change select submit keydown keypress keyup contextmenu".split(" "),function(e,t){w.fn[t]=function(e,n){return arguments.length>0?this.on(t,null,e,n):this.trigger(t)}}),w.fn.extend({hover:function(e,t){return this.mouseenter(e).mouseleave(t||e)}}),w.fn.extend({bind:function(e,t,n){return this.on(e,null,t,n)},unbind:function(e,t){return this.off(e,null,t)},delegate:function(e,t,n,r){return this.on(t,e,n,r)},undelegate:function(e,t,n){return 1===arguments.length?this.off(e,"**"):this.off(t,e||"**",n)}}),w.proxy=function(e,t){var n,r,i;if("string"==typeof t&&(n=e[t],t=e,e=n),g(e))return r=o.call(arguments,2),i=function(){return e.apply(t||this,r.concat(o.call(arguments)))},i.guid=e.guid=e.guid||w.guid++,i},w.holdReady=function(e){e?w.readyWait++:w.ready(!0)},w.isArray=Array.isArray,w.parseJSON=JSON.parse,w.nodeName=N,w.isFunction=g,w.isWindow=y,w.camelCase=G,w.type=x,w.now=Date.now,w.isNumeric=function(e){var t=w.type(e);return("number"===t||"string"===t)&&!isNaN(e-parseFloat(e))},"function"==typeof define&&define.amd&&define("jquery",[],function(){return w});var Jt=e.jQuery,Kt=e.$;return w.noConflict=function(t){return e.$===w&&(e.$=Kt),t&&e.jQuery===w&&(e.jQuery=Jt),w},t||(e.jQuery=e.$=w),w});
</script>
  <script type="text/javascript">/**
 * StyleFix 1.0.3 & PrefixFree 1.0.7
 * @author Lea Verou
 * MIT license
 */(function(){function t(e,t){return[].slice.call((t||document).querySelectorAll(e))}if(!window.addEventListener)return;var e=window.StyleFix={link:function(t){try{if(t.rel!=="stylesheet"||t.hasAttribute("data-noprefix"))return}catch(n){return}var r=t.href||t.getAttribute("data-href"),i=r.replace(/[^\/]+$/,""),s=t.parentNode,o=new XMLHttpRequest,u;o.onreadystatechange=function(){o.readyState===4&&u()};u=function(){var n=o.responseText;if(n&&t.parentNode&&(!o.status||o.status<400||o.status>600)){n=e.fix(n,!0,t);if(i){n=n.replace(/url\(\s*?((?:"|')?)(.+?)\1\s*?\)/gi,function(e,t,n){return/^([a-z]{3,10}:|\/|#)/i.test(n)?e:'url("'+i+n+'")'});var r=i.replace(/([\\\^\$*+[\]?{}.=!:(|)])/g,"\\$1");n=n.replace(RegExp("\\b(behavior:\\s*?url\\('?\"?)"+r,"gi"),"$1")}var u=document.createElement("style");u.textContent=n;u.media=t.media;u.disabled=t.disabled;u.setAttribute("data-href",t.getAttribute("href"));s.insertBefore(u,t);s.removeChild(t);u.media=t.media}};try{o.open("GET",r);o.send(null)}catch(n){if(typeof XDomainRequest!="undefined"){o=new XDomainRequest;o.onerror=o.onprogress=function(){};o.onload=u;o.open("GET",r);o.send(null)}}t.setAttribute("data-inprogress","")},styleElement:function(t){if(t.hasAttribute("data-noprefix"))return;var n=t.disabled;t.textContent=e.fix(t.textContent,!0,t);t.disabled=n},styleAttribute:function(t){var n=t.getAttribute("style");n=e.fix(n,!1,t);t.setAttribute("style",n)},process:function(){t('link[rel="stylesheet"]:not([data-inprogress])').forEach(StyleFix.link);t("style").forEach(StyleFix.styleElement);t("[style]").forEach(StyleFix.styleAttribute)},register:function(t,n){(e.fixers=e.fixers||[]).splice(n===undefined?e.fixers.length:n,0,t)},fix:function(t,n,r){for(var i=0;i<e.fixers.length;i++)t=e.fixers[i](t,n,r)||t;return t},camelCase:function(e){return e.replace(/-([a-z])/g,function(e,t){return t.toUpperCase()}).replace("-","")},deCamelCase:function(e){return e.replace(/[A-Z]/g,function(e){return"-"+e.toLowerCase()})}};(function(){setTimeout(function(){t('link[rel="stylesheet"]').forEach(StyleFix.link)},10);document.addEventListener("DOMContentLoaded",StyleFix.process,!1)})()})();(function(e){function t(e,t,r,i,s){e=n[e];if(e.length){var o=RegExp(t+"("+e.join("|")+")"+r,"gi");s=s.replace(o,i)}return s}if(!window.StyleFix||!window.getComputedStyle)return;var n=window.PrefixFree={prefixCSS:function(e,r,i){var s=n.prefix;n.functions.indexOf("linear-gradient")>-1&&(e=e.replace(/(\s|:|,)(repeating-)?linear-gradient\(\s*(-?\d*\.?\d*)deg/ig,function(e,t,n,r){return t+(n||"")+"linear-gradient("+(90-r)+"deg"}));e=t("functions","(\\s|:|,)","\\s*\\(","$1"+s+"$2(",e);e=t("keywords","(\\s|:)","(\\s|;|\\}|$)","$1"+s+"$2$3",e);e=t("properties","(^|\\{|\\s|;)","\\s*:","$1"+s+"$2:",e);if(n.properties.length){var o=RegExp("\\b("+n.properties.join("|")+")(?!:)","gi");e=t("valueProperties","\\b",":(.+?);",function(e){return e.replace(o,s+"$1")},e)}if(r){e=t("selectors","","\\b",n.prefixSelector,e);e=t("atrules","@","\\b","@"+s+"$1",e)}e=e.replace(RegExp("-"+s,"g"),"-");e=e.replace(/-\*-(?=[a-z]+)/gi,n.prefix);return e},property:function(e){return(n.properties.indexOf(e)?n.prefix:"")+e},value:function(e,r){e=t("functions","(^|\\s|,)","\\s*\\(","$1"+n.prefix+"$2(",e);e=t("keywords","(^|\\s)","(\\s|$)","$1"+n.prefix+"$2$3",e);return e},prefixSelector:function(e){return e.replace(/^:{1,2}/,function(e){return e+n.prefix})},prefixProperty:function(e,t){var r=n.prefix+e;return t?StyleFix.camelCase(r):r}};(function(){var e={},t=[],r={},i=getComputedStyle(document.documentElement,null),s=document.createElement("div").style,o=function(n){if(n.charAt(0)==="-"){t.push(n);var r=n.split("-"),i=r[1];e[i]=++e[i]||1;while(r.length>3){r.pop();var s=r.join("-");u(s)&&t.indexOf(s)===-1&&t.push(s)}}},u=function(e){return StyleFix.camelCase(e)in s};if(i.length>0)for(var a=0;a<i.length;a++)o(i[a]);else for(var f in i)o(StyleFix.deCamelCase(f));var l={uses:0};for(var c in e){var h=e[c];l.uses<h&&(l={prefix:c,uses:h})}n.prefix="-"+l.prefix+"-";n.Prefix=StyleFix.camelCase(n.prefix);n.properties=[];for(var a=0;a<t.length;a++){var f=t[a];if(f.indexOf(n.prefix)===0){var p=f.slice(n.prefix.length);u(p)||n.properties.push(p)}}n.Prefix=="Ms"&&!("transform"in s)&&!("MsTransform"in s)&&"msTransform"in s&&n.properties.push("transform","transform-origin");n.properties.sort()})();(function(){function i(e,t){r[t]="";r[t]=e;return!!r[t]}var e={"linear-gradient":{property:"backgroundImage",params:"red, teal"},calc:{property:"width",params:"1px + 5%"},element:{property:"backgroundImage",params:"#foo"},"cross-fade":{property:"backgroundImage",params:"url(a.png), url(b.png), 50%"}};e["repeating-linear-gradient"]=e["repeating-radial-gradient"]=e["radial-gradient"]=e["linear-gradient"];var t={initial:"color","zoom-in":"cursor","zoom-out":"cursor",box:"display",flexbox:"display","inline-flexbox":"display",flex:"display","inline-flex":"display"};n.functions=[];n.keywords=[];var r=document.createElement("div").style;for(var s in e){var o=e[s],u=o.property,a=s+"("+o.params+")";!i(a,u)&&i(n.prefix+a,u)&&n.functions.push(s)}for(var f in t){var u=t[f];!i(f,u)&&i(n.prefix+f,u)&&n.keywords.push(f)}})();(function(){function s(e){i.textContent=e+"{}";return!!i.sheet.cssRules.length}var t={":read-only":null,":read-write":null,":any-link":null,"::selection":null},r={keyframes:"name",viewport:null,document:'regexp(".")'};n.selectors=[];n.atrules=[];var i=e.appendChild(document.createElement("style"));for(var o in t){var u=o+(t[o]?"("+t[o]+")":"");!s(u)&&s(n.prefixSelector(u))&&n.selectors.push(o)}for(var a in r){var u=a+" "+(r[a]||"");!s("@"+u)&&s("@"+n.prefix+u)&&n.atrules.push(a)}e.removeChild(i)})();n.valueProperties=["transition","transition-property"];e.className+=" "+n.prefix;StyleFix.register(n.prefixCSS)})(document.documentElement);
 </script>
  <script type="text/javascript">/**
 * Minified by jsDelivr using UglifyJS v3.3.21.
 * Original file: /npm/conic-gradient@1.0.0/conic-gradient.js
 * 
 * Do NOT use SRI with dynamically generated files! More information: https://www.jsdelivr.com/using-sri-with-dynamic-files
 */
!function(){var t=Math.PI,e=2*t,d=t/180,o=document.createElement("div");document.head.appendChild(o);var p=self.ConicGradient=function(t){p.all.push(this),t=t||{},this.canvas=document.createElement("canvas"),this.context=this.canvas.getContext("2d"),this.repeating=!!t.repeating,this.size=t.size||Math.max(innerWidth,innerHeight),this.canvas.width=this.canvas.height=this.size;var s=t.stops;this.stops=(s||"").split(/\s*,(?![^(]*\))\s*/);for(var o=this.from=0;o<this.stops.length;o++)if(this.stops[o]){var i=this.stops[o]=new p.ColorStop(this,this.stops[o]);i.next&&(this.stops.splice(o+1,0,i.next),o++)}else this.stops.splice(o,1),o--;if(0==this.stops[0].color.indexOf("from")&&(this.from=360*this.stops[0].pos,this.stops.shift()),void 0===this.stops[0].pos)this.stops[0].pos=0;else if(0<this.stops[0].pos){var e=this.stops[0].clone();e.pos=0,this.stops.unshift(e)}if(void 0===this.stops[this.stops.length-1].pos)this.stops[this.stops.length-1].pos=1;else if(!this.repeating&&this.stops[this.stops.length-1].pos<1){var r=this.stops[this.stops.length-1].clone();r.pos=1,this.stops.push(r)}if(this.stops.forEach(function(t,s){if(void 0===t.pos){for(var o=s+1;this[o];o++)if(void 0!==this[o].pos){t.pos=this[s-1].pos+(this[o].pos-this[s-1].pos)/(o-s+1);break}}else 0<s&&(t.pos=Math.max(t.pos,this[s-1].pos))},this.stops),this.repeating){var n=(s=this.stops.slice())[s.length-1].pos-s[0].pos;for(o=0;this.stops[this.stops.length-1].pos<1&&o<1e4;o++)for(var h=0;h<s.length;h++){var a=s[h].clone();a.pos+=(o+1)*n,this.stops.push(a)}}this.paint()};p.all=[],p.prototype={toString:function(){return"url('"+this.dataURL+"')"},get dataURL(){return"data:image/svg+xml,"+encodeURIComponent(this.svg)},get blobURL(){return URL.createObjectURL(new Blob([this.svg],{type:"image/svg+xml"}))},get svg(){return'<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="none"><svg viewBox="0 0 100 100" preserveAspectRatio="xMidYMid slice"><image width="100" height="100%" xlink:href="'+this.png+'" /></svg></svg>'},get png(){return this.canvas.toDataURL()},get r(){return Math.sqrt(2)*this.size/2},paint:function(){var i,t,e,s=this.context,o=this.r,r=this.size/2,n=0,h=this.stops[n];s.translate(this.size/2,this.size/2),s.rotate(-90*d),s.rotate(this.from*d),s.translate(-this.size/2,-this.size/2);for(var a=0;a<360;){if(a/360+1e-5>=h.pos){for(;i=h,n++,(h=this.stops[n])&&h!=i&&h.pos===i.pos;);if(!h)break;var p=i.color+""==h.color+""&&i!=h;t=i.color.map(function(t,s){return h.color[s]-t})}e=(a/360-i.pos)/(h.pos-i.pos);var l=p?h.color:t.map(function(t,s){var o=t*e+i.color[s];return s<3?255&o:o});if(s.fillStyle="rgba("+l.join(",")+")",s.beginPath(),s.moveTo(r,r),p)var c=360*(h.pos-i.pos);else c=.5;var g=a*d,f=(g=Math.min(360*d,g))+c*d;f=Math.min(360*d,f+.02),s.arc(r,r,o,g,f),s.closePath(),s.fill(),a+=c}}},p.ColorStop=function(t,s){if(this.gradient=t,s){var o=s.match(/^(.+?)(?:\s+([\d.]+)(%|deg|turn|grad|rad)?)?(?:\s+([\d.]+)(%|deg|turn|grad|rad)?)?\s*$/);if(this.color=p.ColorStop.colorToRGBA(o[1]),o[2]){var i=o[3];"%"==i||"0"===o[2]&&!i?this.pos=o[2]/100:"turn"==i?this.pos=+o[2]:"deg"==i?this.pos=o[2]/360:"grad"==i?this.pos=o[2]/400:"rad"==i&&(this.pos=o[2]/e)}o[4]&&(this.next=new p.ColorStop(t,o[1]+" "+o[4]+o[5]))}},p.ColorStop.prototype={clone:function(){var t=new p.ColorStop(this.gradient);return t.color=this.color,t.pos=this.pos,t},toString:function(){return"rgba("+this.color.join(", ")+") "+100*this.pos+"%"}},p.ColorStop.colorToRGBA=function(t){if(!Array.isArray(t)&&-1==t.indexOf("from")){o.style.color=t;var s=getComputedStyle(o).color.match(/rgba?\(([\d.]+), ([\d.]+), ([\d.]+)(?:, ([\d.]+))?\)/);return s&&(s.shift(),(s=s.map(function(t){return+t}))[3]=isNaN(s[3])?1:s[3]),s||[0,0,0,0]}return t}}(),self.StyleFix&&function(){var t=document.createElement("p");t.style.backgroundImage="conic-gradient(white, black)",t.style.backgroundImage=PrefixFree.prefix+"conic-gradient(white, black)",t.style.backgroundImage||StyleFix.register(function(t,s){return-1<t.indexOf("conic-gradient")&&(t=t.replace(/(?:repeating-)?conic-gradient\(\s*((?:\([^()]+\)|[^;()}])+?)\)/g,function(t,s){return new ConicGradient({stops:s,repeating:-1<t.indexOf("repeating-")})})),t})}();
//# sourceMappingURL=/sm/9e0139ba8e1ddb934dfa3689c3207f552762686bca69b4d77270e61d5bcd733c.map</script>
  <script type="text/javascript">
    $(window).on('load', function () {
  let topColHeight = 'auto';
  let sideColWidth = 'auto';
  const csvData = {"rows":[[{"span":20,"isColumn":true,"id":9606500,"title":"State","description":"","setDescription":""}],[{"span":1,"isColumn":true,"id":9606501,"title":"Jammu and Kashmir","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606502,"title":"Punjab","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606503,"title":"Rajasthan","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606504,"title":"Himachal Pradesh","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606505,"title":"Odisha","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606506,"title":"Haryana","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606507,"title":"Karnataka","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606508,"title":"Kerala","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606509,"title":"Maharastra","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606510,"title":"Telangana","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606511,"title":"Tamil Nadu","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606512,"title":"Uttar Pradesh","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606513,"title":"Uttarakhand","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606514,"title":"Andhra Pradesh","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606515,"title":"Chattisgarh","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606516,"title":"Gujarat","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606517,"title":"Madhya Pradesh","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606518,"title":"West Bengal","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606519,"title":"Jharkhand","description":"","setDescription":""},{"span":1,"isColumn":true,"id":9606520,"title":"Bihar","description":"","setDescription":""}],[{"span":3,"isColumn":false,"id":9633221,"title":"Type of study","description":"","setDescription":""},{"span":1,"isColumn":false,"id":9633222,"title":"Impact evaluation","description":"","setDescription":""}],[{"span":1,"isColumn":false,"id":9633223,"title":"Economic evaluation","description":"","setDescription":""}],[{"span":1,"isColumn":false,"id":9633224,"title":"Dissertation and Thesis","description":"","setDescription":""}]],"totalColBreadth":20,"totalColDepth":2,"totalRowBreadth":3,"totalRowDepth":1};
  const filters = [{"id":9632573,"label":"Economic outcomes","checked":false,"children":[{"id":9633209,"label":"Transaction cost","checked":false,"children":[]},{"id":9633202,"label":"Cost of production/ cultivation","checked":false,"children":[]},{"id":9633137,"label":"Productivity","checked":false,"children":[]},{"id":9633204,"label":"Employment","checked":false,"children":[]},{"id":9641036,"label":"Saving ","checked":false,"children":[]},{"id":9633210,"label":"Constraints","checked":false,"children":[]}]}];
  const autoOpenFilter = false;
  const externalURLedAttributes = [{"AttributeSetId":9632464,"AttributeId":9632573,"AttributeName":"Economic outcomes","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633099,"AttributeId":9633208,"AttributeName":"Economic outcomes - Availability of inputs","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633111,"AttributeId":9633220,"AttributeName":"Economic outcomes - Availability of inputs - Credit","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633110,"AttributeId":9633219,"AttributeName":"Economic outcomes - Availability of inputs - Extension services","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633109,"AttributeId":9633218,"AttributeName":"Economic outcomes - Availability of inputs - Fertiliser/ Medicines","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633108,"AttributeId":9633217,"AttributeName":"Economic outcomes - Availability of inputs - Seeds/ One day old chick","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633101,"AttributeId":9633210,"AttributeName":"Economic outcomes - Constraints","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633093,"AttributeId":9633202,"AttributeName":"Economic outcomes - Cost of production/ cultivation","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633095,"AttributeId":9633204,"AttributeName":"Economic outcomes - Employment","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9632961,"AttributeId":9633070,"AttributeName":"Economic outcomes - Price risk/ Price realised","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633028,"AttributeId":9633137,"AttributeName":"Economic outcomes - Productivity","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9640927,"AttributeId":9641036,"AttributeName":"Economic outcomes - Saving ","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633100,"AttributeId":9633209,"AttributeName":"Economic outcomes - Transaction cost","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606394,"AttributeId":9606500,"AttributeName":"State","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606408,"AttributeId":9606514,"AttributeName":"State - Andhra Pradesh","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606414,"AttributeId":9606520,"AttributeName":"State - Bihar","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606409,"AttributeId":9606515,"AttributeName":"State - Chattisgarh","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606410,"AttributeId":9606516,"AttributeName":"State - Gujarat","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606400,"AttributeId":9606506,"AttributeName":"State - Haryana","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606398,"AttributeId":9606504,"AttributeName":"State - Himachal Pradesh","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606395,"AttributeId":9606501,"AttributeName":"State - Jammu and Kashmir","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606413,"AttributeId":9606519,"AttributeName":"State - Jharkhand","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606401,"AttributeId":9606507,"AttributeName":"State - Karnataka","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606402,"AttributeId":9606508,"AttributeName":"State - Kerala","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606411,"AttributeId":9606517,"AttributeName":"State - Madhya Pradesh","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606403,"AttributeId":9606509,"AttributeName":"State - Maharastra","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606399,"AttributeId":9606505,"AttributeName":"State - Odisha","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606396,"AttributeId":9606502,"AttributeName":"State - Punjab","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606397,"AttributeId":9606503,"AttributeName":"State - Rajasthan","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606405,"AttributeId":9606511,"AttributeName":"State - Tamil Nadu","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606404,"AttributeId":9606510,"AttributeName":"State - Telangana","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606406,"AttributeId":9606512,"AttributeName":"State - Uttar Pradesh","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606407,"AttributeId":9606513,"AttributeName":"State - Uttarakhand","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9606412,"AttributeId":9606518,"AttributeName":"State - West Bengal","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633112,"AttributeId":9633221,"AttributeName":"Type of study","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633115,"AttributeId":9633224,"AttributeName":"Type of study - Dissertation and Thesis","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633114,"AttributeId":9633223,"AttributeName":"Type of study - Economic evaluation","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9633113,"AttributeId":9633222,"AttributeName":"Type of study - Impact evaluation","AttributeDescription":"","ExtURL":"","ExtType":""},{"AttributeSetId":9644821,"AttributeId":9644930,"AttributeName":"study done","AttributeDescription":"","ExtURL":"","ExtType":""}];
  const metaProperties = [];
  const aboutContent = "<p>Map depicts the status of contract farming across the country</p>";
  const aboutPopup = false;
  const studySubmissionContent = "";
  const segmentAttributes = [{"attribute":{"AttributeDescription":"","ExtURL":"","ExtType":"","OriginalAttributeID":0,"AttributeSetId":9632961,"AttributeId":9633070,"AttributeSetDescription":"","AttributeType":"Outcome","AttributeName":"Price risk/ Price realised"},"color":"#65665E"},{"attribute":{"AttributeDescription":"","ExtURL":"","ExtType":"","OriginalAttributeID":0,"AttributeSetId":9633100,"AttributeId":9633209,"AttributeSetDescription":"","AttributeType":"Selectable (show checkbox)","AttributeName":"Transaction cost"},"color":"#9F9FCA"},{"attribute":{"AttributeDescription":"","ExtURL":"","ExtType":"","OriginalAttributeID":0,"AttributeSetId":9633093,"AttributeId":9633202,"AttributeSetDescription":"","AttributeType":"Selectable (show checkbox)","AttributeName":"Cost of production/ cultivation"},"color":"#05190A"},{"attribute":{"AttributeDescription":"","ExtURL":"","ExtType":"","OriginalAttributeID":0,"AttributeSetId":9633028,"AttributeId":9633137,"AttributeSetDescription":"","AttributeType":"Selectable (show checkbox)","AttributeName":"Productivity"},"color":"#857A8E"},{"attribute":{"AttributeDescription":"","ExtURL":"","ExtType":"","OriginalAttributeID":0,"AttributeSetId":9633095,"AttributeId":9633204,"AttributeSetDescription":"","AttributeType":"Selectable (show checkbox)","AttributeName":"Employment"},"color":"#D8B3B3"},{"attribute":{"AttributeDescription":"","ExtURL":"","ExtType":"","OriginalAttributeID":0,"AttributeSetId":9640927,"AttributeId":9641036,"AttributeSetDescription":"","AttributeType":"Selectable (show checkbox)","AttributeName":"Saving "},"color":"#7A6E6E"}];
  const referenceData = [{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[{"ItemDocumentId":680629,"TextFrom":0,"TextTo":0,"Text":"Page 1:\n[¬s]\"cost of cultivation[¬e]\"","IsFromPDF":true,"DocTitle":"20163279042.pdf","ItemArm":""}]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[{"ItemDocumentId":680629,"TextFrom":0,"TextTo":0,"Text":"Page 8:\n[¬s]\"seeds,\nfertilizers to the farmers along with technical support.[¬e]\"","IsFromPDF":true,"DocTitle":"20163279042.pdf","ItemArm":""}]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122931,"Title":"Economic Performance and Impact of Contract Farming in Karnataka","ParentTitle":"Mysore Journal of Agricultural Sciences","ShortTitle":"Agric (2013)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"14/09/2021","EditedBy":"Manjisha Sinha","Year":"2013","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"48","Pages":"609-617","Edition":"","Issue":"4","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Agric - 2013 - Economic Performance and Impact of Contract Farming in Karnataka.pdf","OldItemId":"61304829","Abstract":"Contract farming of green chilli production is a recent trend, which began in southern part of Karnataka. The economics performance of contract farming farmers in green chilli and its impact are presented. This study pertains to 45 farmers each, under DCFF-domestic contract farming firm (Namdhari’s fresh, Bidadi), FCFF-foreign contract farming firm (Indo Spanish Tasty foods pvt. Ltd., Kunigal) and 40 non-contract farmers (NCF’s) in Karnataka. The study was conducted during 2005-06 and indicated that, the contract farming firms supplied key inputs to farmers worth 36 per cent of the total cost of cultivation which was deducted in final payment. Total cost incurred per acre was Rs. 26,657, 24,484 and 23,498 for farmers under foreign firm, domestic firm and non-contract, respectively. Non-contract farmers realized net return (Rs. 6,101) which was two times lesser than farmers under domestic firm (Rs. 11,108) and 1.14 times lesser than farmers under foreign firm (Rs. 6,981). The transaction cost per acre was meager for contract farmers (Rs. 79 and 5.75 for farmers under FCFF farmers and DCFF farmers respectively), while it was Rs. 4,991 per acre for non-contract farmers. Production risk is relatively higher for farmers under DCFF. The saved transaction cost (Rs.4, 991) is the implicit benefit to contract farmers since the contract firms provide inputs and procure outputs. The economic performance and impact as measured through the gross benefit and saved transaction cost are Rs. 45, 776, 48,146 and 24,458 for FCFF, DCFF and non-contract farmers, respectively. The net benefit per rupee expenditure was Rs 1.72 and 1.97 under FCFF and DCFF farmers, respectively. CONTRACT","Comments":"","TypeName":"Journal, Article","Authors":"Pramod et al; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, Primary Report, Economic evaluation, Seeds, extension services, gross return , transaction cost, Cost of production, fertilizers, Profit","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Pramod et al (2013) Economic Performance and Impact of Contract Farming in Karnataka. Mysore Journal of Agricultural Sciences 48(4), 609-617"},{"Codes":[{"AttributeId":9606511,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122932,"Title":"CONTRACT FARMING: A MULTI-DIMENSIONAL ANALYSIS","ParentTitle":"","ShortTitle":"Arun (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/97435","OldItemId":"61307302","Abstract":"In the present era of globalization, Indian agriculture is undergoing a distinctive transformation process. The farmers are subjected to more of the risks and it causes lots of distress in their lives. The increased number of farmers’ suicides indicates the importance of effective ri sk management strategy. Understanding agricultural risks and the ways of managi ng it is therefore a topic that deserves serious attention. A contract-farming arrangement is seen as a promising alternative that typically obliges a firm to supply inputs, extension, or credit, in exchange for a marketing agreement that fixes a price for the product and binds the farmer to follow a particular production method or input re gimen. The present study analyzed the contract farming by delving with various dimensions. The specific objectives of the study were to study the genesis of contract farming, to draw the profiles of the contract farmers and non-contracting farmers, to identify the motivating factors of the contract farmers and the contracting firm, to study the constraints of the stakeholders, to study the contract farming practices and procedures, to identify the constraints faced by the stakeholders and to study the effectiveness of contract farming. The study was purposively conducted in Tamil Nadu as this state has separate policy on contract farming. Two crops were selected for the study – Coleus and Cotton. Two contracting firm dealing with these two crops were selected. From the company’s list of contract farmers, forty contract farmers were randomly selected from each contracting firm and forty non-contract farmers were selected from each crop. Therefore, totally 160 farmers were taken for the study. Contract farming has existed in India since colonial period. The British have cultivated indigo, opium, tea, coffee under contracts. After independence, in Maharashtra sugarcane was produced under contract and in Gujarat the milk co- operatives followed the foot paths. Contract farming by Pepsico in Punjab had a positive influence and many companies in different states adopted contract farming in different crops. In Tamil Nadu, the contract farming was present in sugarcane, seed production and broilers. The contract farming in cotton developed out of increased demand for the quality cotton and increased cost of production for the farmers. In case of coleus, it gained popul arity lately and in selected regions. The increased demand of the coleus in foreign market and the poor market has led to contract farming. The importance of cont ract farming can be perceived from the efforts taken by the central which has suggested through the model APMC act and the governments of many states have made necessary amendments. Most of the contract farmers were in the middle aged category. But the contract farmers were relatively younger, attended more years of schooling than the non-contract farmers. Coleus contract farm ers were more from the joint family than the cotton contract farmers. Mostly the contract farmers were of small and semi- medium farmers and they were purely depe ndent on farming. The level of social participation, urban contact, extension agency contact, mass media utilization, communication skills, economic motivation, innovative proneness, risk orientation, planning orientation, scientific orientati on and marketing orientation was relatively higher for the contract farmers. Education, social participation, urban contact and extension agency contact had significant differences between the profiles of the contract and non-contract farmers. Assured price, immediate payment, reduce the credit burden, input assistance are the four important motives of the contract farmers to enter contract farming. Input assistance, increased income, assured market, financial assistance, recognition among friends and relatives, success, know ledge on new technologies, security are the other motives reported by the respondents. For the contracting firms, suitability of crop, interest in medicinal plants, remuneration, motivation to do something useful and opportunity to serve, assured and timely supply of cotton, demand for fine and super fine cotton and quality produce are the motives for them to enter contract farming. Sudden intervention of the brokers, absence of government’s role, no improvement in the price, dissatisfaction with the advices, lower price, rejection of produce and stress are the constraints faced by the contract farmers. In case of the non-contract farmers, lower price, unknow n procedures, No belief on contracting company, insecurity and not approached by the contracting company are some of the constraints reported by the non-contract farmers. Both the contracting companies used written agreements for making the contracts.","Comments":"","TypeName":"Dissertation","Authors":"Arun Kumar S; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nTamil Nadu, Primary report, Need assessment, Inputs, extension services, constraints, Cost of poduction","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Arun Kumar S (2008) CONTRACT FARMING: A MULTI-DIMENSIONAL ANALYSIS. , ."},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122933,"Title":"Economic analysis of potato seed production under contract farming in Haryana","ParentTitle":"","ShortTitle":"Ashu (2017)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2017","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810039782","OldItemId":"61307313","Abstract":"The study on “an economic analysis of potato seed production under contact farming in Haryana” was undertaken with the following specific objectives; (i) To work out cost & return from potato seed production in Haryana (ii) To examine the resource use efficiency of important inputs and their impact on yield. (iii) To identify constraints faced by potato seed growers. The study was based on primary as well as secondary data. The primary data was collected from the 90 (45 contact farmers and 45 non-contract farmers) selected farmers of Karnal district of Haryana while, the secondary data was collected from the National Horticulture Research Development Foundation (New Delhi), Directorate of Horticulture research (Panchkula), National Horticulture Board (Gurugram) and AGMARKET online source in regarding of area, productivity, production and market price, respectively. The cost of cultivation analysis for potato seed production revealed that rental value of land and seed were higher in contract as well as non-contract farming while; cost of plant protection chemicals was higher in contract farming as compare to non-contract farming. However, cost of fertilizer was observed higher in non-contract farming. It was observed that per acre yield, gross return and net return was almost double in contract farming as compare on non-contract farming. From the study it has been revealed that in contract farming, the regression coefficients for the variables namely human labour, seed and plant protection charges were significantly negative whereas the for fertilizer and organic manure significant positive regression coefficient was reported. The price uncertainty ratio for non-contract and contract farming reveals that there is higher price risk under non-contract farming. The main reason for higher price uncertainty ratio for non-contract farming may be due to much variation in price of potato seeds in the market depending upon its quality and quantity marketed, place and location of sale, marketing channel and means of transportation etc. Results indicate that yield risk is higher in non-contract farming than that of contract farming. The lower yield risk in contract farming may be due to the fact that the contract farmers had used good quality seeds. These results further advocate the superiority of contact farming system over the non-contract faming in yield and price uncertainty of potato seed production. To achieve higher productivity of potato seeds, there is vast scope for the contract farming in the study area. Farmers has adopted contract farming mainly due to gain of higher income and good quality of inputs supplied by contractual agency. Moreover, the main reason for non-adoption of contract farming was mainly pertained to gap in communication delivery system in regards of the benefits of contract farming.","Comments":"","TypeName":"Dissertation","Authors":"Ashu  ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nHaryana, Cost of production, Income, Gross return, primary report, price risk, resources use efficiency, constraints, Income, Economic evaluation, need assessment","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Ashu  (2017) Economic analysis of potato seed production under contract farming in Haryana. , ."},{"Codes":[{"AttributeId":9606509,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[{"ItemDocumentId":680541,"TextFrom":0,"TextTo":0,"Text":"Page 11:\n[¬s]\"Cultivation Costs[¬e]\"","IsFromPDF":true,"DocTitle":"j.worlddev.2020.105202.pdf","ItemArm":""}]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122934,"Title":"Can institutional innovations in agri-marketing channels alleviate distress selling ? Evidence from India","ParentTitle":"World Development","ShortTitle":"Bhanot (2021)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2021","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"Elsevier Ltd","Institution":"","Volume":"137","Pages":"105202-105202","Edition":"","Issue":"","Availability":"","URL":"https://doi.org/10.1016/j.worlddev.2020.105202 file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Bhanot, Kathuria, Das - 2021 - Can institutional innovations in agri-marketing channels alleviate distress selling Evidence from India.pdf","OldItemId":"61304851","Abstract":"Distress selling of agri-produce is a common phenomenon in Indian agriculture, and is especially true for horticulture crops, given their highly perishable nature and not being covered under minimum support prices. This study focusses on uncovering the role of institutional innovations in agri-marketing channels in addressing the issue of distress selling. Using primary survey of 108 tomato grower farmers from the Western state Maharashtra in India, the study compares the likelihood of distress selling for farmers sell- ing through the alternative channels of Contract Farming (CF) and Farmer Producer Companies (FPCs), as against selling through the conventional marketing channel of Agriculture Produce Marketing Committees (APMCs). Building on the insights from prospect theory, where a farmer would react more severely to losses than to gains, we develop a mathematical model to compare the utility derived from selling in alternate channels (that is, CF and FPC) vis-à-vis selling through the APMC channel. Subsequently, using econometric analysis, we find that opting to sell through alternative marketing channels helps farmers minimize losses and shields them from distress selling. Finally, a probability function is developed to determine the likelihood of a farmer opting to sell in an alternate marketing channel (CF/ FPC) as against the conventional APMC channel. The findings aid in framing optimal pricing strategies that could be used by the contracting firms and FPCs.","Comments":"","TypeName":"Journal, Article","Authors":"Bhanot Disha ; Kathuria Vinish ; Das Debabrata ; ","ParentAuthors":"","DOI":"10.1016/j.worlddev.2020.105202","Keywords":"eppi-reviewer4\r\nMaharashtra, process evaluation, primary report","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Bhanot Disha, Kathuria Vinish, and Das Debabrata (2021) Can institutional innovations in agri-marketing channels alleviate distress selling ? Evidence from India. World Development 137, 105202-105202 DOI: 10.1016/j.worlddev.2020.105202"},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122935,"Title":"EFFICIENCY AND DISTRIBUTION IN CONTRACT FARMING: THE CASE OF INDIAN POULTRY GROWERS","ParentTitle":"","ShortTitle":"Bharat (2006)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2006","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Unknown - Unknown - No Title.pdf","OldItemId":"61304836","Abstract":"This paper is an empirical analysis of the gains from contract farming in the case of poultry production in the state of Andhra Pradesh in India. The paper finds that contract production is more efficient than noncontract production. The efficiency surplus is largely appropriated by the processor. Despite this, contract growers still gain appreciably from contracting in terms of lower risk and higher expected returns. Improved technology and production practices as well as the way in which the processor selects growers are what make these outcomes possible. In terms of observed and unobserved characteristics, contract growers have relatively poor prospects as independent growers. With contract production, these growers achieve incomes comparable to that of independent growers.","Comments":"","TypeName":"Report","Authors":"Bharat Ramaswami1 ; Pratap Singh Birthal2; P K Joshi3; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nContract Farming\nContracting\nPoultry\nVertical Integration, Primary report, economic evaluation, Efficiency, risk, improved technology, inputs, outcome evaluation, Andhra Pradesh, Income","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Bharat Ramaswami1, Pratap Singh Birthal2, and P K Joshi3 (2006) EFFICIENCY AND DISTRIBUTION IN CONTRACT FARMING: THE CASE OF INDIAN POULTRY GROWERS. : , "},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122936,"Title":"Grower heterogeneity and the gains from contract farming The case of Indian poultry","ParentTitle":"Indian Growth and Development Review","ShortTitle":"Bharat (2009)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2009","Month":"","StandardNumber":"1753825091","City":"","Country":"","Publisher":"","Institution":"","Volume":"2","Pages":"56-74","Edition":"","Issue":"1","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Authors - 2009 - Grower heterogeneity and the gains from contract farming The case of Indian poultry.pdf","OldItemId":"61304857","Abstract":"Purpose – The purpose of this paper is to offer an empirical analysis of contract farming (CF) for poultry in the southern state of Andhra Pradesh in India. Design/methodology/approach – Through a probit equation, the factors that matter to their participation in contracting are evaluated. The estimation of income gains is considered within a treatment effects model. The risk benefits from contracting are estimated by simulating the variability of returns if the contract farmers were to be independent growers. Findings – This paper shows that the poultry integrators in Andhra Pradesh are able to appropriate almost the entire efficiency gains from contracting. Yet, the contract growers are better off with the contract. This outcome is because of grower heterogeneity and the way it is employed in the selection of contract growers. The paper also finds that contract growers do gain substantially in terms of risk reduction. Research limitations/implications – The CF literature reminds us that these arrangements often fail because of opportunistic behavior. The poultry example shows that contracting is a useful institution when processor interests are closely aligned to that of the grower. This paper describes the circumstances under which this alignment is obtained. Originality/value – First, it adds to the small and growing body of work that estimates the income gains to contract growers. Second and going beyond existing work on developing countries, this paper also addresses the risk benefits from contracting. Thirdly, this paper estimates the income gains from contracting to the processing firms.","Comments":"","TypeName":"Journal, Article","Authors":"Bharat Ramaswami ; Pratap Singh Birthal; Joshi P K; ","ParentAuthors":"","DOI":"10.1108/17538250910953462","Keywords":"eppi-reviewer4\r\nAgriculture\nPoultry\nVertical marketing\nIndia, Andhra Pradesh, Outcome evaluation, evaluation, Income, one day old chick, Medicines, Primary report, risk,","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Bharat Ramaswami, Pratap Singh Birthal, and Joshi P K (2009) Grower heterogeneity and the gains from contract farming The case of Indian poultry. Indian Growth and Development Review 2(1), 56-74 DOI: 10.1108/17538250910953462"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122937,"Title":"Farm-Level Impacts of Vertical Coordination of the Food Supply Chain : Evidence from Contract Farming of Milk in India","ParentTitle":"Indian Journal of Agri.Economics","ShortTitle":"Birthal (2009)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2009","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"64","Pages":"481-496","Edition":"","Issue":"3","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Birthal et al. - 2009 - Farm-Level Impacts of Vertical Coordination of the Food Supply Chain Evidence from Contract Farming of Milk in.pdf","OldItemId":"61304861","Abstract":"","Comments":"","TypeName":"Journal, Article","Authors":"Birthal Pratap S; Jha Awadhesh K; Tiongco Marites M; Narrod Clare ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nproductivity, cost of production, Input prices, yield, profit, Punjab, Primary report, Outcome evaluation","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Birthal Pratap S, Jha Awadhesh K, Tiongco Marites M, and Narrod Clare (2009) Farm-Level Impacts of Vertical Coordination of the Food Supply Chain : Evidence from Contract Farming of Milk in India. Indian Journal of Agri.Economics 64(3), 481-496"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606022,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122938,"Title":"Efficiency and equity in contract farming : evidence from a case study of dairying in India","ParentTitle":"Quarterly Journal of International Agriculture","ShortTitle":"Birthal (2009)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2009","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"48","Pages":"363-378","Edition":"","Issue":"4","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Birthal - 2016 - Efficiency and equity in contract farming evidence from a case study of dairying in India.pdf","OldItemId":"61304862","Abstract":"Contract farming is emerging as an important form of vertical coordination in India, and its economic and social consequences are attracting considerable attention in the agri-food policy debates. In this paper, we have examined issues of efficiency and equity in contract farming of milk and arrive at the following conclusions. First, contract farming is more profitable than independent production mainly because of its potential to reduce marketing and transaction costs. Second, small-scale producers face higher marketing and transaction costs, and they derive significant benefits from participation in contract farming. Third, we do not find any difference in price realization by contract and independent producers, hence no extraction of monopsonistic rent by the firm","Comments":"","TypeName":"Journal, Article","Authors":"Birthal Pratap S; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\ncontract farming\nefficiency\nequity\ndairy\nIndia, Punjab, Outcome evaluation, primary report, profit, cost of production, Transaction cost","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Birthal Pratap S (2009) Efficiency and equity in contract farming : evidence from a case study of dairying in India. Quarterly Journal of International Agriculture 48(4), 363-378"},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122946,"Title":"Grower heterogeneity and the gains from contract farming : The case of Indian poultry","ParentTitle":"Indian Growth and Development Review","ShortTitle":"Birthal (2009)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2009","Month":"","StandardNumber":"1753825091","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"1-35","Edition":"","Issue":"June 2017","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Growth, Birthal, Ramaswami - 2009 - Grower heterogeneity and the gains from contract farming The case of Indian poultry.pdf","OldItemId":"61304863","Abstract":"This paper is an empirical analysis of the gains from contract farming in the case of poultry production in the state of Andhra Pradesh in India. The paper finds that contract production is more efficient than noncontract production. The efficiency surplus is largely appropriated by the processor. Despite this, contract growers still gain appreciably from contracting in terms of lower risk and higher expected returns. Improved technology and production practices as well as the way in which the processor selects growers are what make these outcomes possible. In terms of observed and unobserved characteristics, contract growers have relatively poor prospects as independent growers. With contract production, these growers achieve incomes comparable to that of independent growers.","Comments":"","TypeName":"Report","Authors":"Birthal Pratap ; Ramaswami Bharat ; PK Joshi ; ","ParentAuthors":"","DOI":"10.1108/17538250910953462","Keywords":"eppi-reviewer4\r\nAndhra Pradesh, primary report, outcome evaluation, income, risk, one day old chick, extension services","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Birthal Pratap, Ramaswami Bharat, and PK Joshi (2009) Grower heterogeneity and the gains from contract farming : The case of Indian poultry. : , 1-35 DOI: 10.1108/17538250910953462"},{"Codes":[{"AttributeId":9606511,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9641036,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122939,"Title":"Profitability analysis of contract and non-contract Japanese quail farming in Tamil Nadu","ParentTitle":"Indian Journal of Poultry Science","ShortTitle":"Chitrambigai (2016)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2016","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"51","Pages":"84-87","Edition":"","Issue":"1","Availability":"","URL":"","OldItemId":"61307317","Abstract":"The present study was undertaken to analyze the profitability of contract and non-contract Japanese quail farmers. This study was based on the primary data collected from thirty contract and thirty non-contract Japanese quail farmers in the western zone of Tamil Nadu. The profitability of contract and non-contract Japanese quail farmers was found out by analyzing the cost and returns of their farm. It was revealed in the study that the contract Japanese quail farmers were better off in their profitability by getting the high net return from their Japanese quail farm. There was a high initial investment requirement for non-contract Japanese quail farmers than contract Japanese quail farmers. The decreased production cost but increased net return was found in both types of Japanese quail farming with the increase in farm size. The profitability analysis revealed that the benefit-cost ratio of contract Japanese quail farming was higher than that of non-contract Japanese quail farming.","Comments":"","TypeName":"Journal, Article","Authors":"Chitrambigai K ; Pandian A Serma Saravana; Prabu  ; M  ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nContract, Cost of production, Economics, Investment, Japanese quail farming, Profit, Income, Economic evaluation, Primary report, Tamil Nadu, benefit-cost ratio","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Chitrambigai K, Pandian A Serma Saravana, Prabu , and M  (2016) Profitability analysis of contract and non-contract Japanese quail farming in Tamil Nadu. Indian Journal of Poultry Science 51(1), 84-87"},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122963,"Title":"COMPARATIVE STUDY OF CONTRACT FARMING WITH CONVENTIONAL FARMING OF POTATO IN SOUTHERN TRANSITION ZONE OF KARNATAKA: AN ECONOMIC ANALYSIS","ParentTitle":"","ShortTitle":"COMPARATIVE STUDY OF... (MALLIKARJUNA)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"    ","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810024827","OldItemId":"61307300","Abstract":"The study was undertaken to assess the economics of potato production under contract farming and conventional farming in Hassan district of Karnataka from a data of 30 sample size each for 2012-13 season. The data was analysed using simple tabular, production function and partial budgeting. The results revealed that Total production of potato in case of conventional farmers was low (40.43 Quintals) when compared to contract farmers (46.94 Quintals) and Net return over total cost was Rs 4088 in case of conventional farmers and Rs 10103 for contract farmers. The results of Cobb-Douglas production function gives that FYM (0.030) and machinery labour (0.0228) co-efficient were significant at five per cent in case of conventional farming and fertilizer (0.3569) and bul lock labour (0.36119) was significant at five per cent in case of contract farmers. The result for partial budgeting technique shows that extra cost incurred by contract farmers in growing of potato was Rs. 2189 than that of conventional farmers and the profit farmer get by entering into contract farming is Rs.7629. The benefit/Cost Ratio for contract farming is 3.48; means for every one rupee additional investment on potato contract farming the farmer is receiving Rs.2.48 as profit. The constraints faced by farmers was listed using Garrett ranking and the Wage rate of the labour was the major constraint faced by conventional farmers and case of contract farmers Labour availability was the major constraint. Therefore support should be given to contract farming to increase the farmer’s income.","Comments":"","TypeName":"Dissertation","Authors":"MALLIKARJUNA M N; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, Primary report, economic evaluation, profit, cost of production, seeds, extension services, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"MALLIKARJUNA M N (    ) COMPARATIVE STUDY OF CONTRACT FARMING WITH CONVENTIONAL FARMING OF POTATO IN SOUTHERN TRANSITION ZONE OF KARNATAKA: AN ECONOMIC ANALYSIS. , ."},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122943,"Title":"Contract farming of sweet corn in Dharwad District","ParentTitle":"","ShortTitle":"Contract farming of... (Gangadhar)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"    ","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810004257","OldItemId":"61307314","Abstract":"The study was conducted during 2014 in Dharwad district of Karnataka with a sample of 180. Of which 120 contract and 60 non-contract farmers were selected purposively to study the knowledge and opinion of contract and non-contract farmers about contract farming and their socio-economic profile. More than half of the contract (51.67%) and nearly half of non-contract farmers (45.00%) had medium level knowledge about contract farming and Large majority of contract (94.17%) and 68.33 per cent of non-contract farmers opinioned that contract farming increases the returns from farming. Majority of the contract and non-contract farmers belonged to middle age, educated up to middle school, had semi medium land holdings and medium family income. Whereas more than half of both the farmers had medium risk orientation and innovative proneness. Regarding cosmopoliteness, two third of the contract and non-contract farmers visited once in a fortnight and majority of them were visited for personal/domestic/entertainment purpose. Private agency was the most contacted agency for extension help and they contacted whenever a problem arised. More than half of contract and nearly half of non-contract farmers were found to participate in krishi mela organized by UAS Dharwad. Procurement and payment at farm gate (100.00%), increase in income (97.50%) and regular technical advices (94.17%) are the major benefits derived by the contract farming of sweet corn production. Major constraints in contract farming of sweet corn were low contract price (100.00%), price of third grade produce (97.50%), high rejection rate (93.33%) and lack of knowledge about grading (91.67%). And the major suggestions were Provision of good price for their grades and required to offer price for third grade produce (100.00% respectively) and minimum price variation between the grades (93.33%).","Comments":"","TypeName":"Dissertation","Authors":"Gangadhar P S; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, Primary report, need assessment, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Gangadhar P S (    ) Contract farming of sweet corn in Dharwad District. , ."},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606509,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606516,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122940,"Title":"Learning Contract Farming the Banana Way : A Case Study","ParentTitle":"International Journal of Rural Management","ShortTitle":"Dc (2011)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2011","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"7","Pages":"121-132","Edition":"","Issue":"1&2","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Dc, Kumar - 2011 - Learning Contract Farming the Banana Way A Case Study.pdf","OldItemId":"61304835","Abstract":"The success of contract farming is dependent on factors which are related to farmers, the market and government policies. The decision to start an agri- business based on contract farming is a complex one, and an entrepreneur has to consider many inter-dependent factors. The case presents a successful case of contract farming. However, the protagonist, who is planning to launch his own venture, faces many pertinent questions. Not only are the answers of those questions important, but the bases of those answers, and the level of confidence of protagonist too are equally crucial. The case helps in understanding and unrav- elling complexities of contract farming.","Comments":"","TypeName":"Journal, Article","Authors":"Dc Washington ; Kumar Niraj ; ","ParentAuthors":"","DOI":"10.1177/0973005212459831","Keywords":"eppi-reviewer4\r\nagri-business\nbanana\ncontract farming, Gujarat, Descriptive study, seeds, fertilizers, extension services","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Dc Washington, and Kumar Niraj (2011) Learning Contract Farming the Banana Way : A Case Study. International Journal of Rural Management 7(1&2), 121-132 DOI: 10.1177/0973005212459831"},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122941,"Title":"Contract Farming in Tomato : An Economic Analysis","ParentTitle":"Indian Journal of Agricultural Economics","ShortTitle":"Dileep (2002)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2002","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"57","Pages":"197-210","Edition":"","Issue":"2","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Dileep, Grover, Rai - 2002 - Contract Farming in Tomato An Economic Analysis.pdf","OldItemId":"61304848","Abstract":"","Comments":"","TypeName":"Journal, Article","Authors":"Dileep B K; Grover R K; Rai K N; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, economic evaluation, resource use efficiency, cost of cultivation, seeds, fertilizers, benefit cost ratio, profit, gross return, Haryana","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Dileep B K, Grover R K, and Rai K N (2002) Contract Farming in Tomato : An Economic Analysis. Indian Journal of Agricultural Economics 57(2), 197-210"},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122942,"Title":"Economics of Contract farming: A case study of Basmati Rice in western Utter Pradesh","ParentTitle":"","ShortTitle":"EMAL (2019)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2019","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"","OldItemId":"61307311","Abstract":"The 2015 global average paddy production was 746.9 million tonnes (496.0 million tonnes, milled basis). Asia, has the lead and major share in this production, (FAO, 2016). India is the world's second largest producer of Rice and first largest exporter of Basmati rice in the world. (APEDA, 2015). The agricultural marketing and agri-business system need institutions and innovations, to create and develop different marketing strategy for increasing in agricultural production. There are various marketing models, and among these are contract farming including those led by individual, or by farmer groups, or by cooperatives, and by various types of private processing sector that develop backward linkages with growers. Contract farming which was introduce for the first time by Pepsi Foods Ltd (PepsiCo) in 1989 which had built up tomato processing plant in Zahura in Hoshiarpur district of Punjab in India, had benefited the farmers. With the extrication, of the economy in the 90s, there has been a rebound in contract farming in India. Contract farming is done by household, and different national association in cereal crops, cash crops, oilseeds, fruits, vegetable crops and etc. The KRBL ltd started in 1993, is the largest exporter and rice miller in the word, with capacity on 195 MT/hr. and the total contract farmers network of its reaching more than 90,000. and the contracting agreements are often verbal and informal in nature, and there is no, any written contracts agreement which can provide legal protection for both farmers and as well for KRBL contract company. The impact of contract farming on yields of basmati rice is found to be positive. The total income is more for contract farmers, than non-contract farmers. Employment generation on contract farms is also found high especially for female labour compared to that on non-contract farms. The total input costs were slightly higher on contract farming than non-contract farming. The Allocative Efficiency Index indicated resources were being underutilized particularly for fertilizer, insecticide and irrigation are greater than one, and farmers had scope for increasing resources per hectar productivity by using more these factors in contract farming. For non-contract farmers the allocative efficiency index for human and machine labour was being underutilized and also greater than one and positive. The major constraints faced by contract and non-contract farmers in participation in contract farming were ranked and prioritized. In the case of contract farming, the delay in inputs supply was the most important constraint followed by lack of credit for crop production, labour scarcity, delay in payment of produce price by company, scarcity of water for irrigation, difficulty in meeting quality requirements, and distance from the company. The constraint expressed by non-contract farmers, were delay payment, followed by erratic power supply, lack of credit for crop production, distant from the company, difficulty in meeting quality requirements, lower price for crop produce, scarcity of water for irrigation and high cost of inputs. The analytical tools used for the study are: Chow Test, Dummy variable regression, Logit regression, Resource use efficiency and Garrett’s ranking.","Comments":"","TypeName":"Dissertation","Authors":"EMAL SHEGIWAL ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nUttar Pradesh, contract farming, primary report, economic evaluation, cost of production, efficiency, employment, seeds, fertilizers, extension services, return, profit, yield","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"EMAL SHEGIWAL (2019) Economics of Contract farming: A case study of Basmati Rice in western Utter Pradesh. , ."},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606509,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122973,"Title":"Profits from participation in contract farming : Evidence from cultivators of onion , okra and pomegranate in Maharashtra , India","ParentTitle":"30th international conference of Agricultural economist","ShortTitle":"G (2018)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2018","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"1-35","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Office, States, Corresponding - Unknown - Profits from participation in contract farming Evidence from cultivators of onion , okra and.pdf","OldItemId":"61304859","Abstract":"The paper attempts to quantify the benefits of contract farming on farmers’ income and investigates the determinants of participation in contract farming. This is based on a survey of 1,331 farmers engaged in cultivation of onion, okra and pomegranate from Maharashtra State in India. Descriptive statistics, regression analysis (using instrumental variable) and propensity score matching have been used in the analysis. The study reveals that contract farming, by connecting smallholders to high- end international market, ensures them with higher returns to the tune of Rs 14.5 per kilogram over independent farmers. Access to institutional credit, extension services, farm-size, ownership of transport, and migration significantly affected farmers’ participation in contract farming. The empirical evidence on benefits from contract farming in high value export commodities should induce conducive policies for promotion and upscaling of contract farming in India","Comments":"","TypeName":"Conference Proceedings","Authors":"G Tripathi ; A Kumar ; D Roy ; P Joshi ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nContract farming, Primary report, outcome evaluation, profit, net returns, cost of production, Maharashtra","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"G Tripathi, A Kumar, D Roy, and P Joshi (2018) Profits from participation in contract farming : Evidence from cultivators of onion , okra and pomegranate in Maharashtra , India. In: 30th international conference of Agricultural economist, . , p1-35"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122944,"Title":"Impact of contract farming for basmati rice in the Punjab state of India","ParentTitle":"CONTRACT FARMING for inclusive market access","ShortTitle":"Goel (2014)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2014","Month":"","StandardNumber":"9789251080610","City":"","Country":"","Publisher":"FAO","Institution":"","Volume":"","Pages":"165-182","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Silva, Rankin - Unknown - for inclusive market access Edited by.pdf","OldItemId":"61304847","Abstract":"","Comments":"","TypeName":"Book, Chapter","Authors":"Goel Veena ; ","ParentAuthors":"Carlos A da Silva, Marlo Rankin; ","DOI":"","Keywords":"eppi-reviewer4\r\nPunjab, Contract farming, primary report, economic evaluation, productivity, income, price risk, seeds, extension services, technology","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Goel Veena (2014) Impact of contract farming for basmati rice in the Punjab state of India. In: Carlos A da Silva, and Marlo Rankin, editors. CONTRACT FARMING for inclusive market access. : FAO, p165-182"},{"Codes":[{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122945,"Title":"Comparative Economics of Contract and Non-contract Farming of Potato in Comparative Economics of Contract and Non-contract Farming of Potato in Gujarat","ParentTitle":"Economic Affairs","ShortTitle":"Gondalia (2017)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2017","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"62","Pages":"683-690","Edition":"","Issue":"4","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Gondalia, Zala, Bansal - 2017 - Comparative Economics of Contract and Non-contract Farming of Potato in Comparative Economics of Contrac.pdf","OldItemId":"61304846","Abstract":"To study the comparative economics of contract and non-contract farming of potato in Gujarat state, a sample of 120 potato growers comprising 60 each from contract and non-contract were selected. The Cost Concept (CACP approach) was used to work out various costs and “t” test was used for testing their statistical significance. The results revealed that the cost of cultivation (Cost C2 ) was higher on contract farms (` 185435 per ha) when compared to the non-contract farms, (` 154930 per ha) due to higher cost of labor, manures, seeds and chemical fertilizers. The average production of potato was higher on contract farms (399.92 q/ha) than on the non-contract farms (303.83 q/ha). This might be due to the use of better variety, proper use of inputs and better production technology as specified by the contracting firm. The average price received by the farmers was higher on the contract farms (` 830.29 per quintal) when compared to the non-contract farms (` 808.17 per quintal). The net returns received over Cost C2 was higher on contract farms (` 146615 per ha) when compared to the non-contract farms (` 90620 per ha). The yield uncertainty ratio was lower on the contract farms (0.1806) than the non-contract farms (0.4588). Similarly, the price uncertainty ratio was lower on contract farms (0.0162) than the non-contract farms (0.1358). In nutshell, these results clearly revealed that the contract farming in potato was economically more profitable and less risky when compared to traditional non-contract farming. Keywords:","Comments":"","TypeName":"Journal, Article","Authors":"Gondalia Vasantkumar K; Zala Yogendra ; Bansal Rachana ; ","ParentAuthors":"","DOI":"10.5958/0976-4666.2017.00083.3","Keywords":"eppi-reviewer4\r\ncontract farming, primary report, economic evaluation, profit, price risk, \nyield, price realized, cost of cultivation, Gujarat","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Gondalia Vasantkumar K, Zala Yogendra, and Bansal Rachana (2017) Comparative Economics of Contract and Non-contract Farming of Potato in Comparative Economics of Contract and Non-contract Farming of Potato in Gujarat. Economic Affairs 62(4), 683-690 DOI: 10.5958/0976-4666.2017.00083.3"},{"Codes":[{"AttributeId":9606505,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122930,"Title":"CONTRACT FARMING OF SUGARCANE IN DHENKANAL DISTRICT","ParentTitle":"","ShortTitle":"Gyana (2013)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"14/09/2021","EditedBy":"Manjisha Sinha","Year":"2013","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/95375","OldItemId":"61307321","Abstract":"A study was conducted on the Contract farming of sugarcane in Dhenkanal district. Sugarcane is considered as one of the important cash crops grown in Orissa. Dhenkanal is one of the most important industrial districts of Orissa with numerious factories; the most important being Shakti sugar which is the largest sugar factory in the private sector to boost the sugar cultivation in the district and in the adjoining districts.A block viz. Dhenkanal sadar of the district was purposively chosen having maximum contract farmers for sugarcane. The farmers were stratified as contract and non contract farmers, which were further sub-stratified into three size groups i.e. Marginal Farmer (below 1 ha), Small Farmer (1-2 ha) and Large Farmer (more than 2 ha). A total number of 24 farmers each from contract and non contract farmers were randomly selected representing all the size groups from the district following probability proportion to size (PPS) method. Thus a total number of 48 farmers were selected from the district for final analysis. The operational cost was found to be higher in case of contract farmers for all categories of farmers. Among the contract farmers, the cost A1 was highest (Rs.64, 445) in case of large farmers with followed by small and marginal with (Rs.63, 185) and (Rs.61, 057.5) respectively. Over all the cost A1, for contract farmers was Rs.50, 006.8, variables of cost A1, Human Labour accounted for 54.50 per cent of total followed by seed, fertilizer, irrigation and manure respectively. Among the non contract farmers, cost A1 was found to be highest for large farmers (Rs.54, 502.5) followed by small and marginal amounting (Rs.53, 290) and (Rs.47, 335) respectively, over all the cost of production was Rs.51, 709.7. Among the non-contract farms, 59.32 percent of the total cost A1 was incurred for human labor only followed by other input costs. Overall the operational cost incurred by the contract farmers was found to be Rs.11186.6 higher than that of non contract farmers because of the use of improved technology, recommended doses of fertilizer. The Cobb-Douglas production function for sugarcane indicated that the input variables like human labour, pest control and irrigation were found to be significant for contract farmers. The coefficient of multiple regressions R2 varied from 0.995 to 0.997 indicating 95 to 97 variations in the output was explained by the inputs under consideration. On contract farms, delay in payment of produce the most important constraint followed by lack of credit for crop production and scarcity of water for irrigation with corresponding Garrett score 60, 56.8 & 54.8 respectively. On non-contract farms, scarcity of water for ratoon crop was the most important constraint followed by frequent power cutting & lack of credit for crop production with their corresponding Garrett score of 57.4, 54.6 & 53.0 respectively. Contracting companies provide quality inputs such as seeds and plant protection chemicals to the farmers at their farm gate coupled with the technical advice on production aspects. Thus contract farming helped small farmers to improve their income levels.","Comments":"","TypeName":"Dissertation","Authors":"Gyana Ranjan Majhi; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nCost of production, Orissa, Primary Report, Seeds, Extension services, Income, Economic eveluation, Returns","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Gyana Ranjan Majhi (2013) CONTRACT FARMING OF SUGARCANE IN DHENKANAL DISTRICT. , ."},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122947,"Title":"Group contracts and sustainability - Experimental evidences from smallholder rice seed production","ParentTitle":"30th international conference of Agricultural economist","ShortTitle":"Johny (2018)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2018","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Johny, Veettil, Yashodha - Unknown - Group contracts and sustainability - Experimental evidences from smallholder rice seed production.pdf","OldItemId":"61304842","Abstract":"Contract farming in seed production has played a great instrumental role to bring private investment into seed research and production. Poor functioning of institutions hinders the full potential benefits of seed contracts to reach to producers. Seed producers are the most important part of the seed supply chain and thereby the present study attempt to analyze the producer's preference for group contract and its impact on welfare of actors in the seed value chain. We propose two types of group contracts, viz, contract B (company-organizer-seed producers group (SPG)) and C (company-SPG). We carried out an economic experiment using real producers and organizers of the seed contracts, where producers face a choice between an existing contract and either of proposed group contracts. The experiment consists of two treatments, i) concealed and revealed price information and ii) presence and absence of local organizer in producer sessions. We find that preference for contract B is higher than contract C and existing contract. Contract B shows higher price bargaining under the concealed price information compared to revealed treatment. We find group life of 3.78 periods and more than half of the groups (53%) survived throughout the five rounds indicating a very high sustainability.","Comments":"","TypeName":"Conference Proceedings","Authors":"Johny J ; Veettil P C; Yashodha Y ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nAndhra Pradesh, Telangana, Primary report, need assessment, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Johny J, Veettil P C, and Yashodha Y (2018) Group contracts and sustainability - Experimental evidences from smallholder rice seed production. In: 30th international conference of Agricultural economist, . , p"},{"Codes":[{"AttributeId":9606512,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122948,"Title":"Diversification and Its Impact on Smallholders : Evidence from a Study on Vegetable Production *","ParentTitle":"Agricultural Economics Research Review","ShortTitle":"Joshi (2006)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2006","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"19","Pages":"219-236","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Joshi, Joshi, Birthal - 2006 - Diversification and Its Impact on Smallholders Evidence from a Study on Vegetable Production.pdf","OldItemId":"61304841","Abstract":"There is an emerging concern about the viability of small farm agriculture, particularly in the context of on-going process of globalization. It is contended that viability of small farms can be improved through diversification of agriculture into higher-value crops like fruits and vegetables. This paper has assessed the impact of diversification of agriculture towards vegetables on farm income and employment using household level information from the Indian state of Uttar Pradesh. The results clearly reveal that vegetable production is more profitable and labour-intensive, therefore it fits well in the small farm production systems. The smallholders are relatively more efficient in production and own more family labour in contrast to large farmers. Vegetable production is the emerging sector in agricultural diversification that would augment income of smallholders and generate employment opportunities in rural areas. Women are also benefited as the vegetable production engages relatively higher women labour in various operations. However, prevailing constraints do not allow smallholders to fully expropriate the emerging opportunities in vegetable production. Major constraints in vegetable production are lack of assured markets and a well-developed seed sector. Since vegetables are perishable in nature, lack of efficient marketing system and appropriate infrastructure results in huge post-harvest losses. Further, non-availability of improved and good quality seeds reduces the profitability and increases production risk. Other important factors that restrict expansion of area under vegetables are higher price and yield risks as compared to cereals and low marketable surplus that increases transaction costs. The vegetable prices are highly volatile, which severely affect the profitability in the event of marginal increase in their supply. Low volume of marketable surplus also adversely affects the bargaining power of smallholders and thus results in realizing lower prices. The possible solution for overcoming this is through developing institutional arrangements that strengthen farm- firm linkages. Contract farming is one such arrangement that helps smallholders to overcome the constraints in vegetable production.","Comments":"","TypeName":"Journal, Article","Authors":"Joshi P K; Joshi Laxmi ; Birthal Pratap S; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nUttar Pradesh, Primary report, economic evaluation, income, profit, risk, seeds,  transaction cost, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Joshi P K, Joshi Laxmi, and Birthal Pratap S (2006) Diversification and Its Impact on Smallholders : Evidence from a Study on Vegetable Production *. Agricultural Economics Research Review 19, 219-236"},{"Codes":[{"AttributeId":9606509,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122950,"Title":"Inputs and Services Delivery System under Contract Farming : A Case of Broiler Farming","ParentTitle":"Agricultural Economics Research Review","ShortTitle":"Kalamkar (2012)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2012","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"25","Pages":"515-521","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kalamkar - 2012 - Inputs and Services Delivery System under Contract Farming A Case of Broiler Farming §.pdf","OldItemId":"61304840","Abstract":"The paper has analyzed production-related aspects of broiler farming under contract and independent management, and has examined inputs and services provision arrangements. About two-thirds of the contracts are of long duration of three years, and the remaining are of two years or eleven months duration. Surprisingly, none of the contract farmer possesses a copy of the agreement with him. The average net return per kg of live weight as well as per bird has been found higher in non-contract than contract farmers. The average net returns per bird increases with increase in the size of the farm for both the groups. Despite contract for supply of inputs and sale of output, contract farmers face problems like delay in supply of inputs, high feed prices, delay in lifting the produce, delay in payment, low price, and sometime even rejection of output. Beside these problems, low growing charges, delay in providing chicks, delay in providing veterinary services, high visiting charges and deduction of tax at source are some other problems being faced by the contract farmers","Comments":"","TypeName":"Conference Proceedings","Authors":"Kalamkar S S; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\ncontract farming, inputs delivery, Primary report, Economic evaluation, Cost of production, profit, income, constraints, Maharashtra","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kalamkar S S (2012) Inputs and Services Delivery System under Contract Farming : A Case of Broiler Farming. In: Agricultural Economics Research Review, . , p515-521"},{"Codes":[{"AttributeId":9606512,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122951,"Title":"Impact of contract farming on basmati rice ( Oryza sativa ) in India","ParentTitle":"Indian Journal of Agricultural Sciences","ShortTitle":"Kar (2020)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2020","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"90","Pages":"1282-1285","Edition":"","Issue":"7","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kar, Shegiwal, Kumar - 2020 - Impact of contract farming on basmati rice ( Oryza sativa ) in India.pdf","OldItemId":"61304839","Abstract":"India is world's second largest producer of rice and largest exporter of basmati rice in the world. Total paddy production in the year 2018-19, was 115.6 million tonnes and basmati rice output was 5.31 million tonnes. Basmati rice export is projected to hit a record level of ` 30000 crore or nearly $4.28 billion this season. The largest exported basmati variety is Pusa 1121 and the procurement price was ` 35000-38000 a tonne in the year of 2018-19 which was 8.5% higher than the price in 2017-18. A study was undertaken to analyse the contract farming dealing with Pusa Basmati 1121 and its economic impact on farmers in Ghaziabad district of Uttar Pradesh during 2017-18. The findings of the study reveal that the impact of contract farming on yield of basmati rice was found to be positive. The total income was more for contract farmers than non-contract farmers. Total input costs were slightly higher on contract farm than non-contract farm. Major factors responsible for farmers’ participation in the contract farming were found to be company guidance for scientific method of cultivation, higher price for produce received from contracting firm, assured purchase by contracting firm and age of the farmer. It is suggested that agricultural marketing and agri-business system needs institutions and innovations, to create and develop different marketing strategy for further","Comments":"","TypeName":"Journal, Article","Authors":"Kar Amit ; Shegiwal Emal ; Kumar Pramod ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nUttar Pradesh, contract farming, primary report, economic evaluation, cost of production, income, seeds, technologies, gross returns, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kar Amit, Shegiwal Emal, and Kumar Pramod (2020) Impact of contract farming on basmati rice ( Oryza sativa ) in India. Indian Journal of Agricultural Sciences 90(7), 1282-1285"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122952,"Title":"Can Contarct Farming Double Farmer's Income?","ParentTitle":"Economic and Political weekly","ShortTitle":"Kaur (2018)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2018","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"53","Pages":"68-73","Edition":"","Issue":"51","Availability":"","URL":"file:///G:/Articles/Contract farming/Metaanalysis/Kaur and Singla 2018.pdf","OldItemId":"61304852","Abstract":"Following its mandate to double farmers’ income by 2022, the central government has enacted a separate model contract farming act in 2018 based on the perception that contract farming is one of the several pathways for doubling farm income. However, findings from primary surveys in Moga, Tarn Taran and Amritsar districts in Punjab, reveal that despite bringing in new crops, technologies and markets for farmers, contract farming excludes the smallholder farmers. Unless such arrangements can protect the interests of the smallholders who constitute almost four-fifth of India’s farming population, doubling farm income will remain elusive.","Comments":"","TypeName":"Journal, Article","Authors":"Kaur P ; Singla Naresh ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPunjab, Primary report, economic evaluation, income,","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kaur P, and Singla Naresh (2018) Can Contarct Farming Double Farmer's Income?. Economic and Political weekly 53(51), 68-73"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[{"ItemDocumentId":681438,"TextFrom":0,"TextTo":0,"Text":"Page 4:\n[¬s]\"seeds[¬e]\"","IsFromPDF":true,"DocTitle":"Kharumnuid2017.pdf","ItemArm":""}]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122953,"Title":"An assessment of contract farming system for potato seed production in Punjab-A case study An assessment of contract farming system for potato seed production in Punjab – A case study","ParentTitle":"Indian J. Horticulture","ShortTitle":"Kharumnuid (2017)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2017","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"74","Pages":"453-457","Edition":"","Issue":"3","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kharumnuid et al. - 2017 - An assessment of contract farming system for potato seed production in Punjab-A case study An assessment of c.pdf","OldItemId":"61304838","Abstract":"The study was conducted to assess the contract farming system of potato seed production in Punjab with a sample of 30 contract and 30 non-contract farmers from Jalandhar district of Punjab. The major motivating factors identified for participating in the contract farming were assured price, diversification, access to assured market, extension services etc. There was no participation of marginal and small farmers in contract farming. The average net income of contract farmers was about 12 per cent higher than non-contract farmers. The major constraints in potato seed contract farming were pest and disease attacks, non-availability of labor during peak period, difficulty in meeting quality requirement etc. The study suggests that government, non-governmental organizations and other related agencies should play an active role in the contractual arrangement","Comments":"","TypeName":"Journal, Article","Authors":"Kharumnuid P ; Sarkar Sujit ; Singh Premlata ; Priya Satya ; Tomar B S; Singh Dhiraj K; ","ParentAuthors":"","DOI":"10.5958/0974-0112.2017.00088.3","Keywords":"eppi-reviewer4\r\nContract farming, Punjab, Primary report, economic evaluation, profit, yield,  cost of production, price realized, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kharumnuid P, Sarkar Sujit, Singh Premlata, Priya Satya, Tomar B S, and Singh Dhiraj K (2017) An assessment of contract farming system for potato seed production in Punjab-A case study An assessment of contract farming system for potato seed production in Punjab – A case study. Indian J. Horticulture 74(3), 453-457 DOI: 10.5958/0974-0112.2017.00088.3"},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633220,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122954,"Title":"Mode of Operation and Performance of Contract Farming of Cottonseed in Haryana","ParentTitle":"Agricultural Economics Research Review","ShortTitle":"Kumar (2007)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2007","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"20","Pages":"99-116","Edition":"","Issue":"June","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar, Chakarvarty, Chand - 2007 - Mode of Operation and Performance of Contract Farming of Cottonseed in Haryana.pdf","OldItemId":"61304826","Abstract":"The quality of cottonseed matters most for the successful product development. The quality cottonseed production is monitored by the Haryana State Seed Certification Agency in the state. The study has reviewed the prevailing contract cotton farming models; has studied mode of operation of cotton contractual arrangements; has analyzed the production matrix, growth and contributions; and has discerned and quantified variations in intensive structure of public and private seed firms. It has used both primary and secondary data. Appropriate statistical tools, viz. exponential growth model, index, etc., have been used to study the data. All categories of farmers have been brought together under the management of private seed agency for production of cottonseed of a single variety on a large homogeneous block. Contract cotton farming has fully vetted the legal agreements with their growers. The public and private agencies pay incentive price to farmers which is higher than the prevailing market price. Farmers of private agency are free from the intricacies of input and output markets, receive all technology and technical know-how and have facilities for production and consumption loans, whereas farmers of public agency are trailed far behind in terms of these benefits. Private agency has flourished at the expanse of public agency since contract cotton is incentivised by private contractors under flexible and farmer- friendly production regime. The latest production technology, strong capital and management base of private seed agency have left the public agency behind in the competitive race. The study has concluded that favourable changes in socio-economic and legal framework of government policies have to be encouraged for the active participation of private sector in cottonseed business and contract cottonseed farming has emerged as a viable alternative farming in the post-WTO regime.","Comments":"","TypeName":"Journal, Article","Authors":"Kumar Shiv ; Chakarvarty Kavita ; Chand Puran ; Dabas J ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nHaryana, primary report, economic evaluation, price risk","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Shiv, Chakarvarty Kavita, Chand Puran, and Dabas J (2007) Mode of Operation and Performance of Contract Farming of Cottonseed in Haryana. Agricultural Economics Research Review 20(June), 99-116"},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122955,"Title":"Contract Farming : Problems , Prospects and its Effect on Income and Employment","ParentTitle":"Agricultural Economics Research Review","ShortTitle":"Kumar (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"21","Pages":"243-250","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar, K - 2008 - Contract Farming Problems , Prospects and its Effect on Income and Employment.pdf","OldItemId":"61304843","Abstract":"This farm-level study conducted in the Tumkur district of Karnataka state has reported the effect of contract farming on income and employment generation and has identified constraints in and prospects of contract farming. Both income and employment generation have been found higher, almost double, on contract than non-contract farms. The study has observed dominance of female labour on both types of farms. Delayed payment for crop produce, lack of credit for crop production, scarcity of water for irrigation, erratic power supply and difficulty in meeting quality requirements have been found to be the major constraints faced by contract farmers. The scarcity of water for irrigation, erratic power supply, lack of credit for crop production, and lower price for crop produce have been identified as major constraints of non-contract farmers. The major constraints expressed by the contracting agencies in expanding contract farming include violation of terms and conditions by farmers, lack of proper management by the company, frequent price fluctuations in international markets, and scarcity of transport vehicles during peak periods. Introduction","Comments":"","TypeName":"Journal, Article","Authors":"Kumar Jagdish ; K Prakash Kumar; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nprimary report, economic evaluation, income, constraints, employment generation, Karnataka","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Jagdish, and K Prakash Kumar (2008) Contract Farming : Problems , Prospects and its Effect on Income and Employment. Agricultural Economics Research Review 21, 243-250"},{"Codes":[{"AttributeId":9606511,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122962,"Title":"Perceived Constraints of Contract Farmers and Apprehensions of Non-Contract Farmers in Tamil Nadu","ParentTitle":"Pusa Agricultural Sciences","ShortTitle":"Kumar (2009)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2009","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"35","Pages":"75-78","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/37864","OldItemId":"61307316","Abstract":"","Comments":"","TypeName":"Journal, Article","Authors":"Kumar S Arun; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, need assessment, TamilNadu","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar S Arun (2009) Perceived Constraints of Contract Farmers and Apprehensions of Non-Contract Farmers in Tamil Nadu. Pusa Agricultural Sciences 35, 75-78"},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122956,"Title":"Characteristics and Determinants of Contract Design of Wheat Seed Farming in India : A Basis of Decision Making","ParentTitle":"Ind. Jn. of Agricultural Economics","ShortTitle":"Kumar (2010)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2010","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"65","Pages":"621-638","Edition":"","Issue":"4","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar et al. - 2010 - Characteristics and Determinants of Contract Design of Wheat Seed Farming in India A Basis of Decision Making.pdf","OldItemId":"61304825","Abstract":"","Comments":"","TypeName":"Journal, Article","Authors":"Kumar Shiv ; Chand Puran ; Dabas J P S; Singh Harvinder ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nHaryana, primary report, economic evaluation, income, seeds, extension services.","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Shiv, Chand Puran, Dabas J P S, and Singh Harvinder (2010) Characteristics and Determinants of Contract Design of Wheat Seed Farming in India : A Basis of Decision Making. Ind. Jn. of Agricultural Economics 65(4), 621-638"},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122957,"Title":"Contractual Arrangements and Enforcement in India : The Case of Organic Basmati Paddy Farming","ParentTitle":"Indian Journal of Agriculture Economics","ShortTitle":"Kumar (2013)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2013","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"68","Pages":"449-456","Edition":"","Issue":"3","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar et al. - 2013 - Contractual Arrangements and Enforcement in India The Case of Organic Basmati Paddy Farming.pdf","OldItemId":"61304824","Abstract":"The study analyses the empirical relationship between contractual arrangements and their enforcement in organic basmati paddy farming. For the purpose a list of agribusiness firms operating in Sonepat, Karnal, Kaithal and Kurukshetra districts of Haryana state were collected from the official records of their respective markets. The data on contents of contractual arrangements and their enforcement were collected from 40 agribusiness firms operating contract farming schemes in traditional basmati rice belt of the state pertaining to the year 2011-12. Binary logit model was used to capture the determinants of contract fulfilment rates. The study concludes that the provisions in designs of contract, viz., social capital, assured price in advance, bonus clause and specific investment for infrastructure creation for carrying out production and post-harvest operations in contract organic basmati scheme are likely to promote contract fulfilment rate by the farmers. Contractual arrangements are enforced through a mix of quid pro quo, altruism, and adherence to social norms.","Comments":"","TypeName":"Journal, Article","Authors":"Kumar Shiv ; Chandra Subhash ; Singh D R; Chaudhary Khyali Ram; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nHaryana, primary report, economic evaluation, price realized, income","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Shiv, Chandra Subhash, Singh D R, and Chaudhary Khyali Ram (2013) Contractual Arrangements and Enforcement in India : The Case of Organic Basmati Paddy Farming. Indian Journal of Agriculture Economics 68(3), 449-456"},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122958,"Title":"Resource Provision , Productivity and Contract Farming A Case Study of Punjab.","ParentTitle":"Contract Farming in India: A Resource Book","ShortTitle":"Kumar (2016)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2016","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"IFPRI","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"December","Availability":"","URL":"http://www.ncap.res.in/contract_ farming/index.htm file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar, Change - 2016 - Resource Provision , Productivity and Contract Farming A Case Study of Punjab.pdf","OldItemId":"61304833","Abstract":"","Comments":"","TypeName":"Book, Chapter","Authors":"Kumar Parmod ; ","ParentAuthors":"Gulati Ashok P.K. Joshi; Maurice L ; es  ; ","DOI":"","Keywords":"eppi-reviewer4\r\nSecondary report, Economic evaluation, productivity, seeds, extension services, Punjab","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Parmod (2016) Resource Provision , Productivity and Contract Farming A Case Study of Punjab.. In: Gulati Ashok P.K. Joshi, Maurice L, and es , editors. Contract Farming in India: A Resource Book. : IFPRI, p"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122959,"Title":"Contract Farming through Agribusiness Firms and State Corporation","ParentTitle":"Economic and Political weekly","ShortTitle":"Kumar (2016)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2016","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"41","Pages":"5367-5375","Edition":"","Issue":"52","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Weekly - 2016 - Contract Farming through Agribusiness Firms and State Corporation.pdf","OldItemId":"61304834","Abstract":"In order to overcome declining productivity and falling farm incomes in Punjab, the Johl Committee recommended that contract farming be undertaken to reduce costs and provide farmers with better inputs and technical know-how, thereby increasing agricultural yield. This paper compares direct contracts with agribusiness firms and indirect contracts with these firms through the state. Direct contract farming is observed to operate effectively, with positive outcomes for the farmers irrespective of the farm size. Indirect contracts seem to favour only those farmers with larger farms, who do not benefit as much as direct contract farmers","Comments":"","TypeName":"Journal, Article","Authors":"Kumar Parmod ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, economic evaluation, productivity, cost of production, gross return, Profit, Punjab","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Parmod (2016) Contract Farming through Agribusiness Firms and State Corporation. Economic and Political weekly 41(52), 5367-5375"},{"Codes":[{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122960,"Title":"Contract Farming through Agribusiness Firms and State Corporation A Case Study in Punjab","ParentTitle":"Economic and Political Weekly","ShortTitle":"Kumar (2017)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2017","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"41","Pages":"5367-5375","Edition":"","Issue":"52","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar, Change - 2017 - Contract Farming through Agribusiness Firms and State Corporation A Case Study in Punjab.pdf","OldItemId":"61304832","Abstract":"In order to overcome declining productivity and falling farm incomes in Punjab, the Johl Committee recommended that contract farming be undertaken to reduce costs and provide farmers with better inputs and technical know-how, thereby increasing agricultural yield. This paper compares direct contracts with agribusiness firms and indirect contracts with these firms through the state. Direct contract farming is observed to operate effectively, with positive outcomes for the farmers irrespective of the farm size. Indirect contracts seem to favour only those farmers with larger farms, who do not benefit as much as direct contract farmers. PARMOD","Comments":"","TypeName":"Journal, Article","Authors":"Kumar Parmod ; ","ParentAuthors":"","DOI":"10.2307/4419083","Keywords":"eppi-reviewer4\r\nPunjab, seeds, extension services, economic evaluation, cost of production","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Parmod (2017) Contract Farming through Agribusiness Firms and State Corporation A Case Study in Punjab. Economic and Political Weekly 41(52), 5367-5375 DOI: 10.2307/4419083"},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122961,"Title":"Contract Farming , Productivity and Fertilizer Usage Empirical Evidence from Specialty Crop Production","ParentTitle":"","ShortTitle":"Kumar (2018)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2018","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"1-23","Edition":"","Issue":"November","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Kumar, Souza - 2018 - Contract Farming , Productivity and Fertilizer Usage Empirical Evidence from Specialty Crop Production.pdf","OldItemId":"61304853","Abstract":"This study investigates the impact of contract farming (CF) in baby corn production on yield, irrigation costs, fertilizer costs and usage of chemical fertilizer. We find that adoption of CF by baby corn smallholders, after controlling for characteristics of both control and treatment groups, leads to higher yields and lower spending on fertilizers and irrigation. Additionally, CF in baby corn farming leads to a reduction in the use of chemical fertilizers (Urea and DAP). Thus, CF intervention benefits the livelihood of smallholders, reduces environmental degradation and reduces stress on groundwater without compromising yield. Keyword:","Comments":"","TypeName":"Report","Authors":"Kumar Anjani ; Souza Alwin D; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, outcome evaluation, yield, cost of production, return, Punjab, Haryana, yield, cost of production","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Kumar Anjani, and Souza Alwin D (2018) Contract Farming , Productivity and Fertilizer Usage Empirical Evidence from Specialty Crop Production. : , 1-23"},{"Codes":[{"AttributeId":9606513,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122964,"Title":"Potential of contract farming for cultivation of Capsicum in U.S. Nagar of Uttarakhand","ParentTitle":"","ShortTitle":"Mathur (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810082073","OldItemId":"61307308","Abstract":"","Comments":"","TypeName":"Dissertation","Authors":"Mathur Ankur ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report,  Uttarakhand, economic evaluation, cost of production, income, profit, return, Seeds, extension services, benefit cost ratio,","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Mathur Ankur (2008) Potential of contract farming for cultivation of Capsicum in U.S. Nagar of Uttarakhand. , ."},{"Codes":[{"AttributeId":9606509,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122965,"Title":"Featured Article Production Risks , Risk Preference and Contract Farming : Impact on Food Security in India","ParentTitle":"Applied Economic Perspectives and Policy","ShortTitle":"Mishra (2018)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2018","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"40","Pages":"353-378","Edition":"","Issue":"3","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Mishra et al. - 2018 - Featured Article Production Risks , Risk Preference and Contract Farming Impact on Food Security in India.pdf","OldItemId":"61304854","Abstract":"This article reviews the literature on contract farming (CF) in India and assesses the impact of smallholders’ perceived production risks on the adoption of CF; the impact ofCF on smallholders’ food security; and its impact on employment generation in their farming enterprises. We also show the impact ofthe outcome var- iables by risk preference of smallholders. Using farm-level data and endogenous switching regression methods, this study presents three key findings. First, the per- ception of weather and pest risk, access to irrigation facilities, extension visits, and access to institutional credit are the main drivers ofCF adoption. Second, CF adop- tion increases food security and varies with the revealed risk preference ofsmallhold- ers, and risk-seeking smallholders tend to gain higher food security. Third, regardless ofrevealed risk preferences, smallholders who did not adopt CF benefit from adoption by reducing their labor requirements, with no significant losses in yield. Key","Comments":"","TypeName":"Journal, Article","Authors":"Mishra Ashok K; Kumar Anjani ; Joshi Pramod K; Souza Alwin D; ","ParentAuthors":"","DOI":"10.1093/aepp/ppy017","Keywords":"eppi-reviewer4\r\nPrimary report, outcome evaluation,  employment, yield, food security, \nrisk, Maharashtra","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Mishra Ashok K, Kumar Anjani, Joshi Pramod K, and Souza Alwin D (2018) Featured Article Production Risks , Risk Preference and Contract Farming : Impact on Food Security in India. Applied Economic Perspectives and Policy 40(3), 353-378 DOI: 10.1093/aepp/ppy017"},{"Codes":[{"AttributeId":9606513,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122966,"Title":"How can organic rice be a boon to smallholders ? Evidence from contract farming in India","ParentTitle":"Food Policy","ShortTitle":"Mishra (2018)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2018","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"75","Pages":"147-157","Edition":"","Issue":"February","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Mishra et al. - 2018 - How can organic rice be a boon to smallholders Evidence from contract farming in India.pdf","OldItemId":"61304864","Abstract":"Demand for organic basmati rice (OBR), both at home and abroad, coupled with policy reforms have given rise to contract farming (CF) production in India. OBR production, however, is highly susceptible to weather and pest risks. This study investigates the impact of smallholders’ perceived production risks on their adoption of CF in OBR farming. We also assess the impact of CF in OBR production on yields, prices received, and the livelihood of OBR producers. We use farm-level data from smallholder organic basmati rice farms in India and the endogenous switching regression method to account for heterogeneity. Although CF in OBR led to lower yields, it increased the prices producers received and improved the livelihood of OBR producers. The impact of CF varied with farmers’ revealed risk attitudes. Risk-loving OBR growers with CF experienced the highest loss in yields, and risk- averse OBR growers with CF received the highest prices. We find that the OBR growers who did not adopt CF would benefit from adopting it, regardless of their risk attitudes, especially when it comes to prices received and livelihood.","Comments":"","TypeName":"Journal, Article","Authors":"Mishra Ashok K; Kumar Anjani ; Joshi Pramod K; Souza Alwin D; Tripathi Gaurav ; ","ParentAuthors":"","DOI":"https://doi.org/10.1016/j.foodpol.2018.01.007","Keywords":"eppi-reviewer4\r\nContract farming, Primary report, outcome evaluation, \nYield, Punjab, Haryana, price risk, Uttarakhand, price realised, food security","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Mishra Ashok K, Kumar Anjani, Joshi Pramod K, Souza Alwin D, and Tripathi Gaurav (2018) How can organic rice be a boon to smallholders ? Evidence from contract farming in India. Food Policy 75(February), 147-157 DOI: https://doi.org/10.1016/j.foodpol.2018.01.007"},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122967,"Title":"Technology and Managerial Gaps in Contract Farming : The Case of Specialty Crop Production","ParentTitle":"Journal of Agricultural and Resource Economics:","ShortTitle":"Mishra (2020)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2020","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"5502","Pages":"","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Mishra, Mayorga, Kumar - 2020 - Technology and Managerial Gaps in Contract Farming The Case of Specialty Crop Production.pdf","OldItemId":"61304855","Abstract":"The study uses a stochastic frontier approach corrected for self-selection to separate technology and managerial gaps between the treatment and control groups of smallholders in baby corn production in India. Secondly, the study assesses the impact of CF on output prices, profitability, and resource usage—fertilizer and marketing expenses. Findings show that technical efficiency is consistently higher for contract farmers than independent farmers. Also, we find that significant technology and managerial gaps exist between contracted and independent growers. Results show that baby corn producers who are engaged in CF, after controlling for characteristics of both control and treatment groups, receive lower output prices and contract farmers have smaller marketing and fertilizer and expenses. However, results reveal that CF results in higher profits—mainly due to reduced marketing expenditures. Thus, CF intervention benefits the livelihood of smallholders, increases efficiency, and reduces environmental degradation without compromising yield. Key","Comments":"","TypeName":"Journal, Article","Authors":"Mishra Ashok K; Mayorga Joaquin ; Kumar Anjani ; ","ParentAuthors":"","DOI":"10.22004/ag.econ.307460","Keywords":"eppi-reviewer4\r\nHaryana, Primary report, outcome evaluation, price realized, cost of production, efficiency, profit, income, seeds, fertilizers, extension services, price realised","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Mishra Ashok K, Mayorga Joaquin, and Kumar Anjani (2020) Technology and Managerial Gaps in Contract Farming : The Case of Specialty Crop Production. Journal of Agricultural and Resource Economics: 5502,  DOI: 10.22004/ag.econ.307460"},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122968,"Title":"Implications of Contract Farming on Agricultural and Rural Development in India : With Special Reference to Karnataka, India","ParentTitle":"","ShortTitle":"Motkuri (2005)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2005","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"48443","Availability":"","URL":"https://mpra.ub.uni-muenchen.de/id/eprint/48443 file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Personal, Archive, Naik - 2013 - Munich Personal RePEc Archive On the Implications of Contract Farming on Agricultural and Rural Develop.pdf","OldItemId":"61304831","Abstract":"In the Gandhian perspective the real India lives in villages. Taking this perspective into account there had been efforts for rural development since independence. As a matter of fact rural development is intertwined with the development of agrarian economy as majority of the population depends on agriculture activities for their livelihood. In the early stages of first plan, Community Development Programme (CDP) is designed for the rural and agricultural development but the realisation of expected outcome was disappointing. In the 1960’s and 1970’s the green revolution package was seen as another chance to materialise the agricultural and thereby rural development given its advantages in terms of new technology, hybrid seeds, and externalities like commercialisation and linkages between industry and agriculture. It too gave us disappointing results, as it is concentrated in specific areas and benefited the particular sections of farming community. One of the problems found with the agricultural development in Indian context is that lack of infrastructure and credit facilities, absence of frontier technology and technical education and proper monitoring mechanism. In the globalisation and liberalization era a new device for agricultural development brought out in the form of contract farming. It is argued that the new concept of contract farming might address these problems. However, it is open to debate whether the initiatives of contract farming help in rural and agricultural development especially whether it provides any beneficial outcome for the marginal and small farmers in terms of their living standards. In this context the present paper examines the rationale for the introduction of contract farming in Indian context and advantages and disadvantages it draws with reference to rural and agricultural development where particular emphasis is given to marginal and small farmers. It is also looking into what are the ideal market conditions necessary for the contract farming to be encouraged and to what extent state can have its regulatory mechanism to monitor and control the contract farming to the extent it benefits the farmers along with sponsoring companies. The study is narrowed down to a case study of Karnataka, which already launched the initiatives towards the contract farming.","Comments":"","TypeName":"Journal, Article","Authors":"Motkuri Venkatanarayana ; Suresh V Naik; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, Primary report, economic evaluation, seeds, extension services, technology, need assessment, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Motkuri Venkatanarayana, and Suresh V Naik (2005) Implications of Contract Farming on Agricultural and Rural Development in India : With Special Reference to Karnataka, India.  (48443), "},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122969,"Title":"Contract Farming and its Implications for Input-supply , Linkages between Markets and Farmers in Karnataka","ParentTitle":"Agricultural Economics Research Review","ShortTitle":"N (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"21","Pages":"307-316","Edition":"","Issue":"21","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Chandakavate - 2008 - Contract Farming and its Implications for Input-supply , Linkages between Markets and Farmers in Karnataka.pdf","OldItemId":"61304830","Abstract":"This study is focused on the economic analysis of contract farming with a comparison of income, access to technology and credit of contract and non-contract farmers. The advantages of contract farming for smallholders have also been evaluated. In contract farming, quality inputs such as seeds, fertilizers and plant protection chemicals are provided to the farmers at their farm gate, coupled with the technical advice on production aspects. This not only reduces the working capital needs of farmers but also substantially reduces their transaction cost per unit of output. Borrowing of crop loans has been found 33 per cent higher by non-contract farmers than contract farmers, as the former have to buy material inputs. The net returns have been found higher for contract than non-contract farmers. Within contract farming, net returns have been recorded higher under domestic than foreign contracts for both baby corn and chilli. In the case of non-contract farmers, the net returns (Rs 3,035) have been found less than one-third of domestic contract farmers (Rs 10,610) and slightly more than one-third of foreign contract farmers (Rs 8,050). In the case of chilli also, the net returns realized per acre have been recorded maximum under domestic contract farmers, followed by foreign contract farmers and non-contract farmers. The returns per rupee invested have been noted higher in farming of baby corn in all the three categories than those of chilli farming. The constraints identified in the study include delay in payment and delivery of inputs, delay in lifting the produce, access to seeds, manupulation of grades by the buyers, and high cost of inputs in contract farming. Factors inducing farmers into contract are: low initial investment, better price for the produce, access to market, technical support on package of practices, access to inputs and easy transportation facilities.","Comments":"","TypeName":"Conference Proceedings","Authors":"N Nagaraj ; M G Chandrakanth; P G Chengappa; H S Roopa; Pramod M Chandakavate; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, primary report, economic evaluation, profit, transaction cost, cost of production, seeds, extension services, return","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"N Nagaraj, M G Chandrakanth, P G Chengappa, H S Roopa, and Pramod M Chandakavate (2008) Contract Farming and its Implications for Input-supply , Linkages between Markets and Farmers in Karnataka. In: Agricultural Economics Research Review, . , p307-316"},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9641036,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122949,"Title":"Impact of Contract Farming on Economic Status of the Farmers Practicing Contract Farming","ParentTitle":"International Journal of Arts, Science and Humanities","ShortTitle":"N (2019)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2019","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"7","Pages":"39-46","Edition":"","Issue":"2","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Journal, Science - 2019 - Impact of Contract Farming on Economic Status of the Farmers Practicing Contract Farming.pdf","OldItemId":"61304844","Abstract":"This article focused on the economic impact of contract farming on respondents who are involved in contract farming. The various economic indicators of impact on contract framers are discussed. The study was conducted in two districts of Karnataka state viz., Bangalore Rural and Tumakuru. Two taluks each from each district, Tumakuru and Gubbi taluks from Tumakuru district and Nelamangala and Doddaballapura taluks from Bangalore Rural district were selected. Total three crops were selected based on simple random sampling techniques; the sample size was Gherkin 35, Tomato 35, Watermelon 10 and non-contract farmers 20 from each taluks of two districts.","Comments":"","TypeName":"Journal, Article","Authors":"N Harish ; ","ParentAuthors":"","DOI":"10.34293/sijash.v7i2.652","Keywords":"eppi-reviewer4\r\ncontract farming, Karnataka, Primary report, outcome evaluation, income, saving, investment","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"N Harish (2019) Impact of Contract Farming on Economic Status of the Farmers Practicing Contract Farming. International Journal of Arts, and Science and Humanities 7(2), 39-46 DOI: 10.34293/sijash.v7i2.652"},{"Codes":[{"AttributeId":9606511,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9641036,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122970,"Title":"Profits from participation in high value agriculture : Evidence of heterogeneous benefits in contract farming schemes in Southern India","ParentTitle":"Food Policy","ShortTitle":"Narayanan (2014)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2014","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"44","Pages":"142-157","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Narayanan - 2014 - Profits from participation in high value agriculture Evidence of heterogeneous benefits in contract farming schemes.pdf","OldItemId":"61304856","Abstract":"This paper assesses the variable impact of participation in high value agriculture through contract farming arrangements in southern India. Using survey data for 474 farmers in four commodity sectors, gherkins, papaya marigold and broiler, an endogenous switching model is used to estimate net profits from participation. Findings suggest that average treatments effect vary widely across contract commodities. Papaya and broiler contracting offer clear net gains for participants whereas marigold contracting leaves participants worse off. For gherkins, while contracting holds net gains for participating farmers overall, this is true of contracts with some firms but not others. The standard deviations of point estimates of treatment effects are quite large indicating variability in profit gains even within the same commodity sectors. Thus, notwithstanding the sign of average treatment effects, contract farming arrangements have diverse impacts on income for individual farmers and these could have implications for sustained partic- ipation of farmers in high value agriculture. Ó","Comments":"","TypeName":"Journal, Article","Authors":"Narayanan Sudha ; ","ParentAuthors":"","DOI":"10.1016/j.foodpol.2013.10.010","Keywords":"eppi-reviewer4\r\nContract Farming, TamilNadu, primary report, outcome evaluation, profit","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Narayanan Sudha (2014) Profits from participation in high value agriculture : Evidence of heterogeneous benefits in contract farming schemes in Southern India. Food Policy 44, 142-157 DOI: 10.1016/j.foodpol.2013.10.010"},{"Codes":[{"AttributeId":9606516,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122971,"Title":"Economics of Contract Farming: A Case of Potato in Gujarat","ParentTitle":"","ShortTitle":"NEELAKANTAPPA (2019)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2019","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"","OldItemId":"61307310","Abstract":"This study examines prevailing practices, relationships of contractual arrangements among stakeholders, impact of contract compliance on transaction costs, technical efficiency, income and employment besides discussing quantifying the factors governing the contractual agreements in potato in Gujarat state. The study pertains to the year 2018-19. The study is based on the primary survey. Principal component analysis, stochastic frontier production function and simple tabular analysis were used. The sample size is 240 comprising of 122 contract farmers and 118 non-contract farmers in potato farming. The study concludes that supply of potato seed of selected varieties viz., Santana, Lady Rosetta, Innovator, Kennebec was the base of forming contract and they were meant for processing only. Since the seed of these varieties was not available in open market. The price fixation in advance (₹ 180/20 kg) was acceptable to farmers irrespective of the open market price. The pre agreed price was always kept higher than the previous year. The compliance of contract terms and conditions from both sides provides win-win situation for stakeholders in contract system. The contract farmers after nudging into fold of contractual arrangement earned ₹ 46,863 per ha more than their counterparts. Moreover, the labor expenses increased in carrying out contractual arrangements by farmers at his field was ₹ 361 per ha more than non-contract farmers. The cost function of stochastic frontier approach revealed average technical efficiency of potato contract farmers was 0.91 which was less than the non-contract farmers (0.95) and found statistically significant. The dimensions like procedural compliance of contract, levels of knowledge in production process and physical infrastructure through PCA analysis explained variations of around 90% of total contract farming phenomenon. The companies imported not only contract production knowledge to farmers but also provide support in the farming incentive price, support in digging, bagging and lifting of fresh potatoes to cold storage etc. The technology sharing by company with the help of agronomists had helped farmers to produce more than the target production and earns bonus(₹ 0.20/ kg ) more on pre-agreed price of potato.","Comments":"","TypeName":"Dissertation","Authors":"NEELAKANTAPPA P ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nGujarat, primary report, economic evaluation, price realized, transaction cost, efficiency, cost of production, seeds, extension services, fertilizers","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"NEELAKANTAPPA P (2019) Economics of Contract Farming: A Case of Potato in Gujarat. , ."},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9644930,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122972,"Title":"PRODUCTION OF EGGPLANT AND LADIES FINGER UNDER CONTRACT FARMING IN KARNATAKA-AN ECONOMIC ANALYSIS","ParentTitle":"","ShortTitle":"NINGANAGOUDA (2007)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2007","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"","OldItemId":"61307309","Abstract":"This study is an attempt to analyze economics of production of eggplant and ladies finger under contract farming, the transaction cost incurred from the point of view of farmer and benefits accrued to small farmers. The sampling for the study consist 60 contract farmers, 30 each growing eggplant and ladies finger in Namdhari Fresh, a subsidiary of Namdhari Seeds Private Limited. A sample of 30 farmers each, growing egg plant and ladies finger who were not participating in contract farming were selected as control. Contract farming ensures farmers with quality inputs, technical guidance and market","Comments":"","TypeName":"Dissertation","Authors":"NINGANAGOUDA M PATIL; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, Primary report, seeds, extension services, technology, economic evaluation, cost of production, Returns, profit, transaction cost","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"NINGANAGOUDA M PATIL (2007) PRODUCTION OF EGGPLANT AND LADIES FINGER UNDER CONTRACT FARMING IN KARNATAKA-AN ECONOMIC ANALYSIS. , ."},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122974,"Title":"Vertical cordination in high value food commodities: Implications for smallholders","ParentTitle":"","ShortTitle":"Pratap (2005)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2005","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"1-54","Edition":"","Issue":"","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Unknown - Unknown - No Title(2).pdf","OldItemId":"61304816","Abstract":"Rising per capita income, urbanization and globalization are changing the consumption basket in the developing countries towards high-value commodities (like fruits & vegetables, milk, meat, poultry, fish, etc.). This paper explores how smallholders can benefit from the emerging opportunities from a silent demand-driven changes in high-value agriculture in India. The study examines the institutional mechanisms adopted by different firms to integrate small producers of milk, broilers and vegetables in supply chain and their effects on producers’ transaction costs and farm profitability. The study finds that the innovative institutional arrangements in the form of contract farming have considerably reduced transaction costs and improved market efficiency to benefit the smallholders. The study does not find any bias against smallholders in contract farming. Also, the study does not find that the relevant firms have exploited their monopsonistic position by paying lower prices to farmers. On the contrary, contract producers were found enjoying benefits of assured procurement of their produce and higher prices. The study lists policy hurdles in scaling up the innovative models of vertical coordination in high-value food commodities","Comments":"","TypeName":"Report","Authors":"Pratap S Birthal1; P K Joshi; Gulati Ashok ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nAndhra Pradesh, Punjab, primary report, economic evaluation, transaction cost, cost of production, yield, profit, one day old chick, feeds, extension services, price risk","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Pratap S Birthal1, P K Joshi, and Gulati Ashok (2005) Vertical cordination in high value food commodities: Implications for smallholders. : , 1-54"},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122975,"Title":"IMPACT OF CONTRACT FARMING IN POULTRY ENTERPRISES IN RANGA REDDY AND MAHABUBNAGAR DISTRICTS OF A.P.","ParentTitle":"","ShortTitle":"PRAVEENA (2007)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2007","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/72132","OldItemId":"61307318","Abstract":"Ranga Reddy and Mahabubnagar districts were purposively selected for the study. An ultimate sample of 30 contract broiler farms, 30 non-contract broiler farms and 30 non-contract layer farms were selected randomly. Indian poultry has shown an annual growth rate of 8 -10% in eggs and 12-15% in broilers for last several years. However poultry rearing was on a small scale for long and commercial poultry production gained significance only over the last three decades. Within this short span the industry has attained technological improvements contributing significantly to the nation’s economy in terms of GDP, hence special emphasis has been laid on contract poultry farming. Objectives of the study: 1. To analyse the efficiency of contract farming in poultry. 2. To study profitability of contract farming in poultry. 3. To study the input-output supply chain system. 4. To analyse the economics of small, medium and large scale broiler and egg producers. In respect of contract broiler farms the total costs per 1000 birds was Rs.4,030. While in the non-contract farms the total costs per 1000 birds was Rs.46,750. In respect of non-contract layer farms, the total costs per 1000 birds was Rs.2,84, 624. In respect of contract farms, sale of birds was the main source of income accounting for about 75 per cent of the gross income. Gross income per 1000 birds valued at Rs. 5,890. On the whole, over the production cycle, the farmers were found to receive a net income of Rs.1,920 per 1000 birds. Coming to the non-contract farms, the sale of birds was found to contribute about 98 per cent to the gross income. Gross returns per 1000 birds were found to be Rs.51,600. The income per 1000 birds was Rs.4,210. Returns per rupee investment were more on contract farms i.e., 1: 0.48 as against non-contract farms 1: 0.009. The gross income per 1000 birds was found to be less on contract farms, as these farms were paid a given a sum of Rs.2.70 on an average per kg of bird as major items of expenditure like chicks, feed and medicines were borne by hatcheries. The input-output ratio indicates that the returns are more in contract farms against non-contract farms. The feed conversion ratio indicates that feed efficiency increased in contract farms than non-contract farms. The contract farms have lower FCR indicating higher profitability in broiler farming. The PEF and EEF also indicate that the contract farms have better performance than non-contract farms. The break-even output on contract broiler farms was found to be 1073.3 kg and the average break-even output stood at 1910 kg. In respect of non-contract broiler farms, the break-even output was 706.05 kg and the average break- even output was 1840 kg. The total costs for 1000 birds were phenomenally higher on non-contract farms over contract farms. The feed efficiency and performance of the flock was appreciable in broiler contract farms compared to non-contract farms. Gross income per 1000 birds was distinctly higher on non-contract farms over contract farms. But the returns per rupee of investment on contract broiler farms were substantially more over non-contract farms. The average break-even output was more on contract broiler farms over non-contract broiler farms. The reason being the contract broiler farmers get only growing charges which are fairly low. There is a need that the small and medium farmers should be encouraged to produce more cycles per year, so that they can make efficient utilization of available resources to earn a reasonably good income. Integration of broiler industry with greater government intervention by providing legal status to the farmer will help farmers to adopt contracts and produce quality output. Further, in case of sudden out break of diseases in large scale farmer as well as integrators are probe to risk, therefore insurance can be introduced for poultry farmers.","Comments":"","TypeName":"Dissertation","Authors":"PRAVEENA VULKUNDKAR ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nAndhra Pradesh, Primary report, economic evaluation, efficiency, profit, total cost, gross income, income,","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"PRAVEENA VULKUNDKAR (2007) IMPACT OF CONTRACT FARMING IN POULTRY ENTERPRISES IN RANGA REDDY AND MAHABUBNAGAR DISTRICTS OF A.P.. , ."},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122976,"Title":"ECONOMICS OF RED BANANA PRODUCTION UNDER CONTRACT FARMING IN KARNATAKA","ParentTitle":"","ShortTitle":"RAGHAVENDRA (2007)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2007","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810103902","OldItemId":"61307304","Abstract":"India has been a predominantly agrarian economy since time immemorial. The development efforts over the last four decades have doubtlessly strengthened our industrial base. However, agriculture continues to be the main stay of our economy even today. This study has been undertaken to know the economics of red banana production under contract farming in Kamataka. The primary data was collected to study the resource use effieieney, detailed information on input used and output sold and problems faced by the contract farmers for 35 farmers for 2004- 2005.","Comments":"","TypeName":"Dissertation","Authors":"RAGHAVENDRA NADUVINAMANI ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nprimary report, economic evaluation, cost of production, seeds, fertilizers, extension services, net return, resource use efficiency, Karnataka","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"RAGHAVENDRA NADUVINAMANI (2007) ECONOMICS OF RED BANANA PRODUCTION UNDER CONTRACT FARMING IN KARNATAKA. , ."},{"Codes":[{"AttributeId":9606503,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122977,"Title":"Problem Analysis of the Contract Farmers and the Contracting Firm under Problem Analysis of the Contract Farmers and the Contracting Firm under Contract Farming of Bottle Gourd","ParentTitle":"Economic Affairs","ShortTitle":"Rajput (2020)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2020","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"63","Pages":"3-3","Edition":"","Issue":"March","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Rajput, Sharma, Sharma - 2020 - Problem Analysis of the Contract Farmers and the Contracting Firm under Problem Analysis of the Contract.pdf","OldItemId":"61304828","Abstract":"The present investigation was undertaken with a view to study the problems faced by the contract farmers and the contracting firm under contract farming of bottle gourd in the Jaipur district of Rajasthan. The contracting firm Rajasthan olive cultivation limited was selected, as it was only contracting firm in the Bassi tehsil which was engaged in the contract farming related to cucurbits and other vegetables. A list of 26 villages having contract farming in bottle gourd was obtained from the tehsil headquarter. From that list three villages were selected randomly. From these villages, 30 contract farmers were selected randomly and 20 non-contract farmers resembling to the contract farmers except contract component were also selected to make a comparative study of the contract farming vis-à-vis non-contract farming. Primary data were collected for the agricultural year 2015-16. The conventional budgeting technique and multiple regression functions were used to analyze the data. In the production of bottle gourd, contract farmers and contracting firms face many problems like transfer of technology, supply of quality seed, arrangements of institutional credit, fertilizers and other inputs, market arrangements, timely payments, violation of terms and conditions, lack of proper management by the company, frequent price fluctuations in markets, lack of transport facilities during peak periods, etc. For solving such problems it is necessary to first identify the problems and reasons thereof so that corrective measures may be resorted to tackle them. However this study was conducted on simulation conditions that involves the construction of the artificial environment (under control conditions) within which relevant information and data can be generated like in green house, poly house and shade net house for the future scholars.","Comments":"","TypeName":"Journal, Article","Authors":"Rajput Arjun Singh; Sharma Vikalp ; Sharma R C; ","ParentAuthors":"","DOI":"10.30954/0424-2513.3.2018.24","Keywords":"eppi-reviewer4\r\ncontract farming, primary report, Rajasthan, need assessment,constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Rajput Arjun Singh, Sharma Vikalp, and Sharma R C (2020) Problem Analysis of the Contract Farmers and the Contracting Firm under Problem Analysis of the Contract Farmers and the Contracting Firm under Contract Farming of Bottle Gourd. Economic Affairs 63(March), 3-3 DOI: 10.30954/0424-2513.3.2018.24"},{"Codes":[{"AttributeId":9606506,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606517,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606503,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606512,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122978,"Title":"Determinants of contract farming in barley production - Regression tree approach Determinants of contract farming in barley production – Regression tree approach","ParentTitle":"Indian Journal of Agricultural Sciences","ShortTitle":"Ramadas (2021)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2021","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"91","Pages":"402-407","Edition":"","Issue":"3","Availability":"","URL":"file:///C:/Users/User/Downloads/2021_ContractFarmingBarleyRegressionTreeIJAgS(1).pdf","OldItemId":"61304814","Abstract":"Barley, a nutri-rich cereal is gaining momentum among stakeholders owing to multiple health benefits but the concern is its declining area, possibly attributed to lack of market and competitive pricing strategy. Amongst alternatives, contract farming is widely suggested for better price realisation and assured market. In the context, the present study was carried out during 2013–15 in four major barley growing states in India, viz. Haryana, Madhya Pradesh, Rajasthan and Uttar Pradesh for identifying the determinants of contract farming from a sample of 400 randomly selected farmers using regression tree approach. Findings indicated that the average yield of farmers enrolled in contract farming was 4791 kg/ha (n=90) against non-contractors with an estimated yield of 3549 kg/ha (n=310), implying a yield advantage of 35%. The practice of enrollment into contracts was popular in Rajasthan as corroborated by regression tree. The analysis also indicated that farm size, seed replacement behaviour, source of seed and area under barley were turned as deciding factors in contract enrollment. Overall, the study indicated that region plays a prominent role in enrollment into contracts despite multiple benefits availed. The study advocates barley growers to take advantage of contract farming, especially small-holders to enroll into contracts for mitigating price risk apart from self-empowerment in barley production.","Comments":"","TypeName":"Journal, Article","Authors":"Ramadas Sendhil ; Poswal Randhir Singh; Kumar Anuj ; Haryana Karnal ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nHaryana, Madhya Pradesh, Rajasthan and Uttar Pradesh access to quality input, contract farming, seeds, fertilizers, extension services, price realization Primary report, economic evaluation yield, price risk","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Ramadas Sendhil, Poswal Randhir Singh, Kumar Anuj, and Haryana Karnal (2021) Determinants of contract farming in barley production - Regression tree approach Determinants of contract farming in barley production – Regression tree approach. Indian Journal of Agricultural Sciences 91(3), 402-407"},{"Codes":[{"AttributeId":9606518,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122979,"Title":"The impact of contract farming on the welfare and livelihoods of farmers : A village case study from West Bengal","ParentTitle":"Journal of Rural Studies","ShortTitle":"Ray (2021)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2021","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"Elsevier Ltd","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"March","Availability":"","URL":"https://doi.org/10.1016/j.jrurstud.2021.06.003 file:///E:/pd/Contract farming/Ray2021.pdf","OldItemId":"61304815","Abstract":"In many countries of the global south, Governments have recently encouraged neoliberal economic policies which have seen large corporations controlling more of the production process. Some studies have welcomed these interventions, arguing they provide enhanced welfare and income prospects for local farmers. Others have been more cautious, arguing they provide new landscapes of economic hardship for small farming communities, both for those contracted to the corporate chains and those that are not. This paper provides a case study of the impacts of the expansion of contract farming by PepsiCo on small-scale farmers in a small village in West Bengal, India. Through a series of detailed focus group and subsequent one-to-one interviews, we explore whether these local farmers are financially better off when tied to contracts with larger firms, whether they benefit from enhanced training and knowledge about better farming methods and whether they feel they are involved in genuine partnerships and the consequent implications for relationships around status, power and trust. The paper concludes that there are many concerns over contract farming some of which have not been discussed in the literature to date. The paper also reports on different types of coping mechanisms operated by small or marginal farmers, which in some cases, breaches the contracts made with PepsiCo","Comments":"","TypeName":"Journal, Article","Authors":"Ray Nabati ; Clarke Graham ; Waley Paul ; ","ParentAuthors":"","DOI":"10.1016/j.jrurstud.2021.06.003","Keywords":"eppi-reviewer4\r\nPrimary report, economic evaluation, profit, west Bengal","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Ray Nabati, Clarke Graham, and Waley Paul (2021) The impact of contract farming on the welfare and livelihoods of farmers : A village case study from West Bengal. Journal of Rural Studies (March),  DOI: 10.1016/j.jrurstud.2021.06.003"},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606509,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[{"ItemDocumentId":681256,"TextFrom":0,"TextTo":0,"Text":"Page 10:\n[¬s]\"proﬁts[¬e]\"","IsFromPDF":true,"DocTitle":"roy2008.pdf","ItemArm":""},{"ItemDocumentId":681256,"TextFrom":0,"TextTo":0,"Text":"Page 9:\n[¬s]\"Revenue[¬e]\"","IsFromPDF":true,"DocTitle":"roy2008.pdf","ItemArm":""}]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122980,"Title":"Success in High Value Horticultural Export Markets for the Small Farmers : The Case of Mahagrapes in India","ParentTitle":"World Development","ShortTitle":"Roy (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"Elsevier Ltd","Institution":"","Volume":"36","Pages":"1874-1890","Edition":"","Issue":"10","Availability":"","URL":"http://dx.doi.org/10.1016/j.worlddev.2007.09.009 file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Roy - 2008 - Success in High Value Horticultural Export Markets for the Small Farmers The Case of Mahagrapes in India.pdf","OldItemId":"61304858","Abstract":"In spite of being the second largest horticultural producer in the world, India is a failed exporter mainly because of the inability to meet the food safety standards. Hence, successes in horticultural exports are rare. Here, we study one unique success story, Mahagrapes, a marketing partner to farmer cooperatives attributing its success to a combination of collective action and pub- lic private partnerships. Our results indicate that Mahagrapes farmers earn significantly higher in- come vis-a`-vis their outside marketing option and smallholders face no bias in selection. Together with the farmer’s ability to consistently meet standards, this implies that the model can be scaled up. Ó","Comments":"","TypeName":"Journal, Article","Authors":"Roy Devesh ; ","ParentAuthors":"","DOI":"10.1016/j.worlddev.2007.09.009","Keywords":"eppi-reviewer4\r\nMaharashtra, primary report, economic evaluation, price realized, profit, return, transaction cost","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Roy Devesh (2008) Success in High Value Horticultural Export Markets for the Small Farmers : The Case of Mahagrapes in India. World Development 36(10), 1874-1890 DOI: 10.1016/j.worlddev.2007.09.009"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122981,"Title":"Gains from coordination in milkfed dairy in Punjab","ParentTitle":"Journal of Agribusiness in Developing and Emerging Economies","ShortTitle":"Roy (2012)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2012","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"2","Pages":"92-114","Edition":"","Issue":"2","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Roy - 2012 - Gains from coordination in milkfed dairy in Punjab.pdf","OldItemId":"61304845","Abstract":"Purpose – The purpose of this paper is to provide an assessment of benefits to farmers from vertical coordination in dairy. To analyze this, the authors first document the functioning of the cooperative (and changes thereof with increased competition). The paper also uses a field survey to quantify the benefits. In the process, the authors investigate the issue of selection/participation of farmers. Design/methodology/approach – This paper is largely based on a survey of households in two districts of Indian Punjab along with secondary data. Descriptive as well as regression analyses have been conducted to address the research questions. Findings – The paper presents several key findings. First, the public sector enterprise has been dynamic as competition from private sector has brought favorable changes. There is also evidence of negative selection of farmers implying that those who join dairy cooperatives would have significantly inferior outcomes outside vis-a`-vis the ones who actually are independent. No bias against farmers by their herd size and significant gains upon participation can explain the scaling up from the demand side. In other words many farmers would find it profitable to become members of the cooperative. Research limitations/implications – Although the survey was extensive in measurement of costs by including variable and fixed costs of production, marketing as well as transaction costs, the data on fixed costs turned out to be noisy. Further, the analysis based on cross-sectional data could not account for unobserved farmer level individual heterogeneity. Also, the outside option for the farmer in this paper is to be independent. It is possible that this could be integration with private sector, a case that the study does not cover. Social implications – Benefits from coordination should motivate policies for promoting it. The finding that increased competition has fostered dynamism in the public sector has implications far beyond the case studied here. Originality/value – Despite the extensive system of cooperatives, there do not exist rigorous studies that assess the gains to farmers from this type of horizontal and vertical coordination. The extent of gains establishes a measure of foregone earnings since the supply chains in India remain uncoordinated. Keywords","Comments":"","TypeName":"Journal, Article","Authors":"Roy Devesh ; ","ParentAuthors":"","DOI":"10.1108/20440831211272571","Keywords":"eppi-reviewer4\r\nPunjab, primary report, economic evaluation, cost of production,  profit, return, transaction cost","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Roy Devesh (2012) Gains from coordination in milkfed dairy in Punjab. Journal of Agribusiness in Developing and Emerging Economies 2(2), 92-114 DOI: 10.1108/20440831211272571"},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122984,"Title":"Contract farming in maize - an economic analysis","ParentTitle":"","ShortTitle":"S (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"India","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"","OldItemId":"61307301","Abstract":"The production of maize has decreased in Davanagere and Haveri district was noted in study period. Sugana and Riddi-Siddi were the companies taking up contract farming in both the district. The average size of land holding of contract farmers was 10.95 acres. They employed about 53.36 mandays, of which 6.32 mandays of human labour for land preparation. Similarly non-contract farmers employed about 54.32 mandays of which 7.96 mandays of human labour for land preparation. About 53.36 mandays of human labour, 5.00 pair days of bullock labour were used for maize cultivation. Total cost of cultivation of maize in contract and non-contract farming was Rs. 24,698.29 and Rs. 20,975.78 per hectare respectively, under this FYM cost was major item which accounted for nearly Rs. 6750 in contract farming. This was due to companies insist more application of FYM than compost fertilizers in contract farming. Followed by threshing activities in both contract farming and non-contract farming. Per crop of maize in contract and non-contract farming on an average yields about 63.15 quintals and 52.90 quintals per hectare, respectively. The average gross return was Rs. 20,769.71 and 14,996.22 per hectare per crop in contract farming and non-contract farming respectively. This worked out to be Rs. 1.84 and 1.71 return to every rupee invested in contract and non-contract farming. Factors responsible for success of contract farming according to farmers were assured market, higher returns, advance payment, transportation, input supply and irrigation availability. The problems were improper drying of the produce by farmers mainly to get more weight of the produce, selection of loyal farmers to have frequent contract with whom he has entered into agreement.","Comments":"","TypeName":"Dissertation","Authors":"S Shridhar ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, Karnataka, seeds, fertilizers, economic evaluation, gross return, profit, cost of cultivation, yield,","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"S Shridhar (2008) Contract farming in maize - an economic analysis. , ."},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122983,"Title":"A Study on contract farming in Karnataka","ParentTitle":"","ShortTitle":"S (2013)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2013","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/66184","OldItemId":"61307303","Abstract":"Contract farming is providing an opportunity to farmers in commercializing their farm to obatain assured proce and market for their produce. In this regard a survey has been done in six crops viz., Tomato, Marigold, Gherkin, Cotton, Watermelon and Pearl millet which are under contract farming . Six districts of Karnataka viz., Chikkaballapur, Tumkur, Davanagere, Haveri, Gadag and Bellary have been selected as major area under contract farming is in these district. The farmers practicing contract farming since 4 seasons were considered for the study. For each selected crop 40 respondents selected thus forms the sample size of 240. There was significant social and economic impact observed in all the six crops. The most favorable change in the farmers attitude towards contract farming was in the order of Water melon (52.50%), Tomato (40.00%), Pearl millet (40.00%), Gherkin (35.00%) and Cotton (27.50%). Input supplied by firms namely, seeds, fertilizers, protection chemicals are the major facilities provided by the firm. The farmers opined that reputation of company, long term relationship with the company and prices offered by the company for the produce were prime factors influencing their preference for firm. Untimely lifting of produce, isolation, labour scarcity, delay in settling payment and improper legal support were the major constraints expressed by the respondents. Assured irrigation facilities, small and medium category farmers are the pre-requisites for entering into contract farming. The major constraints being faced by the contract sponsors were fixing of procurement price and labour scarcity. The suggestions for success of the contract farming are timely payment and facilities for drip irrigation by the sponsors. However, contract sponsors suggested for selling of the entire produce to contract firm by the farmers and there should be increased involvement of family member in cultivation of contracted crops.","Comments":"","TypeName":"Dissertation","Authors":"S Sahana ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nKarnataka, seeds,fertilizers, extension services, primary report, constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"S Sahana (2013) A Study on contract farming in Karnataka. , ."},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122982,"Title":"Food Processing and contract farming in Andhra Contract Pradesh Perspective","ParentTitle":"Economic and Political weekly","ShortTitle":"S (2015)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2015","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"40","Pages":"2705-2713","Edition":"","Issue":"26","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Unknown - 2015 - Food Processing and in Andhra Contract Pradesh Perspective.pdf","OldItemId":"61304849","Abstract":"This paper analyses various problems faced by the food processing sector in Andhra Pradesh, especially in instances of contract farming, with a focus on oil palm and gherkin. While contract farming has largely solved the problem of supply of quality raw material, cultivators of both crops have their own needs, which in some instances processors are unable or unwilling to meet. Oil palm growers, for instance, are keen on an assured minimum price while gherkin growers are totally dependent on export demand. Processors have also neglected the smaller farmers. Hence, some form of government intervention to ensure contracts are enforced and compiled with, is the need of the hour","Comments":"","TypeName":"Journal, Article","Authors":"S MAHENDRA DEV; N CHANDRASEKHARA ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nAndhra Pradesh, Primary report, economic evaluation,  cost of cultivation, return, net income.","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"S MAHENDRA DEV, and N CHANDRASEKHARA (2015) Food Processing and contract farming in Andhra Contract Pradesh Perspective. Economic and Political weekly 40(26), 2705-2713"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633209,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122985,"Title":"India ’ s Agrarian Crisis and Corporate-Led Contract Farming : Socio-economic Implications for Smallholder Producers","ParentTitle":"International Food and Agribusiness Management Review","ShortTitle":"Sharma (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"11","Pages":"25-48","Edition":"","Issue":"4","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Sharma - 2008 - India ’ s Agrarian Crisis and Corporate-Led Contract Farming Socio-economic Implications for Smallholder Producers.pdf","OldItemId":"61304827","Abstract":"The paper discusses India’s agrarian crisis and the role of corporate-led contract farming in addressing these crisis. A two-stage Heckman model was used to explain determinants of participation in contract farming, and whether participation in contract farming affects farm income. The results indicate that contract farming has a positive impact on crop productivity and farm income. The socio-economic factors that influenced participation in contract farming were education, age, farm size, access to institutional credit, source of off-farm income and membership to an organization. Factors related to the likelihood of participation in contract farming slightly differed from the factors affecting farm income.","Comments":"","TypeName":"Journal, Article","Authors":"Sharma Vijay Paul; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, heckman model, economic evaluation, Punjab, income, Productivity","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Sharma Vijay Paul (2008) India ’ s Agrarian Crisis and Corporate-Led Contract Farming : Socio-economic Implications for Smallholder Producers. International Food and Agribusiness Management Review 11(4), 25-48"},{"Codes":[{"AttributeId":9606501,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122986,"Title":"IMPACT ASSESSMENT OF CONTRACT FARMING OF BASMATI RICE IN JAMMU DIVISION","ParentTitle":"","ShortTitle":"Sharma (2016)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2016","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/79755","OldItemId":"61307312","Abstract":"Contract farming is one among several possible interfaces between crop cultivation and its processing and consumption. It is a powerful means of introduction of new crops or farm technologies, especially when both marketing and production uncertainties predominate. To find out the impact on farmers there is a need to assess the factors which influence contract farmers to join contract farming. As this may help other farmers and company to enter into a new venture. Therefore, the present study entitled \"Impact assessment of contract farming of basmati rice in Jammu division\" was undertaken to assess to study the impact of contract farming on basmati growers. Quasi experimental equivalent control group research design was employed for the study. Random sampling technique was used for selecting the sample of contract and non-contract farmers. The total sample size was 100 contract farmers and 100 non-contract farmers. Thus, making a total sample of 200. Interview schedule was used for the collection of data. Summated Rating Scale was employed to measure the attitude of the contract farmers towards contract farming. The significance difference was observed between the contract and non-contract farmers in case of unirrigated land (t= 4.254, p=0.05), family size (t=2.830, p=0.05), average number of children (t=6.08, p=0.05), occupation (t=2.388, p=0.016). However, insignificant in terms of age, education, caste, irrigated land and farming experience. The contract farmers were creativity well off as compare to non-contract farmers, because of more number of farm inventories possessed by contract farmers. Education, irrigated land and agriculture + sources were important factors which affected their decision to adopt contract farming. More benefits were availed by the contract farmers as compare to non-contract farmers. The income pattern of the contract farmers was more than that of non-contract farmers. Improved living standard was important benefit as 90% of contract farmers placed it rank first but non-contract farmers perceived it on rank second (74%). The major constraints which were faced by the contract farmers were non-adoption of the contract farming by the government agency, irregular payment, no increment in price. But non-contract farmers perceived the constraints of irregular payment, non-adoption of contract farming by government extension agency and poor technical assistance by contract firm. This study provides an empirical feedback to research and extension endeavors to promote contract farming on large scale.","Comments":"","TypeName":"Dissertation","Authors":"Sharma Parvani ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, Jammu, outcome evaluation, income, cost of cultivation, constraints,  seeds, fertilizers, extension services","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Sharma Parvani (2016) IMPACT ASSESSMENT OF CONTRACT FARMING OF BASMATI RICE IN JAMMU DIVISION. , ."},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122987,"Title":"IMPACT OF CORPORATE CONTRACT FARMING ON THE FARM ECONOMY - A CASE OF BABY CORN","ParentTitle":"","ShortTitle":"SHIVANAND (2010)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2010","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810022191","OldItemId":"61307315","Abstract":"Contract Farming is evolving as a better alternative for farmers to face the marketing hurdles. An attempt has been made in this study to assess The relative economics of baby corn cultivation under contract farming and non-contract farming and to study the impact of contract farming on farm income and employment in Tumkur district of Karnataka. The study is based on primary data collected from a sample of 60 contract farmers and another sample of 30 non-contract farmers. In the study area, Indo-Spanish Tasty Foods Private Limited is engaged in contract farming of baby corn. The contracting company before entering in to a contract approaches the Farmer and makes a written contract about the output price. The company Provides seeds and fertilizers, on cost basis and undertakes weekly field Visits and provides the needed technical advice to the farmers to ensure Quality of output. After harvest, the entire output is procured by the Company at the contracted price. Assured price before sowing, higher yield Because of access to improved varieties and better crop management Practices are the distinct advantages enjoyed by the contract farmers. The cost of cultivation of baby corn under contract farming was relatively Higher at Rs.18,091per acre as compared to that of Rs.17,223 incurred Under non-contract farming. In contract farming, the farmers realized net Returns of Rs.8,014per acre which is significantly higher than that of Rs. 2077 realised by non-contract farmers. Contract farmers, despite incurring Higher cost of cultivation, were able to realize higher net profits than that of non-contract farmers. The farmers in contract realized an increase regarding both farm income and employment to the tune of about 26 and 17 percent Respectively.","Comments":"","TypeName":"Dissertation","Authors":"SHIVANAND S HIREMATH; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, economic evaluation, Karnataka, seeds, fertilizers, price risk, cost of cultivation, profit, income, employement","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"SHIVANAND S HIREMATH (2010) IMPACT OF CORPORATE CONTRACT FARMING ON THE FARM ECONOMY - A CASE OF BABY CORN. , ."},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122988,"Title":"Contract Farming for Agricultural Diversification in the Indian Punjab : A Study of Performance and Problems","ParentTitle":"Indian Journal of Agricultural Economics","ShortTitle":"Singh (2000)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2000","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"55","Pages":"283-294","Edition":"","Issue":"3","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Singh - 2000 - Contract Farming for Agricultural Diversification in the Indian Punjab A Study of Performance and Problems.pdf","OldItemId":"61304823","Abstract":"","Comments":"","TypeName":"Journal, Article","Authors":"Singh Sukhpal ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPunjab, Secondary report, need assessment, review","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Singh Sukhpal (2000) Contract Farming for Agricultural Diversification in the Indian Punjab : A Study of Performance and Problems. Indian Journal of Agricultural Economics 55(3), 283-294"},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122989,"Title":"Contracting Out Solutions : Political Economy of Contract Farming in the Indian Punjab","ParentTitle":"World Development","ShortTitle":"Singh (2002)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2002","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"30","Pages":"1621-1638","Edition":"","Issue":"9","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Singh - 2002 - Contracting Out Solutions Political Economy of Contract Farming in the Indian Punjab.pdf","OldItemId":"61304822","Abstract":"This paper examines the rationale, practice, and problems of contract farming in vegetable crops in the agriculturally developed Indian Punjab which has faced the problem of sustainability of growth since the early 1980s. It is found that agribusiness firms deal with relatively large producers and their contracts, which are biased against the farmer, perpetuate the existing problems of the farm sector such as high chemical input intensity, and social differentiation. Contracting has however, led to higher farm incomes and more employment for labor. There seems to be an inherent contradiction in the objectives of the contracting parties and those of the local economy.","Comments":"","TypeName":"Journal, Article","Authors":"Singh Sukhpal ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, Punjab, seeds, fertilizers, extension services, economic evaluation, Income, employement","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Singh Sukhpal (2002) Contracting Out Solutions : Political Economy of Contract Farming in the Indian Punjab. World Development 30(9), 1621-1638"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122990,"Title":"Shifting pattern of agricultural space: evolution of contract farming in Punjab","ParentTitle":"Social Change","ShortTitle":"Singh (2005)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2005","Month":"","StandardNumber":"0049085705035","City":"","Country":"","Publisher":"","Institution":"","Volume":"35","Pages":"32-55","Edition":"","Issue":"4","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Singh - 2005 - Social Change.pdf","OldItemId":"61304820","Abstract":"A conscious policy shift relying heavily on private sector participation for a boost to agriculture through contract farming has failed to produce the desired results on the ground. There is now a move to reverse the trend and check the harm suffered by the farming sector in Punjab.","Comments":"","TypeName":"Journal, Article","Authors":"Singh Mahesh Pratap; ","ParentAuthors":"","DOI":"10.1177/004908570503500402","Keywords":"eppi-reviewer4\r\nPrimary report, Punjab, Review, Constraints","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Singh Mahesh Pratap (2005) Shifting pattern of agricultural space: evolution of contract farming in Punjab. Social Change 35(4), 32-55 DOI: 10.1177/004908570503500402"},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122991,"Title":"Contract Farming in Andhra Pradesh : A case of rice seed and gherkin cultivation","ParentTitle":"Economic & Political Weekly","ShortTitle":"Swain (2011)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2011","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"46","Pages":"60-68","Edition":"","Issue":"42","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Swain - 2015 - Contract Farming in Andhra Pradesh.pdf","OldItemId":"61304818","Abstract":"This paper discusses the performance of contract farming in Mahbubnagar and Karimnagar districts of Andhra Pradesh. It compares contract farming in gherkin and rice seed with non-contract farming. It shows the difference in the characteristics of contract and non-contract farm households. Delayed payment, lack of credit, scarcity of water, and difficulty in meeting quality requirements are found to be the major constraints faced by contract farmers. Whenever there is a decline in productivity, the concerned contracting company has a tendency to shift production to other farmers and also to other regions. Braja","Comments":"","TypeName":"Journal, Article","Authors":"Swain Braja ; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nAndhra Pradesh, primary report, economic evaluation, constraints, price risk, seeds, fertilizers, extension services, technology, income","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Swain Braja (2011) Contract Farming in Andhra Pradesh : A case of rice seed and gherkin cultivation. Economic & Political Weekly 46(42), 60-68"},{"Codes":[{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122992,"Title":"Does Technological Linkage in Contract Farming Increase Farm Productivity and Efficiency ? The Case of Hybrid Paddy Seed Cultivation in Undivided Andhra ","ParentTitle":"Agricultural Economics Research Review","ShortTitle":"Swain (2017)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2017","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"29","Pages":"1-14","Edition":"","Issue":"2","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Swain - 2017 - Does Technological Linkage in Contract Farming Increase Farm Productivity and Efficiency The Case of Hybrid Paddy Seed C.pdf","OldItemId":"61304817","Abstract":"Increasing interest for knowing whether technological and input linkages in contract farming increase the farm productivity and efficiency, this paper provides an empirical evidence by undertaking a case study of hybrid paddy seed cultivation through contract farming in undivided Andhra Pradesh. Heckman sample selection model has been used to estimate the productivity differences between contract and non- contract farmers and production frontier has been used to measure the technical efficiency. The results have indicated that contract farmers could achieve higher productivity and more efficiency by growing contract crop compared to non-contract crop. However, non-contract farmers could achieve higher productivity and more efficiency in growing non-contract crop compared to contract farmers. The results have pointed out many avenues for future research; these include the autonomy of farmer in contract farming, technology spill-over effect, and impact of modern technology in contract farming on farmer’s traditional knowledge and local environment.","Comments":"","TypeName":"Journal, Article","Authors":"Swain Braja Bandhu; ","ParentAuthors":"","DOI":"10.5958/0974-0279.2016.00049.5","Keywords":"eppi-reviewer4\r\nOutcome evaluation, primary report, heckman sample selection, farm productivity, efficiency, Andhra Pradesh, Fertilizers, seeds, Extension services, technology, yield, income","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Swain Braja Bandhu (2017) Does Technological Linkage in Contract Farming Increase Farm Productivity and Efficiency ? The Case of Hybrid Paddy Seed Cultivation in Undivided Andhra . Agricultural Economics Research Review 29(2), 1-14 DOI: 10.5958/0974-0279.2016.00049.5"},{"Codes":[{"AttributeId":9606510,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606021,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633204,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633218,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633223,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122993,"Title":"Determinant in Intensity of Farmers ’ Participation in Contract Farming : The Study of Gherkin and Hybrid Paddy Seed Cultivation in a South Indian State","ParentTitle":"Journal of Land and Rural Studies","ShortTitle":"Swain (2019)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2019","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"6","Pages":"1-21","Edition":"","Issue":"2","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Swain - 2019 - Determinant in Intensity of Farmers ’ Participation in Contract Farming The Study of Gherkin and Hybrid Paddy Seed Culti.pdf","OldItemId":"61304850","Abstract":"This article examines the intensity of farmers’ participation in contract farming by estimating the allocation of land and family labour for the contract and non- contract crops. In addition, factors that influence farmers’ decision to allocate land for the contract crop was identified. The analysis of this article is based on 159 households of Telangana state. The empirical results indicated that farmer is likely to employ proportionately more family labour for contract crop compared to non-contract ones. Small farmers proportionately allocate more land and family labour for the contract crop compared to large ones. Landholding size, education and income have influenced farmers’ decision to allocate land for growing gherkin, while it is landholding size, family size and income in case of hybrid paddy seed. To increase participation of small farmers, focus should be given to improve the education level and increase the landholding size through implementation of proper land policy.","Comments":"","TypeName":"Journal, Article","Authors":"Swain Braja ; ","ParentAuthors":"","DOI":"10.1177/2321024918766585","Keywords":"eppi-reviewer4\r\nPrimary report, Telangana, need assessment, contract farming, employement, economic evaluation","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Swain Braja (2019) Determinant in Intensity of Farmers ’ Participation in Contract Farming : The Study of Gherkin and Hybrid Paddy Seed Cultivation in a South Indian State. Journal of Land and Rural Studies 6(2), 1-21 DOI: 10.1177/2321024918766585"},{"Codes":[{"AttributeId":9606502,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633137,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633222,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122994,"Title":"Multinationals vs . Cooperatives : The Income and Efficiency Effects of Supply Chain Governance in India","ParentTitle":"Journal of Agricultural Economics","ShortTitle":"Vandeplas (2013)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2013","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"64","Pages":"217-244","Edition":"","Issue":"1","Availability":"","URL":"file:///C:/Users/User/AppData/Local/Mendeley Ltd./Mendeley Desktop/Downloaded/Vandeplas, Minten, Swinnen - 2013 - Multinationals vs . Cooperatives The Income and Efficiency Effects of Supply Chain Governance in In.pdf","OldItemId":"61304860","Abstract":"The impact ofmultinational firms on the domestic agricultural sector in developing countries is controversial, in particular in India. Relying on a unique set of house- hold-level data from the state of Punjab, we study the biggest dairy company in the world (Nestle´) in India and compare its vertical spillover effects on upstream suppliers to other market channels (informal sector and cooperatives). We find that farmers that supply informal channels are less efficient and earn lower profits per dairy animal than farmers supplying the cooperative and the multinational sector. Furthermore, we find that farmers using the multinational channel are more efficient than farmers in the cooperative channel, but equally profitable. Hence, we do not find that supplying the cooperative channel is more beneficial for local dairy farmers than supplying the multinational channel. Overall, however, dairy productivity and profitability levels are still dramatically low, with substantial scope for dairy development.","Comments":"","TypeName":"Journal, Article","Authors":"Vandeplas Anneleen ; Minten Bart ; Swinnen Johan ; ","ParentAuthors":"","DOI":"10.1111/1477-9552.12004","Keywords":"eppi-reviewer4\r\nproductivity, primary report, outcome evaluation, income, efficiency, Punjab","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Vandeplas Anneleen, Minten Bart, and Swinnen Johan (2013) Multinationals vs . Cooperatives : The Income and Efficiency Effects of Supply Chain Governance in India. Journal of Agricultural Economics 64(1), 217-244 DOI: 10.1111/1477-9552.12004"},{"Codes":[{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606514,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606511,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633070,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633210,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122995,"Title":"IMPACTS OF CONTRACT FARMING OF GHERKIN IN KARNATAKA STATE","ParentTitle":"","ShortTitle":"VENU (2008)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2008","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/97627","OldItemId":"61307307","Abstract":"Contract farming is defined as a system for the production and supply of agricultural or horticultural produ ce under forward contracts between producers/suppliers and buyers. Contract farming offers the advantage of reduced capital investment, reduced risk of price fluctuation, guaranteed returns and provision of technical assistance to the farmer. Gherkin industry in India is primarily concentrated in the three southern states of Karnatak a, Andhra Pradesh (AP) and Tamil Nadu, Karnataka accounts for almost 60 percent of the gherkin production. Tamil Nadu and AP each account for 20 per cent. Performance for gherkin contract farming was ranked best by the respondents with regard to assured income, timely availability of quali ty inputs, assured price and ready market, getting transport arrangement and increased employment at village level. The respondents preferred gherkin cr op because of high profit. The overall analysis indicated that there existed incr eased changes in living standards, social, home and material possession under socio-economic impact. Cent per cent of the respondents felt that gherkin farming provide employment opportunities to a larger extent. A vast majority of the respondents (98.3%) indicated that the gherkin farming was of more pres tigious compared to other types of crop cultivation. About 98.3 per cent of the respondents indicated that the effluents from gherkin farming affect the ecosystem to some extent. 92 percent of the respondents felt that the Salinization of land affects to some extent due to gherkin contract farming. Majority of the employees (90%) felt that due to gherkin farming farmers standard of living was improved. It also pr ovide assured price for the farmers (77%), eliminates middlemen (53%), provide good guidance (20%). Labour scarcity, lack of insurance cover and high cost of labour (ranked 1, 2 and 3 respectively) were the major cons traints faced by the gherkin growers. The study concluded that all the farmer s in the study area e xpressed that they will continue to grow gherkins with the sa me company again and again. In order to involve more farmers under contract farming crop insurance is covered for gherkin or Government support is necessary for effec tive management of contract farming of gherkin.","Comments":"","TypeName":"Dissertation","Authors":"VENU PRASAD H.D; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, economic evaluation, Tamil Nadu, Karnataka, Andhra Pradesh, seeds, fertilizers, extension services, price risk, constraints.","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"VENU PRASAD H.D (2008) IMPACTS OF CONTRACT FARMING OF GHERKIN IN KARNATAKA STATE. , ."},{"Codes":[{"AttributeId":9606020,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606023,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9606507,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633202,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633217,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633219,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]},{"AttributeId":9633224,"AdditionalText":"","ArmId":0,"ArmTitle":"","ItemAttributeFullTextDetails":[]}],"Outcomes":[],"ItemId":62122996,"Title":"ECONOMICS OF CONTRACT FARMING - A STUDY OF ASHWAGANDHA (Withania somnifera) IN NORTH KARNATAKA","ParentTitle":"","ShortTitle":"Vinayaka (2005)","DateCreated":"07/09/2021","CreatedBy":"Manjisha Sinha","DateEdited":"07/09/2021","EditedBy":"Manjisha Sinha","Year":"2005","Month":"","StandardNumber":"","City":"","Country":"","Publisher":"","Institution":"","Volume":"","Pages":"","Edition":"","Issue":"","Availability":"","URL":"http://krishikosh.egranth.ac.in/handle/1/5810114070","OldItemId":"61307305","Abstract":"Contract farming can be described as a half way house between independent farm production and corporate farming. Contract farming involves a contractual relationship between farmers and a central processing or exporting unit/firms. This unit purchases, produce from contract farmers under the agreed terms of contract. Ashwagandha is an important cultivated medicinal crop of India. It is mentioned as an important drug in ancient Ayurvedic literature. Several type alkaloids are found in this plant, of which 'Withanin' and 'Somniferine' are important. The study was undertaken in Raichur, Gadag and Koppal districts of North Karnataka. All the farmers adopting contract farming were chosen. The companies who are practicing contract farming of Ashwagandha in these districts were also chosen. Hence, the total sample size was 30. The study revealed that family size and young age coupled with better education (96.67%) has made the farmers to increase their farm income by adopting commercial agriculture. The total per acre cost of Ashwiigandha production was Rs. 6896 and net returns obtained per acre was Rs. 14,820. The output elasticities of human labour, machine hour, FYM were statistical significant output elasticities of seeds, bullock labour and other (PPC + interest on working capital) was positive but non-significant. An increased returns to scale was evident in case of Ashwagandha production as returns to scale (2.083) was more than unity. Written agreement was used in Ashwagandha contract farming. The technical aspect of agreement was drafted in short, simple terms, clarifying the responsibilities of both farmer and firms. The regression coefficients of net returns from contract farming land under contract farming, education of the contract farmer and experience of the company were statistically significant. The coefficients of the age of the contract farmer and family size were positive but were statistical!}^ non-significant. There were several problems faced by contract farmer and contract firm, which can be well handled with proper policy interventions","Comments":"","TypeName":"Dissertation","Authors":"Vinayaka N V; ","ParentAuthors":"","DOI":"","Keywords":"eppi-reviewer4\r\nPrimary report, Economic evaluation, Profit, return, cost of production, seeds, extension services","ItemStatus":"I","ItemStatusTooltip":"Included in review","QuickCitation":"Vinayaka N V (2005) ECONOMICS OF CONTRACT FARMING - A STUDY OF ASHWAGANDHA (Withania somnifera) IN NORTH KARNATAKA. , ."}];
  const summaryAttribute = "";
  const checkboxCheckedSvg = '<svg id="checked" fill="#000000" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M0 0h24v24H0z" fill="none"/>' +
    '<path d="M19 3H5c-1.11 0-2 .9-2 2v14c0 1.1.89 2 2 2h14c1.11 0 2-.9 2-2V5c0-1.1-.89-2-2-2zm-9 14l-5-5 1.41-1.41L10 14.17l7.59-7.59L19 8l-9 9z"/>' +
    '</svg>';
  const checkboxUncheckedSvg = '<svg id="unchecked" fill="#000000" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M19 5v14H5V5h14m0-2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2z"/>' +
    '<path d="M0 0h24v24H0z" fill="none"/>' +
    '</svg>';
  const checkboxIndeterminateSvg = '<svg id="indeterminate" fill="#000000" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">' +
    '<defs>' +
    '<path d="M0 0h24v24H0z" id="a"/>' +
    '</defs>' +
    '<clipPath id="b">' +
    '<use overflow="visible" xlink:href="#a"/>' +
    '</clipPath>' +
    '<path clip-path="url(#b)" d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm-2 10H7v-2h10v2z"/>' +
    '</svg>';
  const radioCheckedSvg = '<svg id="checked" fill="#000000" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M12 7c-2.76 0-5 2.24-5 5s2.24 5 5 5 5-2.24 5-5-2.24-5-5-5zm0-5C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8z"/>' +
    '<path d="M0 0h24v24H0z" fill="none"/>' +
    '</svg>';
  const radioUncheckedSvg = '<svg id="unchecked" fill="#000000" height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8 8 3.58 8 8-3.58 8-8 8z"/>' +
    '<path d="M0 0h24v24H0z" fill="none"/>' +
    '</svg>';
  const arrowUpSvg = '<svg class="btnRowCollapse" id="arrowUp" fill="#000000" width="18" height="18" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M20.24 18.804c0 0.116-0.058 0.247-0.145 0.334l-0.725 0.725c-0.087 0.087-0.203 0.145-0.334 0.145-0.116 0-0.247-0.058-0.334-0.145l-5.702-5.702-5.702 5.702c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-0.725-0.725c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l6.761-6.761c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l6.761 6.761c0.087 0.087 0.145 0.218 0.145 0.334zM20.24 13.232c0 0.116-0.058 0.247-0.145 0.334l-0.725 0.725c-0.087 0.087-0.203 0.145-0.334 0.145-0.116 0-0.247-0.058-0.334-0.145l-5.702-5.702-5.702 5.702c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-0.725-0.725c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l6.761-6.761c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l6.761 6.761c0.087 0.087 0.145 0.218 0.145 0.334z"/>' +
    '<path d="M0 0h24v24H0z" fill="none"/>' +
    '</svg>';
  const arrowDownSvg = '<svg class="btnRowCollapse" id="arrowDown" fill="#000000" width="18" height="18" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M20.24 12.768c0 0.116-0.058 0.247-0.145 0.334l-6.761 6.761c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-6.761-6.761c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l0.725-0.725c0.087-0.087 0.203-0.145 0.334-0.145 0.116 0 0.247 0.058 0.334 0.145l5.702 5.702 5.702-5.702c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l0.725 0.725c0.087 0.087 0.145 0.218 0.145 0.334zM20.24 7.196c0 0.116-0.058 0.247-0.145 0.334l-6.761 6.761c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-6.761-6.761c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l0.725-0.725c0.087-0.087 0.203-0.145 0.334-0.145 0.116 0 0.247 0.058 0.334 0.145l5.702 5.702 5.702-5.702c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l0.725 0.725c0.087 0.087 0.145 0.218 0.145 0.334z"/>' +
    '<path fill="none" d="M0 0h24v24H0V0z"/>' +
    '</svg>';
  const arrowLeftSvg = '<svg class="btnColCollapse" id="arrowLeft" fill="#000000" width="18" height="18" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M14.436 19.036c0 0.116-0.058 0.247-0.145 0.334l-0.725 0.725c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-6.761-6.761c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l6.761-6.761c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l0.725 0.725c0.087 0.087 0.145 0.218 0.145 0.334s-0.058 0.247-0.145 0.334l-5.702 5.702 5.702 5.702c0.087 0.087 0.145 0.218 0.145 0.334zM20.008 19.036c0 0.116-0.058 0.247-0.145 0.334l-0.725 0.725c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-6.761-6.761c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l6.761-6.761c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l0.725 0.725c0.087 0.087 0.145 0.218 0.145 0.334s-0.058 0.247-0.145 0.334l-5.702 5.702 5.702 5.702c0.087 0.087 0.145 0.218 0.145 0.334z"/>' +
    '<path fill="none" d="M0 0h24v24H0V0z"/>' +
    '</svg>';
  const arrowRightSvg = '<svg class="btnColCollapse" id="arrowRight" fill="#000000" width="18" height="18" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">' +
    '<path d="M14.436 13c0 0.116-0.058 0.247-0.145 0.334l-6.761 6.761c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-0.725-0.725c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l5.702-5.702-5.702-5.702c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l0.725-0.725c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l6.761 6.761c0.087 0.087 0.145 0.218 0.145 0.334zM20.008 13c0 0.116-0.058 0.247-0.145 0.334l-6.761 6.761c-0.087 0.087-0.218 0.145-0.334 0.145s-0.247-0.058-0.334-0.145l-0.725-0.725c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l5.702-5.702-5.702-5.702c-0.087-0.087-0.145-0.218-0.145-0.334s0.058-0.247 0.145-0.334l0.725-0.725c0.087-0.087 0.218-0.145 0.334-0.145s0.247 0.058 0.334 0.145l6.761 6.761c0.087 0.087 0.145 0.218 0.145 0.334z"/>' +
    '<path fill="none" d="M0 0h24v24H0V0z"/>' +
    '</svg>';
  const refreshSvg = '<svg class="btnRefresh" id="refresh" fill="#000000" width="18" height="18" viewBox="0 0 24 24" width="24"><path d="M0 0h24v24H0z" fill="none"/><path d="M17.65 6.35C16.2 4.9 14.21 4 12 4c-4.42 0-7.99 3.58-7.99 8s3.57 8 7.99 8c3.73 0 6.84-2.55 7.73-6h-2.08c-.82 2.33-3.04 4-5.65 4-3.31 0-6-2.69-6-6s2.69-6 6-6c1.66 0 3.14.69 4.22 1.78L13 11h7V4l-2.35 2.35z"/></svg>';
  const topHeaderColors = ["#A370A7","#a776ab","#af83b3","#bb96be"];
  const topHeaderFontColor = "#FFFFFF";
  const sideHeaderColors = ["#885A85","#8e5e8b","#9a6797","#a679a3"];
  const sideHeaderFontColor = "#FFFFFF";
  const dataColor = "#0275d8";
  const collapseColumnHeaders = undefined;
  const collapseRowHeaders = undefined;
  const allowRISDownload = true;
  const showRecordCount = true;
  const showColumnDescriptions = false;
  const showRowDescriptions = false;

  const $window = $(window);
  const $pivotTable = $('.pivot-table');
  const $pivotBody = $('.body');
  const $topHead = $('.top-head');
  const $topHeadTable = $('table', $topHead);
  const $topHeadWrapper = $('.top-head-wrapper');
  const $sideHead = $('.side-head');
  const $sideHeadTable = $('table', $sideHead);
  const $footer = $('.footer');
  const $menu = $('.menu');
  const $veil = $('.veil');
  const $reader = $('.reader');
  const $attributeTooltip = $('.attribute-tooltip');
  const $attributeTooltipContent = $('.attribute-tooltip .content')
  const $recordCount = $('.record-count');

  let $header = $('.header');
  let chartType = 'bubble';
  let filterMode = 'default';

  /**
   * @param {String} value
   */
  function safeParseInt(value) {
    const parsed = parseInt(value, 10);
    if (isNaN(parsed)) {
      return 0;
    }
    return parsed;
  }

  /**
   * Convert reference object from the eppi mapper to a RIS entry
   * @param referenceItem
   */
  function exportItemToRIS(reference, selectedKeywords) {
    const calend = [
      'Jan',
      'Feb',
      'Mar',
      'Apr',
      'May',
      'Jun',
      'Jul',
      'Aug',
      'Sep',
      'Oct',
      'Nov',
      'Dec',
    ];
    const newLine = '\r\n';
    let res = 'TY  - ';
    let tmp = '';
    switch (reference.TypeId) {
      case 14:
        res += 'JOUR' + newLine;
        break;
      case 1:
        res += 'RPRT' + newLine;
        break;
      case 2:
        res += 'BOOK' + newLine;
        break;
      case 3:
        res += 'CHAP' + newLine;
        break;
      case 4:
        res += 'THES' + newLine;
        break;
      case 5:
        res += 'CONF' + newLine;
        break;
      case 6:
        res += 'ELEC' + newLine;
        break;
      case 7:
        res += 'ELEC' + newLine;
        break;
      case 8:
        res += 'ADVS' + newLine;
        break;
      case 10:
        res += 'MGZN' + newLine;
        break;
      default:
        res += 'GEN' + newLine;
        break;
    }
    res += 'T1  - ' + reference.Title + newLine;
    if (reference.TypeId == 10 || reference.TypeId == 14)
      res += 'JF  - ' + reference.ParentTitle + newLine;
    else res += 'T2  - ' + reference.ParentTitle + newLine;
    for (let au of reference.Authors.split(';')) {
      tmp = au.trim();
      if (tmp != '') res += 'A1  - ' + tmp + newLine;
    }
    for (let au of reference.ParentAuthors.split(';')) {
      tmp = au.trim();
      if (tmp != '') res += 'A2  - ' + tmp + newLine;
    }
    res +=
      'KW  - eppi-reviewer4' +
      newLine +
      (reference.Keywords != null && reference.Keywords.length > 2
        ? reference.Keywords.trim() + newLine
        : '');
    let tmpDate = '';
    let Month = safeParseInt(reference.Month);

    if (!Month || Month < 1 || Month > 12) {
      Month =
        1 + reference.Month.length > 2
          ? calend.indexOf(reference.Month.substring(0, 3)) + 1
          : 0;
    }
    let yr = safeParseInt(reference.Year);
    if (reference.Year !== '' && yr) {
      if (yr > 0) {
        if (yr < 20) yr += 1900;
        else if (yr < 100) yr += 2000;
        if (yr.toString().length == 4) {
          res += 'PY  - ' + yr.toString() + newLine;
          if (Month != 0) {
            tmpDate +=
            reference.Year +
              '/' +
              (Month.toString().length == 1
                ? '0' + Month.toString()
                : Month.toString()) +
              '//';
          } else {
            tmpDate += reference.Year + '///' + reference.Month; //"y1  - "
          }
        }
      }
    }
    if (tmpDate.length > 0) {
      res += 'DA  - ' + tmpDate + newLine;
      res += 'Y1  - ' + tmpDate;

      //little trick: edition information is supposed to be the additional info at the end of the
      //Y1 filed. For Thesis pubtype (4) we use the edition field to hold the thesys type,
      //the following finishes up the Y1 field keeping all this into account

      if (reference.TypeId == 4 && reference.Edition.length > 0)
        res += newLine + 'KW  - ' + reference.Edition + newLine;
      else if (reference.Edition.length > 0) res += ' ' + reference.Edition + newLine;
      else res += newLine;
    } else if (reference.TypeId == 4 && reference.Edition.length > 0) {
      res += newLine + 'KW  - ' + reference.Edition + newLine;
    } //end of little trick

    res += 'AB  - ' + reference.Abstract + newLine;
    if (reference.DOI.length > 0) res += 'DO  - ' + reference.DOI + newLine;
    res += 'VL  - ' + reference.Volume + newLine;
    res += 'IS  - ' + reference.Issue + newLine;
    let split = '-';
    Yr = reference.Pages.indexOf(split);
    if (Yr > 0) {
      let pgs = reference.Pages.split(split);
      res += 'SP  - ' + pgs[0] + newLine;
      res += 'EP  - ' + pgs[1] + newLine;
    } else if (reference.Pages.length > 0) res += 'SP  - ' + reference.Pages + newLine;
    res +=
      'CY  - ' +
      reference.City +
      (reference.Country.length > 0 ? ' ' + reference.Country : '') +
      newLine;
    if (reference.URL.length > 0) res += 'UR  - ' + reference.URL + newLine;
    if (reference.Availability.length > 0) res += 'AV  - ' + reference.Availability + newLine;
    if (reference.Publisher.length > 0) res += 'PB  - ' + reference.Publisher + newLine;
    if (reference.StandardNumber.length > 0)
      res += 'SN  - ' + reference.StandardNumber + newLine;
    res += 'U1  - ' + reference.ItemId.toString() + newLine;
    res += 'U2  - ' + selectedKeywords + newLine;
    if (reference.OldItemId.length > 0) res += 'U3  - ' + reference.OldItemId + newLine;

    res += 'N1  - ' + reference.Comments + newLine;

    res += 'ER  - ' + newLine + newLine;

    res = res.replace('     ', ' ');
    res = res.replace('    ', ' ');
    res = res.replace('   ', ' ');
    res = res.replace('   ', ' ');
    return res;
  }

  /**
   *
   * @param {Array} references - array of eppi reference objects
   */
  function handleRisDownloadButtonClick(references){
    const $downloadButton = $('#risDownload');
    const selectedKeywords = $('li.checked', '.reader-filter').map(function() { return $(this).text().trim() }).get().join('; ');

    // remove existing onclick handlers
    $downloadButton.unbind();
    $downloadButton.on('click', (e) => {
      const fileBlob = createRISFile(references, selectedKeywords);
      downloadRISFile(fileBlob);
    });
  }

  /**
   * Create a RIS file blcb from the given references.
   * @param selectedReferences - list of references to create a RIS file from
   * @returns {Blob}
   */
  function createRISFile(selectedReferences, selectedKeywords){
    const len = selectedReferences.length;
    let risData = '';
    for(let i = 0; i < len; i++){
      risData += exportItemToRIS(selectedReferences[i], selectedKeywords);
    }
    return new Blob([risData], { type: 'text/plain' });

  }

  /**
   * Download the File blob of the references.
   * @param {Blob} file
  */
  function downloadRISFile(file){
    const blobUrl = URL.createObjectURL(file);
    // Save the need for file-save.js
    const link = document.createElement("a");
    link.href = blobUrl;
    link.download = `references.ris`;
    link.click();
  }

  /**
   * Gets the colour for the headings.
   * @param stepNumber
   * @returns {number}
   */
  function getColor(side, stepNumber) {
    // let base = 24;
    // let steps = 5;
    // let step = 8;
    //
    // // stops a step being greater than 5
    // stepNumber = stepNumber % steps;
    // return base + (step * stepNumber);
    stepNumber = stepNumber % 4;
    if (side)
      return sideHeaderColors[stepNumber];
    else
      return topHeaderColors[stepNumber];
  }

  /**
   * Builds the table used as the column headers of the pivot table.
   */
  function buildTableColHead() {
    let tableHeadHtml = '';
    let rowClass = '';
    let styles = [];

    for (let i = 0; i < csvData.totalColDepth; i++) {
      let cellClass = '';

      if (i > 0 && (i + 1) < csvData.totalColDepth) {
        rowClass = 'header-can-hide'
      } else if ((i + 1) === csvData.totalColDepth) {
        cellClass = 'clickable-col'
        rowClass = ''
      } else {
        rowClass = ''
      }

      const row = csvData.rows[i];
      tableHeadHtml += '<tr class="' + rowClass + '">';

      for (let j = 0; j < row.length; j++) {
        const col = row[j];

        const colSpan = i === 0 && j === 0 ? csvData.totalColBreadth : col.span;

        let style = '';
        let title = '';

        if (i === 0) {
          style = 'style="background-color:' + getColor(false, 0) + ';color:' + topHeaderFontColor + ';"';
        }

        if (i === 1) {
          style = 'style="background-color:' + getColor(false, j) + ';color:' + topHeaderFontColor + ';"';

          for (let k = 0; k < colSpan; k++)
          {
            styles.push(style);
          }
        }

        if (i > 1) {
          style = styles[j];
        }
        
        if (showColumnDescriptions && col.setDescription.length > 0) {
          title = col.setDescription;
        }

        tableHeadHtml += '<th class="level-' + i + ' ' + cellClass + '" colspan="' + colSpan + '" title="' + title + '" ' + style + ' data-id="' + col.id + '">';
        tableHeadHtml += '<div>';

        if (i === 1) {
          tableHeadHtml += arrowLeftSvg;
          tableHeadHtml += arrowRightSvg;
          tableHeadHtml += refreshSvg;
        }

        tableHeadHtml += '<span>';
        tableHeadHtml += col.title;
        tableHeadHtml += '</span></div>';
        tableHeadHtml += '</th>'
      }

      tableHeadHtml += '</tr>';
    }

    $('table thead', $topHead).append(tableHeadHtml);
    topColHeight = $('table', $topHead).height();
    $('table', $topHead).height(topColHeight);
  }

  /**
   * Builds the table used as the row headers of the pivot table.
   */
  function buildTableRowHead() {
    let tableHeadHtml = '';
    let rowClass = '';
    let lightnessLevel = 0;
    let backgroundStyle = '';

    for (let i = csvData.totalColDepth; i < csvData.rows.length; i++) {
      const row = csvData.rows[i];
      tableHeadHtml += '<tr>';

      for (let j = 0; j < row.length; j++) {
        const col = row[j];
        const rowSpan = i === csvData.totalColDepth && j === 0 ? csvData.totalRowBreadth : col.span;
        const level = csvData.totalColDepth - row.length + j;

        let title = '';

        if (level <= 0) {
          backgroundStyle = 'background-color:' + getColor(true, 0) + ';color:' + sideHeaderFontColor + ';';
        }

        if (level === 1) {
          backgroundStyle = 'background-color:' + getColor(true, lightnessLevel) + ';color:' + sideHeaderFontColor + ';';
          lightnessLevel += 1;
        }

        if (level > 0 && (level + 1) < csvData.totalColDepth) {
          rowClass = 'header-can-hide'
        } else if ((level + 1) === csvData.totalColDepth) {
          rowClass = 'clickable-row'
        }

        if (showRowDescriptions && col.setDescription.length > 0) {
          title = col.setDescription;
        }

        tableHeadHtml += '<th class="level-' + level + ' ' + rowClass + '" rowspan="' + rowSpan + '" title="' + title + '" style="' + backgroundStyle + '" data-id="' + col.id + '">';
        tableHeadHtml += '<div>';

        if (level === 1) {
          tableHeadHtml += arrowUpSvg;
          tableHeadHtml += arrowDownSvg;
          tableHeadHtml += refreshSvg;
        }

        tableHeadHtml += '<span>';
        tableHeadHtml += col.title;
        tableHeadHtml += '</span></div>';
        tableHeadHtml += '</th>'
      }

      tableHeadHtml += '</tr>';
    }

    $('table tbody', $sideHead).append(tableHeadHtml);
    sideColWidth = $('table', $sideHead).width();
    $('table', $sideHead).width(sideColWidth);
  }

  /**
   * Creates the table columns of a row for the pivot table.
   */
  function buildTableColumns(cols, $colHeaders, rowIds) {
    let colIndex = 0;
    let tableColHtml = '';

    $colHeaders.each(function(colHeaderIndex, colHeader) {
      const $colHeader = $(colHeader);
      const colSpan = parseInt($colHeader.attr('colspan'));

      if ($colHeader.hasClass('collapsed')) {
        const colIds = [];

        for (let i = 0; i < colSpan; i++) {
          colIds.push(cols[colIndex].id);
          colIndex++;
        }

        tableColHtml += '<td class="cell" ' +
          'data-colid="' + colIds.join(',') + '" ' +
          'data-rowid="' + rowIds.join(',') + '">' +
          '</td>';
      } else {
        for (let i = 0; i < colSpan; i++) {
          tableColHtml += '<td class="cell" ' +
            'data-colid="' + cols[colIndex].id + '" ' +
            'data-rowid="' + rowIds.join(',') + '">' +
            '</td>';
          colIndex++;
        }
      }
    });

    return tableColHtml;
  }

  /**
   * Creates the table rows of the pivot table.
   */
  function buildTableRows() {
    let tableRowHtml = '';
    let rowIndex = csvData.totalColDepth;

    const cols = csvData.rows[csvData.totalColDepth - 1];
    const $colHeaders = $('.top-head .level-1');
    const $rowHeaders = $('.side-head .level-1');

    $rowHeaders.each(function(rowHeaderIndex, rowHeader) {
      const rowIds = [];
      const $rowHeader = $(rowHeader);
      const rowSpan = parseInt($rowHeader.attr('rowspan'));


      if ($rowHeader.hasClass('collapsed')) {
        tableRowHtml += '<tr>';
        for (let i = 0; i < rowSpan; i++) {
          const row = csvData.rows[rowIndex];
          rowIds.push(row[row.length - 1].id);
          rowIndex++;
        }
        tableRowHtml += buildTableColumns(cols, $colHeaders, rowIds);
        tableRowHtml += '</tr>';
      } else {
        tableRowHtml += '<tr>';
        for (let i = 0; i < rowSpan; i++) {
          const row = csvData.rows[rowIndex];
          tableRowHtml += buildTableColumns(cols, $colHeaders, [row[row.length - 1].id]);
          rowIndex++;
          tableRowHtml += '</tr>';
        }
      }
    });

    $('table tbody', $pivotBody).html(tableRowHtml);
  }

  /**
   * Gets references that match the given row and column lists.
   * @param rowIdList
   * @param colIdList
   * @returns {Array}
   * @constructor
   */
  function getFilteredReferences(rowIdList, colIdList) {
    const references = [];
    const refMatches = referenceData
      .filter((reference) => {
        if (!reference.hasOwnProperty('Codes')) return false;

        //#region This Code Does All The Reader Filtering
        if (rowIdList.length > 0 && colIdList.length > 0) { // if we have selection in both column and row....
          for (const rowId of rowIdList) {  // for each row in the list of rows
            for (const colId of colIdList) {  // get a column in the list of columns
              if (reference.Codes // of the references that have codes,, does this particular reference have at least 2 codes that match rowid and colid
                .filter((code) => code.AttributeId === rowId || code.AttributeId === colId).length >= 2){
                  return true;
                }
            }
          }
        } else {
          for (const code of reference.Codes) {
            if (rowIdList.length === 0) {  // No row intersections to check for.
              if (colIdList.indexOf(code.AttributeId) >= 0) return true;
            } else if (colIdList.length === 0) {  // No column intersections to check for.
              if (rowIdList.indexOf(code.AttributeId) >= 0) return true;
            }
          }
        }
        //#endregion

        return false;
      });

    for (const reference of refMatches) {
      //#region does filtering in the settings menu (affects map display)
      if (filterMode === 'default'){
        //#region Check all the filters. (Parent AND > Child OR)
        const parentFilters = filters.filter((item) => item.checked);
        let refMatchesFilter = parentFilters.length === 0;

        for (const parentFilter of parentFilters) {
          refMatchesFilter = false;

          for (const childFilter of parentFilter.children.filter((item) => item.checked)) {
            const childFilterMatch = reference.Codes.filter((code) => code.AttributeId === childFilter.id).length > 0;

            if (childFilterMatch) {
              refMatchesFilter = true;
              break; // exit this loop --> immediately goes into execution of the parentFilter loop; leaves childfilter loops
                      // result is we end up not checking each selected child item for a match,, resulting in an "OR" condition; "AND" condition would include all selected child items
            }
          }

          // if we do not match in the child filters, then we know it's not AND and we
          // can break.
          if (!refMatchesFilter) break;
        }

        // if we do not match all active parent filters then we do not count this.
        if (!refMatchesFilter) continue;

        references.push(reference);
        //#endregion
      } else if (filterMode === 'and') {
        //#region Check all the filters. (Parent AND == Child AND)
        const parentFilters = filters.filter((item) => item.checked);
        let refMatchesFilter = parentFilters.length === 0;

        for (const parentFilter of parentFilters) { // when checking each parent filter item,
          refMatchesFilter = false; // reset match to false
          const childFilters = parentFilter.children.filter((item) => item.checked);  // filter out child filter items

          for (const childFilter of childFilters) { // each child filter item
            refMatchesFilter = false; // reset match to false
            const childFilterMatch = reference.Codes.filter((code) => code.AttributeId === childFilter.id).length > 0;  // check if child filter item's code matches any reference code

            if (childFilterMatch) { // if child filter item matches at least 1 reference code,
              refMatchesFilter = true;  // set match to true
              // continue this loop --> we do not immediately go into execution of the parentFilter loop; stay in childfilter loops
              // result is we check each selected child item for a match, returning only references which do match, resulting in an "AND" condition
            } else {
              // refMatchesFilter = false;
              break;
            }
          }

          if (!refMatchesFilter) break;
        }

        if (!refMatchesFilter) continue;

        references.push(reference);
        //#endregion
      } else if (filterMode === 'or') {
        //#region Check all the filters. (Parent OR == Child OR)
        const parentFilters = filters.filter((item) => item.checked);
        let refMatchesFilter = parentFilters.length === 0;

        for (const parentFilter of parentFilters) {
          const childFilters = parentFilter.children.filter((item) => item.checked);

          for (const childFilter of childFilters) {
            const childFilterMatch = reference.Codes.filter((code) => code.AttributeId === childFilter.id).length > 0;

            if (childFilterMatch) {
              refMatchesFilter = true;
              break;
            }
          }

          if (!refMatchesFilter) continue;
        }

        if (!refMatchesFilter){
        } else {
          references.push(reference);
        }
        //#endregion
      }
      //#endregion
    }

    return references;
  }

  /**
   * Builds the legend.
   */
  function buildLegend() {
    if (segmentAttributes === null) return;

    let legendHtml = '';

    segmentAttributes.forEach((segment) => {
      legendHtml += '<span class="legend-item" data-description="' + segment.attribute.AttributeSetDescription + '">' +
          '<span class="dot" style="background-color: ' + segment.color + '"></span>' +
          '<span class="label">' + segment.attribute.AttributeName + '</span></span>'
    })

    $('.legend').html(legendHtml);

    $('.legend-item').hover(
        function () {  // hover on
          const text = $(this).data('description');

          if (text.length === 0) {
            return;
          }

          $(this).css('cursor', 'pointer');
          const filterTooltipHtml = '<div class="legend-tooltip">' + text + '</div>';
          $('body').append(filterTooltipHtml);
        },
        function () {  // hover off
          $('.legend-tooltip').remove();
        },
    ).mousemove((e) => {
      const $legendTooltip = $('.legend-tooltip');
      $legendTooltip
          .css({
            top: e.pageY - 24 - $legendTooltip.height(),
            left: e.pageX + 10
          });
    });;
  }

  /**
   * Creates a pie png image as a data url.
   */
  function createPiePng(counts) {
    let currentPoint = 0;
    let conicGrad = '';

    for (const count of counts) {
      currentPoint += count.width;
      if (conicGrad.length > 0) conicGrad += ', ';
      conicGrad += count.color + ' 0 ' + currentPoint + '%';
    }

    if (currentPoint < 100) {
      if (conicGrad.length > 0) conicGrad += ', ';
      conicGrad += '#eeeeee 0';
    }

    const gradient = new ConicGradient({
      stops: conicGrad,
      size: 97
    });

    const png = gradient.png;

    // Clean up memory issues once we have our PNG.
    $(gradient.canvas).empty().remove();
    delete gradient.canvas;

    return png;
  }

  /**
   * Create the mosiac svg
   *
   * @param {Number} dimension
   * @param {Array} references
   */
  function createMosaic(dimension, references) {
    let x = 0;
    let y = 0;

    let html = `<svg width="100" height="100" xmlns="http://www.w3.org/2000/svg">
   <defs>
   <pattern id="grid" width="${dimension}" height="${dimension}" patternUnits="userSpaceOnUse">
   <path d="M ${dimension} 0 L 0 0 0 ${dimension}" fill="none" stroke="white" stroke-width="0.5" />
   </pattern>
   </defs >
    <rect width="100%" height="100%" fill="url(#grid)" />`;

    for (const ref of references) {
      html += `<rect width="${dimension}" height="${dimension}" fill="${ref}" x="${x}" y="${y}" stroke="white" stroke-width="0.5" />`;
      x += dimension;

      if (x > 90) {
        x = 0;
        y += dimension
      }
    }

    html += '</svg >';


    return html;
  }

  /**
   * Creates the initial zero counts for the block.
   * @param rowIds
   * @param colIds
   */
  function createInitialCounts(rowIds, colIds) {
    let counts = [];

    if (segmentAttributes.length === 0) {
      counts.push({
        id: rowIds.join('_') + '-' + colIds.join('_'),
        attribute: null,
        color: dataColor,
        count: 0,
        width: 0,
        size: 0
      })
    } else {
      for (const segment of segmentAttributes) {
        counts.push({
          id: segment.attribute.AttributeId,
          attribute: segment.attribute,
          color: segment.color,
          count: 0,
          width: 0,
          size: 0
        })
      }
    }

    return counts
  }

  /**
   * Calculate the dimensions of the blocks that will go in the svg grid
   *
   * @param {Number} minRequiredBlocks minimum required mosiac tiles (equal to max number of references)
   * @param {Number} containerDimension dimensions of the container
   */
  function getBlockSize(minRequiredBlocks, containerDimension) {
    let number = Math.round(Math.sqrt(minRequiredBlocks));
    while (containerDimension % number != 0 && number < containerDimension) {
      number = number + 1;
    }
    return containerDimension / number;
  }

  /**
   * Updates all the reference counts and creates the visuals.
   */
  function updateReferenceCounts() {
    let maxCount = 0;

    // Remove old html and detach events.
    $('.cell', $pivotBody).off();
    $('.pie-wrapper').off().detach().remove();
    $('.data-wrapper').off().detach().remove();

    $('.cell', $pivotBody).each((index, cell) => {
      const $cell = $(cell);
      let colIds = $cell.data('colid')
      let rowIds = $cell.data('rowid');

      console.group('cell');
      console.warn('before');
      console.warn('colIds', colIds);
      console.warn('rowIds', colIds);

      if (isNaN(colIds)) {
        colIds = colIds.split(',').map(id => parseInt(id));
      } else {
        colIds = [colIds]
      }

      if (isNaN(rowIds)) {
        rowIds = rowIds.split(',').map(id => parseInt(id));
      } else {
        rowIds = [rowIds]
      }

      console.warn('after');
      console.warn('colIds', colIds);
      console.warn('rowIds', colIds);
      console.groupEnd();

      const references = getFilteredReferences(rowIds, colIds);
      const counts = createInitialCounts(rowIds, colIds);

      let totalCount = 0;

      for (const reference of references) {
        for (const count of counts) {
          if (count.attribute === null) {
            totalCount += 1;
            count.count += 1;
            continue;
          }

          const countMatched = reference.Codes
            .filter((code) => code.AttributeId === count.id).length > 0

          if (countMatched) {
            count.count += 1;
            totalCount += 1;
          }
        }
      }

      if (totalCount === 0) {
        $cell.addClass('none');
      } else {
        $cell.removeClass('none');
      }

      if (totalCount > maxCount) {
        maxCount = totalCount
      }

      for (const count of counts) {
        count.width = totalCount === 0 || count.count === 0 ? 0 : Math.round(count.count / totalCount * 100);

        // Check if the count is a sane amount to see, if not, make it the minimum.
        if (count.width < 8 && count.count !== 0) count.width = 8
      }

      // Sort counts descending.
      counts.sort(function(a, b) { return b.count - a.count});

      $cell.data('totalSize', 0);
      $cell.data('totalCount', totalCount);
      $cell.data('counts', counts);

      let piePngStyle = '';
      if (counts.length > 0 && chartType === 'donut') {
        const png = createPiePng(counts);

        if (png.length > 0) {
          piePngStyle = ' style="background-image: url(' + png + ')"';
        }
      }

      let dataWrapper = '<div class="pie-wrapper">' +
        '<div class="pie"' + piePngStyle + '></div>' +
        '<div class="pie-hole"></div>' +
        '</div>' +
        '<div class="mosaic-wrapper"></div>' +
        '<div class="data-wrapper">';

      let counter = 1;

      for (const count of counts) {
        if (count.count === 0) continue;

        dataWrapper += '<div id="' + count.id + '" ' +
          'class="data" ' +
          'style="background-color: ' + count.color + ';"></div>';

        if (counter % 2 === 0) {
          dataWrapper += '<div class="break"></div>'
        }

        counter ++;
      }

      dataWrapper += '</div>';

      $cell.html(dataWrapper);
    });

    // Update the size of the chart elements.
    $('.cell', $pivotBody).each((index, cell) => {
      const $cell = $(cell);
      const totalCount = $cell.data('totalCount');
      const counts = $cell.data('counts');

      for (const count of counts) {
        count.size = count.count === 0 ? 0 : Math.round(count.count / maxCount * 100);
        // Check if the count is a sane amount to see, if not, make it the minimum.
        if (count.size < 8 && count.count !== 0) count.size = 8
      }

      let totalSize = totalCount === 0 ? 0 : Math.round(totalCount / maxCount * 100);
      // Check if the count is a sane amount to see, if not, make it the minimum.
      if (totalSize < 8 && totalCount !== 0) totalSize = 8

      $cell.data('counts', counts);
      $cell.data('totalSize', totalSize);
      $cell.data('maxCount', maxCount);
    });

    // Setup events.
    setupTooltips();
    handleTableClick();
  }

  /**
   * Switches between the bubble and heat-map views.
   */
  function updateTableDataView() {
    $('.cell', $pivotBody).each((index, cell) => {
      const $cell = $(cell);
      const counts = $cell.data('counts');
      const totalSize = $cell.data('totalSize');
      const totalWidth = $cell.data('totalWidth');
      const maxCount = $cell.data('maxCount');
      const blockSize = 100;
      const itemCount = counts.filter((e) => e.count > 0).length;

      if (chartType === 'donut') {
        const circleSize = (blockSize * totalSize / 100);
        let holeSize = totalSize - (circleSize / blockSize * 24);
        if (holeSize < 0) holeSize = 0;

        $('.pie-wrapper', $cell).css({
          'display': 'block'
        });

        $('.pie', $cell).css({
          'width': circleSize + '%',
          'height': circleSize + '%'
        });

        $('.pie-hole', $cell).css({
          'width': holeSize + '%',
          'height': holeSize + '%'
        });

        $('.data-wrapper', $cell).css({
          'display': 'none'
        });

        $('.mosaic-wrapper', $cell).css({
          'display': 'none'
        });

        return;
      } else {
        $('.pie-wrapper', $cell).css({
          'display': 'none'
        });

        $('.mosaic-wrapper', $cell).css({
          'display': 'none'
        });

        $('.data-wrapper', $cell).css({
          'display': 'flex'
        });
      }

      $('.data-wrapper', $cell).css({
        'display': chartType === 'heat' ? 'flex' : chartType === 'bubble' ? 'flex' : 'block',
        'opacity': chartType === 'heat' ? (totalSize / 100) : 1
      });

      if (chartType === 'mosaic') {
        $('.pie-wrapper', $cell).css({
          'display': 'none'
        });

        $('.data-wrapper', $cell).css({
          'display': 'none'
        });

        $('.mosaic-wrapper', $cell).css({
          'display': 'block'
        });

        const dimension = getBlockSize(maxCount, 100);

        // Get colours from segments
        const referenceColours = counts.map(x => new Array(x.count).fill(x.color));
        const references = [].concat.apply([], referenceColours);
        let mosaic = createMosaic(dimension, references);
        $('.mosaic-wrapper', $cell).html(mosaic)
      }

      $('.data', $cell).css({
        'border-radius': chartType === 'heat' ? '0%' : '100%',
        'position': 'relative'
      });

      let maxBlockSize = blockSize;

      if (segmentAttributes.length > 1) {
        maxBlockSize = blockSize / (segmentAttributes.length / 2);
      }

      for (const [index, count] of counts.entries()) {
        let size = blockSize * count.size / 100;

        // Check if the count is a sane amount to see, if not, make it the minimum.
        if (size < 8 && count.count !== 0) size = 8;
        else if (size > maxBlockSize && count.count !== 0) size = maxBlockSize;

        $('#' + count.id, $cell).css({
          'height': chartType === 'bubble' ? size + 'px' : '100%',
          'width': chartType === 'bubble' ? size + 'px' : count.width + '%'
        });
      }

      setTimeout(function () {
        $('.data-wrapper', $cell).css({
          'opacity': chartType === 'heat' ? totalWidth / 100 : 1
        });
      }, 500);
    });
  }

  /**
   * Cross browser functionality to request full screen access.
   * https://developer.mozilla.org/en-US/docs/Web/API/Fullscreen_API#Toggling_fullscreen_mode
   */
  function toggleFullScreen() {
    if (!document.fullscreenElement &&    // alternative standard method
      !document.mozFullScreenElement && !document.webkitFullscreenElement && !document.msFullscreenElement ) {  // current working methods
      if (document.documentElement.requestFullscreen) {
        document.documentElement.requestFullscreen();
      } else if (document.documentElement.msRequestFullscreen) {
        document.documentElement.msRequestFullscreen();
      } else if (document.documentElement.mozRequestFullScreen) {
        document.documentElement.mozRequestFullScreen();
      } else if (document.documentElement.webkitRequestFullscreen) {
        document.documentElement.webkitRequestFullscreen(Element.ALLOW_KEYBOARD_INPUT);
      }
    } else {
      if (document.exitFullscreen) {
        document.exitFullscreen();
      } else if (document.msExitFullscreen) {
        document.msExitFullscreen();
      } else if (document.mozCancelFullScreen) {
        document.mozCancelFullScreen();
      } else if (document.webkitExitFullscreen) {
        document.webkitExitFullscreen();
      }
    }
  }

  /**
   * Helper function to build the full table.
   */
  function buildTable() {
    buildTableColHead();
    buildTableRowHead();
    buildTableRows();

    // Update data in the table.
    updateReferenceCounts();
    updateTableDataView();
  }

  /**
   * Sets the filter state of the the given filter ID by either adding it or
   * removing it from a list of unchecked filter IDs.
   * @param checkFilters
   * @param filterId
   * @param klass
   */
  function setFilterState(checkFilters, filterId, klass) {
    for (const filter of checkFilters) {
      if (filterId === filter.id) {
        filter.checked = klass === 'checked' || klass === 'indeterminate';
      }

      if (filter.children.length > 0) {
        setFilterState(filter.children, filterId, klass);
      }
    }
  }

  /**
   * Updates the filter's parent node's state.
   * @param $target
   */
  function updateFilterParentNodeCheckedState($target) {
    let hasChecked = false;
    let hasUnchecked = false;
    let hasIndeterminate = false;

    $target.next().children().each(function () {
      const klass = $(this).attr('class');

      if (klass === 'checked') {
        hasChecked = true;
      } else if (klass === 'unchecked') {
        hasUnchecked = true;
      } else {
        hasIndeterminate = true;
      }
    })

    let klass = '';

    if (hasChecked && !hasUnchecked && !hasIndeterminate) {
      klass = 'checked'
    } else if (!hasChecked && hasUnchecked && !hasIndeterminate) {
      klass = 'unchecked'
    } else if ((hasChecked && hasUnchecked && !hasIndeterminate) ||
      (hasChecked && !hasUnchecked && hasIndeterminate) ||
      (!hasChecked && hasUnchecked && hasIndeterminate) ||
      (hasChecked && hasUnchecked && hasIndeterminate)) {
      klass = 'indeterminate'
    }

    if (klass.length > 0) {
      const filterId = $target.data('id');
      setFilterState(filters, filterId, klass);

      $target
        .removeClass($target.attr('class'))
        .addClass(klass);
    }
  }

  /**
   * Updates the filter's node state and calls it's children r
   * recursively.
   * @param $target
   * @param newKlass
   */
  function updateFilterNodeCheckedState($target, newKlass = '') {
    const klass = $target.attr('class');
    $('#filterClearButton').attr('disabled',false);

    if (newKlass.length === 0) {
      if (klass === 'checked') {
        newKlass = 'unchecked';
      } else {
        newKlass = 'checked';
      }
    }

    const $next = $target.next();

    if ($next.is('ul')) {
      $next.children().each(function () {
        updateFilterNodeCheckedState($(this), newKlass);
      })
    }

    if ($target.is('li')) {
      const filterId = $target.data('id');
      setFilterState(filters, filterId, newKlass);

      $target
        .removeClass(klass)
        .addClass(newKlass);

      const $parent = $target.parent().prev();
      updateFilterParentNodeCheckedState($parent);
    }
  }

  /**
   * Update's the filter type and the checked state of the radios.
   * @param $filters
   * @param $target
   */
  function updateFilterMode($filters, $target) {
    const klass = $target.attr('class');
    if (klass === 'checked') return;

    filterMode = $target.data('id');

    $('.filter-type-wrapper li', $filters)
        .removeClass('checked')
        .addClass('unchecked');
    $target
        .removeClass('unchecked')
        .addClass('checked');
  }

  /**
   * Update's the chartType and the checked state of the radios.
   * @param $filters
   * @param $target
   */
  function updateViewStyle($filters, $target) {
    const klass = $target.attr('class');
    if (klass === 'checked') return;

    chartType = $target.data('id');

    $('.style-wrapper li', $filters)
      .removeClass('checked')
      .addClass('unchecked');
    $target
      .removeClass('unchecked')
      .addClass('checked');
  }

  /**
   * Creates a filter node recursively.
   * @param filters
   * @returns {string}
   */
  function createFilterNode(filters) {
    let filterHtml = '<ul>';

    for (const filter of filters) {
      filterHtml += '<li class="unchecked" data-id="' + filter.id + '">' +
        checkboxCheckedSvg +
        checkboxUncheckedSvg +
        checkboxIndeterminateSvg +
        ' <span>' + filter.label + '</span></li>';

      if (filter.children.length > 0) filterHtml += createFilterNode(filter.children);
    }

    filterHtml += '</ul>';
    return filterHtml;
  }

  /**
   * Creates the elements for the settings panel and hooks up
   * the events.
   */
  function createSettingsPanel() {
    const $filters = $('.settings');

    // Open filter if it should be auto open.
    if (autoOpenFilter) {
      $filters.addClass('open');
      $veil.addClass('open');
    }

    let settingsHtml = '<div class="title clearfix">' +
      '<span>Settings</span>' +
      '<a class="btnSettings right" id="close">close</a>' +
      '<a class="btnSettings left disabled" id="update">update</a>' +
      '</div>';
    settingsHtml += createFiltersPanel();
    settingsHtml += createStylesPanel();

    $filters.html(settingsHtml);

    $('.filter-type-wrapper li', $filters).on('click', (e) => {
      updateFilterMode($filters, $(e.currentTarget));
      $('.disabled').removeClass('disabled');
      $('#update', $filters).on('click', handleUpdate);
    });

    $('.filter-wrapper li', $filters).on('click', (e) => {
      updateFilterNodeCheckedState($(e.currentTarget));
      $('.disabled').removeClass('disabled');
      $('#update', $filters).on('click', handleUpdate);
    });

    $('.style-wrapper li', $filters).on('click', (e) => {
      updateViewStyle($filters, $(e.currentTarget));
      $('.disabled').removeClass('disabled');
      $('#update', $filters).on('click', handleUpdate);
    });

    $('.menu-settings').on('click', function () {
      $filters.addClass('open');
      $veil.addClass('open');
    });

    $('#filterClearButton').on('click', function () {
      const $filterButton = $('#filterClearButton');
      const $filteritems = $('.filter-wrapper ul > li');

      for (const item of $filteritems) {
        const $item = $(item);
        updateFilterNodeCheckedState($item, 'unchecked');
      }
      $filterButton.attr('disabled', true);
      $('.disabled').removeClass('disabled');
      $('#update', $filters).on('click', handleUpdate);
    })

    $('#close', $filters).on('click', function () {
      if (!$('#update', $filters).hasClass('disabled')) {
        if (!confirm('You have not updated the map with your changes. Are you sure you want to close?')) {
          return;
        }
      }

      $filters.removeClass('open');
      $veil.removeClass('open');
    });

    function handleUpdate() {
      const $update = $(this);
      $update.addClass('busy');

      setTimeout(() => {
        updateReferenceCounts();
        updateTableDataView();
        UpdateRecordCount();

        $filters.removeClass('open');
        $veil.removeClass('open');
        $update.removeClass('busy')
          .addClass('disabled');
        $update.off('click');
      }, 300);
    }
  }

  /**
   * Creates the filter section elements for the settings panel.
   * @returns {string}
   */
  function createFiltersPanel() {
    let filterHtml = `<div class="filter-type-wrapper">
        <h2>Filter mode</h2>
        <ul>
          <li class="${filterMode === 'default' ? 'checked': 'unchecked'}" data-id="default">
            ${radioCheckedSvg}
            ${radioUncheckedSvg}
            <span>Default <small>(OR within sections, AND across sections)</small></span>
          </li> 
          <li class="${filterMode === 'and' ? 'checked': 'unchecked'}" data-id="and">
            ${radioCheckedSvg}
            ${radioUncheckedSvg}
            <span>And</span>
          </li> 
          <li class="${filterMode === 'or' ? 'checked': 'unchecked'}" data-id="or">
            ${radioCheckedSvg}
            ${radioUncheckedSvg}
            <span>Or</span>
          </li> 
        </ul>
      </div>
      <div class="filter-wrapper">
        <h2>Filters</h2>`;
      filterHtml +=
      '<button id="filterClearButton">Clear Filter</button>';
    filterHtml += createFilterNode(filters);
    filterHtml +=
    '</div>';

    return filterHtml;
  }

  /**
   * Creates the style section elements for the settings panel.
   * @returns {string}
   */
  function createStylesPanel() {
    let styleHtml = `
    <div class="style-wrapper">
    <h2>Style</h2>
      <ul>
      <li class="${chartType === 'bubble' ? 'checked': 'unchecked'}" data-id="bubble">
      ${radioCheckedSvg}
      ${radioUncheckedSvg}
      <span>Bubble-map</span>
      </li> 
      <li class="${chartType === 'heat' ? 'checked': 'unchecked'}" data-id="heat">
      ${radioCheckedSvg}
      ${radioUncheckedSvg} 
      <span>Heat-map</span>
      </li>
      <li class="${chartType === 'mosaic' ? 'checked': 'unchecked'}" data-id="mosaic">
      ${radioCheckedSvg}
      ${radioUncheckedSvg}
      <span>Mosaic</span>
      </li>`;

    if(segmentAttributes.length !== 0){
        styleHtml+=`
        <li class="${chartType === 'donut' ? 'checked': 'unchecked'}" data-id="donut">
        ${radioCheckedSvg}
        ${radioUncheckedSvg} 
        <span>Donut-map</span>
        </li>`;
    }
    styleHtml += '</ul>';

    return styleHtml;
  }

  /**
   * Creates the tooltip for the cell as it's hovered over.
   */
  function setupTooltips() {
    $('.cell').hover((e) => {
      // Hover.
      const $target = $(e.currentTarget);
      const totalCount = $target.data('totalCount');

      if (totalCount <= 0) {
        return
      }

      const counts = $target.data('counts');

      let tooltipHtml = '<div class="tooltip">';

      for (const count of counts) {
        if (count.count === 0) continue;

        let title = 'Record';

        if (count.count > 1) {
          title = 'Records';
        }

        if (count.attribute !== null) {
          title = count.attribute.AttributeName
        }

        tooltipHtml += '<div class="count">' +
          '<span style="background-color: ' + count.color + ';">' + count.count + '</span> ' +
          title +
          '</div>';
      }

      tooltipHtml += '</div>';

      $(tooltipHtml)
        .appendTo('body')
        .fadeIn('fast');
    }, (e) => {
      // Hover out.
      $('.tooltip').remove();
      delete $('.tooltip');
    }).mousemove((e) => {
      $('.tooltip')
        .css({
          top: e.pageY + 10,
          left: e.pageX + 10
        });
    });
  }

  /**
   * Creates the meta item in the reader for the reference key
   * passed in.
   * @param key
   * @param reference
   * @returns {string}
   */
  function createMetaItem(key, reference) {
    let metaItem = '';
    const renameKeys = {
      'Journal': 'ParentTitle'
    }
    let tempKey = renameKeys[key];
    if (reference[tempKey] == undefined) {
      tempKey = key
    }

    if (tempKey !== summaryAttribute && reference[tempKey] !== undefined && reference[tempKey].length > 0) {

      let label = '';
      label = key

      metaItem += '<div class="meta-data-item clearfix ' + tempKey + '">';
      metaItem += '<label>' + label.replace(/([^A-Z])([A-Z])/g, '$1 $2') + '</label>';
      metaItem += '<span>' + reference[tempKey] + '</span>';
      metaItem += '</div>'
    }

    return metaItem;
  }

  /**
   * Creates the elements to read a review.
   * @param refId
   */
  function selectReference(refId) {
    const references = referenceData.filter((reference) => {
      return reference.ItemId === refId;
    });

    if (references.length === 0) {
      $('.read').html('');
      return;
    }

    const reference = references[0];
    let refHtml = '<h2>' + reference.Title + '</h2>';
    refHtml += '<hr>';

    if (reference.Abstract !== undefined && reference.Abstract.length > 0) {
      refHtml += '<p>' + reference.Abstract.replace(/\r/g, '<br>') + '</p>';
      refHtml += '<hr>';
    } else if (summaryAttribute.length > 0 && reference[summaryAttribute] !== undefined && reference[summaryAttribute].length > 0) {
      refHtml += '<p>' + reference[summaryAttribute].replace(/\r/g, '<br>') + '</p>';
      refHtml += '<hr>';
    }

    if (reference.URL !== undefined && reference.URL.length > 0) {
      refHtml += '<ol class="refs">';
      refHtml += '<li><a class="small" href="' + reference.URL + '" target="_blank">' + reference.URL + '</a></li>';

      if (reference.DOI === undefined || reference.DOI.length === 0) {
        refHtml += '</ol>';
        refHtml += '<hr>';
      }
    }

    if (reference.DOI !== undefined && reference.DOI.length > 0) {
      if (reference.URL === undefined || reference.URL.length === 0) {
        refHtml += '<ol class="refs">';
      }

      refHtml += '<li><a class="small" href="' + reference.DOI + '" target="_blank">' + reference.DOI + '</a></li>';
      refHtml += '</ol>';
      refHtml += '<hr>';
    }

    refHtml += '<div class="meta-data">';
    for (const key of metaProperties) {
      refHtml += createMetaItem(key, reference);
    }

    var matchedExturlAttributes = [];
    refHtml += "<div> <hr>";
    // checking for matches with external Attribute URLs to display in reader
    for (const attribute of externalURLedAttributes) {
      matchedExturlAttributes = reference.Codes.filter(code =>
        code.AttributeId === attribute.AttributeId);
      if (matchedExturlAttributes.length > 0 && attribute.ExtURL !== "" && attribute.ExtURL !== undefined) {
        refHtml +=
        '<span>' + attribute.AttributeName + '<br>' +
          '<a href="' + attribute.ExtURL + '" target="_blank">' + attribute.ExtURL + '</a>' +
        '</span><br>';
      }
    }
    refHtml +='</div>';

    refHtml += '</div>';

    $('.read').html(refHtml);
  }

  /**
   * Updates the reader to show the newly filtered/changed references.
   * @param references
   */
  function updateReferenceReader(references) {
    $('.refMenuItem').off();

    const readerOrder = $('#RefSortOrder').val();

    if (readerOrder === 'title') {
      references.sort(function (a, b) {
        if (a.Title > b.Title) return 1;
        else if (a.Title < b.Title) return -1;
        else return 0;
      });
    } else if (readerOrder === 'author') {
      references.sort(function (a, b) {
        if (a.Authors > b.Authors) return 1;
        else if (a.Authors < b.Authors) return -1;
        else return 0;
      });
    } else if (readerOrder === 'date') {
      references.sort(function (a, b) {

        let aDateStr = '';
        let bDateStr = '';

        if (a.Month.length !== 0) {
          aDateStr += a.Month + ' 01, ';
        }
        aDateStr += a.Year;

        if (b.Month.length !== 0) {
          bDateStr += b.Month + ' 01, ';
        }
        bDateStr += b.Year;

        const aDate = Date.parse(aDateStr);
        const bDate = Date.parse(bDateStr);

        if (aDate > bDate) return 1;
        else if (aDate < bDate) return -1;
        else return 0;
      });
    }

    let title = '';

    if (references.length === 1) {
      title = references.length + ' Record'
    } else {
      title = references.length + ' Records'
    }

    $groupingSelect = $('.grouping-opts');

    let refsHtml = '';

    if ($groupingSelect.val() === 'none') {   // no grouping
      //#region ADDS ALL THE STUDIES INTO AN UNSEGMENTED LIST
      refsHtml = '<ul>';

      for (const ref of references) {
        let colors = [];

        for (const code of ref.Codes) {
          for (const segment of segmentAttributes) {
            if (code.AttributeId === segment.attribute.AttributeId) {
              colors.push(segment.color);
            }
          }
        }

        refsHtml += '<li class="refMenuItem" data-refid="' + ref.ItemId + '" segmented="no">' +
          '<div class="title">' + ref.Title + '</div>' +
          '<div class="auth">' + ref.Authors + '</div>';

        refsHtml += '<div class="date">';

        if (ref.Month.length !== 0) {
          refsHtml += ref.Month + ', ';
        }

        refsHtml += ref.Year;

        for (let color of colors) {
          refsHtml += '<span class="refMenuItemLegend" style="background-color: ' + color + '" />';
        }

        refsHtml += '</div>';
        refsHtml += '</li>';
      }

      refsHtml += '</ul>';
      // #endregion
    } else if ($groupingSelect.val() === 'segment') {  // group by segments
      //#region ADD STUDIES INTO INDIVUDUAL UNORDERED LISTS
      refsHtml = '<ul class="segmented">';

      for (const segment of segmentAttributes){
        refsHtml +=
        '<li style="border-left:2px solid ' + segment.color + ';">' +
          '<div class="segment-title" style="border-bottom: 3px solid ' + segment.color + ';border-left: 5px solid ' + segment.color + '">'
            + segment.attribute.AttributeName +
          '</div>' +
          '<ul>';
            for (const ref of references) {
              let colors = [];

              for (const code of ref.Codes) {
                for (const segment of segmentAttributes){
                  if (code.AttributeId === segment.attribute.AttributeId) {
                    colors.push(segment.color);
                  }
                }
              }
              for (const code of ref.Codes) {
                if (code.AttributeId === segment.attribute.AttributeId) {
                  refsHtml +=
                  '<li class="refMenuItem" data-refid="' + ref.ItemId + '" segmented="yes">' +
                    '<div class="title">' + ref.Title + '</div>' +
                    '<div class="auth">' + ref.Authors + '</div>';

                    refsHtml +=
                    '<div class="date">';
                    if (ref.Month.length !== 0) {
                      refsHtml += ref.Month + ', ';
                    }
                    refsHtml += ref.Year;

                    for (let color of colors) {
                      refsHtml +=
                      '<span class="refMenuItemLegend" style="background-color: ' + color + '" />';
                    }
                    refsHtml +=
                    '</div>';
                  refsHtml +=
                  '</li>';
                }
              }
            }
          refsHtml +=
          '</ul>' +
        '</li>'
      }
      refsHtml +=
      '</ul>'
      //#endregion
    }

    $('.title > span', $reader).html(title);
    $('.nav', $reader).html(refsHtml);

    $('.refMenuItem').on('click', (e) => {
      $('.refMenuItem').removeClass('selected');

      const $target = $(e.currentTarget);
      const refId = $target.data('refid');

      $target.addClass('selected');
      selectReference(refId);
    });

    if (references.length > 0) {
      $($('.refMenuItem')[0]).trigger('click');
    } else {
      selectReference(0);
    }

    handleRisDownloadButtonClick(references);
  }

  /**
   * Gets the reference code id's from the checked items in the reader
   * filter.
   * @returns {{rows: Array, cols: Array}}
   */
  function getReaderFilterSelection() {
    const colIdList = [];
    const rowIdList = [];

    $('.reader-filter .cols li').each((index, col) => {
      const $col = $(col);
      if ($col.attr('class') === 'checked') {
        colIdList.push($col.data('id'))
      }
    });

    $('.reader-filter .rows li').each((index, row) => {
      const $row = $(row);
      if ($row.attr('class') === 'checked') {
        rowIdList.push($row.data('id'))
      }
    });

    return {
      cols: colIdList,
      rows: rowIdList
    };
  }

  /**
   * Creates the reader selector HTML
   * @returns {string}
   */
  function buildReaderFilter(rowIdList, colIdList) {
    const readerTopFilter = csvData.rows[csvData.totalColDepth - 1]
    const readerSideFilter = []

    for (let i = csvData.totalColDepth; i < csvData.rows.length; i++) {
      const row = csvData.rows[i]
      readerSideFilter.push(row[row.length - 1])
    }

    let colParent = readerTopFilter.length === colIdList.length ? 'checked' : 'indeterminate';
    if (colIdList.length === 0) colParent = 'unchecked';

    let html = '<div class="reader-filter">' +
      '<button id="codeFilterClearButton" class="btn">Clear Filters</button>' +
      '<ul>' +
      '<li class="' + colParent + '" data-parent="true" title="' + csvData.rows[0][0].title + '">' +
      checkboxCheckedSvg +
      checkboxUncheckedSvg +
      checkboxIndeterminateSvg +
      ' <span>' + csvData.rows[0][0].title + '</span>' +
      '</li>' +
      '<ul class="cols">';

    for (const item of readerTopFilter)
    {
      const state = colIdList.indexOf(item.id) >= 0 ? 'checked' : 'unchecked';
      html += '<li class="' + state + '" data-id="' + item.id + '" data-parent="false" title="' + item.title + '">' +
        checkboxCheckedSvg +
        checkboxUncheckedSvg +
        checkboxIndeterminateSvg +
        ' <span>' + item.title + '</span>' +
        '</li>';
    }

    let rowParent = readerSideFilter.length === rowIdList.length ? 'checked' : 'indeterminate';
    if (rowIdList.length === 0) rowParent = 'unchecked';

    html += '</ul>';
    html += '<li class="' + rowParent + '" data-parent="true" title="' + csvData.rows[csvData.totalColDepth][0].title + '">' +
      checkboxCheckedSvg +
      checkboxUncheckedSvg +
      checkboxIndeterminateSvg +
      ' <span>' + csvData.rows[csvData.totalColDepth][0].title + '</span>' +
      '</li>';
    html += '<ul class="rows">';

    for (const item of readerSideFilter)
    {
      const state = rowIdList.indexOf(item.id) >= 0 ? 'checked' : 'unchecked';
      html += '<li class="' + state + '" data-id="' + item.id + '" data-parent="false" title="' + item.title + '">' +
        checkboxCheckedSvg +
        checkboxUncheckedSvg +
        checkboxIndeterminateSvg +
        ' <span>' + item.title + '</span>' +
        '</li>';
    }

    html += '</ul>';
    html += '</ul>';
    html += '</div>';
    return html
  }

  /**
   * Builds the reference reader.
   * @param selectedRowIds
   * @param selectedColIds
   */
  function buildReferenceReader(selectedRowIds, selectedColIds) {
    let risDownloadButton = '';

    if (allowRISDownload) {
      risDownloadButton = '<button id="risDownload" class="btn">Download Listed References</button>';
    }

    let readerHtml =
      '<div class="title clearfix">' +
        '<a class="close">X</a> <span></span>' +
        risDownloadButton +
        '<input type="text" placeholder="Filter" class="reader-filter">' +
        '<select class="filter-opts">' +
          '<option class="opt-all" value="1"> All </option>' +
          '<option class="opt-title" value="2"> Title </option>' +
          '<option class="opt-abstract" value="3"> Abstract </option>' +
          '<option class="opt-author" value="4"> Author </option>' +
        '</select>' +
      '</div>' +
      '<div class="content">' +
        buildReaderFilter(selectedRowIds, selectedColIds) +
        '<div class="navTainer">' +
          '<div class="navGroupSelect">' +
            '<label for="sgroup" style="width:70px;display:block;float:left;">Group by: </label>' +
            '<select id="sgroup" class="grouping-opts">' +
            '<option value="none">None</option>' +
            '<option value="segment">Segment</option>' +
            '</select>' +
          '</div>' +
          '<div class="ref-sort-order">' +
            '<label for="RefSortOrder" style="width:70px;display:block;float:left;">Sort by: </label>' +
            '<select id="RefSortOrder">' +
              '<option value="title">Title</option>' +
              '<option value="author">Author</option>' +
              '<option value="date">Date</option>' +
            '</select>' +
          '</div>' +
          '<div class="nav">' +
          '</div>' +
        '</div>' +
        '<div class="read"></div>' +
      '</div>';

    $reader.html(readerHtml);

    if (segmentAttributes.length <= 0) {
      $('.navGroupSelect').hide();
    }
  }

  /**
   * Performs the search on the reader.
   * @param event
   * @param references
   * @param $readerFilter
   * @param $filterSelect
   */
  function doReaderSearch(event, references, $readerFilter, $filterSelect) {
    if (event !== null && event.which === -1) return;

    const searchTerm = $readerFilter.val().toLowerCase().trim();
    const filterOption = $filterSelect.val();
    let searchReferences = [];

    if (searchTerm.length <= 0) {
      updateReferenceReader(references);
      return;
    }
    references.forEach((ref) => {
      if (filterOption == 1){   // search across All
        if (Object.keys(ref).indexOf('Abstract') > -1){
          let titleRefs = -1;
          let abstractRefs = -1;
          let authorRefs = -1;
          titleRefs = ref.Title.toLowerCase().indexOf(searchTerm);
          abstractRefs = ref.Abstract.toLowerCase().indexOf(searchTerm);
          authorRefs = ref.Authors.toLowerCase().indexOf(searchTerm);
          if (titleRefs !== -1 || abstractRefs !== -1 || authorRefs !== -1){
            searchReferences.push(ref);
          }
        }
      } else if (filterOption == 2){   // search by Title
        if (Object.keys(ref).indexOf('Title') > -1){
          if (ref.Title.toLowerCase().indexOf(searchTerm) !== -1){
            searchReferences.push(ref);
          }
        }
      } else if (filterOption == 3){   // search by Abstract
        if (Object.keys(ref).indexOf('Abstract') > -1){
          if (ref.Abstract.toLowerCase().indexOf(searchTerm) !== -1){
            searchReferences.push(ref);
          }
        }
      } else if (filterOption == 4){   // search by Author
        if (Object.keys(ref).indexOf('Authors') > -1){
          if (ref.Authors.toLowerCase().indexOf(searchTerm) !== -1){
            searchReferences.push(ref);
          }
        }
      }
    });

    // final line: always do the update
    updateReferenceReader(searchReferences);
  }

  /**
   * Shows the reader for the given row and column id lists.
   * @param rowIdList
   * @param colIdList
   */
  function toggleReader(rowIdList, colIdList) {
    const references = getFilteredReferences(rowIdList, colIdList);
    buildReferenceReader(rowIdList, colIdList);
    updateReferenceReader(references);
    const $readerFilter = $('.reader-filter');
    const $filterSelect = $('.filter-opts');

    $readerFilter.on('keydown', (e) => {
      doReaderSearch(e, references, $readerFilter, $filterSelect);
    });

    $filterSelect.on('change', (e) => {
      doReaderSearch(null, references, $readerFilter, $filterSelect);
    });

    $('.grouping-opts').on('change', (e) => {
      updateReferenceReader(references);
    });

    $('#RefSortOrder').on('change', (e) => {
      updateReferenceReader(references);
    });

    $('.reader-filter li').on('click', (e) => {
      const $target = $(e.currentTarget);
      const klass = $target.attr('class');
      const isParent = $target.data('parent');
      const newKlass = klass === 'checked' ? 'unchecked' : 'checked';
      $('#codeFilterClearButton').attr('disabled', false);

      $target
        .removeClass(klass)
        .addClass(newKlass);

      if (isParent) {
        $target.next().children().each((index, child) => {
          $(child)
            .removeClass('checked')
            .removeClass('unchecked')
            .addClass(newKlass);
        });
      } else {
        const parent = $target.parent().prev();
        $(parent)
          .removeClass('checked')
          .removeClass('unchecked')
          .addClass('indeterminate');
      }

      const newSelection = getReaderFilterSelection();
      const references = getFilteredReferences(newSelection.rows, newSelection.cols);

      updateReferenceReader(references);
    });

    $('#codeFilterClearButton').on('click', function() {
      const $filterItems = $('.reader-filter li');
      for (const item of $filterItems){
        const $item = $(item);
        if ($item.hasClass('unchecked')){
          // do nothing; already in target state
        } else if ($item.hasClass('checked')){
          $item.removeClass('checked');
          $item.addClass('unchecked');
        } else if ($item.hasClass('indeterminate')){
          $item.removeClass('indeterminate');
          $item.addClass('unchecked');
        }
      }

      $('#codeFilterClearButton').attr('disabled', true);
      const newSelection = getReaderFilterSelection();
      const references = getFilteredReferences(newSelection.rows, newSelection.cols);
      updateReferenceReader(references);
    })

    $('.close', $reader).on('click', () => {
      $('.refMenuItem').off();
      $('.reader-filter li').off();
      $reader.removeClass('open');
      $veil.removeClass('open');
    });

    $veil.addClass('open');
    $reader.addClass('open');
  }

  /**
   * Creates the external url popup.
   * @param dataAxis
   * @param headerId
   * @param pageX
   * @param pageY
   */
  function createExtUrlPopup(dataAxis, headerId, pageX, pageY) {
    const filteredExtUrlAttr = externalURLedAttributes.filter(attr =>
      attr.AttributeId === headerId &&
      attr.AttributeName !== null &&
      attr.AttributeName !== undefined &&
      attr.AttributeName !== '' &&
      ((attr.AttributeDescription !== null &&
        attr.AttributeDescription !== undefined &&
        attr.AttributeDescription !== '') ||
        (attr.ExtURL !== undefined &&
        attr.ExtURL !== null &&
        attr.ExtURL !== '' &&
        attr.ExtType !== undefined &&
        attr.ExtType !== null &&
        attr.ExtType !== '')));
    const popupHasAttributeData = filteredExtUrlAttr.length > 0;

    if (!popupHasAttributeData) return false;

    let popUpHtml = '<div class="overlay-text" data-header-id="' + headerId + '" data-axis="' + dataAxis + '">';

    for (const attribute of filteredExtUrlAttr) {
      popUpHtml += '<h4>' + attribute.AttributeName + '</h4>';

      if (attribute.AttributeDescription !== null &&
        attribute.AttributeDescription !== undefined &&
        attribute.AttributeDescription.length > 0) {
        popUpHtml += '<p>' + attribute.AttributeDescription + '</p>';
      }

      if (attribute.ExtURL !== undefined &&
        attribute.ExtURL !== null &&
        attribute.ExtURL !== '' &&
        attribute.ExtType !== undefined &&
        attribute.ExtType !== null &&
        attribute.ExtType !== '') {
        popUpHtml += '<a class="overlay-link" href="' + attribute.ExtURL + '" target="_blank">' + attribute.ExtType + '</a>';
      }
    }

    popUpHtml += '<p class="text-center text-muted">(click to view records)</p></div>'

    $attributeTooltipContent.html(popUpHtml);
    $attributeTooltip.addClass('show');

    $('.close-tooltip').on('click', (e) => {
      $attributeTooltip.removeClass('show');
    });

    $attributeTooltipContent.on('click', (e) => {
      $attributeTooltip.removeClass('show');

      const $target = $('.overlay-text');
      const headerId = parseInt($target.data('header-id'));
      const axis = $target.attr('data-axis');

      if (axis === 'col') {
        toggleReader([], [headerId]);
      } else if (axis === 'row') {
        toggleReader([headerId], []);
      }
    });

    // dynamically calculate and adjust the elements position to always draw it within the window's bounds
    const overlayHeight = $attributeTooltip.height();
    const overlayWidth = $attributeTooltip.width();
    const pageHeight = $window.height();
    const pageWidth = $window.width();

    let top = pageY;
    let left = pageX;

    if ((overlayWidth + left) > pageWidth) {
      left -= overlayWidth - 10;
    } else {
      left += 10;
    }

    if ((overlayHeight + top) > pageHeight) {
      top -= overlayHeight - 10;
    } else {
      top += 10;
    }

    $attributeTooltip.css({
      top: top,
      left: left
    });

    return true;
  }

  /**
   * Handles the table click to show the reader dialog.
   */
  function handleTableClick() {
    //#region Header Click shows popup
    // when clicking the row (i.e - side headers)
    $('.clickable-row').on('click', (e) => {
      const $target = $(e.currentTarget);
      const headerId = $target.data('id');
      const createdPopup = createExtUrlPopup('row', headerId, e.pageX, e.pageY);

      if (!createdPopup) {
        toggleReader([headerId], []);
      }
    });

    // when clicking the column (i.e - top headers)
    $('.clickable-col').on('click', (e) => {
      const $target = $(e.currentTarget);
      const headerId = $target.data('id');
      const createdPopup = createExtUrlPopup('col', headerId, e.pageX, e.pageY);

      if (!createdPopup){
        toggleReader([], [headerId]);
      }
    });
    //#endregion

    $('.cell').on('click', (e) => {
      const $target = $(e.currentTarget);
      const totalCount = $target.data('totalCount');

      if (totalCount === 0) {
        return;
      }

      let colIds = $target.data('colid');
      let rowIds = $target.data('rowid');

      if (isNaN(colIds)) {
        colIds = colIds.split(',').map(id => parseInt(id));
      } else {
        colIds = [colIds]
      }

      if (isNaN(rowIds)) {
        rowIds = rowIds.split(',').map(id => parseInt(id));
      } else {
        rowIds = [rowIds]
      }

      toggleReader(rowIds, colIds);
    });
  }

  /**
   *  handle the about button click to show the about map reader dialog
   */
  function handleAboutClick() {
    $('.menu-about').on('click', e => {
      let aboutHtml = '<div class="title clearfix">' +
        '<a class="close">X</a> <span>About This Map</span>' +
        '</div>' +
        '<div class="content">' +
        '<div class="read">' + aboutContent + '</div>' +
        '</div>';

      $reader.html(aboutHtml);

      $('.close', $reader).on('click', () => {
        $reader.removeClass('open');
        $veil.removeClass('open');
      });

      $veil.addClass('open');
      $reader.addClass('open');
    });
  }

  /**
   * Handles the study submission click to show the information on how to
   * submit a new study to the map.
   */
  function handleStudySubmissionClick() {
    $('.menu-studysubmit').on('click', e => {
      let studySubmitHtml =
      '<div class="title clearfix">' +
        '<a class="close">X</a> <span> Submit a Study </span>' +
      '</div>' +
      '<div class="content">' +
        '<div class="read">' + studySubmissionContent + '</div>' +
      '</div>';

      $reader.html(studySubmitHtml);

      $('.close', $reader).on('click',() => {
        $reader.removeClass('open');
        $veil.removeClass('open');
      });

      $veil.addClass('open');
      $reader.addClass('open');
    });
  }

  /**
   * Makes the headers hide/show.
   */
  function handleExpandClick() {
    const $menuExpand = $('.menu-expand');
    const $topTable = $('table', $topHead);
    const $sideTable = $('table', $sideHead);

    $menuExpand.on('click', e => {

      if ($topTable.find('.collapsed').length > 0 || $sideTable.find('.collapsed').length > 0) {
        alert('You cannot hide the headers when they are collapsed.');
        return;
      }

      $menuExpand.toggleClass('active');

      if ($menuExpand.hasClass('active')) {
        $topTable.height('auto');
        $sideTable.width('auto');
      } else {
        $topTable.height(topColHeight);
        $sideTable.width(sideColWidth);
      }

      $('.header, .header-can-hide').slideToggle(200, function () {
          adjustTable();
      });
    });
  }

  /**
   * Toggles fullscreen mode.
   */
  function handleFullscreenClick() {
    const $menuFullscreen = $('.menu-fullscreen');

    $menuFullscreen.on('click', e => {
      toggleFullScreen();
      $menuFullscreen.toggleClass('active');
    });
  }

  /**
   * Toggles reader mode.
   */
  function handleReaderClick() {
    const $menuReader = $('.menu-reader');

    const colIdList = csvData.rows[csvData.totalColDepth - 1].map(item => item.id)
    const rowIdList = []

    for (let i = csvData.totalColDepth; i < csvData.rows.length; i++) {
      const row = csvData.rows[i]
      rowIdList.push(row[row.length - 1].id)
    }

    $menuReader.on('click', e => {
      toggleReader(rowIdList, colIdList);
      $menuReader.toggleClass('active');
    });
  }

  /**
   * Toggles the column collapse.
   * @param miss
   * @param count
   */
  function toggleTopColCollapse(miss, count) {
    const max = miss + count;

    $('.top-head tr').each((rowIndex, row) => {
      if (rowIndex <= 1) return;
      let total = 0;

      $(row).children().each((colIndex, cell) => {
        const $cell = $(cell);
        const colSpan = parseInt($cell.attr('colspan'));
        total += colSpan;

        if (total > miss && total <= max) {
          if (total - 1 === miss) {
            $cell.toggleClass('first');
          }

          if (total - 1 === max) {
            $cell.toggleClass('last');
          }

          $cell.toggleClass('collapsed');
        } else if (total > max) {
          return false;
        }
      });
    });

    buildTableRows();
    adjustTable();

    $pivotBody.trigger('scroll');

    // Update data in the table.
    updateReferenceCounts();
    updateTableDataView();
  }

  /**
   * Toggles the row collapse.
   * @param miss
   * @param count
   */
  function toggleSideColCollapse(miss, count) {
    const max = miss + count;
    let total = 0;

    $('.side-head .level-2').each((index, cell) => {
      const $cell = $(cell);
      const rowSpan = parseInt($cell.attr('rowspan'));
      total += rowSpan;

      if (total > miss && total <= max) {
        if (total - 1 === miss) {
          $cell.toggleClass('first');
        }

        if (total - 1 === max) {
          $cell.toggleClass('last');
        }

        $cell.toggleClass('collapsed')
      } else if (total > max) {
        return false;
      }
    });

    total = 0;

    $('.side-head .level-3').each((index, cell) => {
      const $cell = $(cell);
      const rowSpan = parseInt($cell.attr('rowspan'));
      total += rowSpan;

      if (total > miss && total <= max) {
        if (total - 1 === miss) {
          $cell.toggleClass('first');
        }

        if (total - 1 === max) {
          $cell.toggleClass('last');
        }

        $cell.toggleClass('collapsed')
      } else if (total > max) {
        return false;
      }
    });

    buildTableRows();
    adjustTable();

    $pivotBody.trigger('scroll');

    // Update data in the table.
    updateReferenceCounts();
    updateTableDataView();
  }

  /**
   * Collapse all the rows and columns in the map.
   */
  function collapseAll(){
    if (collapseColumnHeaders)
    {
      const $colHeaders =  $('.level-1')
        .filter(function() {
          return this.colSpan > 1;
        });

      $colHeaders.each((index, cell) => {
        const $cell = $(cell);
        
        $cell.toggleClass('collapsed');
        const count = parseInt($cell.attr('colspan'));
        let miss = 0;

        let $prev = $cell.prev();

        while ($prev.length > 0) {
          try {
            miss += parseInt($prev.attr('colspan'))
            $prev = $prev.prev();
          }
          catch (e) {
            break;
          }
        }

        if (count > 0) {
            toggleTopColCollapse(miss, count);
        }
      });
    }

    if (collapseRowHeaders)
    {
      const $rowHeaders =  $('.level-1').filter(function() {
        return this.rowSpan > 1;
      });

      $rowHeaders.each((index, cell) => {
        const $cell = $(cell);
        $cell.toggleClass('collapsed');

        const count = parseInt($cell.attr('rowspan'));
        let miss = 0;
        $('.side-head .level-1').each((index, otherCell) => {
          const $otherCell = $(otherCell);

          if ($otherCell.text() !== $cell.text()) {
            miss += parseInt($otherCell.attr('rowspan'));
          } else {
            return false;
          }
        });

        if (count > 0) {
            toggleSideColCollapse(miss, count);
        }
      });
    }
  }

  /**
   * Toggles collapsing columns and rows.
   */
  function handleTableRowColCollapse() {
    // Manage column collapse.
    $('.btnColCollapse').on('click', e => {
      const $target = $(e.currentTarget);
      const $cell = $target.parent().parent();
      $cell.toggleClass('collapsed');
      $cell.toggleClass('busy');

      const count = parseInt($cell.attr('colspan'));
      let miss = 0;

      let $prev = $cell.prev();

      while ($prev.length > 0) {
        try {
          miss += parseInt($prev.attr('colspan'))
          $prev = $prev.prev();
        }
        catch (e) {
          break;
        }
      }

      if (count > 0) {
        setTimeout(() => {
          toggleTopColCollapse(miss, count);
          $cell.toggleClass('busy');
        }, 50);
      } else {
        $cell.toggleClass('busy');
      }
    });

    // Manage row collapse.
    $('.btnRowCollapse').on('click', e => {
      const $target = $(e.currentTarget);
      const $cell = $target.parent().parent();
      $cell.toggleClass('collapsed');
      $cell.toggleClass('busy');

      const count = parseInt($cell.attr('rowspan'));
      let miss = 0;

      $('.side-head .level-1').each((index, cell) => {
        const $otherCell = $(cell);

        if ($otherCell.text() !== $cell.text()) {
          miss += parseInt($otherCell.attr('rowspan'));
        } else {
           return false;
        }
      });

      if (count > 0) {
        setTimeout(() => {
          toggleSideColCollapse(miss, count);
          $cell.toggleClass('busy');
        }, 50);
      } else {
        $cell.toggleClass('busy');
      }
    });
  }

  /**
   * Adjusts the table as the window is resized.
   */
  function adjustTable() {
    const bodyWidth = $pivotTable.width() - $sideHead.width();
    const topHeadWrapperCssHeight = $topHead.height();
    const topHeadWrapperCssPaddingLeft = $sideHead.width();
    const topHeadCssWidth = bodyWidth;
    const bodyCssWidth = bodyWidth - 1;
    let sideHeadCssHeight = $window.height() - $topHead.height() - $footer.height() - $menu.height() - 48;
    let bodyCssHeight = sideHeadCssHeight;

    $header = $('.header')

    if ($header.length > 0 && $header.css('display') !== 'none') {
      sideHeadCssHeight = sideHeadCssHeight - $header.height() - 8;
      bodyCssHeight = sideHeadCssHeight;
    }

    $topHeadWrapper.css({
      'height': topHeadWrapperCssHeight,
      'padding-left': topHeadWrapperCssPaddingLeft
    });

    $topHead.css({
      'width': topHeadCssWidth
    });

    $topHeadTable.css({
      'margin-left': '0px'
    });

    $sideHead.css({
      'height': sideHeadCssHeight
    });

    $sideHeadTable.css({
      'margin-top': '0px'
    });

    $pivotBody.css({
      overflow: 'scroll',
      width: bodyCssWidth,
      height: bodyCssHeight
    });

    $pivotBody.scroll(function (e) {
      $topHeadTable.css({
        'margin-left': e.target.scrollLeft * -1
      });

      $sideHeadTable.css({
        'margin-top': e.target.scrollTop * -1
      });
    });
  }

  function UpdateRecordCount() {
    if (!showRecordCount) return;

    const colIdList = csvData.rows[csvData.totalColDepth - 1].map(item => item.id)
    const rowIdList = []

    for (let i = csvData.totalColDepth; i < csvData.rows.length; i++) {
      const row = csvData.rows[i]
      rowIdList.push(row[row.length - 1].id)
    }

    const references = getFilteredReferences(rowIdList, colIdList);
    $recordCount.html('(' + references.length + ')');
  }

  // Call all the methods to initialize the page.
  createSettingsPanel();
  buildTable();
  adjustTable();
  buildLegend();
  handleExpandClick();
  handleFullscreenClick();
  handleReaderClick();
  handleTableRowColCollapse();

  // Update the record count on first load.
  UpdateRecordCount();

  if(collapseColumnHeaders || collapseRowHeaders) {
    collapseAll();
  }

  if (aboutContent.trim().length === 0) {
    $('.menu-about').hide();
  }
  else {
    handleAboutClick();

    if (aboutPopup) {
      $('.menu-about').trigger('click');
    }
  }

  if (studySubmissionContent.trim().length === 0) {
    $('.menu-studysubmit').hide();
  } else {
    handleStudySubmissionClick();
  }

  // Show the loader.
  const $loader = $('.loader');
  const windowHeight = $window.height() + 200;

  $window.resize(adjustTable);

  // Slide the up after all is done.
  $loader
    .css({
      'top': -windowHeight,
      'bottom': windowHeight
    });

  // Removes the loader after the animation is complete.
  setTimeout(() => {
    $loader.remove();
  }, 2000);
});

  </script>
</body>
</html>
