# DBMS_SoyabeanCrop
DBMS project on disease tracker of soyabean

This is a project that tracks the type and severity of diseases in the Soybean crop.
The project is built primarily by using MySQL in the backend and connected with JAVA for the front end. There are 4 main tables: Deficiency, Disease, Factor, and Severity in the project. The functions of the tables are:
1. Deficiency table with rows containing deficiency Id as did, deficient element as elem, and leaf color as lcolor
2. Diseases table with rows containing disease Id as did,name of the disease as name and colour as scolor
3. Factors table with rows containing factor Id as fid and factor as a factor
4. Severity table with rows containing severity Id as sid, deficiency Id as did, factor Id as fid, and severity as the severity
