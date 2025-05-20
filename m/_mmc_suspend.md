# Function: <code>_mmc_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c47e0)
Location: drivers/mmc/core/mmc.c:1800
Inline: False
```
**Symbols:**

```
ffffffff816c47e0-ffffffff816c4aa8: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81726530)
Location: drivers/mmc/core/mmc.c:1901
Inline: False
```
**Symbols:**

```
ffffffff81726530-ffffffff817267f5: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8175a8b0)
Location: drivers/mmc/core/mmc.c:1927
Inline: False
```
**Symbols:**

```
ffffffff8175a8b0-ffffffff8175ab6b: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81776cd0)
Location: drivers/mmc/core/mmc.c:1954
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81776cd0-ffffffff81776f71: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817ed0e0)
Location: drivers/mmc/core/mmc.c:1969
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff817ed0e0-ffffffff817ed383: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81836230-ffffffff818364b4: _mmc_suspend (STB_LOCAL)
ffffffff818387bd-ffffffff818387e3: _mmc_suspend.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2006
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81862240-ffffffff818624a4: _mmc_suspend (STB_LOCAL)
ffffffff818647bd-ffffffff818647e3: _mmc_suspend.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2013
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff818a6390-ffffffff818a6600: _mmc_suspend (STB_LOCAL)
ffffffff818a87ad-ffffffff818a87d3: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff818d87e0-ffffffff818d8a5f: _mmc_suspend (STB_LOCAL)
ffffffff818dac08-ffffffff818dac2e: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2025
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff819ab5f0-ffffffff819ab72f: _mmc_suspend (STB_LOCAL)
ffffffff819ad6c5-ffffffff819ad6eb: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2036
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff819ae190-ffffffff819ae2d6: _mmc_suspend (STB_LOCAL)
ffffffff81c2a85a-ffffffff81c2a880: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2038
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff819926a0-ffffffff8199290b: _mmc_suspend (STB_LOCAL)
ffffffff81c1cc12-ffffffff81c1cc38: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2061
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81a3e0c0-ffffffff81a3e342: _mmc_suspend (STB_LOCAL)
ffffffff81d2d8c6-ffffffff81d2d8eb: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2096
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81bab380-ffffffff81bab60b: _mmc_suspend (STB_LOCAL)
ffffffff81ef9ccf-ffffffff81ef9cfd: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4e6a0)
Location: drivers/mmc/core/mmc.c:2096
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81d4e6a0-ffffffff81d4e953: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db8fb0)
Location: drivers/mmc/core/mmc.c:2096
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81db8fb0-ffffffff81db926d: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e71500)
Location: drivers/mmc/core/mmc.c:2121
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff81e71500-ffffffff81e717bd: _mmc_suspend (STB_LOCAL)
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
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b32e40)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffff800010b32e40-ffff800010b330cc: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0d8b4)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
c0c0d8b4-c0c0db58: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2d1a0)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
c000000000c2d1a0-c000000000c2d520: _mmc_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070b5cc)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffe00070b5cc-ffffffe00070b80e: _mmc_suspend (STB_LOCAL)
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
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff8187c1a0-ffffffff8187c41f: _mmc_suspend (STB_LOCAL)
ffffffff8187e5c8-ffffffff8187e5ee: _mmc_suspend.cold (STB_LOCAL)
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
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff818cd640-ffffffff818cd8bf: _mmc_suspend (STB_LOCAL)
ffffffff818cfa68-ffffffff818cfa8e: _mmc_suspend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int _mmc_suspend(struct mmc_host *host, bool is_suspend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:2016
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_shutdown
```
**Symbols:**

```
ffffffff818ea160-ffffffff818ea3df: _mmc_suspend (STB_LOCAL)
ffffffff818ec588-ffffffff818ec5ae: _mmc_suspend.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
