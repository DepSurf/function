# Function: <code>zero_resv_unavail</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8198d671)
Location: mm/page_alloc.c:6251
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff8198d671-ffffffff8198d776: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff819e9f31)
Location: mm/page_alloc.c:6394
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff819e9f31-ffffffff819ea036: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b9507)
Location: mm/page_alloc.c:6709
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828b9507-ffffffff828b95fa: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d65fe)
Location: mm/page_alloc.c:6905
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828d65fe-ffffffff828d66ea: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828dea81)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828dea81-ffffffff828deb7b: zero_resv_unavail (STB_GLOBAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000114577b4)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffff8000114577b4-ffff8000114578c8: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/mm.h:2216
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000001380db8)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
c000000001380db8-c000000001380efc: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000016298)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffe000016298-ffffffe00001637a: zero_resv_unavail (STB_GLOBAL)
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
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c7935)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828c7935-ffffffff828c7a2f: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c005a)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828c005a-ffffffff828c0154: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828da6b5)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828da6b5-ffffffff828da7af: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void zero_resv_unavail();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828dfad6)
Location: mm/page_alloc.c:6926
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828dfad6-ffffffff828dfbd0: zero_resv_unavail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
