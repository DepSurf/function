# Function: <code>fbcon_putcs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff81460340)
Location: drivers/video/console/fbcon.c:1275
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_putc
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
```
**Symbols:**

```
ffffffff81460340-ffffffff8146046c: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814ae230)
Location: drivers/video/console/fbcon.c:1274
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff814ae230-ffffffff814ae366: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814d0320)
Location: drivers/video/console/fbcon.c:1277
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff814d0320-ffffffff814d0456: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/console/fbcon.c (ffffffff814de7d0)
Location: drivers/video/console/fbcon.c:1275
Inline: False
Direct callers:
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_scrolldelta
  - drivers/video/console/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff814de7d0-ffffffff814de904: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81526b00)
Location: drivers/video/fbdev/core/fbcon.c:1291
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff81526b00-ffffffff81526c36: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8155c7b0)
Location: drivers/video/fbdev/core/fbcon.c:1298
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff8155c7b0-ffffffff8155c8cf: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815726f0)
Location: drivers/video/fbdev/core/fbcon.c:1317
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815726f0-ffffffff815727ed: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a2be0)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815a2be0-ffffffff815a2ce9: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815c3a60)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815c3a60-ffffffff815c3b69: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8166df20)
Location: drivers/video/fbdev/core/fbcon.c:1300
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff8166df20-ffffffff8166e026: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff8168e4d0)
Location: drivers/video/fbdev/core/fbcon.c:1296
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff8168e4d0-ffffffff8168e5d6: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816711d0)
Location: drivers/video/fbdev/core/fbcon.c:1288
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff816711d0-ffffffff816712d5: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff816e7990)
Location: drivers/video/fbdev/core/fbcon.c:1288
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff816e7990-ffffffff816e7b21: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff81812180)
Location: drivers/video/fbdev/core/fbcon.c:1279
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff81812180-ffffffff81812370: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819411e0)
Location: drivers/video/fbdev/core/fbcon.c:1274
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff819411e0-ffffffff819413d0: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819857d0)
Location: drivers/video/fbdev/core/fbcon.c:1273
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_redraw
  - drivers/video/fbdev/core/fbcon.c:fbcon_redraw
  - drivers/video/fbdev/core/fbcon.c:fbcon_redraw
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff819857d0-ffffffff819859c0: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cf6f0)
Location: drivers/video/fbdev/core/fbcon.c:1275
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_redraw
  - drivers/video/fbdev/core/fbcon.c:fbcon_redraw
  - drivers/video/fbdev/core/fbcon.c:fbcon_redraw
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff819cf6f0-ffffffff819cf8e0: fbcon_putcs (STB_LOCAL)
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
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffff80001074e698)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffff80001074e698-ffff80001074e7c4: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c08cf9a4)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
c08cf9a4-c08cfa98: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (c0000000008af240)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
c0000000008af240-c0000000008af3a8: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffe0004fa88c)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffe0004fa88c-ffffffe0004fa966: fbcon_putcs (STB_LOCAL)
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
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b7bb0)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815b7bb0-ffffffff815b7cb9: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815a6990)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815a6990-ffffffff815a6a99: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815b8140)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815b8140-ffffffff815b8249: fbcon_putcs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fbcon_putcs(struct vc_data *vc, const short unsigned int *s, int count, int ypos, int xpos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fbcon.c (ffffffff815d1ba0)
Location: drivers/video/fbdev/core/fbcon.c:1345
Inline: False
Direct callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_scrolldelta
  - drivers/video/fbdev/core/fbcon.c:fbcon_putc
```
**Symbols:**

```
ffffffff815d1ba0-ffffffff815d1ca9: fbcon_putcs (STB_LOCAL)
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
