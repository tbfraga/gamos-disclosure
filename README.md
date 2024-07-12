# gamos-disclosure
Dissemination of work carried out by GAMOS, such as publications, videos and reports. 

As cópias e distribuições dos arquivos disponibilizados neste diretório, devem respeitar à licença Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License.

Por essa licença, é permitido fazer download e compartilhamento dos documentos disponibilizados neste diretório desde que atribuam crédito aos autores originais, e sem que possa alterá-los de nenhuma forma ou utilizá-los para fins comerciais. 

A licença na íntegra pode ser consultada no documento LICENSE, ou através do site: https://creativecommons.org/licenses/by-nc-nd/4.0/legalcode

*** Work in progress:

-->> Development of local search heuristics based algorithms to solve the production planning problem (p-batch s-batch) in a plastic bag production factory.

    *** I am thinking of using the particle collision heuristic, which was adapted by me (in my doctorate), to solve discrete problems, from the particle collision method, developed by Prof. Wagner Sacco.
    *** Other heuristics or new ideas may be developed, tested and applied.
    
    *** What's done:
        --> Problem identification and proposition of an exact analytical method for the multiproduct p-batch processing time maximization (MBPTM) problem.
        
    *** Next steps:
        --> In the case of the problem dealt with in this project, it is necessary to make the production schedule for several days. It is also necessary to propose solutions that are generated dynamically.
        --> So, the next small step to be taken is the expansion of the initially proposed solution to the MBPTM problem considering a multiperiod and dynamic scenario.
        --> This method will then be applied iteratively as part of the algorithm that will be developed to solve the problem of production planning in extrusions, in the studied company.
    
-->> Creation of a compound algorithm to demand forecasting with different demand patterns.

    *** When I created the demand forecasting project in  August 2019, I was reading scientific articles and I had the idea of working with compound methods, using standard forecasting method for normal data and working with other methods (such as neural networks) to treat the change in the forecast around the leftover. I thought of this technique and left the idea aside because I was busy with other things. At the moment I am thinking of a new idea of using the data partition. But for now it's just an idea. Soon I will be working with the development of a demand forecasting method. I hope it works. 

    *** The idea is to partition the data so that lumpness (and other Willians paramenters) decreases, by decreasing the coefficient of variation (and other paramenters), when possible, if possible. Thus, according to Willians's classification, it may be possible to bring the data into the normal standard.

    *** The question is: is it possible to decrease, through the data partition, the 'lumpiness' of the demand, the mean number of lead times between demands, and the lead time variance, acording to Willians classification method ? I believe the answer is yes. So I intend to work on this in the coming months.

    *** Another idea that begins to emerge in my mind, when analyzing the data, consists in identifying patterns using different scales defined for periods (i.e., day, week, month, year).
        --> when analyzing longtime data, it is necessary to verify if an old standard is maintained or modified for recent dates.
        --> for the studied region it is certainly necessary to work with information that goes beyond the data.
        --> then it is possible that it is necessary to work with causal methods, along with other standard methods. 
        --> mabe this could solve the forecast problem for the studied case.

    *** What's done:
        --> proposal of a new approach for multicriteria ABC classification with analytical hierarchy process.

    *** Next steps:
        --> portfolio study, considering ABC classification, demand patterns, and methods used for demand forecasting.

-->> Elaboration of a scientific article for publication of the particle collision applied to discrete problem solving (part of my doctoral work).

-->> Elaboration of scientific article for the publication of the undergraduate work of my guiding Edwedja. 
    
    *** In this work the student modeled the chain stock problem and created an optimization algorithm for the problem based on the simulated annealing method.

-->> COPSolver: continue software development along with works development.
    
    *** COPSolver is currently gaining new libraries for ABC multicriteria classification (with Saat's Analytical Hierarchy Process method) and identification of demand patterns with the Willians demand partition method.

-->> I will be focusing on the completion (if possible) and the publication of all work ongoing, more than on the development of new works.

*** New project ideas

--> game MY LIFE

    *** objective of the game is bring people back to life.
    *** not to transforme life in game, but mabe it will. 

    *** create a new game with the following aspects:
    *** single user offline interface;
    *** multiuser online interface;
    *** enviromente where user can define the task;
    *** tasks must be tasks from real life;
    *** user create a scenario like his real life (home, work, etc)
    *** user define his tasks as a scheduling;
    *** game creates tasks on enviroment scenario;
    *** game provides score for acomplish the tasks;
    *** user mark the start time for each task;
    *** user go to real life to perform its own task;
    *** user come back to game to finish quests and recive bonifications;
    *** game evaluate tasks execution time and help to plan / schedule and acomplish real life tasks.

    *** as one of the bonifications of a day of tasks acomplished user has acces to a multiuser interface where user can talk, change material, disclose multiuser tasks, etc.

    *** the game can provide real bonifications as ticket for cinema, etc.
    *** on multiuser interface gamers can combine multiuser real tasks.

    *** user data stays on his own app. Data must be not stoqued or used for any other ends. Privacy must be the main game rule.

-->> Semester evaluation method for disciplines of the Production Engineering course, based on the dynamics adopted in selection processes of multinational companies.

    *** This idea just came up.
    *** When students are about to graduate, they can participate in selection processes for the function of trainee in multinationals.
    *** In the selection process, both practical knowledge of the students and behavioral aspects are evaluated.
    *** These assessments are done through group dynamics.
    *** Students need to apply their knowledge gained in their training to problem solving cases.

    *** Looking at these selection processes, it may be possible to think of a semester evaluation model (of production engineering course subjects) based on the following aspects:

    *** the assessment activities are group dynamics in which students must apply the knowledge acquired throughout the semester at displina to solve problems cases;
    *** students of courses in the areas of human resources are invited to participate in the construction of dynamics and evaluations;
    *** an evaluation board is created to evaluate acquired knowledge as well as behavioral aspects.
    *** the evaluation board must create the dynamics so that at least 70% of the content presented in the discipline is necessary to solve the problem;
    *** in assessment games, each group of students will need to use theoretical methods and concepts to solve a problem.
    
    *** For example, a dynamic can be created in which a fictitious factory has working capital problems, and it is necessary to reformulate a certain industrial process to improve the company's profit;
    *** It is necessary that there is enough data so that students can apply their knowledge in order to try to solve the problem.
    
    *** But I have a huge difficulty not to get involved with new projects. I'll try.
