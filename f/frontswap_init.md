# Function: <code>frontswap_init</code>

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
Location: include/linux/frontswap.h:101
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
Location: include/linux/frontswap.h:107
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
In mm/swapfile.c (ffffffff81205a85)
Location: include/linux/frontswap.h:107
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
In mm/swapfile.c (ffffffff81211384)
Location: include/linux/frontswap.h:107
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
In mm/swapfile.c (ffffffff81228920)
Location: include/linux/frontswap.h:108
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
Location: include/linux/frontswap.h:108
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
Location: include/linux/frontswap.h:108
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb025)
Location: include/linux/frontswap.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:enable_swap_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c6adb)
Location: include/linux/frontswap.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:enable_swap_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd67b)
Location: include/linux/frontswap.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:enable_swap_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312a0d)
Location: include/linux/frontswap.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:enable_swap_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff81383f10)
Location: mm/frontswap.c:110
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81383f10-ffffffff81383f57: frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff814019d0)
Location: mm/frontswap.c:110
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff814019d0-ffffffff81401a24: frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void frontswap_init(unsigned int type, long unsigned int *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/frontswap.c (ffffffff814348b0)
Location: mm/frontswap.c:110
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff814348b0-ffffffff81434904: frontswap_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/swapfile.c (ffff8000103238c0)
Location: include/linux/frontswap.h:115
Inline: True
Inline callers:
  - mm/swapfile.c:enable_swap_info
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
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
Location: include/linux/frontswap.h:115
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
