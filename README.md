<section class="theory-viewer prisma prisma_theme_light big-theory"><section class="theory-viewer__blocking-layout-block theory-viewer__block theory-viewer__block_type_vertical-layout theory-viewer__block_layout"><section class="theory-viewer__block theory-viewer__block_type_markdown"><div class="Markdown base-markdown base-markdown_with-gallery markdown markdown_size_normal markdown_type_theory full-markdown"><div class="paragraph">Congratulations! You’ve completed another training platform course. Now is the perfect time to test your skills and solve a new machine learning problem. For this project, you will be on your own.</div><div class="paragraph">When you finish, send your work to the project reviewer. You will receive feedback within 24 hours. After that, you will make any necessary changes to your work and send it for a second review.</div><div class="paragraph">Usually, this process has to be repeated several times until you get the green light from the reviewer and all the corrections are approved. That’s all part of the job.</div><div class="paragraph">Your project will be considered complete once the project reviewer approves it.</div><h1>Project description</h1><div class="paragraph">Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value. </div><div class="paragraph">Rusty Bargain is interested in:</div><ul><li>the quality of the prediction</li><li>the speed of the prediction</li><li>the time required for training</li></ul><h3>Project instructions</h3><ol start="1"><li>Download and look at the data.</li><li>Train different models with various hyperparameters (You should make at least two different models, but more is better. Remember, various implementations of gradient boosting don't count as different models.) The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.</li><li>Analyze the speed and quality of the models.</li></ol><div class="paragraph">Notes:</div><ul><li>Use the <em>RMSE</em> metric to evaluate the models.</li><li>Linear regression is not very good for hyperparameter tuning, but it is perfect for doing a sanity check of other methods. If gradient boosting performs worse than linear regression, something definitely went wrong.</li><li>On your own, work with the LightGBM library and use its tools to build gradient boosting models.</li><li>Ideally, your project should include linear regression for a sanity check, a tree-based algorithm with hyperparameter tuning (preferably, random forrest), LightGBM with hyperparameter tuning (try a couple of sets), and CatBoost and XGBoost with hyperparameter tuning (optional).</li><li>Take note of the encoding of categorical features for simple algorithms. LightGBM and CatBoost have their implementation, but XGBoost requires OHE.</li><li>You can use a special command to find the cell code runtime in Jupyter Notebook. Find that command.</li><li>Since the training of a gradient boosting model can take a long time, change only a few model parameters.</li><li><div class="paragraph">If Jupyter Notebook stops working, delete the excessive variables by using the <code class="code-inline code-inline_theme_light">del</code> operator:</div><div class="python code-block code-block_theme_light"><div class="code-block__tools"><button class="code-block__clipboard" type="button">Copy code</button><span class="code-block__lang">PYTHON</span></div><div class="scrollable-default scrollable scrollable_theme_light code-block__scrollable prisma prisma_theme_light"><div></div><div class="scrollable__content-wrapper"><div class="scrollbar-remover scrollable__content-container" style="--scroll-bar-width: 18px; --scroll-bar-height: 18px;"><div class="scrollable__content"><pre class="code-block__code-wrapper"><code class="code-block__code python">  <span class="hljs-keyword">del</span> features_train
   </code></pre><div></div></div></div></div><section class="scrollbar-default scrollbar scrollbar_vertical scrollbar_hidden scrollable__scrollbar scrollable__scrollbar_type_vertical" size="1" style="--scrollbar-offset-size: 57px; --scrollbar-control-size: 57px; --scrollbar-control-container-size: 100%; --scrollbar-scale: 1; --scrollbar-control-offset: 0;"><div class="scrollbar__control-container"><div class="scrollbar__control"><div class="scrollbar__control-line"></div></div></div></section><section class="scrollbar-default scrollbar scrollbar_horizontal scrollbar_hidden scrollable__scrollbar scrollable__scrollbar_type_horizontal" size="1" style="--scrollbar-offset-size: 640px; --scrollbar-control-size: 640px; --scrollbar-control-container-size: 100%; --scrollbar-scale: 1; --scrollbar-control-offset: 0;"><div class="scrollbar__control-container"><div class="scrollbar__control"><div class="scrollbar__control-line"></div></div></div></section></div></div></li></ul><h3>Data description</h3><div class="paragraph">The dataset is stored in file <code class="code-inline code-inline_theme_light">/datasets/car_data.csv</code>. <a href="https://practicum-content.s3.us-west-1.amazonaws.com/datasets/car_data.csv" target="_blank">download dataset</a>.</div><div class="paragraph paragraph_has-one-child"><strong>Features</strong></div><ul><li><em>DateCrawled</em> — date profile was downloaded from the database</li><li><em>VehicleType</em> — vehicle body type</li><li><em>RegistrationYear</em> — vehicle registration year</li><li><em>Gearbox</em> — gearbox type</li><li><em>Power</em> — power (hp)</li><li><em>Model</em> — vehicle model</li><li>Mileage — mileage (measured in km due to dataset's regional specifics)</li><li><em>RegistrationMonth</em> — vehicle registration month</li><li><em>FuelType</em> — fuel type</li><li><em>Brand</em> — vehicle brand</li><li><em>NotRepaired</em> — vehicle repaired or not</li><li><em>DateCreated</em> — date of profile creation</li><li><em>NumberOfPictures</em> — number of vehicle pictures</li><li><em>PostalCode</em> —  postal code of profile owner (user)</li><li><em>LastSeen</em> — date of the last activity of the user</li></ul><div class="paragraph paragraph_has-one-child"><strong>Target</strong></div><div class="paragraph"><em>Price</em> — price (Euro)</div><h2>Project evaluation</h2><div class="paragraph">We’ve put together the evaluation criteria for the project. Read this carefully before moving on to the task.</div><div class="paragraph">Here’s what the reviewers will look at when reviewing your project:</div><ul><li>Have you followed all the steps of the instructions?</li><li>How did you prepare the data?</li><li>What models and hyperparameters have you considered?</li><li>Have you managed to avoid code duplication?</li><li>What are your findings?</li><li>Have you kept to the project structure?</li><li>Have you kept the code neat?</li></ul><div class="paragraph">The <a href="https://tripleten.gatsbyjs.io/DS/NM/" target="_blank">Knowledge Base</a> has everything you need to complete the project.</div><div class="paragraph">Good luck!</div></div></section></section></section>
