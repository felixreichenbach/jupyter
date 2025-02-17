# Client Side Field Level Encryption Demo

This demo is built upon a Jupyter Notebook and will show how to handle encryption keys and data in different databases. In this case, the keys will be hostet onPrem on a local running mongod on your laptop and the data will be stored in Atlas.

The code is written in Python and can easily be adjusted to accomodate specific needs.

Please provide feedback and suggestions for improvement!

If you haven't worked with Jupyter yet, please head to https://jupyter.org/.

Installation on your Mac is easy and straight forward!




## Prerequisits

**pymongo** (version >=3.9)

```pip show pymongo```

```pip install pymongo```

**pymongocrypt**

```pip install pymongocrypt```

**mongocryptd**

Executable in the installation folder of MongoDB Enterprise 4.2.
I have created a symbolic link in to /usr/local/bin/ but may depend on the way you install MongoDB EA.
