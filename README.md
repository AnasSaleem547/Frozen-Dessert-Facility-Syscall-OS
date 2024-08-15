# Frozen Dessert Facility Simulation System

## Introduction

The **Frozen Dessert Facility Simulation System** is a project aimed at simulating the operations of an ice cream shop. This simulation leverages operating system principles to manage inventory and enhance customer service. The project demonstrates the practical application of threads and system calls to prevent race conditions and ensure resource synchronization, contributing to the overall operational efficiency of the shop.

## Features

- **Customer Interaction:** Customers can interact with the ice cream parlor by selecting their preferred flavor and topping.
- **Concurrency:** Multithreading is implemented using POSIX threads (`pthreads`), allowing multiple customers to be served concurrently.
- **Mutexes:** Mutexes ensure thread safety when accessing shared resources, such as flavor and topping availability, as well as total revenue.
- **Dynamic Pricing:** Prices for flavors and toppings are stored in arrays, allowing easy modification and dynamic pricing.
- **Error Handling:** The system handles errors by informing customers if their selected flavor or topping is unavailable and prompts them to make another selection.
- **Logging:** A custom system call (`SYS_MY_CUSTOM_LOG`) logs customer transactions, including their name, selected flavor and topping, and total bill.

## Technologies Used

- **C Programming Language:** The project is implemented in C, a widely-used language for system programming.
- **POSIX Threads (pthread):** POSIX Threads are utilized to implement multithreading in the simulation.
- **VMware Workstation 17:** A virtual machine environment was created using VMware Workstation 17.
- **Linux (Ubuntu):** The system runs on Ubuntu, a popular Linux distribution.

##How To Implement SYS Call

- **Clone:** Clone this repository into your pc or simply download it to get our codes.
- **Video:** Watch this youtube video (https://youtu.be/qcsKGWshRZE?si=MwP88MRMZLpw8t-d) for properly implementing custom SysCall.
- **Note:** Follow the exact steps from video, even installed versions should be same as in video to avoid any configuration issues. Obviously this is for those who will implement SysCall by following above video only.

## Conclusion

The **Frozen Dessert Facility Simulation System** effectively bridges the gap between theoretical operating system concepts and their practical applications in a real-world scenario. 

By simulating the operations of an ice cream shop, this project provides:

- **Hands-on Understanding:** How operating system principles can be utilized to optimize business processes.
- **Enhanced Customer Satisfaction:** Demonstrating the impact of system efficiency on user experience.
- **Practical Application:** A real-world example of managing concurrency, preventing race conditions, and ensuring resource synchronization.

 
