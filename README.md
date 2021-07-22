# Unity_CustomDropdownMenu
A script to create a simple and costomizable dropdown menu 

How to use 
1. Add a UI button to the scene canvas , it will use the script
2. Add another button as a son of the first one, it will be used as template to instantiate the menu options
3. Script usage , you have two options :
  
  - Option 1 : attach the given script to the main button, fill the public atributes and modify the method "clickOnOption"
  ![image](https://user-images.githubusercontent.com/15013415/126622502-91d2b23e-dd31-40f0-99e7-e843f4c4f0b6.png)
  
  - Option 2 : create a new script, extend the given one and override the same function as in the first option, fill the public atributes
  ![image](https://user-images.githubusercontent.com/15013415/126622988-5f2bb3a1-deaf-4487-8642-559f95d061e1.png)
  
  cleaner option if you need multiple dropdown menus
