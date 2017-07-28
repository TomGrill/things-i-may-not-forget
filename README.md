# things-i-may-not-forget



# MSDF

In OpenGL ES we can read the available extension like this:
```java
String result = Gdx.gl.glGetString(GL20.GL_EXTENSIONS);
String[] res = result.split(" ");

for (String s : res) {
  System.out.println(s);
}
```





