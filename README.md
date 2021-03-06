## **Ez Chatbot**

This repository helps new learners to build an ez FAQ chatbot on **Ubuntu 16.04** using [**RASA**](https://rasa.com/) framework. Please check out installation on other operation systems, updates, tutorials, and tricks of RASA from [**here**](https://rasa.com/docs/rasa/).

### **Environment**

- Install Anaconda from [here](https://docs.anaconda.com/anaconda/install/).
- Create and activate environment for chatbot

```
conda create -n chatbot python=3.6
conda activate chatbot
```

### **Quick installation**

- Create new Rasa chatbot project

```
rasa init --no-prompt
```

The command generated all needed files and train a simple sample data.

- Train a model

```
rasa train
```

- Test a model

```
rasa test
```

- Interactive learning Interface: 
![interface](./images/rasa.png)
![interface](./images/rasa1.png)
