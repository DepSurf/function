# Function: <code>sk_is_readable</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5a766)
Location: include/net/sock.h:2831
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81b8bc79)
Location: include/net/sock.h:2831
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/unix/af_unix.c (ffffffff81be6bc7)
Location: include/net/sock.h:2831
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/ipv4/tcp.c (ffffffff81ce8b9f)
Location: include/net/sock.h:2946
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81d1a797)
Location: include/net/sock.h:2946
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/unix/af_unix.c (ffffffff81d7d5a7)
Location: include/net/sock.h:2946
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/ipv4/tcp.c (ffffffff81ead22f)
Location: include/net/sock.h:2992
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81ee14b7)
Location: include/net/sock.h:2992
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/unix/af_unix.c (ffffffff81f4adb7)
Location: include/net/sock.h:2992
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/ipv4/tcp.c (ffffffff81f0b94f)
Location: include/net/sock.h:2983
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff81f40ef7)
Location: include/net/sock.h:2983
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/unix/af_unix.c (ffffffff81faaa68)
Location: include/net/sock.h:2983
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
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
In net/ipv4/tcp.c (ffffffff81fcf9ff)
Location: include/net/sock.h:2997
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/udp.c (ffffffff82006b47)
Location: include/net/sock.h:2997
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_poll
```
```
In net/unix/af_unix.c (ffffffff82077e58)
Location: include/net/sock.h:2997
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_dgram_poll
  - net/unix/af_unix.c:unix_poll
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
