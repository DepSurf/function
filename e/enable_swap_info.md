# Function: <code>enable_swap_info</code>

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
In mm/swapfile.c (ffffffff811d6dd3)
Location: mm/swapfile.c:1828
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
In mm/swapfile.c (ffffffff811f4f35)
Location: mm/swapfile.c:1815
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
In mm/swapfile.c (ffffffff81205a80)
Location: mm/swapfile.c:1834
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
In mm/swapfile.c (ffffffff8121137f)
Location: mm/swapfile.c:2266
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
In mm/swapfile.c (ffffffff81228918)
Location: mm/swapfile.c:2500
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
In mm/swapfile.c (ffffffff8124e195)
Location: mm/swapfile.c:2500
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
In mm/swapfile.c (ffffffff8126255b)
Location: mm/swapfile.c:2477
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
In mm/swapfile.c (ffffffff8127d417)
Location: mm/swapfile.c:2472
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
In mm/swapfile.c (ffffffff8128ceb4)
Location: mm/swapfile.c:2471
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info, long unsigned int *frontswap_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb020)
Location: mm/swapfile.c:2501
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812bb020-ffffffff812bb0cd: enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info, long unsigned int *frontswap_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6ac0)
Location: mm/swapfile.c:2517
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812c6ac0-ffffffff812c6b6d: enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info, long unsigned int *frontswap_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd660)
Location: mm/swapfile.c:2488
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812cd660-ffffffff812cd70d: enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info, long unsigned int *frontswap_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813129f0)
Location: mm/swapfile.c:2475
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff813129f0-ffffffff81312aa1: enable_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81382f54)
Location: mm/swapfile.c:2343
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fce23)
Location: mm/swapfile.c:2345
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81430125)
Location: mm/swapfile.c:2336
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81469bce)
Location: mm/swapfile.c:2347
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
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
void enable_swap_info(struct swap_info_struct *p, int prio, unsigned char *swap_map, struct swap_cluster_info *cluster_info, long unsigned int *frontswap_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010323890)
Location: mm/swapfile.c:2471
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffff800010323890-ffff800010323a60: enable_swap_info (STB_LOCAL)
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
In mm/swapfile.c (c053f9cc)
Location: mm/swapfile.c:2471
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
In mm/swapfile.c (c0000000003ff660)
Location: mm/swapfile.c:2471
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
In mm/swapfile.c (ffffffe0002281fa)
Location: mm/swapfile.c:2471
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
In mm/swapfile.c (ffffffff81285494)
Location: mm/swapfile.c:2471
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
In mm/swapfile.c (ffffffff81277304)
Location: mm/swapfile.c:2471
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
In mm/swapfile.c (ffffffff812832a4)
Location: mm/swapfile.c:2471
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
In mm/swapfile.c (ffffffff81292f88)
Location: mm/swapfile.c:2471
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
</ul>
<b>Arch</b>
<ul>
</ul>
