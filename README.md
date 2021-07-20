# Vuforia Studio Templates

**Objective:** Jumpstart users in creating AR experiences in Vuforia Studio by providing templates for specific use cases.

**Available Vuforia Studio Templates:**

1. [Maintenance/Assembly Template](https://github.com/PTC-Education/VuforiaStudioTemplates#Maintenance) - This template makes it easier to update a data table in ThingWorx from a Vuforia Studio experience. The purpose is to allow a user to update information regarding a process and its documentation automatically by going through the experience. 

2. [Machine Learning Template](https://github.com/PTC-Education/VuforiaStudioTemplates#Machine) - This template connects Vuforia Studio with Microsoft Lobe, a machine learning engine, that allows the user to train and test a model by taking pictures in Vuforia Studio and sending them to ThingWorx. The purpose is to allow the Studio experience to recognize parts/machinery that may not have CAD data.

---

## Maintenance / Assembly Template

### Intro 
  This allows the user to import a Creo Illustrate file as an animation for maintenance or dis/assembly. Within the experience the template prompts the user for input, such as name and notes, which is sent into ThingWorx datatable that can be accessed. The Template comes in two parts, the Vuforia Studio zip file and ThingWorx Datatable file.
### Template Entities: 

- [Vuforia Studio zip file](https://github.com/PTC-Education/VuforiaStudioTemplates/files/6845625/Maintenance_Assembly_Template.zip)

- [ThingWorx Data Table](https://github.com/PTC-Education/VuforiaStudioTemplates/blob/main/Things_Maintenance_DataTable_Template.xml)- 

### Getting Started

- Import the Vuforia Studio template file to your local Vuforia Studio. 
- You will need to import or create your own Creo Illustrate animation (.pvz file) to the template. This animation will be the main aspect of the experience that the user will interact with. For additional information on how to create Creo Illustrate animations, follow this [link](https://support.ptc.com/help/creo/illustrate/r6.1/en/index.html#page/creo_illustrate%2Fgxy1120.html%23).
- Open up the template and find model-1. Import your Creo Illustrate file to model-1 and select your desired sequence. 

<img width="168" alt="resourcesScreenShot" src="https://user-images.githubusercontent.com/78899336/124706357-5535c980-deb4-11eb-9135-3a8ab9980dd6.PNG">
<img width="160" alt="chooseSequenceScreenshot" src="https://user-images.githubusercontent.com/78899336/124706363-58c95080-deb4-11eb-8b14-b85f09ff8283.PNG">
 

- Open up your ThingWorx instance and import the ThingWorx Data Table entities. Make sure the permissions are turned to public access. 
- Go back into Vuforia Studio and make sure your instance matches you ThingWorx instance. 
- Click Save and Preview. Note: In preview, follow the prompts to go through the experience and click finish at the end. 
- To make sure your input was recorded correctly in ThingWorx, go to your Data Table and open up properties. There should now be new values in each of the columns.

<img width="584" alt="ThingworxPropertiesScreenshot" src="https://user-images.githubusercontent.com/78899336/124706405-6a125d00-deb4-11eb-9797-5838f29a56aa.PNG">


---

## Machine Learning Template

