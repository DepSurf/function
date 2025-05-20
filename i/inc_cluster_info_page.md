# Function: <code>inc_cluster_info_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d2e10)
Location: mm/swapfile.c:351
Inline: False
Direct callers:
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff811d2e10-ffffffff811d2e90: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f0c60)
Location: mm/swapfile.c:348
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:scan_swap_map
```
**Symbols:**

```
ffffffff811f0c60-ffffffff811f0ce3: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81201b80)
Location: mm/swapfile.c:366
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:scan_swap_map
```
**Symbols:**

```
ffffffff81201b80-ffffffff81201c0d: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d5b0)
Location: mm/swapfile.c:460
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8120d5b0-ffffffff8120d5f2: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812270a0)
Location: mm/swapfile.c:472
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812270a0-ffffffff812270e2: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81248da0)
Location: mm/swapfile.c:472
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81248da0-ffffffff81248de1: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125d440)
Location: mm/swapfile.c:500
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8125d440-ffffffff8125d481: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278700)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81278700-ffffffff81278741: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812881f0)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812881f0-ffffffff81288231: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ba620)
Location: mm/swapfile.c:534
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812ba620-ffffffff812ba698: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6190)
Location: mm/swapfile.c:547
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812c6190-ffffffff812c6208: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ccb40)
Location: mm/swapfile.c:546
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812ccb40-ffffffff812ccbbd: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312040)
Location: mm/swapfile.c:554
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81312040-ffffffff813120bd: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d530)
Location: mm/swapfile.c:556
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8137d530-ffffffff8137d5d4: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fb300)
Location: mm/swapfile.c:560
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff813fb300-ffffffff813fb3a4: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142e260)
Location: mm/swapfile.c:561
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8142e260-ffffffff8142e304: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467d20)
Location: mm/swapfile.c:563
Inline: False
Direct callers:
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:setup_swap_map_and_extents
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81467d20-ffffffff81467dc4: inc_cluster_info_page (STB_LOCAL)
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
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010323060)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffff800010323060-ffff800010323110: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053bbb0)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
c053bbb0-c053bc40: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f9310)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
c0000000003f9310-c0000000003f93c0: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000223b56)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffe000223b56-ffffffe000223bf0: inc_cluster_info_page (STB_LOCAL)
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
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812807d0)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812807d0-ffffffff81280811: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272640)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81272640-ffffffff81272681: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127e5e0)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8127e5e0-ffffffff8127e621: inc_cluster_info_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inc_cluster_info_page(struct swap_info_struct *p, struct swap_cluster_info *cluster_info, long unsigned int page_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128ecf0)
Location: mm/swapfile.c:535
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8128ecf0-ffffffff8128ed31: inc_cluster_info_page (STB_LOCAL)
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
