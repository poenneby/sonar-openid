Sonar OpenID Plugin
===================

See [http://docs.codehaus.org/display/SONAR/OpenID+Plugin]

This fork enables openID for Sonar without having to handle the openID resolution on the host side. (http://mycorp.com/openid?id=12345)

An additional property is required in sonar.properties:
sonar.openid.domainName

Inspired by the jenkins openid plugin:
[https://github.com/jenkinsci/openid-plugin/blob/master/src/main/java/hudson/plugins/openid/GoogleAppSsoSecurityRealm.java]