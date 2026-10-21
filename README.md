# CompLabNGS
Welcome to TAU Life Sciences - Computational Lab in Next Generation Sequencing and Genomics Data Analysis - 0411358701

Course material will be updated weekly prior to our Sunday session. Make sure you grub necessary slides, data and class/HW assignments from the relevant directory.

Course announcements and HW submissions will be delivered via the course's [Moodle site](https://moodle.tau.ac.il/course) **only!**

Please use the *Issues* tab above to ask questions and report problems. Your questions will be answered by the course staff and/or your fellow students. Please refrain from sending us emails regarding course-related issues. Your questions and our answers will be visible to all students. This way, we can avoid duplicate questions and you can benefit from the questions and answers of your fellow students.

## Setting up your environment

Our course is all about hands-on experience with NGS data analysis. You'll need to set yourself up with a Unix-based environment. Please follow the instructions on [0-SettingUp](https://github.com/hadasvolk/CompLabNGS/blob/main/0-SettingUp/SettingUp.md) for possible solutions to this task.

## Course timeline
| Week | Date | Topic | Data |
|:----:|:----:|:-----:|:----:|
| 1 | 18/10/2026 | Introduction to NGS and Genomics | |
| 2 | 25/10/2026 | Introduction to Linux and the command line | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/2-Linux/data) |
| 3 | 01/11/2026 | NGS data quality control and pre-processing | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/3-QC/data) |
| 4 | 08/11/2026 | Sequence mapping part I | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/4-Mapping1/data) |
| 5 | 15/11/2026 | Sequence mapping part II | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/5-Mapping2/data) |
| 6 | 22/11/2026 | Variant calling | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/6-VariantCalling/data) |
| 7 | 29/11/2026 | Assembly | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/7-Assembly/data) |
| 8 | 13/12/2026 | RNA-Seq I | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/8-RNA1/data) |
| 9 | 20/12/2026 | Python | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/9-Python/data) |
| 10 | 27/12/2026 | RNA-Seq II | [Data](https://github.com/hadasvolk/CompLabNGS/tree/main/10-RNA2/data) |
| 11 | 03/01/2027 | Third Generation Sequencing | |
| 12 | 10/01/2027 | Genome Annotation & Genomic DBs | |
| 13 | 17/01/2027 | Final project presentation | |

## Large files
Some of the files in this repository are large and cannot be viewed directly in the browser. These files are accesible in a Google Drive folder. You can access the folder [here](https://drive.google.com/drive/folders/1N1pYkeFPUOo4_Hv_Jk2MzgzlZ-LLWXSY?usp=sharing)

## Roadmap to final grade of 100
30 points - Class assignments
* Starting on lesson 2
* One week to complete each assignment and submit via Moodle
* Partial credit (average of best 8 assignments)
* Must submit at least 8 assignments to pass the course

70 points - Final project
* Can be done in pairs/threes
* Submission deadline: TBD

## Download the data | git clone
If you wish to pull data and material hosted in this GitHub repo automatically and not download each file individually, you can use `git` to `clone` the entire repository to your local machine.

Make sure you have `git` installed by running `git --version`. If you don't have it installed, you can download it from [here](https://git-scm.com/downloads). Or simply use the `sudo apt install git` command if you are using a Ubuntu-based system.

Then, to clone the repository, use the following command:
```bash
git clone https://github.com/hadasvolk/CompLabNGS.git
```

From now on, you can use `git pull` to get the latest version of the repository. E.g., you can run:
```bash
cd CompLabNGS
git pull
```

Do it every time you want to get the latest version of the repository.
