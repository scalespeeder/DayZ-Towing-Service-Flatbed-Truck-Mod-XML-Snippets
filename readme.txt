DAYZ PC Towing Service Recovery / General Purpose Truck Mod XML Code Snippets Changelog & Terms Of Use

Will work on PC Community Servers.

Limited Testing on PC Chernarus Local PC Server DAYZ  Version 1.21 July 2023.

Towing Services Mod Created by HunterZ.

https://steamcommunity.com/sharedfiles/filedetails/?id=3004707934

Please report mod bugs on his Discord: https://discord.gg/49FvN7rRpF

XML Code Snippets by @scalespeeder. Please report errors to scalespeeder@gmail.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml code snippets could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml code snippets neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these code snippets to ensure proper
functioning of your server.

==========================

The below XML Snippets will help you to get the Towing Services Mod working on your PC Community Server.
We add the Ford Trucks to the existing M3S Truck Events so we can use their event spawn locations without having
to creat more custom spawn points on Chernarus or Livonia (or other maps that have Truck Spawns already).Customise to your needs.


Add these entries to your types.xml (parts spawning may be bugged as of July 2023, if so, use the "complete" version of the cfgspawnabletypes below)

	<type name="Ford_flatbed">
		<nominal>0</nominal>
		<lifetime>3888000</lifetime>
		<restock>0</restock>
		<min>0</min>
		<quantmin>-1</quantmin>
		<quantmax>-1</quantmax>
		<cost>100</cost>
		<flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
	</type>
	<type name="Ford_flatbed_blue">
		<nominal>0</nominal>
		<lifetime>3888000</lifetime>
		<restock>0</restock>
		<min>0</min>
		<quantmin>-1</quantmin>
		<quantmax>-1</quantmax>
		<cost>100</cost>
		<flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
	</type>
	<type name="Ford_flatbed_red">
		<nominal>0</nominal>
		<lifetime>3888000</lifetime>
		<restock>0</restock>
		<min>0</min>
		<quantmin>-1</quantmin>
		<quantmax>-1</quantmax>
		<cost>100</cost>
		<flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
	</type>
	<type name="Ford_flatbed_green">
		<nominal>0</nominal>
		<lifetime>3888000</lifetime>
		<restock>0</restock>
		<min>0</min>
		<quantmin>-1</quantmin>
		<quantmax>-1</quantmax>
		<cost>100</cost>
		<flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
	</type>
	
	<type name="Ford_flatbed_doors_driver">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_codriver">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_hood">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_driver_green">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
		<type name="Ford_flatbed_doors_codriver_green">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_hood_green">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
		<type name="Ford_flatbed_doors_driver_blue">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_codriver_blue">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
		<type name="Ford_flatbed_doors_hood_blue">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_driver_red">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
		<type name="Ford_flatbed_doors_codriver_red">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
	<type name="Ford_flatbed_doors_hood_red">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
		<type name="Ford_flatbed_doors_trunk">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
		<type name="Ford_flatbed_tent">
    <nominal>10</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>6</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
	</type>
	
<type name="Ford_flatbed_wheel">
    <nominal>40</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>30</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
  </type>
  
  <type name="Ford_flatbed_WheelDouble">
    <nominal>40</nominal>
    <lifetime>28800</lifetime>
    <restock>0</restock>
    <min>30</min>
    <quantmin>-1</quantmin>
    <quantmax>-1</quantmax>
    <cost>100</cost>
    <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0" />
    <category name="vehiclesparts" />
    <usage name="Industrial" />
    <usage name="Farm" />
  </type>
	
REMEMBER TO SAVE!
	
In events.xml, edit your trucks event to this: 

	 <event name="VehicleTruck01">
        <nominal>24</nominal>
        <min>21</min>
        <max>35</max>
        <lifetime>300</lifetime>
        <restock>0</restock>
        <saferadius>500</saferadius>
        <distanceradius>500</distanceradius>
        <cleanupradius>200</cleanupradius>
        <flags deletable="0" init_random="0" remove_damaged="1"/>
        <position>fixed</position>
        <limit>mixed</limit>
        <active>1</active>
        <children>
            <child lootmax="0" lootmin="0" max="5" min="3" type="Truck_01_Covered"/>
            <child lootmax="0" lootmin="0" max="5" min="3" type="Truck_01_Covered_Blue"/>
            <child lootmax="0" lootmin="0" max="5" min="3" type="Truck_01_Covered_Orange"/>
			<child lootmax="0" lootmin="0" max="5" min="3" type="Ford_flatbed"/>
            <child lootmax="0" lootmin="0" max="5" min="3" type="Ford_flatbed_blue"/>
            <child lootmax="0" lootmin="0" max="5" min="3" type="Ford_flatbed_red"/>
			<child lootmax="0" lootmin="0" max="5" min="3" type="Ford_flatbed_green"/>
        </children>
    </event>
		
REMEMBER TO SAVE!
		
In cfgspawnabletypes add this for trucks to spawn with bits missing: (scroll downn for complete trucks)

<type name="Ford_flatbed">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_Pink" chance="0.10" />
		</attachments>
	</type>
	
	<type name="Ford_flatbed_green">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver_green" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver_green" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood_green" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
			<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_White" chance="0.10" />
		</attachments>
	</type>
	
	<type name="Ford_flatbed_blue">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver_blue" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver_blue" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood_blue" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_Dark" chance="0.10" />
		</attachments>
	</type>
	
	<type name="Ford_flatbed_red">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver_red" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver_red" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood_red" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="0.40" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.40" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_Beige" chance="0.10" />
		</attachments>
	</type>
	
REMEMBER TO SAVE!

Complete Trucks for cfgspawnabletypes:

<type name="Ford_flatbed">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.25" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_Pink" chance="0.10" />
		</attachments>
	</type>
	
	<type name="Ford_flatbed_green">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver_green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver_green" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood_green" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
			</attachments>
			<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
			<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_White" chance="0.10" />
		</attachments>
	</type>
	
	<type name="Ford_flatbed_blue">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver_blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver_blue" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood_blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>		
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.25" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_Dark" chance="0.10" />
		</attachments>
	</type>
	
	<type name="Ford_flatbed_red">
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_driver_red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_codriver_red" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_hood_red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_doors_trunk" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>	
		<attachments chance="1.00">
			<item name="Ford_flatbed_wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Ford_flatbed_tent" chance="0.25" />
		</attachments>
		<attachments chance="1.00">
			<item name="Bear_Beige" chance="0.10" />
		</attachments>
	</type>
	

Restart your server, and you should be good to go!

Good luck, Rob.