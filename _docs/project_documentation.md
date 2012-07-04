<h1>Circadia documentation</h1>

<h2>What is Circadia?</h2>
<p>
    Circadia is a "humanitarian" app aimed at improving the lesser known areas of the city of Ghent by generating data for city management, which they can use to see which areas are the most popular, and which areas need more attention.
</p>
<p>
    Users can check into pre-defined events, which will earn them points (provided they actually stay there and attend the event). These points are tallied up into a leaderboard, which will provide a competitive feel to the users who utilize the app. A possibility would be to give culture cheques, provided by the city of Ghent, to the top users in order to motivate people even further. Obviously, this is just an idea so far.
</p>
<p>
    This means that our application has two main sides to it: on the one hand, we have the Circadia "game" for the users, in which they compete for getting the most points (and hopefully rewards). On the other hand, we provide the anonymous data to the city of Ghent which they can use to make decisions regarding culture development in the city.
</p>

<h2>Main features of the app</h2>
<ul>
    <li>Check-in system for the events</li>
    <li>Leaderboard to see how users compete against eachother</li>
    <li>"Heatmap" to see where all the popular locations are: less popular locations = more points</li>
</ul>

<h2>Default app flow</h2>
<h3>Check for events</h3>
The user checks for events that are going on in Ghent, after making a choice he/she gets a route to the location.

<h3>Go to location</h3>
By using the route, the user goes to the location (hopefully on time!).

<h3>Check in at event</h3>
After arriving at the event, the user checks in at the location

<h3>Attend event</h3>
The user attends the event -- no interaction is needed for this step

<h3>Check out</h3>
Checking out of the event makes sure we have a timestamp for entrance and exit: this means that users have to stay a certain amount of time in order to receive points (to avoid cheating the leaderboards)

<h3>Receive points</h3>
Points are tallied up and added to the account. Leaderboards are updated