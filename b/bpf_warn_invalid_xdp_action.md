# Function: <code>bpf_warn_invalid_xdp_action</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d230)
Location: net/core/filter.c:2503
Inline: True
```
**Symbols:**

```
ffffffff8179d230-ffffffff8179d266: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cace0)
Location: net/core/filter.c:2969
Inline: True
```
**Symbols:**

```
ffffffff817cace0-ffffffff817cad16: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9dd0)
Location: net/core/filter.c:3303
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_skb_internal
```
**Symbols:**

```
ffffffff817e9dd0-ffffffff817e9dfd: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865440)
Location: net/core/filter.c:3816
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:do_xdp_generic
```
**Symbols:**

```
ffffffff81865440-ffffffff81865482: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2fe0)
Location: net/core/filter.c:5412
Inline: True
```
**Symbols:**

```
ffffffff818b2fe0-ffffffff818b3021: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d7e30)
Location: net/core/filter.c:6132
Inline: True
```
**Symbols:**

```
ffffffff818d7e30-ffffffff818d7e71: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81925bb0)
Location: net/core/filter.c:6814
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81925bb0-ffffffff81925bf1: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81957fe0)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81957fe0-ffffffff81958021: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b6d0)
Location: net/core/filter.c:7122
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81a2b6d0-ffffffff81a2b711: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2c520)
Location: net/core/filter.c:7928
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81a2c520-ffffffff81a2c561: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a13a30)
Location: net/core/filter.c:8050
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_run_prog
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81a13a30-ffffffff81a13a71: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81d37048)
Location: net/core/filter.c:8180
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81d37034-ffffffff81d37079: bpf_warn_invalid_xdp_action.cold (STB_LOCAL)
ffffffff81ac5350-ffffffff81ac537d: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(struct net_device *dev, struct bpf_prog *prog, u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81f039b9)
Location: net/core/filter.c:8592
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81f03978-ffffffff81f039e1: bpf_warn_invalid_xdp_action.cold (STB_LOCAL)
ffffffff81c40890-ffffffff81c408e3: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(struct net_device *dev, struct bpf_prog *prog, u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81df5f85)
Location: net/core/filter.c:8758
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff820ac05d-ffffffff820ac080: bpf_warn_invalid_xdp_action.cold (STB_LOCAL)
ffffffff81df5f10-ffffffff81df5fbd: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(struct net_device *dev, struct bpf_prog *prog, u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81e67b3b)
Location: net/core/filter.c:8905
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff8212d7ae-ffffffff8212d7d1: bpf_warn_invalid_xdp_action.cold (STB_LOCAL)
ffffffff81e67af0-ffffffff81e67b9d: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(struct net_device *dev, struct bpf_prog *prog, u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81f26cff)
Location: net/core/filter.c:8996
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:dev_map_generic_redirect
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_xdp
  - kernel/bpf/cpumap.c:cpu_map_bpf_prog_run_skb
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff8220f4fb-ffffffff8220f516: bpf_warn_invalid_xdp_action.cold (STB_LOCAL)
ffffffff81f26cb0-ffffffff81f26d6b: bpf_warn_invalid_xdp_action (STB_GLOBAL)
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
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf9648)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffff800010bf9648-ffff800010bf96b8: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d12da4)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
c0d12da4-c0d12e28: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce0b70)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
c000000000ce0b70-c000000000ce0be8: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077b660)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_xdp_act
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffe00077b660-ffffffe00077b6c8: bpf_warn_invalid_xdp_action (STB_GLOBAL)
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
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f7fb0)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff818f7fb0-ffffffff818f7ff1: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1de0)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff818b1de0-ffffffff818b1e21: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81948fe0)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff81948fe0-ffffffff81949021: bpf_warn_invalid_xdp_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bpf_warn_invalid_xdp_action(u32 act);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196a8f0)
Location: net/core/filter.c:6901
Inline: True
Direct callers:
  - net/core/dev.c:netif_receive_generic_xdp
```
**Symbols:**

```
ffffffff8196a8f0-ffffffff8196a931: bpf_warn_invalid_xdp_action (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net_device *dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_prog *prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>act</code> ➡️ <code>dev, prog, act</code>
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
