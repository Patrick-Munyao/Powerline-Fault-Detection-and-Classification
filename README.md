# Powerline-Fault-Detection-and-Classification
**Specifying the question**

Electrical Fault Definition: Fault in electrical equipment or apparatus is defined as an imperfection in the electrical circuit due to which current is deflected from the intended path. In other words, fault is the abnormal condition of the electrical system which damages the electrical equipment and disturbs the normal flow of the electric current.


**Types of Electrical Fault**


There are two main types of electric fault:


**Symmetrical** - Symmetrical fault is one that affects each of the phases equally. Its occurence is rare and 5% of transmission-line faults are symmetrical.

**Asymmetrical**- Here, all the three phases are not affected equally unlike in symmetrical faults. Common types of asymmetric faults and their causes:


1. Single Phase to Ground Fault – It is also called a line-to-ground fault. It mainly occurs due to insulation breakdown between one of the phases and earth. Their chances of appearance in the power system are 70%.

2. Phase-to-Phase Fault – Such type of fault rarely occurs on the power system. It is also called Line-to-line fault. It occurs when two conductors are short circuited. Their chance of appearance is hardly 15% in the power system.

3. Two Phases to Ground Fault – In this type of fault breakdowns of insulation between two phases and earth occur. It is the most severe type of fault but rarely occurs in the power system. It is also called Line-to-line-to-ground fault (L-L-G). Their chance of occurrence is hardly 10%.

4. Phase to phase and Third Phase to Ground Fault – It is the combination of phase to phase and phase to phase to ground fault. Such types of fault occur due to the breakdown of insulation between two phases and simultaneous breakdown of insulation between the third phase and earth. The chance of such a type of fault is hardly 2% to 3%.

5. All the Three Phases to Ground Fault – It is the most severe type of the fault and very rarely occurs in the power system. It occurs due to a breakdown of insulation between all the phases as well as to the earth. Its chance of occurence is 2% to 3% in the power system.

**Reason for faults**

Possible causes of powerline faults include:


* Insulation failure or breakdown
* Lighting
* Power surge
* Unbalance current or voltage
* Stability fall
* Mechanical fault in transmission line
* Over voltage
* Temperature rise

**Study Objectives**

The objective of our study is to build a supervised machine learning model that can be used to classify and predict all the signals in most efficient manner in incases where there is actually fault in the system.


The machine learning models employed include:

1. Linear regression

2. Logistic regression

3. Decision trees

4. Random forest

5. Support Vector Machine

6. KNN

7. Naive bayes

8. Multi layer perceptron

**Defining Metrics of Success**

This study is based on electric power fault. Considering the huge costs and other damages related with power faults, acquisition of precise results is of great importance. Misclassification could lead to frequent power faults and blackouts resulting in endless outcry among consumers. These power interruptions occur during the distribution of power from the generation end to user premises, affecting the system reliability and increasing the fault line restoration costs.

This study will only be considered successful if the following is achieved:

Train numerous supervised models with relevant data for performance comparison. Model to be preferred for deployment should have an accuracy score of at least 99%. In addition, the model should be simple to understand (and non complex in structure), easy to train and implement, and have a good computational power.

**Definition of terminologies**

**Voltage** is the potential difference between two points in an electric field, which causes current to flow in the circuit. The SI unit for voltage is Volts and denoted as V. Voltage is the cause of the current. V= Work done/Charge

**Current** is the rate of flow of electrons/rate at which electric charge flows in a circuit at a particular point. Current's SI unit is Ampere (A) and current is denoted as I. Current is the effect of the voltage i.e. current cannot flow without voltage. I= Charge/ Time The current flowing in a circuit is directly proportional to the applied voltage and inversely proportional to the resistance of the circuit, provided the temperature remains constant (Ohm's Law). As such, Current (I = V/R)

**A 3-phase power supply system** is a three-wire ac power circuit with each phase ac signal 120 electrical degrees apart. It is a common method of alternating current electric power generation, transmission, and distribution. It is a type of polyphase system and is the most common method used by electrical grids worldwide to transfer power. It is also used to power large motors and other heavy loads.

**Experimental Design**

The following steps wil be taken in this study:

1. Importing libraries and loading datasets
2. Checking the dataset and the components
3. Checking for possible anomalies in the dataset
4. Conducting necessary data preparation procedures
5. Conducting Exploratory Data Analysis and documenting the findings
6. Building a baseline model that we will use to compare our models to
7. Building and optimizing seven supervised machine learning models.

**Contributors**

* Patrick Munyao
* Hazra Kerubo
* Jesse Mogere
* Eunice Wataaru

