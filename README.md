# semantically-correct

Will print the lastVersion or the nextVersion

## Dependencies
* semantic-release

## Usage
```bash
$ npm install -g semantically-correct
...
$ cd some-repo
some-repo$ semantically-correct
2.2.0
```

Output as JSON
```bash
some-repo$ semantically-correct --JSON
{"type":"minor","version":"2.2.0"}
```