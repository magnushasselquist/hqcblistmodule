#HQ CB List for Community Builder

##Description
The purpose of this module is to present a Community Builder list of Users with a custom presentation-template with the possibility of using/presenting all user fileds from CB.

##Screenshots

Example of presentation in front-end.

Back-end configuration. Select a list, prepare a template.

Use advanced template configuration if needed.

##Configuration
The only configuration for the module, apart from regular module configuration such as position etc, are two things:
* The CB list to be displayed
* The template to be used for presentation of each CB User in the CB List.

template example:
``````    <div class="yourclasstostyle"><p>[firstname] [lastname]<br/>[cb_yourfiled]</p></div>``````

`````` <div class="yourclasstostyle">[avatar]<br /> <a href="cb-profile/[user_id]">[Name]</a>
`````` <div class="role"><a href="departmens/[cb_department]">[cb_department]</a>,[cb_role]</div>
``````  </div>


### rule
avatar
``````<a href="cb-profile/[user_id]"><img src="[avatar]" alt="[name]" title="[name]" width="80" height="80" /></a>


##Download
[Click here to see available downloads](https://github.com/magnushasselquist/hqcblistmodule/releases)
