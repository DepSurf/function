# Function: <code>sparse_buffer_free</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81acea63)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81acea63-ffffffff81aceaaa: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81bc7450)
Location: mm/sparse.c:469
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81bc7450-ffffffff81bc7493: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c40153)
Location: mm/sparse.c:468
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81c40153-ffffffff81c40196: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81c32214)
Location: mm/sparse.c:477
Inline: False
Direct callers:
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
```
**Symbols:**

```
ffffffff81c32214-ffffffff81c32258: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81d50c14)
Location: mm/sparse.c:451
Inline: False
Direct callers:
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
```
**Symbols:**

```
ffffffff81d50c14-ffffffff81d50c58: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81f20e4b)
Location: mm/sparse.c:452
Inline: False
Direct callers:
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
```
**Symbols:**

```
ffffffff81f20e4b-ffffffff81f20e74: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff820caad5)
Location: mm/sparse.c:452
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8214ed65)
Location: mm/sparse.c:452
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff82231bd5)
Location: mm/sparse.c:451
Inline: True
Inline callers:
  - mm/sparse.c:sparse_buffer_alloc
  - mm/sparse.c:sparse_buffer_fini
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
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff800010da0590)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffff800010da0590-ffff800010da05fc: sparse_buffer_free (STB_LOCAL)
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
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000000eed288)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
c000000000eed288-c000000000eed2dc: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe000048c92)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffe000048c92-ffffffe000048cc6: sparse_buffer_free (STB_LOCAL)
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
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a6d8d3)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81a6d8d3-ffffffff81a6d91a: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81a29e1a)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81a29e1a-ffffffff81a29e61: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ad9ce3)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81ad9ce3-ffffffff81ad9d2a: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sparse_buffer_free(long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81ae6199)
Location: mm/sparse.c:475
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_buffer_alloc
```
**Symbols:**

```
ffffffff81ae6199-ffffffff81ae61e0: sparse_buffer_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
