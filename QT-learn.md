python子类定义中使用super（）调用父类成员函数，也可以使用父类名称调用父类成员函数

## qt基本使用方法 py
    app = QtWidgets.QApplication(sys.argv)
    widget = QtWidgets.QWidget()
    widget.show()
    sys.exit(app.exec_())
添加其他ui部件可以将实例作为widget的孩子

## qt多线程使用 py
    class myThread(QThread):
        def run(self):
        # 线程中要做的事情

    app = QtWidgets.QApplication(sys.argv)
    widget = QtWidgets.QWidget()    
    widget.show()
    thread=myThread()
    thread.start()
    sys.exit(app.exec_())

## 信号和槽
    # 自定义信号和槽
    sig = pyqtSignal(int,int) # 信号
    sig.connect(slot) # 接受者的槽
    sig.emit(inta,intb) #发送者
    def slot(inta,intb): # 槽
        # 接受到信号要做的事情

    # 使用button自带的信号click
    button.clicked.connect(partial(slot, a,b,c))
    def slot(a,b,c): 
        # 接受到信号要做的事情