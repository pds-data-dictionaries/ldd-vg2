# Voyager-2 Local Data Dictionary (LDD)

The Voyager-2 Mission dictionary contains classes that describe attributes of the Voyager 2 mission. 
## Versions

- [1.0.0.0](src/1.0.0.0)
- [1.0.0.1](src/1.0.0.1)

## Builds

A Local Data Dictionary (LDD) is built for each version of the [PDS4 Information Model](https://pds.nasa.gov/pds4/doc/im/).
The build process insures compatiblity of the LDD with the core information model.

This LDD has been built for the following versions of the PDS4 information model.

- [1.9.0.0](build/1.9.0.0)
	- Package: [v1.9.0.0](https://github.com/nasa-pds/ldd-wave/releases/tag/v1.9.0.0)
	
## Notes

Each build is generating using the [lddtool](https://pds.nasa.gov/pds4/software/ldd/) specific to a version of the [PDS4 Information Model](https://pds.nasa.gov/pds4/doc/im/). The build command used is:

```
lddtool -lpJM ldd-file.xml
```

Documentation included in the source (src) directory is generated using the "pds-ldd-doc" tool in the [pds4-tools](https://github.com/nasa-pds/pds4-tools) package. The build command used is:

```
pds-ldd-doc ldd-file.xml > README.md
```

After a build the README.md files are updated (manually) to reflect the content of repository.

