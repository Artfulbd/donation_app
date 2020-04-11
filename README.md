# donation_app
Donation for epidemic app(Covid-19)

1.	There will be two type of user. Donator and Receiver.
2.	Donator will donate, actually they are the actual app user.
3.	 Receiver will receive donation; they will not use the app but get donation on their respective account.

Details: 
1.	Donor: 
a.	They will create account from app’s home page. Using there Facebook account.
b.	We will take only user name from the Facebook App. Then additionally take payment account number (bkash, rocket or other payment app’s number) and a password. To keep it short and simple for user. This is sign up [1].
c.	During login user can use that phone number and password or use Facebook account to log in.
d.	After a successful log in a dashboard [2] appears.
e.	On dashboard they can –
•	See other collaborators [3].
•	Create [4] ‘receiver’ type user.
•	Review [5] ‘receiver’ type unregistered users.
•	Donate [6] to any ‘receiver’ user. 
•	See area status [7]
•	See ‘epidemic name’ status [8]
•	Contribute on epidemic status [9]


2.	Receiver: They don’t have any job here except receiving money. More specifically they are our targeted poor needy peoples. The only thing they can do is, open payment app account (like bkash, rocket etc.) and give their details directly or indirectly to ‘donor’ user. Get registered and receive donation.




** So this is the main Idea, now feature details is given billow.

1.	[1] Sign up: To register a donor account. To avoid further verification, Facebook API will be used to create a new account. Additionally, primary payment account number (mobile banking) will be needed with a password.
2.	[2] Log in: There will be two option for logging in. Facebook, or manual. For manual login, need to put payment account number and password. For Facebook login, only click a button that will validate from Facebook and logs in to dashboard.
3.	 Dashboard: It is primary landing page of this app. Everything(features) will be displayed here as a menu or content or progress bar.
4.	[3] Other collaborators: User can see other user, only name and contact number if that user make his or her number public, nothing else. Initially user will see their own area’s collaborators. To see other areas collaborators, they need to search for that area from dashboard and find them from there.
5.	Message: User can send message to other collaborators. Facebook Message API will be used here.
6.	[4] Create receiver user: Donor user will create new receiver user by entering their details manually, who belongs to his/her area only.
They need to enter the following details-
>Name: Receiver’s name.
>Phone number: Which is the mobile banking number too.
>Family member count: From one family one member will be registered, so the family member count is needed.
>Home-coordinate: This is optional, if possible GPS coordinate from google map will be used here. (google map API will be used)
>Previous donation status: Before registering to this app, if this receiver receives any kind of donation from anywhere, will be mentioned here, it will be a drop down menu. Yes, or no. If yes then a date item will appear, user will select date (approximately). If no, then nothing to give more. Press register button. 
Then it will be sent to all collaborator of that area. They will review [5] and validate that whenever they log in. 
7.	 [5] Review: On dashboard there will be a review menu. There user will review those receiver user, created by other donor users. User will check information and vote as approve or reject or correction. if 60% collaborator approves, then the receiver account will be registered to the system immediately. If anyone has any objection he/she will vote as disagree for that requested receiver user and wrote objection cause on objection box. Those causes will be sent to that donor user who creates it. He/she will correct it. Then again approve request will be sent to donor users (same area).
Only voting part will be done by user, but actual registration will be done by system (API) automatically, based on collaborators vote.
8.	[6] Donate: User will donate to any receiver user directly to receiver’s account. Here respective mobile banking API will be used. Who donated whom, this will not be tracked. Only tracked thing will be who received how much donation. There will be a target amount for an area. After a successful donation of a user, that amount will be added to that area’s total donation amount. Users will be encouraged to donate to their own area first, then donate to other areas receiver. 
9.	[7] Area status: Initially user can see their own area information here, at a glance. Like total donor/collaborator, total receiver, total donated count, how many to be donated, which receiver receives how much etc.
10.	[8] ‘Epidemic name’ status: In our case “Covid-19 status”. Areas corona status will display under this section.
11.	[9] Contribute on epidemic status: Here user can contribute on epidemic current status.
                                          By, Md. Ariful Haque
