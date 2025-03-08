# Web-Text20 Dataset

## Overview

The **Web-Text20** dataset is a curated collection of textual content spanning 20 diverse categories, each sourced from reputable websites. This dataset is designed to facilitate research and development in areas such as text classification, natural language processing, and machine learning.

## Categories and Sources

| Category            | Websites |
|--------------------|----------|
| **Technology News** | [TechCrunch](https://techcrunch.com/), [The Verge](https://www.theverge.com/), [Wired](https://www.wired.com/) |
| **World News** | [BBC World](https://www.bbc.com/news/world), [Al Jazeera](https://www.aljazeera.com/), [AP News](https://apnews.com/hub/world-news) |
| **Sports** | [ESPN](https://www.espn.com/), [Sky Sports](https://www.skysports.com/), [BBC Sport](https://www.bbc.com/sport) |
| **Entertainment** | [Variety](https://variety.com/), [Hollywood Reporter](https://www.hollywoodreporter.com/), [EW](https://ew.com/) |
| **Science** | [Scientific American](https://www.scientificamerican.com/), [Phys.org](https://phys.org/), [Live Science](https://www.livescience.com/) |
| **Health** | [WebMD](https://www.webmd.com/), [Mayo Clinic](https://www.mayoclinic.org/), [Health](https://www.health.com/) |
| **Business** | [Forbes](https://www.forbes.com/), [CNBC](https://www.cnbc.com/), [Financial Times](https://www.ft.com/) |
| **Politics** | [NPR Politics](https://www.npr.org/sections/politics/), [BBC Politics](https://www.bbc.com/news/politics), [FiveThirtyEight](https://fivethirtyeight.com/) |
| **Environment** | [National Geographic](https://www.nationalgeographic.com/environment/), [EcoWatch](https://www.ecowatch.com/), [Treehugger](https://www.treehugger.com/) |
| **Education** | [EdWeek](https://www.edweek.org/), [Inside Higher Ed](https://www.insidehighered.com/), [The Chronicle](https://www.chronicle.com/) |
| **Travel** | [Lonely Planet](https://www.lonelyplanet.com/), [Rough Guides](https://www.roughguides.com/), [Condé Nast Traveler](https://www.cntraveler.com/) |
| **Food** | [Epicurious](https://www.epicurious.com/), [AllRecipes](https://www.allrecipes.com/), [Bon Appétit](https://www.bonappetit.com/) |
| **Fashion** | [Vogue](https://www.vogue.com/), [Elle](https://www.elle.com/), [Harper's Bazaar](https://www.harpersbazaar.com/) |
| **Automotive** | [Car and Driver](https://www.caranddriver.com/), [MotorTrend](https://www.motortrend.com/), [Autocar](https://www.autocar.co.uk/) |
| **Real Estate** | [Realtor](https://www.realtor.com/news/), [Redfin](https://www.redfin.com/blog/), [Trulia](https://www.trulia.com/blog/) |
| **Personal Finance** | [NerdWallet](https://www.nerdwallet.com/), [Bankrate](https://www.bankrate.com/), [Investopedia](https://www.investopedia.com/) |
| **Gaming** | [IGN](https://www.ign.com/), [GameSpot](https://www.gamespot.com/), [Kotaku](https://kotaku.com/) |
| **Parenting** | [Parents](https://www.parents.com/), [BabyCenter](https://www.babycenter.com/), [What to Expect](https://www.whattoexpect.com/) |
| **DIY and Crafts** | [Instructables](https://www.instructables.com/), [Apartment Therapy](https://www.apartmenttherapy.com/), [DIY & Crafts](https://www.diyncrafts.com/) |
| **Fitness** | [Bodybuilding](https://www.bodybuilding.com/), [Men's Health](https://www.menshealth.com/fitness/), [Shape](https://www.shape.com/fitness) |

## Dataset Creation Process

The dataset was constructed using web scraping techniques to extract relevant textual content from the aforementioned websites. The process involved:

1. **Web Scraping:** Utilizing Python libraries such as `requests` and `BeautifulSoup` to fetch and parse HTML content.

2. **Data Extraction:** Extracting pertinent information, including article titles, content, and publication dates.

3. **Data Cleaning:** Implementing Natural Language Processing (NLP) preprocessing techniques to remove HTML tags, punctuation, and stop words.

4. **Data Storage:** Organizing the cleaned text data into separate text files for each category.

## Usage

Researchers and developers can employ the Web-Text20 dataset for various applications, including but not limited to:

- Training and evaluating text classification models.
- Conducting sentiment analysis across different domains.
- Exploring topic modeling and clustering techniques.
- Enhancing information retrieval systems.


