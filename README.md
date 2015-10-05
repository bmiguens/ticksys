# ticksys


Libs

```
git clone https://github.com/quark-dev/Phonon-Framework.git libs/phonon &&\
git clone https://github.com/janl/mustache.js.git libs/mustache &&\
git clone https://github.com/madrobby/zepto.git libs/zepto &&\
git clone https://github.com/almende/vis.git libs/vis 
```

Auth

Get Token
```
curl -X POST https://api.github.com/authorizations --user "bmiguens:PASS" --data '{"scopes":["user","repo","gist"], "note":"tickSys"}'
```

Get Info user
```
curl https://api.github.com/user --user "bmiguens:043f2d4227d89b8315f227f70eed8e878631441c"
```