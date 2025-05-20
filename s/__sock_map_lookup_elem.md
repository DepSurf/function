# Function: <code>__sock_map_lookup_elem</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__sock_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b1b00)
Location: kernel/bpf/sockmap.c:633
Inline: False
Direct callers:
  - net/core/filter.c:do_sk_redirect_map
```
**Symbols:**

```
ffffffff811b1b00-ffffffff811b1b24: __sock_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__sock_map_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811d05c0)
Location: kernel/bpf/sockmap.c:1776
Inline: False
Direct callers:
  - net/core/filter.c:bpf_msg_redirect_map
  - net/core/filter.c:bpf_sk_redirect_map
```
**Symbols:**

```
ffffffff811d05c0-ffffffff811d05e4: __sock_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f1ae8)
Location: net/core/sock_map.c:264
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81943f88)
Location: net/core/sock_map.c:261
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81978f78)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (ffffffff81a4e302)
Location: net/core/sock_map.c:371
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
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
In net/core/sock_map.c (ffffffff81a536d4)
Location: net/core/sock_map.c:372
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
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
In net/core/sock_map.c (ffffffff81a4f2f4)
Location: net/core/sock_map.c:372
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
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
In net/core/sock_map.c (ffffffff81b07ed4)
Location: net/core/sock_map.c:372
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
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
In net/core/sock_map.c (ffffffff81c8dd75)
Location: net/core/sock_map.c:372
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e48c95)
Location: net/core/sock_map.c:374
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea43b5)
Location: net/core/sock_map.c:370
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f66d15)
Location: net/core/sock_map.c:370
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_seq_next
  - net/core/sock_map.c:sock_map_seq_start
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
  - net/core/sock_map.c:sock_map_lookup
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
In net/core/sock_map.c (ffff800010c1f7a4)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (c0d37790)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (c000000000d1198c)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (ffffffe000799eee)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (ffffffff81918de8)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (ffffffff818d2b98)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (ffffffff81969f78)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
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
In net/core/sock_map.c (ffffffff8198c398)
Location: net/core/sock_map.c:267
Inline: True
Inline callers:
  - net/core/sock_map.c:bpf_msg_redirect_map
  - net/core/sock_map.c:bpf_sk_redirect_map
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
