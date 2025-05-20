# Function: <code>pmap_unschedule</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d7ad)
Location: drivers/usb/dwc2/hcd_queue.c:337
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb87d)
Location: drivers/usb/dwc2/hcd_queue.c:337
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf530)
Location: drivers/usb/dwc2/hcd_queue.c:336
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff816cf530-ffffffff816cf5a1: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173bb80)
Location: drivers/usb/dwc2/hcd_queue.c:337
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff8173bb80-ffffffff8173bbf1: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c3f0)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff8177c3f0-ffffffff8177c461: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2950)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff817a2950-ffffffff817a29c1: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1a50)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff817e1a50-ffffffff817e1ac3: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812920)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff81812920-ffffffff81812993: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e3970)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff818e3970-ffffffff818e39e0: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ece50)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff818ece50-ffffffff818ecec0: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d0650)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff818d0650-ffffffff818d06c0: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196aed0)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff8196aed0-ffffffff8196af40: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac5220)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff81ac5220-ffffffff81ac52a5: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c4f2a0)
Location: drivers/usb/dwc2/hcd_queue.c:310
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff81c4f2a0-ffffffff81c4f325: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb6840)
Location: drivers/usb/dwc2/hcd_queue.c:310
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff81cb6840-ffffffff81cb68c5: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6b590)
Location: drivers/usb/dwc2/hcd_queue.c:310
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
```
**Symbols:**

```
ffffffff81d6b590-ffffffff81d6b615: pmap_unschedule (STB_LOCAL)
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
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4b930)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffff800010a4b930-ffff800010a4b9bc: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1dbe8)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
  - drivers/usb/dwc2/hcd_queue.c:dwc2_ls_pmap_unschedule
```
**Symbols:**

```
c0b1dbe8-c0b1dc5c: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12770)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
c000000000b12770-c000000000b12844: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe00066889a)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffe00066889a-ffffffe00066890c: pmap_unschedule (STB_LOCAL)
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
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cad00)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff817cad00-ffffffff817cad73: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818077a0)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff818077a0-ffffffff81807813: pmap_unschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int *map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818218b0)
Location: drivers/usb/dwc2/hcd_queue.c:340
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule
```
**Symbols:**

```
ffffffff818218b0-ffffffff81821923: pmap_unschedule (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
