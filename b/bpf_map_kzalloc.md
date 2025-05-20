# Function: <code>bpf_map_kzalloc</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fdb30)
Location: kernel/bpf/syscall.c:416
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811fdb30-ffffffff811fdbc4: bpf_map_kzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe6f0)
Location: kernel/bpf/syscall.c:417
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff811fe6f0-ffffffff811fe784: bpf_map_kzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230330)
Location: kernel/bpf/syscall.c:436
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81230330-ffffffff812303c4: bpf_map_kzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81272cb0)
Location: kernel/bpf/syscall.c:443
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff81272cb0-ffffffff81272d5c: bpf_map_kzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c9040)
Location: kernel/bpf/syscall.c:459
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff812c9040-ffffffff812c914c: bpf_map_kzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f0610)
Location: kernel/bpf/syscall.c:427
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff812f0610-ffffffff812f071c: bpf_map_kzalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_map_kzalloc(const struct bpf_map *map, size_t size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f3f0)
Location: kernel/bpf/syscall.c:428
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_selem_alloc
  - net/xdp/xskmap.c:xsk_map_update_elem
```
**Symbols:**

```
ffffffff8130f3f0-ffffffff8130f4fc: bpf_map_kzalloc (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
