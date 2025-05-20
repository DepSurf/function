# Function: <code>spi_replace_transfers</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81644850)
Location: drivers/spi/spi.c:2213
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81644850-ffffffff81644b61: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81675920)
Location: drivers/spi/spi.c:2240
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81675920-ffffffff81675c31: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168a030)
Location: drivers/spi/spi.c:2403
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff8168a030-ffffffff8168a333: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f3870)
Location: drivers/spi/spi.c:2473
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff816f3870-ffffffff816f3b4a: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817301b0)
Location: drivers/spi/spi.c:2523
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff817301b0-ffffffff81730499: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817528c0)
Location: drivers/spi/spi.c:2589
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff817528c0-ffffffff81752bc1: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2794
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff817929ee-ffffffff81792a49: spi_replace_transfers.cold (STB_LOCAL)
ffffffff817907b0-ffffffff81790a7d: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff817b6550-ffffffff817b65ab: spi_replace_transfers.cold (STB_LOCAL)
ffffffff817b4390-ffffffff817b466e: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3004
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
```
**Symbols:**

```
ffffffff8187d1f4-ffffffff8187d24e: spi_replace_transfers.cold (STB_LOCAL)
ffffffff818798e0-ffffffff81879b24: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3093
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
```
**Symbols:**

```
ffffffff81c18c5e-ffffffff81c18cb8: spi_replace_transfers.cold (STB_LOCAL)
ffffffff81888280-ffffffff818884b3: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3100
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81c0a9e9-ffffffff81c0aa3b: spi_replace_transfers.cold (STB_LOCAL)
ffffffff8186aed0-ffffffff8186b107: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3229
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81d0f938-ffffffff81d0f98a: spi_replace_transfers.cold (STB_LOCAL)
ffffffff818fa070-ffffffff818fa2a5: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3222
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81a4ab50-ffffffff81a4acef: spi_replace_transfers.constprop.0 (STB_LOCAL)
ffffffff81eda62b-ffffffff81eda67f: spi_replace_transfers.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd1c90)
Location: drivers/spi/spi.c:3413
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff81bd1c90-ffffffff81bd1eaa: spi_replace_transfers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c29500)
Location: drivers/spi/spi.c:3419
Inline: True
Direct callers:
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
```
**Symbols:**

```
ffffffff81c29500-ffffffff81c2978d: spi_replace_transfers.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81cdbd40)
Location: drivers/spi/spi.c:3590
Inline: True
Direct callers:
  - drivers/spi/spi.c:__spi_split_transfer_maxsize
```
**Symbols:**

```
ffffffff81cdbd40-ffffffff81cdbfcd: spi_replace_transfers.constprop.0 (STB_LOCAL)
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
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c3848)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffff8000109c3848-ffff8000109c3b00: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab16dc)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
c0ab16dc-c0ab1930: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a88f40)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
c000000000a88f40-c000000000a89238: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000616bce)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffe000616bce-ffffffe000616dee: spi_replace_transfers (STB_GLOBAL)
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
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff8177b030-ffffffff8177b08b: spi_replace_transfers.cold (STB_LOCAL)
ffffffff81778e70-ffffffff8177914e: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff8175ade0-ffffffff8175ae3b: spi_replace_transfers.cold (STB_LOCAL)
ffffffff81758c20-ffffffff81758efe: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff817ab3d0-ffffffff817ab42b: spi_replace_transfers.cold (STB_LOCAL)
ffffffff817a9210-ffffffff817a94ee: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct spi_replaced_transfers *spi_replace_transfers(struct spi_message *msg, struct spi_transfer *xfer_first, size_t remove, size_t insert, spi_replaced_release_t release, size_t extradatasize, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2798
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_split_transfers_maxsize
```
**Symbols:**

```
ffffffff817c5360-ffffffff817c53bb: spi_replace_transfers.cold (STB_LOCAL)
ffffffff817c30a0-ffffffff817c337e: spi_replace_transfers (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
