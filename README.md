# Ride Management System

A C++ console-based application for managing ride and delivery bookings using OOP principles. It demonstrates file handling and object-oriented design with classes for Customers, Drivers, Vehicles, Services, Rides, and Deliveries.

## Features

- Register, view, and manage Customers, Drivers, Vehicles.
- Book or cancel Rides and Deliveries.
- Service history tracking.
- File-based persistent storage (text files for customers, vehicles, drivers, services).
- Various queries (drivers above 4.5 rating, drivers with multiple licenses, etc.)

## Files

- **Source.cpp:** Main C++ code using OOP classes.
- **customers.txt:** Customer data.
- **driver.txt:** Driver information.
- **Services.txt:** Bookings, service history for rides and deliveries.
- **vehicles.txt:** Vehicle info such as registration, type, features.

## Compile & Run

Windows OS required (uses `<windows.h>`).

```
 g++ Source.cpp -o ride_management.exe
 ride_management.exe
```
(Or use any C++ compiler supporting Standard Library)

## Example

On startup, the app loads data from text files. Use main menu to add users, manage rides/services, or generate reports.

## Author

- AnsCheema36

## License

MIT License (see LICENSE file).