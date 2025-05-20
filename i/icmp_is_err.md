# Function: <code>icmp_is_err</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a92098)
Location: include/linux/icmp.h:24
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
In net/ipv4/route.c (ffffffff81a9bf38)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06d89)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81a86ed4)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af24c2)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81b41694)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb29d2)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81cce0f9)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d461a9)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81e8e0b9)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f589)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81eec7f9)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f279)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
In net/ipv4/route.c (ffffffff81fb0859)
Location: include/linux/icmp.h:25
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff820359a9)
Location: include/linux/icmp.h:25
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
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
