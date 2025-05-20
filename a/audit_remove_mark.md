# Function: <code>audit_remove_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8112aa50)
Location: kernel/audit_fsnotify.c:144
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8112aa50-ffffffff8112aa78: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81132c76)
Location: kernel/audit_fsnotify.c:144
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81132c40-ffffffff81132c68: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8113c9c6)
Location: kernel/audit_fsnotify.c:143
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8113c990-ffffffff8113c9b8: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8113e056)
Location: kernel/audit_fsnotify.c:143
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8113e020-ffffffff8113e048: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8114ae26)
Location: kernel/audit_fsnotify.c:143
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8114adf0-ffffffff8114ae18: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81159885)
Location: kernel/audit_fsnotify.c:143
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81159850-ffffffff81159878: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811667f5)
Location: kernel/audit_fsnotify.c:141
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff811667c0-ffffffff811667e8: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811733c5)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81173390-ffffffff811733ba: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8117f235)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8117f200-ffffffff8117f22a: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81192745)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81192710-ffffffff8119273c: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8118f8b5)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8118f880-ffffffff8118f8ac: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811907f5)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff811907c0-ffffffff811907ec: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811b96d5)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff811b96a0-ffffffff811b96cc: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff811ec7d5)
Location: kernel/audit_fsnotify.c:133
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff811ec790-ffffffff811ec7c3: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81232cd5)
Location: kernel/audit_fsnotify.c:133
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81232c80-ffffffff81232cb3: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81249955)
Location: kernel/audit_fsnotify.c:133
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81249900-ffffffff81249933: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81263865)
Location: kernel/audit_fsnotify.c:133
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81263810-ffffffff81263843: audit_remove_mark (STB_GLOBAL)
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
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffff8000101f4208)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffff8000101f41b0-ffff8000101f41f0: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (c04345b8)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
c043456c-c04345a4: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (c00000000026930c)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
c0000000002692a0-c0000000002692f0: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffe0001674e6)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffe000167492-ffffffe0001674d0: audit_remove_mark (STB_GLOBAL)
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
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81177855)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81177820-ffffffff8117784a: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff8116a9f5)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff8116a9c0-ffffffff8116a9ea: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81175625)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff811755f0-ffffffff8117561a: audit_remove_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_remove_mark(struct audit_fsnotify_mark *audit_mark);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_fsnotify.c (ffffffff81182f05)
Location: kernel/audit_fsnotify.c:132
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_remove_mark_rule
Direct callers:
  - kernel/auditfilter.c:audit_update_lsm_rules
  - kernel/auditfilter.c:audit_rule_change
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/auditfilter.c:audit_data_to_entry
  - kernel/audit_watch.c:audit_watch_handle_event
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_tree.c:kill_rules
```
**Symbols:**

```
ffffffff81182ed0-ffffffff81182efa: audit_remove_mark (STB_GLOBAL)
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
