# Function: <code>swsusp_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d5080)
Location: kernel/power/swap.c:889
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810d5080-ffffffff810d543a: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d9e90)
Location: kernel/power/swap.c:908
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810d9e90-ffffffff810da253: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e0970)
Location: kernel/power/swap.c:908
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810e0970-ffffffff810e0d30: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dfac0)
Location: kernel/power/swap.c:908
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810dfac0-ffffffff810dfe88: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e7d50)
Location: kernel/power/swap.c:903
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810e7d50-ffffffff810e8118: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:903
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810f045b-ffffffff810f0589: swsusp_write.cold.23 (STB_LOCAL)
ffffffff810ef190-ffffffff810ef439: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:903
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810fbae9-ffffffff810fbc17: swsusp_write.cold.22 (STB_LOCAL)
ffffffff810fa820-ffffffff810faad0: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff8110419f-ffffffff811042eb: swsusp_write.cold (STB_LOCAL)
ffffffff81102eb0-ffffffff81103162: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81110583-ffffffff811106cf: swsusp_write.cold (STB_LOCAL)
ffffffff8110f300-ffffffff8110f5b2: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff8111b7b9-ffffffff8111b819: swsusp_write.cold (STB_LOCAL)
ffffffff8111a650-ffffffff8111a804: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:911
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81be0fe3-ffffffff81be1075: swsusp_write.cold (STB_LOCAL)
ffffffff81115f50-ffffffff8111617f: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:911
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81bd3050-ffffffff81bd30e2: swsusp_write.cold (STB_LOCAL)
ffffffff81116640-ffffffff811168d2: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:911
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81cabd71-ffffffff81cabe03: swsusp_write.cold (STB_LOCAL)
ffffffff811368f0-ffffffff81136bb0: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:912
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81e5c1b1-ffffffff81e5c23d: swsusp_write.cold (STB_LOCAL)
ffffffff81158e00-ffffffff811590ee: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8118af80)
Location: kernel/power/swap.c:910
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff8118af80-ffffffff8118b2d9: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8119c6d0)
Location: kernel/power/swap.c:910
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff8119c6d0-ffffffff8119c9f0: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811ab820)
Location: kernel/power/swap.c:911
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff811ab820-ffffffff811abb3a: swsusp_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c2e5c)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
c03c2e5c-c03c3398: swsusp_write (STB_GLOBAL)
```
</details>
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
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:968
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81108b46-ffffffff81108c92: swsusp_write.cold (STB_LOCAL)
ffffffff811078a0-ffffffff81107b38: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff810f9a43-ffffffff810f9b8f: swsusp_write.cold (STB_LOCAL)
ffffffff810f87c0-ffffffff810f8a72: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81106a53-ffffffff81106b9f: swsusp_write.cold (STB_LOCAL)
ffffffff811057d0-ffffffff81105a82: swsusp_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int swsusp_write(unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:901
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernate
```
**Symbols:**

```
ffffffff81111e13-ffffffff81111f5f: swsusp_write.cold (STB_LOCAL)
ffffffff81110bb0-ffffffff81110e62: swsusp_write (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
