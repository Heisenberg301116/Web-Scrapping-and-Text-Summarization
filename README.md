# Web-Scrapping-and-Text-Summarization
Scrapping a website using Beautiful Soup and summarizing the content of a webpage or a section of a web page using OpenAI’s GPT-3 powered TL;DR summarization tool. 

************************************************************************************************************************************************************************

Important: 
1) The application accepts test cases only through command line.
2) Make sure your presently working directly in the terminal is same as the one where main.py file is present before running the below test cases !!!

************************************************************************************************************************************************************************

Testcases:

Testcase 1:
python main.py --link "https://en.wikipedia.org/wiki/India" --keywords "Biodiversity" --model "text-ada-001"

Testcase 2:
python main.py --link "https://en.wikipedia.org/wiki/India" --keywords "Biodiversity" --out "india-biodiversity-ada-summary.json" --model "text-ada-001"

Testcase 3:
python main.py --link "https://en.wikipedia.org/wiki/India" --keywords "Biodiversity" --out "india-biodiversity-davinci-summary.json" --model "text-davinci-003"

Testcase 4:
python main.py --link "https://en.wikipedia.org/wiki/India" --keywords "Biodiversity" --out "india-biodiversity-gpt-3.5-summary.json" --model "gpt-3.5-turbo"
