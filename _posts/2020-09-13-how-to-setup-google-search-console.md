---
title: How To Set Up Google Search Console On Your Website? 
categories: SEO
excerpt: Set up Google Search Console easily on your website.
keywords: how to set up google search console
tags:
  - SEO
  - Google Search Console
toc: true
toc_sticky: true
author_profile: true
comments: true
header:
  overlay_color: '#000'
  overlay_filter: '0.5'
  overlay_image: /assets/images/posts/how-to-set-up-google-search-console/how-to-set-up-google-search-console.jpg
  teaser: /assets/images/posts/how-to-set-up-google-search-console/how-to-set-up-google-search-console.jpg
date: 2020-09-13
last_modified_at: 2020-09-13
---

<b>--------------------------------------------------------------------------------------------------------------------------------</b>

In this article, I will be showing the easiest method to set up Google Search Console successfully on your website. 

Before we begin, you need to have a Gmail account ready to set up Google Search Console. If you have one already, then you are good to go. Otherwise, please create one before going through the steps below. 

So, let’s get started.

## Set Up Google Search Console

 **Step 1:** Sign in to <a href="https://accounts.google.com/ServiceLogin/signinchooser?service=sitemaps&passive=1209600&continue=https%3A%2F%2Fsearch.google.com%2Fsearch-console%2Fwelcome&followup=https%3A%2F%2Fsearch.google.com%2Fsearch-console%2Fwelcome&flowName=GlifWebSignIn&flowEntry=ServiceLogin" target="_blank"> Google Search Console </a>using your Gmail. 
 
 **Step 2:** You will come across the UI as shown below. You just need to insert your website URL on URL Prefix and click Continue. 

 ![GoogleSearchConsoleWelcomeScreen](/assets/images/posts/how-to-set-up-google-search-console/welcome.png "Google Search Console Welcome Screen")
 
 **Steps 3:** Wait for some time until Google Search Console is verifying your website URL. Then, the Recommended verification method is presented to you, and if you scroll down, then other verification methods are also presented to you as shown below. 
 
 In this step, you need to download the HTML file. But, don’t click the Verify button yet. 

 ![VerificationMethod](/assets/images/posts/how-to-set-up-google-search-console/verify-ownership.png "Google Verification Method")

 ![VerificationMethods](/assets/images/posts/how-to-set-up-google-search-console/verification-methods.png "Google Search Verification Methods")
 
 **Step 4:** Now, upload the downloaded HTML file in your website root directory and click the Verify button. And, click the Done button. 
 
 Wait until Google Search Console verifies whether the HTML is successfully uploaded in your website root directory or not. Once it successfully verifies, then Google Search Console is installed on your website. 
 
 Now, you need to upload Sitemaps on Google Search Console so that Googlebot crawls and indexes your website effectively. 
 
 See the steps below to upload sitemaps to Google Search Console. 
 
 **Step 5:** First, you need to generate sitemap.xml before uploading it to the Google Search Console. You can find many online tools to generate sitemap.xml. I used <a href="https://www.xml-sitemaps.com" target="_blank"> XML-Sitemaps</a> to create sitemap.xml for my website. 
 
 You can also use the same tool to generate one for you. 
 
 a. Just insert your website URL and click start.

 ![XMLSitemaps](/assets/images/posts/how-to-set-up-google-search-console/xml-sitemaps.png "XML Sitemaps")

 b. Once the processing is finished, click the View Sitemap Details button.

 ![SitemapDetail](/assets/images/posts/how-to-set-up-google-search-console/sitemap-details-button.png "Sitemap Detail")

 c. Now, download your XML sitemap file.

 ![DownloadSitemap](/assets/images/posts/how-to-set-up-google-search-console/download-xml-sitemap.png "Download Sitemap")

 **Step 6:** Now, upload your XML sitemap file in your website root directory and click the Verify button. And, then click the Done button. (See step 3 above to click/find the Verify button.) 
 
 **Step 7:** Now, go to Google Search Console and click Sitemaps as shown below.
 
 ![SearchConsoleSitemap](/assets/images/posts/how-to-set-up-google-search-console/sitemaps.png "Search Console Sitemap")
 
 **Step 8:** Now, add a sitemap by typing “/sitemap.xml” inside the sitemap URL field and click the Submit button as shown below. 

 ![AddSitemap](/assets/images/posts/how-to-set-up-google-search-console/sitemap-upload.png "Add Sitemap")

 Then wait for the process to end. Once the verification process is finished, it shows success as shown below. 
 
 ![SitemapSuccess](/assets/images/posts/how-to-set-up-google-search-console/sitemap-success.png "Sitemap Success")
 
 This means Google Search Console is now successfully installed on your website. 
 
## Set Up Google Search Console For Wordpress

 Repeat up to step 2 the same as above. 
 
 **Step 3:** Go to the Other Verification Methods the same as the above step 3 and click HTML tag. 
 
 **Step 4:** You will be given a meta tag as shown below. Now copy the meta tag, but don’t click the Verify button yet. 
 
 ![HTMLTag](/assets/images/posts/how-to-set-up-google-search-console/html-tag.png "HTML Tag")
 
 **Step 5:** Now, go to your WordPress dashboard and click Plugins. 
 
 ![Plugins](/assets/images/posts/how-to-set-up-google-search-console/plugins.png "Plugins")
 
 **Step 6:** Now, click Add New button and search for Headers and Footers Plugin. Install one plugin and activate it. I am using **Insert Headers and Footers** by WPBeginner. 
 
 **Step 7:** Now from the Dashboard menu, hover over or click the Settings and click Headers and Footers plugin. 
 
 ![HeadersandFootersPlugin](/assets/images/posts/how-to-set-up-google-search-console/header-footer-plugin.png "Headers and Footers Plugin")
 
 **Step 8:** Now, paste your HTML tag inside the header section of the Headers and Footers plugin as shown below and click the Save button. 
 
 ![HeaderSection](/assets/images/posts/how-to-set-up-google-search-console/header-section.png "Header Section")
 
 **Step 9:** Now click the Verify button and then click the Done button. (See step 4 to click/find the Verify button.) 
 
 **Step 10:** Now, you need to upload Sitemap XML on Google Search Console. So, go to your WordPress Dashboard and click the SEO plugin that you are using. I am using the Rank Math SEO plugin. 
 
 If you don’t have one, then go to the plugins and install and activate one SEO plugin. I would recommend either Rank Math or Yoast SEO plugin. 
 
 **Step 11:** Now go to your Wordpress Dashboard and click the SEO plugin you are using and then click Sitemap settings. 
 
 ![SitemapsSettings](/assets/images/posts/how-to-set-up-google-search-console/sitemap-settings.png "Sitemaps Settings")
 
 **Step 12:** Now, click the Sitemap URL as shown below. 
 
 ![SitemapsURL](/assets/images/posts/how-to-set-up-google-search-console/sitemaps-url.png "Sitemaps URL")
 
 **Step 13:** Copy the URL from the URL section of your browser. 
 
 ![SitemapURL](/assets/images/posts/how-to-set-up-google-search-console/sitemap-url.png "Sitemap URL")
 
 If you are using the Yoast SEO plugin, then click Yoast SEO plugin from the WordPress Dashboard, click General, and then Features. Now look for the XML sitemaps and click on the “?” symbol. Then click “See the XML SItemap” link. You will come across the same UI as shown in the above image in step 13. Now copy the URL and follow the steps given below. 
 
 If you are using other than these SEO plugins, then go to the SEO plugins you are using and look for the XML SItemap and copy the URL and follow the steps given below. 
 
 **Step 14:** Now, go to your Google Search Console and click Sitemaps.
 
 ![SearchConsoleSitemaps](/assets/images/posts/how-to-set-up-google-search-console/sitemaps.png "Search Console Sitemaps")
 
 **Step 15:** Paste the copied URL in the “Add a new sitemap” section and click submit. 
 
 ![AddSitemap](/assets/images/posts/how-to-set-up-google-search-console/add-sitemap.png "Add Sitemap")
 
 Once, Google Search Console verifies the uploaded sitemap.xml, it shows a success message as shown below. 
 
 ![SitemapsSuccess](/assets/images/posts/how-to-set-up-google-search-console/sitemap-success-msg.png "Sitemaps Success")
 
 This means Google Search Console is now successfully installed on your WordPress website. 
 
 Soon you will be able to see the performance of your website.
 
**In Conclusion**

This is how you set up Google Search Console on your website. 

It might be a bit lengthy but I hope this article helped you. 

Please share this article if it helped you. 

Thank You.