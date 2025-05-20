# Function: <code>mmc_of_parse_voltage</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818a4eb0)
Location: drivers/mmc/core/host.c:357
Inline: False
```
**Symbols:**

```
ffffffff818a4eb0-ffffffff818a4edb: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818d7320)
Location: drivers/mmc/core/host.c:354
Inline: False
```
**Symbols:**

```
ffffffff818d7320-ffffffff818d734b: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819a9c70)
Location: drivers/mmc/core/host.c:340
Inline: False
```
**Symbols:**

```
ffffffff819a9c70-ffffffff819a9c9b: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819ac880)
Location: drivers/mmc/core/host.c:344
Inline: False
```
**Symbols:**

```
ffffffff819ac880-ffffffff819ac8ab: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_of_parse_voltage(struct mmc_host *host, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/host.c:427
Inline: False
```
**Symbols:**

```
ffffffff81c1c9d2-ffffffff81c1ca1c: mmc_of_parse_voltage.cold (STB_LOCAL)
ffffffff819910f0-ffffffff81991225: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_of_parse_voltage(struct mmc_host *host, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/host.c:448
Inline: False
```
**Symbols:**

```
ffffffff81d2d5d7-ffffffff81d2d621: mmc_of_parse_voltage.cold (STB_LOCAL)
ffffffff81a3cb70-ffffffff81a3cca2: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_of_parse_voltage(struct mmc_host *host, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (0)
Location: drivers/mmc/core/host.c:448
Inline: False
```
**Symbols:**

```
ffffffff81ef9a10-ffffffff81ef9a52: mmc_of_parse_voltage.cold (STB_LOCAL)
ffffffff81ba9c10-ffffffff81ba9d43: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct mmc_host *host, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81d4ca20)
Location: drivers/mmc/core/host.c:448
Inline: False
```
**Symbols:**

```
ffffffff81d4ca20-ffffffff81d4cbb0: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct mmc_host *host, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81db7390)
Location: drivers/mmc/core/host.c:448
Inline: False
```
**Symbols:**

```
ffffffff81db7390-ffffffff81db7520: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct mmc_host *host, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81e6f860)
Location: drivers/mmc/core/host.c:447
Inline: False
```
**Symbols:**

```
ffffffff81e6f860-ffffffff81e6f9f0: mmc_of_parse_voltage (STB_GLOBAL)
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
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffff800010b31500)
Location: drivers/mmc/core/host.c:354
Inline: False
```
**Symbols:**

```
ffff800010b31500-ffff800010b31640: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (c0c0c20c)
Location: drivers/mmc/core/host.c:354
Inline: False
Direct callers:
  - drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe
```
**Symbols:**

```
c0c0c20c-c0c0c33c: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (c000000000c2b230)
Location: drivers/mmc/core/host.c:354
Inline: False
```
**Symbols:**

```
c000000000c2b230-c000000000c2b3c0: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffe000709f78)
Location: drivers/mmc/core/host.c:354
Inline: False
Direct callers:
  - drivers/mmc/host/of_mmc_spi.c:mmc_spi_get_pdata
```
**Symbols:**

```
ffffffe000709f78-ffffffe00070a0b0: mmc_of_parse_voltage (STB_GLOBAL)
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
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff8187ace0)
Location: drivers/mmc/core/host.c:354
Inline: False
```
**Symbols:**

```
ffffffff8187ace0-ffffffff8187ad0b: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818cc180)
Location: drivers/mmc/core/host.c:354
Inline: False
```
**Symbols:**

```
ffffffff818cc180-ffffffff818cc1ab: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_of_parse_voltage(struct device_node *np, u32 *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818e8ca0)
Location: drivers/mmc/core/host.c:354
Inline: False
```
**Symbols:**

```
ffffffff818e8ca0-ffffffff818e8ccb: mmc_of_parse_voltage (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmc_host *host</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device_node *np</code>
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
