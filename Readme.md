

## Organ donation web application

## Overview:

 The organ donation web application aims at digitalizing the organ donation process and eliminating the organ transplant wait list. The application intends to serve as a donor registry which can be used by the hospitals at emergency situations. The web application also helps the people to register as a donor and provide necessary details about the donation. 
 
 Essentially there are two different user bases for this application, namely the donors and the hospitals.

In our web application, hospitals can mainly perform the following  operations:
     1. Approving/denying the donor's appointment.
     2. Approving/denying donations.
     3. Searching for donations and contacting the donors at the time of emergencies.
     
The assignment 2 submission focuses on the front-end of the hospital management system (hospital user base).  As part of the assignment, 4 general screens and one user profile management (update profile) screens are developed. They are as follows:

  1. **Action items screen**:  Serves as the landing page. Provides information about pending appointment approvals, and pending donation approvals.
     
  2. **Pending appointments screen**: Hospitals can manage the appointments received from the donors using this screen.   The page allows the user (hospital user) to accept/deny appointments and view details of the appointment.  Note that only when the appointment is approved, the donation will be eligible for acceptance/denial (covered in the Pending donations screen).
     
  3. **Pending donations screen**: Hospitals can manage the donations using this screen. The page allows the user to accept/deny donations and view the details of the donations. 
     
 4. **Search donations screen**: Hospitals can use this screen to search for donations at the time of emergencies.  Only the approved donations will be displayed on this screen. 
     
 5. **Update profile screen**: Allows hospitals to update their basic details.

## Files involved:

The following files are involved for creating the front-end for the hospital user base:

  1. *index.html*: Contains the entire structure of the hospital management system.
  2. *style_hospital_homepage.css*: Covers the styling segment for the hospital management system.
  3. *hospital_script.js*: Handles user interactions with the web application.
     
**Instruction for downloading and loading the project:**

 1. The project is available at the following link: [Project Git Lab link](https://git.cs.dal.ca/aravind/organ-donation---hospital-management-front-end.git)
 2. Click on the download option and choose an appropriate file format. For example, zip format.
 3. Extract the files and open the 'index.html' file on any browser.
    

## Frameworks used:

**Bootstrap 4:** 
     Bootstrap was used because of its responsive, mobile grid system. The Bootstrap components in this assignment were used with the help of Bootstrap CDN. Some of the components used are:

  1. **Navigation bar** [1]: 
    *Justification*: The functionality of the hospital management system demanded an easy-to-use navigation bar that would allow the users to switch between various features efficiently.  
     
     *Customization*: The navigation bar was customized in various ways by altering its look and feel.  For instance, simple and effective CSS animations were added for the active tabs, the color of the navigation bar and the tabs were changed, the alignment, borders, and margins were customized, the hover effects were altered and so on.  

    2. **Tables** [2]: 
     *Justification*: The major functionalities of the hospital (accepting appointments, accepting donations, searching for donations) involves managing several donor records. While a normal HTML5 table could serve this purpose, Bootstrap 4 table has a better edge because of its responsiveness.
	 *Customization*: The Bootstrap table was customized in many ways. Some of the important customizations include enhancing the table to provide hovering and row selection capabilities.
	     The Bootstrap 4 tables are used in 'Pending appointments', 'Pending donations', and 'Search donations' screens.
     
     3. Form [3]:
     *Justification*: The update profile section requires a simple yet beautiful form that allow the user to
	 update their details. Bootstrap 4 provides elegant forms which can be easily customized according to our needs.
	 *Customization*: The elements of the form were customized in such a way that the form fits best for
	 the application. Bootstrap form buttons were replaced by custom made buttons,the 
	 grid column length of the elements were also altered according to the need. 
	 
**SweetAlert2** [4]:  SweetAlert2 framework was used for providing user alerts and feedbacks. The main purpose of using it was to replace the traditional JavaScript alert boxes which are plain  and simple. The alert boxes center itself on the page and looks great across all devices. The alerts werecustomized according to the success, error, and information scenarios. The framework was linked to
     the project using the CDN. 	 
	 
References:
	 
[1]"Bootstrap Tabs and Pills", W3schools.com, 2019. [Online]. Available: https://www.w3schools.com/bootstrap/bootstrap_tabs_pills.asp
	 [2]a. Mark Otto, "Tables", Getbootstrap.com, 2019. [Online]. Available: https://getbootstrap.com/docs/4.0/content/tables/
	 [3]a. Mark Otto, "Forms", Getbootstrap.com, 2019. [Online]. Available: https://getbootstrap.com/docs/4.0/components/forms/
	 [4]"SweetAlert2", Sweetalert2.github.io, 2019. [Online]. Available: https://sweetalert2.github.io/
	 [5]"The W3C Markup Validation Service", Validator.w3.org, 2019. [Online]. Available: https://validator.w3.org/
	 [6]"The W3C CSS Validation Service", Jigsaw.w3.org, 2019. [Online]. Available: https://jigsaw.w3.org/css-validator/
	 [7]"Sublime Text - A sophisticated text editor for code, markup and prose", _Sublimetext.com_, 2019. [Online]. Available: https://www.sublimetext.com/. [Accessed: 10- Feb- 2019].
	 
