# AL-CAPONE

#!/usr/bin/env python3
# -*- coding: utf-8 -*-
"""
Created on Mon Jul 12 13:45:46 2021

@author: jcjoyce
"""
xSmall = [x for x in range(101) if x < 17]
print(xSmall)

xEven = [x for x in range(101) if x%2 == 0]
print(xEven)

y = {x:'even' if x%2 == 0 else 'odd' for x in range(101)}
yEvenKey = {x**2 for x in range(101) if x%2 == 0}
print(yEvenKey)

#Program = AlCapone
