# Function: <code>bpf_mem_free</code>

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
void bpf_mem_free(struct bpf_mem_alloc *ma, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8131c750)
Location: kernel/bpf/memalloc.c:649
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_obj_drop_impl
  - kernel/bpf/helpers.c:bpf_list_head_free
```
**Symbols:**

```
ffffffff8131c750-ffffffff8131c804: bpf_mem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_mem_free(struct bpf_mem_alloc *ma, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff8134c250)
Location: kernel/bpf/memalloc.c:649
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:__bpf_obj_drop_impl
```
**Symbols:**

```
ffffffff8134c250-ffffffff8134c304: bpf_mem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_mem_free(struct bpf_mem_alloc *ma, void *ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/memalloc.c (ffffffff813736b0)
Location: kernel/bpf/memalloc.c:913
Inline: False
Direct callers:
  - kernel/bpf/task_iter.c:bpf_iter_css_task_destroy
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_destroy
  - kernel/bpf/task_iter.c:bpf_iter_task_vma_new
```
**Symbols:**

```
ffffffff813736b0-ffffffff81373777: bpf_mem_free (STB_GLOBAL)
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
