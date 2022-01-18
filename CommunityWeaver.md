[Home](index.html) | [Toolkit](Toolkit.html) 

# Community Weaver 3 (CW3)


[Community Weaver 3](https://timebanks.org/communityweaver3/) is the current software platform for Timebanks provided by [Timebanks.org](https://timebanks.org/timebanks/) when you start a Timebank.

You'll want someone in your group who is comfortable being able to configure and administer Community Weaver to manage your Timebank. This guide will provide you with some basics, some warnings and some tips.

``NOTICE`` **The following warning is currently displayed at the CW3 wiki**

     Due to our email server hardware failure, the site email address is temporarily out of service. 
     Email sent to the CW site's email address will not be sent to coordinators. Please inform your 
     members of this issue and that they will need to send their emails directly to a coordinator's 
     email address. We regret this disturbance to communications with your timebank members and are 
     currently working to resolve this issue.

## Managing a CW3 Site

1. [Assigning Coordinators](#assigning_coordinators)
2. [Configuring CW3](#configuring_cw3)
3. [Content of Special Pages](#special_pages)

### Coordinators <a name="assigning_coordinators"></a>

#### Types of Coordinators

There are five different coordinator roles, each has a special set of tasks: Admin, Member, Member Support, Outreach, and Payments.

``TIP`` You can assign coordinator roles to lots of people, so they share the workload.

``TIP`` You can also assign multiple coordinator roles to a single person

``CW3 Wiki`` [Timebank coordinator's roles and permissions](http://wiki.timebanks.org/wiki/Coordinator_Permissions)

**Admin**
 coordinator is responsible for the site-wide aspects of the Community Weaver site and has access to everything in the timebank, especially all site-wide configurations
 This coordinator does everything
 __There may be more than one admin__

**Member**
 coordinator is responsible for supporting and managing Community Weaver memberships.
 This coordinator handles member profiles and activities

**Member Support**
 coordinator is responsible to support members posting offers and requests as well as recording their exchanges
 This coordinator can give members a hand with exchanges

**Outreach**
 coordinator is responsible for publicity and outreach in Community Weaver. They are generating marketing, communications, and web content.

**Payments**
 coordinator is responsible for managing payment processing, nothing else.

## Configuring Community Weaver <a name="configuring_cw3"></a>


``CW3 Wiki`` [Configuring New Timebank][1]

``TIP``: Do your own tests. Ensure your settings are working the way that you expect them to.

1. [CW3 Help Pages](#cw3_help_pages)
2. [General Settings](#general_settings)
3. [Sign Up](#sign_up)
4. [Design](#design)
5. [Lists](#lists)
6. [Email](#email)
7. [Payments](#payments)

### CW3 Help Pages <a name="cw3_help_pages"></a>

``CW3 Wiki`` [Coordinator configuration options for your timebank](http://wiki.timebanks.org/wiki/Category:Coordinator_Options)

``CW3 Wiki`` [The online Community Weaver manual for coordinators](http://wiki.timebanks.org/wiki/Help_for_Coordinators)

``TRAP`` The information in the help pages can be confusing. Often there is no information, just a lot of links leading you in circles.


### General <a name="general_settings"></a>

``CW3 Wiki`` [TimeBank General Settings][2]

#### Identity

The information you provide here will be used at the top of the page and at the bottom of the page.

**Site Name**
  Appears at the top left of the page in bold and same colour as the theme. Also appears at the bottom left with the address and telephone number.
  
**Email Subject Brand**
  This is used to identify email by prefixing the subject with this text in square brackets. It would be a good idea to keep this fairly short.
  
**Slogan**
  This is displayed beneath the logo, which appears on most pages.
  
**Footer Message**
  This can be HTML. You can includes images, text formatting, and CSS. We don’t suggest that you try to include javascript/ECMAscript as it would probably conflict with the CW3 code.
  
**Site Email Address**  
   ``CW3 Wiki``[wiki.timebanks.org/wiki/TimeBank_Email_Address][3]
  
  This email address is used by CW3 to direct communications to coordinators
  
  ``CRAP`` At the beginning of 2022 it is broken and has been broken for some time.
  
**Postal Address**  
   ``WARNING`` This address is displayed at the bottom of every page and in emails. It will definitely be indexed by search engines.
  
**Phone Number**  
   ``WARNING`` This number is displayed at the bottom of every page and in emails. It will definitely be indexed by search engines.
  

#### Features

``TIP`` The choices you make here controls the behaviour of CW3.

**Signup Page**
  - Allow anyone to signup as a member?
    - When checked, anyone can sign up
      - Pros
        - Easy to sign up
      - Cons
        - Hard to manage who signs up
        - If you have referee checks, or any other requirement, such as identity validation, then you may need a different sign up form. For a user, having to sign up multiple times is confusing and can undermine confidence.  

``WARNING`` If you allow anyone to sign up there is more to do. Go to [Configure->Signup](#sign_up) and follow the instructions there.
          
**Member Privacy**
  ``TIP`` Always check this box
  
  ``Pro`` MEMBER PRIVACY
  
  ``Con`` Cannot share user offers/requests with FaceBook
  
**External Links open in new window**  
  Generates a new browser tab for links outside CW3. This setting benefits users who are younger than the internet.
  
**Default Ad Expiration**  
  Choose the period that you think best suits the sort of exchanges for your group. Users can override this easily, but if they don’t need to change it, there is less friction in the offer/request process.
  
**Facebook and Facebook Like Page**
  If you have a Facebook group, use this setting to put social buttons on the page and link to your group
  
**Twitter and Twitter User Name**
  If you have a Twitter account, use this setting to put social buttons on the page and link to your account
  

#### Language and Text

- Localise your settings.
- These settings are important. You should set them appropriately.
- In Aotearoa / New Zealand the settings would typically be
  - **Default Country**: New Zealand
  - **Language**: English
  - **Time Zone**: Auckland
  - **Restrict Member Time Zones**: Pacific

### Sign Up <a name="sign_up"></a>

``CW3 Wiki`` [Signup Settings][4]

#### Step 1: Sign Up

**Allow anyone to sign up?**  
  ``TIP`` This is the same as the checkbox in General->Features. (But in this case, its in the right place)
  - You may not want this option checked.
  - If you have a custom sign up form, you need to turn this option OFF and redirect users to your sign up form. We suggest you use “Special Pages” to either present your form or to redirect users to your form.

#### Step 2: Profile

``TIP`` Be frugal with these options. Use the absolute minimum.  
`TRAP` If users do not provide answers to every one of the options you have selected their profile will not be marked as 100% complete.  
`CRAP` CW3 actives recommends that **most options should not be used**

We have some observations

The **Time Zone** is pointless in NZ
  
**Neighbourhood** : not recommended
  - USA-centric. In NZ we have suburbs and don’t usually need any further breakdown.
  - Users who enter their address will have included their suburb already. Asking for their “neighbourhood” is a duplication.
  - If you are going to use this you MUST provide a list of neighbourhoods.
  
 ``TIP`` Don't repeat your suburbs in the list of neighbourhoods, it gets really confusing when you do that. 

 ``GOTCHA`` Users enter neighbourhoods that are not in your list.  

 - If you are _not_ going to use neighbourhoods, ensure that the list of neighbourhoods is empty. 
  
 ``GOTCHA`` The implementation is a bit messy. You’ll find places where “neighbourhood” is an option even though you are not using them. 

**County** : not recommended
 - USA-centric. Could be useful in wide-spread groups but the language is wrong, so you may not get reliable inputs.  
 - If you use this you MUST provide a list of “counties”  
 - If you do not use this make sure the list of counties is empty.  
``GOTCHA`` the implementation is messy. You’ll find places where “county” is an option even though you are not using them.

``CW3 Wiki`` [IMPORTANT RECOMMENDATIONS][5]

``TIP`` _Profile options that are **Not Recommended** for use in Sign Up Forms._

- Neighborhood
- County
- Nickname
- Phone
- Phone (Work)
- Phone (Home)
- Phone (Cell)
- Fax
- Alternate email
- Alternate email (home)
- Alternate email (work)
- Twitter
- Facebook
- Linkedin
- Google+
- Web address

#### Step 3: External Validation

``TRAP``: These checkboxes to not do anything.  
 ``CRAP``: future version of CW3 is vaporware

### Design <a name="design"></a>

``CW3 Wiki`` [Design Settings][6]

#### Fonts

- The font you choose will be used everywhere.  
  ``TIP`` Tahoma, Trebuchet, and Verdana are designed for digital screens  
  ``TRAP`` Only three of the fonts in the list where designed for reading on computers.  
  ``CRAP`` It’s easier to get it wrong than it is to get it right. Eight of the eleven options are not recommended

#### Logo

``CW3 Wiki`` [Site Logo][7]

``TIP``

- Use a minimum logo size of 500 x 500 pixels  
- Use a version of your logo that is approximately square
  

``TRAP``

- The site will crop your logo using a circular boundary.
- The site will put your logo into narrow columns

``CRAP``

- You can only provide one logo file
- If your logo was not designed to fit in a circle, or was not designed for portrait mode, it will get munched.

#### Colours

``CW3 Wiki``[Site Colours][8]

``TRAP``  
 * Actual designers who think in colour were never consulted by the programmers who developed CW3  
 * There are too many colour options  
 * [Relative Color Densities][9] are used for reasons that have no relevance for end-users.

``CRAP``  
 * You must use all the options  
 * The options work against each other  
 * No matter what colours you choose. The site will use Red (#FF0000), Orange (#FFA500), Yellow(#FFFF00), and Blue (#0000FF) for various purposes.  
 ``CW3 Wiki``[ou.edu/research/electron/internet/bgcolors.shtml][10]

``TIP``  
 * [Mineral UI Color scheme][11] is designed for use on digital screens for the widest possible range of users (old, young, sight impaired, etc)  
 * The Mineral UI colour schemes will give you an approximate sense of what effect the [Relative Color Densities][12] will have.

### Lists <a name="lists"></a>

``CW3 Wiki`` [wiki.timebanks.org/wiki/Time_Bank_Manage_Lists][13]

#### Service Categories

``CW3 Wiki`` [wiki.timebanks.org/wiki/Service_Categories][14]

``WARNING`` - DO NOT DELETE ALL THE CATEGORIES  
 * If you delete all the categories, CW3 will crash  
 * At least one top-level category and one sub-category is required.

#### Tags

- Tags are used by coordinators, not members. Use them to mark (tag) a member account for use in filtering and reporting.

#### Affiliations

- This is just a list of things that people might affiliate with. It could be business, sporting teams or houses of the horoscope.

#### Counties

``Tip`` clear the default entries

### Neighbourhoods

``TIP`` clear the default entries

#### Community Timebanks

``CW3 Wiki`` [wiki.timebanks.org/wiki/Community_Timebanks][15]

- can also be thought of as branches or sub-timebanks,
- This allows Sub-groups within your timebank
- If you do create community TimeBanks they are completely optional. Coordinators don’t have any control over which communities the members choose to be in.
  - If community TimeBanks are created, members can choose to be in any, all, or none of them.
  - Members can post their ads to any, all, or none of the community Timebanks.
- All timebank members can see all other timebank members even if they are associated with different Community Timebanks.

#### Contact Form Categories

``CW3 Wiki`` [wiki.timebanks.org/wiki/Contact_Form#Managing_Contact_Forms][16]

- Contact forms can be used by anyone, and is accessible on every page on your Timebank as an **Envelope** icon in the toolbar  
  ``TIP`` Make contact forms for different purposes  
  ``TRAP`` The contact form is a source of attempted spam or phishing messages  
  ``CRAP`` They don’t work if the email server is broken.
- Due to our email server hardware failure, this feature may not function as expected. If your contact form submission bounces, please write directly to your timebank coordinator. We regret this disturbance to your communications and are currently working to resolve this issue.

### Email <a name="email"></a>

``CW3 Wiki`` [Email Settings][17]

**It is extremely important to setup your email correctly**

Use the [instructions provided by CW3 help][17] for this task.

``CW3 Wiki`` [Understanding email notifications][18]

``CW3 Wiki`` [How to configure CW email][19]

#### Email Templates

``CW3 Wiki`` [How to customize email notification templates][20]

``TIP`` Put some thought into the content of your email templates. It makes a big difference for your members who receive good information.


### Payments <a name="payments"></a>

``CW3 Wiki`` [Payments][21]

#### Is your timebank a Pay-to-Play community?

If so, you’ll benefit from the payment features in CW3.

[Payment feature overview][22]  

[Payment feature configuration][23]

## Content of Special Pages <a name="special_pages"></a>
CW3 expects you to provide a certain amount of content as web pages. It calls the web pages that you are required to provide _special pages_. 

```TIP``` Provide good content for the special pages, you can include images and formatting.    
```GOTCHA``` If you only use a single sentence as content on a special page, most people will only see a big empty white page.    

CW3 allows you to generate web pages. You can create as many pages as you like within CW3. There is no stated limit. This is an excellent feature and really should be explored fully. Good content can build and bond your community together. 

Within CW3, under the gear cog icon, look for "Manage, Pages." The link will reveal the Pages module. CW3 recognises two types of pages: regular pages and special pages. We'll look at what is special about special pages but before we do that we'll discuss regular pages. 

### Regular Pages

The admin and the outreach coordinater are able to create pages. These pages can contain any content. With a little planning, you are able to hyperlink news and pages. This allows you to generate more focussed content and to build on previous content without having to repeat yourself. Interactivity of this kind provides a richer and more rewarding experience for your members. 

``TIP`` Use relative URLs to generate links to other pages and news items. 

Every page and news item has an ID number, and it is used to create a URL. When you are editing a news item or a page, the ID number will be visible in your web browser location box. For example, in this URL, "https://wellingtonsouth.timebanks.org/page/2903" the ID number is 2903. The relative URL is "/page/2093".

> Relative URLS for news items begin with "/news/"   
> Relative URLs for regular and special pages begin with "/page/"  

### Special Pages
Special pages are used to describe things, like the mission of the timebank, the code of conduct, membership info, subscription instructions, and so on. These special pages need good content. Without good content your timebank web site will provide a confusing, underwhelming experience. 

> The worst thing that you can do with these pages is provide a short sentence of plain text. 

When the page is displayed that sentence will appear in the top left corner of the page beneath the menu. The rest of the page will be blank and the dominant impression is that the page is empty. People may not even notice the little sentence you provided. 

> The best thing you can do is to provide structured text and include images

Start by giving your special pages a structured outline, for example:
```
hero image
Title
section one
text
section two
text and image
section three
text
```

Use HTML formatting so that it has visual appeal. Include images to convey ideas. The special pages may not be the most interesting aspect of the web site but they will be viewed frequently. Make them appealing. 

---




[1]: http://wiki.timebanks.org/wiki/Configuring_a_New_Timebank  
[2]: http://wiki.timebanks.org/wiki/TimeBank_General_Settings  
[3]: http://wiki.timebanks.org/wiki/TimeBank_Email_Address  
[4]: http://wiki.timebanks.org/wiki/TimeBank_Signup_Settings  
[5]: http://wiki.timebanks.org/wiki/Member_Signup_Settings#IMPORTANT_RECOMMENDATIONS  
[6]: http://wiki.timebanks.org/wiki/TimeBank_Design_Settings  
[7]: http://wiki.timebanks.org/wiki/TimeBank_Design_Settings#Site_Logo  
[8]: http://wiki.timebanks.org/wiki/TimeBank_Design_Settings#Site_Colors  
[9]: http://wiki.timebanks.org/wiki/TimeBank_Design_Settings#Relative_Color_Densities  
[10]: https://www.ou.edu/research/electron/internet/bgcolors.shtml  
[11]: https://mineral-ui.netlify.app/color  
[12]: http://wiki.timebanks.org/wiki/TimeBank_Design_Settings#Relative_Color_Densities  
[13]: http://wiki.timebanks.org/wiki/Time_Bank_Manage_Lists  
[14]: http://wiki.timebanks.org/wiki/Service_Categories  
[15]: http://wiki.timebanks.org/wiki/Community_Timebanks  
[16]: http://wiki.timebanks.org/wiki/Contact_Form#Managing_Contact_Forms  
[17]: http://wiki.timebanks.org/wiki/Configuring_a_New_Timebank#Email  
[18]: http://wiki.timebanks.org/wiki/Notification_Emails_used_in_CW  
[19]: http://wiki.timebanks.org/wiki/TimeBank_Email_Configuration  
[20]: http://wiki.timebanks.org/wiki/TimeBank_Email_Notifications_-_Customization  
[21]: http://wiki.timebanks.org/wiki/Configuring_a_New_Timebank#Payments  
[22]: http://wiki.timebanks.org/wiki/Payment_feature_overview  
[23]: http://wiki.timebanks.org/wiki/Payment_feature_setup
