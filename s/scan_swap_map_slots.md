# Function: <code>scan_swap_map_slots</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e7f0)
Location: mm/swapfile.c:637
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8120e7f0-ffffffff8120ee1c: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81229f40)
Location: mm/swapfile.c:669
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81229f40-ffffffff8122a5e7: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124b1d0)
Location: mm/swapfile.c:669
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8124b1d0-ffffffff8124b884: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125f9d0)
Location: mm/swapfile.c:697
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8125f9d0-ffffffff8125ff1d: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127a690)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8127a690-ffffffff8127ab92: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128a170)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8128a170-ffffffff8128a672: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bcde0)
Location: mm/swapfile.c:754
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812bcde0-ffffffff812bd441: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c8900)
Location: mm/swapfile.c:770
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812c8900-ffffffff812c8f63: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cf340)
Location: mm/swapfile.c:769
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff812cf340-ffffffff812cf9e4: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813148e0)
Location: mm/swapfile.c:777
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff813148e0-ffffffff81314fb4: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137fe90)
Location: mm/swapfile.c:795
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8137fe90-ffffffff81380527: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fe7e0)
Location: mm/swapfile.c:798
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff813fe7e0-ffffffff813fee0d: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81431730)
Location: mm/swapfile.c:800
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81431730-ffffffff81431d44: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146ab20)
Location: mm/swapfile.c:800
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff8146ab20-ffffffff8146b134: scan_swap_map_slots (STB_LOCAL)
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
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010325040)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffff800010325040-ffff80001032581c: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053ca94)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
c053ca94-c053d0c8: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fb2e0)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
c0000000003fb2e0-c0000000003fbae8: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000225676)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffe000225676-ffffffe000225d52: scan_swap_map_slots (STB_LOCAL)
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
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81282750)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81282750-ffffffff81282c52: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81274270)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81274270-ffffffff81274772: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280560)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81280560-ffffffff81280a62: scan_swap_map_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scan_swap_map_slots(struct swap_info_struct *si, unsigned char usage, int nr, swp_entry_t *slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81290280)
Location: mm/swapfile.c:732
Inline: False
Direct callers:
  - mm/swapfile.c:get_swap_page_of_type
  - mm/swapfile.c:get_swap_pages
```
**Symbols:**

```
ffffffff81290280-ffffffff8129078f: scan_swap_map_slots (STB_LOCAL)
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
