# Function: <code>scm_recv</code>

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
In net/netlink/af_netlink.c (ffffffff8174c612)
Location: include/net/scm.h:110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff817bede3)
Location: include/net/scm.h:110
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_stream_read_generic
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
In net/netlink/af_netlink.c (ffffffff817b832e)
Location: include/net/scm.h:110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8182c518)
Location: include/net/scm.h:110
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff817e7e0e)
Location: include/net/scm.h:110
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8185dfcf)
Location: include/net/scm.h:110
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81807b2e)
Location: include/net/scm.h:111
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff818834d5)
Location: include/net/scm.h:111
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8188669e)
Location: include/net/scm.h:112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81903bc7)
Location: include/net/scm.h:112
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff818d9f86)
Location: include/net/scm.h:112
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8195bce5)
Location: include/net/scm.h:112
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81906a80)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81990502)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81967d20)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819fbbe5)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8199e7c0)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a32875)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81a783e0)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b27534)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81a811d5)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b35e0e)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81a6994e)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81b23a02)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81b22f0b)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81be7eff)
Location: include/net/scm.h:114
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81caa9a0)
Location: include/net/scm.h:118
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81d7d8e0)
Location: include/net/scm.h:118
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81caa9a0-ffffffff81caab4c: scm_recv.constprop.0 (STB_LOCAL)
ffffffff81d7d8e0-ffffffff81d7da8c: scm_recv.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e67a90)
Location: include/net/scm.h:118
Inline: True
Direct callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81f4aa20)
Location: include/net/scm.h:118
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:__unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff81e67a90-ffffffff81e67c3c: scm_recv.constprop.0 (STB_LOCAL)
ffffffff81f4aa20-ffffffff81f4abcc: scm_recv.constprop.0 (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffff81ec47d0)
Location: include/net/scm.h:191
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffffffff81f87b98)
Location: include/net/scm.h:191
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
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
In net/netlink/af_netlink.c (ffff800010c4d4c0)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffff800010cf2008)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (c0d5c640)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (c0df9f3c)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (c000000000d4a078)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (c000000000e1839c)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffe0007b925c)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffe00083f174)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8193e630)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff819d1f05)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff818f8130)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff8198ecc5)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff8198f7c0)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a3c985)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
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
In net/netlink/af_netlink.c (ffffffff819b20a0)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_recvmsg
```
```
In net/unix/af_unix.c (ffffffff81a47f3d)
Location: include/net/scm.h:113
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_stream_read_generic
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
</details>
</li>
</ul>

## Differences
