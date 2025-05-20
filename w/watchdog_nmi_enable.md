# Function: <code>watchdog_nmi_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113ab84)
Location: kernel/watchdog.c:572
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811430b4)
Location: kernel/watchdog.c:588
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114d0a0)
Location: kernel/watchdog.c:246
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff8114d6a0-ffffffff8114d7ea: watchdog_nmi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114ee10)
Location: kernel/watchdog.c:122
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff8114f6b0-ffffffff8114f854: watchdog_nmi_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8115b5d0)
Location: kernel/watchdog.c:109
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff8115b5d0-ffffffff8115b5e2: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8116a130)
Location: kernel/watchdog.c:109
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff8116a130-ffffffff8116a142: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811770f0)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff811770f0-ffffffff81177102: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81183ed0)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff81183ed0-ffffffff81183ee2: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8118fd50)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff8118fd50-ffffffff8118fd62: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a48d0)
Location: kernel/watchdog.c:100
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff811a48d0-ffffffff811a48e2: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a1970)
Location: kernel/watchdog.c:98
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff811a1970-ffffffff811a1982: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a2640)
Location: kernel/watchdog.c:98
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff811a2640-ffffffff811a2652: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811cbe20)
Location: kernel/watchdog.c:98
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff811cbe20-ffffffff811cbe32: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811ffbc0)
Location: kernel/watchdog.c:98
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff811ffbc0-ffffffff811ffbd6: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81247610)
Location: kernel/watchdog.c:98
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff81247610-ffffffff81247626: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffff800010207558)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffff800010207558-ffff800010207574: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c044630c)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
c044630c-c0446328: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c000000000283c20)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
c000000000283c20-c000000000283c30: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffe000169d14)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffe000169d14-ffffffe000169d30: watchdog_nmi_enable (STB_WEAK)
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
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81188370)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff81188370-ffffffff81188382: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8117b4b0)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff8117b4b0-ffffffff8117b4c2: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81186140)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff81186140-ffffffff81186152: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int watchdog_nmi_enable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81193a90)
Location: kernel/watchdog.c:105
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_enable
```
**Symbols:**

```
ffffffff81193a90-ffffffff81193aa2: watchdog_nmi_enable (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
