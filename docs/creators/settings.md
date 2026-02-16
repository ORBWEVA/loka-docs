---
sidebar_position: 4
title: Platform Settings
description: "Configure your Loka Creator school — branding, booking page, services, payment settings, calendar integration, and notifications."
---

# Platform Settings

As a Loka Creator, you can configure your school's settings to match your business needs. Access all settings from **Admin Panel > Settings**.

## System Settings

### Timezone

Set your school's default timezone. This affects:

- How available time slots are displayed to learners
- Default timezone for new user accounts
- Scheduling and reminder calculations

Individual users can override this with their own timezone in their account settings.

### Currency

Choose the currency used for pricing and invoices. Loka supports major currencies through Stripe. Once set, all pricing displayed to your learners will use this currency.

### Booking Rules

Configure how learners book lessons at your school:

- **Minimum advance booking** -- how far in advance a lesson must be booked (e.g., 24 hours).
- **Maximum booking window** -- how far into the future learners can book (e.g., 2 weeks, 1 month).
- **Cancellation policy** -- the cutoff time for free cancellations and what happens with late cancellations.
- **Booking limits** -- the maximum number of active bookings a learner can hold at once.
- **Lesson duration options** -- the lesson lengths you offer (e.g., 25 min, 50 min, 80 min).

## Integrations

Loka connects with several third-party services to extend your school's capabilities.

### Stripe

Stripe handles all payment processing for Loka. Your Stripe connection is set up during onboarding.

- View connection status in **Settings > Integrations > Stripe**
- Manage your Stripe account directly from the Stripe dashboard
- Webhook events are handled automatically (lesson payments, seat renewals, cancellations)

### Zoom

Connect Zoom to automatically generate meeting links for online lessons.

- Go to **Settings > Integrations > Zoom**
- Authorize your Zoom account
- Once connected, booking an online lesson automatically creates a Zoom meeting and includes the join link in the confirmation email

### Asana

Connect Asana to manage tasks and projects related to your school operations.

- Go to **Settings > Integrations > Asana**
- Authorize your Asana account
- Link Loka tasks to Asana projects for team coordination

## Email Configuration

Customize the emails your school sends to educators and learners.

### Email Templates

Loka provides default email templates for common events:

- Welcome / invitation emails
- Booking confirmations and reminders
- Lesson summary notifications
- Password reset emails

You can customize the content of these templates from **Settings > Emails**. Brand-specific elements like your school name and logo are automatically included.

### Sender Settings

Configure the sender name and reply-to address for outgoing emails so they appear to come from your school rather than from Loka directly.

## School Branding

Customize how Loka appears to your educators and learners:

- **School name** -- displayed throughout the platform and in emails.
- **Logo** -- upload your school's logo to appear in the navigation bar and emails.

:::tip
Adding your school name and logo helps build trust with your learners and reinforces your school's identity.
:::
