# Function: <code>devlink_fmsg_obj_nest_start</code>

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
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194eef1)
Location: net/core/devlink.c:4111
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81947320-ffffffff81947335: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81985c61)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8197c470-ffffffff8197c485: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5c00d)
Location: net/core/devlink.c:4603
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a53460-ffffffff81a534bc: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5ecc2)
Location: net/core/devlink.c:5292
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a59b00-ffffffff81a59b5c: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a49970)
Location: net/core/devlink.c:5495
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81a3c9a0-ffffffff81a3c9fc: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6108
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff81d3843b-ffffffff81d38450: devlink_fmsg_obj_nest_start.cold (STB_LOCAL)
ffffffff81af3740-ffffffff81af37ad: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:6603
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff81f04e0d-ffffffff81f04e22: devlink_fmsg_obj_nest_start.cold (STB_LOCAL)
ffffffff81c775d0-ffffffff81c77647: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:7158
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/core/devlink.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff820acdf6-ffffffff820ace0b: devlink_fmsg_obj_nest_start.cold (STB_LOCAL)
ffffffff81e300f0-ffffffff81e30167: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (0)
Location: net/devlink/health.c:675
Inline: False
Direct callers:
  - net/devlink/health.c:devlink_nl_cmd_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff821366e4-ffffffff821366f9: devlink_fmsg_obj_nest_start.cold (STB_LOCAL)
ffffffff82045e30-ffffffff82045ea7: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/health.c (ffffffff82114278)
Location: net/devlink/health.c:700
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff822182ee-ffffffff82218315: devlink_fmsg_obj_nest_start.cold (STB_LOCAL)
ffffffff82111ed0-ffffffff82111f3b: devlink_fmsg_obj_nest_start (STB_GLOBAL)
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
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2e548)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffff800010c24020-ffff800010c24050: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d45298)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c0d3b534-c0d3b554: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1a520)
Location: net/core/devlink.c:4165
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
c000000000d1a520-c000000000d1a5a4: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079ff28)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffe00079c62a-ffffffe00079c658: devlink_fmsg_obj_nest_start (STB_GLOBAL)
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
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81925ad1)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8191c2e0-ffffffff8191c2f5: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818df881)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff818d6090-ffffffff818d60a5: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81976c61)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8196d470-ffffffff8196d485: devlink_fmsg_obj_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devlink_fmsg_obj_nest_start(struct devlink_fmsg *fmsg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81999151)
Location: net/core/devlink.c:4165
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit
```
**Symbols:**

```
ffffffff8198f8c0-ffffffff8198f8d5: devlink_fmsg_obj_nest_start (STB_GLOBAL)
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
