
Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Navigate to MY OKULink App	App should open	As Expected	Pass	
2	Tap “Don't have an account? Sign Up”	Sign Up page is displayed	As Expected	Pass	
3	Enter name, existing email, password, and confirm password	User can input valid data	As Expected	Pass	
4	Tap “Sign Up” button	System displays "The email address is already in use by another account"	As Expected	Pass	
5	Enter name, existing email, password, and confirm password	User can input valid data	As Expected	Pass	
6	Tap “Sign Up” button	Registration Successful	As Expected	Pass	

Table 6.1: Register Page Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Navigate to MY OKULink App	App should open	As Expected	Pass	
2	Enter Email & Password	Credential can be entered	As Expected	Pass	
3	Click Login	User is redirected to Dashboard	As Expected	Pass	

Table 6.2: Login Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Navigate to MY OKULink App	App should open	As Expected	Pass	
2	Tap G icon	Google account popup appears	As Expected	Pass	
3	Select an account	Login successful, user enters Dashboard	As Expected	Pass	

Table 6.3: Google Sign-In Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Navigate to MY OKULink App	The app should open	As Expected	Pass	
2	Enter email address	No warning	As Expected	Pass	
3	Click Forgot Password	Password Reset Email sent	As Expected	Pass	
4	Click the Password reset link in the email	New password required	As Expected	Pass	

Table 6.4: Forgot Password Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Logged to MY OKULink	Dashboard loads	As Expected	Pass	
2	Check all main buttons visible	All icons and buttons displayed	As Expected	Pass	
3	Observe Dashboard Elements	Search bar, category cards, dropdown filter are displayed	As Expected	Pass	

Table 6.5: Dashboard Page Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Enter keyword in search bar	Keyword appears in text field	As Expected	Pass	
2	Tap search icon	Relevant results are displayed in list	As Expected	Pass	

Table 6.6: Search Information from Dashboard Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap any category card (eg: Government Aid)	App navigates to corresponding information list page	As Expected	Pass	
2	Observe list page	Page shows information related to the selected category	As Expected	Pass	

Table 6.7: Navigate to Information List Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Open dropdown menu	All categories appear	As Expected	Pass	
2	Select Category, PWD Type and Region	Dropdown list has multiple choices	As Expected	Pass	
3	Click Search Button	Relevant results are displayed in list	As Expected	Pass	

Table 6.8: Dropdown Filter Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap any information item from the list	Information Details page loads	As Expected	Pass	
2	Observe details displayed	Name, description, contact info, address, services, link to the source all visible	As Expected	Pass	

Table 6.9: View Information Details Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	On Information Details page, tap bookmark/save icon	Icon changes (e.g., from outline → filled)	As Expected	Pass	
2	Data saved in backend (Firestore/Supabase)	Saved status persists after reopening page	As Expected	Pass	

Table 6.10: Save or Bookmark Information Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “+ Add Post” button	Post creation form opens	As Expected	Pass	
2	Enter text OR upload image OR record audio	User input is accepted	As Expected	Pass	
3	If audio → tap “Transcribe”	Speech-to-text is generated	As Expected	Pass	
4	Tap “Post”	Post successfully uploaded and visible in Community feed	As Expected	Pass	

Table 6.11: Community Add Post Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Enter username in search bar	Matching usernames appear	As Expected	Pass	
2	Tap a result	User is navigated to that profile page	As Expected	Pass	

Table 6.12: Search User Profile Test Case
Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “Like” icon on a post	Like count increases, icon changes	As Expected	Pass	
2	Tap “Comment”	Comment section opens	As Expected	Pass	
3	Enter comment text and submit	Comment appears under post	As Expected	Pass	

Table 6.13: Like & Comment on a Post Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “Reply” under a comment	Reply input field appears	As Expected	Pass	
2	Enter reply text	Text is accepted	As Expected	Pass	
3	Submit reply	Reply displayed nested under parent comment	As Expected	Pass	
4	Tap “Like” icon on a comment	Like count increases, icon changes	As Expected	Pass	

Table 6.13: Reply and like to a Comment Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “Message” icon on a post	Direct Message screen opens	As Expected	Pass	
2	View chat UI	Chatbox, send button visible	As Expected	Pass	

Table 6.14: Direct Message Button (Open Chat Page) Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Open Chatbot page	Chatbot screen loads with empty chat	As Expected	Pass	
2	Type message in input box	Text appears correctly	As Expected	Pass	
3	Tap “Send” icon button	Message sent as user bubble	As Expected	Pass	
4	Observe chatbot response	Chatbot replies with relevant message	As Expected	Pass	

Table 6.15: Chatbot Responds to User Query Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “Edit Profile”	Edit form opens	As Expected	Pass	
2	Change profile picture	New image preview displayed	As Expected	Pass	
3	Enter new bio	Bio field updated	As Expected	Pass	
4	Tap “Save Changes”	Changes saved and updated on profile page	As Expected	Pass	

Table 6.16: Edit Profile Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “My Posts”	My Posts page opens	As Expected	Pass	
2	Observe list	All posts displayed correctly	As Expected	Pass	

Table 6.17: View My Posts Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap “Saved Information”	Saved items list page opens	As Expected	Pass	
2	Check list	All previously saved items displayed correctly	As Expected	Pass	

Table 6.18: View Saved Information Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Go to Settings Page	Settings Page Loads	As Expected	Pass	
2	Toggle Dark Mode On	App theme changes to dark	As Expected	Pass	
3	Toggle Dark Mode Off	App theme changes to light	As Expected	Pass	

Table 6.19: Toggle Dark Mode Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Tap toggle for Screen Reader Mode	Warning popup appears (“Enable Screen Reader Mode”)	As Expected	Pass	
2	Tap “Proceed” on warning dialog	App navigates to device Accessibility Settings	As Expected	Pass	
3	User enables TalkBack manually	TalkBack On	As Expected	Pass	
4	Return to App	Screen Reader Mode shows ON state	As Expected	Pass	

Table 6.20: Toggle Screen Reader Mode Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Toggle for High Contrast Mode ON	Interface switches to high contrast colours	As Expected	Pass	
2	Toggle for High Contrast Mode OFF	Interface returns to normal colours	As Expected	Pass	

Table 6.21: Toggle High Contrast Mode Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
				
1	Select “Small” text size	All UI text becomes smaller	As Expected	Pass
2	Select “Medium” text size	Text returns to default size	As Expected	Pass
3	Select “Large” text size	Text increases in size	As Expected	Pass

Table 6.22: Change Text Size Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Navigate to MY OKULink App	App should open	As Expected	Pass	
2	Enter Email & Password	Credential can be entered	As Expected	Pass	
3	Click Login	Admin is redirected to Admin Dashboard	As Expected	Pass	

Table 6.23: Login Admin Test Case


Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Navigate to Admin Dashboard	Dashboard loads successfully	As Expected	Pass	
2	Check category tabs (Government Aid, Special Schools, Therapy, NGOs)	Tabs visible and scrollable horizontally	As Expected	Pass	
3	Check PWD Filter dropdown	Shows “All PWD Types” by default	As Expected	Pass	
4	Check list of information cards	All published items displayed	As Expected	Pass	
5	Tap triple-dot menu on any item	Shows options: Edit, Delete	As Expected	Pass	

Table 6.24: Admin Dashboard Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Click Add New Info button	Post creation form opens	As Expected	Pass	
2	Select category filter (Government Aid, Special Schools, Therapy, NGOs)	Drop down filter visible and scrollable horizontally	As Expected	Pass	
3	Check PWD Type Filter dropdown	Shows “All PWD Types” and types	As Expected	Pass	
4	Check region	All Region across Malaysia displayed	As Expected	Pass	
5	Fill in the information in title form	Title form can be filled	As Expected	Pass	
6	Fill in the information in the Summary (short intro) form	Title form can be filled	As Expected	Pass	
7	Fill in the information in Description (Markdown supported) form	Title form can be filled	As Expected	Pass	
8	Fill in the information Extra Info (for See More) form	Title form can be filled	As Expected	Pass	
9	Fill a valid link in Source link (Optional)
	Title form can be filled	As Expected	Pass	
10	Choose Status Published	Status can be chosen	As Expected	Pass	
11	Click Create Button	Information posted successfully	As Expected	Pass	

Table 6.25: Add New Info Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Click Edit from the triple dot button 	Post creation form opens	As Expected	Pass	
2	Select category filter (Government Aid, Special Schools, Therapy, NGOs)	Drop down filter visible and scrollable horizontally	As Expected	Pass	
3	Check PWD Type Filter dropdown	Shows “All PWD Types” and types	As Expected	Pass	
4	Check region	All Region across Malaysia displayed	As Expected	Pass	
5	Fill in the information in title form	Title form can be filled	As Expected	Pass	
6	Fill in the information in the Summary (short intro) form	Title form can be filled	As Expected	Pass	
7	Fill in the information in Description (Markdown supported) form	Title form can be filled	As Expected	Pass	
8	Fill in the information Extra Info (for See More) form	Title form can be filled	As Expected	Pass	
9	Fill a valid link in Source link (Optional)
	Title form can be filled	As Expected	Pass	
10	Choose Status Published	Status can be chosen	As Expected	Pass	
11	Click the Save Changes Button	Information edited and posted successfully	As Expected	Pass	

Table 6.26: Edit Info Test Case

Step #	Step Details	Expected Results	Actual Results	Pass / Fail / Not executed / Suspended
					
1	Click Delete from the triple dot button 	Post creation form opens	As Expected	Pass	
2	Confirm Delete warning 	Delete warning displays	As Expected	Pass	
3	User click delete	Post deleted successfully	As Expected	Pass	

Table 6.27: Delete Info Test Case
