// ==UserScript==

// @name         ScriptGTD-Snow

// @namespace    http://tampermonkey

// @version      2025-10-02

// @description  KhĂ´ng shared linh linh lĂ  Ä‘Æ°á»£c, script giĂºp hack gacha thĂ¡p Ä‘á»

// @author       Snow

// @match        https://gtd-cdn.gamehollywood.com/GTD_service/index_gh.html*

// @icon         https://www.google.com/s2/favicons?sz=64&domain=gamehollywood.com

// @grant        none

// ==/UserScript==

(function () {

  'use strict';
    // 1. Chá»‰nh time gacha x
      S_GACHA.REWARD_TIME_MS = 1000;
    // 2. Chá»‰nh rate
 setInterval(() => {
    if (S_GACHA.data[1].B === 9) {
        S_GACHA.data[1].B = 0;
        S_GACHA.data[1].C = 0;
        S_GACHA.data[1].D = 0;
        S_GACHA.data[1].S = 100;
        console.log("ÄĂ£ reset data[1]");
    }
}, 100); // kiá»ƒm tra má»—i 100ms


})();// ==UserScript==
// @name        New script
// @namespace   Violentmonkey Scripts
// @match       *://example.org/*
// @grant       none
// @version     1.0
// @author      -
// @description 12:06:58 7/9/2025
// ==/UserScript==