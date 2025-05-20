# Function: <code>tcp_skb_sent_after</code>

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
In net/ipv4/tcp_rate.c (ffffffff81d13b93)
Location: include/net/tcp.h:1164
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81d140f4)
Location: include/net/tcp.h:1164
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_rate.c (ffffffff81ed9b93)
Location: include/net/tcp.h:1177
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81eda144)
Location: include/net/tcp.h:1177
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_rate.c (ffffffff81f38c73)
Location: include/net/tcp.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81f39224)
Location: include/net/tcp.h:1175
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
In net/ipv4/tcp_rate.c (ffffffff81ffed53)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_rate.c:tcp_rate_skb_delivered
```
```
In net/ipv4/tcp_recovery.c (ffffffff81fff314)
Location: include/net/tcp.h:1212
Inline: True
Inline callers:
  - net/ipv4/tcp_recovery.c:tcp_rack_advance
  - net/ipv4/tcp_recovery.c:tcp_rack_detect_loss
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
