dict_aisle = { "A100": ['bananas', 'milk', 'bread'],                     
              "A101": ['pens', 'pencils', 'paper'],                       
              "A102": ['canned_peas', 'canned_carrots', 'canned_beans'],                       
              "A103": ['plates', 'glasses', 'table_cloth'] } 
 
dict_employee_IDs = {"ID01": 'John Papa',
 "ID02": 'David Thompson',
 "ID03": 'Terry Gao',
 "ID04": 'Barry Tex'}

print(dict_employee_IDs["ID02"])  
del(dict_aisle["A102"])
print(dict_aisle)

OUTPUT:
David Thompson
{'A100': ['bananas', 'milk', 'bread'], 'A101': ['pens', 'pencils', 'paper'], 'A103': ['plates', 'glasses', 'table_cloth']}
