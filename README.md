# Timesheet Management System

The Timesheet Management System is a Go-based web service designed to manage and track timesheets. It provides endpoints for creating, updating, retrieving, and deleting timesheets, as well as managing associated notes.

## Features

- **Create Timesheet**: Add a new timesheet for a user, specifying the login name, month, year, and associated details.
- **Update Timesheet**: Modify an existing timesheet by providing the login name, month, year, and updated details.
- **List of Timesheets**: Retrieve a list of timesheets for a specific user.
- **Get Timesheets By Week**: Retrieve timesheets for a user based on the week, month, and year.
- **Update Notes**: Add or update notes for a specific timesheet, providing login name, month, year, and note details.
- **Delete Timesheet**: Remove a timesheet record for a specific user, month, and year.

## Getting Started

**Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/timesheet-management-system.git
   cd timesheet-management-system

1. **Set Up Configuration:**

Copy the config.example.yaml file to config.yaml and adjust the configuration settings as needed.

2. **Build and Run:**
  go build
./timesheet-management-system


3.** API Endpoints:**

The service exposes RESTful API endpoints for timesheet management. Refer to the API documentation for details on each endpoint.
API Documentation
For detailed information on the available API endpoints and their usage, please refer to the API documentation.

**Dependencies**

Go-Chi: Lightweight, idiomatic, and composable router for building Go HTTP services.
Zerolog: Zero-allocation JSON logger library for Go.
Chi Cors: Go middleware that provides Cross-Origin Resource Sharing (CORS) support.
Config: Go configuration library for YAML configuration files.
Contributing
Contributions are welcome! If you have suggestions, improvements, or find any issues, please open an issue or submit a pull request.


# Keywords
Keywords: break , default , func , interface , select , case , defer , go , map , struct , chan , else , goto , package , switch , const , fallthrough , if , range , type , continue , for , import , return , var, else if .
# Data Types:
Number ->
Integers:  int8, int16, int32 and int64, uint8, uint16, uint32 and uint64
Float: float32 and float64
Complex: complex64 and complex128
Strings
Boolean - false & true
rune - same as int32 and byte - same as uint8
int,uint, uintptr

# Formatting by golang
------------------------------
d - decimal integer
o - octal integer
O - octal integer with 0o prefix
b - binary integer
x - hexadecimal integer lowercase
X - hexadecimal integer uppercase
f - decimal floating point, lowercase
F - decimal floating point, uppercase
c - a character represented by the corresponding Unicode code point
q - a quoted character
t - the word true or false
s - a string
v - default format
T - a Go-syntax representation of the type of the value



