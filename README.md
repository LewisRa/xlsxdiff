# Comparing two excel files for differences using Python

## idea from:
 https://kanoki.org/2019/02/26/compare-two-excel-files-for-difference-using-python/
 
 ## forked from:
 - https://github.com/mwcm

**usage:**
- python xlsxdiff.py --file1 /path/to/file1.xlsx --file2 /path/to/file2.xlsx

**outputs:**
- ./Excel_diff.xlsx

**todo:**
- output options
- clarify input restrictions wrt column label & value's names & types

**Click Example:
```
import click

@click.command()
@click.option('--count', default=1, help='Number of greetings.')
@click.option('--name', prompt='Your name',
              help='The person to greet.')
def hello(count, name):
    """Simple program that greets NAME for a total of COUNT times."""
    for x in range(count):
        click.echo('Hello %s!' % name)

if __name__ == '__main__':
    hello()
```
And what it looks like when run:

```
$ python hello.py --count=3
Your name: John
Hello John!
Hello John!
Hello John!
```
