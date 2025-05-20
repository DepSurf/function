# Function: <code>oom_killer_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool oom_killer_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190ac0)
Location: mm/oom_kill.c:458
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81190ac0-ffffffff81190ba2: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool oom_killer_disable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a51b0)
Location: mm/oom_kill.c:711
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811a51b0-ffffffff811a528a: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b59e0)
Location: mm/oom_kill.c:709
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811b59e0-ffffffff811b5afd: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd720)
Location: mm/oom_kill.c:713
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811bd720-ffffffff811bd84b: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d2360)
Location: mm/oom_kill.c:737
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811d2360-ffffffff811d248b: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:739
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff811f3fa2-ffffffff811f3fba: oom_killer_disable.cold.28 (STB_LOCAL)
ffffffff811f3290-ffffffff811f33ce: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:747
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81205f3e-ffffffff81205f54: oom_killer_disable.cold.31 (STB_LOCAL)
ffffffff81205280-ffffffff812053c7: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8121d32a-ffffffff8121d353: oom_killer_disable.cold (STB_LOCAL)
ffffffff8121cd80-ffffffff8121cead: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff8122ad07-ffffffff8122ad30: oom_killer_disable.cold (STB_LOCAL)
ffffffff8122a760-ffffffff8122a88d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:759
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81257ac5-ffffffff81257aee: oom_killer_disable.cold (STB_LOCAL)
ffffffff81257570-ffffffff8125769d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:761
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81be6e37-ffffffff81be6e60: oom_killer_disable.cold (STB_LOCAL)
ffffffff81262150-ffffffff8126227d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:760
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81bd8bce-ffffffff81bd8bf7: oom_killer_disable.cold (STB_LOCAL)
ffffffff81266be0-ffffffff81266d0d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:761
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81cba43f-ffffffff81cba468: oom_killer_disable.cold (STB_LOCAL)
ffffffff812a33e0-ffffffff812a350d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:818
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81e6bb5b-ffffffff81e6bb8e: oom_killer_disable.cold (STB_LOCAL)
ffffffff812fb300-ffffffff812fb425: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81365340)
Location: mm/oom_kill.c:817
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81365340-ffffffff81365492: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81397800)
Location: mm/oom_kill.c:817
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81397800-ffffffff81397952: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c1630)
Location: mm/oom_kill.c:814
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff813c1630-ffffffff813c1782: oom_killer_disable (STB_GLOBAL)
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
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b8870)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffff8000102b8870-ffff8000102b89f8: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e5028)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c04e5028-c04e517c: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c000000000370aa0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c000000000370aa0-c000000000370c5c: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dc580)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffe0001dc580-ffffffe0001dc68e: oom_killer_disable (STB_GLOBAL)
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
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81223357-ffffffff81223380: oom_killer_disable.cold (STB_LOCAL)
ffffffff81222db0-ffffffff81222edd: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff81216507-ffffffff81216530: oom_killer_disable.cold (STB_LOCAL)
ffffffff81215f60-ffffffff8121608d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff812210f7-ffffffff81221120: oom_killer_disable.cold (STB_LOCAL)
ffffffff81220b50-ffffffff81220c7d: oom_killer_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool oom_killer_disable(long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:757
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffff812302ac-ffffffff812302d5: oom_killer_disable.cold (STB_LOCAL)
ffffffff8122fcf0-ffffffff8122fe18: oom_killer_disable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long int timeout</code>
</li>
</ul>
</details>
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
