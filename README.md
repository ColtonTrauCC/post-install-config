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
  <li><b>Roles</b> grant certain permisions to Agents in an Department they are assigned to</li>
  <ul>
    <li>In the <b>Admin Panel</b>, go to the <b>Agents</b> tab and click on <b>Roles</b>, then click on <b>Add New Role</b></li>
    <ul>
      <li><b>Note</b>: osTickets creates four Roles (All Access, Expanded Access, Limited Access, and View Only) by default.</li>
      <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/6347ce31-f5f1-4078-b738-dc70dd037df6" alt="Disk Sanitization Steps"/></li>
    </ul>
    <li>Name the new Role <b>Supreme Admin</b>, and click on the <b>Permissions</b> tab; in this tab you can assign specific permissions to this role. For our "Supreme Admin" Role, we will check every box under the <b>Tickets</b>, <b>Tasks</b>, and <b>Knowledgebase</b> tabs. Click on <b>Add Role</b> to finish and create the role.</li>
    <ul>
      <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/306c368f-76fb-4b25-869b-d1a1f430ed76" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
    </ul>
  </ul>

  <li><b>Departments</b> are needed to route and resolve tickets based on their importance or instructions</li>
  <ul>
  <li>Still on the Agents tab, click on <b>Departments</b> and click on <b>Add New Department</b></li>
  <ul>
    <li><b>Note</b>: Much like Roles, osTicket also creates two Departments (Maintenance and Support) by default</li>
    <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/2a449d47-9632-47ee-9606-65512e292a2e" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
  </ul>
  <li>Name the Department <b>System Administrators</b> (we'll leave everything else by default for now), then click on <b>Create Dept</b> to create Department</li>
  <ul>
    <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/700f78be-2640-4f34-85d6-0ab8ff6ae994" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
  </ul>
  </ul>

  <li><b>Teams</b> allow us to organize Agents from different Departments in osTicket to handle specific issues and supersede Agents and their Departments' parameter rules</li>
  <ul>
    <li>In the Agents tab, click on <b>Teams</b> and click on <b>Add New Team</b></li>
    <ul>
    <li><b>Note</b>: Just like previous set ups, osTicket creates a Team (Level I Support) by default</li>
    <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/5ede2f9c-91d5-4f9b-8199-99e8f0696e5c" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
    </ul>
    <li>Name the Team <b>Level II Support</b> then click on <b>Create Team</b> to create the Team</li>
    <ul>
      <li><img src="https://github.com/ColtonTrauCC/post-install-config/assets/147654000/b9aa5ab2-2c41-4666-a4f2-6a0f3ff88bc1" height="80%" width="80%" alt="Disk Sanitization Steps"/></li>
    </ul>
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

<h3>Further Reading and Manual</h3>
<ul>
  <li>This concludes to basics of osTicket configuration, but further information and research on the features of osTicket can be found in the official online doccumentation <a href= "https://docs.osticket.com/en/latest/index.html">here</a></li>
</ul>

