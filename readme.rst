jest-templatecache-transformer
==============================

Jest transformer which handles html templates loaded from AngularJS *$templatecache*.

Usage
-----
Add below configuration into *package.json*

.. code:: json

   "jest": {
     "transform": {
       "(html)": "<rootDir>/node_modules/jest-templatecache-transformer"
     }
   }

Requirements
------------
- Node.js v. 6
