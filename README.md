# llm-archives

### Instructions

Click the "Use this template" button for this repository and choose "Create a new repository". You can give it the same name (llm-archives).

Once it's ready, go to [Groq](https://console.groq.com/keys) and follow the directions to get an API key. You'll need to login (or create an account if you don't have one).

Copy the API key value and then click on the Settings of your GitHub repository and click on "Secrets and variables" on the left side, then choose "Codespaces"

Click the green "New Repository Secret" button and paste your API Key into the "Secret" box, then put GROQ_API_KEY in the Name box above it. Click "Add Secret" and click on the name of the repository to return to the main page.

From there, click the green "Code" button and create a new Codespace in the Codespaces tab.

In the Terminal type the following: pip install requests groq and hit enter.

Then type: python get_stories.py

You should see a file called cns_maryland_posts.json appear. Let's look at it. It contains some details of the past 10 CNS stories.

Back in the Terminal, type: python entity_extraction.py and watch the output.

### Evaluation for JOUR389W

PUT YOUR EVALUATION HERE
I got all the names mentioned in the story I chose and I think this exercise was very effective.
Gathering data like this is a good way to develop some sort of database of sources. The output from this exercise not only listed the people mentioned in this story, it included a description for each of them the same way the reporter captured these in the story. If, in future, a reporter wants to do a story that is similar to this, it will be easier to come back here and find a source that can give me more information. Having an archives of sources can also help with future investigations.
Using this exercise as an instance, the way I think about the usefulness of this in a newsroom is:
Let's assume it happens in future that Eniku Aghogho Tayo, described in this exercise as the owner of an abandoned vehicle where children were found dead, is caught for trafficking children. If we have a source database at the ICIR where I can search for Eniku Aghogho Tayo, I already have relevant background information without doing much. It already creates a connection bvetween Tayo and bad things happening to children. And this is information I might not have by just searching the internet, depending on how many years have gone by between this story and the hypothetical future story.
Also, it could be an entirely different scenario and I might need sources for a story in Agyaragu community, which I have never heard of. Searching for the community on this type of database already shows me a list of people that live here. It might not be too much, but it is a nice place to start.