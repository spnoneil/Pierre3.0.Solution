# Pierre's Bakery (now in 3.0!)

#### An MVC application for our best imaginary friend, Pierre, and his bakery, utilizing authorization and account creation

#### By &copy; [Scott O'Neil](https://github.com/spnoneil), 3/26/2021

## Technologies Used

* _C# / .NET 5.0 SDK / ASP .NET Core_
* _HTML5_
* _CSS3 / Bootstrap 4.5_
* _VS Code 1.54.2_
* _Entity Framework Core 5.0_
* _MySQL/Workbench 8.0.19_

## Description
_A simple MVC page, created for Epicodus Coding School to practice/show knowledge of basic database management, as well as authorization and login account creation_

## Setup/Installation Requirements

* _Clone/download from GitHub (unzip, if necessary)_
* _Open terminal, navigate to the `Pierre3.0` directory, inside the `Pierre3.0.Solution` root directory_
* _Still in the terminal, enter `dotnet restore`._
* _Next, enter `dotnet build`_
* _Then, enter `dotnet run`_
* _Finally, in browser of choice, navigate to `http://localhost:5000`_

### Database Setup


* _First, download MySQL Workbench [here](https://dev.mysql.com/downloads/workbench/)_
* _After a successful install and setup, in the Administration tab, hit "Data Import/Restore", followed by clicking "Import from Self-Contained File", and navigate to the included `scott_oneil.sql` dump structure file_
* _Click "Start Import"_
* _Next, in the root directory of `Pierre3.0.Solution`, create a file called `appsettings.json` and input the following, with "YOUR-PASSWORD-HERE" being the password you set up with MySQL workbench:_
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=scott_oneil;uid=root;pwd=[YOUR-PASSWORD-HERE];"
  }
}
```
* _Now, navigate back to the `Pierre3.0` directory, and update the database with the command `dotnet ef database update` in the terminal_
* _Now you're ready to head back to that `http://localhost:5000` and refresh to view project_


Database, Visualized:
<!-- UPDATE -->
[![gyazo](https://i.gyazo.com/2f826aa51212f6f9ca98d6ef465cc75d.png)]

## Known Bugs

* _No known bugs_

## Future implementation
* _Further styling_
* _Search_
* _Select multiple flavors/treats on creation_

## License
_GPL_
## Contact Information

_Issues can be reported [here](https://github.com/spnoneil/Pierre3.0.Solution/issues/new) on GitHub_
