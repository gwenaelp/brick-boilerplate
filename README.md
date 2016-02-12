# Boilerplate Canopsis Brick

## Description

An empty canopsis brick, to kickstart brick creation

## Screenshots



## Installation

You need to clone the git repository and copy directory to Canopsis path

    $ git clone https://git.canopsis.net/canopsis-ui-bricks/brick-boilerplate.git
    $ cp -r brick-boilerplate $CANOPSIS_PATH/var/www/canopsis

Then, you need to import specific schemas

    $ su - canopsis
    $ cp $CANOPSIS_PATH/var/www/canopsis/brick-boilerplate/schemas/* $CANOPSIS_PATH/etc/schema.d
    $ schema2db update

Then, you need to enable the brick

    $ su - canopsis
    $ webmodulemanager enable brick-boilerplate

You can see enabled bricks

    $ su - canopsis
    $ webmodulemanager list
    [u'core', u'uibase', u'monitoring', ..., **u'brick-boilerplate'**]

## Usage

See [Howto](https://git.canopsis.net/canopsis-ui-bricks/brick-boilerplate/blob/master/doc/index.rst)

## Continuous Integration

Tested on commit : bbae8f1.

| Target | Status | Log |
| ------ | ------ | --- |
| Lint   | :ok: OK |  |

## Code Notes

### TODOS



### FIXMES


