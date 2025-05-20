# Function: <code>bpf_mem_alloc_init</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_mem_alloc_init(struct bpf_mem_alloc *ma, int size, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8131c1f0)
Location: kernel/bpf/memalloc.c:377
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_global_ma_init
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8131c1f0-ffffffff8131c40c: bpf_mem_alloc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_mem_alloc_init(struct bpf_mem_alloc *ma, int size, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8134bc90)
Location: kernel/bpf/memalloc.c:380
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_global_ma_init
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
```
**Symbols:**

```
ffffffff8134bc90-ffffffff8134bee2: bpf_mem_alloc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_mem_alloc_init(struct bpf_mem_alloc *ma, int size, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff81372cc0)
Location: kernel/bpf/memalloc.c:513
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_global_ma_init
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
  - kernel/bpf/cpumask.c:cpumask_kfunc_init
```
**Symbols:**

```
ffffffff81372cc0-ffffffff8137307a: bpf_mem_alloc_init (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
