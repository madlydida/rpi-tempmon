#!/usr/bin/env python
# -*- coding: utf-8 -*-
#
#  Read Temp
#  
#  Copyright 2019 root <root@kali>
#  
#  This program is free software; you can redistribute it and/or modify
#  it under the terms of the GNU General Public License as published by
#  the Free Software Foundation; either version 2 of the License, or
#  (at your option) any later version.
#  
#  This program is distributed in the hope that it will be useful,
#  but WITHOUT ANY WARRANTY; without even the implied warranty of
#  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
#  GNU General Public License for more details.
#  
#  You should have received a copy of the GNU General Public License
#  along with this program; if not, write to the Free Software
#  Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston,
#  MA 02110-1301, USA.
#  
#  
# 

#f = open('/root/Documents/New Folder/test','a')
#file_object = open('/root/Documents/New Folder/test','r')  #where file_object is the varialbe to add the file obj ect.
#time.sleep(30)
import time
def dth():
	while(True):
		
		f = open('/sys/class/thermal/thermal_zone0/temp','r')
		read = int(f.read()) / 1000
		print (read, "*c", end='\r')
		#print (f.read(), end='')
		time.sleep(2)

dth()
