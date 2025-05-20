# Function: <code>inet_match</code>

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
In net/ipv4/inet_hashtables.c (ffffffff81ce290d)
Location: include/net/inet_hashtables.h:259
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/udp.c (ffffffff81d1f01c)
Location: include/net/inet_hashtables.h:259
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/inet_hashtables.c (ffffffff81ea3d9f)
Location: include/net/inet_hashtables.h:359
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/udp.c (ffffffff81ee6134)
Location: include/net/inet_hashtables.h:359
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/inet_hashtables.c (ffffffff81f025ea)
Location: include/net/inet_hashtables.h:359
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/udp.c (ffffffff81f45934)
Location: include/net/inet_hashtables.h:359
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
In net/ipv4/inet_hashtables.c (ffffffff81fc69aa)
Location: include/net/inet_hashtables.h:354
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_check_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
  - net/ipv4/inet_hashtables.c:__inet_lookup_established
```
```
In net/ipv4/udp.c (ffffffff8200ba84)
Location: include/net/inet_hashtables.h:354
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_v4_early_demux
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
