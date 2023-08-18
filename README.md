# AI Academy Semester 1 Capstone Project


# Project Overview:

## Business Understanding: 

§ Stakeholders/ Key business Question: 

   ► Computing Vision is in a competitive industry and is looking to expand its business by creating original video content. The company has decided to create a new movie studio, but they don’t have much background in creating movies. As         Deloitte professionals, we are responsible for exploring what types of films are currently doing the best at the box    office using different samples of available data. After conducting extensive data analysis, our team will translate        those findings into actionable insights that the head of Computing Vision's new movie studio can use to help decide what type of films to create.

## Data Understanding & Analysis:

#### Source and Description of Data:
§ IMDB - imdb.com:
        ► Database that contains information from the IMDB website, including general movie information. The data was collected within the SQL database, using the movies_basics, movie_ratings, directors, and persons tables and joined with the respective movie IDs

§ Numbers & TheMovieDB:
        ► Datasets that contain information about movie popularity, movie budget, and total grossing information from themoviedb.org and the-numbers.com.

§ Finalized Data Frame used for Analysis:
        ► Finalized data frame combines the information from these two sources of data, as well as profit calculations.

#### Results & Recommendations:
§ Genre Prioritization: 
        ► Based on the data analysis, Computing Vision should prioritize Animation, Adventure, and Sci-Fi films 
        ► The profits for these genres based on the analysis are the following:
            ► Animation: $250 million
            ► Adventure: $229 million
            ► Sci-fi: $202 million

§ Directorship Prioritization:
        ► Top 8 directors (produced 5+ movies) that have the highest average gross profit across movies they directed *doesn't  take genre into account* 
        ► Top 3 Directors:
            ► Joss Whedon $1.46 billion
            ► Anthony Russo $1.30 billion
            ► Kyle Balda $1.10 billion
        ► Directorship recommendations based on genre: 
            ► Animation: Brad Bird
            ► Adventure: Colin Trevorrow
            ► Sci-Fi: Colin Trevorrw

§ Runtime Optimization:
        ► Optimal runtime for films: Between 140 and 180 minutes

#### Visualizations:
  § Why focus on profit:

 
 
 
 § Genre Prioritization:
 ![image.png](attachment:image.png)
 

 § Directorship Prioritization:
 ![image-2.png](attachment:image-2.png)
 
 
 

## Statistical Communication:

#### Results of statistical inference:
§ Testing Significance of Runtime on Worldwide Profit
        ► When conducting statistical testing, we found that there is a significance and runtime does impact worldwide profit
        
§ What Runtime Range Maximizes Profit Worldwide?
        ► The runtime dataset was divided by standard deviations from the average runtime. We calculated statistical insights including the mean of the profit within each runtime range and compared it against other ranges. On average, a runtime of 140 (approximately) to 180 minutes has the highest worldwide profit ($295 million) across all genres. While the number of datapoints for each respective range vaired, we looked at other statistical calculations such as percentiles and maximum values to reinforce our conclusions.

#### Interpretation of these results in the context of the problem
§ The Runtime Value Matters
        ► For Computing Vision to maximize profit, they need to account for runtime in order to do so. The results of our significance result proved that the runtime value does indeed impact whether or not a movie is profitable worldwide, regardless of genre.
        
§ Optimal Runtime Range is 140 to 180 minutes
        ► An actionable item for Computing Vision to maximize profit would be creating a project that is within 140 to 180 minutes. A note to keep in mind is that this value also depends on Computing Vision's production budget. This recommendation is based solely on the given data set.


## Navigating the repository:
§ Branches
   ► There are two types of branches, the main/production branch and the development branches
   ► The main branch contains all of the finalized code, whereas the development branch contains each respective team member's work
   ► Commits can be viewed [here](https://github.com/abwilliamss/AIAcademy-capstone/commits)

§ File Structure
   ► AI Academy Capstone Project.ipynb is the finalized notebook file
   ► Readme.md contains the description of the project
   ► .gitignore contains all of the files that git will not track or commit, typically large or irrelevant files

## Conclusion:
§ Computing Vision Business Goal: Increase Profitability using 3 recommendations
        ► Genre Prioritization: Animation, Adventure, Sci-Fi
        ► Directorship Prioritization:Joss Whedon, Anthony Russo, Adam Green or  Brad Bird for an Animation film, and Colin Trevorrow for an Adventure or Sci-Fi film 
        ► Runtime Optimization: Between 87.3-122.7 minutes



## Resources:
§ [Computing Vision Business Recommendations Presentation](https://amedeloitte-my.sharepoint.com/:p:/g/personal/rvanjani_deloitte_com/EbAjkbM5Av5Es9vSwdEFIgUBqqthI59BTML3DVKlw5PYpA?email=kbilgere%40deloitte.com&e=mfa8Y8) 

§ Data Sources:
        ► [IMDB](https://www.imdb.com/)
        ► [TheMovieDB](https://www.themoviedb.org/) 
        ► [The Numbers](https://www.the-numbers.com/)


