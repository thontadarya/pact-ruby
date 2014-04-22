# Configuration

## Consumer and Provider

### diff_formatter

Default value: `:embedded`

```ruby
Pact.configure do | config |
  config.diff_formatter = :list
end

```

#### :list

<img src="diff_formatter_list.png">

#### :embedded

<img src="diff_formatter_embedded.png">

#### :unix
<img src="diff_formatter_unix.png">

## Consumer


## Provider