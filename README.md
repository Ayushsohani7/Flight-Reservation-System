# ✈️ Flight Ticket Reservation System

A console-based backend flight reservation system written in **C**. This project replaces standard, memory-heavy arrays with a **Doubly Linked List (DLL)** to dynamically manage passenger bookings in real-time. 

By utilizing dynamic memory allocation, the system scales infinitely and reclaims memory instantly upon ticket cancellations.

## 🚀 Key Features

* **Dynamic Booking (Insertion):** Allocates memory on the fly (`malloc`) for new passengers instead of relying on fixed quotas.
* **Auto-Generated IDs:** Securely assigns a unique, randomized 4-digit Ticket ID to every new booking.
* **Seamless Cancellations (Deletion):** Uses bidirectional pointers to safely bypass and remove canceled nodes (`free`) without breaking the active reservation chain.
* **Targeted Searching:** Instantly retrieve and display specific passenger and flight details using a unique Ticket ID.
* **Live Manifest:** View a complete, cleanly formatted table of all active reservations.

## 🧠 Technical Architecture

* **Language:** C
* **Data Structure:** Doubly Linked List (DLL)
* **Core Concepts:** Pointers, `struct` & `typedef`, Dynamic Memory Allocation (`malloc`/`free`), Random Number Generation (`rand`/`srand`).

## 🛠️ How to Compile and Run

If you have a C compiler (like GCC) installed, you can run this project locally:

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/flight-reservation-system.git](https://github.com/yourusername/flight-reservation-system.git)# Flight-Reservation-System
