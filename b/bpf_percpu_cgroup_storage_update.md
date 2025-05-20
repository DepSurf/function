# Function: <code>bpf_percpu_cgroup_storage_update</code>

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
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d8400)
Location: kernel/bpf/local_storage.c:187
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d8400-ffffffff811d84cd: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ecea0)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ecea0-ffffffff811ecf73: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f95f0)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f95f0-ffffffff811f96c3: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d480)
Location: kernel/bpf/local_storage.c:200
Inline: False
```
**Symbols:**

```
ffffffff8121d480-ffffffff8121d54e: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81220390)
Location: kernel/bpf/local_storage.c:212
Inline: False
```
**Symbols:**

```
ffffffff81220390-ffffffff81220468: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223e20)
Location: kernel/bpf/local_storage.c:213
Inline: False
```
**Symbols:**

```
ffffffff81223e20-ffffffff81223efe: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125bce0)
Location: kernel/bpf/local_storage.c:211
Inline: False
```
**Symbols:**

```
ffffffff8125bce0-ffffffff8125bdfe: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a57d0)
Location: kernel/bpf/local_storage.c:211
Inline: False
```
**Symbols:**

```
ffffffff812a57d0-ffffffff812a5917: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81303740)
Location: kernel/bpf/local_storage.c:211
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81303740-ffffffff81303890: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81332170)
Location: kernel/bpf/local_storage.c:211
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81332170-ffffffff813322c0: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81356720)
Location: kernel/bpf/local_storage.c:211
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81356720-ffffffff81356870: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
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
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027ee68)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffff80001027ee68-ffff80001027ef9c: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b0398)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c04b0398-c04b0488: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000328f60)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
c000000000328f60-c0000000003290fc: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5cd8)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffe0001b5cd8-ffffffe0001b5ddc: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
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
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1c10)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811f1c10-ffffffff811f1ce3: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4960)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811e4960-ffffffff811e4a33: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef9e0)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811ef9e0-ffffffff811efab3: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_percpu_cgroup_storage_update(struct bpf_map *_map, void *_key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fdee0)
Location: kernel/bpf/local_storage.c:200
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_update_elem
```
**Symbols:**

```
ffffffff811fdee0-ffffffff811fdfcb: bpf_percpu_cgroup_storage_update (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *key</code>
</li>
<li>
<b>Param removed. </b>
<code>void *_key</code>
</li>
</ul>
</details>
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
