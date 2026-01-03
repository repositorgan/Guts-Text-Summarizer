# Guts-Text-Summarizer
> Reads a text (.txt) file and consolidates it into an easy to read 1-2 sentence summary. Performance spinner UX.

**Why do we care?**

_Summarizer is perfect for analysts, developers, lawyers, and teachers._

_Saves time and money in labor of interpretating larger bulk text data._

_Provides option to save a new .txt file, client product._

**Usage**

**Produce Summary**
_python -m summarizer example.txt_

**Verbose Mode**
_python -m summarizer example.txt -v_

**Save new file**
_python -m summarizer example.txt -o output.txt_

**How it Works**
 _______________________________
|    INPUT TEXT, (.txt), FILE   |
|-------------------------------|
| Full length analysis or report|

                |
                V
                |
                V
                |
                V
 _________________________________
|      SUMMARIZER PROCESS        |
|--------------------------------|
|   1. Split text into sentences |
|   2. Count keyword frequencies |
|   3. Skips common words        |
|   4. Score each sentence       |
|   5. Pick top 1-2 sentences    |

                |
                V
                |
                V
                |
                V
 __________________________________
|           FINAL OUTPUT           |
|----------------------------------|
|     Top scoring 1-2 sentences    |
|        Keywords identified       |
|       Option to save output      |

**Installation**
Clone the repository:
