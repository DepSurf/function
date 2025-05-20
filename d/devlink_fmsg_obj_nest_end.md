# Function: <code>devlink_fmsg_obj_nest_end</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194ef54)
Location: net/core/devlink.c:4122
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81947340-ffffffff81947355: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985cc4)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8197c490-ffffffff8197c4a5: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5c06a)
Location: net/core/devlink.c:4620
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a53520-ffffffff81a5357c: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ed1f)
Location: net/core/devlink.c:5309
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a59bc0-ffffffff81a59c1c: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a499d2)
Location: net/core/devlink.c:5512
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a3cc50-ffffffff81a3ccac: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6125
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81d384bf-ffffffff81d38505: devlink_fmsg_obj_nest_end.cold (STB_LOCAL)
ffffffff81af3b70-ffffffff81af3be0: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6620
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff81f04ea5-ffffffff81f04eeb: devlink_fmsg_obj_nest_end.cold (STB_LOCAL)
ffffffff81c77d70-ffffffff81c77dea: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7175
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff820ace8e-ffffffff820aced4: devlink_fmsg_obj_nest_end.cold (STB_LOCAL)
ffffffff81e307e0-ffffffff81e3085a: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:692
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff82136863-ffffffff821368a9: devlink_fmsg_obj_nest_end.cold (STB_LOCAL)
ffffffff82046bb0-ffffffff82046c2a: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82114320)
Location: net/devlink/health.c:713
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff82218410-ffffffff82218437: devlink_fmsg_obj_nest_end.cold (STB_LOCAL)
ffffffff821127d0-ffffffff821128a3: devlink_fmsg_obj_nest_end (STB_GLOBAL)
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
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2e5b0)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffff800010c24050-ffff800010c24080: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d452f8)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c0d3b554-c0d3b574: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d246a0)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c000000000d1a640-c000000000d1a654: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ff7a)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffe00079c658-ffffffe00079c686: devlink_fmsg_obj_nest_end (STB_GLOBAL)
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
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925b34)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8191c300-ffffffff8191c315: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818df8e4)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff818d60b0-ffffffff818d60c5: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976cc4)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8196d490-ffffffff8196d4a5: devlink_fmsg_obj_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_end(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819991b4)
Location: net/core/devlink.c:4176
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8198f8e0-ffffffff8198f8f5: devlink_fmsg_obj_nest_end (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
