# Start
In this document, I will teach you how to quickly to start to use the Unicorn-test.

## Lets go!
---
### Step 01:Install
It is easy to install the unicorn-test.You need to find the official website and download it from the official website.


### Step 02:Link this in your test program
Ok!Now you need to link the unicorn-test to your test program.You can move Unicorn-test to where the test program is.Then you use this ccode to link.
```Javascript
import './unicorn-test'//link
```

### Step 03:Use the test function
Here is a example.
```Javascript
import './unicorn-test'//link
function AplusB(a,b)
{
	var c=a+b;
	return c;
}//make function
test(AplusB(1,2),3)//use the test function
```

## Step 04:Check the test information
If is true,then it will tell you it is true in console.It also will tell you is false when it is false.

## Step 05:Finish!!!
You can use the test framework now!