# Function: <code>rbt_memtype_check_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81071e50)
Location: arch/x86/mm/pat_rbtree.c:191
Inline: False
```
**Symbols:**

```
ffffffff81071e50-ffffffff81072016: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81072c80)
Location: arch/x86/mm/pat_rbtree.c:200
Inline: False
```
**Symbols:**

```
ffffffff81072c80-ffffffff81072dd6: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81076830)
Location: arch/x86/mm/pat_rbtree.c:200
Inline: False
```
**Symbols:**

```
ffffffff81076830-ffffffff81076986: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff81074fa0)
Location: arch/x86/mm/pat_rbtree.c:200
Inline: False
```
**Symbols:**

```
ffffffff81074fa0-ffffffff81075151: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (ffffffff8107b1e0)
Location: arch/x86/mm/pat_rbtree.c:201
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff8107b1e0-ffffffff8107b391: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:201
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff8107e776-ffffffff8107e7f1: rbt_memtype_check_insert.cold.8 (STB_LOCAL)
ffffffff8107dfb0-ffffffff8107e0f8: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:201
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff810852f6-ffffffff81085371: rbt_memtype_check_insert.cold.8 (STB_LOCAL)
ffffffff81084b30-ffffffff81084c78: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:201
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff81088ef1-ffffffff81088f75: rbt_memtype_check_insert.cold (STB_LOCAL)
ffffffff81088780-ffffffff81088877: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:188
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff81089b61-ffffffff81089be5: rbt_memtype_check_insert.cold (STB_LOCAL)
ffffffff810893f0-ffffffff810894e7: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:188
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff81088b21-ffffffff81088ba5: rbt_memtype_check_insert.cold (STB_LOCAL)
ffffffff810883b0-ffffffff810884a7: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:188
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff81077781-ffffffff81077805: rbt_memtype_check_insert.cold (STB_LOCAL)
ffffffff81077010-ffffffff81077107: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:188
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff81088ad1-ffffffff81088b55: rbt_memtype_check_insert.cold (STB_LOCAL)
ffffffff81088360-ffffffff81088457: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rbt_memtype_check_insert(struct memtype *new, enum page_cache_mode *ret_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat_rbtree.c (0)
Location: arch/x86/mm/pat_rbtree.c:188
Inline: False
Direct callers:
  - arch/x86/mm/pat.c:reserve_memtype
```
**Symbols:**

```
ffffffff8108ad71-ffffffff8108adf5: rbt_memtype_check_insert.cold (STB_LOCAL)
ffffffff8108a600-ffffffff8108a6f7: rbt_memtype_check_insert (STB_GLOBAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
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
