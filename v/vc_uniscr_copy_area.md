# Function: <code>vc_uniscr_copy_area</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816462ae)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8167a8d2)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8169d0c5)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8174f86f)
Location: drivers/tty/vt/vt.c:475
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8176b9af)
Location: drivers/tty/vt/vt.c:468
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8174e8b3)
Location: drivers/tty/vt/vt.c:468
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff817d06f1)
Location: drivers/tty/vt/vt.c:464
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8190e585)
Location: drivers/tty/vt/vt.c:464
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vc_uniscr_copy_area(struct uni_screen *dst, unsigned int dst_cols, unsigned int dst_rows, struct uni_screen *src, unsigned int src_cols, unsigned int src_top_row, unsigned int src_bot_row);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a66b80)
Location: drivers/tty/vt/vt.c:464
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81a66b80-ffffffff81a66c8e: vc_uniscr_copy_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vc_uniscr_copy_area(u32 **dst_lines, unsigned int dst_cols, unsigned int dst_rows, u32 **src_lines, unsigned int src_cols, unsigned int src_top_row, unsigned int src_bot_row);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab1390)
Location: drivers/tty/vt/vt.c:446
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81ab1390-ffffffff81ab14a4: vc_uniscr_copy_area (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vc_uniscr_copy_area(u32 **dst_lines, unsigned int dst_cols, unsigned int dst_rows, u32 **src_lines, unsigned int src_cols, unsigned int src_top_row, unsigned int src_bot_row);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b03ff0)
Location: drivers/tty/vt/vt.c:445
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81b03ff0-ffffffff81b04104: vc_uniscr_copy_area (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff8000108748b8)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (c09776c4)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (c000000000915cbc)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffe0005461b8)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff81662b25)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff81642ea5)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff81690f05)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff816ab4f5)
Location: drivers/tty/vt/vt.c:469
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 **dst_lines</code>
</li>
<li>
<b>Param added. </b>
<code>u32 **src_lines</code>
</li>
<li>
<b>Param removed. </b>
<code>struct uni_screen *dst</code>
</li>
<li>
<b>Param removed. </b>
<code>struct uni_screen *src</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
