# Function: <code>make_device_exclusive_range</code>

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
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int make_device_exclusive_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct page **pages, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2190
Inline: False
```
**Symbols:**

```
ffffffff81cbcdb7-ffffffff81cbcde6: make_device_exclusive_range.cold (STB_LOCAL)
ffffffff812f9960-ffffffff812f9b34: make_device_exclusive_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int make_device_exclusive_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct page **pages, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2316
Inline: False
```
**Symbols:**

```
ffffffff81e6e96d-ffffffff81e6e98e: make_device_exclusive_range.cold (STB_LOCAL)
ffffffff8135bf30-ffffffff8135c145: make_device_exclusive_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int make_device_exclusive_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct page **pages, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2330
Inline: False
```
**Symbols:**

```
ffffffff820648a6-ffffffff820648c7: make_device_exclusive_range.cold (STB_LOCAL)
ffffffff813d74a0-ffffffff813d76c7: make_device_exclusive_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int make_device_exclusive_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct page **pages, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2328
Inline: False
```
**Symbols:**

```
ffffffff820e3f61-ffffffff820e3f82: make_device_exclusive_range.cold (STB_LOCAL)
ffffffff8140b9b0-ffffffff8140bc15: make_device_exclusive_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int make_device_exclusive_range(struct mm_struct *mm, long unsigned int start, long unsigned int end, struct page **pages, void *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:2485
Inline: False
```
**Symbols:**

```
ffffffff821c0b8f-ffffffff821c0bb0: make_device_exclusive_range.cold (STB_LOCAL)
ffffffff81438270-ffffffff814384c9: make_device_exclusive_range (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
