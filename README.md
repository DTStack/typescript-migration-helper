# typescript-migration-helper

Help ES6 + React + Redux project migrates to the Typescript project.

This is just a helper script, current only tested in **MacOS**. It can't transform old project to Typescript project completely, some situations still need you to solve manually.

# Usage

The first, you need to download the migration.pl script to your project **root** directory, and then exec the command:

> find ./src/**/*.js -exec ./scripts/migration.pl '{}' \;

It's means transform all js files below src directory into ts. There put the migration.pl file into scripts directory.