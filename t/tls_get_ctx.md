# Function: <code>tls_get_ctx</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81976921)
Location: include/net/tls.h:440
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffff819e0496)
Location: include/net/tls.h:466
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffff81a174c6)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/skmsg.c (ffffffff81a3bbcc)
Location: include/net/tls.h:474
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b0849a)
Location: include/net/tls.h:474
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81a2d454)
Location: include/net/tls.h:494
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81a3e55c)
Location: include/net/tls.h:494
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b169fa)
Location: include/net/tls.h:494
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81a15466)
Location: include/net/tls.h:502
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81a4c75c)
Location: include/net/tls.h:502
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b04718)
Location: include/net/tls.h:502
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81ac6486)
Location: include/net/tls.h:495
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81b0507c)
Location: include/net/tls.h:495
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc6a7d)
Location: include/net/tls.h:495
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81c423f5)
Location: include/net/tls.h:494
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81c8a92c)
Location: include/net/tls.h:494
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5c215)
Location: include/net/tls.h:494
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81df8585)
Location: include/net/tls.h:381
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81e4554c)
Location: include/net/tls.h:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f26396)
Location: include/net/tls.h:381
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81e6a4f5)
Location: include/net/tls.h:386
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81ea1a72)
Location: include/net/tls.h:386
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f85f9c)
Location: include/net/tls.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/core/filter.c (ffffffff81f29485)
Location: include/net/tls.h:362
Inline: True
Inline callers:
  - net/core/filter.c:sk_skb_adjust_room
```
```
In net/core/skmsg.c (ffffffff81f64282)
Location: include/net/tls.h:362
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_data_ready
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204d57c)
Location: include/net/tls.h:362
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffff800010cd3508)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (c0ddd294)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (c000000000df1aa8)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffe0008243be)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffff819b6b56)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffff81973946)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffff81a215d6)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
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
In net/ipv4/tcp_bpf.c (ffffffff81a2c926)
Location: include/net/tls.h:477
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_push
```
</details>
</li>
</ul>

## Differences
