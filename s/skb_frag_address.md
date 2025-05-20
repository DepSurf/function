# Function: <code>skb_frag_address</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (0)
Location: include/linux/skbuff.h:2449
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177b4c8)
Location: include/linux/skbuff.h:2585
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a8b2e)
Location: include/linux/skbuff.h:2623
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c71d9)
Location: include/linux/skbuff.h:2672
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81840db9)
Location: include/linux/skbuff.h:2769
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b429)
Location: include/linux/skbuff.h:2781
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac5a9)
Location: include/linux/skbuff.h:2857
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f7e34)
Location: include/linux/skbuff.h:2944
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81929be4)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff8196122b)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fdc1b)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff81a3475e)
Location: include/linux/skbuff.h:3021
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fd76b)
Location: include/linux/skbuff.h:3047
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff81a36ab6)
Location: include/linux/skbuff.h:3047
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f2623)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
```
In net/core/tso.c (ffffffff81a1dc31)
Location: include/linux/skbuff.h:3111
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa44f3)
Location: include/linux/skbuff.h:3148
Inline: True
Inline callers:
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:napi_gro_receive
```
```
In net/core/tso.c (ffffffff81ad16d1)
Location: include/linux/skbuff.h:3148
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3f642)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81c4f047)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81c51cd7)
Location: include/linux/skbuff.h:3517
Inline: True
```
```
In net/core/gro.c (ffffffff81c544c3)
Location: include/linux/skbuff.h:3517
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81cb35a7)
Location: include/linux/skbuff.h:3517
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df3b52)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81e040f7)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e07084)
Location: include/linux/skbuff.h:3413
Inline: True
```
```
In net/core/gro.c (ffffffff81e09c13)
Location: include/linux/skbuff.h:3413
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81e7172b)
Location: include/linux/skbuff.h:3413
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e63544)
Location: include/linux/skbuff.h:3473
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81e767f4)
Location: include/linux/skbuff.h:3473
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81e79374)
Location: include/linux/skbuff.h:3473
Inline: True
```
```
In net/core/gro.c (ffffffff81e7c3d9)
Location: include/linux/skbuff.h:3473
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81ecd9eb)
Location: include/linux/skbuff.h:3473
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f27c74)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/filter.c:bpf_xdp_adjust_tail
  - net/core/filter.c:bpf_xdp_pointer
  - net/core/filter.c:bpf_xdp_copy_buf
```
```
In net/core/tso.c (ffffffff81f367b7)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
```
In net/core/xdp.c (ffffffff81f39404)
Location: include/linux/skbuff.h:3498
Inline: True
```
```
In net/core/gro.c (ffffffff81f3c729)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/core/gro.c:napi_gro_frags
  - net/core/gro.c:napi_gro_receive
```
```
In net/bpf/test_run.c (ffffffff81f9121b)
Location: include/linux/skbuff.h:3498
Inline: True
```
```
In net/xdp/xsk.c (ffffffff8213c763)
Location: include/linux/skbuff.h:3498
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_copy_xdp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7f50)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In net/core/dev.c (ffff800010bc62a8)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffff800010c04b08)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/freescale/fec_main.c (c0acd3c4)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In net/core/dev.c (c0ce49d4)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (c0d1df54)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca0e94)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (c000000000ceeabc)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000752a92)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffe0007836e6)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818c9be4)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff819011fb)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81883b24)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff818bb02b)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191abe4)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff8195222b)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193bd74)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/dev.c:skb_gro_reset_offset
```
```
In net/core/tso.c (ffffffff81973c6b)
Location: include/linux/skbuff.h:2998
Inline: True
Inline callers:
  - net/core/tso.c:tso_start
```
</details>
</li>
</ul>

## Differences
