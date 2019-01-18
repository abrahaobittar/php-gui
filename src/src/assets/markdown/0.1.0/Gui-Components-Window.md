Gui\Components\Window
===============

This is the Window Class

It is a visual component for window


* Class name: Window
* Namespace: Gui\Components
* Parent class: Gui\Components\ContainerObject





Properties
----------


### $lazarusClass

    protected string $lazarusClass = 'TObject'

The lazarus class as string



* Visibility: **protected**


### $children

    protected array $children = array()

The children objetcs



* Visibility: **protected**


### $lazarusObjectId

    protected integer $lazarusObjectId

The communication object id



* Visibility: **protected**


### $application

    protected \Gui\Application $application

The application object



* Visibility: **protected**


### $eventHandlers

    protected array $eventHandlers = array()

The array of callbacks



* Visibility: **protected**


### $runTimeProperties

    protected array $runTimeProperties = array()

The array of special properties



* Visibility: **protected**


Methods
-------


### setTitle

    \Gui\Components\Window Gui\Components\Window::setTitle(string $title)

Sets the window title



* Visibility: **public**


#### Arguments
* $title **string**



### getTitle

    String Gui\Components\Window::getTitle()

Gets the window title



* Visibility: **public**




### setIcon

    \Gui\Components\Window Gui\Components\Window::setIcon(string $icon)

Sets the icon



* Visibility: **public**


#### Arguments
* $icon **string**



### setWindowState

    \Gui\Components\Window Gui\Components\Window::setWindowState(string $state)

Sets the window state. Can be one of the following values: fullscreen, minimized, maximized, normal



* Visibility: **public**


#### Arguments
* $state **string**



### appendChild

    void Gui\Components\ContainerObjectInterface::appendChild(\Gui\Components\VisualObjectInterface $object)

Append object as child



* Visibility: **public**
* This method is defined by Gui\Components\ContainerObjectInterface


#### Arguments
* $object **Gui\Components\VisualObjectInterface**



### getChild

    \Gui\Components\VisualObjectInterface Gui\Components\ContainerObjectInterface::getChild(integer $lazarusObjectId)

Get child



* Visibility: **public**
* This method is defined by Gui\Components\ContainerObjectInterface


#### Arguments
* $lazarusObjectId **integer**



### getChildren

    array Gui\Components\ContainerObjectInterface::getChildren()

Get children array



* Visibility: **public**
* This method is defined by Gui\Components\ContainerObjectInterface




### getAutoSize

    Boolean Gui\Components\VisualObjectInterface::getAutoSize()

Get the auto size



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setAutoSize

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setAutoSize(Boolean $autoSize)

Set the auto size



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $autoSize **Boolean**



### getBackgroundColor

    String Gui\Components\VisualObjectInterface::getBackgroundColor()

Get the background color



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setBackgroundColor

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setBackgroundColor(string $color)

Set the background Color



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $color **string**



### getBottom

    integer Gui\Components\VisualObjectInterface::getBottom()

Gets the value of bottom in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setBottom

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setBottom(integer $bottom)

Sets the value of bottom in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $bottom **integer**



### getHeight

    integer Gui\Components\VisualObjectInterface::getHeight()

Gets the value of height in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setHeight

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setHeight(integer $height)

Sets the value of height in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $height **integer**



### getLeft

    integer Gui\Components\VisualObjectInterface::getLeft()

Gets the value of left in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setLeft

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setLeft(integer $left)

Sets the value of left in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $left **integer**



### getRight

    integer Gui\Components\VisualObjectInterface::getRight()

Gets the value of right in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setRight

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setRight(integer $right)

Sets the value of right in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $right **integer**



### getTop

    integer Gui\Components\VisualObjectInterface::getTop()

Gets the value of top in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setTop

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setTop(integer $top)

Sets the value of top in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $top **integer**



### getWidth

    integer Gui\Components\VisualObjectInterface::getWidth()

Gets the value of width in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setWidth

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setWidth(integer $width)

Sets the value of width in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $width **integer**



### getVisible

    boolean Gui\Components\VisualObjectInterface::getVisible()

Gets the value of visible in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface




### setVisible

    \Gui\Components\VisualObjectInterface Gui\Components\VisualObjectInterface::setVisible(boolean $visible)

Sets the value of visible in pixel.



* Visibility: **public**
* This method is defined by Gui\Components\VisualObjectInterface


#### Arguments
* $visible **boolean**



### __construct

    void Gui\Components\Object::__construct(array $defaultAttributes, \Gui\Components\ContainerObjectInterface $parent, \Gui\Application $application)

The constructor



* Visibility: **public**
* This method is defined by Gui\Components\Object


#### Arguments
* $defaultAttributes **array**
* $parent **Gui\Components\ContainerObjectInterface**
* $application **Gui\Application**



### __call

    self|mixed Gui\Components\Object::__call(string $method, array $params)

The special method used to do the getters/setters for special properties



* Visibility: **public**
* This method is defined by Gui\Components\Object


#### Arguments
* $method **string**
* $params **array**



### call

    void Gui\Components\Object::call(string $method, array $params, boolean $isCommand)

This method is used to send an object command/envent to lazarus



* Visibility: **protected**
* This method is defined by Gui\Components\Object


#### Arguments
* $method **string**
* $params **array**
* $isCommand **boolean**



### set

    void Gui\Components\Object::set(string $name, mixed $value)

this method is used to send the IPC message when a property is set



* Visibility: **protected**
* This method is defined by Gui\Components\Object


#### Arguments
* $name **string**
* $value **mixed**



### get

    mixed Gui\Components\Object::get(string $name)

This magic method is used to send the IPC message when a property is get



* Visibility: **protected**
* This method is defined by Gui\Components\Object


#### Arguments
* $name **string**



### getLazarusObjectId

    mixed Gui\Components\LazarusObjectInterface::getLazarusObjectId()

Gets the value of lazarusObjectId.



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface




### getLazarusClass

    mixed Gui\Components\LazarusObjectInterface::getLazarusClass()

Gets the value of lazarusClass.



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface




### fire

    void Gui\Components\LazarusObjectInterface::fire(string $eventName)

Fire an object event



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface


#### Arguments
* $eventName **string**



### on

    void Gui\Components\LazarusObjectInterface::on(string $eventName, callable $eventHandler)

Add a listener to an event



* Visibility: **public**
* This method is defined by Gui\Components\LazarusObjectInterface


#### Arguments
* $eventName **string**
* $eventHandler **callable**

