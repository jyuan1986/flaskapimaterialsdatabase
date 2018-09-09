# API for Materials Database

Materials Database is an online database with structural and dielectric information of various crystalline materials. 
For each material, information is described via a row in SQLite3 database. A row can be divided into different groups:
Name, Space Group, Band Gap (exp), Phonon Frequency (max), Dielectric Breakdown Strength Fb (exp), Dielectric Breakdown Strength Fb (ml), Dielectric Constant (tot), Dielectric Constant (ele), Density, Bulk Modulus, Nearest Neighbor Distance

API is constructed via Flask framework and fully restful. 

