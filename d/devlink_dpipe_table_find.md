# Function: <code>devlink_dpipe_table_find</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946cd0)
Location: net/core/devlink.c:2077
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81946cd0-ffffffff81946d28: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197b8f0)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff8197b8f0-ffffffff8197b948: devlink_dpipe_table_find (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a537d6)
Location: net/core/devlink.c:2111
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
In net/core/devlink.c (ffffffff81a5a1c6)
Location: net/core/devlink.c:2443
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
In net/core/devlink.c (ffffffff81a3d316)
Location: net/core/devlink.c:2646
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
In net/core/devlink.c (ffffffff81af3906)
Location: net/core/devlink.c:3208
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
In net/core/devlink.c (ffffffff81c77b26)
Location: net/core/devlink.c:3723
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
In net/core/devlink.c (ffffffff81e30585)
Location: net/core/devlink.c:3987
Inline: True
Inline callers:
  - net/core/devlink.c:devl_dpipe_table_resource_set
  - net/core/devlink.c:devl_dpipe_table_unregister
  - net/core/devlink.c:devl_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
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
In net/devlink/leftover.c (ffffffff82033375)
Location: net/devlink/leftover.c:3205
Inline: True
Inline callers:
  - net/devlink/leftover.c:devl_dpipe_table_resource_set
  - net/devlink/leftover.c:devl_dpipe_table_unregister
  - net/devlink/leftover.c:devl_dpipe_table_register
  - net/devlink/leftover.c:devlink_dpipe_table_counter_enabled
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
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
In net/devlink/dpipe.c (ffffffff8210a765)
Location: net/devlink/dpipe.c:452
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devl_dpipe_table_resource_set
  - net/devlink/dpipe.c:devl_dpipe_table_unregister
  - net/devlink/dpipe.c:devl_dpipe_table_register
  - net/devlink/dpipe.c:devlink_dpipe_table_counter_enabled
  - net/devlink/dpipe.c:devlink_nl_dpipe_table_counters_set_doit
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
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
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23280)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffff800010c23280-ffff800010c23300: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3a870)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
c0d3a870-c0d3a8d8: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d16870)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
c000000000d16870-c000000000d16ab0: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079baf8)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffe00079baf8-ffffffe00079bb5c: devlink_dpipe_table_find (STB_LOCAL)
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
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191b760)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff8191b760-ffffffff8191b7b8: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5510)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff818d5510-ffffffff818d5568: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196c8f0)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff8196c8f0-ffffffff8196c948: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_dpipe_table *devlink_dpipe_table_find(struct list_head *dpipe_tables, const char *table_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198ed70)
Location: net/core/devlink.c:2079
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_table_resource_set
  - net/core/devlink.c:devlink_dpipe_table_unregister
  - net/core/devlink.c:devlink_dpipe_table_register
  - net/core/devlink.c:devlink_dpipe_table_counter_enabled
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_counters_set
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff8198ed70-ffffffff8198edc8: devlink_dpipe_table_find (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
