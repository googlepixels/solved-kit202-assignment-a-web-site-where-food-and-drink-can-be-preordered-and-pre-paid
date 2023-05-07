Download Link: https://assignmentchef.com/product/solved-kit202-assignment-a-web-site-where-food-and-drink-can-be-preordered-and-pre-paid
<br>
Y.E.O.M. Pty. Ltd. has bought out Lazenbys, The Ref and The Trade Table at University of Tasmania (UTas).  In discussion with the staff and students at UTas, it was discovered that the biggest complaint was having to wait in long queues during peak times when they have just a short time to get a meal or beverage.

To address this issue, it has been decided to develop a web site where food and drink can be preordered and pre-paid so that clients can quickly collect their meals.

DETAILS

Each café will have its own menu displayed by the system.

There will be a “Master List of Food &amp; Beverages”.  This list will contain the ONLY items that may appear on a menu.




Each café manager will be responsible for selecting items from the “Master List of Food &amp; Beverages” that will appear on their cafes menu <em>(i.e. the manager for The Ref can select items to appear on the menu for The Ref, but NOT for Lazenbys or The Trade Table menus). </em>

<table width="340">

 <tbody>

  <tr>

   <td width="151">User Type</td>

   <td width="189">ID format (CCnnnn)</td>

  </tr>

  <tr>

   <td width="151"><strong>D</strong>irector of the <strong>B</strong>oard</td>

   <td width="189">DBnnnn (e.g. DB2123)</td>

  </tr>

  <tr>

   <td width="151"><strong>B</strong>oard <strong>M</strong>embers</td>

   <td width="189">BMnnnn (e.g. BM0234)</td>

  </tr>

  <tr>

   <td width="151"><strong>C</strong>afé <strong>M</strong>anagers</td>

   <td width="189">CMnnnn (e.g. CM3122)</td>

  </tr>

  <tr>

   <td width="151"><strong>C</strong>afé <strong>S</strong>taff</td>

   <td width="189">CSnnnn (e.g. CS1898)</td>

  </tr>

 </tbody>

</table>




The Director of The Board will be responsible for security access for the Board Members.

The Board Members of Y.E.O.M.:

<ul>

 <li>will control what will be available at the UTas cafes, so will be the only people who can create and modify the master list of food and drinks.</li>

 <li>will be responsible for employment and security access at the cafes.</li>

</ul>




Each café will have at least 2 staff members (numbers are determined by a Board Member), one of whom will be assigned (by a Board Member) to be that cafes manager. Staff and managers can be rostered to work at any café, but there can be only one manager at each café at a time.




To use the online menu system, UTas staff and students must first register by providing their Name, Student/Staff ID, E-mail address, mobile phone number, credit card details and password. After registering, an e-mail will be sent to the users e-mail that contains a link that is used to confirm registration <em>(for the purposes of testing you should use your own e-mail account)</em>.




Payment for menu items will come from a pre-paid account. All users will have an account created at registration that they must deposit funds into to purchase items from a menu <em>(i.e. like the caps printing system)</em>.




When ordering from a menu, users will be able to add comments to any item ordered.  This will be to specify any item specifics e.g. if ordering coffee, a description of the type of coffee may be supplied such as “large soy latte +3 sugars”. Each menu is for the following day.




User ID Ranges:

<table width="340">

 <tbody>

  <tr>

   <td width="151"><strong>U</strong>Tas <strong>S</strong>tudents</td>

   <td width="189">USnnnn (e.g. US3212)</td>

  </tr>

  <tr>

   <td width="151"><strong>U</strong>Tas <strong>E</strong>mployees</td>

   <td width="189">UEnnnn (e.g. UE1234)</td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong> </strong>

<h2>PLANNING &amp; DEVELOPMENT CONSIDERATIONS</h2>

Planning the site.

<ul>

 <li>Plan a site overall in the first place is a crucial step to construct a site. Understand the client’s needs and plan accordingly. For example, planning a design theme for the site with variations of the theme that may be used for sub sections is a recommendation.</li>

</ul>




Develop using the appropriate tools.

<ul>

 <li>HTML 5 for static content.</li>

 <li>CSS for formatting.</li>

 <li>JavaScript, Ajax and jQuery for client-side interactivity.</li>

 <li>PHP for dynamic content and server-side interactivity.</li>

 <li>MySQL for data storage and retrieval.</li>

</ul>




Apply consistent structure.

The files needed for the web site will be included in a single folder (directory) – the name of this folder is the same as your alacritas username. The files must be organized into sensibly chosen sub-folders (i.e. sub-folder for CSS or sub-folder for images, etc.).

All semantic structure of the website is controlled by “HTML”. Pay close attention to the elements that you use – make sure that you use the most appropriate element for the <em>kind of </em>text you are marking up.

All layout and other details of the appearance of the website are controlled by valid CSS (Cascading Style Sheets) rules. You place the overall CSS rules in an external style sheet.

All client side behavior of the website (the response to mouse clicking or keyboard reaction) are controlled by valid JavaScript / Ajax / jQuery.

All data is stored in the MySQL database.




<h1>Part 1 (15%)</h1>

<h2>HOME PAGE</h2>

This is the starting / entry point to the café menu system which will have:

<ul>

 <li>links to each of the café menus.</li>

 <li>A link to a registration page.</li>

 <li>login/logout section.</li>

</ul>

For Assignment 1 (Part 1) the login/logout section does not need to authenticate a user, it just needs to change the security state/level <em>(i.e. no database access is required)</em>.




<h2>REGISTRATION PAGE</h2>

This is where new users can register to use the system. Further details are in the DETAILS section above.

Proper input validation must be applied at this point including:

<ul>

 <li>double entry password check • password is:</li>

 <li>6 to 12 characters in length</li>

 <li>Contains at least 1 lower case letter, 1 uppercase letter, 1 number and one of the following special characters ~ ! # $</li>

</ul>

Café staff and managers do not register, they are added to the system by a Board Member. Once added to the system, café staff can also use the menu system to order food and beverages. For Part 1 the registration page does not need to store the registration data <em>(i.e. no database access is required)</em>.




<h2>CAFÉ MENU PAGE</h2>

It will display:

<ul>

 <li>The opening and closing times of the café,</li>

 <li>the list of food and beverage items available at that café, their cost and an initial associated order quantity of 0 (zero).</li>

</ul>

If a user <strong>is not</strong> logged in, they can only view the menu items. The comment and quantity fields for each item cannot be viewed, and an order cannot be submitted.

If a user <strong>is</strong> logged in, they can view a menu and change any items quantity and submit it as an order. For Part 1 the café menu page does not need to store a submitted order <em>(i.e. no database access is required)</em>.




<h2>MASTER FOOD &amp; BEVERAGE LIST PAGE</h2>

This is where a Board Member creates, edits or removes items in the list of food and beverages that will be available for selection by the café managers to use in their menus.

A Board Member also allocates the purchase price for each item and sets the date that the menu applies to.

For Part 1 the master food and beverage list page does not need to store any changes to the list or the items in it <em>(i.e. no database access is required)</em>.     <strong> </strong>




<h1>Part 2a (20%)</h1>

<h2>HOME PAGE</h2>

For Part 2 the login/logout section <strong><em><u>WILL</u></em></strong> need to authenticate a user <em>(i.e. database access <strong>IS</strong> required)</em>.




<h2>REGISTRATION PAGE</h2>

For Part 2 the registration page <strong><em><u>WILL</u></em></strong> need to store the registration data <em>(i.e. database access <strong>IS</strong> required)</em>.




<h2>CAFÉ MENU PAGE</h2>

It will display a total cost of all items selected to be ordered.

It will display a user’s account balance which will decrease or increase in value as menu items are added or removed from an order.

There must be an order collection time selected from a drop-down list.  All order collection times will be on the quarter hour e.g. 8:30am,10:45am,12:30pm. All order collection times must be at least 30 minutes after opening and at least 60 minutes before closing.

It will not allow a user to order more than their account balance can pay for.

For Part 2 the café menu page <strong><em><u>WILL</u></em></strong> need to store a submitted order and update a user’s account balance as required <em>(i.e. database access <strong>IS</strong> required)</em>.




<h2>USER ACCOUNT PAGE</h2>

This page can only be accessed while a user is logged in.

Here a user can view their account balance and deposit more funds.

For Part 2 the user account page <strong><em><u>WILL</u></em></strong> need to retrieve and update a user’s account details as required <em>(i.e. database access <strong>IS</strong> required)</em>.




<h2>MENU MANAGEMENT PAGE</h2>

This page can only be accessed while the café manager is logged in.

Here the café manager can add or remove items from the menu and can change the café opening and closing times.  Opening and closing times must be on the quarter hour.




<h2>USER MANAGEMENT PAGE</h2>

Here:

<ul>

 <li>users can change their password, mobile number or e-mail address,</li>

 <li>a Board Member can o add or remove café staff, o allocate café staff to be managers, o allocate staff to a café.</li>

</ul>




<h2>MASTER FOOD &amp; BEVERAGE LIST PAGE</h2>

For Part 2 the master food &amp; beverage list page <strong><em><u>WILL</u></em></strong> need to modify the list of food and beverages that will be available for selection by the café managers to use in their menus<em> (i.e. database access <strong>IS</strong> required)</em>.




<h2>CAFÉ ORDERS PAGE</h2>

This page is only available to the café staff and café manager, and lists all orders and the order details placed. Only the current days orders will be visible.

<h1>Part 2b Additional Features</h1>

Part 2b Additional Features is self-directed learning and as such there will not be any formal instruction on how to achieve it – you will need to conduct your own research and self-study. To attempt the last 5 marks, the following 8 attributes/features must be applied to Part 1 and Part 2a of the assignment (0.625 marks for each).

You are advised not to attempt these modifications until you have achieved a fully featured and correctly functioning website that meets all of the Part 1 and Part 2a criteria.

<ol>

 <li>Order discounts will apply:</li>

</ol>

<table width="274">

 <tbody>

  <tr>

   <td width="170">User</td>

   <td width="104">Discount</td>

  </tr>

  <tr>

   <td width="170">Director of the Board</td>

   <td width="104">100%</td>

  </tr>

  <tr>

   <td width="170">Board Members</td>

   <td width="104">80%</td>

  </tr>

  <tr>

   <td width="170">Café managers</td>

   <td width="104">15%</td>

  </tr>

  <tr>

   <td width="170">Café staff</td>

   <td width="104">10%</td>

  </tr>

  <tr>

   <td width="170">UTas Students</td>

   <td width="104">7%</td>

  </tr>

  <tr>

   <td width="170">UTas Employees</td>

   <td width="104">0%</td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li>All order totals are rounded to the nearest cent (i.e. a student order totalling $15.50 gets a discount of $1.085 making the new order total $14.415, which would be recorded/processed as $14.42</li>

 <li>Challenge response is required for registration.</li>

 <li>Forgot password feature is required.</li>

 <li>Can top up account balance during an order and not lose the order details.</li>

 <li>Pictures of users, food and beverages will be stored and displayed in appropriate areas. <strong>Note</strong>: There is a storage limit in alacritas. Be careful not to exceed the allowance.</li>

 <li>A basic Responsive layout is required (i.e. layout, text and image proportions are maintained when the screen is resized).</li>

 <li>Email addresses must have a valid format where for our purposes:

  <ol>

   <li>there is a local part followed by an @ symbol followed by a domain part,</li>

   <li>there are no spaces,</li>

   <li>the local part may be up to 64 characters long,</li>

   <li>the domain part may have a maximum of 255 characters,</li>

   <li>the local part contains only the ascii characters a to z, A to Z, the integer characters</li>

  </ol></li>

</ol>

0 to 9 and the special ascii characters !#$%&amp;’*+-/=?^_`{|}~;,

<ol>

 <li>the local part may contain the “.” (period) character but may not start or end with it and may not have 2 consecutive period characters,</li>

 <li>the domain part contains only the ascii characters a to z, A to Z and the integer characters 0 to 9 and the special ascii character the hyphen “–“,</li>

 <li>the domain part must have at least one period character but may not start or end with it and may not have 2 consecutive period characters.</li>

</ol>

<strong> </strong>