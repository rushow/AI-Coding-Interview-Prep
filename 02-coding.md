# Coding

## Object-Oriented Programming (OOP)

### The big idea: think of a car 🚗

OOP (Object-Oriented Programming) organizes code around **objects** that hold both **data** and **actions**.

A car is an object:

- **Properties (data):** Color, Speed, Model
- **Actions (methods):** Start, Stop, Brake

| Term | Meaning | Car example |
| --- | --- | --- |
| **Class** | The blueprint | The car design |
| **Object** | An actual instance created from the class | A real car built from that design |

OOP rests on four pillars: Encapsulation, Abstraction, Inheritance and Polymorphism.

### Pillar 1: Encapsulation 🔒

**Definition:** Wrapping data and methods together while controlling access to them.

**Car example:** You can accelerate or brake, but you can't directly manipulate the engine's internal components.

**In code:** Private data is accessed only through controlled methods.

> 💡 **Remember:** Protect the data.

### Pillar 2: Abstraction 🎭

**Definition:** Showing only what's necessary and hiding internal complexity.

**Car example:** You press the accelerator and the car speeds up. You don't need to understand how the engine and transmission work internally.

> 💡 **Remember:** Show WHAT, hide HOW.

### Pillar 3: Inheritance 🧬

**Definition:** A child class reuses the features of a parent class.

**Car example:** `Car` has wheels, brakes and steering. `ElectricCar` inherits these features and adds a battery and charging.

**In code:** `ElectricCar extends Car`

> 💡 **Remember:** Reuse existing code.

### Pillar 4: Polymorphism 🔄

**Definition:** The same method, with different implementations.

**Car example:** Calling `car.start()`:

- ⛽ `PetrolCar` → starts the combustion engine
- ⚡ `ElectricCar` → activates the electric motor

Same method, different behavior.

> 💡 **Remember:** One interface, many forms.

### 🎯 Quick interview revision

| Pillar | One-line meaning | Car example |
| --- | --- | --- |
| 🔒 Encapsulation | Protect the data | Use the pedals, not the engine internals |
| 🎭 Abstraction | Hide complexity | Press accelerator → car goes faster |
| 🧬 Inheritance | Reuse code | `ElectricCar extends Car` |
| 🔄 Polymorphism | Different behaviors | `start()` works differently for petrol vs electric |

**One car. Four pillars. OOP simplified.** 🚗

---

[← Back to contents](README.md)
