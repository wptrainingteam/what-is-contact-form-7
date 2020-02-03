# What Is Contact Form 7

## Description

Contact Form 7 is an easy-to-use plugin to create and add a contact form to your WordPress website. In this lesson, you will learn how to prepare and install the plugin and create and customize your first form, as well as setting up notifications to yourself and the form submitter.

## Objectives

After completing this lesson, participants will be able to:

* Explain the purpose of using Contact Form 7 plugin
* Add contact form into pages
* Customize contact forms according to requirements

## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Choose all that apply.

* [X] Users
* [X] Designers
* [X] Developers
* [ ] Speakers
* [ ] All

## Experience Level

How much experience would a participant need to get the most from this lesson?

* [x] Beginner
* [x] Intermediate
* [ ] Advanced
* [ ] Any

## Type of Instruction

Which strategies will be used for this lesson plan? Choose all that apply.

* [X] Demonstration
* [ ] Discussion
* [X] Exercises
* [ ] Feedback
* [x] Lecture (Presentation)
* [x] Show & Tell
* [ ] Tutorial

## Time Estimate (Duration)

How long will it take to teach this lesson (in minutes)?

45 minutes

## Prerequisite Skills

Participants will get the most from this lesson if they have familiarity with:

*   Ability to [install a plugin](https://github.com/wptrainingteam/choosing-and-installing-plugins) from the WordPress.org repository
*   Ability to [create and edit pages](https://github.com/wptrainingteam/pages-versus-posts) on your WordPress website

## Readiness Questions

* Do you have a self-hosted WordPress.org website (vs. WordPress.com website)?
* Do you have a user role that allows you to install plugins?
* Have you made a backup of your site before installing any plugins?
* Have you installed the Contact Form 7 plugin from the WordPress.org plugin repository?

## Materials Needed

* [Contact Form 7](https://wordpress.org/plugins/contact-form-7/) plugin

## Notes for the Instructor

* It is recommended that all students have made a backup of their site and have installed the Contact Form 7 plugin before working through this lesson. If they have not, ask them to do so before they get started, but the specifics of how to do so will not be covered in this lesson.
* The recommended way to approach the scenarios would be to demonstrate and explain the process first and then ask students to repeat the actions using their own devices, while you’re available for questions and troubleshooting if something doesn’t work out.

## Have You Thought About...?

* What if a participant owns a WordPress.com site that doesn't allow to install a plugin?
* What if a participant doesn’t has a WordPress site to work with?
* What if there's no Internet available?
* What if a participant doesn't own a computer?

## Lesson Overview

* A brief introduction on Contact Form 7
* Demonstrate how to add a contact form to a page
* Demonstrate how to customize a contact form
* Practice exercises to have participants add a customized contact form to a post

## Exercises

**Creating a contact form with mandatory fields**

Practice creating a form with mandatory fields.

* Create a new form using Contact Form 7
* Customize the form to make below fields as mandatory inputs
	* Name
	* Email address
* Add the form to any page of your choice

**Creating a questionnaire**

Practice creating a questionnaire containing five questions.

*   Add new contact form using Contact Form 7
* Design a form with five questions that contains below input types
	* Radio buttons
	* Checkboxes

**Creating a booking form with phone number**

Practice creating a booking form with phone number to be contacted.

* Add new contact form using Contact Form 7
* Design a booking form with below fields
	* Your Name (mandatory)
	* Your Email (mandatory)
	* Your Phone Number (mandatory, with format of "123-456-7890")
	* Booking Time (mandatory, in drop-down menu)
	* Message

## Assessment

**Which of the following is a Contact Form 7 tag?**

1. Your Message
2. [textarea your-message 40x2]
3. ["Enter your message" textarea your-message]
4. form.wpcf7-form {text-align: center;}

**Answer:** 2. [textarea your-message 40x2]

**What symbol is used to mark a field is required to answer?**

1. !
2. /
3. &
4. \*

**Answer:** 4. \*

**Which option can we use to wrap each checkbox and radio button with <label> tag?**
	
1. label
2. free_text
3. use_label_element
4. buton_label
	
**Answer:** 3. use_label_element
	
**How can I embed a contact form into my template file?**

1. [contact-form-7 id="1234" title="Contact form 1"]
2. <?php echo [contact-form-7 id="1234" title="Contact form 1"]; ?>
3. <?php echo do_shortcode( '[contact-form-7 id="1234" title="Contact form 1"]' ); ?>
**Answer:** 3. <?php echo do_shortcode( '[contact-form-7 id="1234" title="Contact form 1"]' ); ?>

## Additional Resources

* [Getting Started with Contact Form 7](http://contactform7.com/getting-started-with-contact-form-7/)
* [Contact Form 7: Documentation](http://contactform7.com/docs/)

## Example Lesson

### Introduction

Contact Form 7 is a user-friendly plugin for adding forms to your site, and these forms are not just limited to just contact forms. This plugin uses shortcodes and generator tools to help you create the form you are looking for on your website. Regarding contact forms, some of the benefits of using contact forms over just publishing a contact e-mail would be:

* It lets the user stay on the same page.
* It doesn’t require a user to redirect to their email account, which can be a hassle in a library or friend’s computer.
* You may take advantage of a browser’s auto fill function.
* Using such additional WordPress plugins like Gravity Forms, a form can route the notification to different addresses depending on the form subject.
* It doesn't reveal your email address to spammers.
* It allows for use of reCaptcha to avoid form fill-ins by bots.

### Using your form

Let's try using the default form in Contact Form 7 to add a simple contact form to a post.

1. Install Contact Form 7 using the <span style="color: #ff0000">WordPress plugin [directory](https://wordpress.org/plugins/search.php?type=term&q=contact+form+7)</span> and activate it.

[![Install Contact Form 7](images/installcontactform7.PNG)](images/installcontactform7.PNG)

2. By default, when you first install Contact Form 7 on your site, it will create a simple Contact Form for you. This can be accessed by clicking on **Contact** on the left-side menu, and then **Contact Forms**, which will bring up a list of all forms created with this plugin on your site.

[![Default Contact Form](images/defaultcontactform.png)](images/defaultcontactform.png)

The default form contains the following fields:

* Your Name - required
* Your Email - required
* Subject
* Your Message

You can insert this form immediately into any page or post on your site by using the shortcode shown next to the form name.

[![Edit Contact Form](images/editcontactform.png)](images/editcontactform.png)

3. Copy the shortcode, and paste into a new post to test it out. It also could be a good idea to use it for pages and widgets.

[![Add Contact Form to Post](images/addcontactformintopost.PNG)](images/addcontactformintopost.png)

Check out the result.

[![Preview Contact Form](images/previewcontactform.png)](images/previewcontactform.png)

### Customizing your form

You can further customize your form to look more stylish by using HTML or CSS. You can also edit the default template using tags to add or remove fields in the form to suit your needs. If you require more than a form on your site, you can always create a new one and customize it using the methods listed below.

#### Modifying Form Fields

1. Go to **Contact** > **Contact Forms** and select to **Edit** your form.

![Edit Contact Form](/images/editcontactform2.png)

2. You can start modifying the form by altering its code and adding fields using tags. To add fields to a form, you should make tags for them and put them into the ‘Form’ field.

![Add Tags](/images/addtags.png)

Tags are codes representing elements of the form, for example [text your-subject] or [text* your-name]. The tags can be added by clicking on the tags button when editing the form or by typing the codes directly into the editing area. Generated tags can be edited to suit various requirements as well.

![Generate Tag](/images/generatetag.PNG)

The basic parts that compose a tag can be found in [Using Tags](#using-tags) section.

> ![https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png) There are also some options available if you want to validate your data input for it to fit some requirements, i.e. phone number format, by using [Jquery Validation For Contact Form 7](https://wordpress.org/plugins/jquery-validation-for-contact-form-7/).

3. Don't forget to modify the email that you will be receiving then someone fills in your form to include the new fields. Make sure the fields you want to see there are included.

[![Mail Template](/images/mailtemplate.png)](/images/mailtemplate.png)

You can also check the Mail (2) template checkbox and edit the template of what someone who fills in a contact form will receive. It'll be called as auto-responder. This is useful to send acknowledgment to the person who submitted the form to let them know you have received their inputs from the form.

4. Save the changes.

5. Add the form to a page.

6. Check out the resulting form.

[![Preview Contact Form 2](/images/previewcontactform2.png)](/images/previewcontactform2.png)

#### Using Tags

Tags in Contact Form 7 allows you to design and customize your form. You can set a field to be a mandatory field, you can customize an input to a field to be a textbox or drop down list. Tags are pre-defined keywords enclosed in square brackets ([ ]).

[![Syntax of Form Tags](/images/formtagsyntax.png)](/images/formtagsyntax.png)

Note that order of those parts is important. Here is a list of most commonly used tags that can be used in your forms:

* _text, email, textarea_ - for text fields
* _checkbox, radio, select_ - for checkboxes, radio buttons and drop-down menu
* _file_ - for file uploading and attachment
* _captchac, captchar_ for reCAPTCHA
* _quiz_ for quiz
* _acceptance_ for acceptance checkbox
* _submit_ for submit button.

#### Modifying HTML

Let's see how the form will look if we edit some HTML and modify our form to be composed out of two columns. We can combine HTML with the tag code.

1. Go to **Contact** > **Contact Forms** and select to **Edit** your form again.

2. Alter the code to look like this:


```
<table>
	<tbody>
		<tr>
			<td>
				Your Name (required)
				[text* your-name]

				Your Phone Number
				[tel* your-phone "123-456-7890"]
			</td>
			<td>
				Select the time we should call you:
				[select time-to-call "Business hours" "Evening" "Morning" "As soon as possible"]

				Subject
				[text your-subject]
			</td>
		</tr>
	</tbody>
</table>

Your Message
[textarea your-message 40x2]

[submit "Send"]

```

3. Save the changes. Now there's two columns to the form.

[![Form with Two Columns](/images/twocolumnform.png)](/images/twocolumnform.png)

#### Modifying CSS

And, of course, you can also prettify the form with some CSS. Open your theme's style.css in a text editor of your choice and add the following code:

```
/** Contact 7 Form **/

form.wpcf7-form {
	text-align: center;
}

input#formname, #subject, #message {
	width:75%;
	margin-top: 5px;
	margin-bottom: 5px;
}

input#formname {
	margin-top: 20px;
}

input.wpcf7-form-control.wpcf7-submit{
	margin-bottom: 20px;
	background-color: #fcd2d2;
	width: 50%;
}

.wpcf7 select {
    border: 1px solid #fcd2d2;
    border-radius: 5px 5px 5px 5px;
    margin: 0;
    padding: 15px 10px 15px;
    width: 300px;
    z-index: 100;
}

input.wpcf7-form-control.wpcf7-submit input:hover[type="button"], input:hover[type="reset"], input:hover[type="submit"], .button:hover, .entry-content .button:hover {
	background-color: #f88888;
}
```

After you save the file and refresh the form it looks a bit different.

[![CSS Customization](/images/csscustomization.png)](/images/csscustomization.png)

### Summary

Well done! You have successfully added a new contact form to your website. Now you should be able to create a new contact form when you need it  and modify it to fit your needs.

### Lesson Wrap Up

![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with the Exercises and Assessment outlined above.
