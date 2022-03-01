# web-learning
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        /* this is main top navbar  */
    .navbar {
	display: flex;
	position: sticky;
	top: 0px;
	background-color: #17678E;
	height: 50px;
	padding: 10px;
	align-items: center;
}
     /* this is main top navbar left */
.navbar-left {
	display: flex;
	justify-content: space-around;
	width: 50%;
	color: white;
	font-size: larger;
}
     /* this is main top navbar right */
.navbar-right {
	display: flex;
	justify-content: space-around;
	margin-left: 30%;
	width: 50%;
	color: white;
	font-size: larger;
}
    /* this is center registration form  */
.register-form {
	display: grid;
	padding: 30px;
	width: 70%;
	height: 70%;
	margin-left: 10%;
	margin-right: 10%;
	top: 50%;
}
    /* this is center registration form lsit 1 -2  */
.register-form>div {
	font-size: medium;
	padding: 10%;

}
    /* this is center registration form lsit 1  */
.list1 {
	grid-area: 1/1;
}
     /* this is center registration form lsit 2  */
.list2 {
	grid-area: 1/2;
	background-color: #122f50;
	color: white;
}
     /* this is center registration table */
.table1 {
	border: 1px solid black;
}

td,th {
	border: 1px solid black;
}

#font {
	font-weight: bold;
	background-color: gainsboro;
	font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.creadit {
	margin-top: 30px;
	background-color: gray;
	padding: 20px;
	display: flex;
	flex-direction: column;
}

#button1 {
	background-color: red;
	width: 200px;
}
  /* this is data show on page footer main  */
.footer {
	display: flex;
	flex-direction: row;
	justify-content: space-around;
	background-color: #112e51;
	color: white;
	padding: 20px;
	padding-top: 120px;
}
/* this is data show on page footer main list 1-2 */
.footer-list1{
	flex-direction: column;
	justify-content: space-evenly;
}

.footer-list2{
	margin-top: 10px;
}

.footer-image {
	display: flex;
	background-color: #112e51;
	height: 50px;
	padding: 10px;
	padding-top: 80px;
}
    </style>
</head>
<body>
    <!-- this is mainu bar top side -->
	<div class="navbar">
		<div class="navbar-left"> <img src="C:\Users\Parvez\Desktop\logotype.svg" height="30px">
			<div>Games</div>
			<div>Plans</div>
			<div>Blog</div>
		</div>
		<div class="navbar-right">
			<div>Log in </div>
			<div>Sing up</div>
		</div>
	</div>
    <!-- this is a center registraion form -->
	<div class="register-form">
		<div class="list1">
			<div class="main">
				<br class="register">
				<h2> Register New Account</h2>
				<br id="register" method="post">
				<label> User Name </label>
				<br>
				<input type="text" Name="Sname"> </br>
				</br>
				<label> Email </label>
				<br>
				<input type="text" Name="Sname"> </br>
				</br>
				<label> Password </label>
				<br>
				<input type="number" Name="Tname"> </br>
				</br>
				<label> Password Again </label>
				<br>
				<input type="number" Name="fname"> </br>
				</br>
                <!-- this is center resgistration radio button -->
				<input type="radio" id="rad_1">
				<label for="rad_1">Basic-free</label>
				<br>
				<br>
				<input type="radio" id="rad_2">
				<label for="rad_2">Pro Monthly - $6.00</label>
				<br>
				<br>
				<input type="radio" id="rad_2">
				<label for="rad_2"> Pro Lifetime - $99.00</label>
				<br>
				<br>
				<input type="radio" id="rad_2">
				<label for="rad_2">Pro Group Monthly - $3.00 Per Seat</label>
				<br>
				<br>
				<input type="radio" id="rad_2">
				<label for="rad_2"> Pro Group Annual - $24.00 Per Sea</label>
				<br>
				<br> </div>
			<div class="table1">
				<table>
					<tr>
						<th id="font"> Member ship </th>
						<th id="font"> Amount </th>
					</tr>
					<tr>
						<td> Pro Monthly </td>
						<td> $6 </td>
					</tr>
					<tr>
						<td id="font"> Total Today </td>
						<td> $6</td>
					</tr>
					<tr>
						<td id="font"> Total Recurring Per Month</td>
						<td> $6 / Month</td>
					</tr>
					<tr>
						<td id="font"> Next Renewal due </td>
						<td> March 24 2022</td>
					</tr>
				</table>
			</div>
            <!-- this is a center table formate -->
			<div class=" table2">
				<h3>  Choose Your Payment Method </h3>
				<input type="radio" id="rad_3">
				<label for="rad_1"> Creadit Card</label>
				<input type="radio" id="rad_3">
				<label for="rad_1">Paypal</label>
			</div>
			<div class="creadit">
				<label for="rad_1"> Name on Card</label>
				<input type="text" id="rad_5">
				<label for="rad_1"> Creadit Card</label>
				<input type="number" id="rad_5" placeholder="Card Number       MM/YY"> </div>
			<br>
			<br>
			<input type="checkbox" id="rad_5">
			<label for="rad_1"> I agree to the terms and conditions </label>
			<br>
			<input type="checkbox" id="rad_5">
			<label for="rad_1"> I want to get emails about news games and exclusive offers</label>
			<br>
			<br>
			<input type="button" id="button1" value="Register"> </form>
		</div>
        <!-- this is a center registration list 2 -->
		<div class="list2">
			<h2> Basic Plan </h2>
			<h4> Free Games </h4>
			<p>Play free games that introduce the latest coding topics.</p>
			<h4> Checkpoints </h4>
			<p>Save your progress and access it from anywhere</p>
			<h4></h4>
			<p>Save your progress and access it from anywhere</p>
			<h4>Achievements </h4>
			<p>Track and share your in-game achievements.</p>
			<h4> Checkpoints </h4>
			<h2> Pro Plan </h2>
			<h4> Pro Games </h4>
			<p>Play premium games that help you achieve mastery.</p>
			<h4> Solution Guides </h4>
			<p>Access detailed explanations for educators or stumped students.</p>
			<h4>No Ads</h4>
			<p>Hide ads and play distraction-free.</p>
			<br>
			<br>
			<h2> Group Plans</h2>
			<h4> Classroom Management</h4>
			<p>All of the above, plus register and manage other users. </p>
		</div>
	</div>
        <!-- this is buttum footer data  image list 1-2 -->
	<div class="footer-image"><img src="C:\Users\Parvez\Desktop\logotype.svg" height="30px"></div>
	<div class="footer">
		<div class="footer-list1"> CODEPIP
			<div class="footer-list2">About Us</div>
			<div class="footer-list2">Blog</div>
			<div class="footer-list2">Pricing</div>
			<div class="footer-list2">Curriculum</div>
			<div class="footer-list2"> Press</div>
		</div>
		<div class="footer-list1"> FEATURES
			<div class="footer-list2"> Games</div>
			<div class="footer-list2">Individual Plans</div>
			<div class="footer-list2">Group Plans</div>
			<div class="footer-list2">Classroom</div>
		</div>
		<div class="footer-list1"> SUPPORT
			<div class="footer-list2">FAQ</div>
			<div class="footer-list2">Contact Us</div>
			<div class="footer-list2">Privacy Policy</div>
			<div class="footer-list2">Terms of Service</div>
		</div>
		<div> FOLLOW
			<div class="footer-list1">Twitter</div>
			<div class="footer-list2">Facebook</div>
			<div class="footer-list2"> Instagram</div>
			<div class="footer-list2"> LinkedIn</div>
			<div class="footer-list2"> YouTube </div>
			<div class="footer-list2"> RSS </div>
		</div>
		<div> LATEST
			<div class="footer-list2">Reach your resources with Pathfinder, a game of constructing file paths</div>
			<div class="footer-list2">Treat yourself to selectors with CSS Scoops</div>
			<div class="footer-list2"> Organize emoji with Disarray, a coding game about JavaScript array methods </div>
			<div class="footer-list2">Dig deep about the :nth-child() selector with our newest CSS game, Nth Cart</div>
		</div>
</body>

</html>
