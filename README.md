![](https://listmonk.itmorelia.com/uploads/1CE5qnRC0nOaXBHYKZSBIMw.png)

**Dear {{ .Subscriber.Name }}** ,📚📝✨

As we explore regression analysis, it's time to get hands-on and explore the Ordinary Least Squares (OLS) method. Your upcoming **lab delivery session** will provide a valuable opportunity to apply and demonstrate the knowledge and skills you acquired in the previous lab session. Now, let's take a look at the **tasks** that are waiting for you:

*   **Deadlines** 📅: Always be aware of the **delivery and presentation** date and time. **Mark them in your calendar or planner**. It’s a good idea to set a reminder a day or two before the due date as an extra precaution. The session deadline is **September** **18th at 12:00 pm - 13:00 pm.**
*   **Follow the Format** 📄: Please ensure that your team follows the specified format. This is a particular Jupyter file with defined sections ([use the previous LaTeX structure, but in Markdown](https://blog-gmarx.itmorelia.com/posts/reports@TrackLink)). 
*   **Double-Check Your Work** 🔍: Before submission, review your answers. Make sure you’ve completed all the **tasks for students**. Proofread for spelling and grammatical errors.
*   **Tasks for the OLS Lab Session** ✅: To ensure you conclude all assigned tasks for this lab session, create a list of **Todos** and mark each task as completed as you progress. The tasks are listed and detailed below:
    *   ☑️ **Theoretical Background and Mathematical Procedure:** Add a theoretical background section to your report, explaining the concepts behind the OLS method. Utilize LaTeX to present the mathematical procedure **for obtaining the OLS parameters ($\\theta\_0$ and $\\theta\_1$)** clearly and concisely.
    *   **☑️ Dataset Loading and Analysis:** The datasets required for this activity are in the following repository (put the `CSV` files in the same folder as your `ipynb` file). Each dataset contains two columns, corresponding to the input variable (x) and output variable (y). 
        * The `dataset-1.csv` to `dataset-5.csv` have a different number of points and the same dispersion value, while the `dataset-6.csv` to `dataset-10.csv` have the same number of points and different dispersion values.
    *   **☑️ Load, extract, and compute:** Use pandas.read_csv() to import the CSV file, store each column as a NumPy array, and calculate the basic statistical characteristics of the (y) data with:
        ```python
        import pandas as pd
        data = pd.read_csv("dataset-1.csv")
        x = data["x"].to_numpy()
        y = data["y"].to_numpy()
        N = len(x) #number of points
        yMean = np.mean(y) # mean
        yStd = np.std(y) # dispersion
        ```
    *   **☑️ Develop a function** that computes the **Sum of Squared Error** (SSE) based on the formula discussed in lectures: $SSE=\\sum{(y-\\hat{y})}^2$.
    *   **☑️ SSE Evolution Plot: Compute and plot** the evolution of SSE using Datasets 1, 2, 3, 4, and 5 (number of points vs. SSE) and Datasets 6 to 10  (dispersion vs. SSE)**.**
    *   **☑️ Comparison Table of Theta Values:** Create a comparison table to show the computed $\\theta$'s values for each dataset.
    *   **☑️ Conclusions: Based on the previous tasks, conclude how the OLS method performs with small and large data sets, and dispersion, using your previously generated plots as support.** Provide insights into the efficiency and accuracy of the methods under various scenarios, including the number of points and dispersion.
*   **Stay Organized** 🗂️: Keep all your assignments in a dedicated folder on your computer or in a specific notebook. Consider backing up your work on cloud storage or an external drive.
*   **Seek Clarifications Early** ❓: If you’re unsure about any requirements, ask your lecturer well in advance. Don’t wait until the last minute. You can use our [Answer-Itmorelia](https://answer.itmorelia.com) service to post questions and ask for help.
*   **Avoid Procrastination** ⏰: Start your homework early. This gives you ample time to research, think through your answers, and ask for help if needed.
*   **Stay Updated** 📢: Sometimes, teachers might provide additional instructions or changes. Stay updated by checking your registered email regularly.
*   **Feedback is Gold** 🌟: After submitting, if you receive feedback, take it positively. It’s a chance to learn and improve for future assignments.
*   **Support Resources 🧑🏽💻:** To complement this session **or if you missed**, we provide [video resources that review the fundamentals of Ordinary Least Squares (OLS) regression](https://www.youtube.com/watch?v=RtnjXvwbVjw@TrackLink) covered previously. These videos explain step by step how the method works, how the model parameters are estimated, and how OLS can be applied to simple datasets;[the video's repository]. The repository of the code developed during the [lab session can be foud here.](https://github.com/gmarxcc/lab-sessions-26b/tree/main@TrackLink)

Finally, everyone occasionally faces challenges with schoolwork. The key is to stay organized, ask for help when needed, and strive constantly for your best. Here's to successful homework submissions and continuous learning!

_**Happy coding and warm regards,**_

_**Gerardo Marx**_

_**Lecturer of the AIA Course,**_

_**gerardo.cc@morelia.tecnm.mx**_
