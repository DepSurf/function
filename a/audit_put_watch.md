# Function: <code>audit_put_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81129b90)
Location: kernel/audit_watch.c:116
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/audit_watch.c:audit_remove_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_add_watch
```
**Symbols:**

```
ffffffff81129b90-ffffffff81129bee: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81131d40)
Location: kernel/audit_watch.c:117
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff81131d40-ffffffff81131da1: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113baa0)
Location: kernel/audit_watch.c:117
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff8113baa0-ffffffff8113bb01: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113d150)
Location: kernel/audit_watch.c:118
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff8113d150-ffffffff8113d194: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81149f20)
Location: kernel/audit_watch.c:118
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff81149f20-ffffffff81149f68: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81158920)
Location: kernel/audit_watch.c:118
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff81158920-ffffffff81158968: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811658d0)
Location: kernel/audit_watch.c:118
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff811658d0-ffffffff81165918: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117246a)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff8117300f-ffffffff81173035: audit_put_watch.cold (STB_LOCAL)
ffffffff81172450-ffffffff8117249e: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117e300)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff8117e300-ffffffff8117e34e: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811915f0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811915f0-ffffffff8119165c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118e7a0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8118e7a0-ffffffff8118e80c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118f720)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8118f720-ffffffff8118f78c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b8600)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811b8600-ffffffff811b866c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811eb510)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811eb510-ffffffff811eb59c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81231900)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81231900-ffffffff8123198c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81248590)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81248590-ffffffff8124861c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff812624b0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_remove_watch_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff812624b0-ffffffff8126253c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffff8000101f31a0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffff8000101f31a0-ffff8000101f320c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0433688)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
c0433688-c0433714: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c000000000267bd0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
c000000000267bd0-c000000000267c6c: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffe0001666e0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffe0001666e0-ffffffe000166742: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81176920)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff81176920-ffffffff8117696e: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81169ac0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff81169ac0-ffffffff81169b0e: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811746f0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff811746f0-ffffffff8117473e: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_put_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81181fd0)
Location: kernel/audit_watch.c:105
Inline: True
Direct callers:
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/auditfilter.c:audit_free_rule_rcu
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_remove_watch
```
**Symbols:**

```
ffffffff81181fd0-ffffffff8118201e: audit_put_watch (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
