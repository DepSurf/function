# Function: <code>sk_mem_reclaim_final</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/stream.c (ffffffff81c016fe)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/af_inet.c (ffffffff81d2d4d8)
Location: include/net/sock.h:1629
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/stream.c (ffffffff81db0a9a)
Location: include/net/sock.h:1675
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/af_inet.c (ffffffff81ef5348)
Location: include/net/sock.h:1675
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/stream.c (ffffffff81e20f5a)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/af_inet.c (ffffffff81f54c28)
Location: include/net/sock.h:1666
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
In net/core/stream.c (ffffffff81edee2f)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/core/stream.c:sk_stream_kill_queues
```
```
In net/ipv4/af_inet.c (ffffffff8201ae98)
Location: include/net/sock.h:1641
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:inet_sock_destruct
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
