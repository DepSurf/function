# Function: <code>fbcon_scrolldelta</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff81461e20)
Location: drivers/video/console/fbcon.c:2768
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_cursor
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81461e20-ffffffff81462425: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814afdd0)
Location: drivers/video/console/fbcon.c:2767
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff814afdd0-ffffffff814b0415: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d1ee0)
Location: drivers/video/console/fbcon.c:2778
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_switch
  - drivers/video/console/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff814d1ee0-ffffffff814d2525: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814df4f0)
Location: drivers/video/console/fbcon.c:2776
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_do_set_font
  - drivers/video/console/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff814df4f0-ffffffff814dfb16: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81527830)
Location: drivers/video/fbdev/core/fbcon.c:2792
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81527830-ffffffff81527e60: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155e1a0)
Location: drivers/video/fbdev/core/fbcon.c:2800
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff8155e1a0-ffffffff8155e7c6: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81574ce0)
Location: drivers/video/fbdev/core/fbcon.c:2819
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
```
**Symbols:**

```
ffffffff81574ce0-ffffffff815752ca: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a5140)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff815a5140-ffffffff815a5766: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c6010)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff815c6010-ffffffff815c6636: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff80001074f770)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffff80001074f770-ffff80001074fcfc: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08d1d80)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
c08d1d80-c08d2348: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008b1190)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
c0000000008b1190-c0000000008b18cc: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fbcf0)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffe0004fbcf0-ffffffe0004fc1f0: fbcon_scrolldelta (STB_LOCAL)
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
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba110)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff815ba110-ffffffff815ba736: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a8ef0)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff815a8ef0-ffffffff815a9516: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815ba6a0)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff815ba6a0-ffffffff815bacc6: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_scrolldelta(struct vc_data *vc, int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d4150)
Location: drivers/video/fbdev/core/fbcon.c:2836
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_do_set_font
  - drivers/video/fbdev/core/fbcon.c:fbcon_switch
  - drivers/video/fbdev/core/fbcon.c:fbcon_cursor
```
**Symbols:**

```
ffffffff815d4150-ffffffff815d4776: fbcon_scrolldelta (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
