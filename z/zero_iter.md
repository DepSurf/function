# Function: <code>zero_iter</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t zero_iter(struct iov_iter *iter, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814104c0)
Location: mm/vmalloc.c:3571
Inline: False
Direct callers:
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:aligned_vread_iter
```
**Symbols:**

```
ffffffff814104c0-ffffffff8141057e: zero_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t zero_iter(struct iov_iter *iter, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8143ce20)
Location: mm/vmalloc.c:3571
Inline: False
Direct callers:
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:vread_iter
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:vmap_ram_vread_iter
  - mm/vmalloc.c:aligned_vread_iter
```
**Symbols:**

```
ffffffff8143ce20-ffffffff8143cede: zero_iter (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
