Code for the mermaid tool (https://mermaid-js.github.io/). Can be
generated with the live editor (https://mermaid.live/).


Diagram 1 (cf_conv_benefits.svg):
=================================

Code:
-----

graph LR
    A(robust, standardised<br>metadata for netCDF data)
    ==> B(data is more machine-parsable <br>and human-comprehensible)
    ==> C(related software is improved<br>and more maintainable)


Config:
-------

{
  "theme": "base",
  "themeVariables": {
    "nodeBorder" : "#000000",
    "mainBkg" : "#CEE6FF",
    "fontFamily": "arial",
    "fontSize": "30px"
  }
}


Diagram 2 (cf_conv_process.svg):
================================

Code:
-----

graph LR
    D(open proposals<br>on GitHub)
    ==> E(open discussion)
    ==> F(acceptance)
    ==> G(incorporation into<br>the next release)

    E ==> H(turned down in present form)

Config:
-------

{
  "theme": "base",
  "themeVariables": {
    "nodeBorder" : "#000000",
    "mainBkg" : "#D9CCFF",
    "fontFamily": "arial",
    "fontSize": "30px"
  }
}
