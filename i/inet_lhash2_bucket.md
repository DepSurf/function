# Function: <code>inet_lhash2_bucket</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff818f2094)
Location: include/net/inet_hashtables.h:164
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819ac880)
Location: include/net/inet_hashtables.h:164
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff8191fa39)
Location: include/net/inet_hashtables.h:165
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e33cf)
Location: include/net/inet_hashtables.h:165
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81982347)
Location: include/net/inet_hashtables.h:161
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a52180)
Location: include/net/inet_hashtables.h:161
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b8baa)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a88d83)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa35ca)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b84643)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81aadb0f)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b93ec0)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81a98bcb)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81b82fd0)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81b540b0)
Location: include/net/inet_hashtables.h:173
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81c4f0a0)
Location: include/net/inet_hashtables.h:173
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81ce1fb9)
Location: include/net/inet_hashtables.h:145
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81defa8f)
Location: include/net/inet_hashtables.h:145
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81ea31a9)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81fc3b7f)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81f019e9)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff82024a42)
Location: include/net/inet_hashtables.h:193
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
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
In net/ipv4/inet_hashtables.c (ffffffff81fc66c8)
Location: include/net/inet_hashtables.h:188
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff820f3d29)
Location: include/net/inet_hashtables.h:188
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c69fec)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffff800010d55a3c)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d79538)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (c0e56010)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d6f4f0)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (c000000000e8eaa4)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007cfe52)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffe00088d20e)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81958a1a)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a28413)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff8191250a)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff819e51d3)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c31ea)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81a93fc3)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cceba)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:__inet_lookup_listener
  - net/ipv4/inet_hashtables.c:inet_lhash2_bucket_sk
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81aa0113)
Location: include/net/inet_hashtables.h:167
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
  - net/ipv6/inet6_hashtables.c:inet6_lookup_listener
```
</details>
</li>
</ul>

## Differences
