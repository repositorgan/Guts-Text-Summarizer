# Guts-Text-Summarizer
> Reads a text (.txt) file and consolidates it into an easy to read 1-2 sentence summary. Performance spinner UX. Base for package expansion.

**Why do we care?**

_Summarizer is perfect for analysts, developers, lawyers, and teachers._

_Saves time and money in labor of interpretating larger bulk text data._

_Provides option to save a new .txt file, client product._


**Usage**


<img width="1455" height="813" alt="full length text" src="https://github.com/user-attachments/assets/46d46a2c-6040-4510-abe3-24edec0f286f" />


**Produce Summary**
_python -m summarize example.txt_

<img width="1462" height="272" alt="Summary of Disney Wikipedia" src="https://github.com/user-attachments/assets/f202608f-228d-4245-bf8c-b77ef47b7762" />

**Verbose Mode**
_python -m summarize example.txt -v_

<img width="1458" height="307" alt="verbose Summary of Disney Wikipedia" src="https://github.com/user-attachments/assets/a754f2be-c136-4789-9d8b-5b5710eab437" />

**Save new file**
_python -m summarize example.txt -o output.txt_

<img width="1460" height="301" alt="Summary of Disney Wikipedia saved" src="https://github.com/user-attachments/assets/5c9f2abf-52a3-487c-bd04-3ca8334f21ba" />



<img width="757" height="33" alt="Summary saved" src="https://github.com/user-attachments/assets/c2ad1eb0-b163-4385-87dc-9be02859a2b7" />

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
