# Function: <code>skb_zcopy_set</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81837d8c)
Location: include/linux/skbuff.h:1285
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_iter_stream
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
In net/core/skbuff.c (ffffffff8187eecc)
Location: include/linux/skbuff.h:1296
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
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
In net/core/skbuff.c (ffffffff8189fcbc)
Location: include/linux/skbuff.h:1334
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff8191a894)
Location: include/linux/skbuff.h:1334
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819964ec)
Location: include/linux/skbuff.h:1334
Inline: True
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
In net/core/skbuff.c (ffffffff818ea6e7)
Location: include/linux/skbuff.h:1422
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff8197ca3f)
Location: include/linux/skbuff.h:1422
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8199b2e5)
Location: include/linux/skbuff.h:1422
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a0297a)
Location: include/linux/skbuff.h:1422
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
In net/core/skbuff.c (ffffffff8191c857)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff819b33df)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819d1d25)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a39555)
Location: include/linux/skbuff.h:1419
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
In net/core/skbuff.c (ffffffff819eeb4e)
Location: include/linux/skbuff.h:1425
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81a9d7aa)
Location: include/linux/skbuff.h:1425
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81abec0d)
Location: include/linux/skbuff.h:1425
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b2ecc2)
Location: include/linux/skbuff.h:1425
Inline: True
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
In net/core/skbuff.c (ffffffff819ee7ee)
Location: include/linux/skbuff.h:1446
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81aa7666)
Location: include/linux/skbuff.h:1446
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81aca56d)
Location: include/linux/skbuff.h:1446
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b3d712)
Location: include/linux/skbuff.h:1446
Inline: True
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
In net/core/skbuff.c (ffffffff819d41eb)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81a9284b)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ab53ed)
Location: include/linux/skbuff.h:1464
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81b2aba8)
Location: include/linux/skbuff.h:1464
Inline: True
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
In net/core/skbuff.c (ffffffff81a83f0b)
Location: include/linux/skbuff.h:1477
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81b4dc4f)
Location: include/linux/skbuff.h:1477
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81b723e5)
Location: include/linux/skbuff.h:1477
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81bf0c92)
Location: include/linux/skbuff.h:1477
Inline: True
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
In net/core/skbuff.c (ffffffff81bf9809)
Location: include/linux/skbuff.h:1826
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81cdb4d8)
Location: include/linux/skbuff.h:1826
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81d01b0c)
Location: include/linux/skbuff.h:1826
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81d899f8)
Location: include/linux/skbuff.h:1826
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
In net/core/skbuff.c (ffffffff81da8659)
Location: include/linux/skbuff.h:1676
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81e9be83)
Location: include/linux/skbuff.h:1676
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81ec6c7c)
Location: include/linux/skbuff.h:1676
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81f5767f)
Location: include/linux/skbuff.h:1676
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
In net/core/skbuff.c (ffffffff81e172f9)
Location: include/linux/skbuff.h:1705
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81efaa1d)
Location: include/linux/skbuff.h:1705
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81f254c8)
Location: include/linux/skbuff.h:1705
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7178)
Location: include/linux/skbuff.h:1705
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
In net/core/skbuff.c (ffffffff81ed46f9)
Location: include/linux/skbuff.h:1712
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff81fbe96a)
Location: include/linux/skbuff.h:1712
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (ffffffff81fe9d8a)
Location: include/linux/skbuff.h:1712
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff82083f44)
Location: include/linux/skbuff.h:1712
Inline: True
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
In net/core/skbuff.c (ffff800010bb6e34)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffff800010c62dd8)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffff800010c848dc)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffff800010cf94b4)
Location: include/linux/skbuff.h:1419
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
In net/core/skbuff.c (c0cd3c74)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (c0d73af4)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
  - net/ipv4/ip_output.c:__ip_append_data
```
```
In net/ipv4/tcp_output.c (c0d93bd0)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (c0e010a4)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:__ip6_append_data
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
In net/core/skbuff.c (c000000000c8e838)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (c000000000d67e00)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (c000000000d906c4)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (c000000000e21194)
Location: include/linux/skbuff.h:1419
Inline: True
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
In net/core/skbuff.c (ffffffe000746a66)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffe0007cb710)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffe0007e6316)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffe000844e3e)
Location: include/linux/skbuff.h:1419
Inline: True
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
In net/core/skbuff.c (ffffffff818bc857)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff8195324f)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81971b95)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff819d8be5)
Location: include/linux/skbuff.h:1419
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
In net/core/skbuff.c (ffffffff81876797)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff8190cd3f)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff8192b665)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff819959a5)
Location: include/linux/skbuff.h:1419
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
In net/core/skbuff.c (ffffffff8190d857)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff819bda1f)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819dc365)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a43665)
Location: include/linux/skbuff.h:1419
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
In net/core/skbuff.c (ffffffff8192e987)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_clone
  - net/core/skbuff.c:skb_zerocopy_iter_stream
  - net/core/skbuff.c:skb_zerocopy_iter_stream
```
```
In net/ipv4/ip_output.c (ffffffff819c732f)
Location: include/linux/skbuff.h:1419
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff819e5fe5)
Location: include/linux/skbuff.h:1419
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
```
```
In net/ipv6/ip6_output.c (ffffffff81a4f305)
Location: include/linux/skbuff.h:1419
Inline: True
```
</details>
</li>
</ul>

## Differences
