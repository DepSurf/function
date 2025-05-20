# Function: <code>sk_storage_update</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81953090)
Location: net/core/bpf_sk_storage.c:385
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81953090-ffffffff819533f0: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff819894e0)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff819894e0-ffffffff81989798: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a61a50)
Location: net/core/bpf_sk_storage.c:388
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81a61a50-ffffffff81a61d30: sk_storage_update (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c31c88)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffff800010c31c88-ffff800010c31fd0: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d48788)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
c0d48788-c0d48a6c: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2ac00)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
c000000000d2ac00-c000000000d2af74: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a75ae)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffe0007a75ae-ffffffe0007a77a0: sk_storage_update (STB_LOCAL)
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
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81929350)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81929350-ffffffff81929608: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e3100)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff818e3100-ffffffff818e33b8: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8197a4e0)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff8197a4e0-ffffffff8197a798: sk_storage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_sk_storage_data *sk_storage_update(struct sock *sk, struct bpf_map *map, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199ca10)
Location: net/core/bpf_sk_storage.c:387
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff8199ca10-ffffffff8199ccc8: sk_storage_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
