# action-readme-examples

## Option A

| Input      | Type   | Required | Default       | Description                       |
| ---------- | ------ | -------- | ------------- | --------------------------------- |
| `my-input` | string | false    | "Hello World" | A test input for our test action. |

## Option B

##### `my-input`
- **Required:** false
- **Default:** Hello World
- **Description:** A test input for our test action.

## Option C

```yaml
- uses: PhantasmicDev/my-test-action@v1
  with:
    # A test input for our test action.
    # Required: false
    # Default: Hello World
    my-input: ''
```

## Option D

- `my-input`: A test input for our test action.
	- **Type:** string
	- **Required:** false
	- **Default:** Hello World
