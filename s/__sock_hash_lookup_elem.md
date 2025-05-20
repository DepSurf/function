# Function: <code>__sock_hash_lookup_elem</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811d06e0)
Location: kernel/bpf/sockmap.c:2500
Inline: False
Direct callers:
  - net/core/filter.c:bpf_msg_redirect_hash
  - net/core/filter.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff811d06e0-ffffffff811d08a4: __sock_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f2b00)
Location: net/core/sock_map.c:554
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff818f2b00-ffffffff818f2d1a: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944fe0)
Location: net/core/sock_map.c:558
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff81944fe0-ffffffff819451d7: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8197a000)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff8197a000-ffffffff8197a1f7: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4de70)
Location: net/core/sock_map.c:744
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81a4de70-ffffffff81a4dec9: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53e60)
Location: net/core/sock_map.c:884
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81a53e60-ffffffff81a53eb9: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f970)
Location: net/core/sock_map.c:876
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81a4f970-ffffffff81a4f9c9: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08640)
Location: net/core/sock_map.c:867
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81b08640-ffffffff81b08696: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8e5a0)
Location: net/core/sock_map.c:869
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81c8e5a0-ffffffff81c8e602: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e49960)
Location: net/core/sock_map.c:871
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81e49960-ffffffff81e499c2: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea5020)
Location: net/core/sock_map.c:876
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81ea5020-ffffffff81ea5082: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67a80)
Location: net/core/sock_map.c:880
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
  - net/core/sock_map.c:sock_hash_lookup
```
**Symbols:**

```
ffffffff81f67a80-ffffffff81f67ae2: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c21208)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffff800010c21208-ffff800010c21414: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d38a28)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
c0d38a28-c0d38bd0: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d135c0)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
c000000000d135c0-c000000000d13840: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe00079a00c)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffe00079a00c-ffffffe00079a272: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81919e70)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff81919e70-ffffffff8191a067: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d3c20)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff818d3c20-ffffffff818d3e17: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196b000)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff8196b000-ffffffff8196b1f7: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__sock_hash_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198d470)
Location: net/core/sock_map.c:566
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_msg_redirect_hash
  - net/core/sock_map.c:bpf_sk_redirect_hash
```
**Symbols:**

```
ffffffff8198d470-ffffffff8198d667: __sock_hash_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
