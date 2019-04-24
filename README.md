
# bingcogserv
Process to feed pictures from bing into a customvisio project .
# Variables used
 
>  **Bing Variables:**
* search_url is the Bing url to used extract images from the Bing API
> Example search_url = "https://api.cognitive.microsoft.com/bing/v7.0/images/search"

* search_term is the text that Bing will perform the search
>Example search_term = "person" is equivalent to [https://www.bing.com/images/search?q=person](https://www.bing.com/images/search?q=person)

* tagname is how the pictures are going to be tagged on the customvisio model
>Example tagname = "person" 

* bing_subscription_key  is the bing subscription key that can be found on the Azure UI

>  **Customvision Variables:**
* ENDPOINT is basically the region of your customvision service
>Example ENDPOINT="https://southcentralus.api.cognitive.microsoft.com" is a customvision service based on **southcentralus**
* project is the project Id of your customvision service and can be retrieve from the customvisio webpage or the Azure portal
* training_key  is the custom visio key fro training subscription key that can be found on the Azure UI or customvisio UI.
