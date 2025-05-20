# Function: <code>xas_create_range</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a18440)
Location: lib/xarray.c:682
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81a18440-ffffffff81a1853b: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a88060)
Location: lib/xarray.c:699
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_shmem
```
**Symbols:**

```
ffffffff81a88060-ffffffff81a88159: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abf300)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81abf300-ffffffff81abf3f9: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb490)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff815fb490-ffffffff815fb589: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620000)
Location: lib/xarray.c:703
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81620000-ffffffff816200fa: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603760)
Location: lib/xarray.c:703
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81603760-ffffffff8160385a: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:703
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81ce0005-ffffffff81ce0038: xas_create_range.cold (STB_LOCAL)
ffffffff81671cd0-ffffffff81671de7: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:706
Inline: False
Direct callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81ea6743-ffffffff81ea6784: xas_create_range.cold (STB_LOCAL)
ffffffff8178bdc0-ffffffff8178bf0a: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:706
Inline: False
Direct callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff820b7f10-ffffffff820b7f51: xas_create_range.cold (STB_LOCAL)
ffffffff82049320-ffffffff8204946a: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:704
Inline: False
Direct callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff82139359-ffffffff8213939a: xas_create_range.cold (STB_LOCAL)
ffffffff820c7be0-ffffffff820c7d25: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:704
Inline: False
Direct callers:
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff8221b0fe-ffffffff8221b13f: xas_create_range.cold (STB_LOCAL)
ffffffff821a2560-ffffffff821a26a5: xas_create_range (STB_GLOBAL)
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
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9a520)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffff800010d9a520-ffff800010d9a660: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e97278)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
c0e97278-c0e97394: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee0b30)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
c000000000ee0b30-c000000000ee0ccc: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c1dc0)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
```
**Symbols:**

```
ffffffe0008c1dc0-ffffffe0008c1eb6: xas_create_range (STB_GLOBAL)
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
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5e150)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81a5e150-ffffffff81a5e249: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1b220)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81a1b220-ffffffff81a1b319: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81aca540)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81aca540-ffffffff81aca639: xas_create_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xas_create_range(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6b10)
Location: lib/xarray.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_add_to_page_cache
  - mm/swap_state.c:add_to_swap_cache
  - mm/khugepaged.c:collapse_file
```
**Symbols:**

```
ffffffff81ad6b10-ffffffff81ad6c09: xas_create_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
