// ==UserScript==
// @name         Quizlet Match Hacker
// @namespace    Ray D. Adams
// @version      1.1
// @description  The time will freeze and the answers will be the same color
// @author       You
// @match        https://quizlet.com/*/*
// @grant        none
// @license MIT
// ==/UserScript==

//Ignore the variable gravityScore because it doesn't work any more, but I decided to keep the code here
var gravityScore,
	 href = window.location.href;
	//<br><br><button class="UIButton" id="customWaitButton" type="button"><span class="UIButton-wrapper"><span>Inject</span></span></button>
(function() {	
