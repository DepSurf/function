# Function: <code>inet_addr_valid_or_nonlocal</code>

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
In net/ipv4/raw.c (ffffffff81d15d54)
Location: include/net/inet_sock.h:393
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff81d2de23)
Location: include/net/inet_sock.h:393
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81d8598b)
Location: include/net/inet_sock.h:393
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff81edc194)
Location: include/net/inet_sock.h:393
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff81ef5d53)
Location: include/net/inet_sock.h:393
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81f5346c)
Location: include/net/inet_sock.h:393
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff81f3b224)
Location: include/net/inet_sock.h:395
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff81f555b3)
Location: include/net/inet_sock.h:395
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2e90)
Location: include/net/inet_sock.h:395
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/raw.c (ffffffff82001334)
Location: include/net/inet_sock.h:428
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_bind
```
```
In net/ipv4/af_inet.c (ffffffff8201ba0c)
Location: include/net/inet_sock.h:428
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff82080676)
Location: include/net/inet_sock.h:428
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
