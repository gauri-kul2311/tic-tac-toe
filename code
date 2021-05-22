from Tkinter import *
import tkMessageBox
window=Tk()
window.title("Welcome To TIC TAC TOE Game")
window.geometry("400x300")
lbl=Label(window,text="Tic-Tac-Toe",font=('Helvetica','35'))
lbl.grid(row=0,column=0)
lbl=Label(window,text="player 1:X",font=('Helvetica','25'))
lbl.grid(row=1,column=0)
lbl=Label(window,text="player 2:O",font=('Helvetica','25'))
lbl.grid(row=2,column=0)
turn=1;# to handle the turn
def select_box_1():
global turn
if button_1["text"]==" ":
if turn==1:
turn=2 #to filp player
button_1["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_1["text"]="O"
check_for_winner()
def select_box_2():
global turn
if button_2["text"]==" ":
if turn==1:
turn=2 #to filp player
button_2["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_2["text"]="O"
check_for_winner()
def select_box_3():
global turn
if button_3["text"]==" ":
if turn==1:
turn=2 #to filp player
button_3["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_3["text"]="O"
check_for_winner()
def select_box_4():

global turn
if button_4["text"]==" ":
if turn==1:
turn=2 #to filp player
button_4["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_4["text"]="O"
check_for_winner()
def select_box_5():
global turn
if button_5["text"]==" ":
if turn==1:
turn=2 #to filp player
button_5["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_5["text"]="O"
check_for_winner()
def select_box_6():
global turn
if button_6["text"]==" ":
if turn==1:
turn=2 #to filp player
button_6["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_6["text"]="O"
check_for_winner()
def select_box_7():
global turn
if button_7["text"]==" ":
if turn==1:
turn=2 #to filp player
button_7["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_7["text"]="O"
check_for_winner()
def select_box_8():
global turn
if button_8["text"]==" ":
if turn==1:
turn=2 #to filp player
button_8["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_8["text"]="O"
check_for_winner()
def select_box_9():

global turn
if button_9["text"]==" ":
if turn==1:
turn=2 #to filp player
button_9["text"]="X" #if button is empty it will insert text into it
elif turn==2:
turn=1
button_9["text"]="O"
check_for_winner()
counter=1
def check_for_winner():
global counter
row_1=(button_1["text"]==button_2["text"]==button_3["text"]!=" ")
row_2=(button_4["text"]==button_5["text"]==button_6["text"]!=" ")
row_3=(button_7["text"]==button_8["text"]==button_9["text"]!=" ")
column_1=(button_1["text"]==button_4["text"]==button_7["text"]!=" ")
column_2=(button_2["text"]==button_5["text"]==button_8["text"]!=" ")
column_3=(button_3["text"]==button_6["text"]==button_9["text"]!=" ")
diagonal_1=(button_1["text"]==button_5["text"]==button_9["text"]!=" ")
diagonal_2=(button_7["text"]==button_5["text"]==button_3["text"]!=" ")
counter+=1
if row_1:
win(button_1["text"])
if row_2:
win(button_4["text"])
if row_3:
win(button_7["text"])
if column_1:
win(button_1["text"])
if column_2:
win(button_2["text"])
if column_3:
win(button_3["text"])
if diagonal_1:
win(button_1["text"])
if diagonal_2:
win(button_3["text"])
if counter==10:
labl=Label(window,text="Game Tied..... Try Again
:)",bg="red",fg="black",font=('Helvetica','35'))
labl.pack()
def win(player):
winner=Label(window,text="congratulations...!! "+player+"
won",bg="purple",fg="yellow",font=('Helvetica','35'))
winner.pack()
button_1=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_1)
button_1.grid(column=1,row=1)

button_2=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_2)
button_2.grid(column=1,row=2)
button_3=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_3)
button_3.grid(column=1,row=3)
button_4=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_4)
button_4.grid(column=2,row=1)
button_5=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_5)
button_5.grid(column=2,row=2)
button_6=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_6)
button_6.grid(column=2,row=3)
button_7=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_7)
button_7.grid(column=3,row=1)
button_8=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_8)
button_8.grid(column=3,row=2)
button_9=Button(window,text="
",bg="black",fg="white",width=20,height=15,font=('Helvetica','10'),activebackground="pink
",command=select_box_9)
button_9.grid(column=3,row=3)
window.mainloop()
