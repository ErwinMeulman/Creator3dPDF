# Creator3dPDF

Essential parameters:
    -pdfPath,       Location of output pdf-file
    -u3dPath,       Location of input u3d-file
    -viewName,      The name of view
    -viewSchema,    Schema of view
    -projType,      The type of projection
    -cooX,          Center of orbit coordinates - Ordinate X
    -cooY,          Center of orbit coordinates - Ordinate Y
    -cooZ,          Center of orbit coordinates - Ordinate Z
    -c2cX,          Center of orbit to camera direction vector - Ordinate X
    -c2cY,          Center of orbit to camera direction vector - Ordinate Y
    -c2cZ,          Center of orbit to camera direction vector - Ordinate Z
    -roo,           Orbital radius
    -rol,           Camera roll
    -attr0,         Pdf-file attribute Title
    -attr1,         Pdf-file attribute Creator
    -attr2,         Pdf-file attribute Author
    -attr3,         Pdf-file attribute Subject
    -attr4,         Pdf-file attribute Keywords
    -attr5,         Pdf-file attribute Producer
    -pgW,           Width of page (cm)
    -pgH,           Height of page (cm)
    
Sample:

creator3dpdf.exe -u3dPath sample.u3d -pdfPath sample.pdf -pgW 21.0 -pgH 29.7
