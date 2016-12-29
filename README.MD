
 
<p align="center"><img src="http://puu.sh/qlIQC/7b9adb7a67.png" alt="hackemon"></p>

<p align="center"><b>"Gotta Hack'em All!"</b></p>
<p align="center"><h2 align="center">www.hackemon.io</h2></p>

<br><br> <h1><b>The Multi-Platform Pokemon-Go farming bot on a whole new human level is here! </b></h1><br><h2><b>"Now</b> you officially have no excuse for exercising anymore, you are free to sit back on your ass and eat your pizza while drinking your fav beer ;)"</h2>
 
 *PS: If Issues has been closed on github, please visit the forums for that:
 <br>
 [→Click here Check out the official Hackemon Forums](http://www.hackemon.io)
 <br>
 [→Click here to join disucssion & News on Discord](https://discord.gg/mMhuG6q)
 <br><br>
 <h1>Its back! up and running on the latest API, time to continue the genius plans we had!</h1>
<br><br>
<p align="center"><img src="http://puu.sh/rlrWd/4fa6c91d80.jpg" alt="settings"></p>
<p align="center"><img src="http://puu.sh/rnHMF/07856b5b47.jpg" alt="settings"></p>
<p align="center"><img src="http://puu.sh/rlrXJ/1a0ed0e7d5.png" alt="settings"></p>
<p align="center"><img src="http://puu.sh/rls14/c7c1e04417.png" alt="settings"></p>
<p align="center"><img src="http://puu.sh/sjHUj/27bdc9f99e.png" alt="settings"></p>
<p align="center"><img src="http://puu.sh/sjHKp/8f468364d4.png" alt="settings"></p>
<p align="center"><img src="http://puu.sh/sjHLK/abe0e54813.png" alt="settings"></p>
 

<h2><b>Hackémon</b> is designed with a primary intent for it to be very rich in logic, highly customizable, brightly intuitive and of course the most core principle, Undetectability (Ban-Safe) through utilizing human road/path finding under customizable settings with presets.</h2>
<br>


<h1>Hackemon 2.07</h1> 
* Hackemon is back and running on the latest API, however unfortunately the main POGO reverse engineers from "Bossland GmbH" company that were taking care of cracking the API 
decided to no longer release it for free, and now they run a paid hashing service for map scanners & bots and they divided it into packages based on an RPM (Requests per Minute)
model, and users now will have to purchase  one of the keys they offer and each lasts for one month, for Hackemon you just need to buy the basic 150 RPM key for now and you will be able to run full speed 2-3 separate instances max per each 150 RPM key, if you want to run more instances buy another key for other 2-3 accounts or a bigger package,  you will be able to insert the key(s) in Hackemon's 'Accounts Dialogs'.
<p align="center"><img src="http://puu.sh/t4AJx/a2fd9b2d60.png" alt="settings"></p>

Bare in mind i have 0 profit off of this, as you will be purchasing the key from an external service.

*To purchase an RPM key please refere to* : https://talk.pogodev.org/d/51-api-hashing-service-by-pokefarmer

* Finally fixed "Clear Last Saved Location" bug and renamed to "Rebase"
<h1>Hackemon 2.06</h1> 
* Added a unique challenge/captcha handler for users to solve, long time spent on it and required some hacks to make it work properly. 
Once you are challenged, Hackemon will display a window pop up showing the captcha for you to solve (using its own browser/renderer), once you've completed the 
challenge and press 'Verify' Hackemon will automatically intercept the network traffic and grab the required token for validation and notify the niantic server, incase the response
back from niantic was success , bot will continue its task normally, otherwise it'll close current popup and display another challenge.
*click image to see it in action*
<a href="https://www.youtube.com/watch?v=cFdJZSnTlMg"><p align="center"><img src="http://puu.sh/sp0rb/9e90d27bad.jpg" alt="settings"></p></a>

* Walking now allows you to set "Minimum different pokestops to be visited before visiting the same one again" so that it prevents walking only across limited amount of pokestops
(as some reported it walking only between 2 pokestops and ignoring the rest), while it still sorts the pokestops by shortest distance.

* Added an option in the Pokemon inventory tab to disable "Auto refresh" and manual refresh the inventory as requested.

* Updated ball picking logic so that it prioritize the fittest ball based on the pokemon's CP, however if it ran out of pokemon balls it will still use other balls most fitting the current 
situation.

* Fixed a bug where it still attempt to encounter some pokemons when it doesnt have any pokeballs left which made it enter an infinite attempt loop in some cases.

<br>
<b><h1>→ List of Current Features:</h1></b>
<b>
<ul>
<li>Runs on all PC Operating Systems : Windows,Linux,Mac,OpenBSD, etc.. </li>
  <li> Supports Google & PTC Accounts</li>
               <li> Kick-ass Intuitive & Responsive/Scalable GUI </li>
                <li> <b> Realtime Visualized interactive map.</b></li>
                <li> Optimum human walking featuring SMART_MODE (curvy undetectable paths) , real WALKING,DRIVING,BIKING ROAD MAPS and other routes.
                <li> Interactive region editor embeded in map to created multiple timed regions for randomized roaming [Under Re-write as of Hackemon 2.0]</li>
                 <li> Visits all pokestops (non cooldowned) in the region based on many heuristics</li>
                <li> Catches all pokemons while walking to pokestops</li>
                <li> Consumes Raspberries when needed to gain a higher chance to catch a pokemon.</li>
                <li> <b>Multiple Parallel Async Rare Pokemon Sniping exploit (Very fast XP)</b></li>
                <li> <b> Manual-Sniping </b></li>
                <li> Rich Break-Handler with option to take a break based on pokestops, pokemon cought, levels gained caps or just every x min and max time passed.</li>
                <li> Lucky Egg Utilization for boosting XP.</li>
                <li> Auto-Egg Incubation</li>
                <li> Transferes the pokemons to the professor and gain candy</li>
                <li> Auto Evolve the pokemons</li>
                <li>Auto Items Recycling </li>         
                <li> fully interactive pokemon inventory in which you can manually transfer, evolve and power-up each</li>
                <li> Auto collects Rewards on level up.</li>
		<li> Captcha challenge display in custom browser with success listener.
                <li> Proxy Support (SOCKS & HTTP) [Under re-planning as of Hackemon 2.0]</li>
                <li> Lots of Humanization and other settings to set under the setting tab</li>
                <li> Ban-safe</li>
                <li> Automatic Save</li>
                <li> Easy Account Switch Feature</li>
</ul>
</b>
<br>
<br>
<b><h1>→ Installation:</h1></b>
<p>
All you only need to have in-case you didn't is <b><a href="http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html">Java 8</a></b> to be able to run this wonderful bot on any operating system of your liking, extract the
zipped files to a destination, run & enjoy!.
<br><br>
  <b>  Linux Installation Tips:</b>
*Make sure to use Oracle JDK 8 instead of OpenJDK 8*
    
</p>

<br>
<b><h1>→ Tips:</h1></b>
<ul>
<li>Make sure you you set the longitude and latitude locations under the settings -> general tab, otherwise you might hard teleport and get some soft ban for a short period of time.</li>
<li>Make sure you set decent delay times between various tasks under the settings Humanization tab to avoid any possible softbans.</li>

</ul>
<br>
<p><h4>Since this took and will take a lot of my time (many hours a day) to make it at tops, feel free to donate the amount you want, and if this goes paid any time soon, you will get it for free ^.^</h4></p>

[![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)]
(https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=U7BRDDXTZ8UHE)

<h1>Credits</h1>
Thanks to AeonLucid for his protos used in this project : https://github.com/AeonLucid/POGOProtos
<h1>Legal</h1>
This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by Niantic, The Pokémon Company, Nintendo or any of its affiliates or subsidiaries. This is an independent and unofficial Bot for educational use ONLY. Use at your own risk.

	
