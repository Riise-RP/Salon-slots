# Salon Slots

### Book your slot. Skip the waiting.

Salon Slots is a simple appointment-booking system designed to help independent
hairstylists manage their schedules while helping customers avoid unnecessary waiting.

## The Problem

I was at a salon from 8 AM to 8 PM waiting to get my hair braided.

I had called the stylist beforehand and told her I would come at 8 AM. When I arrived,
there were already three people waiting, and the stylist was still preparing the salon.

I ended up being the fourth person in line and spent the entire day waiting.

While I was sitting there, I started thinking:

*What if customers could simply choose a time slot before coming to the salon?*

That experience became the inspiration for Salon Slots.

## The Solution

Salon Slots turns the traditional "arrive and wait" experience into a simple
appointment system.

Customers can view available time slots, choose a suitable appointment, and provide
their name, phone number, and hairstyle. Once the booking is made, that slot becomes
unavailable to other customers.

The stylist has a dedicated dashboard where they can view upcoming bookings,
see customer details, manage their availability, and block times when they are
unavailable or already busy.

When a new booking is made, the stylist also receives an email notification.

Because bookings and availability are stored online, information can be shared
across different devices using the same Salon Slots website.

## Features

- Customer appointment booking
- Available and booked time slots
- Hairstyle selection
- Customer name and phone number
- Stylist dashboard
- Stylist availability management
- Block unavailable or busy slots
- Shared bookings across devices
- Booking lookup using a phone number
- Email notifications for new bookings
- Automatic daily closing at 6 PM
- Past dates are automatically blocked
- Customers cannot book past or closed dates

## How It Works

1. Customer chooses an available time slot.
2. Customer enters their name, phone number, and hairstyle.
3. The booking is stored online.
4. The selected slot becomes unavailable to other customers.
5. The stylist receives an email notification.
6. The stylist can view bookings and manage their availability.
7. Past dates are automatically unavailable.
8. Each day's remaining booking slots automatically close at 6 PM.

## What Makes Salon Slots Different?

Salon Slots isn't designed as a large, complicated salon-management platform.

It focuses on a simple problem:

*Helping independent stylists and their customers manage time better.*

The idea came directly from experiencing the problem myself. Instead of customers
arriving without knowing how long they will wait, they can see available slots
and choose when they want to come.

At the same time, the stylist gets a simple way to control their availability,
see who is coming, and manage bookings from one place.

I also wanted the system to work across different devices. A booking made by a
customer should affect what another customer sees rather than being information
stored only on one phone.

*The goal isn't to make salon booking complicated. It's to make waiting unnecessary.*

## Built With

- React
- JavaScript
- CSS
- Supabase
- Web3Forms
- Netlify
- Claude

## Challenges & What I Learned

One of the biggest challenges was turning the original prototype into a real,
standalone web application.

My first version was built as a Claude Artifact, but I discovered that external
services such as email notifications could not work properly inside that environment.

I had to move the application to a standalone website, connect it to Supabase for
shared data, configure email notifications, and deploy it through Netlify.

I also tested the application across multiple devices to make sure bookings and
blocked slots were synchronized between devices.

This taught me that building an application isn't only about creating the interface.
You also have to think about how data is stored, how different devices communicate,
and how the application works in the real world.

## Future Plans

Salon Slots is currently a working MVP, but I see several ways it could grow.

In the future, I would like to:

- Make the system easier for small salons to set up themselves.
- Add customer booking confirmations and reminders.
- Allow stylists to manage different services and the amount of time each hairstyle takes.
- Add cancellation and rescheduling.
- Improve the system for areas where customers may have limited internet or mobile data.
- Eventually allow multiple independent stylists to use Salon Slots, each with their
  own salon profile and dashboard.

The long-term goal is to make appointment booking practical for small salons and
independent stylists who may not need or want a complicated booking platform.

## Live Demo

https://comforting-chaja-7abf6d.netlify.app

## Inspiration

Salon Slots was inspired by a real experience of spending an entire day waiting
at a salon.

The goal is simple:

**Book your slot. Skip
