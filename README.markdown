Forked from: http://github.com/andre/geokit-rails

The official geokit-rails mysql adapter name does not match the naming convention of the jdbc-mysql adapter ("MySQL" vs "Mysql"). Patched the adapter's class name to match our adapter name for now. This should probably be discussed with the geokit-rails maintainers as there have to be others that will run into this.
