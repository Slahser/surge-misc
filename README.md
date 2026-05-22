# surge-misc

Personal Surge rule lists for [Slahser](https://github.com/Slahser). No secrets in this repo.

## Files

| File | Applied as |
|------|------------|
| `rules/direct.list` | `DIRECT` |
| `rules/reject.list` | `REJECT` |
| `rules/proxy.list` | `✈️ 节点选择` |

One rule per line, no policy suffix (Surge `RULE-SET` adds the policy).

## Raw URLs

```
https://raw.githubusercontent.com/Slahser/surge-misc/main/rules/direct.list
https://raw.githubusercontent.com/Slahser/surge-misc/main/rules/reject.list
https://raw.githubusercontent.com/Slahser/surge-misc/main/rules/proxy.list
```

## Edit

Change a list → commit → Surge refreshes rule sets per `update-interval` in your profile.
