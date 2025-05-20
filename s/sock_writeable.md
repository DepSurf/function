# Function: <code>sock_writeable</code>

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
In drivers/net/tun.c (ffffffff815eda95)
Location: include/net/sock.h:2076
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817018f0)
Location: include/net/sock.h:2076
Inline: True
```
```
In net/core/datagram.c (ffffffff8170c998)
Location: include/net/sock.h:2076
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
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
In drivers/net/tun.c (ffffffff8164cbeb)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81768b75)
Location: include/net/sock.h:2049
Inline: True
```
```
In net/core/datagram.c (ffffffff817753df)
Location: include/net/sock.h:2049
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
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
In drivers/net/tun.c (ffffffff8167e955)
Location: include/net/sock.h:2115
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81795a85)
Location: include/net/sock.h:2115
Inline: True
```
```
In net/core/datagram.c (ffffffff817a26cf)
Location: include/net/sock.h:2115
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
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
In drivers/net/tun.c (ffffffff81693b4a)
Location: include/net/sock.h:2139
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff817b3ce5)
Location: include/net/sock.h:2139
Inline: True
```
```
In net/core/datagram.c (ffffffff817c01da)
Location: include/net/sock.h:2139
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
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
In kernel/bpf/sockmap.c (ffffffff811b0e36)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In drivers/net/tun.c (ffffffff816fd97d)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff8182bf18)
Location: include/net/sock.h:2153
Inline: True
```
```
In net/core/datagram.c (ffffffff81839bf0)
Location: include/net/sock.h:2153
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
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
In kernel/bpf/sockmap.c (ffffffff811cc85c)
Location: include/net/sock.h:2160
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:smap_read_sock_strparser
```
```
In drivers/net/tun.c (ffffffff8173c9f3)
Location: include/net/sock.h:2160
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81876108)
Location: include/net/sock.h:2160
Inline: True
```
```
In net/core/datagram.c (ffffffff8188433b)
Location: include/net/sock.h:2160
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
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
In drivers/net/tun.c (ffffffff81760f03)
Location: include/net/sock.h:2246
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81896988)
Location: include/net/sock.h:2246
Inline: True
```
```
In net/core/datagram.c (ffffffff818a47ad)
Location: include/net/sock.h:2246
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff818e5f88)
Location: include/net/sock.h:2246
Inline: True
Inline callers:
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
In drivers/net/tun.c (ffffffff8179eb98)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff818e0c28)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff818eff27)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81935b8b)
Location: include/net/sock.h:2252
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffff817c2628)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81912df2)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff81921f50)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff8196899b)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffff8188d103)
Location: include/net/sock.h:2323
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819e4bbd)
Location: include/net/sock.h:2323
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff819f5190)
Location: include/net/sock.h:2323
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81a3ca03)
Location: include/net/sock.h:2323
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_skb_redirect
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
In drivers/net/tun.c (ffffffff8189b384)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819e442d)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff819f4bc0)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81a3f7ac)
Location: include/net/sock.h:2344
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffffffff8187e014)
Location: include/net/sock.h:2380
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff819ca4bd)
Location: include/net/sock.h:2380
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff819dad50)
Location: include/net/sock.h:2380
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81a4e984)
Location: include/net/sock.h:2380
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffffffff8190f7f9)
Location: include/net/sock.h:2434
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81a79a5d)
Location: include/net/sock.h:2434
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff81a8b3d0)
Location: include/net/sock.h:2434
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81b074f1)
Location: include/net/sock.h:2434
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffffffff81a62dbb)
Location: include/net/sock.h:2557
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81beddb2)
Location: include/net/sock.h:2557
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_wfree
```
```
In net/core/datagram.c (ffffffff81c00681)
Location: include/net/sock.h:2557
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81c8cc61)
Location: include/net/sock.h:2557
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffffffff81bee06b)
Location: include/net/sock.h:2603
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81d9ad42)
Location: include/net/sock.h:2603
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_wfree
```
```
In net/core/datagram.c (ffffffff81dafe81)
Location: include/net/sock.h:2603
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81e47afa)
Location: include/net/sock.h:2603
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffffffff81c4659b)
Location: include/net/sock.h:2591
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81e095c2)
Location: include/net/sock.h:2591
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_wfree
```
```
In net/core/datagram.c (ffffffff81e200e7)
Location: include/net/sock.h:2591
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81ea3277)
Location: include/net/sock.h:2591
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffffffff81cfbeab)
Location: include/net/sock.h:2581
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81ec5fb2)
Location: include/net/sock.h:2581
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_wfree
```
```
In net/core/datagram.c (ffffffff81eddfc7)
Location: include/net/sock.h:2581
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff81f65590)
Location: include/net/sock.h:2581
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In drivers/net/tun.c (ffff8000109dcf48)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffff800010baa51c)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffff800010bbc614)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffff800010c0f49c)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (c0ac2548)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (c0cc9070)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (c0cd8920)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (c0d269dc)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (c000000000aa28ec)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (c000000000c80944)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (c000000000c946a8)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (c000000000cfa0cc)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffe000627c2c)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffe00073deca)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffe00074a748)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffe00078b046)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffff817870f8)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff818b2df2)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff818c1f50)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff8190896b)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffff81766a48)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff8186cd42)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff8187be90)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff818c277b)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffff817b74a8)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81903df2)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff81912f50)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff8195999b)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
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
In drivers/net/tun.c (ffffffff817cf549)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_chr_poll
  - drivers/net/tun.c:tun_chr_poll
```
```
In net/core/sock.c (ffffffff81924df7)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/sock.c:sock_def_write_space
```
```
In net/core/datagram.c (ffffffff819340d0)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/datagram.c:datagram_poll
```
```
In net/core/skmsg.c (ffffffff8197bbc4)
Location: include/net/sock.h:2271
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_strp_read
```
</details>
</li>
</ul>

## Differences
