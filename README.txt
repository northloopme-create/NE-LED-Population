NE LED POPULATION V0.3

PURPOSE
This build turns the app toward a controlled Ellis Signs manufacturing / ordering / assembly engineering database.

MAIN CHANGES
- Rebuilt sign-type taxonomy so each sign type has valid face/skin constructions and illumination modes.
- Flex-face is explicitly printed double-strike flex skin; rigid acrylic/polycarbonate and SEG/fabric are separate sign families.
- Added fret-cut trays, flat-cut halo letters, block acrylic, rigid lightboxes, flex-face boxes, SEG/fabric, projecting signs, totems, menu/poster boxes, neon/flex, ribbon/extrusion and edge-lit acrylic.
- Product compatibility is now filtered by sign type + internal illuminated depth + colour + supplier + voltage.
- Expanded product database with SloanLED VL5, FirstLite, Citi-LED, UltraLEDs/Tagra and Applelec light-sheet/ribbon systems.
- Products/data that are not fully verified are flagged [VERIFY] and the app does not invent power data.
- Supplier/source is carried into the BOM CSV.

CONTROL PRINCIPLE
This software should become Ellis Signs' controlled engineering reference. Every supplier product must eventually have:
manufacturer, product code, version/date, voltage, W/module or W/m, lumens, optics, IP, dimensions, max run, allowable driver loads, application types, depth rules, face/material conditions, spacing/density tables, cable requirements, controller requirements, warranty and source URL/datasheet revision.

NEXT REQUIRED ENGINEERING PHASE
- Import full manufacturer datasheets and current power-supply tables.
- Add SignComp extrusion/profile database and BOM logic by sign construction.
- Add cable size / voltage-drop calculator.
- Add circuit grouping and driver mapping.
- Add separate algorithms for modules, side-light bars, ribbon, light sheet and halo.
- Add signed-off product-data revision control before a project can be marked RELEASED TO PRODUCTION.
