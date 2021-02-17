# Using Bootstrap Icons in ASP.NET Core Blazor project

![Resulting screen shot](./screenshots/resulting_webpage.png)


This repository demonstrate how to use [Bootstrap Icons](https://icons.getbootstrap.com/) in ASP.NET Core Project:

1. Download the [Bootstrap Icons zip file distribution](https://github.com/twbs/icons/releases)
2. Using curl or browser to download the **bootstrap-icons.css** in to the `wwwroot\lib\bootstrap-icons` folder in project:  
   ![Curl download bootstrap-icons.css file](./screenshots/02_download_css.png)
3. Extract the **fonts** folder from the zip file distribution into the `wwwroot\lib\bootstrap-icons\fonts` folder in project, like following structure:  
   ![project files structure](./screenshots/03_project_structure.png)
4. Add CSS reference in `Pages\_Host.cshtml` file:  
   ![Add CSS reference in _Host.cshtml](./screenshots/04_reference_css_file.png)
5. Use *Icon font* notation in razor files:  
   ![Use icon font notation in razor file](./screenshots/05_icon_font_notation.png)
