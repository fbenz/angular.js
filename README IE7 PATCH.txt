Patch created with:
diff -c jqLite.js.unpatched jqLite.js > jqLite.js.patch

The patch is necessary, because the use of setAttribute/getAttribute was introducted with the following commit and both functions are not supported by IE7:
https://github.com/angular/angular.js/commit/c785267eb8780d8b7658ef93ebb5ebddd566294d
