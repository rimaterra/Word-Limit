# Word-Limit

Permits you to limit the number of words in some text

## Usage

### `{exp:word_limit}`

#### Example Usage

```
{exp:word_limit total="100"}
	text you want processed
{/exp:word_limit}
```

#### Parameters

- `total` - lets you specify the number of words.

## Change Log

### 2.2 rk

- Allow em, strong, b, i tags

### 2.1 rk

- Filter out HTML tags to avoid picking up partial tags
- Allow paragraph and break tags

### 2.0

- Updated plugin to be 3.0 compatible

### 1.1.1

- Updated plugin to be 2.5 compatible and PHP 5.6 compatible

### 1.1

- Updated plugin to be 2.0 compatible
