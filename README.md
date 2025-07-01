# customer_insights_extractor
This is a n8n workflow for extracting cutomer inights from customer queries

# How to use this 
1. Import the json file using the "Import from File" feature. 
2. In the Gmail Node, connect with your Gmail account using credential. Set any filtering you need to put for example emails coming from your support email.
3. In the Edit Field node, change the IssueTypeCanonicalLabel to the specific issue type categories for your product. Currently the categories are specific for an apparel subscription product that I worked on. 
4. Set your OpenAI node credentials.  
5. Run the workflow. It will output the biggest customer painpoint along with the summary text.
