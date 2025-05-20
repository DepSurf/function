# Function: <code>xb_init_comms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff814ccf00)
Location: drivers/xen/xenbus/xenbus_comms.c:205
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
**Symbols:**

```
ffffffff814ccf00-ffffffff814ccfd4: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8151da60)
Location: drivers/xen/xenbus/xenbus_comms.c:205
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff8151da60-ffffffff8151db34: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81549ef0)
Location: drivers/xen/xenbus/xenbus_comms.c:205
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81549ef0-ffffffff81549fc4: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8155e220)
Location: drivers/xen/xenbus/xenbus_comms.c:441
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff8155e220-ffffffff8155e34b: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815c2540)
Location: drivers/xen/xenbus/xenbus_comms.c:442
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff815c2540-ffffffff815c266b: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:442
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff815facdd-ffffffff815fad2e: xb_init_comms.cold.7 (STB_LOCAL)
ffffffff815fabb0-ffffffff815fac8a: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:442
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81615d8d-ffffffff81615dde: xb_init_comms.cold.7 (STB_LOCAL)
ffffffff81615c60-ffffffff81615d3a: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:442
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff816499ff-ffffffff81649a50: xb_init_comms.cold (STB_LOCAL)
ffffffff816498d0-ffffffff816499a8: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff8166be9f-ffffffff8166bef0: xb_init_comms.cold (STB_LOCAL)
ffffffff8166bd70-ffffffff8166be48: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff8171bedf-ffffffff8171bf30: xb_init_comms.cold (STB_LOCAL)
ffffffff8171bdb0-ffffffff8171be88: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81c05529-ffffffff81c0557a: xb_init_comms.cold (STB_LOCAL)
ffffffff81738df0-ffffffff81738ec8: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81bf718e-ffffffff81bf71df: xb_init_comms.cold (STB_LOCAL)
ffffffff8171c810-ffffffff8171c8e8: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81cf6070-ffffffff81cf60c1: xb_init_comms.cold (STB_LOCAL)
ffffffff8179b580-ffffffff8179b658: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81ebe158-ffffffff81ebe1a6: xb_init_comms.cold (STB_LOCAL)
ffffffff818d4ab0-ffffffff818d4b92: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a26d70)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81a26d70-ffffffff81a26e94: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a703e0)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81a703e0-ffffffff81a70504: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81ac24e0)
Location: drivers/xen/xenbus/xenbus_comms.c:438
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81ac24e0-ffffffff81ac2604: xb_init_comms (STB_GLOBAL)
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
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffff8000108360c0)
Location: drivers/xen/xenbus/xenbus_comms.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffff8000108360c0-ffff800010836210: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff81631d0f-ffffffff81631d60: xb_init_comms.cold (STB_LOCAL)
ffffffff81631be0-ffffffff81631cb8: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff8165fcdf-ffffffff8165fd30: xb_init_comms.cold (STB_LOCAL)
ffffffff8165fbb0-ffffffff8165fc88: xb_init_comms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xb_init_comms();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: drivers/xen/xenbus/xenbus_comms.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xs_resume
```
**Symbols:**

```
ffffffff8167a2df-ffffffff8167a330: xb_init_comms.cold (STB_LOCAL)
ffffffff8167a1b0-ffffffff8167a288: xb_init_comms (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
