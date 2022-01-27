# Thunder Finesse 2

Is SpringBoot and Angular project for analyzing players and vehicles statistics in War Thunder. <br>

Consist of:
<ul>
  <li>
    <a href="https://github.com/RafalZdulski/ThunderFinesseFrontend">ThunderFinesseFrontend </a> - AngularJS application <br>
    - ...
  </li>  
  <li>
    <a href="https://github.com/RafalZdulski/ThunderFinesseBackendtend">ThunderFinesseBackend </a> - SpringBoot application <br>
    - So far only connects frontend with MongoDB database and control usage of ThunderSkillPlayer submodule
  </li>
</ul>

<br>
Uses:
<ul>
<li>
mongoDB for data storage
</li>
<li>
<a href="https://github.com/RafalZdulski/WikiFetcher">Wikifetcher </a> <br>
- Java application for retrieving vehicles data from <a href="wiki.warthunder.com">wiki.warthunder.com</a> and inserting them into given MongoDB database.  
</li>
<li>
<a href="https://github.com/RafalZdulski/ThunderSkillPlayer">ThunderSkillPlayer</a> <br>
- Java application for retrieving players stats from <a href="thunderskill.com">thunderskill.com</a> and inserting them into given MongoDB database.  
</li>
</ul>
