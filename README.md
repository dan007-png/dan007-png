<div align="center">

<!-- Início do SVG Animado -->
<svg xmlns="http://www.w3.org/2000/svg" font-family="ConsolasFallback,Consolas,monospace" width="1180" height="530" viewBox="0 0 1180 530" fontsize="15px">
<style>
@font-face {
  src: local('Consolas'), local('Consolas Bold');
  font-family: 'ConsolasFallback';
  font-display: swap;
  -webkit-size-adjust: 109%;
  size-adjust: 109%;
}
.key      { fill: #5EEAD4; }   
.value    { fill: #E5E7EB; }   
.cc       { fill: #5f6b7a; }   
.addColor { fill: #39ff14; }   
.delColor { fill: #ef4444; }   
text, tspan { white-space: pre; }

/* ANIMAÇÕES CYBER */
@keyframes flicker {
  0%, 19.1%, 21.2%, 43.3%, 45.4%, 67.5%, 69.6%, 81.7%, 83.8%, 95.9%, 100% { opacity: 1; }
  19.2%-21.1%, 43.4%-45.3%, 67.6%-69.5%, 81.8%-83.7%, 96%-99% { opacity: 0.4; }
}

@keyframes pulse {
  0%, 100% { opacity: 1; filter: drop-shadow(0 0 2px #00f0ff); }
  50% { opacity: 0.7; filter: drop-shadow(0 0 8px #00f0ff); }
}

@keyframes scan {
  0% { transform: translateY(-100%); }
  100% { transform: translateY(100%); }
}

.anim-flicker { animation: flicker 3s linear infinite; }
.anim-pulse { animation: pulse 4s ease-in-out infinite; }
.ascii-art { animation: pulse 5s ease-in-out infinite; }
</style>
<rect width="1180px" height="530px" fill="#0a0b10" rx="15" stroke="rgba(0, 240, 255, 0.15)" stroke-width="2"/>

<!-- Efeito de Scanline (Linha de Varredura) -->
<rect width="1180" height="20" fill="rgba(0, 240, 255, 0.03)" pointer-events="none">
  <animate attributeName="y" values="0;530;0" dur="10s" repeatCount="indefinite" />
</rect>

<g transform="translate(22,20) scale(0.42,0.88)" class="ascii-art">
<text x="0" y="0" fill="#00f0ff" class="ascii">
<tspan x="-10" y="-30">                                                        .:  .::::.                                                             </tspan>
<tspan x="-10" y="-21">                                                  .   .       .   ...-                                                         </tspan>
<tspan x="-10" y="-12">                                               :. .::                .:                                                        </tspan>
<tspan x="-10" y="-3">                                              :  -                                                                             </tspan>
<tspan x="-10" y="6">                                             :.::..         .                                                                  </tspan>
<tspan x="-10" y="15">                                            -.:. :      ..                                                                     </tspan>
<tspan x="-10" y="24">                                           --...:.   .            .. ..:...                                                    </tspan>
<tspan x="-10" y="33">                                          -=.-----:.-::.. .::-+==+***+====---.                                                 </tspan>
<tspan x="-10" y="42">                                         --:-# +**##%####+*+*%%%%%%%%#**+=====:                                                </tspan>
<tspan x="-10" y="51">                                         ==-%%*%@@@@@@%@@@@@@@@%%%%%%##*+==-=--:                                               </tspan>
<tspan x="-10" y="60">                                        :--%@@%@@@@@@@@@@@@@@@@%%%%%%##*+==-----:                                              </tspan>
<tspan x="-10" y="69">                                        .=#@@@@@@@@@@@@@@@@@@@@%%%%%%##*+=-------                                              </tspan>
<tspan x="-10" y="78">                                        .+@@@@@@@@@@@@@@@@@@@@%%%%%%%##*+=-------:                                             </tspan>
<tspan x="-10" y="87">                                       .:+@@@@@@@@@@@@@@@@@@@@%%%%%%###*+==-=----:.                                            </tspan>
<tspan x="-10" y="96">                                       .-*%@@@@@@@@@@@@@@@@@@@@%%%%%%##*+====----:.                                            </tspan>
<tspan x="-10" y="105">                                       :+#%@@@@@@@@@@@@@@@@@@@@@@@@%%##*++==--:::-:                                            </tspan>
<tspan x="-10" y="114">                                       -+#%@@@@@@@@@@@@@@@@@@@@@@@%%###*+++=-::::-:.                                           </tspan>
<tspan x="-10" y="123">                                       :=*%@@@@@@@@@@@@@@@@@@@@@@%%%%##****+=-:::--:                                           </tspan>
<tspan x="-10" y="132">                                        -+%@@@@@@@@%*#*#%@@@@@%%%##=:      :.:-::--:                                           </tspan>
<tspan x="-10" y="141">                                        -*@@@@*+=.    -=#%%%%%##*+=.     .:..  .---:                                           </tspan>
<tspan x="-10" y="150">                                        =*@@%*#%%#*+-..:-*#%@%%*=:      :: ..:..:--.                                           </tspan>
<tspan x="-10" y="159">                                        +*%@%%#*=: :    .-*@@@%*:     +=      ..:--.                                           </tspan>
<tspan x="-10" y="168">                                         #%@@%*-:%-   -.+%%@@@@#:    .#+  ..    .--:    .-                                     </tspan>
<tspan x="-10" y="177">                                     %@@%#%@@%#####*+--=*%%@@@@#:.  .:---........:-- :... .                                    </tspan>
<tspan x="-10" y="186">                                     :-%@@%@@@@@%%###***#@@@@@%#::.---=====----:.:--....:                                      </tspan>
<tspan x="-10" y="195">                                     +%@@@@@@@@@@@@@%%@@@@@@@@@#=::-=+*+++*+++=-::--..:.:.                                     </tspan>
<tspan x="-10" y="204">                                     *@@@#@@@@@@@@@@@@@@@@@@@@%%#=:-=+****+=++=-:---:  .: .                                    </tspan>
<tspan x="-10" y="213">                                     @%@%*@@@@@@@@@@@@@@@@@@@@@#*=-.:==+*+++=---:-=--   :.                                     </tspan>
<tspan x="-10" y="222">                                      %@##@@@@@@@@@@@@@@@@@@@%#*----.:=++++=--::--=.-   :.                                     </tspan>
<tspan x="-10" y="231">                                      @%%#@%@@@@@@@@@@@@@%--#+=.  ::..-=++=--:-::-:   ...                                      </tspan>
<tspan x="-10" y="240">                                       %%@@+@@@@@@@@@@@@@*:##+:   ....-=++=-:::---  :-..                                       </tspan>
<tspan x="-10" y="249">                                        @@@+@@@@@@@@@@@@@%%+###*. ..:-=+=+==:-:--- ::::                                        </tspan>
<tspan x="-10" y="258">                                         @@%#@@@@@@@@@@@@%++==*=-  .:=+====--::-:.  .                                          </tspan>
<tspan x="-10" y="267">                                            =%@@@@@@@@%#=--=-.++.    .-===---::..                                              </tspan>
<tspan x="-10" y="276">                                            :#%@@@@%****+**++#*-.:-: -  .:::::...                                              </tspan>
<tspan x="-10" y="285">                                            .+##@@@+-++#=-==:-..          ::.   .                                              </tspan>
<tspan x="-10" y="294">                                             :**#@%**= .=*****++=-.    :: ..                                                   </tspan>
<tspan x="-10" y="303">                                              +*-*%**%@%#*****+=......:-::.                                                    </tspan>
<tspan x="-10" y="312">                                               +:-+%#@@@%%%*=-....:..:::::                                                     </tspan>
<tspan x="-10" y="321">                                                ::+%%%%%%##+=:..-.:.......      :                                              </tspan>
<tspan x="-10" y="330">                                                 :##+*#%%%%%#+--==-:.::.       .:                                              </tspan>
<tspan x="-10" y="339">                                                #..---%%@@@@@@##**==-:.       ..:                                              </tspan>
<tspan x="-10" y="348">                                                %%.   +*%%#%%%##+==-..        ..::                                             </tspan>
<tspan x="-10" y="357">                                                 @%.  :-:==+++=+--.          ....:                                             </tspan>
<tspan x="-10" y="366">                                                 %%#=     ..:               . ...:                                             </tspan>
<tspan x="-10" y="375">                                                 %%@@#                          .: .                                           </tspan>
<tspan x="-10" y="384">                                                 %%@@@%-                        .  ..                                          </tspan>
<tspan x="-10" y="393">                                                +%@@@%@%%%%#-                                                                  </tspan>
<tspan x="-10" y="402">                                                ++%@@%@%%%%%%+=-:.                                                             </tspan>
<tspan x="-10" y="411">                                                + %%%@%%%%%%%#+=:.                                                             </tspan>
<tspan x="-10" y="420">                                                + :%%%%@%%%###*-..      .                                                      </tspan>
<tspan x="-10" y="429">                                               -*= -#%%%@%%%#*=::..    ...                                                     </tspan>
<tspan x="-10" y="438">                                               -##. -%%@%%%%##+*+--.  .::                                                      </tspan>
<tspan x="-10" y="447">                                               -##-  -%%%%%%%%#***=:  :-:.::                                                   </tspan>
<tspan x="-10" y="456">                                                +*=   :*%%%%%##*+=-  :--.+-.                                                   </tspan>
<tspan x="-10" y="465">                                                *+=+   .*####*++--:-:-=::::                                                    </tspan>
<tspan x="-10" y="474">                                                #+   -  .+****+++=--=-                                                         </tspan>
<tspan x="-10" y="483">                                                +    :=  .--=++++===      .                                                    </tspan>
<tspan x="-10" y="492">                                                =          ..::-==-       .                                                    </tspan>
<tspan x="-10" y="501">                                                +       :    .:-=+                                                             </tspan>
<tspan x="-10" y="510">                                                =     +=      -=+-                                                             </tspan>
<tspan x="-10" y="519">                                                    .--+-     :=*    .     .                                                   </tspan>
<tspan x="-10" y="528">                                                 -. -=+-+     .-**:+.     :=                                                   </tspan>
<tspan x="-10" y="537">                                                 :..-+#:=  .   .+*:       -                                                    </tspan>
<tspan x="-10" y="546">                                                 :+:=++* .     .+#      .-                                                     </tspan>
<tspan x="-10" y="555">                                                  +=-+=.+:.   . ++     .=:                                                     </tspan>
<tspan x="-10" y="564">                                                  *-=---=+.    #       +*                                                      </tspan>
<tspan x="-10" y="573">                                                  *:-+:==+ .  -       .+                                                       </tspan>
<tspan x="-10" y="582">                                                  *: +#+=-..:      ::=-.                                                       </tspan>
<tspan x="-10" y="591">                                                  =-:-*+:=-       -+*#-                                                        </tspan>
<tspan x="-10" y="600">                                                  : --+=:      --. -+*                                                         </tspan>
</text>
</g>
<text x="500" y="30" fill="#E5E7EB">
<tspan x="520" y="30" fill="#00f0ff" fontsize="17px" class="anim-flicker">SIDDHUX9@Neural-grid</tspan> -———————————————————————————————————————————-—-
<tspan x="520" y="50" class="cc">. </tspan><tspan class="key">Subject</tspan><tspan class="cc"> ............................ </tspan><tspan class="value">Siddhu Singh</tspan>
<tspan x="520" y="70" class="cc">. </tspan><tspan class="key">Role</tspan><tspan class="cc"> .......... </tspan><tspan class="value">Blockchain &amp; Full Stack Dev</tspan>
<tspan x="520" y="90" class="cc">. </tspan><tspan class="key">Age</tspan><tspan class="cc" id="age_dots"> ......... </tspan><tspan class="value" id="age_data">20 years, 5 months, 14 days</tspan>
<tspan x="520" y="110" class="cc">. </tspan><tspan class="key">Status</tspan><tspan class="cc"> ........... </tspan><tspan class="value">Building • Learning • Shipping</tspan>
<tspan x="520" y="130" class="cc">. </tspan><tspan class="key">ToolChain</tspan><tspan class="cc"> ............. </tspan><tspan class="value">VS Code, Git, Foundry, Hardhat</tspan>
<tspan x="520" y="150" class="cc">. </tspan>
<tspan x="520" y="170" class="cc">. </tspan><tspan class="key anim-flicker">Neural</tspan>.<tspan class="key anim-flicker">Core</tspan>:<tspan class="cc"> ... </tspan><tspan class="value">Solidity, Rust, TS, JS, Python</tspan>
<tspan x="520" y="190" class="cc">. </tspan><tspan class="key anim-flicker">Neural</tspan>.<tspan class="key anim-flicker">AI</tspan>:<tspan class="cc"> ......................... </tspan><tspan class="value">LangChain, OpenAI, LLMs</tspan>
<tspan x="520" y="210" class="cc">. </tspan><tspan class="key anim-flicker">Neural</tspan>.<tspan class="key anim-flicker">Frontend</tspan>:<tspan class="cc"> ........ </tspan><tspan class="value">HTML/CSS, React, Next.js, Tailwind</tspan>
<tspan x="520" y="230" class="cc">. </tspan><tspan class="key anim-flicker">Neural</tspan>.<tspan class="key anim-flicker">Backend</tspan>:<tspan class="cc"> .. </tspan><tspan class="value">Node.js, Express, MongoDB, Postgres</tspan>
<tspan x="520" y="250" class="cc">. </tspan><tspan class="key anim-flicker">Neural</tspan>.<tspan class="key anim-flicker">Stack</tspan>:<tspan class="cc"> ............. </tspan><tspan class="value">EVM, Smart Contracts, AggLayer</tspan>
<tspan x="520" y="270" class="cc">. </tspan>
<tspan x="520" y="290" fill="#ff007f" class="anim-flicker">- Contact</tspan> -————————————————————————————————________________—————-—-
<tspan x="520" y="310" class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">Mail</tspan>:<tspan class="cc"> ...................... </tspan><tspan class="value">siddhu3116@gmail.com</tspan>
<tspan x="520" y="330" class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">Portfolio</tspan>:<tspan class="cc"> .......................... </tspan><tspan class="value">siddhu.info</tspan>
<tspan x="520" y="350" class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">LinkedIn</tspan>:<tspan class="cc"> ............................ </tspan><tspan class="value">siddhu-singh</tspan>
<tspan x="520" y="370" class="cc">. </tspan><tspan class="key">Grid</tspan>.<tspan class="key">Github</tspan>:<tspan class="cc"> ..................... </tspan><tspan class="value">SIDDHUX9</tspan>
<tspan x="520" y="410" fill="#ff007f" class="anim-flicker">- GitHub Stats</tspan> -————————————————————————————————________________-—-
<tspan x="520" y="430" class="cc">. </tspan><tspan class="key">Repos</tspan>:<tspan class="cc" id="repo_dots"> .. </tspan><tspan class="value" id="repo_data">23</tspan> {<tspan class="key">Contributed</tspan>: <tspan class="value" id="contrib_data">29</tspan>   }  | <tspan class="key">Stars</tspan>:<tspan class="cc" id="star_dots"> .......... </tspan><tspan class="value" id="star_data">13</tspan>
<tspan x="520" y="450" class="cc">. </tspan><tspan class="key">Commits</tspan>:<tspan class="cc" id="commit_dots"> .................. </tspan><tspan class="value" id="commit_data">85</tspan>       | <tspan class="key">Followers</tspan>:<tspan class="cc" id="follower_dots"> ...... </tspan><tspan class="value" id="follower_data">12</tspan>
<tspan x="520" y="470" class="cc">. </tspan><tspan class="key">Lines of Code on GitHub</tspan>:<tspan class="cc" id="loc_dots">. </tspan><tspan class="value" id="loc_data">156,151</tspan> ( <tspan class="addColor" id="loc_add">158,647</tspan><tspan class="addColor">++</tspan>, <tspan id="loc_del_dots">. </tspan><tspan class="delColor" id="loc_del">2,496</tspan><tspan class="delColor">--</tspan> )
</text>
</svg>
<!-- Fim do SVG Animado -->

</div>
