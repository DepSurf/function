# Function: <code>devlink_trap_item_lookup</code>

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
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b6a0)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff8197b6a0-ffffffff8197b703: devlink_trap_item_lookup (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a5f058)
Location: net/core/devlink.c:5850
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_register
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
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
In net/core/devlink.c (ffffffff81a65eb8)
Location: net/core/devlink.c:6701
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_trap_register
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
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
In net/core/devlink.c (ffffffff81a4b816)
Location: net/core/devlink.c:6904
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
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
In net/core/devlink.c (ffffffff81b04136)
Location: net/core/devlink.c:7530
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
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
In net/core/devlink.c (ffffffff81c85696)
Location: net/core/devlink.c:8023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
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
In net/core/devlink.c (ffffffff81e3f8ec)
Location: net/core/devlink.c:8558
Inline: True
Inline callers:
  - net/core/devlink.c:devl_traps_unregister
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
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
In net/devlink/leftover.c (ffffffff820400d8)
Location: net/devlink/leftover.c:5414
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_traps_unregister
  - net/devlink/leftover.c:devlink_trap_unregister
  - net/devlink/leftover.c:devlink_nl_cmd_trap_set_doit
  - net/devlink/leftover.c:devlink_nl_cmd_trap_get_doit
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
In net/devlink/trap.c (ffffffff82116b98)
Location: net/devlink/trap.c:86
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_traps_unregister
  - net/devlink/trap.c:devlink_trap_unregister
  - net/devlink/trap.c:devlink_nl_trap_set_doit
  - net/devlink/trap.c:devlink_nl_trap_get_doit
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
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c22fa8)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffff800010c22fa8-ffff800010c2302c: devlink_trap_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a508)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
c0d3a508-c0d3a574: devlink_trap_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d15b40)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
c000000000d15b40-c000000000d15d80: devlink_trap_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079b8cc)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffe00079b8cc-ffffffe00079b936: devlink_trap_item_lookup (STB_LOCAL)
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
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b510)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff8191b510-ffffffff8191b573: devlink_trap_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d52c0)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff818d52c0-ffffffff818d5323: devlink_trap_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c6a0)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff8196c6a0-ffffffff8196c703: devlink_trap_item_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_trap_item *devlink_trap_item_lookup(struct devlink *devlink, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198eb20)
Location: net/core/devlink.c:5262
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_traps_unregister
  - net/core/devlink.c:devlink_traps_register
  - net/core/devlink.c:devlink_trap_unregister
  - net/core/devlink.c:devlink_nl_cmd_trap_set_doit
  - net/core/devlink.c:devlink_nl_cmd_trap_get_doit
```
**Symbols:**

```
ffffffff8198eb20-ffffffff8198eb83: devlink_trap_item_lookup (STB_LOCAL)
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
