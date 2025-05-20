# Function: <code>add_to_avail_list</code>

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
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226890)
Location: mm/swapfile.c:627
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81226890-ffffffff8122694c: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81249120)
Location: mm/swapfile.c:627
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81249120-ffffffff812491dc: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125d9e0)
Location: mm/swapfile.c:655
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8125d9e0-ffffffff8125daa2: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81278c70-ffffffff81278d41: add_to_avail_list (STB_LOCAL)
ffffffff8127dadf-ffffffff8127dafa: add_to_avail_list.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288760)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81288760-ffffffff81288822: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bacc0)
Location: mm/swapfile.c:684
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff812bacc0-ffffffff812bad82: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6740)
Location: mm/swapfile.c:697
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff812c6740-ffffffff812c6802: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd300)
Location: mm/swapfile.c:696
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff812cd300-ffffffff812cd3a9: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312690)
Location: mm/swapfile.c:704
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81312690-ffffffff81312739: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d210)
Location: mm/swapfile.c:706
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8137d210-ffffffff8137d2cb: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa690)
Location: mm/swapfile.c:710
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff813fa690-ffffffff813fa73b: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d5d0)
Location: mm/swapfile.c:712
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8142d5d0-ffffffff8142d67b: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467050)
Location: mm/swapfile.c:714
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81467050-ffffffff814670e5: add_to_avail_list (STB_LOCAL)
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
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff8000103236b8)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
```
**Symbols:**

```
ffff8000103236b8-ffff8000103237dc: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053b238)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
```
**Symbols:**

```
c053b238-c053b2bc: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8bc0)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:_enable_swap_info
  - mm/swapfile.c:swapcache_free_entries
```
**Symbols:**

```
c0000000003f8bc0-c0000000003f8d20: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000224216)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_free_entries
```
**Symbols:**

```
ffffffe000224216-ffffffe0002242ae: add_to_avail_list (STB_LOCAL)
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
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280d40)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81280d40-ffffffff81280e02: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272bb0)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81272bb0-ffffffff81272c72: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127eb50)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8127eb50-ffffffff8127ec12: add_to_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_to_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128e1c0)
Location: mm/swapfile.c:690
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8128e1c0-ffffffff8128e280: add_to_avail_list (STB_LOCAL)
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
