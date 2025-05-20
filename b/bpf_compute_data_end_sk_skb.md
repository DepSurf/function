# Function: <code>bpf_compute_data_end_sk_skb</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cc40a)
Location: include/net/tcp.h:833
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_parse_func_strparser
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In net/core/filter.c (ffffffff818b4a31)
Location: include/net/tcp.h:833
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
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
In net/core/filter.c (ffffffff818dc321)
Location: include/net/tcp.h:856
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff818e5c7b)
Location: include/net/tcp.h:856
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
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
In net/core/filter.c (ffffffff819292b9)
Location: include/net/tcp.h:857
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff819359c7)
Location: include/net/tcp.h:857
Inline: True
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
In net/core/filter.c (ffffffff8195b999)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff819687d7)
Location: include/net/tcp.h:878
Inline: True
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
In net/core/filter.c (ffffffff81a2ecf4)
Location: include/net/tcp.h:889
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3ccc7)
Location: include/net/tcp.h:889
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
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
In net/core/filter.c (ffffffff81a3029a)
Location: include/net/tcp.h:895
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_adjust_room
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff81a3f65b)
Location: include/net/tcp.h:895
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_verdict_recv
  - net/core/skmsg.c:sk_psock_strp_parse
  - net/core/skmsg.c:sk_psock_strp_read
  - net/core/skmsg.c:sk_psock_tls_strp_read
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In net/core/filter.c (ffff800010bfccc0)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffff800010c0f2b4)
Location: include/net/tcp.h:878
Inline: True
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
In net/core/filter.c (c0d18104)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (c0d267ac)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
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
In net/core/filter.c (c000000000ce524c)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (c000000000cf9e00)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
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
In net/core/filter.c (ffffffe00077f12e)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffe00078ae72)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_bpf_run
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
In net/core/filter.c (ffffffff818fb969)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff819087a7)
Location: include/net/tcp.h:878
Inline: True
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
In net/core/filter.c (ffffffff818b5799)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff818c25b7)
Location: include/net/tcp.h:878
Inline: True
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
In net/core/filter.c (ffffffff8194c999)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff819597d7)
Location: include/net/tcp.h:878
Inline: True
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
In net/core/filter.c (ffffffff8196e359)
Location: include/net/tcp.h:878
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_change_head
  - net/core/filter.c:sk_skb_change_tail
  - net/core/filter.c:sk_skb_pull_data
```
```
In net/core/skmsg.c (ffffffff8197b9b7)
Location: include/net/tcp.h:878
Inline: True
```
</details>
</li>
</ul>

## Differences
