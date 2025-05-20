# Function: <code>lookup_reuseport</code>

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
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aadbdf)
Location: net/ipv4/inet_hashtables.c:253
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81adfad8)
Location: net/ipv4/udp.c:412
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv6/udp.c (ffffffff81b688d8)
Location: net/ipv6/udp.c:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93f88)
Location: net/ipv6/inet6_hashtables.c:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a98c9e)
Location: net/ipv4/inet_hashtables.c:253
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv4/udp.c (ffffffff81aca9e1)
Location: net/ipv4/udp.c:412
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
```
```
In net/ipv6/udp.c (ffffffff81b56bc6)
Location: net/ipv6/udp.c:144
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b83095)
Location: net/ipv6/inet6_hashtables.c:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b5417c)
Location: net/ipv4/inet_hashtables.c:255
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81b8969d)
Location: net/ipv4/udp.c:413
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81c1c322)
Location: net/ipv6/udp.c:146
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f163)
Location: net/ipv6/inet6_hashtables.c:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce20a5)
Location: net/ipv4/inet_hashtables.c:219
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81d1c3c0)
Location: net/ipv4/udp.c:413
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81db8b44)
Location: net/ipv6/udp.c:148
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81defb6a)
Location: net/ipv6/inet6_hashtables.c:116
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea3295)
Location: net/ipv4/inet_hashtables.c:335
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81ee32b0)
Location: net/ipv4/udp.c:420
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81f88b94)
Location: net/ipv6/udp.c:162
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3c59)
Location: net/ipv6/inet6_hashtables.c:114
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81f01acd)
Location: net/ipv4/inet_hashtables.c:335
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
  - net/ipv4/inet_hashtables.c:inet_lhash2_lookup
```
```
In net/ipv4/udp.c (ffffffff81f42b32)
Location: net/ipv4/udp.c:422
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:__udp4_lib_lookup
  - net/ipv4/udp.c:udp4_lib_lookup2
  - net/ipv4/udp.c:udp4_lib_lookup2
```
```
In net/ipv6/udp.c (ffffffff81feaddd)
Location: net/ipv6/udp.c:164
Inline: True
Inline callers:
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:__udp6_lib_lookup
  - net/ipv6/udp.c:udp6_lib_lookup2
  - net/ipv6/udp.c:udp6_lib_lookup2
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024b24)
Location: net/ipv6/inet6_hashtables.c:114
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
  - net/ipv6/inet6_hashtables.c:inet6_lhash2_lookup
```
</details>
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
