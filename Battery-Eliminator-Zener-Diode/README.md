# 🔋 Battery Eliminator Using Zener Diode

A hardware project designed to provide a regulated DC supply using a Zener diode, eliminating the need for disposable batteries in low-power electronic devices like multimeters.


## 📷 Circuit Diagram

*Simulated using an AC input of 230V, stepped down to 9V with a transformer, followed by rectification and voltage regulation using a Zener diode.*


## 🎯 Objective

To develop a stable and cost-effective DC power source using a Zener diode-based voltage regulator circuit. This setup can be used as a battery eliminator in applications like digital multimeters and other small electronics.


## 🧰 Components Used

| Component             | Specification         | Quantity     |
|-----------------------|------------------------|--------------|
| Breadboard            | Standard               | 1            |
| PCB                   | General-purpose        | 1            |
| Zener Diode           | 5V                     | 1            |
| Transformer           | 9-0-9 V AC             | 1            |
| PN Diode              | IN4007                 | 4            |
| Capacitor             | 100µF, 25V             | 1            |
| Resistor              | 1kΩ                    | 2            |
| Connecting Wires      | As required            | –            |
| Multimeter            | For testing            | 1            |


## ⚙️ Working Principle

- The transformer steps down the 230V AC mains to 9V AC.
- A bridge rectifier (made of 4 PN diodes) converts AC to pulsating DC.
- A 100µF capacitor smooths the ripple from rectification.
- The Zener diode regulates the voltage to approximately 5V.
- Final output is filtered and tested with a multimeter showing a stable 5.7V DC.


## 📝 Features

- Eliminates the need for batteries in multimeters
- Stable DC output with simple components
- Compact and low-cost solution for lab or personal use

## 📁 Repository Structure

battery-eliminator-zener-diode/
├── README.md
├── circuit-diagram/
│ └── battery-eliminator-circuit.jpg
├── calculations/
│ └── zener-diode-analysis.pdf
├── report/
│ └── battery-eliminator-report.pdf
├── BOM/
│ └── components-list.csv


## 🧑‍🤝‍🧑 Team Members

- <PRIYADHARSHINI K> – Circuit design, testing, documentation
- <Teammate 2> – Simulation and report
- <Teammate 3> – Component sourcing, assembly


## 📜 License

This project is licensed under the [MIT License](LICENSE).


## 🙏 Acknowledgments

Thanks to our faculty guide and <SSN College of Engineering> for support and lab access.
