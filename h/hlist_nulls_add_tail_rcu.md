# Function: <code>hlist_nulls_add_tail_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff817cef88)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv6/inet6_hashtables.c (ffffffff81873822)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff817fed9c)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818a7e74)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
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
In net/ipv4/inet_hashtables.c (ffffffff8181f0b9)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
  - net/ipv4/inet_hashtables.c:__inet_check_established
```
```
In net/ipv6/inet6_hashtables.c (ffffffff818ce6f1)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv6/inet6_hashtables.c:__inet6_check_established
```
</details>
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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819b98e8)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aa438f)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81aae9d1)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81a99c25)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81b5508d)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ce2c72)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
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
In net/ipv4/inet_hashtables.c (ffffffff81ea416b)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
  - net/ipv4/inet_hashtables.c:inet_ehash_insert
```
```
In net/ipv4/inet_timewait_sock.c (ffffffff81ea5caa)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_timewait_sock.c:inet_twsk_hashdance
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
In mm/vmscan.c (ffffffff813b7b70)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In net/ipv4/inet_hashtables.c (ffffffff81f029ca)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
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
In mm/vmscan.c (ffffffff813e0a51)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - mm/vmscan.c:lru_gen_online_memcg
  - mm/vmscan.c:lru_gen_rotate_memcg
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc6d82)
Location: include/linux/rculist_nulls.h:130
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffff800010c6b0b0)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c0d7a144)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (c000000000d70490)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffe0007d0d56)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81959758)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81913248)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819c3f28)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff819cd990)
Location: include/linux/rculist_nulls.h:122
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_hash
```
</details>
</li>
</ul>

## Differences
