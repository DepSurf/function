# Function: <code>__map_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81f7ab3f)
Location: arch/x86/platform/efi/efi_64.c:204
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
```
**Symbols:**

```
ffffffff81f7ab3f-ffffffff81f7aba0: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81fa3440)
Location: arch/x86/platform/efi/efi_64.c:289
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff81fa3440-ffffffff81fa3498: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff81fded79)
Location: arch/x86/platform/efi/efi_64.c:315
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff81fded79-ffffffff81fdedd1: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff820bfc4a)
Location: arch/x86/platform/efi/efi_64.c:399
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff820bfc4a-ffffffff820bfca7: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff826c7d92)
Location: arch/x86/platform/efi/efi_64.c:417
Inline: True
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff826c7d92-ffffffff826c7e11: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff826f1dad)
Location: arch/x86/platform/efi/efi_64.c:411
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff826f1dad-ffffffff826f1e33: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828a8bf9)
Location: arch/x86/platform/efi/efi_64.c:411
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828a8bf9-ffffffff828a8c7f: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828c13ba)
Location: arch/x86/platform/efi/efi_64.c:414
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828c13ba-ffffffff828c143b: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828c7839)
Location: arch/x86/platform/efi/efi_64.c:412
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828c7839-ffffffff828c78ba: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff82cea8da)
Location: arch/x86/platform/efi/efi_64.c:281
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff82cea8da-ffffffff82cea96b: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff82fd8193)
Location: arch/x86/platform/efi/efi_64.c:265
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff82fd8193-ffffffff82fd8224: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff831e2b92)
Location: arch/x86/platform/efi/efi_64.c:262
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff831e2b92-ffffffff831e2c23: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff832c6517)
Location: arch/x86/platform/efi/efi_64.c:262
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff832c6517-ffffffff832c65a8: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff83479251)
Location: arch/x86/platform/efi/efi_64.c:262
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff83479251-ffffffff834792f7: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff83ea3370)
Location: arch/x86/platform/efi/efi_64.c:270
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff83ea3370-ffffffff83ea3435: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff836c75c0)
Location: arch/x86/platform/efi/efi_64.c:270
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff836c75c0-ffffffff836c7685: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff838f81c0)
Location: arch/x86/platform/efi/efi_64.c:270
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff838f81c0-ffffffff838f8285: __map_region (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828b27d1)
Location: arch/x86/platform/efi/efi_64.c:412
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828b27d1-ffffffff828b2852: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828aa943)
Location: arch/x86/platform/efi/efi_64.c:412
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828aa943-ffffffff828aa9c4: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828c56d0)
Location: arch/x86/platform/efi/efi_64.c:412
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828c56d0-ffffffff828c5751: __map_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __map_region(efi_memory_desc_t *md, u64 va);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi_64.c (ffffffff828c8876)
Location: arch/x86/platform/efi/efi_64.c:412
Inline: False
Direct callers:
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region_fixed
  - arch/x86/platform/efi/efi_64.c:efi_map_region
  - arch/x86/platform/efi/efi_64.c:efi_map_region
```
**Symbols:**

```
ffffffff828c8876-ffffffff828c88f7: __map_region (STB_LOCAL)
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
