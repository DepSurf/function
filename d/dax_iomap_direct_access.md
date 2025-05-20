# Function: <code>dax_iomap_direct_access</code>

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
int dax_iomap_direct_access(const struct iomap *iomap, loff_t pos, size_t size, void **kaddr, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f7ad0)
Location: fs/dax.c:1053
Inline: False
Direct callers:
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_dedupe_file_range_compare
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_file_unshare
  - fs/dax.c:dax_file_unshare
  - fs/dax.c:dax_iomap_copy_around
```
**Symbols:**

```
ffffffff814f7ad0-ffffffff814f7bba: dax_iomap_direct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dax_iomap_direct_access(const struct iomap *iomap, loff_t pos, size_t size, void **kaddr, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8152e920)
Location: fs/dax.c:1080
Inline: False
Direct callers:
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_copy_around
```
**Symbols:**

```
ffffffff8152e920-ffffffff8152ea0a: dax_iomap_direct_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dax_iomap_direct_access(const struct iomap *iomap, loff_t pos, size_t size, void **kaddr, pfn_t *pfnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81563800)
Location: fs/dax.c:1066
Inline: False
Direct callers:
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_range_compare_iter
  - fs/dax.c:dax_fault_iter
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_unshare_iter
  - fs/dax.c:dax_iomap_copy_around
```
**Symbols:**

```
ffffffff81563800-ffffffff815638ea: dax_iomap_direct_access (STB_LOCAL)
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
