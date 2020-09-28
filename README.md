# python_calc

Calculator using python pyQt

MVC Design Pattern (Model--View--Control design)

STEPS:

install pyQt 

create a file test.py and add the following for testing pyQt:

	import sys
	from PyQt5.QtWidgets import QAplication
	from PyQt5.QtWidgets import QLabel
	from PyQt5.QtWidgets import QWidget
		

Create a file view.py to create GUI for the calculator:

	app = QApplication(sys.argv)
	window = QWidget()
	window.QLabel("This is Test", parent = window)
	window.show()
	sys.exit(app.exce_())
	
	
	Add following module:
	from PyQt5.QtWidgets import QMainWindow
	from PyQt5.QtWidgets import QWidget
	from PyQt5.QtWidgets import QGridLayout
	from PyQt5.QtWidgets import QLineEdit
	from PyQt5.QtWidgets import QPushButton
	from PyQt5.QtWidgets import QVBoxLayout


	
