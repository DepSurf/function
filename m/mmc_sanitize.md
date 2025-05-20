# Function: <code>mmc_sanitize</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_sanitize(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:1034
Inline: False
```
**Symbols:**

```
ffffffff819af35d-ffffffff819af4b2: mmc_sanitize.cold (STB_LOCAL)
ffffffff819aefb0-ffffffff819af09d: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_sanitize(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:1034
Inline: False
```
**Symbols:**

```
ffffffff81c2ac76-ffffffff81c2adcb: mmc_sanitize.cold (STB_LOCAL)
ffffffff819b1610-ffffffff819b16fd: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_sanitize(struct mmc_card *card, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:1012
Inline: False
```
**Symbols:**

```
ffffffff81c1d0a0-ffffffff81c1d11e: mmc_sanitize.cold (STB_LOCAL)
ffffffff81995d40-ffffffff81995e21: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_sanitize(struct mmc_card *card, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:1005
Inline: False
```
**Symbols:**

```
ffffffff81d2df23-ffffffff81d2dfa1: mmc_sanitize.cold (STB_LOCAL)
ffffffff81a41c10-ffffffff81a41ceb: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_sanitize(struct mmc_card *card, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:1035
Inline: False
```
**Symbols:**

```
ffffffff81efa34a-ffffffff81efa3c5: mmc_sanitize.cold (STB_LOCAL)
ffffffff81baf2f0-ffffffff81baf3e6: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_sanitize(struct mmc_card *card, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d52cf0)
Location: drivers/mmc/core/mmc_ops.c:1035
Inline: False
```
**Symbols:**

```
ffffffff81d52cf0-ffffffff81d52e3a: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_sanitize(struct mmc_card *card, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd6a0)
Location: drivers/mmc/core/mmc_ops.c:1036
Inline: False
```
**Symbols:**

```
ffffffff81dbd6a0-ffffffff81dbd80b: mmc_sanitize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_sanitize(struct mmc_card *card, unsigned int timeout_ms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75cd0)
Location: drivers/mmc/core/mmc_ops.c:1036
Inline: False
```
**Symbols:**

```
ffffffff81e75cd0-ffffffff81e75e3b: mmc_sanitize (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int timeout_ms</code>
</li>
</ul>
</details>
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
