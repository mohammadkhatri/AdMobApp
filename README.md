# AdMob in all activities

* This is a sample demo app creating admob banner at bottom of any activity by using a single piece of code.
* It doesn't affect your layout and you have not to implement admob code in each and every screen.
* It uses `android.R.id.content`
* Read More [Here](http://mohammadkhatri.github.io/blog/2015/08/03/AdMob-Banner-In-all-activities/).

```java
@Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        setupAdAtBottom();
    }
```

```
Copyright [2015] [Mohammadhussain Khatri]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
