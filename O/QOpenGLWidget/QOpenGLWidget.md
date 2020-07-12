# **QOpenGLWidget**
 
----------
 
## **QOpenGLWidget类是用于渲染OpenGL图形的widget部件**
 
|    属性 | 方法                         |
| -----: | :--------------------------- |
| 头文件: | ` #include <QOpenGLWidget> ` |
| qmake: | QT += widgets                |
|   继承: | QWidget                      |
|   派生: | xxxxxx                       |
 
 
----------
 
## **简述**
 
----------
### **公共类型**
 
|   类型 | 方法                                              |
| -----: | :------------------------------------------------ |
| enum	 | UpdateBehavior { NoPartialUpdate, PartialUpdate } |
|  xxxxx | 222222                                            |
 
 
----------
 
 
### **属性**
| 函数名 | 类型                                                                            |
| ----: | :------------------------------------------------------------------------------ |
|       | QOpenGLWidget(QWidget *parent = nullptr, Qt::WindowFlags f = Qt::WindowFlags()) |
virtual	 | ~QOpenGLWidget()
QOpenGLContext *	 | context() const
GLuint	 | defaultFramebufferObject() const
void | 	doneCurrent()
QSurfaceFormat | 	format() const
QImage | 	grabFramebuffer()
bool	 | isValid() const
void	 | makeCurrent()
void	 | setFormat(const QSurfaceFormat &format)
void	 | setTextureFormat(GLenum texFormat)
void	 | setUpdateBehavior(QOpenGLWidget::UpdateBehavior updateBehavior)
GLenum	 | textureFormat() const
QOpenGLWidget::UpdateBehavior	 | updateBehavior() const
 
----------
 
### **Public Functions**
 
|  类型  | 函数名|
|------:|:------|
| xxxx   |yyyyyyyy|
|xxxxxx |yyyyyyyy|
 
----------
 
### **信号**
 
|  类型  | 函数名|
|------:|:------|
|xxxx| yyyyyy|
 

----------
 
## **详细说明**
 
----------

6666666

----------
 
 
## **成员变量**
 
----------
 
**11111**
描述
 
**相关函数**
 
|  类型  | 函数名|
|------:|:------|
|xxxx|   yyy|
|xxxx|	yyy|
 
**通知信号**
 
|  类型  | 函数名|
|------:|:------|
|xxx| yyy|
 

----------
 
##**成员函数**
 
----------
 
**aaa**
描述aaaaa

----------
 
 
