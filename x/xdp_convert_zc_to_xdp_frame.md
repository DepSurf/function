# Function: <code>xdp_convert_zc_to_xdp_frame</code>

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
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1b80)
Location: net/core/xdp.c:413
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff818e1b80-ffffffff818e1ca3: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81930600)
Location: net/core/xdp.c:500
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81930600-ffffffff81930730: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81962760)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81962760-ffffffff81962890: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a356b0)
Location: net/core/xdp.c:434
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a356b0-ffffffff81a357ce: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37a50)
Location: net/core/xdp.c:471
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a37a50-ffffffff81a37b6e: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1ebe0)
Location: net/core/xdp.c:472
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a1ebe0-ffffffff81a1ecfe: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad2c80)
Location: net/core/xdp.c:473
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81ad2c80-ffffffff81ad2d9e: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c507a0)
Location: net/core/xdp.c:559
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81c507a0-ffffffff81c508d4: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e05c20)
Location: net/core/xdp.c:557
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81e05c20-ffffffff81e05d53: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e78550)
Location: net/core/xdp.c:544
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81e78550-ffffffff81e78683: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f39150)
Location: net/core/xdp.c:544
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/filter.c:xdp_do_redirect
```
**Symbols:**

```
ffffffff81f39150-ffffffff81f39300: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
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
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c07070)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffff800010c07070-ffff800010c071a4: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d20268)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/core/filter.c:xdp_do_redirect_slow
```
**Symbols:**

```
c0d20268-c0d20384: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1900)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
c000000000cf1900-c000000000cf1aac: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000785458)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffe000785458-ffffffe00078555e: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
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
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81902730)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81902730-ffffffff81902860: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc560)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff818bc560-ffffffff818bc690: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81953760)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81953760-ffffffff81953890: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xdp_frame *xdp_convert_zc_to_xdp_frame(struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81975280)
Location: net/core/xdp.c:467
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/cpumap.c:cpu_map_enqueue
```
**Symbols:**

```
ffffffff81975280-ffffffff819753b0: xdp_convert_zc_to_xdp_frame (STB_GLOBAL)
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
