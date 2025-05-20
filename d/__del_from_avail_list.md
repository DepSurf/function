# Function: <code>__del_from_avail_list</code>

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
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226340)
Location: mm/swapfile.c:595
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:del_from_avail_list
```
**Symbols:**

```
ffffffff81226340-ffffffff812263cb: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248950)
Location: mm/swapfile.c:595
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81248950-ffffffff812489db: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125cf30)
Location: mm/swapfile.c:623
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8125cf30-ffffffff8125cfbe: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812780e0)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812780e0-ffffffff8127816e: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81287bd0)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81287bd0-ffffffff81287c5e: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812b9f90)
Location: mm/swapfile.c:652
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812b9f90-ffffffff812ba01e: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c5a00)
Location: mm/swapfile.c:665
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812c5a00-ffffffff812c5a8e: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ccbc0)
Location: mm/swapfile.c:664
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812ccbc0-ffffffff812ccc39: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81311eb0)
Location: mm/swapfile.c:672
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81311eb0-ffffffff81311f29: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d0f0)
Location: mm/swapfile.c:674
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8137d0f0-ffffffff8137d17d: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa3c0)
Location: mm/swapfile.c:678
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff813fa3c0-ffffffff813fa43d: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d2f0)
Location: mm/swapfile.c:679
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8142d2f0-ffffffff8142d379: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81466a60)
Location: mm/swapfile.c:681
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81466a60-ffffffff81466ae9: __del_from_avail_list (STB_LOCAL)
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
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010322998)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffff800010322998-ffff800010322a50: __del_from_avail_list (STB_LOCAL)
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
In mm/swapfile.c (c053d1bc)
Location: mm/swapfile.c:658
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:del_from_avail_list
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f83b0)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:del_from_avail_list
```
**Symbols:**

```
c0000000003f83b0-c0000000003f84a4: __del_from_avail_list (STB_LOCAL)
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
In mm/swapfile.c (ffffffe000225e2e)
Location: mm/swapfile.c:658
Inline: True
Inline callers:
  - mm/swapfile.c:get_swap_pages
  - mm/swapfile.c:del_from_avail_list
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
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812801b0)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812801b0-ffffffff8128023e: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272020)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81272020-ffffffff812720ae: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127dfc0)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8127dfc0-ffffffff8127e04e: __del_from_avail_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __del_from_avail_list(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128db70)
Location: mm/swapfile.c:658
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8128db70-ffffffff8128dbfe: __del_from_avail_list (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
