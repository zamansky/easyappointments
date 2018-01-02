---
title: Changelog of Easy!Appointments v1.3.0
author: Alex Tselegidis
categories:
  - Announcements
tags:
  - Development
  - Changelog
date: 2018-01-02 14:41:59
---

After months of development the new release is coming closer and closer to completion. Here's the changes that are introduced into the new release taken directly from the [CHANGELOG.md](https://github.com/alextselegidis/easyappointments/blob/1.3.0-alpha.1/CHANGELOG.md) file. 

## [1.3.0]

### Added 

- [#65](https://github.com/alextselegidis/easyappointments/issues/65): Insert new appointment by clicking directly on the calendar.
- [#122](https://github.com/alextselegidis/easyappointments/issues/122): Add customer email and phone number in the event popover of the backend/calendar page.
- [#152](https://github.com/alextselegidis/easyappointments/issues/152): Add support for American Time Format (AM/PM).
- [#176](https://github.com/alextselegidis/easyappointments/issues/176): Add Docker container for Easy!Appointments development.
- [#362](https://github.com/alextselegidis/easyappointments/issues/362): Add Arabic language translation.
- [#395](https://github.com/alextselegidis/easyappointments/issues/395): Add aggregates GET parameter in the appointments REST API resource.

### Changed 

- [#276](https://github.com/alextselegidis/easyappointments/issues/276): Update FullCalendar dependency.
- [#394](https://github.com/alextselegidis/easyappointments/issues/394): Corrections in the Bootstrap classes in view files.

### Fixed

- [#155](https://github.com/alextselegidis/easyappointments/issues/155): Appointment management modal is not updated after appointment duration resize.
- [#236](https://github.com/alextselegidis/easyappointments/issues/236): Duplicate availabilities with short service duration and unavailabilities ignorance. 
- [#315](https://github.com/alextselegidis/easyappointments/issues/315): Calendar doesn't update when Attendants number changes. 
- [#334](https://github.com/alextselegidis/easyappointments/issues/334): Use of session_start() function may cause issues as the default options are not being used.
- [#336](https://github.com/alextselegidis/easyappointments/issues/336): Deleting provider doesn't work in some languages.
- [#337](https://github.com/alextselegidis/easyappointments/issues/337): Full day appointment with multiple attendants are not being taken into concern during availabilities generation.
- [#342](https://github.com/alextselegidis/easyappointments/issues/342): Email notifications must honor the date format value.
- [#370](https://github.com/alextselegidis/easyappointments/issues/370): AJAX Error: SyntaxError: Unexpected token < in JSON at position 0

### Deprecated

- The availabilities generation and AJAX endpoints will change with a future release.