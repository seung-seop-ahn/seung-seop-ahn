# How I increase my productivity

I use PARA as a basic framework and use GTD within PARA's Project items. Also, I am using it by adding a folder for Zetelkasten's temporary notes.


<details>
<summary>PARA</summary>
<div markdown="1">

> [Reference](https://fortelabs.com/blog/para/)

- Get Things Done.
- Change the location of notes as needed.

| Subject  | Description                                                                                                | Example         |
|----------|------------------------------------------------------------------------------------------------------------|-----------------|
| Project  | Short-term efforts in my work or life that I'm working on now. (Goals, deadline)                           | Travel, Develop |
| Area     | Long-term responsibilities I want to manage over time. (Something to do consistently)                      | Health, Career  |
| Resource | Topics or interests that may be useful in the future. (Interests, data)                                    | Develop (K8S)   |
| Archive  | Inactivate items from the other three categories. (Completed project, irresponsible area, out of interest) |                 |

</div>
</details>

<details>
<summary>GTD</summary>
<div markdown="1">

> [Reference](https://lifehacker.com/productivity-101-a-primer-to-the-getting-things-done-1551880955)

![img.png](./docs/images/gtd.png)

| In                | Define                                          | Possible | Next Action     |
|-------------------|-------------------------------------------------|----------|-----------------|
| Buy snacks        | Come to think of it, there were snacks at home. | Y        | Trash           |
| Study K8S         | Too busy to do.                                 | Y        | Someday         |
| Version updates   | Nothing to do, but let's be aware.              | Y        | Reference       |
| Buy pants         | What brand? What color? Too Complicated.        | Y        | Projects        |
| Brush teeth       | Let's brush my teeth.                           | Y        | Do              |
| Needs code review | Remind to co-workers and wait for the review.   | Y        | Delegate & Wait |
| Movie reserved    | Let's remind on calendar.                       | Y        | Calendar        |
| Off work          | As soon as possible.                            | Y        | Next Action     |

</div>
</details>


<details>
<summary>Zettelkasten</summary>
<div markdown="1">

> [Reference](https://zenkit.com/en/blog/a-beginners-guide-to-the-zettelkasten-method/)

| Subject         | Description                                                  |
|-----------------|--------------------------------------------------------------|
| Fleeting note   | Temporary notes. (Idea)                                      |
| Literature note | Reference notes. (Book, youtube)                             |
| Permanent note  | Notes that will used later. (Connections to literature note) |

</div>
</details>


```txt
└── project
│   └── <project name>
│       ├── document
│       │   └── <project plans and documentaion>
│       ├── reference
│       ├── someday
│       ├── trash
│       ├── delegate
│       │   ├── <follow up delegated jobs>
│       │   └── <keep in remind by using calendar>
│       └── daily-scrum
│           └── <date>
│               ├── todo
│               │   └── <define job>
│               │   └── <check if it's possible>
│               └── next
│                   ├── <what to do after all stuff is done>
│                   └── <stuff that are not done>
├── area
├── resource
├── archive
└── fleeting 
```