
### **Project Description**

This project is a local web page for generating and printing medical prescriptions. The primary function of the website is to format prescription details for easy printing, with a key feature being the use of **Print CSS** to ensure that the output is properly spaced and fits correctly on a single page. The page supports a variety of prescription elements, including a header, footer, patient gender selection, and the ability to add and delete multiple medicine entries. After printing, the page automatically refreshes to prepare for the next patient's prescription, streamlining the workflow.

### **Technical Stack**
* **HTML**: Provides the structure and content of the web page.
* **CSS**: Styles the page and, most importantly, uses the `@media print { }` rule to apply specific formatting for printing, ensuring an optimized layout.
* **JavaScript**: Manages dynamic functionalities, such as adding and deleting medicine lists, as well as refreshing the page after the print action is triggered.

### **Key Features**
* **Print Optimization**: The CSS is specifically designed to handle printing, ensuring that all medicine entries are equally spaced and limited to eight per page to maintain a clean and readable format.
* **Dynamic Content**: Users can dynamically add and remove medicine entries, providing flexibility for different prescription needs.
* **Automated Workflow**: The page refreshes automatically after printing, simplifying the process for creating sequential prescriptions.
