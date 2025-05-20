# Function: <code>devlink_fmsg_alloc</code>

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
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81947290)
Location: net/core/devlink.c:4072
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81947290-ffffffff819472bd: devlink_fmsg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197c3e0)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8197c3e0-ffffffff8197c40d: devlink_fmsg_alloc (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a5bfdd)
Location: net/core/devlink.c:4564
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff81a5ec92)
Location: net/core/devlink.c:5253
Inline: True
Inline callers:
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
In net/core/devlink.c (ffffffff81a49940)
Location: net/core/devlink.c:5456
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
In net/core/devlink.c (ffffffff81af8531)
Location: net/core/devlink.c:6069
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
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
In net/core/devlink.c (ffffffff81c84251)
Location: net/core/devlink.c:6564
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
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
In net/core/devlink.c (ffffffff81e3c7e1)
Location: net/core/devlink.c:7119
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
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
In net/devlink/health.c (ffffffff8204818d)
Location: net/devlink/health.c:30
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
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
In net/devlink/health.c (ffffffff8211421d)
Location: net/devlink/health.c:31
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
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
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23f80)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffff800010c23f80-ffff800010c23fb8: devlink_fmsg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3b49c)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c0d3b49c-c0d3b4d8: devlink_fmsg_alloc (STB_LOCAL)
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
In net/core/devlink.c (c000000000d245e8)
Location: net/core/devlink.c:4126
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079c59e)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffe00079c59e-ffffffe00079c5d6: devlink_fmsg_alloc (STB_LOCAL)
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
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191c250)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8191c250-ffffffff8191c27d: devlink_fmsg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d6000)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff818d6000-ffffffff818d602d: devlink_fmsg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196d3e0)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8196d3e0-ffffffff8196d40d: devlink_fmsg_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct devlink_fmsg *devlink_fmsg_alloc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198f830)
Location: net/core/devlink.c:4126
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8198f830-ffffffff8198f85d: devlink_fmsg_alloc (STB_LOCAL)
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
