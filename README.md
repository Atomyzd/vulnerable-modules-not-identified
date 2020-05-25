## Records of vulnerable modules that cannot be identified by FRFS, NFS and ALL

In “Empirical Studies on the Impact of Filter-based Ranking Feature Selection on Security Vulnerability Prediction”，we analyze the number of vulnerable modules which can not be correctly identified by the methods in a specific category.  Now，we upload the following files. 

- Produce source code (the source code of three real-world large-scale web applications we used)
- drupal-6_0.txt (the vulnerable modules in drupal-6_0  which can not be correctly identified by the methods in a specific category.)
- moodle-2_0_0.txt  (the vulnerable modules in moodle-2_0_0  which can not be correctly identified by the methods in a specific category.)
- phpmyadmin-3_3_0.txt (the vulnerable modules in phpmyadmin-3_3_0  which can not be correctly identified by the methods in a specific category.)

In drupal-6_0.txt,  moodle-2_0_0.txt  and  phpmyadmin-3_3_0.txt,  noVul(FS) represents the vulnerable modules which none of the methods in FS category(using FRFS methods) can correctly identify. noVul(NFS) represents the vulnerable modules which none of the methods in NFS category(NFSA, NFST and NFSM) can correctly identify. noVul(ALL) represents the vulnerable modules which none of the methods in ALL category(including all the FRFS methods and baseline methods) can correctly identify.



