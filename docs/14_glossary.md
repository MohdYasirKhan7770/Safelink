# SafeLink Glossary

**Document Version:** 1.0  
**Status:** Draft  
**Last Updated:** July 2026

---

# Purpose

This glossary explains important technical, product, and emergency communication terms used throughout the SafeLink project.

The glossary helps team members, developers, researchers, designers, and future contributors understand the same terminology.

---

# A

## API

**Application Programming Interface**

An API is a set of rules that allows different software applications or services to communicate with each other.

In SafeLink, APIs may allow the mobile application, backend, and dashboards to exchange information.

---

## Authentication

The process of verifying the identity of a user.

Examples include:

- Password login
- One-time verification code
- Biometric authentication

---

## Authorization

The process of determining what an authenticated user is allowed to access or do.

For example, a normal user and an authorized administrator may have different permissions.

---

# B

## Backend

The server-side part of an application that manages data, business logic, authentication, and communication between different system components.

In SafeLink, the backend may process emergency alerts and provide services to dashboards.

---

## Beacon

A small communication device installed at a fixed location.

A future SafeLink beacon may receive or relay emergency alerts in areas with poor or unavailable mobile network coverage.

---

## Bluetooth

A short-range wireless communication technology used to exchange information between nearby devices.

SafeLink may research Bluetooth as an additional method for relaying emergency alerts.

---

## Bluetooth Low Energy (BLE)

A low-power version of Bluetooth designed for devices that need to conserve battery.

BLE may be useful for future SafeLink wearables and low-power emergency devices.

---

## Bluetooth Mesh

A communication system in which multiple Bluetooth devices can help relay messages across a larger area.

Its real-world reliability and suitability for emergency communication must be researched and tested.

---

# C

## Cloud

Remote computing infrastructure used to store data, run applications, and provide online services.

SafeLink may use cloud services for backend systems, dashboards, notifications, and data synchronization.

---

## Communication Engine

The SafeLink component responsible for selecting and managing available communication methods.

It may use:

- Internet
- SMS
- Bluetooth
- Wi-Fi Direct
- Future LoRa infrastructure

---

## Connectivity

The ability of a device to communicate with another device, service, or network.

Connectivity may be provided through mobile networks, Wi-Fi, Bluetooth, or other communication technologies.

---

# D

## Dashboard

A web-based interface used to view and manage information.

Future SafeLink dashboards may support:

- Emergency alerts
- Latest available locations
- Alert history
- User management
- Relay beacon monitoring

---

## Data Encryption

The process of converting information into a protected form so that unauthorized users cannot easily read it.

SafeLink may use encryption to protect sensitive information such as emergency records and location data.

---

## Database

An organized system used to store and manage information.

SafeLink may use databases to store user information, emergency contacts, alerts, and emergency history.

---

## Delay-Tolerant Networking

A communication approach designed for situations where a continuous connection is not available.

Messages may be stored temporarily and forwarded when a communication path becomes available.

This concept may be relevant to future SafeLink offline communication research.

---

# E

## Emergency Alert

A message created when a user activates SOS or another emergency feature.

An emergency alert may include:

- Time of activation
- Latest available location
- Alert status
- Selected emergency contacts
- Relevant emergency information

---

## Emergency Contact

A trusted person selected by the user to receive emergency information or alerts.

---

## Emergency Evidence

Information recorded during an emergency.

Possible evidence may include:

- Audio recordings
- Images
- Videos
- Location records
- Emergency timestamps

---

## Emergency Mode

A special operating state activated after an SOS event.

Emergency mode may prioritize:

- Location capture
- Alert generation
- Communication attempts
- Evidence recording
- Emergency notifications

---

# F

## FastAPI

A Python framework used to develop web APIs.

FastAPI is planned as a possible backend framework for SafeLink.

---

## Functional Requirement

A requirement describing what a system must do.

Example:

> The application shall allow users to add emergency contacts.

---

# G

## Gateway

A system that connects one network or communication method to another.

A future SafeLink gateway may receive emergency messages from relay beacons and forward them to cloud services or authorized dashboards.

---

## Gateway Station

A physical SafeLink infrastructure unit that may connect offline communication networks with internet, mobile, or other wider communication networks.

---

## GPS

**Global Positioning System**

A satellite-based system that helps a device determine its location.

GPS does not require mobile data or internet to calculate a location. However, a separate communication method is required to send the location to another person or service.

---

## GPS Coordinates

Numerical values representing a geographic location.

Coordinates usually include:

- Latitude
- Longitude

---

# I

## Internet

A global network that allows devices and services to communicate online.

SafeLink may use internet connectivity as one of several communication methods.

---

## IoT

**Internet of Things**

A network of connected physical devices that collect, send, or receive information.

Future SafeLink relay beacons, wearables, and sensors may be considered IoT devices.

---

# J

## Jetpack Compose

A modern Android user-interface toolkit used to build application screens with Kotlin.

Jetpack Compose is planned for the SafeLink Android application.

---

# L

## Leaflet

An open-source JavaScript library used to create interactive maps.

Future SafeLink dashboards may use Leaflet to display emergency locations.

---

## Local Database

A database stored directly on a user's device.

SafeLink may use local storage to keep emergency alerts and other important information available when the device is offline.

---

## LoRa

**Long Range**

A low-power wireless communication technology designed to send small amounts of data over long distances.

Future SafeLink infrastructure may research LoRa for relay beacons and emergency communication.

LoRa is not the same as a complete internet connection. It is a communication technology with limitations related to data size, range, regulations, and network design.

---

## LoRaWAN

**Long Range Wide Area Network**

A networking protocol commonly used with LoRa devices.

It provides a structured method for managing communication between LoRa devices and gateways.

---

# M

## Mesh Network

A network in which devices may help forward messages between one another.

A future SafeLink mesh network could allow emergency information to travel through nearby devices or infrastructure.

The effectiveness of a mesh network depends on factors such as device availability, range, power, and network density.

---

## Mobile Network

A cellular communication network used by smartphones for calls, SMS, and mobile data.

Examples include 4G and 5G networks.

---

# N

## Non-Functional Requirement

A requirement describing how a system should perform.

Examples include:

- Reliability
- Security
- Performance
- Scalability
- Accessibility

---

## Notification

A message displayed or delivered to inform a user about an event.

SafeLink may use notifications to provide emergency updates and alert-status information.

---

# O

## Offline-First

A design approach in which an application continues providing important functionality even when internet connectivity is unavailable.

For SafeLink, offline-first means that emergency information can be captured and stored locally while the system searches for a communication path.

Offline-first does not guarantee that an emergency alert can be delivered without any available communication method.

---

## OpenStreetMap

An open geographic database used for maps and location-based applications.

SafeLink may use OpenStreetMap data in future dashboards.

---

# P

## PostgreSQL

An open-source relational database system.

PostgreSQL is planned as a possible main database for the SafeLink backend.

---

## Privacy by Design

An approach in which privacy protection is included from the beginning of product design rather than added later.

---

# R

## Relay

The process of receiving a message and forwarding it to another device, network, or system.

---

## Relay Beacon

A future SafeLink infrastructure device designed to receive and forward emergency information.

A relay beacon may use technologies such as Bluetooth, Wi-Fi, LoRa, or other communication methods.

---

## Retry System

A system that attempts to send a failed message again.

SafeLink may use retries when an emergency alert cannot be delivered immediately.

---

## Room Database

An Android library that helps applications store and manage structured information locally on a device.

SafeLink may use Room for offline emergency data storage.

---

# S

## Scalability

The ability of a system to handle increasing numbers of users, devices, alerts, or services without major performance problems.

---

## SMS

**Short Message Service**

A mobile-network service used to send text messages.

SMS normally requires access to a cellular network.

---

## SOS

An internationally recognized emergency distress signal.

In SafeLink, SOS refers to the emergency action used to start the emergency workflow.

---

## SOS Engine

The SafeLink component responsible for managing the emergency workflow after SOS activation.

Possible responsibilities include:

- Capturing location
- Creating an emergency alert
- Starting emergency recording
- Saving data locally
- Starting communication attempts

---

## Smart City

A city that uses digital technology and connected infrastructure to improve public services, transportation, safety, energy, and other systems.

Future SafeLink infrastructure may explore smart-city integration.

---

## System Architecture

The high-level structure of a system and the way its components interact.

---

# U

## User Interface (UI)

The screens, buttons, text, controls, and visual elements through which a user interacts with an application.

---

## User Experience (UX)

The overall experience of using a product, including usability, accessibility, speed, clarity, and ease of completing tasks.

---

# W

## Wi-Fi

A wireless technology that allows devices to communicate through local networks and internet connections.

---

## Wi-Fi Direct

A technology that allows compatible devices to communicate directly without requiring a traditional Wi-Fi router.

SafeLink may research Wi-Fi Direct as a possible offline communication method.

---

## WorkManager

An Android component used to schedule reliable background tasks.

SafeLink may use WorkManager for tasks such as retrying pending alerts when appropriate.

---

# SafeLink-Specific Terms

## Alert Status

The current state of an emergency alert.

Possible statuses include:

- Created
- Saved Locally
- Queued
- Transmission Attempted
- Sent
- Delivery Confirmed
- Failed
- Cancelled

---

## Communication Path

A method through which an emergency alert can travel from the user's device to another device, service, or responder.

Examples include:

- Internet
- SMS
- Bluetooth
- Wi-Fi Direct
- LoRa infrastructure

---

## Emergency Communication Ecosystem

The complete group of technologies and systems used by SafeLink to support emergency communication.

Possible components include:

- Mobile applications
- Wearable devices
- Relay beacons
- Gateway stations
- Cloud services
- Emergency dashboards

---

## Zero-Network Zone

An area where conventional communication services, such as mobile network coverage or internet access, are unavailable or unreliable.

A zero-network zone may still have other possible communication paths, such as nearby devices or dedicated relay infrastructure.

---

# Closing Statement

This glossary should be updated whenever new technologies, product concepts, or technical terms are introduced into SafeLink.

Clear terminology helps the SafeLink team communicate accurately and make better technical decisions.

> **A shared understanding is the foundation of a strong system.**
