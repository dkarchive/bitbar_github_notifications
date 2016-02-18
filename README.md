# bitbar_github_notifications

Simple GitHub notifications [BitBar](https://github.com/matryer/bitbar) plugin :octocat:

<img src=assets/screenshot.png width=500>

## Setup

1. Copy [`github_notifications.1m.rb`](github_notifications.1m.rb) to your BitBar plugin folder
- Make the plugin executable `chmod +x github_notifications.1m.rb`
- Create a [GitHub personal access token](https://github.com/settings/tokens) scoped for `notifications`
- Edit `github_notifications.1m.rb` with your login and access token

```ruby
GITHUB_USERS = ['dkhamsing']
GITHUB_ACCESS_TOKENS = ['cool-access-token-here']
```
<img src=assets/personal-access-token.png width=500>

You can also check notifications for multiple accounts

```ruby
GITHUB_USERS = ['dkhamsing', 'second-account']
GITHUB_ACCESS_TOKENS = ['cool-access-token-here', 'second-token']
```

## Credits

- [Mat Ryer](https://github.com/matryer) for the fantastic BitBar
- [Keith Cirkel](https://github.com/keithamus) [:sunglasses:](https://github.com/matryer/bitbar-plugins/pull/18)

## Contact

- [github.com/dkhamsing](https://github.com/dkhamsing)
- [twitter.com/dkhamsing](https://twitter.com/dkhamsing)

## License

This project is available under the MIT license. See the [LICENSE](LICENSE) file for more info.
