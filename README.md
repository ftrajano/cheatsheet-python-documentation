# cheatsheet-python-documentation
This file is a cheatsheet of useful tools for python documentation


# PEP8 
We can use the package 
>>pycodestyle 
to helps us adequating our python code to the PEP8 specifications

we need to install with pip
>>pip install pycodestyle

and we can investigate using
>>pycodestyle our_script


another way is using it in the script itself

we need to import the module 
>> import pycodestyle

and create a pycodestyle object, we can verify a list of file as
code_verifier=pycodestyle.StyleGuide()

Run PEP 8 check on multiple files
>> result = style_checker.check_files(['nay_pep8.py', 'yay_pep8.py'])

Print result of PEP 8 style check
>>print(result.messages)
