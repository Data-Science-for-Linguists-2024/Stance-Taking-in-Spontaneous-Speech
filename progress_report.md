Maya Asher, mia83
# Progress Report - 2/13/24
I've made my project plan, read "Stance and Stancetaking" by Dr. Scott Kiesling, and started processing my data in a Jupyter Notebook. 

# 1st Progress Report - 2/23/24
## Summary
My data was in the form of transcripts and needed a lot of cleaning in order to have a tokenized and searchable data frame. I cleaned out the timestamps and non-alphabetical characters from the text and compiled it all into a pandas data frame, which can be found in my [Jupyter Notebook](https://github.com/Data-Science-for-Linguists-2024/Stance-Taking-in-Spontaneous-Speech/blob/main/processing_sbcsae.ipynb). I then did some basic stats and am now ready to actually perform my actual analysis. 

My next steps will be to identify my target words formulate my hypothesis. I can then search for the words and perform the analysis. 

## Sharing Plan
The SBCSAE license is a [Creative Commons Attribution-No Derivative Works 3.0 United States License](https://creativecommons.org/licenses/by-nd/3.0/us/), which clearly states that I am able to "copy and redistribute the material in any medium or format for any purpose, even commercially" as long as appropriate credit is given. Since there appear to be very few limitations on data sharing with this corpus, I have uploaded the entire data set I'm using (which includes 43/60 files). 

Before working with the data, I had to convert all the files to UTF-16, so I have uploaded those UTF-16 files rather than the original ones I downloaded from the UCSB website. This license does not allow derivative works, but I don't believe changing the encoding of the file is enough to consider it remixed, transformed, or built upon. 

In the directory labeled `data_samples`, I have included the 43 TRN files (in UTF-16) and a TXT file called `license_info` in compliance with the license's requirement of providing appropriate credit. 

# 2nd Progress Report - 3/22/24
## Summary
I have completely redone my data processing, which can be found in [this new notebook](https://github.com/Data-Science-for-Linguists-2024/Stance-Taking-in-Spontaneous-Speech/blob/main/reprocessing_sbcsae.ipynb). Rather than breaking apart and stripping my data, I am going to keep them in their original transcript format with the time stamps and non-alphanumeric characters. While this will make things like token count and searching more difficult, it will be more convenient for my discourse analysis purposes. However, I am still running into formatting issues with my data frames, so those will need to be resolved before moving forward.

## Sharing Plan
My sharing plan remains the same as I have listed in my first progress report. 

## Licensing
I chose to use a MIT license because it allows people to pretty much do whatever they want with my code and does not hold me liable for their actions. I am very supportive of making resources free and accessible, so I am happy to let other people use my code if it suits their needs. The only condition with this license is that the user would have to preserve the copyright and license notices. 

My data has a more restrictive license because it doesn't allow the creation and distribution of derivatives, but that is documented elsewhere in my repo so users would also have to follow those rules if they are planning to use the data too. 

# 3rd Progress Report - 4/9/24
## Summary
I continued editing my [data processing notebook](https://github.com/Data-Science-for-Linguists-2024/Stance-Taking-in-Spontaneous-Speech/blob/main/reprocessing_sbcsae.ipynb) and began my [analysis notebook](https://github.com/Data-Science-for-Linguists-2024/Stance-Taking-in-Spontaneous-Speech/blob/main/analyzing_sbcsae.ipynb). Due to weird spacing errors, I unfortunately had to manually go through about half of the files and make minor adjustments (like removing an extraneous tab), so I have reuploaded my [data samples](https://github.com/Data-Science-for-Linguists-2024/Stance-Taking-in-Spontaneous-Speech/tree/main/data_samples). My data is now in its final form and the only things left to worry about are the analysis specifics and the presentation. I am having a sparsity issue with current target words, so I may try to find substitutes.

I also added a new markdown file called [file_summary](https://github.com/Data-Science-for-Linguists-2024/Stance-Taking-in-Spontaneous-Speech/blob/main/file_summary.md) that has descriptions of each transcript that I included in my analysis (43 out of 60). I took the descriptions straight from the SBCSAE website (cited of course) and I think this will be a helpful resource for my analysis and for viewers of my repo.

Aside from the notebooks, I did a lot of research on stance and stancetaking so that my analysis can be as factual and interesting as possible. There has been a decent amount of corpus work done regarding stance, but they are very niche and take a while to understand, especially since I am not a big fan of syntax!

## Action Items
1. Figure out new target words and update the notebooks accordingly
2. Analyze the resulting data
3. Figure out how to add value (still unclear about this)
4. Work on presentation for next week
