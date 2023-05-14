# Queens_University_Data-Mining_Airbnb-price-category-prediction

**Airbnb price category prediction**

![inbox_4409738_229f8a04bb84f4474b43b63a2a1da38d_red-airbnb (1)](https://github.com/Bilal-Elhlwany/Queens_University_Data-Mining_Airbnb-price-category-prediction/assets/100938358/d4823896-c968-4e24-9e3e-6b32bd50d541)

(meme source: People Are Having a Lot of Fun With the New Airbnb Logo)

One of the biggest problems when people prepare to post a new listing on airbnb is, how much should one ask for? Of course the most intuitive way is to check how other similar postings price their apartment/house. So in this assignment, we are going to predict the listing price based on the listing characteristics 🔥🔥, in this way to optimize user experience and lower the bar to be a new host😍 !

Predicting the actual price could be simple (well you can just go search online 👍), so we cut the pricing into three different bins for classification 😂. For each listing, we recommend a pricing range to the new host rather than a fix price (how nice is that!). So we define three categories: beginner, plus, premium based on the created listing. Respectively we use 0, 1, 2 to denote these three categories.

The dataset contains listings of different areas in Montreal during 2019. It comes with rich information for each listing, including a link to the thumbnails etc. As discussed in the last lecture, we will follow a multi-objective (multi-task) multi-modality solution.
https://www.kaggle.com/t/3d7fae64524242e381082320549b95d8

Enjoy!

**Tasks:**

**✔️ Meme competition:**

Include/find a MEME that you liked related to data science/data mining/machine learning

**✔️ Understand the template:**

Put detailed comment on each line of the code to show your understanding of the template (you can find it at the Data tab). Then describe: What is the experimental protocol used and how was it carried out? How did we tune hyper-parameters in the template? What is the search space and what is the criteria to determine good/bad hyper-parameters?

**✔️ Problem Formulation:**

Define the problem. What is the input? What is the output? What data mining function is required? What could be the challenges? What is the impact? What is an ideal solution?

**✔️ Model Tuning and Documentation:**

Now based on the template, try to improve the model's performance on the public leaderboard by following the data science life-cycle for tuning. You can try different features, different hyperparameters/configurations of the model, and even a different model. For each trial, document the reason why you want to make the certain change and the expected outcome, before running the code. Record the observed performance and your thought on it. Recall that we have a DS life-cycle and we should know what to do when underfit/overfit. The final result is not important, but the process is. Documentation of your thought process is very important, since most people forgot why they test certain model/hyperparameter after they got the result (it takes time). It also helps a lot when you got stuck. You can organize the notebook by listing

thoughts and observations for trial 0, plan for trial 1

code for trial 1

thoughts and observations for trial 1, plan for trial 2

code for trial 2

…
You have to tune at least 6 times. All the tried solutions should be different (e.g. different feature sets/different preprocessing). The tried solutions should cover at least:

Text inputs. Cover at least once a GRU/LSTM layer.

Text inputs. Cover at least once a BiDirectional layer.

Image inputs. Cover at least once a Conv2d layer.

Image inputs. Cover at least once a Dropout layer.

Multi-modality learning. Cover at least once a multi-modality (text+image) model.

Multi-objective learning. Cover at least once a multi-objective model (predicting both price and type).

**✔️ Answer the questions below (briefly):**

**🌈Is fully-connected model a good one for sequential data? Why? How about for image data? Is it good? Why?**

**🌈What is gradient vanishing and gradient explosion, and how GRU/LSTM tries to mitigate this problem?**

**🌈What is multi-objective/multi-task learning? What is multi-modality learning? How do you use them in this assignment?**

**🌈What is the difference among xgboost, lightgbm and catboost**

Deliverable:

🔥 A python notebook containing the documentation of how you reach the final design as well as the answers to the questions.

1 bonus point if you do transfer learning and up-training

Note: Emoji allowed and encouraged so it will be more fun for us to grade it.
