# Function: <code>fb_check_caps</code>

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
In drivers/video/fbdev/core/fbmem.c (ffffffff8146c52f)
Location: drivers/video/fbdev/core/fbmem.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814ba87f)
Location: drivers/video/fbdev/core/fbmem.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814dc87f)
Location: drivers/video/fbdev/core/fbmem.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff814e83b1)
Location: drivers/video/fbdev/core/fbmem.c:921
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8151ce94)
Location: drivers/video/fbdev/core/fbmem.c:923
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81552bbe)
Location: drivers/video/fbdev/core/fbmem.c:911
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8156a43e)
Location: drivers/video/fbdev/core/fbmem.c:940
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159ab5b)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815bbf3b)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fb_check_caps(struct fb_info *info, struct fb_var_screeninfo *var, u32 activate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff81665d90)
Location: drivers/video/fbdev/core/fbmem.c:937
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff81665d90-ffffffff81665e49: fb_check_caps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fb_check_caps(struct fb_info *info, struct fb_var_screeninfo *var, u32 activate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbmem.c (ffffffff816869f0)
Location: drivers/video/fbdev/core/fbmem.c:937
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
```
**Symbols:**

```
ffffffff816869f0-ffffffff81686aa9: fb_check_caps (STB_LOCAL)
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816698b8)
Location: drivers/video/fbdev/core/fbmem.c:937
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff816dcd79)
Location: drivers/video/fbdev/core/fbmem.c:937
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81806c55)
Location: drivers/video/fbdev/core/fbmem.c:935
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81935785)
Location: drivers/video/fbdev/core/fbmem.c:937
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff81979a75)
Location: drivers/video/fbdev/core/fbmem.c:831
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff819c3c15)
Location: drivers/video/fbdev/core/fbmem.c:203
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffff800010742d30)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (c08c75c4)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (c0000000008a3a2c)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffe0004f3a3a)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b008b)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff8159f21b)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815b061b)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
In drivers/video/fbdev/core/fbmem.c (ffffffff815ca08b)
Location: drivers/video/fbdev/core/fbmem.c:932
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:fb_set_var
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
</ul>
