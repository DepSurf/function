# Function: <code>__bpf_try_make_writable</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb536)
Location: net/core/filter.c:1355
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/filter.c (ffffffff817ead3e)
Location: net/core/filter.c:1380
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/filter.c (ffffffff818677ee)
Location: net/core/filter.c:1401
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/filter.c (ffffffff818b2389)
Location: net/core/filter.c:1613
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/filter.c (ffffffff818d6eb0)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
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
In net/core/filter.c (ffffffff81924741)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956a51)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fe21)
Location: net/core/filter.c:1621
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a326f1)
Location: net/core/filter.c:1651
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19857)
Location: net/core/filter.c:1651
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acabd7)
Location: net/core/filter.c:1652
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c486f7)
Location: net/core/filter.c:1653
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfd5b7)
Location: net/core/filter.c:1655
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6e9c7)
Location: net/core/filter.c:1655
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2ec57)
Location: net/core/filter.c:1662
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c002ec)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d11de4)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdee00)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f70e)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6a21)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b0851)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947a51)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81969361)
Location: net/core/filter.c:1632
Inline: True
Inline callers:
  - net/core/filter.c:bpf_lwt_seg6_store_bytes
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:bpf_skb_change_tail
  - net/core/filter.c:bpf_clone_redirect
  - net/core/filter.c:bpf_l4_csum_replace
  - net/core/filter.c:bpf_l3_csum_replace
  - net/core/filter.c:sk_skb_pull_data
  - net/core/filter.c:bpf_skb_pull_data
  - net/core/filter.c:bpf_skb_store_bytes
```
</details>
</li>
</ul>

## Differences
