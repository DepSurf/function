# Function: <code>single_hugepage_flag_store</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81214120)
Location: mm/huge_memory.c:202
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff81214120-ffffffff812141a8: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81226560)
Location: mm/huge_memory.c:222
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff81226560-ffffffff812265e8: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81232400)
Location: mm/huge_memory.c:198
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff81232400-ffffffff8123248a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124fac0)
Location: mm/huge_memory.c:198
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff8124fac0-ffffffff8124fb4a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81274020)
Location: mm/huge_memory.c:198
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff81274020-ffffffff812740aa: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81289050)
Location: mm/huge_memory.c:208
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff81289050-ffffffff812890da: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a3d00)
Location: mm/huge_memory.c:213
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812a3d00-ffffffff812a3d8a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b5200)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812b5200-ffffffff812b528a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e8a4c)
Location: mm/huge_memory.c:210
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812ea6c0-ffffffff812ea74a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f3ebc)
Location: mm/huge_memory.c:215
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812f5b20-ffffffff812f5baa: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f9f4c)
Location: mm/huge_memory.c:228
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812fbf00-ffffffff812fbf8a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81343dac)
Location: mm/huge_memory.c:228
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff81345d50-ffffffff81345dda: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813b93ec)
Location: mm/huge_memory.c:227
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff813bbf30-ffffffff813bbfd1: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143b73c)
Location: mm/huge_memory.c:290
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:defrag_store
```
**Symbols:**

```
ffffffff8143e4a0-ffffffff8143e541: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8147114c)
Location: mm/huge_memory.c:291
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:defrag_store
```
**Symbols:**

```
ffffffff81473c80-ffffffff81473d21: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a087c)
Location: mm/huge_memory.c:325
Inline: True
Inline callers:
  - mm/huge_memory.c:use_zero_page_store
Direct callers:
  - mm/khugepaged.c:defrag_store
```
**Symbols:**

```
ffffffff814a3180-ffffffff814a3221: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010356698)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffff800010356698-ffff80001035677c: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043da00)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
c00000000043da00-c00000000043db10: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad7e0)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812ad7e0-ffffffff812ad86a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129ee60)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff8129ee60-ffffffff8129eeea: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab5f0)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812ab5f0-ffffffff812ab67a: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t single_hugepage_flag_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count, enum transparent_hugepage_flag flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bb960)
Location: mm/huge_memory.c:210
Inline: False
Direct callers:
  - mm/huge_memory.c:use_zero_page_store
  - mm/khugepaged.c:khugepaged_defrag_store
```
**Symbols:**

```
ffffffff812bb960-ffffffff812bb9ea: single_hugepage_flag_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
