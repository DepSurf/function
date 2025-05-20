# Function: <code>vmacache_flush_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vmacache_flush_all(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmacache.c (ffffffff811b83b0)
Location: mm/vmacache.c:16
Inline: False
Direct callers:
  - mm/mmap.c:vma_adjust
  - mm/mmap.c:do_munmap
```
**Symbols:**

```
ffffffff811b83b0-ffffffff811b8457: vmacache_flush_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vmacache_flush_all(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmacache.c (ffffffff811d2650)
Location: mm/vmacache.c:16
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:vma_adjust
```
**Symbols:**

```
ffffffff811d2650-ffffffff811d26f7: vmacache_flush_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vmacache_flush_all(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmacache.c (ffffffff811e2510)
Location: mm/vmacache.c:16
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff811e2510-ffffffff811e25b7: vmacache_flush_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vmacache_flush_all(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmacache.c (ffffffff811ec340)
Location: mm/vmacache.c:17
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff811ec340-ffffffff811ec3e7: vmacache_flush_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vmacache_flush_all(struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmacache.c (ffffffff812026b0)
Location: mm/vmacache.c:18
Inline: False
Direct callers:
  - mm/mmap.c:do_munmap
  - mm/mmap.c:__vma_adjust
```
**Symbols:**

```
ffffffff812026b0-ffffffff81202757: vmacache_flush_all (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
