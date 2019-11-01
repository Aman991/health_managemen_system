# health_management_system
I have wriitten code for  health management system 
# health managment system make by Aman991
n1 = 'harry'
n2 = 'jerry'
n3 = 'jack'
import datetime
p = datetime.datetime.now()
n = input('enter name : ')
n.lower()
if n == n1 :
    print('what is input food or exe  ')
    s1 = 'Food'
    s2  = 'exe'
 
    n1  = input('input Food and exe : ')
    
    print('check ........... ')
    if n1==s1:
        
       
        print('what is write in text file  : ')
        n2 = input('what is write in text file \n : ')
        print('\n')

        with open('Harry_food.txt','a') as f:
            f.write(f'{p} --->    :     {n2}')
            
        print('Thanks for written')
        
    elif n1==s2:
               
        print('what is write in text file : ')
        n2 = input('what is write in text file \n : ')
        print('\n')
        print('\n')
        print('\n')
        print('\n')

        with open('Harry_exe.txt','a') as f:
            f.write(f'{p} --->    :     {n2}')
            
                # func(n2)

    else:
        print('Invaild input !! ')
       
elif n==n2:
    print('what is input food or exe  ')
    s1 = 'Food'
    s2  = 'exe'
 
    n1  = input(f'input Food and exe : ')
    
    print('check ........... ')
    if n1==s1:
        
       
        print('what is write in text file : ')
        n2 = input('what is write in text file \n : ')
        print('\n')
        

        with open('jerry_food.txt','a') as f:
            f.write(f'{p} --->    :     {n2}')
            
        print('Thanks for written')
    elif n1==s2:
               
        print('what is write in text file  : ')
        n2 = input('what is write in text file \n  : ')
        print('\n')


        with open('jerry_exe.txt','a') as f:
            f.write(f'{p} --->    :     {n2}')
            
                # func(n2)
        print('Thanks for written')
        
    else:
        print('Invaild input !! ')
       
elif n==n3:
    print('what is input food or exe  ')
    s1 = 'Food'
    s2  = 'exe'
 
    n1  = input(f'input Food and exe \n : ')
    
    print('check ........... ')
    if n1==s1:
        
       
        print('what is write in text file : ')
        n2 = input('what is write in text file \n : ')
        print('\n')
    

        with open('jack_food.txt','a') as f:
            f.write(f'{p} --->    :     {n2}')
        print('Thanks for written')
        
    elif n1==s2:
               
        print('what is write in text file  : ')
        n2 = input('what is write  in text file \n : ')
        print('\n')
    

        with open('jack_exe.txt','a') as f:
            f.write(f'{p} --->    :     {n2}')
            
        print('Thanks for written')
        

    else:
        print('Invaild input !! ')
else:
    print(f'{n} is not exist ')
