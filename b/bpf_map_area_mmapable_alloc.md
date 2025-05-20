# Function: <code>bpf_map_area_mmapable_alloc</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe6d0)
Location: kernel/bpf/syscall.c:308
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff811fe6d0-ffffffff811fe6e5: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fd9b0)
Location: kernel/bpf/syscall.c:316
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff811fd9b0-ffffffff811fd9c5: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe570)
Location: kernel/bpf/syscall.c:317
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff811fe570-ffffffff811fe585: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812301b0)
Location: kernel/bpf/syscall.c:336
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff812301b0-ffffffff812301c5: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81272ae0)
Location: kernel/bpf/syscall.c:342
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff81272ae0-ffffffff81272aff: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c8db0)
Location: kernel/bpf/syscall.c:342
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff812c8db0-ffffffff812c8dcf: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f03a0)
Location: kernel/bpf/syscall.c:315
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff812f03a0-ffffffff812f03bf: bpf_map_area_mmapable_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_map_area_mmapable_alloc(u64 size, int numa_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130f180)
Location: kernel/bpf/syscall.c:316
Inline: False
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff8130f180-ffffffff8130f19f: bpf_map_area_mmapable_alloc (STB_GLOBAL)
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
