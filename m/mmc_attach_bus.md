# Function: <code>mmc_attach_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816c0b20)
Location: drivers/mmc/core/core.c:1823
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff816c0b20-ffffffff816c0baf: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81723850)
Location: drivers/mmc/core/core.c:1839
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81723850-ffffffff817238df: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817566a0)
Location: drivers/mmc/core/core.c:1907
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff817566a0-ffffffff81756763: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81774690)
Location: drivers/mmc/core/core.c:1732
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81774690-ffffffff8177470e: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea8c0)
Location: drivers/mmc/core/core.c:1946
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff817ea8c0-ffffffff817ea93e: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81833810)
Location: drivers/mmc/core/core.c:1750
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81833810-ffffffff81833886: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185f7a0)
Location: drivers/mmc/core/core.c:1753
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8185f7a0-ffffffff8185f816: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818a4059-ffffffff818a40a2: mmc_attach_bus.cold (STB_LOCAL)
ffffffff818a3340-ffffffff818a33be: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d5630)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818d5630-ffffffff818d56ae: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a8000)
Location: drivers/mmc/core/core.c:1418
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819a8000-ffffffff819a807e: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819ab260)
Location: drivers/mmc/core/core.c:1418
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819ab260-ffffffff819ab2de: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198f970)
Location: drivers/mmc/core/core.c:1387
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8198f970-ffffffff8198f982: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a3b0c0)
Location: drivers/mmc/core/core.c:1388
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81a3b0c0-ffffffff81a3b0d2: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba7fb0)
Location: drivers/mmc/core/core.c:1388
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81ba7fb0-ffffffff81ba7fca: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4a780)
Location: drivers/mmc/core/core.c:1395
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81d4a780-ffffffff81d4a79a: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db4fd0)
Location: drivers/mmc/core/core.c:1395
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81db4fd0-ffffffff81db4fea: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6d420)
Location: drivers/mmc/core/core.c:1400
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81e6d420-ffffffff81e6d43a: mmc_attach_bus (STB_GLOBAL)
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
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2eeb0)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffff800010b2eeb0-ffff800010b2efac: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a39c)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c0c0a39c-c0c0a46c: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c28a00)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c000000000c28a00-c000000000c28ab8: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe00070869a)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffe00070869a-ffffffe00070872a: mmc_attach_bus (STB_GLOBAL)
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
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81878ff0)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81878ff0-ffffffff8187906e: mmc_attach_bus (STB_GLOBAL)
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
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818ca490)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818ca490-ffffffff818ca50e: mmc_attach_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_attach_bus(struct mmc_host *host, const struct mmc_bus_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e6fb0)
Location: drivers/mmc/core/core.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818e6fb0-ffffffff818e702e: mmc_attach_bus (STB_GLOBAL)
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
