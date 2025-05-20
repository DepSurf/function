# Function: <code>agp_alloc_page_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8151cb70)
Location: drivers/char/agp/generic.c:89
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8151cb70-ffffffff8151cbbc: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8156f8c0)
Location: drivers/char/agp/generic.c:89
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8156f8c0-ffffffff8156f90c: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8159bf80)
Location: drivers/char/agp/generic.c:89
Inline: False
Direct callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8159bf80-ffffffff8159bfcc: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff815b1534)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff815affb0-ffffffff815affd3: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81618124)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81616b50-ffffffff81616b73: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81651a2d)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81650870-ffffffff81650893: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166f8cd)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8166ea30-ffffffff8166ea53: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816a544d)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff816a4640-ffffffff816a4663: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816c817d)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff816c7370-ffffffff816c7393: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8177d20d)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8177be30-ffffffff8177be56: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8179635d)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81794f80-ffffffff81794fa6: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8177902d)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81777c30-ffffffff81777c56: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff817fef4d)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff817fd8c0-ffffffff817fd8e6: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8193e020)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8193c8d0-ffffffff8193c902: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81a9ef20)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81a9d3e0-ffffffff81a9d412: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81aea88e)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81ae8d40-ffffffff81ae8d72: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff81b3dd6d)
Location: drivers/char/agp/generic.c:90
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff81b3c1d0-ffffffff81b3c202: agp_alloc_page_array (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (c000000000955e30)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
c0000000009545c0-c00000000095460c: agp_alloc_page_array (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8168dbcd)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8168cdc0-ffffffff8168cde3: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff8166b5bd)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff8166a7b0-ffffffff8166a7d3: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816bbe3d)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff816bb030-ffffffff816bb053: agp_alloc_page_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void agp_alloc_page_array(size_t size, struct agp_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/generic.c (ffffffff816d640d)
Location: drivers/char/agp/generic.c:91
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
**Symbols:**

```
ffffffff816d5600-ffffffff816d5623: agp_alloc_page_array (STB_GLOBAL)
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
