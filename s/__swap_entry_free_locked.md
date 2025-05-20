# Function: <code>__swap_entry_free_locked</code>

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
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125e150)
Location: mm/swapfile.c:1140
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8125e150-ffffffff8125e1e6: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81279280)
Location: mm/swapfile.c:1177
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81279280-ffffffff8127931d: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288d60)
Location: mm/swapfile.c:1177
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81288d60-ffffffff81288dfd: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb9f0)
Location: mm/swapfile.c:1213
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff812bb9f0-ffffffff812bba8d: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c7490)
Location: mm/swapfile.c:1228
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff812c7490-ffffffff812c7538: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cddd0)
Location: mm/swapfile.c:1227
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff812cddd0-ffffffff812cde78: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81313250)
Location: mm/swapfile.c:1196
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff81313250-ffffffff813132f8: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137e5d0)
Location: mm/swapfile.c:1178
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff8137e5d0-ffffffff8137e68b: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fc1f0)
Location: mm/swapfile.c:1182
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff813fc1f0-ffffffff813fc2ab: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142f300)
Location: mm/swapfile.c:1182
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff8142f300-ffffffff8142f3bb: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81466f80)
Location: mm/swapfile.c:1182
Inline: False
Direct callers:
  - mm/swapfile.c:swapcache_clear
  - mm/swapfile.c:put_swap_folio
  - mm/swapfile.c:__swap_entry_free
```
**Symbols:**

```
ffffffff81466f80-ffffffff8146703b: __swap_entry_free_locked (STB_LOCAL)
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
In mm/swapfile.c (ffff8000103242a0)
Location: mm/swapfile.c:1177
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (c053c004)
Location: mm/swapfile.c:1177
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fa128)
Location: mm/swapfile.c:1177
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
In mm/swapfile.c (ffffffe000224a00)
Location: mm/swapfile.c:1177
Inline: True
Inline callers:
  - mm/swapfile.c:put_swap_page
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
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281340)
Location: mm/swapfile.c:1177
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff81281340-ffffffff812813dd: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812731b0)
Location: mm/swapfile.c:1177
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff812731b0-ffffffff8127324d: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127f150)
Location: mm/swapfile.c:1177
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8127f150-ffffffff8127f1ed: __swap_entry_free_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned char __swap_entry_free_locked(struct swap_info_struct *p, long unsigned int offset, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128e120)
Location: mm/swapfile.c:1177
Inline: False
Direct callers:
  - mm/swapfile.c:put_swap_page
```
**Symbols:**

```
ffffffff8128e120-ffffffff8128e1bd: __swap_entry_free_locked (STB_LOCAL)
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
