---
title: about
date: 2023-12-02 22:53:46
---
## This is the web page of Class 6, Grade 10 of The Second High School attached to Beijing Normal University.

## On this site you'll find all kinds of posts related to us.
## 一些没用的东西（
```py3
import tkinter as tk
from tkinter import *
from tkinter import ttk


root = tk.Tk()
frm = ttk.Frame(root, padding=10)
frm.grid()
rp=-114
def action1():
    global rp
    rp=rp-1
ttk.Label(frm, text="鞠佶昌rp:"+str(rp)).grid(column=0, row=0)
ttk.Button(frm,text="点我试试",command=action1).grid(column=1,row=0)
ttk.Button(frm, text="Quit", command=root.destroy).grid(column=1, row=1)

root.update()
root.mainloop()
```