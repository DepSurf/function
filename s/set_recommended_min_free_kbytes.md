# Function: <code>set_recommended_min_free_kbytes</code>

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
In mm/huge_memory.c (ffffffff811f40ae)
Location: mm/huge_memory.c:110
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
In mm/khugepaged.c (ffffffff8121cd1c)
Location: mm/khugepaged.c:1858
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff8122f31c)
Location: mm/khugepaged.c:1866
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff8123ab7c)
Location: mm/khugepaged.c:1867
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff8125a40c)
Location: mm/khugepaged.c:1873
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff8127e130)
Location: mm/khugepaged.c:1873
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff81292810)
Location: mm/khugepaged.c:1862
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff812ad1e0)
Location: mm/khugepaged.c:1868
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff812bed30)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2249
Inline: False
Direct callers:
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff812ef9f0-ffffffff812efab1: set_recommended_min_free_kbytes (STB_LOCAL)
ffffffff812f412d-ffffffff812f4149: set_recommended_min_free_kbytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2286
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff812fb1e0-ffffffff812fb2a1: set_recommended_min_free_kbytes (STB_LOCAL)
ffffffff81be9b5d-ffffffff81be9b79: set_recommended_min_free_kbytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2274
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81301fb0-ffffffff81302071: set_recommended_min_free_kbytes (STB_LOCAL)
ffffffff81bdbb79-ffffffff81bdbb95: set_recommended_min_free_kbytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2296
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff8134bba0-ffffffff8134bc61: set_recommended_min_free_kbytes (STB_LOCAL)
ffffffff81cc263e-ffffffff81cc265a: set_recommended_min_free_kbytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2309
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff813c34a0-ffffffff813c358b: set_recommended_min_free_kbytes (STB_LOCAL)
ffffffff81e74c0c-ffffffff81e74c28: set_recommended_min_free_kbytes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81445c20)
Location: mm/khugepaged.c:2509
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff81445c20-ffffffff81445d1e: set_recommended_min_free_kbytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8147b300)
Location: mm/khugepaged.c:2698
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff8147b300-ffffffff8147b3fe: set_recommended_min_free_kbytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_recommended_min_free_kbytes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814ab430)
Location: mm/khugepaged.c:2577
Inline: False
Direct callers:
  - mm/khugepaged.c:khugepaged_min_free_kbytes_update
  - mm/khugepaged.c:start_stop_khugepaged
```
**Symbols:**

```
ffffffff814ab430-ffffffff814ab545: set_recommended_min_free_kbytes (STB_LOCAL)
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
In mm/khugepaged.c (ffff800010360388)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (c00000000044b88c)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b7310)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff812a84e0)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff812b5120)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
In mm/khugepaged.c (ffffffff812c5660)
Location: mm/khugepaged.c:2123
Inline: True
Inline callers:
  - mm/khugepaged.c:start_stop_khugepaged
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
