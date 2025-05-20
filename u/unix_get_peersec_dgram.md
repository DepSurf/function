# Function: <code>unix_get_peersec_dgram</code>

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
In net/netlink/af_netlink.c (ffffffff8174e70c)
Location: include/net/scm.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff817bf0e9)
Location: include/net/scm.h:44
Inline: True
Inline callers:
  - net/unix/af_unix.c:maybe_init_creds
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/netlink/af_netlink.c (ffffffff817ba922)
Location: include/net/scm.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8182db46)
Location: include/net/scm.h:44
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff817ea2c2)
Location: include/net/scm.h:44
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8185f616)
Location: include/net/scm.h:44
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81809f86)
Location: include/net/scm.h:45
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81883cf0)
Location: include/net/scm.h:45
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81888f06)
Location: include/net/scm.h:46
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819043ff)
Location: include/net/scm.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff818dc98b)
Location: include/net/scm.h:46
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8195a9b8)
Location: include/net/scm.h:46
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff8190936e)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198f6a8)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff8196a682)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819fae01)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff819a10f2)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a31a91)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81a7aa31)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b2664c)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81a83887)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b351d6)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81a6c95a)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81b22dd6)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81b25faf)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81be8bc6)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81caebd5)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81d81287)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81e6c225)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81f4dc1a)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81ec8285)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81fada75)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/netlink/af_netlink.c (ffffffff81f8b694)
Location: include/net/scm.h:49
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8207a345)
Location: include/net/scm.h:49
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/netlink/af_netlink.c (ffff800010c4f7c8)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffff800010cf049c)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (c0d5f950)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c0df8d64)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendpage
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
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
In net/netlink/af_netlink.c (c000000000d4e118)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (c000000000e17438)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffe0007bb3d6)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffe00083e78e)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff81940f62)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff819d1121)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff818faa52)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff8198dee1)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff819920f2)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a3bba1)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
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
In net/netlink/af_netlink.c (ffffffff819b4be2)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_sendmsg
```
```
In net/unix/af_unix.c (ffffffff81a47541)
Location: include/net/scm.h:47
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_sendmsg
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:maybe_init_creds
```
</details>
</li>
</ul>

## Differences
