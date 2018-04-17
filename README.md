# Year of the Monkey Countdown

There's a lot of fancy animation in the CSS and JavaScript, but the main bread-and-butter of this code is the countdown.

On page load, the JavaScript gets the current date and the date of Chinese New Year, then calculates the number of seconds there are remaining from the current date to Chinese New Year. From there, the seconds are boken down into days, hours and minutes and the time display created accordingly.

After that, a timer is invoked, with the number of seconds decrementing with each passing second. Again, the time display is updated accordingly.

Once the number of seconds reaches zero, the animation starts.
