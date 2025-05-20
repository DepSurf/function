# Function: <code>devlink_fmsg_nest_common</code>

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
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819472c0)
Location: net/core/devlink.c:4096
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff819472c0-ffffffff81947311: devlink_fmsg_nest_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197c410)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8197c410-ffffffff8197c461: devlink_fmsg_nest_common (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a5c013)
Location: net/core/devlink.c:4588
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
In net/core/devlink.c (ffffffff81a5ecc8)
Location: net/core/devlink.c:5277
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
In net/core/devlink.c (ffffffff81a49976)
Location: net/core/devlink.c:5480
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
In net/core/devlink.c (ffffffff81af3b97)
Location: net/core/devlink.c:6093
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_obj_nest_end
  - net/core/devlink.c:devlink_fmsg_obj_nest_start
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
In net/core/devlink.c (ffffffff81c77d17)
Location: net/core/devlink.c:6588
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_end
  - net/core/devlink.c:devlink_fmsg_pair_nest_start
  - net/core/devlink.c:devlink_fmsg_obj_nest_end
  - net/core/devlink.c:devlink_fmsg_obj_nest_start
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
In net/core/devlink.c (ffffffff81e30777)
Location: net/core/devlink.c:7143
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_end
  - net/core/devlink.c:devlink_fmsg_pair_nest_start
  - net/core/devlink.c:devlink_fmsg_obj_nest_end
  - net/core/devlink.c:devlink_fmsg_obj_nest_start
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
In net/devlink/health.c (ffffffff82046827)
Location: net/devlink/health.c:660
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_fmsg_pair_nest_end
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
  - net/devlink/health.c:devlink_fmsg_obj_nest_end
  - net/devlink/health.c:devlink_fmsg_obj_nest_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82114361)
Location: net/devlink/health.c:683
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
Direct callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_binary_pair_put
  - net/devlink/health.c:devlink_fmsg_string_pair_put
  - net/devlink/health.c:devlink_fmsg_u64_pair_put
  - net/devlink/health.c:devlink_fmsg_u32_pair_put
  - net/devlink/health.c:devlink_fmsg_u8_pair_put
  - net/devlink/health.c:devlink_fmsg_bool_pair_put
  - net/devlink/health.c:devlink_fmsg_pair_nest_start
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff821119d0-ffffffff82111a5e: devlink_fmsg_nest_common.part.0 (STB_LOCAL)
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
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23fb8)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffff800010c23fb8-ffff800010c2401c: devlink_fmsg_nest_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3b4d8)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c0d3b4d8-c0d3b534: devlink_fmsg_nest_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d25a24)
Location: net/core/devlink.c:4150
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_fmsg_pair_nest_start
  - net/core/devlink.c:devlink_fmsg_nest_end
  - net/core/devlink.c:devlink_fmsg_obj_nest_start
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079c5d6)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffe00079c5d6-ffffffe00079c62a: devlink_fmsg_nest_common (STB_LOCAL)
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
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191c280)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8191c280-ffffffff8191c2d1: devlink_fmsg_nest_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d6030)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff818d6030-ffffffff818d6081: devlink_fmsg_nest_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196d410)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8196d410-ffffffff8196d461: devlink_fmsg_nest_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_fmsg_nest_common(struct devlink_fmsg *fmsg, int attrtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198f860)
Location: net/core/devlink.c:4150
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8198f860-ffffffff8198f8b1: devlink_fmsg_nest_common (STB_LOCAL)
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
