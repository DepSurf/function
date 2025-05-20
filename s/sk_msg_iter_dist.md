# Function: <code>sk_msg_iter_dist</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195d6d2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81969012)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a18638)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81a2c860)
Location: include/linux/skmsg.h:146
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3c371)
Location: include/linux/skmsg.h:146
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b09369)
Location: include/linux/skmsg.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81a2de10)
Location: include/linux/skmsg.h:146
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a3ea31)
Location: include/linux/skmsg.h:146
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b17b84)
Location: include/linux/skmsg.h:146
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81a14ae0)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81a4ce91)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81b05753)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81ac8374)
Location: include/linux/skmsg.h:148
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81b04cc6)
Location: include/linux/skmsg.h:148
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81bc82a3)
Location: include/linux/skmsg.h:148
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81c4489f)
Location: include/linux/skmsg.h:147
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81c8a520)
Location: include/linux/skmsg.h:147
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81d5db37)
Location: include/linux/skmsg.h:147
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81dfee50)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81e45150)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f277e7)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81e70920)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81ea0740)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81f86e88)
Location: include/linux/skmsg.h:149
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff81f2ffb0)
Location: include/linux/skmsg.h:155
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81f62ee0)
Location: include/linux/skmsg.h:155
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204e4c8)
Location: include/linux/skmsg.h:155
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffff800010bfd838)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffff800010c0e46c)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffff800010cd3e24)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (c0d19c3c)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c0d26fac)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (c0dddd10)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (c000000000ce932c)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (c000000000cfabac)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (c000000000df31b0)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffe00077cfd8)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffe00078b6c4)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffe000824c62)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff818fd6a2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff81908fe2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff819b7cc8)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff818b74d2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff818c2df2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81974ab8)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff8194e6d2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8195a012)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a22748)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
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
In net/core/filter.c (ffffffff819700a2)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/filter.c:bpf_msg_pop_data
  - net/core/filter.c:bpf_msg_push_data
```
```
In net/core/skmsg.c (ffffffff8197c232)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_msg_zerocopy_from_iter
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_trim
  - net/core/skmsg.c:sk_msg_clone
  - net/core/skmsg.c:sk_msg_alloc
```
```
In net/ipv4/tcp_bpf.c (ffffffff81a2db23)
Location: include/linux/skmsg.h:145
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
</details>
</li>
</ul>

## Differences
