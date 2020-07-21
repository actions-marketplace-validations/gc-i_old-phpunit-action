# old-phpunit-action
Github Action with an old version of PHPUnit.
The base is the docker image phpunit/phpunit with PHPUnit 6.5.

## Inputs

### `configfile`

**Required** Location of the PHPUnit config XML. Default `"tests/phpunit.xml"`.

### `more_params`

More parameters for PHPUnit. Default `""`.

## Example usage

```
- name: Old PHPUnit
  uses: gc-i/old-phpunit-action@v1.2
  with:
    configfile: 'tests/phpunit.xml'
    more_params: 'tests'
```
