# RSVPED (Web)

- Host can create a password protected event
- Host can send invitation to invitee to RSVP
- Invitee can "login" (temp access) to event using their email (send code)
- Invitee can see/add notes

## Event

- Host can see list of events they've created
- Host can create new event
    - Title
    - Description
    - Start date/time
    - End date/time
    - All day?
    - Max invitees
    - Additional links (multiple) for more info
    - Password (salt)
    - Allowlist (emails/phone numbers, multiple)
    - Questionnaire
        - Polls (options, completed, expiry date)
    - Publish (option: send emails to invitees)

## RSVP

- Insert email
    - If user is on invite list, receive access code
    - Else, tell them they are not invited
- Click Yes, Maybe, No (remove from event's allowlist)
- Answer poll
- Answer question

## Create account