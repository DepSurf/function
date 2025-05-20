# Function: <code>vmemmap_p4d_populate</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819056a3)
Location: mm/sparse-vmemmap.c:211
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff819056a3-ffffffff81905750: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8198f70d)
Location: mm/sparse-vmemmap.c:225
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff8198f70d-ffffffff8198f7c3: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff819ebf85)
Location: mm/sparse-vmemmap.c:203
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff819ebf85-ffffffff819ec030: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a271f3)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a271f3-ffffffff81a2729e: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a97a9e)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a97a9e-ffffffff81a97b4c: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81acf36c)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81acf36c-ffffffff81acf41a: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81bc7d27)
Location: mm/sparse-vmemmap.c:191
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81bc7d27-ffffffff81bc7e17: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c40a52)
Location: mm/sparse-vmemmap.c:195
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81c40a52-ffffffff81c40b42: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81c329b1)
Location: mm/sparse-vmemmap.c:195
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81c329b1-ffffffff81c32aa5: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81d513bf)
Location: mm/sparse-vmemmap.c:549
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81d513bf-ffffffff81d51475: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81f21649)
Location: mm/sparse-vmemmap.c:610
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff81f21649-ffffffff81f2171c: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff820cb7c0)
Location: mm/sparse-vmemmap.c:220
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff820cb7c0-ffffffff820cb8bb: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff8214fa50)
Location: mm/sparse-vmemmap.c:220
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff8214fa50-ffffffff8214fb4b: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff82232910)
Location: mm/sparse-vmemmap.c:220
Inline: False
Direct callers:
  - mm/sparse-vmemmap.c:vmemmap_populate_hugepages
  - mm/sparse-vmemmap.c:vmemmap_populate_address
```
**Symbols:**

```
ffffffff82232910-ffffffff82232976: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
pgd_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffff800010da0f50)
Location: mm/sparse-vmemmap.c:192
Inline: True
```
**Symbols:**

```
ffff800010da0f50-ffff800010da0f54: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
pgd_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (c000000000eede28)
Location: mm/sparse-vmemmap.c:192
Inline: True
```
**Symbols:**

```
c000000000eede28-c000000000eede2c: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffe0000490cc)
Location: mm/sparse-vmemmap.c:192
Inline: True
```
**Symbols:**

```
ffffffe0000490cc-ffffffe0000490d8: vmemmap_p4d_populate (STB_GLOBAL)
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
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a6e1dc)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a6e1dc-ffffffff81a6e28a: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81a2a623)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81a2a623-ffffffff81a2a692: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ada5ec)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81ada5ec-ffffffff81ada69a: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
p4d_t *vmemmap_p4d_populate(pgd_t *pgd, long unsigned int addr, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse-vmemmap.c (ffffffff81ae6aa2)
Location: mm/sparse-vmemmap.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:vmemmap_populate
  - mm/sparse-vmemmap.c:vmemmap_populate_basepages
```
**Symbols:**

```
ffffffff81ae6aa2-ffffffff81ae6b50: vmemmap_p4d_populate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>p4d_t *</code> ➡️ <code>pgd_t *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>p4d_t *</code> ➡️ <code>pgd_t *</code>
</li>
</ul>
</details>
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
