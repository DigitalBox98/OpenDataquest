# OpenDataquest
Welcome to the DOL dataquests sharing project !

# How to import an existing CSV quest  
Open the Dataquest input tool "DataQuest_Input.ods" and activate macros : <br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/d30d4ba8-a62d-48c9-9570-c75f327b5ee3)
<br><br>
Select one of the CSV quests in the "quests" folder and do a copy of the content :<br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/b871bb1a-df0e-44d2-932a-869e556dcdca)
Paste the content into the spreadsheet in order to import the CSV : <br><br>

Select the "tab" only as a separator : <br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/4b0a1c8e-9e75-46ce-b8af-13698dd102ca)
<br><br>
The quest is now imported into the spreadsheet : <br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/e20470fe-23a7-4a71-8a74-e90b605af590)

<br><br>
Click on "Finalize Import" and answer "Yes" to the two questions :<br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/e1e47c9e-d7b9-4a5d-af05-73e3c56a4553)
<br><br>
Go into the "SQL Datasheet Output" :<br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/31c5606c-2606-4b52-a3b2-24eb44a585a9)

<br><br>
Select the 2 cells on the right of Query 1 and Query 2 and paste the content into a SQL client connected to your DOL database then execute the SQL : <br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/53b26f8e-10a0-4ca5-854c-c76350417b38)

<br><br>
The quest is now inserted/updated into your DOL database !<br><br>

Launch your DOL server or - if server already started - do a /mob refreshquests on the corresponding NPC :<br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/363b5bd5-ea83-465d-b575-abadc4b42e8b)
<br>
Your quest is now ready to be played/ tested !
<br><br>


# How to export a quest to CSV 

Just do a copy of all your cells in the "Dataquest Input" tab.<br>
Paste the content to a text editor like Notepad++.<br>
Save your file to CSV (tab as a separator).<br>

The filename convention is :<br>
&lt;Quest Name&gt;-&lt;NPC Name&gt;.csv  <br>

(please replace " " by "_" in the filename) <br><br>


# How to create a new quest 

Open the file "Quests_List.ods" in the "samples" folder and do Ctrl+Click on the quest's title to go into the corresponding quest description on Allakhazam website.
<br><br>
Open the Dataquest input tool "DataQuest_Input.ods" and select your number of steps in the spreadsheet : <br>
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/feeee5b3-2e48-4a79-8802-8a3fcd45d5ae)

Start to do copy/paste of the steps description from Allakhazam into your spreadsheet and create a Finish step to finalize your quest.<br><br>

You can check the details of the fields in the instructions document : OpenDataQuest_Instructions.ods

![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/2f522b7b-b3ab-47a8-a4e4-2558714a816c)


The version of the OpenDataQuest input tool is based on the below :<br>
- a major version (v1.0, v1.1, ...) : in case the CSV structure must be changed<br>
- a minor version (64, 65, ...) : corresponding to EveOfDarkness/db-public data release  = the Mob, Worldobject, ItemTemplate dropdown lists are based on this version<br><br>

![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/c18ea369-56af-4945-aaa7-8f5aeb8a1a99)
![image](https://github.com/DigitalBox98/OpenDataquest/assets/57635141/98767f1c-c6bb-434c-858a-938ef330ef77)

It means the CSV files are compatible within the same major version.<br>

<br>

Start testing and share your findings !







