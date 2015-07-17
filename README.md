# druphpet-modules

If you don't want to wait every time during `vagrant up` or `vagrant reload --provision` or `vagrant provision` while Puppet modules are being synced, you can just do the following:
- Download the repository contents as [Zip archive](https://github.com/alehkot/druphpet-modules/archive/master.zip) and extract it to `puphpet/puppet/modules folder`.
- Edit `puphpet/config.yaml` file and switch `sync_modules` to `false`.
