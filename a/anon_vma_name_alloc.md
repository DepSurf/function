# Function: <code>anon_vma_name_alloc</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct anon_vma_name *anon_vma_name_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81377f20)
Location: mm/madvise.c:70
Inline: False
Direct callers:
  - kernel/fork.c:vm_area_dup
  - kernel/sys.c:prctl_set_vma
  - mm/madvise.c:madvise_update_vma
```
**Symbols:**

```
ffffffff81377f20-ffffffff81377f79: anon_vma_name_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct anon_vma_name *anon_vma_name_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f5820)
Location: mm/madvise.c:71
Inline: False
Direct callers:
  - kernel/fork.c:vm_area_dup
  - kernel/sys.c:prctl_set_vma
  - mm/madvise.c:madvise_update_vma
```
**Symbols:**

```
ffffffff813f5820-ffffffff813f5879: anon_vma_name_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct anon_vma_name *anon_vma_name_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81428570)
Location: mm/madvise.c:71
Inline: False
Direct callers:
  - kernel/fork.c:vm_area_dup
  - kernel/sys.c:prctl_set_vma
  - mm/madvise.c:madvise_update_vma
```
**Symbols:**

```
ffffffff81428570-ffffffff814285c9: anon_vma_name_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct anon_vma_name *anon_vma_name_alloc(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81461e20)
Location: mm/madvise.c:71
Inline: False
Direct callers:
  - kernel/fork.c:vm_area_dup
  - kernel/sys.c:prctl_set_vma
  - mm/madvise.c:madvise_update_vma
```
**Symbols:**

```
ffffffff81461e20-ffffffff81461e79: anon_vma_name_alloc (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
