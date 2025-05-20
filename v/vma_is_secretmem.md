# Function: <code>vma_is_secretmem</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool vma_is_secretmem(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff813668c0)
Location: mm/secretmem.c:126
Inline: False
Direct callers:
  - mm/gup.c:check_vma_flags
  - mm/gup.c:follow_page
  - mm/mlock.c:mlock_fixup
```
**Symbols:**

```
ffffffff813668c0-ffffffff813668d9: vma_is_secretmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool vma_is_secretmem(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff813e3c40)
Location: mm/secretmem.c:137
Inline: False
Direct callers:
  - mm/gup.c:check_vma_flags
  - mm/gup.c:follow_page
  - mm/mlock.c:mlock_fixup
```
**Symbols:**

```
ffffffff813e3c40-ffffffff813e3c5f: vma_is_secretmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool vma_is_secretmem(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff8146b630)
Location: mm/secretmem.c:137
Inline: False
Direct callers:
  - mm/gup.c:check_vma_flags
  - mm/gup.c:follow_page
  - mm/mlock.c:mlock_fixup
```
**Symbols:**

```
ffffffff8146b630-ffffffff8146b64c: vma_is_secretmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vma_is_secretmem(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff814a0430)
Location: mm/secretmem.c:137
Inline: False
Direct callers:
  - mm/gup.c:check_vma_flags
  - mm/gup.c:follow_page
  - mm/mlock.c:mlock_fixup
```
**Symbols:**

```
ffffffff814a0430-ffffffff814a044c: vma_is_secretmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vma_is_secretmem(struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/secretmem.c (ffffffff814cfaa0)
Location: mm/secretmem.c:139
Inline: False
Direct callers:
  - mm/gup.c:check_vma_flags
  - mm/gup.c:follow_page
  - mm/mlock.c:mlock_fixup
```
**Symbols:**

```
ffffffff814cfaa0-ffffffff814cfabc: vma_is_secretmem (STB_GLOBAL)
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
