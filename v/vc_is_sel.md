# Function: <code>vc_is_sel</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81695040)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81695040-ffffffff81695055: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81747af0)
Location: drivers/tty/vt/selection.c:90
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81747af0-ffffffff81747b05: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81763440)
Location: drivers/tty/vt/selection.c:90
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81763440-ffffffff81763455: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff817470e0)
Location: drivers/tty/vt/selection.c:90
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff817470e0-ffffffff817470f5: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff817c8150)
Location: drivers/tty/vt/selection.c:90
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff817c8150-ffffffff817c8165: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81905300)
Location: drivers/tty/vt/selection.c:90
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81905300-ffffffff8190531b: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81a5f470)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81a5f470-ffffffff81a5f48b: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81aa9b30)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81aa9b30-ffffffff81aa9b4b: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81afc5f0)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:con_font_op
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81afc5f0-ffffffff81afc60b: vc_is_sel (STB_GLOBAL)
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
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffff800010869560)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffff800010869560-ffff800010869594: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (c096e6a8)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
c096e6a8-c096e6d8: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (c0000000009091f0)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
c0000000009091f0-c000000000909218: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffe00053e1e2)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffe00053e1e2-ffffffe00053e212: vc_is_sel (STB_GLOBAL)
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
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff8165aac0)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff8165aac0-ffffffff8165aad5: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff8163ae40)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff8163ae40-ffffffff8163ae55: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81688e80)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff81688e80-ffffffff81688e95: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool vc_is_sel(struct vc_data *vc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff816a3470)
Location: drivers/tty/vt/selection.c:91
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_disallocate_all
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:hide_cursor
```
**Symbols:**

```
ffffffff816a3470-ffffffff816a3485: vc_is_sel (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
