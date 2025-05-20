# Function: <code>__dst_negative_advice</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e8bd9)
Location: include/net/sock.h:1953
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace137)
Location: include/net/sock.h:1953
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff819ced0f)
Location: include/net/sock.h:1970
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab92cf)
Location: include/net/sock.h:1970
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81a7e42c)
Location: include/net/sock.h:2010
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76693)
Location: include/net/sock.h:2010
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81bf1f3e)
Location: include/net/sock.h:2131
Inline: True
Inline callers:
  - net/core/sock.c:sock_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81d05ea8)
Location: include/net/sock.h:2131
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81d9f6ea)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81ecb230)
Location: include/net/sock.h:2168
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81e0d662)
Location: include/net/sock.h:2156
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81f29e12)
Location: include/net/sock.h:2156
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
In net/core/sock.c (ffffffff81eca7f2)
Location: include/net/sock.h:2146
Inline: True
Inline callers:
  - net/core/sock.c:sk_setsockopt
```
```
In net/ipv4/tcp_timer.c (ffffffff81fee988)
Location: include/net/sock.h:2146
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_write_timeout
  - net/ipv4/tcp_timer.c:tcp_write_timeout
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
