# Function: <code>mmc_rescan_try_freq</code>

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
In drivers/mmc/core/core.c (ffffffff816c119a)
Location: drivers/mmc/core/core.c:2459
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
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
In drivers/mmc/core/core.c (ffffffff81723df9)
Location: drivers/mmc/core/core.c:2514
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81756ce8)
Location: drivers/mmc/core/core.c:2612
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81774bff)
Location: drivers/mmc/core/core.c:2445
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817eae55)
Location: drivers/mmc/core/core.c:2652
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833d5f)
Location: drivers/mmc/core/core.c:2487
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185fcef)
Location: drivers/mmc/core/core.c:2476
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818a388a)
Location: drivers/mmc/core/core.c:2164
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d5df7)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7610)
Location: drivers/mmc/core/core.c:2114
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff819a7610-ffffffff819a77c6: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819aa860)
Location: drivers/mmc/core/core.c:2124
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff819aa860-ffffffff819aaa2e: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198f100)
Location: drivers/mmc/core/core.c:2050
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff8198f100-ffffffff8198f2ce: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3a7f0)
Location: drivers/mmc/core/core.c:2035
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81a3a7f0-ffffffff81a3a9c3: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba7680)
Location: drivers/mmc/core/core.c:2037
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81ba7680-ffffffff81ba7828: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d49d10)
Location: drivers/mmc/core/core.c:2049
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81d49d10-ffffffff81d49ea9: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db4580)
Location: drivers/mmc/core/core.c:2049
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81db4580-ffffffff81db4717: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_rescan_try_freq(struct mmc_host *host, unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6cdd0)
Location: drivers/mmc/core/core.c:2054
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81e6cdd0-ffffffff81e6cf5e: mmc_rescan_try_freq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2fb24)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0ad04)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c295b8)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708bc6)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818797b7)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818cac57)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e7777)
Location: drivers/mmc/core/core.c:2166
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
