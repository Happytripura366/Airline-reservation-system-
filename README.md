Airline Reservation System:
class Passenger {
    String name;
    String passportNumber;

    public Passenger(String name, String passportNumber) {
        this.name = name;
        this.passportNumber = passportNumber;
    }
}

class Reservation {
    String reservationId;
    Passenger passenger;
    Ticket ticket;

    public Reservation(String reservationId, Passenger passenger, Ticket ticket) {
        this.reservationId = reservationId;
        this.passenger = passenger;
        this.ticket = ticket;
    }

    public void bookTicket() {
        System.out.println("Ticket booked for " + passenger.name + " with ticket number " + ticket.ticketNumber);
    }
}

class Ticket {
    String ticketNumber;
    String flightNumber;
    double price;

    public Ticket(String ticketNumber, String flightNumber, double price) {
        this.ticketNumber = ticketNumber;
        this.flightNumber = flightNumber;
        this.price = price;
    }
}

class Employee {
    String employeeId;
    String role;

    public Employee(String employeeId, String role) {
        this.employeeId = employeeId;
        this.role = role;
    }
}# Airline-reservation-system-
