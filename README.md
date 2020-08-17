# Hello world javascript action

This action prints 'Hello world' or Hello + name of the person to greet to the log

## inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"WOrld"`.

## Outputs

### `time`

The time we greeted you.

## Exemple usage 

uses: actions/hello-world-javascript-action@v1
with:
who-to-greet:'Mona the Octocat'
