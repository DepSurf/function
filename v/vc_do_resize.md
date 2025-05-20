# Function: <code>vc_do_resize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f89e0)
Location: drivers/tty/vt/vt.c:856
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_resize
  - drivers/tty/vt/vt.c:vt_resize
```
**Symbols:**

```
ffffffff814f89e0-ffffffff814f8f06: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81549070)
Location: drivers/tty/vt/vt.c:855
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81549070-ffffffff81549589: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81575ad0)
Location: drivers/tty/vt/vt.c:844
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81575ad0-ffffffff81575fbe: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81589970)
Location: drivers/tty/vt/vt.c:852
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81589970-ffffffff81589e4a: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ef110)
Location: drivers/tty/vt/vt.c:854
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff815ef110-ffffffff815ef59d: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81628850)
Location: drivers/tty/vt/vt.c:854
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81628850-ffffffff81628cbe: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81646090)
Location: drivers/tty/vt/vt.c:1158
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81646090-ffffffff816466be: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:1166
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff8167a6c0-ffffffff8167acc3: vc_do_resize (STB_LOCAL)
ffffffff8167f230-ffffffff8167f243: vc_do_resize.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169ceb0)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff8169ceb0-ffffffff8169d4b8: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174f5c0)
Location: drivers/tty/vt/vt.c:1202
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff8174f5c0-ffffffff8174fbfa: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176b700)
Location: drivers/tty/vt/vt.c:1207
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff8176b700-ffffffff8176bce2: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e630)
Location: drivers/tty/vt/vt.c:1206
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff8174e630-ffffffff8174ebf6: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d0450)
Location: drivers/tty/vt/vt.c:1195
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff817d0450-ffffffff817d0a9c: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190e360)
Location: drivers/tty/vt/vt.c:1195
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff8190e360-ffffffff8190e999: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a69380)
Location: drivers/tty/vt/vt.c:1195
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81a69380-ffffffff81a69878: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab3a60)
Location: drivers/tty/vt/vt.c:1145
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81ab3a60-ffffffff81ab3f5a: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b06740)
Location: drivers/tty/vt/vt.c:1144
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81b06740-ffffffff81b06c3a: vc_do_resize (STB_LOCAL)
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
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff8000108746f8)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffff8000108746f8-ffff800010874c50: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c09774dc)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
c09774dc-c0977a90: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000915aa0)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
c000000000915aa0-c000000000916160: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe00054602c)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffe00054602c-ffffffe000546538: vc_do_resize (STB_LOCAL)
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
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81662910)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81662910-ffffffff81662f18: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81642c90)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81642c90-ffffffff81643298: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81690cf0)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff81690cf0-ffffffff816912f8: vc_do_resize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vc_do_resize(struct tty_struct *tty, struct vc_data *vc, unsigned int cols, unsigned int lines);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816ab2e0)
Location: drivers/tty/vt/vt.c:1190
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vt_resize
  - drivers/tty/vt/vt.c:vc_resize
```
**Symbols:**

```
ffffffff816ab2e0-ffffffff816ab8e8: vc_do_resize (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
