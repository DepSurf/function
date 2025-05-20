# Function: <code>_enable_swap_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d30a0)
Location: mm/swapfile.c:1791
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapoff
  - mm/swapfile.c:SyS_swapon
```
**Symbols:**

```
ffffffff811d30a0-ffffffff811d313e: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f0f40)
Location: mm/swapfile.c:1778
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
**Symbols:**

```
ffffffff811f0f40-ffffffff811f0fde: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812018b0)
Location: mm/swapfile.c:1797
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
**Symbols:**

```
ffffffff812018b0-ffffffff8120194e: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120cb30)
Location: mm/swapfile.c:2229
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapon
  - mm/swapfile.c:SyS_swapoff
```
**Symbols:**

```
ffffffff8120cb30-ffffffff8120cbc9: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81226950)
Location: mm/swapfile.c:2454
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapon
  - mm/swapfile.c:SYSC_swapoff
```
**Symbols:**

```
ffffffff81226950-ffffffff81226ab4: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812491e0)
Location: mm/swapfile.c:2454
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff812491e0-ffffffff81249344: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125dab0)
Location: mm/swapfile.c:2431
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8125dab0-ffffffff8125dc11: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81278d50)
Location: mm/swapfile.c:2451
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81278d50-ffffffff81278da2: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81288830)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81288830-ffffffff81288882: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bad90)
Location: mm/swapfile.c:2480
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812bad90-ffffffff812bade4: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6810)
Location: mm/swapfile.c:2496
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812c6810-ffffffff812c6864: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd3b0)
Location: mm/swapfile.c:2467
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff812cd3b0-ffffffff812cd404: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312740)
Location: mm/swapfile.c:2454
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffffffff81312740-ffffffff81312792: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d2d0)
Location: mm/swapfile.c:2322
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8137d2d0-ffffffff8137d32b: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fa750)
Location: mm/swapfile.c:2324
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff813fa750-ffffffff813fa7ab: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142d690)
Location: mm/swapfile.c:2315
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8142d690-ffffffff8142d6eb: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467210)
Location: mm/swapfile.c:2323
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81467210-ffffffff81467282: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff8000103237e0)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
  - mm/swapfile.c:enable_swap_info
```
**Symbols:**

```
ffff8000103237e0-ffff80001032388c: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053b7a0)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
c053b7a0-c053b82c: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003f8d20)
Location: mm/swapfile.c:2450
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
c0000000003f8d20-c0000000003f8dc4: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe0002242ae)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffe0002242ae-ffffffe000224324: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81280e10)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81280e10-ffffffff81280e62: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81272c80)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81272c80-ffffffff81272cd2: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127ec20)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8127ec20-ffffffff8127ec72: _enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void _enable_swap_info(struct swap_info_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128e7c0)
Location: mm/swapfile.c:2450
Inline: True
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8128e7c0-ffffffff8128e812: _enable_swap_info (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int prio</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char *swap_map</code>
</li>
<li>
<b>Param removed. </b>
<code>struct swap_cluster_info *cluster_info</code>
</li>
</ul>
</details>
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
