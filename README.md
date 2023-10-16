<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket. This tutorial assumes you have fully completed, installed, set up login credentials, and perform clean up on osTicket in your Virtual Machine environment via following the previous tutorial <a href ="https://github.com/ColtonTrauCC/osticket-prereqs">"osTicket - Prerequisites and Installation"</a><br />

</br>

<h2>Environments and Technologies Used</h2>
<ul>
  <li>Microsoft Azure (Virtual Machines/Compute)</li>
  <li>Remote Desktop</li>
  <li>Internet Information Services (IIS)</li>
  <li>osTicket</li>
</ul>

</br>

<h2>Operating Systems Used </h2>
<ul>
  <li>Windows 10</li>
</ul>

</br>

<h2>Post-Install Configuration Objectives</h2>
<ol>
  <li>Familiarity with the UI of osTicket</li>
  <li>Creating and Configuring Roles</li>
  <li>Creation of Tickets</li>
  <li>Creating Agents and Users</li>
  <li>Setting up Service Level Agreements (SLA) in ticketing system</li>
  <li>Configuring Help Topics</li>
</ol>

</br>

<h2>Configuration Setups</h2>

<!-- <img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/> -->

<h3>Configuring Roles, Departments, & Teams</h3>

<p>
  
<ul>
  <li><b>Note</b>: There are two panels when navigating osTicket; <b>Agent Panel</b> and <b>Admin Panel</b>, you'll know which panel you are on if the <b>opposite panel</b> is displayed on the top right of the UI next to your user login name</li>
  <ul>
    <li>In this example, the user "josh" is on the Agent Panel</li>
    <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/6abb22de-3ec5-47a9-8efd-46caf9d1622f" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
  </ul>
  <li>In the <b>Admin Panel</b>, go to the <b>Agents</b> tab and click on <b>Roles</b>, then click on <b>Add new Role</b></li>
  <ul>
    <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/6347ce31-f5f1-4078-b738-dc70dd037df6" alt="Disk Sanitization Steps"/></li>
  </ul>
  <li>Name the new Role <b>Supreme Admin</b>, and click on the <b>Permissions</b> tab; in this tab you can assign specific permissions to this role. For our "Supreme Admin" Role, we will check every box under the <b>Tickets</b>, <b>Tasks</b>, and <b>Knowledgebase</b> tabs.</li>
  <ul>
    <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/306c368f-76fb-4b25-869b-d1a1f430ed76" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
  </ul>
</ul>
  
</p>

</br>

<h3>Allowing creation of Tickets</h3>

<p>
  
<ul>
  <li></li>
  <li></li>
</ul>
  
</p>

</br>

<h3>Adding Agents and Users</h3>

<p>
  
<ul>
  <li></li>
  <li></li>
</ul>
  
</p>

</br>

<h3>Adding SLAs</h3>

<p>
  
<ul>
  <li></li>
  <li></li>
</ul>
  
</p>

</br>

<h3>Configuring Help Topics</h3>

<p>
  
<ul>
  <li></li>
  <li></li>
</ul>
  
</p>

</br>

