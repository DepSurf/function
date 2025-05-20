# Function: <code>devlink_trap_group_item_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b630)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff8197b630-ffffffff8197b692: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b629)
Location: net/core/devlink.c:6164
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a62ba9)
Location: net/core/devlink.c:7010
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_group_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a454dd)
Location: net/core/devlink.c:7213
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afe58c)
Location: net/core/devlink.c:7892
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c8199a)
Location: net/core/devlink.c:8385
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e39bf4)
Location: net/core/devlink.c:8914
Inline: True
Inline callers:
  - net/core/devlink.c:devl_trap_groups_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff8203c5fc)
Location: net/devlink/leftover.c:5766
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_trap_groups_register
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_group_get_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82115a46)
Location: net/devlink/trap.c:436
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_trap_groups_register
  - net/devlink/trap.c:devlink_nl_trap_group_set_doit
  - net/devlink/trap.c:devlink_nl_trap_group_get_doit
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c22f20)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffff800010c22f20-ffff800010c22fa4: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a344)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
c0d3a344-c0d3a3b0: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15900)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
c000000000d15900-c000000000d15b40: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b862)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffe00079b862-ffffffe00079b8cc: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b4a0)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff8191b4a0-ffffffff8191b502: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5250)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff818d5250-ffffffff818d52b2: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c630)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff8196c630-ffffffff8196c692: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_trap_group_item *devlink_trap_group_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198eab0)
Location: net/core/devlink.c:5572
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_nl_cmd_trap_group_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_group_get_doit
```
**Symbols:**

```
ffffffff8198eab0-ffffffff8198eb12: devlink_trap_group_item_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
