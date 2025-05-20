# Function: <code>__tcp_add_write_queue_tail</code>

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
In net/ipv4/tcp.c (ffffffff81765d65)
Location: include/net/tcp.h:1520
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8177445e)
Location: include/net/tcp.h:1520
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff817d21e5)
Location: include/net/tcp.h:1535
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff817e130e)
Location: include/net/tcp.h:1535
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81801fa6)
Location: include/net/tcp.h:1609
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff818117de)
Location: include/net/tcp.h:1609
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff818220db)
Location: include/net/tcp.h:1660
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81831a4e)
Location: include/net/tcp.h:1660
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect_queue_skb
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff818a114b)
Location: include/net/tcp.h:1634
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff818b6347)
Location: include/net/tcp.h:1634
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff818f5ce3)
Location: include/net/tcp.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff8190bb87)
Location: include/net/tcp.h:1650
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
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
In net/ipv4/tcp.c (ffffffff81923940)
Location: include/net/tcp.h:1722
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_entail
```
```
In net/ipv4/tcp_output.c (ffffffff81939e54)
Location: include/net/tcp.h:1722
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
```
</details>
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
