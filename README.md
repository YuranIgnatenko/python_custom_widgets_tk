# python_custom_widgets_tk

> Demo screen
![demo](/src/screen.png)

> Requirements
```
python3
tkinter
pillow
```
> Install ImageTk

```
sudo apt-get install -y python3-pil.imagetk
```

> Install 
```
git clone https://github.com/YuranIgnatenko/python_custom_widgets_tk.git
```

> Example
```python
root = Tk()

lb1, lb2 = WgtLabel().create(root, 'x1 :', '8.9008f', 10, 10) # return Label,Label

WgtLabel().create(root, 'x2 :', '8.9002f', 10, 10) # return Label,Label

root.mainloop()

```