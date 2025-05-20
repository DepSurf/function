# Function: <code>vmemmap_alloc_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8181f0b9)
Location: mm/sparse-vmemmap.c:50
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
```
**Symbols:**

```
ffffffff8181f0b9-ffffffff8181f179: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818995c8)
Location: mm/sparse-vmemmap.c:51
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:alloc_block_buf
```
**Symbols:**

```
ffffffff818995c8-ffffffff8189965c: vmemmap_alloc_block.part.0 (STB_LOCAL)
ffffffff8189965c-ffffffff818996c0: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff818cdc80)
Location: mm/sparse-vmemmap.c:51
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pgd_populate
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:alloc_block_buf
```
**Symbols:**

```
ffffffff818cdc80-ffffffff818cdd0e: vmemmap_alloc_block.part.0 (STB_LOCAL)
ffffffff818cdd0e-ffffffff818cdd72: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81905127)
Location: mm/sparse-vmemmap.c:51
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:alloc_block_buf
```
**Symbols:**

```
ffffffff81905127-ffffffff819051a4: vmemmap_alloc_block.part.3 (STB_LOCAL)
ffffffff819051a4-ffffffff81905209: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f119)
Location: mm/sparse-vmemmap.c:52
Inline: True
Direct callers:
  - mm/sparse-vmemmap.c:alloc_block_buf
```
**Symbols:**

```
ffffffff8198f119-ffffffff8198f1f7: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819eb995)
Location: mm/sparse-vmemmap.c:52
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff819eb995-ffffffff819eba73: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a26c18)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81a26c18-ffffffff81a26cf4: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a974b9)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81a974b9-ffffffff81a97597: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81aced9b)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81aced9b-ffffffff81acee79: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc7765)
Location: mm/sparse-vmemmap.c:48
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81bc7765-ffffffff81bc783a: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c40491)
Location: mm/sparse-vmemmap.c:48
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81c40491-ffffffff81c4056f: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c32539)
Location: mm/sparse-vmemmap.c:48
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81c32539-ffffffff81c32617: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d51078)
Location: mm/sparse-vmemmap.c:402
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81d51078-ffffffff81d51177: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f212a2)
Location: mm/sparse-vmemmap.c:448
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81f212a2-ffffffff81f213ab: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cb140)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
**Symbols:**

```
ffffffff820cb140-ffffffff820cb27a: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214f3d0)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
**Symbols:**

```
ffffffff8214f3d0-ffffffff8214f50a: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff822322a0)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_pte_populate
```
**Symbols:**

```
ffffffff822322a0-ffffffff822323da: vmemmap_alloc_block (STB_GLOBAL)
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
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da09a0)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffff800010da09a0-ffff800010da0ab4: vmemmap_alloc_block (STB_GLOBAL)
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
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eed774)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - arch/powerpc/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
c000000000eed774-c000000000eed89c: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe000048d5c)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_pud_populate
  - mm/sparse-vmemmap.c:vmemmap_pmd_populate
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffe000048d5c-ffffffe000048e1e: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6dc0b)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81a6dc0b-ffffffff81a6dce9: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2a152)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81a2a152-ffffffff81a2a230: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ada01b)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81ada01b-ffffffff81ada0f9: vmemmap_alloc_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vmemmap_alloc_block(long unsigned int size, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ae64d1)
Location: mm/sparse-vmemmap.c:49
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_alloc_block_buf
```
**Symbols:**

```
ffffffff81ae64d1-ffffffff81ae65af: vmemmap_alloc_block (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
