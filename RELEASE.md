- Create a new release tag by running:
	- `./release.sh $new_version`
- https://travis-ci.com/facebookincubator/TestSlide/
	- Check if master build is OK.
- https://readthedocs.org/projects/testslide/
	- Trigger bulid for
		- new version
		- master
	- Admin > Versions: make new version the default
- Build & publish
	- `make twine`