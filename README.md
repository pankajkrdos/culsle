# culsle

To use this library in your project open gradle (module)

and in the dependencies section

dependencies
{
...
...
}

add
compile 'com.pro.lib:surf:0.1.1'

so it becomes 

dependencies
{
...
...
compile 'com.pro.lib:surf:0.1.1'
}

Now use the provided class in your app like 
MyView myView = new MyView(context);
setContentView(myView);
