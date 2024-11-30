import tkinter as tk
from currency_converter import CurrencyConverter
a = CurrencyConverter()

window = tk.Tk()
window.geometry("500x360")

def clicked():
    amount = int(entry1.get())
    curr1 = entry2.get()
    curr2 = entry3.get()
    data  = a.convert(amount, curr1, curr2)
    label5 = tk.Label(window, text=data, font="Times 25 bold").place(x = 200, y = 290)

# Add a label to the window
label1 = tk.Label(window, text="Currency Converter", font="Times 25 bold")
label1.place(x=100, y=30)

label2 = tk.Label(window, text = "Enter amount here : ", font="Times 18 bold").place(x=50, y=80)
entry1 = tk.Entry(window)

label3 = tk.Label(window, text = "Enter Currency : ", font="Times 18 bold").place(x=50, y=130)
entry2 = tk.Entry(window)

label4 = tk.Label(window, text = "Convert Currency : ", font="Times 18 bold").place(x=50, y=180)
entry3 = tk.Entry(window)

button1 = tk.Button(window, text="click", command= clicked).place(x=230, y=240)
entry1.place(x=300, y=90)
entry2.place(x=300, y=130)
entry3.place(x=300, y=190)


window.mainloop()
