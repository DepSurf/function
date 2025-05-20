# Function: <code>check_usemap_section_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81f8c6a9)
Location: mm/sparse.c:294
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81fb63d3)
Location: mm/sparse.c:296
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ff2d9c)
Location: mm/sparse.c:296
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff820d54a2)
Location: mm/sparse.c:333
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff826de073)
Location: mm/sparse.c:339
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8270866f)
Location: mm/sparse.c:319
Inline: True
Inline callers:
  - mm/sparse.c:sparse_early_usemaps_alloc_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828bf971)
Location: mm/sparse.c:336
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828d8b64)
Location: mm/sparse.c:381
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828e0fe2)
Location: mm/sparse.c:383
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff82cfe560)
Location: mm/sparse.c:378
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff82cfe560-ffffffff82cfe67b: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff82feaf53)
Location: mm/sparse.c:377
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff82feaf53-ffffffff82feb06e: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff831f58dc)
Location: mm/sparse.c:386
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff831f58dc-ffffffff831f59f3: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff832dbf7f)
Location: mm/sparse.c:361
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff832dbf7f-ffffffff832dc0a6: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8349173e)
Location: mm/sparse.c:361
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff8349173e-ffffffff83491868: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff83ec4d90)
Location: mm/sparse.c:361
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff83ec4d90-ffffffff83ec4f0a: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff836e9e80)
Location: mm/sparse.c:361
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff836e9e80-ffffffff836e9ffa: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_usemap_section_nr(int nid, struct mem_section_usage *usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8391d240)
Location: mm/sparse.c:360
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff8391d240-ffffffff8391d3ba: check_usemap_section_nr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (0)
Location: mm/sparse.c:433
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c0000000013840b4)
Location: mm/sparse.c:383
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (0)
Location: mm/sparse.c:433
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828c9e96)
Location: mm/sparse.c:383
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828c25bb)
Location: mm/sparse.c:383
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828dcc16)
Location: mm/sparse.c:383
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828e202d)
Location: mm/sparse.c:383
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
