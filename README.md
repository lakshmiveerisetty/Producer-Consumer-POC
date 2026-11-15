# 🧵 Producer-Consumer – Java Multithreading POC

## 📌 Project Description
Producer-Consumer POC is a Java-based application that demonstrates multithreading and inter-thread communication using a shared resource. The Producer generates data, and the Consumer retrieves data from the shared resource. The application uses synchronization to coordinate both threads and avoid accessing the resource at the same time.

## 🛠️ Technologies Used
- ☕ Java
- 🧵 Multithreading
- 🔒 Synchronization
- 🔄 Inter-Thread Communication
- 💻 Object-Oriented Programming (OOP)

## ✨ Features
- 📤 Producer generates and puts data into the shared resource.
- 📥 Consumer retrieves data from the shared resource.
- 🔐 Uses synchronized methods for thread safety.
- ⏳ Uses `wait()` to make threads wait when the resource is unavailable.
- 🔔 Uses `notify()` to notify waiting threads.
- 🔄 Maintains communication between Producer and Consumer.
- 📊 Uses a shared Resource object to exchange data.

## 📚 Concepts Implemented
1. 🧵 **Multithreading:** Executes Producer and Consumer operations using separate threads.
2. 🔒 **Synchronization:** Controls access to the shared Resource object.
3. ⏸️ **wait():** Makes a thread wait until the required condition is satisfied.
4. 🔔 **notify():** Wakes up a waiting thread.
5. 🔄 **Shared Resource:** Both Producer and Consumer use the same Resource object.
6. ⏱️ **Thread.sleep():** Introduces delays between Producer and Consumer operations.
7. 🧩 **Runnable Interface:** Producer and Consumer implement the Runnable interface.

## ⚙️ Working
