You can observe that there is an issue with the 'onInput' function. The button passes the value, and you can see it, but the value of 'name' does not behave similarly.

![image](https://github.com/barel-mishal/no-reactive/assets/56759851/54a807de-e2ff-4b09-acf5-6ceef253afef)

Why does this happen?
In the store, the parameter does not get reassigned upon creation, which disrupts the reactivity. Here is an image demonstrating how I define the store:
![image](https://github.com/barel-mishal/no-reactive/assets/56759851/ff4f7dfb-9fc3-4e79-a4ff-454d17589ec6)
