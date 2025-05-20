# Function: <code>madvise_set_anon_name</code>

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
int madvise_set_anon_name(struct mm_struct *mm, long unsigned int start, long unsigned int len_in, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81378930)
Location: mm/madvise.c:1273
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
```
**Symbols:**

```
ffffffff81378930-ffffffff813789aa: madvise_set_anon_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int madvise_set_anon_name(struct mm_struct *mm, long unsigned int start, long unsigned int len_in, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f6250)
Location: mm/madvise.c:1306
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
```
**Symbols:**

```
ffffffff813f6250-ffffffff813f62ca: madvise_set_anon_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int madvise_set_anon_name(struct mm_struct *mm, long unsigned int start, long unsigned int len_in, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81429040)
Location: mm/madvise.c:1308
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
```
**Symbols:**

```
ffffffff81429040-ffffffff814290ba: madvise_set_anon_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int madvise_set_anon_name(struct mm_struct *mm, long unsigned int start, long unsigned int len_in, struct anon_vma_name *anon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81462870)
Location: mm/madvise.c:1302
Inline: False
Direct callers:
  - kernel/sys.c:prctl_set_vma
```
**Symbols:**

```
ffffffff81462870-ffffffff814628ea: madvise_set_anon_name (STB_GLOBAL)
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
