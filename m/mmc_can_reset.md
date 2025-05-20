# Function: <code>mmc_can_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_can_reset(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c22b0)
Location: drivers/mmc/core/mmc.c:1956
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_reset
```
**Symbols:**

```
ffffffff816c22b0-ffffffff816c22cd: mmc_can_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_can_reset(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8172799e)
Location: drivers/mmc/core/mmc.c:2046
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_reset
```
**Symbols:**

```
ffffffff81725040-ffffffff8172505d: mmc_can_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mmc_can_reset(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8175a7be)
Location: drivers/mmc/core/mmc.c:2066
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_reset
```
**Symbols:**

```
ffffffff81757fc0-ffffffff81757fdd: mmc_can_reset (STB_GLOBAL)
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
In drivers/mmc/core/mmc.c (ffffffff81779026)
Location: drivers/mmc/core/mmc.c:2093
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_reset
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
In drivers/mmc/core/mmc.c (ffffffff817ef476)
Location: drivers/mmc/core/mmc.c:2108
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_reset
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
In drivers/mmc/core/mmc.c (ffffffff818382b6)
Location: drivers/mmc/core/mmc.c:2122
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffff818642a9)
Location: drivers/mmc/core/mmc.c:2139
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffff818a812d)
Location: drivers/mmc/core/mmc.c:2146
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffff818da58d)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819acfed)
Location: drivers/mmc/core/mmc.c:2158
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819afbcd)
Location: drivers/mmc/core/mmc.c:2170
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8199439d)
Location: drivers/mmc/core/mmc.c:2172
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81a400ca)
Location: drivers/mmc/core/mmc.c:2195
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81bad476)
Location: drivers/mmc/core/mmc.c:2230
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d50ab6)
Location: drivers/mmc/core/mmc.c:2230
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81dbb476)
Location: drivers/mmc/core/mmc.c:2230
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e73a46)
Location: drivers/mmc/core/mmc.c:2255
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffff800010b34a40)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (c0c0f588)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (c000000000c2f4e8)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffe00070cfe6)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffff8187df4d)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffff818cf3ed)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
In drivers/mmc/core/mmc.c (ffffffff818ebf0d)
Location: drivers/mmc/core/mmc.c:2149
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
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
</ul>
