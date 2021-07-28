#create window on python gui

from tkinter import *
from tkinter import messagebox

root = Tk()
root.title("TIC-TAC-TOE")

#background color
root.configure(background ="Teal")

#create top frame, write label
Top_Frame = Frame (root, bg = "Teal", pady=2, width=1350, height=100, relief =RIDGE)
Top_Frame.grid(row = 0, column = 0)

label = Label(Top_Frame, font=("arial", 50, "bold"), text="TIC TAC TOE GAME", bd = 21, bg="Teal", fg="cornsilk", justify=CENTER)
label.grid(row = 1, column = 1)

#main frame
Main_Frame = Frame (root, bg = "light blue", bd= 10, width = 1350, height=600, relief=RIDGE)
Main_Frame.grid(row = 1, column = 0)

#Frame_1
Frame_1 = Frame (Main_Frame, bd= 10, width = 750, height=500, pady=2, padx=10, bg = "Teal", relief =RIDGE)
Frame_1.grid(row = 2, column = 1 )

#Frame_2
Frame_2 = Frame (Main_Frame, bd= 10, width = 360, height=300, pady=2, padx=10, bg = "Cadet blue", relief =RIDGE)
Frame_2.grid(row = 0, column = 1)

#player name
#pa = StringVar()
#playerb = StringVar()
p1 = StringVar()
p2 = StringVar()

#write labels
label1 = Label(Frame_2, text="Player-1 Name: ")
label1.grid(row = 1,column = 1)

label2 = Label(Frame_2, text="Player-2 Name: ")
label2.grid(row = 2,column = 1)

#player names entry
player1 = Entry(Frame_2, textvariable = p1, bd = 5)
player1.grid(row = 1,column = 2)

player2 = Entry(Frame_2, textvariable = p2, bd = 5)
player2.grid(row = 2,column = 2)


clicked = True       #Python Tkinter GUI Tutorial #113
count = 0            #Python Tkinter GUI Tutorial #113

#function disable all button
def disable_all_buttons():            #Python Tkinter GUI Tutorial #113
    b_1.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_2.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_3.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_4.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_5.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_6.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_7.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_8.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113
    b_9.config(state= DISABLED)       #Python Tkinter GUI Tutorial #113

#function check win?   
def check_if_win():       #Python Tkinter GUI Tutorial #113
    global winner        #Python Tkinter GUI Tutorial #113
    winner = False       #Python Tkinter GUI Tutorial #113
    
    #Xs
    
    if b_1["text"] == "X" and b_2["text"] == "X" and b_3["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_1.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_2.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_3.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
        
    elif b_4["text"] == "X" and b_5["text"] == "X" and b_6["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_4.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_6.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_7["text"] == "X" and b_8["text"] == "X" and b_9["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_7.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_8.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_9.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_1["text"] == "X" and b_4["text"] == "X" and b_7["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_1.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_4.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_7.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_2["text"] == "X" and b_5["text"] == "X" and b_8["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_2.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_8.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_3["text"] == "X" and b_6["text"] == "X" and b_9["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_3.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_6.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_9.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
        
    elif b_1["text"] == "X" and b_5["text"] == "X" and b_9["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_1.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_9.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()           #Python Tkinter GUI Tutorial #113
        
    elif b_3["text"] == "X" and b_5["text"] == "X" and b_7["text"] == "X":       #Python Tkinter GUI Tutorial #113
        b_3.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_7.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-1 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113

  #0s     
        
    elif b_1["text"] == "0" and b_2["text"] == "0" and b_3["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_1.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_2.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_3.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_4["text"] == "0" and b_5["text"] == "0" and b_6["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_4.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_6.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player 2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_7["text"] == "0" and b_8["text"] == "0" and b_9["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_7.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_8.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_9.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_1["text"] == "0" and b_4["text"] == "0" and b_7["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_1.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_4.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_7.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_2["text"] == "0" and b_5["text"] == "0" and b_8["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_2.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_8.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113
    
    elif b_3["text"] == "0" and b_6["text"] == "0" and b_9["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_3.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_6.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_9.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113

    elif b_1["text"] == "0" and b_5["text"] == "0" and b_9["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_1.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_9.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()           #Python Tkinter GUI Tutorial #113
        
    elif b_3["text"] == "0" and b_5["text"] == "0" and b_7["text"] == "0":       #Python Tkinter GUI Tutorial #113
        b_3.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_5.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        b_7.config(bg = "yellow")       #Python Tkinter GUI Tutorial #113
        winner = True       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo ("Tic Tac Toe","CONGRATULATIONS! Player-2 Won The Game.")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()        #Python Tkinter GUI Tutorial #113
        
    #if the game is tie    
    if count == 9 and winner == False:       #Python Tkinter GUI Tutorial #113
        messagebox.showinfo("Tic Tac Toe", "It's a Tie :(\nPlease Try Again :)")       #Python Tkinter GUI Tutorial #113
        disable_all_buttons()       #Python Tkinter GUI Tutorial #113

#function click        
def click(a):       #Python Tkinter GUI Tutorial #113
    global clicked, count       #Python Tkinter GUI Tutorial #113

    if a["text"] == " " and clicked == True:        #Python Tkinter GUI Tutorial #113
        a["text"] = "X"       #Python Tkinter GUI Tutorial #113
        clicked = False       #Python Tkinter GUI Tutorial #113
        count += 1       #Python Tkinter GUI Tutorial #113
        check_if_win()       #Python Tkinter GUI Tutorial #113
        
    elif a["text"] == " " and clicked == False:       #Python Tkinter GUI Tutorial #113
        a["text"] = "0"       #Python Tkinter GUI Tutorial #113
        clicked = True       #Python Tkinter GUI Tutorial #113
        count += 1       #Python Tkinter GUI Tutorial #113
        check_if_win()       #Python Tkinter GUI Tutorial #113
        
    else:       #Python Tkinter GUI Tutorial #113
        messagebox.showerror("Tic Tac Toe", "Hey! this box has already been selected\nPick Another Box")       #Python Tkinter GUI Tutorial #113

#function restart        
def restart():       #Python Tkinter GUI Tutorial #113
    global b_1, b_2, b_3, b_4, b_5, b_6, b_7, b_8, b_9       #Python Tkinter GUI Tutorial #113
    global clicked, count       #Python Tkinter GUI Tutorial #113
    clicked = True       #Python Tkinter GUI Tutorial #113
    count = 0       #Python Tkinter GUI Tutorial #113
    
    b_1 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_1))       #Python Tkinter GUI Tutorial #113
    b_1.grid(row = 1, column = 1)       #Python Tkinter GUI Tutorial #113
    
    b_2 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_2))       #Python Tkinter GUI Tutorial #113
    b_2.grid(row = 1, column = 2)       #Python Tkinter GUI Tutorial #113
    
    b_3 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_3))       #Python Tkinter GUI Tutorial #113
    b_3.grid(row = 1, column = 3)       #Python Tkinter GUI Tutorial #113
    
    b_4 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_4))       #Python Tkinter GUI Tutorial #113
    b_4.grid(row = 2, column = 1)       #Python Tkinter GUI Tutorial #113
    
    b_5 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_5))       #Python Tkinter GUI Tutorial #113
    b_5.grid(row = 2, column = 2)       #Python Tkinter GUI Tutorial #113
    
    b_6 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_6))       #Python Tkinter GUI Tutorial #113
    b_6.grid(row = 2, column = 3)       #Python Tkinter GUI Tutorial #113
    
    b_7 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_7))       #Python Tkinter GUI Tutorial #113
    b_7.grid(row = 3, column = 1)       #Python Tkinter GUI Tutorial #113
    
    b_8 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_8))       #Python Tkinter GUI Tutorial #113
    b_8.grid(row = 3, column = 2)       #Python Tkinter GUI Tutorial #113
    
    b_9 = Button(Frame_1, text =" ", font = ("arial",20),height = 3, width = 6, bg = "Cadet blue", command = lambda: click(b_9))       #Python Tkinter GUI Tutorial #113
    b_9.grid(row = 3, column = 3)       #Python Tkinter GUI Tutorial #113
    
    
#function main    
def main():
    info = restart()
    
main_button = Button(Frame_2, text="Restart", command = main, font =("arial", 15), bg = "lightgrey")
main_button.grid(row = 3, column = 2)



restart()       #Python Tkinter GUI Tutorial #113

root.mainloop()
