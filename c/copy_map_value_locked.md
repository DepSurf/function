# Function: <code>copy_map_value_locked</code>

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
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e6760)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff811e6760-ffffffff811e6842: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2eb0)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff811f2eb0-ffffffff811f2f92: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214e70)
Location: kernel/bpf/helpers.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81214e70-ffffffff81214f52: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216a60)
Location: kernel/bpf/helpers.c:325
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81216a60-ffffffff81216b42: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812197a0)
Location: kernel/bpf/helpers.c:326
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812197a0-ffffffff812198a1: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81250430)
Location: kernel/bpf/helpers.c:336
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81250430-ffffffff81250483: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81297aa0)
Location: kernel/bpf/helpers.c:350
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81297aa0-ffffffff81297b2b: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f2c10)
Location: kernel/bpf/helpers.c:367
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff812f2c10-ffffffff812f2ca6: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131f950)
Location: kernel/bpf/helpers.c:368
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff8131f950-ffffffff8131f9e6: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81341e40)
Location: kernel/bpf/helpers.c:374
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_copy_value
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:diag_get
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff81341e40-ffffffff81341ed6: copy_map_value_locked (STB_GLOBAL)
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
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff800010276998)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffff800010276998-ffff800010276acc: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8f54)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c04a8f54-c04a9080: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031ef00)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c00000000031ef00-c00000000031f088: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001aed14)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffe0001aed14-ffffffe0001aee08: copy_map_value_locked (STB_GLOBAL)
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
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eb4d0)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff811eb4d0-ffffffff811eb5b2: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811de280)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff811de280-ffffffff811de34d: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e92a0)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff811e92a0-ffffffff811e9382: copy_map_value_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void copy_map_value_locked(struct bpf_map *map, void *dst, void *src, bool lock_src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f7650)
Location: kernel/bpf/helpers.c:299
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/arraymap.c:array_map_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff811f7650-ffffffff811f7756: copy_map_value_locked (STB_GLOBAL)
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
