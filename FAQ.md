## **Dojo / World modelers FAQ questions**

 **1. Will my model be a good fit for running in Dojo?**
 
To be a good fit for Dojo

 **2. Can I register Windows applications/models?**

At this time, no, Windows applications cannot be registered in Dojo

 **3. What if my data doesn’t have a temporal or geospatial dimension?**

 **4. Running my model requires X number of steps, but there’s only one
    directive, how can I make this work?**

Frequently, this can be resolved by wrapping your steps in a simple bash script, and the bash script can be set as the directive

 **5. What if I need to download the latest data for each model run?**

It is possible to to use curl or wget to download data, or to do so directly in your model code, but this is generally not recommended as broken download links is one of the most common causes of failure when running models.

 **6. What if my code and/or model is not allowed to be shared with the
    public?**


 **7. How do I cite Dojo in papers?**

 **8. What if I need to make changes to the model in the future?**

Dojo utilizes a versioning system where once a model is published it becomes unchangeable. However at any point you can create a new version of the model, cloning the existing model into a brand new model. Publishing this clone replaces the previous version of the model for purposes or running.

 **9. What languages can my model be written in?**

Dojo is language agnostic, as long as the resulting binaries or code can be executed in a Debian/Ubuntu based environment. During model registration modelers can install any required runtimes or libraries needed.

 **10. What data file formats and Dojo process?**