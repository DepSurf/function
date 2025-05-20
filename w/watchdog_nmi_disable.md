# Function: <code>watchdog_nmi_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8113a820)
Location: kernel/watchdog.c:645
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog
```
**Symbols:**

```
ffffffff8113a820-ffffffff8113a887: watchdog_nmi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81142d50)
Location: kernel/watchdog.c:661
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff81142d50-ffffffff81142db7: watchdog_nmi_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114d170)
Location: kernel/watchdog.c:250
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff8114d7f0-ffffffff8114d857: watchdog_nmi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8114eee0)
Location: kernel/watchdog.c:126
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff8114f860-ffffffff8114f8c4: watchdog_nmi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8115b6b0)
Location: kernel/watchdog.c:115
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff8115b6b0-ffffffff8115b6c0: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8116a210)
Location: kernel/watchdog.c:115
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff8116a210-ffffffff8116a220: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81177200)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff81177200-ffffffff81177210: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81183fe0)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff81183fe0-ffffffff81183ff0: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8118fe60)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff8118fe60-ffffffff8118fe70: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a49e0)
Location: kernel/watchdog.c:106
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff811a49e0-ffffffff811a49f0: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a1a80)
Location: kernel/watchdog.c:104
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff811a1a80-ffffffff811a1a90: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811a2770)
Location: kernel/watchdog.c:104
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff811a2770-ffffffff811a2780: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811cbf50)
Location: kernel/watchdog.c:104
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
```
**Symbols:**

```
ffffffff811cbf50-ffffffff811cbf60: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff811ffd00)
Location: kernel/watchdog.c:104
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
```
**Symbols:**

```
ffffffff811ffd00-ffffffff811ffd14: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81247780)
Location: kernel/watchdog.c:104
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_offline_cpu
  - kernel/watchdog.c:softlockup_stop_fn
```
**Symbols:**

```
ffffffff81247780-ffffffff81247794: watchdog_nmi_disable (STB_WEAK)
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
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffff800010207690)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffff800010207690-ffff8000102076a8: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c044646c)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
c044646c-c0446484: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (c000000000283dc0)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
c000000000283dc0-c000000000283dcc: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffe000169e34)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffe000169e34-ffffffe000169e4e: watchdog_nmi_disable (STB_WEAK)
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
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81188480)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff81188480-ffffffff81188490: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff8117b5c0)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff8117b5c0-ffffffff8117b5d0: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81186250)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff81186250-ffffffff81186260: watchdog_nmi_disable (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void watchdog_nmi_disable(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watchdog.c (ffffffff81193ba0)
Location: kernel/watchdog.c:111
Inline: False
Direct callers:
  - kernel/watchdog.c:watchdog_disable
```
**Symbols:**

```
ffffffff81193ba0-ffffffff81193bb0: watchdog_nmi_disable (STB_WEAK)
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
