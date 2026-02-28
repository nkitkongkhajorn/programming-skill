# insect-solo-assessment

This program implements a breadth-first search algorithm to simulate predator animals tracking prey. For background information about the algorithm, please read the background information document on LEARN.

The assessment code is available in [Python](./Python).

You can test the codes with a variety of [landscape files](./landscapes).

## Using this repository

1. Clone this repository. This should create a folder called `insect-solo-assessment`:

```console
$ git clone https://git.ecdf.ed.ac.uk/epcc110172025s2/insect-solo-assessment.git
```

2. Clone your personal repository, replacing `sxxxxxxx` with your student ID. This should create a folder named after your student ID:

```console
$ git clone https://git.ecdf.ed.ac.uk/epcc110172025s2/sxxxxxxx
```

3. Choose a language (Python)
4. Copy the contents of the directory of your chosen language to your personal repository:

```console
$ cd insect-solo-assessment
$ cp -R Python/* ../sxxxxxxx/
```

5. Copy the landscape files to your personal repository:

```console
$ cp -R landscapes ../sxxxxxxx/
```

Your repository should now have this structure for Python:

```text
sxxxxxxx/
  landscapes/
  insect/
  test/
  README.md
```

6. Upload the changes to your personal repository to GitLab

```console
$ cd ../sxxxxxxx
$ git add .
$ git commit -m "Populate repo with source code"
$ git push origin main
```

7. Check your repository in GitLab. You're now ready to go!
