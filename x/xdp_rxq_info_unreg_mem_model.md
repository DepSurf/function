# Function: <code>xdp_rxq_info_unreg_mem_model</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1cb0)
Location: net/core/xdp.c:97
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff818e1cb0-ffffffff818e1f39: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81930b70)
Location: net/core/xdp.c:146
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81930b70-ffffffff81930d6f: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81962ec0)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81962ec0-ffffffff8196301e: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35bd0)
Location: net/core/xdp.c:113
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81a35bd0-ffffffff81a35c55: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37e00)
Location: net/core/xdp.c:113
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81a37e00-ffffffff81a37e76: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1efa0)
Location: net/core/xdp.c:113
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81a1efa0-ffffffff81a1f016: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3040)
Location: net/core/xdp.c:113
Inline: True
```
**Symbols:**

```
ffffffff81ad3040-ffffffff81ad30c2: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c5173e)
Location: net/core/xdp.c:135
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81c515e0-ffffffff81c51616: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e0689e)
Location: net/core/xdp.c:135
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81e05f10-ffffffff81e05f46: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e79205)
Location: net/core/xdp.c:137
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81e78b70-ffffffff81e78ba6: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f390d5)
Location: net/core/xdp.c:137
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_rxq_info_reg
  - net/core/xdp.c:__xdp_rxq_info_reg
```
**Symbols:**

```
ffffffff81f38a40-ffffffff81f38a76: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
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
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06a30)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffff800010c06a30-ffff800010c06bb4: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1fdb0)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
c0d1fdb0-c0d1fec4: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1040)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
c000000000cf1040-c000000000cf1264: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000784ef8)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffe000784ef8-ffffffe000785034: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
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
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902e90)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81902e90-ffffffff81902fee: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bccc0)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff818bccc0-ffffffff818bce1e: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81953ec0)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81953ec0-ffffffff8195401e: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_rxq_info_unreg_mem_model(struct xdp_rxq_info *xdp_rxq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81975950)
Location: net/core/xdp.c:137
Inline: False
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg
```
**Symbols:**

```
ffffffff81975950-ffffffff81975cc5: xdp_rxq_info_unreg_mem_model (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
