# Function: <code>read_swap_header</code>

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
In mm/swapfile.c (ffffffff811d6439)
Location: mm/swapfile.c:2215
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
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
In mm/swapfile.c (ffffffff811f4503)
Location: mm/swapfile.c:2202
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
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
In mm/swapfile.c (ffffffff81205033)
Location: mm/swapfile.c:2221
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
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
In mm/swapfile.c (ffffffff812106f3)
Location: mm/swapfile.c:2670
Inline: True
Inline callers:
  - mm/swapfile.c:SyS_swapon
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
In mm/swapfile.c (ffffffff81227bb4)
Location: mm/swapfile.c:2912
Inline: True
Inline callers:
  - mm/swapfile.c:SYSC_swapon
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
In mm/swapfile.c (ffffffff8124d6af)
Location: mm/swapfile.c:2941
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffff81261ad3)
Location: mm/swapfile.c:2919
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffff8127c788)
Location: mm/swapfile.c:2931
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffff8128c269)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2971
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812bee80-ffffffff812bf007: read_swap_header (STB_LOCAL)
ffffffff812c0093-ffffffff812c00f7: read_swap_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2990
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812caaa0-ffffffff812cac27: read_swap_header (STB_LOCAL)
ffffffff81be87b5-ffffffff81be8819: read_swap_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2961
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812d1580-ffffffff812d1707: read_swap_header (STB_LOCAL)
ffffffff81bda7ac-ffffffff81bda810: read_swap_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2956
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81316c80-ffffffff81316e0a: read_swap_header (STB_LOCAL)
ffffffff81cbec45-ffffffff81cbeca9: read_swap_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (0)
Location: mm/swapfile.c:2825
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff813822a0-ffffffff8138242f: read_swap_header (STB_LOCAL)
ffffffff81e70dfb-ffffffff81e70e61: read_swap_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813faef0)
Location: mm/swapfile.c:2827
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff813faef0-ffffffff813fb0be: read_swap_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142df40)
Location: mm/swapfile.c:2818
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8142df40-ffffffff8142e135: read_swap_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int read_swap_header(struct swap_info_struct *p, union swap_header *swap_header, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467a00)
Location: mm/swapfile.c:2824
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81467a00-ffffffff81467bf5: read_swap_header (STB_LOCAL)
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
In mm/swapfile.c (ffff80001032794c)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (c053ed18)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (c0000000003fe6d0)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffe0002277a8)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
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
In mm/swapfile.c (ffffffff81284849)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffff812766b9)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffff81282659)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
In mm/swapfile.c (ffffffff81292342)
Location: mm/swapfile.c:2927
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
