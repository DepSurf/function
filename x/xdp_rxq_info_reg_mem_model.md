# Function: <code>xdp_rxq_info_reg_mem_model</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818ba5e0)
Location: net/core/xdp.c:238
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff818ba5e0-ffffffff818ba823: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1510)
Location: net/core/xdp.c:252
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff818e1510-ffffffff818e1753: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (ffffffff8192fd63)
Location: net/core/xdp.c:315
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff81930ec3-ffffffff81930edc: xdp_rxq_info_reg_mem_model.cold (STB_LOCAL)
ffffffff8192fd10-ffffffff8192ffd7: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81961f60)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff81961f60-ffffffff81962234: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35830)
Location: net/core/xdp.c:262
Inline: False
```
**Symbols:**

```
ffffffff81a35830-ffffffff81a35b15: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37f90)
Location: net/core/xdp.c:263
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_page_pool
```
**Symbols:**

```
ffffffff81a37f90-ffffffff81a38265: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1f590)
Location: net/core/xdp.c:263
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81a1f590-ffffffff81a1f865: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3360)
Location: net/core/xdp.c:264
Inline: True
```
**Symbols:**

```
ffffffff81ad30d0-ffffffff81ad3359: xdp_rxq_info_reg_mem_model.part.0 (STB_LOCAL)
ffffffff81d377c6-ffffffff81d377f0: xdp_rxq_info_reg_mem_model.part.0.cold (STB_LOCAL)
ffffffff81ad3360-ffffffff81ad33b7: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c50bf0)
Location: net/core/xdp.c:348
Inline: True
```
**Symbols:**

```
ffffffff81c50bf0-ffffffff81c50c8d: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e06280)
Location: net/core/xdp.c:348
Inline: False
```
**Symbols:**

```
ffffffff81e06280-ffffffff81e0631b: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e789c0)
Location: net/core/xdp.c:350
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_open
```
**Symbols:**

```
ffffffff81e789c0-ffffffff81e78a5b: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f38890)
Location: net/core/xdp.c:350
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_open
```
**Symbols:**

```
ffffffff81f38890-ffffffff81f3892b: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c061e8)
Location: net/core/xdp.c:289
Inline: True
```
**Symbols:**

```
ffff800010c061e8-ffff800010c06500: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1ee0c)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs
```
**Symbols:**

```
c0d1ee0c-c0d1f12c: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf0120)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
c000000000cf0120-c000000000cf0578: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe00078453c)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffe00078453c-ffffffe000784806: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81901f30)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff81901f30-ffffffff81902204: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bbd60)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff818bbd60-ffffffff818bc034: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81952f60)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff81952f60-ffffffff81953234: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg_mem_model(struct xdp_rxq_info *xdp_rxq, enum xdp_mem_type type, void *allocator);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81974a50)
Location: net/core/xdp.c:289
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
```
**Symbols:**

```
ffffffff81974a50-ffffffff81974d3d: xdp_rxq_info_reg_mem_model (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
