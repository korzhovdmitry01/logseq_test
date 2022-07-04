project_name:: [[Data Sources]]
status:: [[Draft]] 
assing:: [[Dmitry Korzhov]]
relation_task:: ((62c2df03-bd62-4eab-9849-383daa1f0419))

- Description of data sources need to include sections. #loc_data_sources_structure_description
  collapsed:: true
	- General and integration description (information about tool and sync);
	- Features (description of the features that they are supported and their description);
	- Setup Guide (step-by-step and easy-to-use instructions on how to set up sync with many photos and examples);
	- Schema information (a schematic representation of how the process works);
	- Release Notes (description of the all changes in sync setting).
- The description must meet three key criteria: comprehensive, understandable and searchable.
  collapsed:: true
	- Comprehensive means that all information about connecting, using, updating, etc. must be inside one place in the knowledge base;
	- Understandable means that the information must be designed and written in such a way that a user of any level can understand it and make connections to the data source;
	- Searchable means that any information can be easily found either by searching or by using the built-in navigation.
- Overview 20 syncs from [Jira tasks](https://improvado.atlassian.net/browse/IMD-22023).
  collapsed:: true
	- First, we need to check how are these 20 syncs made in Fivetran (the sources are arranged in order of popularity).
	  collapsed:: true
		- Facebook Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/facebook-ads)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/facebook-ads)
			- [description in Funnel;](https://help.funnel.io/en/articles/3741666-how-to-connect-facebook-ads)
		- Google Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/google-ads)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/google-ads)
		- Google Universal Analytics
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/google-analytics)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/google-analytics) (?)
			- [description in Funnel;](https://help.funnel.io/en/articles/56807-connect-your-google-analytics-data) (?)
		- Twitter Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/twitter-ads) (?)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/twitter-ads)
		- Bing Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/microsoft-advertising) (?)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/microsoft-advertising) (?)
		- Facebook Pages
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/facebook-pages)
		- LinkedIn Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/linkedin-ads) (?)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/linkedin-ads)
			- [description in Funnel;](https://help.funnel.io/en/articles/4794440-how-to-connect-to-linkedin)
		- Pinterest Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/pinterest-ads)
		- Snapchat Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/snapchat-ads)
		- TikTok Ads
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/tiktok-ads)
		- Instagram Organic
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/instagram-business) (?)
		- Google Search Console
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/google-search-console)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/google-search-console)
		- Amazon Advertising
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/amazon-ads) (?)
		- Instagram Stories and Mentions;
		- Youtube Organic
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/youtube-analytics/) (?)
			- [description in Funnel;](https://help.funnel.io/en/articles/4210106-how-to-connect-to-youtube) (?)
		- Google Campaign Manager
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/google-campaign-manager-360)
		- Google Display & Video 360
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/google-display-and-video-360)
		- Shopify
		  collapsed:: true
			- [description in Fivetran;](https://fivetran.com/docs/applications/shopify)
			- [description in Stitch Data;](https://www.stitchdata.com/docs/integrations/saas/shopify)
		- LinkedIn Organic;
		- Google Campaign Manager (by Advertisers).
		- (?) — means that the description partially corresponds [to the task in Jira.](https://improvado.atlassian.net/browse/IMD-22023)