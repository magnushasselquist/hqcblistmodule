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

The following template is an easy beginner template:
``````    <div class="yourclasstostyle"><p>[firstname] [lastname]<br/>[cb_yourfiled]</p></div>``````

And the following template example is a more advanced usage:
``````    <div class="yourclasstostyle">``````
    ``````<p><a href="/path-to/userprofile/[user_id]"> <img id="avatar_img_[user_id]" width="50" /></a>``````
    ``````<script type="text/javascript">``````
    ``````// <![CDATA[``````
    ``````var avatar_str = "[avatar]";``````
    ``````if (avatar_str.length > 3) {``````
    ``````avatar_url = "[avatar]";``````
    ``````} else {``````
    ``````avatar_url = "/components/com_comprofiler/plugin/templates/default/images/avatar/tnnophoto_n.png";``````
    ``````}``````
    ``````document.getElementById("avatar_img_[user_id]").src = avatar_url;``````
    ``````// ]]>``````
    ``````</script>``````
    ``````</p>``````
    ``````<p>&nbsp;</p>``````
    ``````<p><a href="/ledare/profil/userprofile/[user_id]">[firstname] [lastname]</a>``````
    ``````</p>``````
    ``````<div class="roles">[cb_role]</div>``````
    ``````<div class="badges">[cb_department]</div>``````

##Download
[Click here to see available downloads](https://github.com/magnushasselquist/hqcblistmodule/releases)
