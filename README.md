# ![Ironhack logo](https://i.imgur.com/1QgrNNw.png)

# DE | Angular Introduction

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_a21d309e7c9666ea85d408b21c98f147.png)

## Learning Goals

After this lesson, you will be able to:

- Create an static Angular application with Angular CLI.
- Build an Angular application with one component.
- Build an Angular application with two nested components.
- Build an Angular application using nested iterators.

## Requirements

- [Fork this repo](https://guides.github.com/activities/forking/).
- Clone your fork into your `~/code/labs` folder.

## Submission

Upon completion, run the following commands:

```bash
$ git add .
$ git commit -m"done"
$ git push origin master
```

Navigate to your repo and create a Pull Request -from your master branch to the original repository master branch.

In the Pull Request name, add your campus, name, and last name separated by a dash "-".

## Deliverables

All the files in the different folders you have, being these folders one per iteration.

## Introduction

In this lesson we are going to work for the first time with Angular 2. The goal here is to work over three small projects where you are going to practice all what we have learnt.

### Starter Code

The starter code is composed by three different folders, called `iteration-1`, `iteration-2`, `iteration-3`. The only folder that has something inside is the `iteration-1`, that contains a project created with the Angular CLI.

As you may noticed, this lesson is composed by three different iterations. In each iteration we will cover a different project. In the first iteration we provide you the basic skeleton of the app, while in the other two iterations you will have to create it.

## Iteration #1: Photo Album

In the first iteration we are going to build a photo album. Imagine you have an album at home. On it, you can find a photo and its description. This is what we are going to build.

We will build this album over the `AppComponent` component. The album will have three photos and their descriptions, and **it's not necessary to have an Array to store this values**.

Easy, right? Add some styles to the page to see the different photos as better as you can show them :)

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cdd5a4fee9ee1b900411bc225c5b56a4.png)

## Iteration #2: Article with comments

In the second project of this lesson we are going to create a blog article with comments. We are going to create two different components:

- The `main` component will contain the article, composed by a `title`, an `image`, and a `description`.
- The `comments` component, that will contain several comments (feel free to add as many comments as you want).

At the bottom of the comments, we will add a comment form to add some reality to our article. We can't have comments without a form!

The first thing you will have to do is to generate the project with `Angular CLI`.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_5a601671143a8ff4233ee93b9bb65a84.png)

## Iteration #3: NBA Champions

Last, but not least, we are going to create a Dashboard with the last NBA Champions. In this case, we will need to create one component, that will contain an array of Championships, with the following fields:

- `year` of the championship.
- Name of the `champion` team.
- A `champion_url` to show the team badge.
- A list with the best players of the champion team, called `best_players`

You can find the full list of [NBA Champions](https://en.wikipedia.org/wiki/List_of_NBA_champions) in wikipedia. In our application we have to show, at least, three of them. The result could be something like that:

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ae412842465e31600c1b5ad3837eb4bf.png)

:::info
Note that we are iterating over two different arrays to show all the information: `Championships` and `best_players` of every team.
:::

/Happy coding!
