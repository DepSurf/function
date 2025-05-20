# Function: <code>devlink_fmsg_free</code>

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
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81946e60)
Location: net/core/devlink.c:4085
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff81946e60-ffffffff81946ec5: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197bfb0)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8197bfb0-ffffffff8197c015: devlink_fmsg_free (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81a59fd5)
Location: net/core/devlink.c:4577
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
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
In net/core/devlink.c (ffffffff81a5b20a)
Location: net/core/devlink.c:5266
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_put
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
In net/core/devlink.c (ffffffff81a3deda)
Location: net/core/devlink.c:5469
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_put
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
In net/core/devlink.c (ffffffff81af563a)
Location: net/core/devlink.c:6082
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_put
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
In net/core/devlink.c (ffffffff81c79b3c)
Location: net/core/devlink.c:6577
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
  - net/core/devlink.c:devlink_health_reporter_put
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
In net/core/devlink.c (ffffffff81e3296c)
Location: net/core/devlink.c:7132
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
  - net/core/devlink.c:devlink_health_reporter_put
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
In net/devlink/health.c (ffffffff8204851c)
Location: net/devlink/health.c:43
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_reporter_destroy
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
In net/devlink/health.c (ffffffff82114643)
Location: net/devlink/health.c:44
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_dump_clear_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_reporter_destroy
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
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23a78)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffff800010c23a78-ffff800010c23af4: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3afa8)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
c0d3afa8-c0d3b00c: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d174e0)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
c000000000d174e0-c000000000d175a8: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079c1ae)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffe00079c1ae-ffffffe00079c214: devlink_fmsg_free (STB_LOCAL)
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
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191be20)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8191be20-ffffffff8191be85: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5bd0)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff818d5bd0-ffffffff818d5c35: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196cfb0)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8196cfb0-ffffffff8196d015: devlink_fmsg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devlink_fmsg_free(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198f400)
Location: net/core/devlink.c:4139
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_reporter_destroy
```
**Symbols:**

```
ffffffff8198f400-ffffffff8198f465: devlink_fmsg_free (STB_LOCAL)
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
