# Install

Sublime Text 3

```
git clone https://github.com/maxmckenzie/cucumber-boilerplate-sublime-snippits.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/cucumber-boilerplate-sublime-snippits
```

Package Control for Sublime Text 3

```
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

Install Package Cucumber

  Mac OSX:
```
cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
git clone git://github.com/drewda/cucumber-sublime-bundle.git Cucumber
```
  Linux:
```
cd ~/.config/sublime-text-2/Packages
git clone git://github.com/drewda/cucumber-sublime-bundle.git Cucumber
```
  Windows:
```
cd Users/<user>/AppData/Roaming/Sublime\ Text\ 2/Packages/
git clone git://github.com/drewda/cucumber-sublime-bundle.git Cucumber
```

## Triggers
- Given `giv+tab`
- When `whe+tab`
- then `the+tab`
