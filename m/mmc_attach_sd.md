# Function: <code>mmc_attach_sd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff816c7e90)
Location: drivers/mmc/core/sd.c:1200
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff816c7e90-ffffffff816c8003: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8172ae50)
Location: drivers/mmc/core/sd.c:1218
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff8172ae50-ffffffff8172afc4: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8175df20)
Location: drivers/mmc/core/sd.c:1214
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff8175df20-ffffffff8175e089: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8177c660)
Location: drivers/mmc/core/sd.c:1201
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff8177c660-ffffffff8177c7b8: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff817f2be0)
Location: drivers/mmc/core/sd.c:1244
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff817f2be0-ffffffff817f2d3c: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1246
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff8183c176-ffffffff8183c18e: mmc_attach_sd.cold.22 (STB_LOCAL)
ffffffff8183bdb0-ffffffff8183bef7: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1246
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81868106-ffffffff8186811e: mmc_attach_sd.cold.22 (STB_LOCAL)
ffffffff81867d40-ffffffff81867e87: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff818ac053-ffffffff818ac07e: mmc_attach_sd.cold (STB_LOCAL)
ffffffff818abc20-ffffffff818abd6e: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff818de4a7-ffffffff818de4bf: mmc_attach_sd.cold (STB_LOCAL)
ffffffff818de080-ffffffff818de1d5: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1303
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff819b12bd-ffffffff819b12d5: mmc_attach_sd.cold (STB_LOCAL)
ffffffff819b0e70-ffffffff819b0fc5: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1333
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81c2b10d-ffffffff81c2b125: mmc_attach_sd.cold (STB_LOCAL)
ffffffff819b33e0-ffffffff819b3535: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1341
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81c1d487-ffffffff81c1d49f: mmc_attach_sd.cold (STB_LOCAL)
ffffffff81997bc0-ffffffff81997d15: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1810
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81d2e527-ffffffff81d2e53f: mmc_attach_sd.cold (STB_LOCAL)
ffffffff81a44380-ffffffff81a444d5: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1817
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81efa94a-ffffffff81efa962: mmc_attach_sd.cold (STB_LOCAL)
ffffffff81bb1e50-ffffffff81bb1fb3: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d560b0)
Location: drivers/mmc/core/sd.c:1813
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81d560b0-ffffffff81d56223: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dc0a20)
Location: drivers/mmc/core/sd.c:1813
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81dc0a20-ffffffff81dc0b93: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e792b0)
Location: drivers/mmc/core/sd.c:1827
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan_try_freq
```
**Symbols:**

```
ffffffff81e792b0-ffffffff81e79423: mmc_attach_sd (STB_GLOBAL)
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
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffff800010b38408)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffff800010b38408-ffff800010b3857c: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c0c12d68)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
c0c12d68-c0c12ef0: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c000000000c34130)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
c000000000c34130-c000000000c34314: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffe0007102c2)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffe0007102c2-ffffffe0007103fa: mmc_attach_sd (STB_GLOBAL)
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
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff81881e67-ffffffff81881e7f: mmc_attach_sd.cold (STB_LOCAL)
ffffffff81881a40-ffffffff81881b95: mmc_attach_sd (STB_GLOBAL)
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
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff818d3307-ffffffff818d331f: mmc_attach_sd.cold (STB_LOCAL)
ffffffff818d2ee0-ffffffff818d3035: mmc_attach_sd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_attach_sd(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1269
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_rescan
```
**Symbols:**

```
ffffffff818efe27-ffffffff818efe3f: mmc_attach_sd.cold (STB_LOCAL)
ffffffff818efa00-ffffffff818efb55: mmc_attach_sd (STB_GLOBAL)
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
