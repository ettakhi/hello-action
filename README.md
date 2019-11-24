# Hello action

This action prints "Hello Hakim" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: ettakhi/hello-action@master
with:
  who-to-greet: "Hakim"
```
