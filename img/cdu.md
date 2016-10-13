![](http://yuml.me/diagram/scruffy/usecase/
note: figure 1.2{bg:beige}, 
[User]-(Login),
[Site Maintainer]-(Add User),
[Site Maintainer]-(Add Company),
(Add User)<(Add Company),
[Site Maintainer]-(Upload Docs),
[User]-(Upload Docs), 
[User]-(Full Text Search Docs), 
(Full Text Search Docs)>(Preview Doc),
[User]-(Browse Docs), 
(Browse Docs)>(Preview Doc), 
[Site Maintainer]-(Post New Event To The Web Site), 
[User]-(View Events)
)
