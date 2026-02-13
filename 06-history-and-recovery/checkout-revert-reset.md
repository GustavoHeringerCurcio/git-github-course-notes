# Checkout vs Reset

## Checkout
- Safe
- Used to inspect old commits

# Revert

The `git revert` command creates a new commit that undoes a previous one.

This is safer than reset and keeps history intact.

## Reset
- Removes commits
- Can be dangerous

### Hard reset
⚠️ Deletes changes permanently.

```bash
git reset --hard <commit>
```
```md


