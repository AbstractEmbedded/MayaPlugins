Currently, the only posted Maya Plugin is an Alembic Export Plugin.  The purposes of packaging Alembic geometry export functionality as a geometry export plugin are several-fold over the existing Alembic Geometry Cache Export funcitonality packaged by default with a Maya release:

1.  The latest version of Maya always uses an outdated version of the Alembic SDK.  Through Maya 2018, this was Alembic 1.5.3, while Maya 2019 finally updated to the Alembic 1.7.5 SDK.  The latest version of Alembic is currently 1.7.10.

2.  To provide a path for utilizing Alembic as a complete standalone renderable asset format:
  
    --To extend the Maya Alembic output functionality to include face set groupings
    --To extend current Maya Alembic output functionality to make use of the new(ish) AbcMaterial API, populated with Data from Maya hypershade objects  
