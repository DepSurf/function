# Function: <code>dev_map_enqueue</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ca000)
Location: kernel/bpf/devmap.c:336
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811ca000-ffffffff811ca13f: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dd910)
Location: kernel/bpf/devmap.c:337
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811dd910-ffffffff811dda5b: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f2f70)
Location: kernel/bpf/devmap.c:323
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f2f70-ffffffff811f3108: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ffd10)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811ffd10-ffffffff811ffea8: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81227800)
Location: kernel/bpf/devmap.c:502
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81227800-ffffffff8122795d: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122e350)
Location: kernel/bpf/devmap.c:487
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8122e350-ffffffff8122e4b3: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812331c0)
Location: kernel/bpf/devmap.c:480
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812331c0-ffffffff81233329: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126c700)
Location: kernel/bpf/devmap.c:529
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8126c700-ffffffff8126c849: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bb480)
Location: kernel/bpf/devmap.c:525
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff812bb480-ffffffff812bb5ac: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131e890)
Location: kernel/bpf/devmap.c:525
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8131e890-ffffffff8131e964: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134e6a0)
Location: kernel/bpf/devmap.c:526
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff8134e6a0-ffffffff8134e784: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_frame *xdpf, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81375ba0)
Location: kernel/bpf/devmap.c:535
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect_frame
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81375ba0-ffffffff81375c81: dev_map_enqueue (STB_GLOBAL)
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
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff800010287678)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffff800010287678-ffff800010287818: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b75f0)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c04b75f0-c04b7770: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c000000000332790)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
c000000000332790-c0000000003329c8: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bc146)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffe0001bc146-ffffffe0001bc2a0: dev_map_enqueue (STB_GLOBAL)
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
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f8330)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f8330-ffffffff811f84c8: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811eb080)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811eb080-ffffffff811eb218: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f6100)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff811f6100-ffffffff811f6298: dev_map_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_map_enqueue(struct bpf_dtab_netdev *dst, struct xdp_buff *xdp, struct net_device *dev_rx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81204670)
Location: kernel/bpf/devmap.c:461
Inline: False
Direct callers:
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81204670-ffffffff81204808: dev_map_enqueue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xdp_frame *xdpf</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xdp_buff *xdp</code>
</li>
</ul>
</details>
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
