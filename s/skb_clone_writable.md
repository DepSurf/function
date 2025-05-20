# Function: <code>skb_clone_writable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817099af)
Location: include/linux/skbuff.h:2540
Inline: True
```
```
In net/core/dev.c (ffffffff81718d6d)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff8173242a)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/netfilter/core.c (ffffffff81751019)
Location: include/linux/skbuff.h:2540
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81771d0f)
Location: include/linux/skbuff.h:2676
Inline: True
```
```
In net/core/dev.c (ffffffff8178061d)
Location: include/linux/skbuff.h:2676
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/netfilter/core.c (ffffffff817bd045)
Location: include/linux/skbuff.h:2676
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8179ee3f)
Location: include/linux/skbuff.h:2714
Inline: True
```
```
In net/core/dev.c (ffffffff817adf6d)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/netfilter/core.c (ffffffff817ec985)
Location: include/linux/skbuff.h:2714
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bc5af)
Location: include/linux/skbuff.h:2763
Inline: True
```
```
In net/core/dev.c (ffffffff817cab69)
Location: include/linux/skbuff.h:2763
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/netfilter/core.c (ffffffff8180cda3)
Location: include/linux/skbuff.h:2763
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81836c7f)
Location: include/linux/skbuff.h:2860
Inline: True
```
```
In net/core/dev.c (ffffffff818461d9)
Location: include/linux/skbuff.h:2860
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/netfilter/core.c (ffffffff8188bf83)
Location: include/linux/skbuff.h:2860
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81880d9d)
Location: include/linux/skbuff.h:2872
Inline: True
```
```
In net/core/dev.c (ffffffff8188f690)
Location: include/linux/skbuff.h:2872
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
```
```
In net/netfilter/core.c (ffffffff818dfc45)
Location: include/linux/skbuff.h:2872
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a1c44)
Location: include/linux/skbuff.h:2948
Inline: True
```
```
In net/core/dev.c (ffffffff818aee9a)
Location: include/linux/skbuff.h:2948
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/netfilter/core.c (ffffffff8190c7c8)
Location: include/linux/skbuff.h:2948
Inline: True
Inline callers:
  - net/netfilter/core.c:skb_make_writable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818ec621)
Location: include/linux/skbuff.h:3035
Inline: True
```
```
In net/core/dev.c (ffffffff818fbe81)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81924a8a)
Location: include/linux/skbuff.h:3035
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff8191e751)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffffffff8192e421)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81956eba)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff819f0fd1)
Location: include/linux/skbuff.h:3123
Inline: True
```
```
In net/core/filter.c (ffffffff81a2d410)
Location: include/linux/skbuff.h:3123
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff819f0f61)
Location: include/linux/skbuff.h:3149
Inline: True
```
```
In net/core/filter.c (ffffffff81a2ecb0)
Location: include/linux/skbuff.h:3149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff819d6221)
Location: include/linux/skbuff.h:3213
Inline: True
```
```
In net/core/filter.c (ffffffff81a1630f)
Location: include/linux/skbuff.h:3213
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff81a86861)
Location: include/linux/skbuff.h:3250
Inline: True
```
```
In net/core/filter.c (ffffffff81ac726f)
Location: include/linux/skbuff.h:3250
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3619
Inline: True
```
```
In net/core/filter.c (ffffffff81c42a73)
Location: include/linux/skbuff.h:3619
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3515
Inline: True
```
```
In net/core/filter.c (ffffffff81df7a63)
Location: include/linux/skbuff.h:3515
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3549
Inline: True
```
```
In net/core/filter.c (ffffffff81e6976d)
Location: include/linux/skbuff.h:3549
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:3574
Inline: True
```
```
In net/core/filter.c (ffffffff81f28d4d)
Location: include/linux/skbuff.h:3574
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffff800010bb8f0c)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffff800010bc9a00)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffff800010bf8680)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (c0cd59cc)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (c0ce7c24)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c0d122c8)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (c000000000c91390)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (c000000000ca772c)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (c000000000cdf5a0)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffe000748558)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffffffe00075708c)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffe00077a398)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff818be751)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffffffff818ce421)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818f6e8a)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff81878691)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffffffff81888541)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff818b0cba)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff8190f751)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffffffff8191f421)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff81947eba)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
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
In net/core/skbuff.c (ffffffff81930881)
Location: include/linux/skbuff.h:3100
Inline: True
```
```
In net/core/dev.c (ffffffff81941181)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/dev.c:skb_checksum_help
  - net/core/dev.c:skb_checksum_help
```
```
In net/core/filter.c (ffffffff819697ca)
Location: include/linux/skbuff.h:3100
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_ecn_set_ce
```
</details>
</li>
</ul>

## Differences
