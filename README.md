# Dropzone delivery app
This is an on-demand courier service built using Javascript and [What3Words](https://what3words.com/).

## Why?
I built this app because many people in my area do not have home adresses that they can use to receive deliveries.
What3Words is able to solve this problem by providing a 3 word combination that corresponds to a 3 * 3 metre square of any point on the earth's surface, e.g. [crashing.mops.seriously](https://what3words.com/crashing.mops.seriously).
This means that any user could have a unique 3-word address that corresponds to their home/office coordinates.
This makes it easier for the user to send and receive packages.

## How it works
* The merchant registers an account or signs in to an existing account.
* Once signed in, the merchant sets up their what3words address then uploads a photo of the item they would like to send and the mobile number of the recepient.
* This photo is then to the recepient in a link via SMS.
* Once the recepient clicks on the link, they can set their address using what3words and accept the delivery charges.
* The delivery request is then dispatched to the motorcycle courier who is nearest to the merchant.
* The courier accepts the request and receives pick-up and drop-off addresses.
* The merchant is notified that the courier is on the way to pick up the delivery.
* Once the delivery is collected, the recipient is notified that their package is en-route.
* When the delivery is completed, the courier gets paid by the recepient and the merchant is notified that the delivery was successful.

# Languages
* JavaScript
* HTML
* CSS
