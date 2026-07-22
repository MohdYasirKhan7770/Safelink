# System Requirements

**Document Version:** 1.0  
**Status:** Draft  
**Last Updated:** July 2026

---

# Purpose

This document defines the functional and non-functional requirements of the SafeLink platform. These requirements will guide the design, development, testing, and future expansion of the system.

---

# Functional Requirements

## User Management

The system shall allow users to:

- Create an account
- Log in securely
- Reset passwords
- Manage profile information
- Delete their account

---

## Emergency Contacts

The system shall allow users to:

- Add emergency contacts
- Edit emergency contacts
- Remove emergency contacts
- Assign priority contacts

---

## SOS System

The system shall:

- Allow one-tap SOS activation
- Display a countdown before sending (optional)
- Cancel accidental activation
- Trigger emergency mode

---

## GPS & Location

The system shall:

- Retrieve GPS coordinates
- Store location offline
- Update location periodically
- Share the latest available location

---

## Emergency Evidence

The system shall:

- Record audio
- Record video (future)
- Capture images (future)
- Store evidence securely
- Encrypt emergency evidence

---

## Communication

The system shall support:

- Internet
- SMS
- Bluetooth Relay
- Wi-Fi Direct
- Future LoRa Communication

---

## Offline Mode

The system shall:

- Continue functioning without internet
- Store pending alerts
- Retry automatically
- Synchronize when connectivity returns

---

## Notification System

The platform shall notify:

- Emergency contacts
- Future emergency dashboard
- Future responders

---

## History

The system shall:

- Maintain emergency history
- Store previous alerts
- Allow users to review records

---

# Non-Functional Requirements

## Reliability

The platform should remain operational even during poor network conditions.

---

## Availability

Critical emergency features should remain accessible 24/7.

---

## Performance

- Fast SOS activation
- Low latency
- Minimal loading time

---

## Security

The platform should:

- Encrypt sensitive data
- Protect communication
- Prevent unauthorized access

---

## Privacy

SafeLink shall:

- Collect only necessary data
- Give users control over their information
- Never sell personal data

---

## Battery Efficiency

The application should minimize battery consumption while maintaining emergency readiness.

---

## Scalability

The architecture should support growth from individual users to city-wide deployments.

---

## Accessibility

The application should:

- Support large touch targets
- Use readable typography
- Provide intuitive navigation

---

## Maintainability

The platform should use modular architecture to simplify updates and future development.

---

# Assumptions

- Users possess GPS-enabled smartphones.
- GPS may remain available even when internet is unavailable.
- Users grant required permissions.

---

# Constraints

- GPS accuracy depends on environmental conditions.
- Offline communication options have limited range.
- Hardware infrastructure (relay beacons) will be introduced in future phases.

---

# Success Criteria

The system should successfully:

- Allow users to activate SOS quickly.
- Preserve emergency evidence securely.
- Maximize the probability of delivering emergency alerts.
- Continue functioning during network outages.

---

> "Every requirement exists to improve the probability of saving a life."
