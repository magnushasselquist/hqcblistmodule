
#HQ CB List for Community Builder

##Description
The purpose of this module is to present a Community Builder list of Users with a custom presentation-template with the possibility of using/presenting all user fileds from CB.

##Screenshots

Example of presentation in front-end.  
![cblistfront](https://user-images.githubusercontent.com/23451105/120665837-6a21d600-c48c-11eb-9815-c243f2310b37.png)

Back-end configuration. Select a list, prepare a template.
![cblistbackend](https://user-images.githubusercontent.com/23451105/120665765-5c6c5080-c48c-11eb-8c16-c0904452d1a4.png)

##Configuration
The only configuration for the module, apart from regular module configuration such as position etc, are two things:
* The CB list to be displayed
* The template to be used for presentation of each CB User in the CB List.

###template example:
`<div class="yourclasstostyle"><p>[firstname] [lastname]<br/>[cb_yourfiled]</p></div>
<div class="yourclasstostyle">[avatar]<br /> <a href="cb-profile/[user_id]">[Name]</a>
<div class="role"><a href="departmens/[cb_department]">[cb_department]</a>,[cb_role]</div>`  


### rule example;
avatar
`<a href="cb-profile/[user_id]"><img src="[avatar]" alt="[name]" title="[name]" width="80" height="80" /></a>`


##Download
[Click here to see available downloads](https://github.com/magnushasselquist/hqcblistmodule/releases)
