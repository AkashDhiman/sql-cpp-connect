# sql-cpp-connect

-this repository aims to provide a step by step process to install xampp in a windows distribution

- to know more about [XAMPP](https://www.apachefriends.org/download.html) and tutorials .
- to know more about [MYSQL](https://www.mysql.com) and its implementation.
- to know more about [CODEBLOCKS](http://www.codeblocks.org/) and its implementation.
  this setup helps in using MYSQL as RDBMS ( relational database management environment ) and PHP as object oriented scripting language.

# SQL through C PLUS PLUS

### this is a Guide on how to use the XAMPP setup with C++.

---

C++ contains libraries and header files that can be used in order to access the data present in mysql or MariaDB. Follow the steps listed below in order to create the full development environment:

> prerequisites

1.  A g++ compiler.

> These instructions are for windows only.

1. Download XAMPP for windows using the following link: `wget https://www.apachefriends.org/xampp-files/7.3.9/xampp-windows-x64-7.3.9-0-VC15-installer.exe`
2. Run the installer, this will install Xampp which contains mariaDB which we will be using as our database
3. To install codeblocks in your sytem use the following link: `wget https://sourceforge.net/projects/codeblocks/files/Binaries/17.12/Windows/codeblocks-17.12-setup.exe/download`
   this will install codeblocks with all the plugins .

> now configuring codeblocks for mysql by installing and saving the files

4. Download the zip file and unzip Mysql.zip  
   --paste libmysql.a in g++ compiler in codeblocks in your C drive .
   --paste libmysql.dll in g++ compiler in codebocks/include in C drive.
   --paster mysql headers in g++ compiler in codeblocks in C drive .
5. Configure the mysql from codeblocks linker settings after setting up a new project .
   --add the parth to /codeblocks/include in c drive with absolute path in your compiler.
6. Start up the database in xampp with opening xampp console and running the apache server and mysql in your system.
7. Set up a connection with running the sample file in your mysql server , open a project in codeblocks and run `sample.cpp` file .
8. After a database connection is set up with php myadmin try to run sample code from **sample** directory .

### Directory Structure

- **sample**: contains the source-code for sample programs.
- **bin**: contains the compiled version of the sample program with the same name.
- **test**: empty directory for you to compile the source yourself.
