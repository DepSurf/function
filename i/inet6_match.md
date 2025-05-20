# Function: <code>inet6_match</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81ce2958)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv6/udp.c (ffffffff81dbbc35)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81def72f)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81ea3dd2)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv6/udp.c (ffffffff81f8bd5d)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc37ff)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81f02651)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv6/udp.c (ffffffff81fec4fd)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff8202464a)
Location: include/net/inet6_hashtables.h:107
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
In net/ipv4/inet_hashtables.c (ffffffff81fc6a11)
Location: include/net/inet6_hashtables.h:178
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv6/udp.c (ffffffff820ba10d)
Location: include/net/inet6_hashtables.h:178
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_early_demux
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f395a)
Location: include/net/inet6_hashtables.h:178
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
  - net/ipv6/inet6_hashtables.c:__inet6_lookup_established
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
