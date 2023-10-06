This field/property list is meant to be "best effort" and exhaustive but is likely imperfect

Probably not production quality

- probably some field types are missing properties
- field value datatypes are known to have issues from the source
  eg: things like option array can be a list of options [...], empty list ([]), null, or empty string
  this has been a long-standing issue that likely manifests into to "can not read ... from 'undefined'" errors
