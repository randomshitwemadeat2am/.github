# Introduction
Hello! We're @etherealthedev and @diedyesterdaywashere, 2 young devs making random stuff at night, some of our projects are gonna be open-sourced in this organisation!

---

The Chicken Butt joke in 10 different languages (Ethereal):

Python:
```python
print("Guess what?")
response = input().lower()
if response == "what":
    print("Chicken Butt!")
```

Javascript:
```js
console.log("Guess what?");
var response = prompt().toLowerCase();
if (response === "what") {
    console.log("Chicken Butt!");
}
```

Java:
```java
import java.util.Scanner;

public class ChickenButt {
    public static void main(String[] args) {
        System.out.println("Guess what?");
        Scanner scanner = new Scanner(System.in);
        String response = scanner.nextLine().toLowerCase();
        if (response.equals("what")) {
            System.out.println("Chicken Butt!");
        }
    }
}
```

C#:
```cs
using System;

class ChickenButt {
    static void Main() {
        Console.WriteLine("Guess what?");
        string response = Console.ReadLine().ToLower();
        if (response == "what") {
            Console.WriteLine("Chicken Butt!");
        }
    }
}
```

Ruby:
```ruby
puts "Guess what?"
response = gets.chomp.downcase
if response == "what"
    puts "Chicken Butt!"
end
```

PHP:
```php
<?php
echo "Guess what?\n";
$response = strtolower(trim(fgets(STDIN)));
if ($response === "what") {
    echo "Chicken Butt!\n";
}
?>
```

C++
```cpp
#include <iostream>
#include <string>
#include <algorithm>

int main() {
    std::cout << "Guess what?" << std::endl;
    std::string response;
    std::getline(std::cin, response);
    std::transform(response.begin(), response.end(), response.begin(), ::tolower);
    if (response == "what") {
        std::cout << "Chicken Butt!" << std::endl;
    }
    return 0;
}
```

Swift:
```swift
import Foundation

print("Guess what?")
if let response = readLine()?.lowercased() {
    if response == "what" {
        print("Chicken Butt!")
    }
}
```

Go:
```go
package main

import (
	"fmt"
	"strings"
)

func main() {
	var response string
	fmt.Println("Guess what?")
	fmt.Scanln(&response)
	response = strings.ToLower(response)
	if response == "what" {
		fmt.Println("Chicken Butt!")
	}
}
```

Rust:
```rust
use std::io;

fn main() {
    println!("Guess what?");
    let mut response = String::new();
    io::stdin().read_line(&mut response).expect("Failed to read line");
    response = response.trim().to_lowercase();
    if response == "what" {
        println!("Chicken Butt!");
    }
}
```

Haha!
