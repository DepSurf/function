# Function: <code>xdp_do_redirect</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818660a0)
Location: net/core/filter.c:2645
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
```
**Symbols:**

```
ffffffff818660a0-ffffffff81866460: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b4480)
Location: net/core/filter.c:3285
Inline: False
```
**Symbols:**

```
ffffffff818b4480-ffffffff818b4945: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818da220)
Location: net/core/filter.c:3501
Inline: False
```
**Symbols:**

```
ffffffff818da220-ffffffff818da4f2: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819289e0)
Location: net/core/filter.c:3630
Inline: False
```
**Symbols:**

```
ffffffff819289e0-ffffffff81928c01: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195b0b0)
Location: net/core/filter.c:3636
Inline: False
```
**Symbols:**

```
ffffffff8195b0b0-ffffffff8195b2ed: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a312b0)
Location: net/core/filter.c:3573
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a312b0-ffffffff81a31468: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32e70)
Location: net/core/filter.c:3980
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a32e70-ffffffff81a32ff8: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19ed0)
Location: net/core/filter.c:3926
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a19ed0-ffffffff81a1a08a: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acca60)
Location: net/core/filter.c:3964
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81acca60-ffffffff81accc5d: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4be40)
Location: net/core/filter.c:4268
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81c4be40-ffffffff81c4c270: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e00ba0)
Location: net/core/filter.c:4282
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81e00ba0-ffffffff81e00fc7: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e72670)
Location: net/core/filter.c:4336
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
**Symbols:**

```
ffffffff81e72670-ffffffff81e72a87: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f31dc0)
Location: net/core/filter.c:4415
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
**Symbols:**

```
ffffffff81f31dc0-ffffffff81f321c4: xdp_do_redirect (STB_GLOBAL)
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
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c01930)
Location: net/core/filter.c:3636
Inline: False
```
**Symbols:**

```
ffff800010c01930-ffff800010c01c00: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d15f90)
Location: net/core/filter.c:3636
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
```
**Symbols:**

```
c0d15f90-c0d16250: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce44a0)
Location: net/core/filter.c:3636
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
c000000000ce44a0-c000000000ce47d4: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077da8e)
Location: net/core/filter.c:3636
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffe00077da8e-ffffffe00077dc98: xdp_do_redirect (STB_GLOBAL)
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
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb080)
Location: net/core/filter.c:3636
Inline: False
```
**Symbols:**

```
ffffffff818fb080-ffffffff818fb2bd: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b4eb0)
Location: net/core/filter.c:3636
Inline: False
```
**Symbols:**

```
ffffffff818b4eb0-ffffffff818b50ed: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194c0b0)
Location: net/core/filter.c:3636
Inline: False
```
**Symbols:**

```
ffffffff8194c0b0-ffffffff8194c2ed: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xdp_do_redirect(struct net_device *dev, struct xdp_buff *xdp, struct bpf_prog *xdp_prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196da40)
Location: net/core/filter.c:3636
Inline: False
```
**Symbols:**

```
ffffffff8196da40-ffffffff8196dca5: xdp_do_redirect (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
