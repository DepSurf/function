# Function: <code>sock_hash_update_common</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f2550)
Location: net/core/sock_map.c:651
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff818f2550-ffffffff818f29d5: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944680)
Location: net/core/sock_map.c:655
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff81944680-ffffffff81944b32: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979680)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff81979680-ffffffff81979b32: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f690)
Location: net/core/sock_map.c:841
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff81a4f690-ffffffff81a4f9ba: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a55530)
Location: net/core/sock_map.c:982
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81a55530-ffffffff81a55828: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a50ca0)
Location: net/core/sock_map.c:974
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81a50ca0-ffffffff81a50fd4: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b09d50)
Location: net/core/sock_map.c:965
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81b09d50-ffffffff81b0a081: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8ffb0)
Location: net/core/sock_map.c:967
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81c8ffb0-ffffffff81c902e9: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e4b430)
Location: net/core/sock_map.c:969
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81e4b430-ffffffff81e4b6f8: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea6b50)
Location: net/core/sock_map.c:974
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81ea6b50-ffffffff81ea6e1c: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f69640)
Location: net/core/sock_map.c:978
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81f69640-ffffffff81f6993b: sock_hash_update_common (STB_LOCAL)
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
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c20ab0)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffff800010c20ab0-ffff800010c21078: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d3840c)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
c0d3840c-c0d388ac: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d12c60)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
c000000000d12c60-c000000000d13260: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe000799914)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffe000799914-ffffffe000799d78: sock_hash_update_common (STB_LOCAL)
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
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff819194f0)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff819194f0-ffffffff819199a2: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d32a0)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff818d32a0-ffffffff818d3752: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196a680)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff8196a680-ffffffff8196ab32: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_hash_update_common(struct bpf_map *map, void *key, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198caf0)
Location: net/core/sock_map.c:663
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_hash_update
  - net/core/sock_map.c:sock_hash_update_elem
```
**Symbols:**

```
ffffffff8198caf0-ffffffff8198cfa2: sock_hash_update_common (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
