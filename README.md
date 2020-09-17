<p align="center">
  <a href="https://jannisbrandt.de/">
  <img src='http://jannisbrandt.de/jb-logo.png' width="100" alt="Pattern Lab Logo" style="max-width: 100%;" />
  </a>
</p>

<h3 align="center">a plugin for custom fields in your magento newsletter subscription </h3>

<p align="center">
With this magento plugin you have the option to add/show some custom fields like firstname, lastname and salutation in the magento newsletter-subscription.
  <br>
  <a href="mailto:sayhello@jannisbrandt.de">Report bug</a>
  ·
  <a href="mailto:sayhello@jannisbrandt.de">Request feature</a>
  ·
  <a href="https://devdocs.magento.com/">Magento Documentation</a>
  </p>


## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```text
NewsletterSubscription/
├── registration.php	
├── Subscriber.php	
└── etc/
	├── db_schema.xml
	├── di.xml module.xml
	├── module.xml
        
└── view/
    ├── adminhtml/
    │   ├── frontend/
    		├── newsletter_subscriber_block.xml
    │  
    │ 
    └── frontend/
        ├── templates/
        	├── subscribe.phtml
        

```


## What you have to do? 

<p align="center">
1. Change the path to your plugin-file: in this example I use Module_
2. Create a Content-Page in Magento
3. In the content-area you have to add your custom template: {{block class="Magento\Newsletter\Block\Subscribe" template="Module_FewsletterSubscription::subscribe.phtml"}}
</p>
