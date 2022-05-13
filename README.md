/* ---------------------single CSS----------------------- */

/* display */
.dn {
  display: none;
}
.di {
  display: inline;
}
.db {
  display: block;
}
.dib {
  display: inline-block;
} /* if the element is block level(eg. div, li), using 'inline-any' instead */
/* height */
.h14 {
  height: 14px;
}
.h16 {
  height: 16px;
}
.h18 {
  height: 18px;
}
.h20 {
  height: 20px;
}
.h22 {
  height: 22px;
}
.h24 {
  height: 24px;
}
.hPct100 {
  height: 100%;
}
ul,
li,
ol {
  padding: 0;
  margin: 0;
  list-style: none;
}

/* width,height */
$whList: 14, 16, 18, 22, 24, 20, 50, 70, 100, 120, 140, 160, 180, 200, 220, 250,
  280, 300, 320, 360, 400, 460, 500, 600, 640, 700;
@each $value in $whList {
  .w#{$value} {
    width: #{$value}px;
  }
  .h#{$value} {
    height: #{$value}px;
  }
}
/* line-height */
$lineHeightList: 14, 16, 18, 20, 22, 24, 32;
@each $value in $lineHeightList {
  .lh#{$value} {
    line-height: #{$value}px;
  }
}
/* margin,padding */
$mpList: -1, -3, -20, 1, 2, 4, 5, 8, 10, 15, 20,26, 30, 40, 60;
@each $value in $mpList {
  .ml#{$value} {
    margin-left: #{$value}px;
  }
  .mr#{$value} {
    margin-right: #{$value}px;
  }
  .mt#{$value} {
    margin-top: #{$value}px;
  }
  .mb#{$value} {
    margin-bottom: #{$value}px;
  }
  .m#{$value} {
    margin: #{$value}px;
  }
  .pl#{$value} {
    padding-left: #{$value}px;
  }
  .pr#{$value} {
    padding-right: #{$value}px;
  }
  .pt#{$value} {
    padding-top: #{$value}px;
  }
  .pb#{$value} {
    padding-bottom: #{$value}px;
  }
  .p#{$value} {
    padding: #{$value}px;
  }
}

/* percent width value */
.pct10 {
  width: 10%;
}
.pct15 {
  width: 15%;
}
.pct20 {
  width: 20%;
}
.pct25 {
  width: 25%;
}
.pct30 {
  width: 30%;
}
.pct33 {
  width: 33.3%;
}
.pct40 {
  width: 40%;
}
.pct50 {
  width: 50%;
}
.pct60 {
  width: 60%;
}
.pct66 {
  width: 66.6%;
}
.pct70 {
  width: 70%;
}
.pct75 {
  width: 75%;
}
.pct80 {
  width: 80%;
}
.pct90 {
  width: 90%;
}
.pct100 {
  width: 100%;
}

/* border-color name rule:  border(b)-position(l/r/t/b/d)-width(null/2)-style(null/sh)-color(first one letter/first two letter) |-> All colors are safe color*/
.bdc {
  border: 1px solid #ccc;
}
.blc {
  border-left: 1px solid #ccc;
}
.brc {
  border-right: 1px solid #ccc;
}
.btc {
  border-top: 1px solid #ccc;
}
.bbc {
  border-bottom: 1px solid #ccc;
}
.bdd {
  border: 1px solid #ddd;
}
.bld {
  border-left: 1px solid #ddd;
}
.brd {
  border-right: 1px solid #ddd;
}
.btd {
  border-top: 1px solid #ddd;
}
.bbd {
  border-bottom: 1px solid #ddd;
}
.bde {
  border: 1px solid #eee;
}
.ble {
  border-left: 1px solid #eee;
}
.bre {
  border-right: 1px solid #eee;
}
.bte {
  border-top: 1px solid #eee;
}
.bbe {
  border-bottom: 1px solid #eee;
}

/* background-color name rule:  bg - (key word/Hex color) |-> All colors are safe color */
.bgfb {
  background-color: #fbfbfb;
}
.bgf5 {
  background-color: #f5f5f5;
}
.bgf0 {
  background-color: #f0f0f0;
}
.bgeb {
  background-color: #ebebeb;
}
.bge0 {
  background-color: #e0e0e0;
}
.bgf {
  background-color: #fff;
}
.bgf8 {
  background-color: #f8f8f8;
}
/* safe color */
.gf {
  color: #fff;
}
.g0 {
  color: #000;
}
.g3 {
  color: #333;
}
.g6 {
  color: #666;
}
.g9 {
  color: #999;
}
.gc {
  color: #ccc;
}
.red {
  color: #f00000;
}
.orange {
  color: #ffc343;
}
.gf2 {
  color: rgba(255, 255, 255, 0.2);
}
.gf4 {
  color: rgba(255, 255, 255, 0.4);
}
.gf5 {
  color: rgba(255, 255, 255, 0.5);
}
.gf6 {
  color: rgba(255, 255, 255, 0.6);
}
.gf8 {
  color: rgba(255, 255, 255, 0.8);
}
/* font-size */
.f0 {
  font-size: 0;
}
.f10 {
  font-size: 10px;
}
.f12 {
  font-size: 12px;
}
.f13 {
  font-size: 13px;
}
.f14 {
  font-size: 14px;
}
.f16 {
  font-size: 16px;
}
.f18 {
  font-size: 18px;
}
.f20 {
  font-size: 20px;
}
.f24 {
  font-size: 24px;
}
.f28 {
  font-size: 28px;
}
.f32 {
  font-size: 32px;
}
.f80 {
  font-size: 80px;
}

/* font-style */
.n {
  font-weight: normal;
  font-style: normal;
}
.b {
  font-weight: bold;
}
.i {
  font-style: italic;
}
/* text-align */
.tc {
  text-align: center;
}
.tr {
  text-align: right;
}
.tl {
  text-align: left;
}
.tj {
  text-align: justify;
}

.vm {
  vertical-align: middle;
}
.vtb {
  vertical-align: text-bottom;
}
.vtt {
  vertical-align: text-top;
}
.vb {
  vertical-align: bottom;
}
.vt {
  vertical-align: top;
}
.vsub {
  vertical-align: sub;
}
.vn {
  vertical-align: -2px;
}
/* float */
.l {
  float: left;
}
.r {
  float: right;
}
/* clear */
.cl {
  clear: both;
}
/* position */
.rel {
  position: relative;
}
.abs {
  position: absolute;
}

/* cursor */
.poi {
  cursor: pointer;
}
.def {
  cursor: default;
}
/* overflow */
.ovh {
  overflow: hidden;
}
.ova {
  overflow: auto;
}
/* visibility */
.vh {
  visibility: hidden;
}
.vv {
  visibility: visible;
}

.ell {
  text-overflow: ellipsis;
  white-space: nowrap;
  overflow: hidden;
}
.ell2line {
  overflow: hidden;
  -webkit-line-clamp: 2;
  -moz-line-clamp: 2;
  -ms-line-clamp: 2;
  -o-line-clamp: 2;
  line-clamp: 2;
  line-height: 1.5;
  -webkit-box-orient: vertical;
  -moz-box-orient: vertical;
  -ms-box-orient: vertical;
  -o-box-orient: vertical;
  box-orient: vertical;
  display: -webkit-box;
  display: -moz-box;
  display: -ms-box;
  display: -o-box;
  word-break: break-all;
  -webkit-box-orient: vertical;
}

.flex {
  display: flex;
}
.flexCol {
  display: flex;
  flex-direction: column;
}
.flexVM {
  display: flex;
  align-items: center;
  justify-content: center;
}
.flexSP {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.flexSE {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
}
.flex0 {
  flex-grow: 0;
  flex-shrink: 0;
}
.flex1 {
  flex-grow: 1;
  min-width: 0;
}
