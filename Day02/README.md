# 学习要点

- Kotlin 语言基础
- Android Studio With Kotlin



## Kotlin 语言基础
<http://kotlinlang.org/docs/reference/basic-syntax.html>
[中文](https://www.kotlincn.net/docs/reference)

Java VS Kotlin
```java
public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);//设置要显示的视图
    }
}
```

```kotlin
class MainActivity : AppCompatActivity() {

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
    }
}
```


## Android Studio With Kotlin
[Demo](https://github.com/a112121788/Learn-Android-Dev/tree/master/Day02)

