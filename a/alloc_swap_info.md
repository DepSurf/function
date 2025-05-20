# Function: <code>alloc_swap_info</code>

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
In mm/swapfile.c (ffffffff811d621b)
Location: mm/swapfile.c:2140
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
In mm/swapfile.c (ffffffff811f42eb)
Location: mm/swapfile.c:2127
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
In mm/swapfile.c (ffffffff81204e1b)
Location: mm/swapfile.c:2146
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
In mm/swapfile.c (ffffffff812104ca)
Location: mm/swapfile.c:2595
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
In mm/swapfile.c (ffffffff81227923)
Location: mm/swapfile.c:2834
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
In mm/swapfile.c (ffffffff8124d183)
Location: mm/swapfile.c:2834
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
In mm/swapfile.c (ffffffff81261586)
Location: mm/swapfile.c:2811
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
In mm/swapfile.c (ffffffff8127c4f6)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (ffffffff8128bfd6)
Location: mm/swapfile.c:2824
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
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bb590)
Location: mm/swapfile.c:2861
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812bb590-ffffffff812bb758: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c7030)
Location: mm/swapfile.c:2878
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812c7030-ffffffff812c71f9: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cd970)
Location: mm/swapfile.c:2849
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff812cd970-ffffffff812cdb20: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81312d10)
Location: mm/swapfile.c:2835
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81312d10-ffffffff81312f9a: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137d940)
Location: mm/swapfile.c:2704
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8137d940-ffffffff8137dc30: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fac00)
Location: mm/swapfile.c:2706
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff813fac00-ffffffff813faed6: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142dc50)
Location: mm/swapfile.c:2697
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff8142dc50-ffffffff8142df26: alloc_swap_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct swap_info_struct *alloc_swap_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81467710)
Location: mm/swapfile.c:2702
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
```
**Symbols:**

```
ffffffff81467710-ffffffff814679e6: alloc_swap_info (STB_LOCAL)
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
In mm/swapfile.c (ffff8000103276f4)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (c053eb50)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (c0000000003fe3b0)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (ffffffe0002275e4)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (ffffffff812845b6)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (ffffffff81276426)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (ffffffff812823c6)
Location: mm/swapfile.c:2824
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
In mm/swapfile.c (ffffffff812920b6)
Location: mm/swapfile.c:2824
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
