# Function: <code>sata_link_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c93f0)
Location: drivers/ata/libata-core.c:3576
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff815c93f0-ffffffff815c9534: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81621b80)
Location: drivers/ata/libata-core.c:3751
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81621b80-ffffffff81621ce0: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81652700)
Location: drivers/ata/libata-core.c:3793
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81652700-ffffffff81652860: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666d20)
Location: drivers/ata/libata-core.c:3870
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81666d20-ffffffff81666e80: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d0380)
Location: drivers/ata/libata-core.c:3879
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff816d0380-ffffffff816d04e0: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3875
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81712f48-ffffffff81712f6b: sata_link_resume.cold.46 (STB_LOCAL)
ffffffff8170cc90-ffffffff8170cdd1: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3875
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff817353f8-ffffffff8173541b: sata_link_resume.cold.47 (STB_LOCAL)
ffffffff8172f110-ffffffff8172f251: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81770de7-ffffffff81770e09: sata_link_resume.cold (STB_LOCAL)
ffffffff8176a8d0-ffffffff8176aa0f: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81794de5-ffffffff81794e07: sata_link_resume.cold (STB_LOCAL)
ffffffff8178e940-ffffffff8178ea7f: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81868460)
Location: drivers/ata/libata-sata.c:296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81868460-ffffffff818685bd: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81877270)
Location: drivers/ata/libata-sata.c:296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81877270-ffffffff818773cd: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81859af0)
Location: drivers/ata/libata-sata.c:296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81859af0-ffffffff81859c4d: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818e86a0)
Location: drivers/ata/libata-sata.c:296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff818e86a0-ffffffff818e87fd: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-sata.c (0)
Location: drivers/ata/libata-sata.c:296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81ed8d94-ffffffff81ed8e0f: sata_link_resume.cold (STB_LOCAL)
ffffffff81a39fe0-ffffffff81a3a137: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbf310)
Location: drivers/ata/libata-sata.c:296
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81bbf310-ffffffff81bbf4dc: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c16e70)
Location: drivers/ata/libata-sata.c:298
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81c16e70-ffffffff81c1703c: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6bf70)
Location: drivers/ata/libata-sata.c:298
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-sata.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81c6bf70-ffffffff81c6c13c: sata_link_resume (STB_GLOBAL)
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
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff8000109975c8)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffff8000109975c8-ffff800010997770: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a68110)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
c0a68110-c0a6828c: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5ada0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
c000000000a5ada0-c000000000a5af88: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f8ec4)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffe0005f8ec4-ffffffe0005f9016: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81759ef5-ffffffff81759f17: sata_link_resume.cold (STB_LOCAL)
ffffffff81753ab0-ffffffff81753bef: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81739d95-ffffffff81739db7: sata_link_resume.cold (STB_LOCAL)
ffffffff81733950-ffffffff81733a8f: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff81789c65-ffffffff81789c87: sata_link_resume.cold (STB_LOCAL)
ffffffff817837c0-ffffffff817838ff: sata_link_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sata_link_resume(struct ata_link *link, const long unsigned int *params, long unsigned int deadline);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
```
**Symbols:**

```
ffffffff817a3ab5-ffffffff817a3ad7: sata_link_resume.cold (STB_LOCAL)
ffffffff8179d680-ffffffff8179d7bf: sata_link_resume (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const long unsigned int *params</code> ➡️ <code>const unsigned int *params</code>
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
