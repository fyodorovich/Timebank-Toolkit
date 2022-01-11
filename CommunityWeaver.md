General
	Identity
		The information you provide here will be used at the top of the page and at the bottom of the page.
		Site Name
			Appears at the top left of the page in bold and same colour as the theme. Also appears at the bottom left with the address and telephone number.
		Email Subject Brand
			This is used to identify email by prefixing the subject with this text in square brackets. It would be a good idea to keep this fairly short.
		Slogan
			This is displayed beneath the logo, which appears on most pages.
		Footer Message
			This can be HTML. You can includes images, text formatting, and CSS. We don’t suggest that you try to include javascript/ECMAscript as it would probably conflict with the CW3 code.
		Site Email Address
			This email address is used by CW3 to direct communications to coordinators
			``CRAP``
				At the beginning of 2022 it is broken and has been broken for some time.
		Postal Address
			WARNING: This address is displayed at the bottom of every page and in emails. It will definitely be indexed by search engines.
		Phone Number
			WARNING: This number is displayed at the bottom of every page and in emails. It will definitely be indexed by search engines.
	Features
		The choices you make here controls the behaviour of CW3.
		Signup Page
			Allow anyone to signup as a member?
				When checked, anyone can sign up
					Pros
						Easy to sign up
					Cons
						Hard to manage who signs up
						If you have referee checks, or any other requirement, such as identity validation, then you may need a different sign up form. For a user, having to sign up multiple times is confusing and can undermine confidence.
				WARNING: If you allow anyone to sign up there is more to do. Go to Configure->Signup and follow the instructions there.
		Member Privacy
			Check this box at all times
				Pros
					MEMBER PRIVACY!
				Cons
					Cannot share user offers/requests with FaceBook
		External Links open in new window
			Generates a new browser tab for links outside CW3. This setting benefits users who are younger than the internet.
		Default Ad Expiration
			Choose the period that you think best suits the sort of exchanges for your group. Users can override this easily, but if they don’t need to change it, there is less friction in the offer/request process.
		Facebook
		Facebook Like Page
		Twitter
		Twitter User Name
		If you have a Facebook group, use this setting to put social buttons on the page and link to your group
		If you have a Twitter account, use this setting to put social buttons on the page and link to your account
	Language and Text
		Localise your settings.
		These settings are important. You should set them appropriately.
		In Aotearoa / New Zealand the settings would typically be
			Default Country: New Zealand
			Language: English
			Time Zone: Auckland
			Restrict Member Time Zones: Pacific

``TIP``: Do your own tests. Ensure your settings are working the way that you expect them to.

See Also

Lists
	Service Categories
		WARNING - DO NOT DELETE ALL THE CATEGORIES
			If you delete all the categories, CW3 will crash
			At least one top-level category and one sub-category is required.
	Tags
		Tags are used by coordinators, not members. Use them to mark (tag) a member account for use in filtering and reporting.
	Affiliations
		This is just a list of things that people might affiliate with. It could be business, sporting teams or houses of the horoscope.
	Counties
		``Tip``: clear the default entries
	Neighbourhoods
		``TIP``: clear the default entries
	Community Timebanks
		can also be thought of as branches or sub-timebanks,
		This allows Sub-groups within your timebank
		If you do create community TimeBanks they are completely optional. Coordinators don’t have any control over which communities the members choose to be in.
			If community TimeBanks are created, members can choose to be in any, all, or none of them.
			Members can post their ads to any, all, or none of the community Timebanks.
		All timebank members can see all other timebank members even if they are associated with different Community Timebanks.
	Contact Form Categories
		Contact forms can be used by anyone, and is accessible on every page on your Timebank as an Envelope icon in the toolbar
		``TIP``
			Make contact forms for different purposes
		``TRAP``
			The contact form is a source of attempted spam or phishing messages
		``CRAP``
			They don’t work if the email server is broken.
		Due to our email server hardware failure, this feature may not function as expected. If your contact form submission bounces, please write directly to your timebank coordinator. We regret this disturbance to your communications and are currently working to resolve this issue.

Design
	Fonts
		The font you choose will be used everywhere.
		``TIP``
			Tahoma, Trebuchet, and Verdana are designed for digital screens
		``TRAP``
			Only three of the fonts in the list where designed for reading on computers.
		``CRAP``
			It’s easier to get it wrong than it is to get it right. Eight of the eleven options are not recommended
	Logo
		Use a minimum size of 500 x 500 pixels
		``TRAP``
			The site will crop your logo using a circular boundary.
			The site will put your logo into narrow columns
		``CRAP``
			You can only provide one logo file
			If your logo was not designed to fit in a circle, or was not designed for portrait mode, you will be unhappy.
		``TIP``
			Use a version of your logo that is approximately square
	Colours (Colors)
		``TRAP``
			Actual designers who think in colour were never consulted by the programmers who developed CW3
			There are too many colour options
			[Relative Color Densities][1] are used for reasons that have no relevance for end-users. [1]: http://wiki.timebanks.org/wiki/TimeBank_Design_Settings#Relative_Color_Densities
		``CRAP``
			You must use all the options
			The options work against each other
			No matter what colours you choose. The site will use Red (#FF0000), Orange (#FFA500), Yellow(#FFFF00), and Blue (#0000FF) for various purposes.
		``TIP``
			Mineral UI Color scheme is designed for use on digital screens for the widest possible range of users (old, young, sight impaired, etc)
			The Mineral UI colour schemes will give you an approximate sense of what effect the Relative Color Densities will have.

Sign Up
	Step 1: Sign Up
		Allow anyone to sign up?
			This is the same as the checkbox in General->Features. (But in this case, its in the right place)
		You may not want this option checked.
		If you have a custom sign up form, you need to turn this option OFF and redirect users to your sign up form. We suggest you use “Special Pages” to either present your form or to redirect users to your form.
	Step 2: Profile
		``TIP``
			Be frugal with these options. Use the absolute minimum.
				Time Zone
					Pointless in NZ
				Neighbourhood
					USA-centric. In NZ we have suburbs and don’t usually need any further breakdown.
					Users who enter their address will have included their suburb already. Asking for their “neighbourhood” is a duplication.
					If you are going to use this you MUST provide a list of neighbourhoods.
					If you do not use this, ensure that the list of neighbourhoods is empty.
					GOTCHA: Users enter neighbourhoods that are not in your list.
					GOTCHA: The implementation is a bit messy. You’ll find places where “neighbourhood” is an option.
				County
					USA-centric. Could be useful in wide-spread groups but the language is wrong, so you may not get reliable inputs.
					If you use this you MUST provide a list of “counties”
					If you do not use this make sure the list of counties is empty.
					GOTCHA: the implementation is messy. You’ll find places where “county” is an option.
		``TRAP``
			If users do not provide answers to every one of the options you select their profile will not be marked as 100% complete.
		``CRAP``
			CW3 actives recommends that MOST of options that they offer SHOULD NOT BE USED
				Profile options that are Not Recommended for use in Sign Up Forms.
					Neighborhood County Nickname Phone Phone (Work) Phone (Home) Phone (Cell) Fax Alternate email Alternate email (home) Alternate email (work) Twitter Facebook Linkedin Google+ Web address
	Step 3: External Validation
		``TIP``: These checkboxes to not do anything.
		``TRAP``: see ``TIP``
		``CRAP``: future version of CW3 is vaporware

Payments
	Is your timebank a Pay-to-Play community? If so, you’ll benefit from the payment features in CW3.
	Payment feature overview
	Payment feature configuration

Email
	Currently affected by email server outage but still needs to be setup correctly.
	Understanding email notifications
	How to configure CW email
	How to customize email notification templates
	``TIP``
		Put some thought into the templates. It makes a big difference to users to receive good information, even when they know it’s bot-driven.
