# Helicopter-Crash-Sites-for-Sakhal






The below config’s were made for the sole purpose of bringing the immersive feeling back to dayz on the newly relased map Sakhal, I may be the only one who has done this, I take no credit. I did this purely for everyone to enjoy. 

This will be a rather easy install, 

The below entry for the events.xml file will need to be copied and then pasted within your own events.xml file. I’d recommend trying to locate the entry first before copying and pasting, you can do this by hitting ctrl f on your keyboard this should bring up a search bar, just put this line into the search bar : <event name="StaticHeliCrash"> and push enter, if it is unable to be located don’t stress just paste the entry below into your events.xml.  (top of the file is preferred but entirely up to you)
    <event name="StaticHeliCrash">
        <nominal>8</nominal>
        <min>2</min>
        <max>6</max>
        <lifetime>1500</lifetime>
        <restock>0</restock>
        <saferadius>1000</saferadius>
        <distanceradius>1000</distanceradius>
        <cleanupradius>1000</cleanupradius>
        <secondary>InfectedArmy</secondary>
        <flags deletable="1" init_random="0" remove_damaged="0"/>
        <position>fixed</position>
        <limit>child</limit>
        <active>1</active>
        <children>
            <child lootmax="15" lootmin="10" max="4" min="1" type="Wreck_Mi8_Crashed"/>
            <child lootmax="15" lootmin="10" max="2" min="1" type="Wreck_UH1Y"/>
        </children>
    </event>

    <event name="StaticHeliCrash">
        <nominal>8</nominal>
        <min>2</min>
        <max>6</max>
        <lifetime>1500</lifetime>
        <restock>0</restock>
        <saferadius>1000</saferadius>
        <distanceradius>1000</distanceradius>
        <cleanupradius>1000</cleanupradius>
        <secondary>InfectedArmy</secondary>
        <flags deletable="1" init_random="0" remove_damaged="0"/>
        <position>fixed</position>
        <limit>child</limit>
        <active>0</active>
        <children>
            <child lootmax="15" lootmin="10" max="4" min="1" type="Wreck_Mi8_Crashed"/>
            <child lootmax="15" lootmin="10" max="2" min="1" type="Wreck_UH1Y"/>
        </children>
    </event>




These positions will need to be placed within our Cfgeventspawns.xml, (top of the file is preferred but entirely up to you). 
They have been categorized for our convenience as you may want to adjust or remove one of the positions if needed be, this will make it easier if you intend to add your own. 

<event name="StaticHeliCrash">
		  <!-- MAIN ISLAND -->
  <pos x="4933.873047"  z="9729.281250"  a="270"/>
	<pos x="6180.720215"  z="11046.200195" a="270"/>
	<pos x="4718.375000"  z="11267.736328" a="270"/>
	<pos x="5482.352539"  z="12393.046875" a="270"/>
	<pos x="5766.848145"  z="13051.944336" a="270"/>
	<pos x="7559.769531"  z="10565.326172" a="270"/>
	<pos x="7741.924805"  z="11482.252930" a="270"/>
	<pos x="7018.093750"  z="11919.824219" a="270"/>
	<pos x="7508.282227"  z="13385.980469" a="270"/>
	<pos x="9315.553711"  z="13309.456055" a="270"/>
	<pos x="10124.543945" z="13463.372070" a="270"/>
	<pos x="11037.011719" z="13065.044922" a="270"/>
	<pos x="11483.673828" z="13203.867188" a="270"/>
  <pos x="11745.105469" z="12691.756836" a="270"/>
  <pos x="12333.378906" z="12790.140625" a="270"/>
	<pos x="12751.155273" z="12152.327148" a="270"/>
	<pos x="13293.083984" z="11861.715820" a="270"/>
	<pos x="13364.771484" z="11193.265625" a="270"/>
  <pos x="14144.483398" z="11937.863281" a="270"/>
	<pos x="11821.372070" z="10156.478516" a="270"/>
  <pos x="12940.270508" z="10240.467773" a="270"/>
	<pos x="11336.835938" z="11163.215820" a="270"/>
  <pos x="10838.299805" z="10188.599609" a="270"/>
	<pos x="10140.921875" z="9722.050781"  a="270"/>
	<pos x="9191.588867"  z="10025.488281" a="270"/>
	<pos x="8708.279297"  z="10209.719727" a="270"/>
	<pos x="9106.705078"  z="11070.887695" a="270"/>
	<pos x="8472.573242"  z="12518.965820" a="270"/>
	<pos x="8525.886719"  z="10725.271484" a="270"/>
	<pos x="8308.178711"  z="9882.106445"  a="270"/>
	<pos x="8154.662598"  z="8925.051758"  a="270"/>
  <pos x="7313.580078"  z="7433.729980"  a="270"/>
	<pos x="7473.399902"  z="8156.689941"  a="270"/>
	<pos x="6823.779785"  z="8411.160156"  a="270"/>
	<pos x="5759.640137"  z="7727.620117"  a="270"/>
  <pos x="5634.609863"  z="8695.750000"  a="270"/>
	<pos x="5600.685547"  z="9499.745117"  a="270"/> 
	<pos x="8975.875000"  z="6630.343750"  a="270"/>
  <pos x="9426.873047"  z="7559.528809"  a="270"/>
	<pos x="10571.096680" z="6598.590820"  a="270"/>
	<pos x="12361.616211" z="7870.373535"  a="270"/>
	<pos x="14160.939453" z="8479.455078"  a="270"/>
  <pos x="14424.095703" z="10417.768555" a="270"/>
	<pos x="14362.611328" z="11240.191406" a="270"/>
  <pos x="11555.441406" z="9157.089844"  a="270"/>
      <!-- MAIN ISLAND -->

		  <!-- MILITARY Tier 3 ISLAND -->
  <pos x="3277.469971" z="9339.009766" a="270"/>
  <pos x="2464.433594" z="8596.406250" a="270"/>
  <pos x="984.139099"  z="7510.009766" a="270"/>
  <pos x="2153.494873" z="7775.643555" a="270"/>
	<pos x="2271.562500" z="6782.175293" a="270"/>
	<pos x="3494.869141" z="6197.046875" a="270"/> 
      <!-- MILITARY Tier 3 ISLAND -->


		  <!-- MILITARY Tier 4 ISLAND -->
  <pos x="4331.597168" z="5404.987305" a="270"/>
  <pos x="5603.623535" z="4705.295898" a="270"/>
	<pos x="4837.740234" z="4527.160156" a="270"/>
	<pos x="5295.705566" z="3572.081787" a="270"/>
	<pos x="7073.431152" z="4101.639648" a="270"/>
	    <!-- MILITARY Tier 4 ISLAND -->

		  <!-- SOUTHERN ISLAND --> 
  <pos x="1648.684937" z="4246.220703" a="270"/>
	<pos x="2151.166016" z="4636.243164" a="270"/>
	<pos x="2285.219971" z="3687.199951" a="270"/>
  <pos x="3202.429932" z="3382.020020" a="270"/>
</event>



Once that is completed, save the changes and restart your server. (Unless you plan on doing some tweaking to the <min> and <max> to your heart's content) I would recommend increasing the nominal if you plan on tweaking how many crash sites will spawn at one time. 

If the crash sites haven’t worked (They should), I would set your <active>1</active> to <active>0</active>. Make sure you stop the server first, save changes then restart, once the server has restarted stop the server once again, set the active back to 1 (<active>1</active> ) save changes then restart the server. All should be fixed. 




If you need help feel free to add me on discord and ill be happy to help. Discord: jamracked










