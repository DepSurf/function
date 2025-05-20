# Function: <code>bpf_map_uncharge_memlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81172981)
Location: kernel/bpf/syscall.c:67
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811807a1)
Location: kernel/bpf/syscall.c:82
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118dd23)
Location: kernel/bpf/syscall.c:110
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811939e7)
Location: kernel/bpf/syscall.c:121
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811a11c1)
Location: kernel/bpf/syscall.c:168
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5482)
Location: kernel/bpf/syscall.c:202
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c32a0)
Location: kernel/bpf/syscall.c:232
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811c32a0-ffffffff811c32bc: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3ff0)
Location: kernel/bpf/syscall.c:248
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d3ff0-ffffffff811d400e: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0380)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811e0380-ffffffff811e039e: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe8c0)
Location: kernel/bpf/syscall.c:405
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811fe8c0-ffffffff811fe8de: bpf_map_uncharge_memlock (STB_GLOBAL)
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
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102629a0)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffff8000102629a0-ffff800010262a14: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04954d8)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
c04954d8-c0495524: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003076d0)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
c0000000003076d0-c000000000307708: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f2ce)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffe00019f2ce-ffffffe00019f314: bpf_map_uncharge_memlock (STB_GLOBAL)
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
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d89a0)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d89a0-ffffffff811d89be: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb760)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811cb760-ffffffff811cb77e: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6770)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d6770-ffffffff811d678e: bpf_map_uncharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_uncharge_memlock(struct bpf_map *map, u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4ae0)
Location: kernel/bpf/syscall.c:251
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811e4ae0-ffffffff811e4afe: bpf_map_uncharge_memlock (STB_GLOBAL)
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
