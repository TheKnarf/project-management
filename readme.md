#Projects

An easy command line projectmanagement, basically works as alias for sql commands.

##Usage

 - projects
 
   _lists up all projects_
 - projects -a somename

   _adds current folder as new project with name: somename_
 - . projects somename
 
   _changes directory to project somename_  
 - projects -d somename
 
   _deletes refrence to project somename from the database_
   
 - projects -setup
 
  _setup the database, to reinstall; delete database and setup anew_
  
 - projects -i readme
 
 _initialize the project with some readme files_