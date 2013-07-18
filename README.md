# TmTheme Editor Variables
Work in progress.
Made, and able to be edited, using http://tmtheme-editor.herokuapp.com/. Shown below is a reference list of variables in the theme editor and where their rules apply in `HTML`, `SCSS`, and `JS` files. Text affected is either wrapped in "*"s or properly italicized.

![Screenshot](/screenshot.png)

#### String
`.SCSS`
* @import *"partials/base"*;
* @include svg(*"gear_white"*);

`.HTML`
* class=*"analytics-body"*
* role=*"main"*

`.JS`
* $(*'.analytics-body'*).addClass(*'loading'*);
* if (!target.hasClass(*'tip-trigger'*)) {

-------

#### Number
`.SCSS`
* width: *32.5*%;
* border: *1*px solid $black-25;

`.JS`
* if (windowWidth > *960*) {
* tooltip.css('z-index', *1500*);

-------

#### Built-in Constant
`.JS`
* *true*, *false*

-------

#### User-defined Constant
`.HTML`
* *&copy*
* *&nbsp*

`.SCSS`
* *px*, *%*

-------

#### Variable
`.JS`
* $(*this*)

-------

#### Keyword
`.SCSS`
* .ie7 *&*
* *@mixin body-padding*($top: 0px, $bottom:0px)
* *@include no-trans;*
* *h4*, *button*

`.JS`
* *if*(tooltip *&&* tooltip.length *>* 0)
* *$*('.loading-overlay').hide();
* modalOpen *=* false;
* *return* layout;

-------

#### Storage
No finding

-------

#### Storage Type
`.JS`
* *function*(block)
* *var* contents;
* *function*(){

-------

#### Class Name
No finding

-------

#### Inherited Storage Type
No finding

-------

#### Function name
`.JS`
* layout.*initModal* = function(id) {
* function *equalizeBedHeights*(){
* layout.*init_listeners* = function() {

-------

#### Function Argument
`.JS`
* layout.init = function(*app, callback*)
* layout.init_modal_listener = function(*context*) {
* layout.initModal = function(*id*) {

-------

#### Tag Name
`.HTML`
* <*body*></*body*>
* <*div*></*div*>

-------

#### Tag Attribute
*In HTML*
* <meta *charset*="utf-8">
* <link *rel*="stylesheet" *type*="text/css"…
* <div *class*="ftr-logo"></div>

`.SCSS`
* *.loading-overlay* {
* @extend *.text*;
* *.panel* > *.panel-grid-3* {

-------

#### Library Function
`.JS`
* modal.*remove*();
* $(document).*find*('ul, dl')

-------

#### Library Constant
`.JS`
* var section = $(this).*parent*();
* var len = panels.*length*;
* tooltip.*width*()

`.SCSS`
* cursor: *pointer*;
* display: *none*;
* margin: 0 *auto*;
* position: *relative*;

-------

#### Library Class Type
`.SCSS`
* *text-align*: center;
* *padding*: 0px;
* *vertical-align*: middle;

*In JS*
* *layout*.initModal = function(id) {
* $(*window*)

-------

#### Library Variable
No findings

-------

#### JSON String
`.JSON`
* *"defaults"*: {
			*"filterable"*: true,
			*"editable"*: true
}

-------

#### Foreground
Line numbers

`.HTML`
* *<* title *>* *RGI | Healthcare Analytics Solution*
* *<!DOCTYPE html>*

`.SCSS`
* .bar *{* 
		margin*:* auto*;*
		width*:* 100%*;*
	*}*

`.JS`
[?]

-------

#### Caret
* The blinking cursor



