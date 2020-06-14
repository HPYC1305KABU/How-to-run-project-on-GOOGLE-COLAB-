# How-to-run-project-on-GOOGLE-COLAB-

Steps to run any type of Project(more than one program file in project) in GOOGLE COLAB:

1st : upload a project file in .zip in google drive.

2st : Type google colab in web browser and open it (choose gmail google account where you store a file or project).

3rd : When you open google colab, in screen left-top corner you see a folder symbol and click it and after click on unmount Drive, after when you done this step then google drive data is show in left-top corner.

4th : After 3rd step you create a new python file from open File (left-top corner on screen) select New Notebook.

work in create file new_notebook.ipyb

5th Command :: change the path of the directory = cd drive/MyDrive

    Command :: Unzip project file/folder = from zipfile import ZipFile 
				       file_name = 'CSRNet-pytorch-master.zip'
				       with ZipFile(file_name,'r') as zip :
  				       	  zip.extractall()
                                          print('Done') 
	
	
	
