# Template Application IExternalApplication

In this section, we will create a template for our IExternalCommand applications so that we don't have to follow all the steps we saw in Project 2 each time we want to create an application of this type.

## STEP 1 - Set up work template

Through of the editor code VISUAL STUDIO CODE we choose the framework 4.8 to use and select a class library template. This template will allow us to access the revit libraries.

![image](https://github.com/user-attachments/assets/fe10c8e2-2cd1-4cdf-b02b-3c1ba45067a4)

## STEP 2 - Add Revit references

To add the references that allow us connect with the Revit API files, we must:

![image](https://github.com/user-attachments/assets/90a29773-e322-41da-9f32-25833a9b7e17)

## STEP 3 -  Implement the IExternalCommand interface and write code

![image](https://github.com/user-attachments/assets/687b2cb6-4885-485d-8fc2-57668c0caed5)

## STEP 4 - Generate .addin file 

![image](https://github.com/user-attachments/assets/fe0559ec-3f10-4e49-9a22-df29d8b738e8)

## STEP 5 - We check that the app works OK

In this step, we verify that our app works correctly so that we can later set it as a template.

![image](https://github.com/user-attachments/assets/18b5e106-3fca-4cc4-8180-ccbea0389aa4)

## STEP 6 - Set as template

To set as a project, we follow these steps

 - Proyecto
   - Exportar plantilla

![image](https://github.com/user-attachments/assets/83f30d0e-cd8d-4c03-86be-9f091855c4fb)

 - Select Plantilla de proyecto

![image](https://github.com/user-attachments/assets/e468cf9a-86eb-4b73-8842-6727903632c8)

- Complete required fields

  In this case, we only complete the first two fields; however, an image can be added for the icon if desired.

  ![image](https://github.com/user-attachments/assets/704efbab-4fb3-487c-9ee0-e50886d3dd9b)

  Once we press finish, the template is created and we are directed to the folder where it was saved.

  ![image](https://github.com/user-attachments/assets/e0cf784c-34af-4083-8305-9df028495d04)

  ## STEP 7 - Create a new application from the template

  To use the template, we open a new project in Visual Studio and select our template, which should already appear, or we can search for it if it is not visible.

  ![image](https://github.com/user-attachments/assets/34923cd1-7e2c-4369-ac9e-24285ca126bd)

  We assign the name of the new application and change the path where the new project will be saved, if desired.

  ![image](https://github.com/user-attachments/assets/78584cab-b86f-480a-83a1-32306e25db8b)

   ## STEP 8 - Modify .addin file

  To create the application, we need to make some modifications to the .addin file.

  We modify the tags Name, Assembly, FullClassName, AddInId, and Text.

  ## STEP 9 - Verify our new Application
  

  ![image](https://github.com/user-attachments/assets/29646158-1131-4cb0-b399-316e249b8e5e)
  

  ![image](https://github.com/user-attachments/assets/864d37b4-53a2-4d64-94f3-7ce7742fd758)



  

  



  












