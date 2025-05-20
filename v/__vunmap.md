# Function: <code>__vunmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cecf0)
Location: mm/vmalloc.c:1452
Inline: False
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff811cecf0-ffffffff811cedcf: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ebe90)
Location: mm/vmalloc.c:1476
Inline: False
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff811ebe90-ffffffff811ebf53: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fd0d0)
Location: mm/vmalloc.c:1461
Inline: False
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff811fd0d0-ffffffff811fd193: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207dd0)
Location: mm/vmalloc.c:1513
Inline: True
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81207dd0-ffffffff81207e80: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220ec0)
Location: mm/vmalloc.c:1511
Inline: True
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81220ec0-ffffffff81220f70: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242d60)
Location: mm/vmalloc.c:1497
Inline: False
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81242d60-ffffffff81242e1c: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257440)
Location: mm/vmalloc.c:1499
Inline: False
Direct callers:
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81257440-ffffffff812574fc: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81269530)
Location: mm/vmalloc.c:2223
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81269530-ffffffff8126973d: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81278470)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81278470-ffffffff81278673: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812abd50)
Location: mm/vmalloc.c:2274
Inline: False
Direct callers:
  - mm/vmalloc.c:__vmalloc_area_node
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff812abd50-ffffffff812abfcd: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b7270)
Location: mm/vmalloc.c:2256
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff812b7270-ffffffff812b74ed: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bcb40)
Location: mm/vmalloc.c:2537
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff812bcb40-ffffffff812bcdbd: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ff2d0)
Location: mm/vmalloc.c:2589
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff812ff2d0-ffffffff812ff526: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2629
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81366300-ffffffff81366641: __vunmap (STB_LOCAL)
ffffffff81e6ed83-ffffffff81e6ede8: __vunmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2691
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff813e1f10-ffffffff813e2251: __vunmap (STB_LOCAL)
ffffffff82064c68-ffffffff82064ccd: __vunmap.cold (STB_LOCAL)
```
</details>
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
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030ed10)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffff80001030ed10-ffff80001030ef90: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052a5bc)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
c052a5bc-c052a7dc: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003dfd30)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:vunmap
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
c0000000003dfd30-c0000000003dff70: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000217614)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffe000217614-ffffffe000217770: __vunmap (STB_LOCAL)
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
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81270ac0)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81270ac0-ffffffff81270cc3: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81262a30)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff81262a30-ffffffff81262c33: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126e860)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff8126e860-ffffffff8126ea63: __vunmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __vunmap(const void *addr, int deallocate_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127e240)
Location: mm/vmalloc.c:2229
Inline: False
Direct callers:
  - mm/vmalloc.c:__vfree
  - mm/vmalloc.c:free_work
```
**Symbols:**

```
ffffffff8127e240-ffffffff8127e467: __vunmap (STB_LOCAL)
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
