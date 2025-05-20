# Function: <code>next_pseudo_random32</code>

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
In net/ipv4/inet_hashtables.c (ffffffff817626fe)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81788fa6)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv6/udp.c (ffffffff817e37de)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81802253)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff817ce46f)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff817f6975)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81851e08)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873499)
Location: include/linux/random.h:125
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff817fe26c)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff818278d5)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81883bc8)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7af8)
Location: include/linux/random.h:136
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff8181e5f9)
Location: include/linux/random.h:195
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81849185)
Location: include/linux/random.h:195
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff818a9fa0)
Location: include/linux/random.h:195
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce350)
Location: include/linux/random.h:195
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff8189d517)
Location: include/linux/random.h:196
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff818c8bf3)
Location: include/linux/random.h:196
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff8192c9aa)
Location: include/linux/random.h:196
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819531c3)
Location: include/linux/random.h:196
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
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
