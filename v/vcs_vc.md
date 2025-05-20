# Function: <code>vcs_vc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff814f0350)
Location: drivers/tty/vt/vc_screen.c:140
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_size
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
```
**Symbols:**

```
ffffffff814f0350-ffffffff814f03c5: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81540f60)
Location: drivers/tty/vt/vc_screen.c:140
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81540f60-ffffffff81540fd5: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff8156d5a0)
Location: drivers/tty/vt/vc_screen.c:140
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff8156d5a0-ffffffff8156d615: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81581b20)
Location: drivers/tty/vt/vc_screen.c:140
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81581b20-ffffffff81581b86: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff815e6640)
Location: drivers/tty/vt/vc_screen.c:141
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff815e6640-ffffffff815e66a6: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff8161f8e0)
Location: drivers/tty/vt/vc_screen.c:141
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff8161f8e0-ffffffff8161f93e: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff8163cb80)
Location: drivers/tty/vt/vc_screen.c:167
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff8163cb80-ffffffff8163cbea: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (0)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81671040-ffffffff816710ac: vcs_vc (STB_LOCAL)
ffffffff81672051-ffffffff81672064: vcs_vc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81693720)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81693720-ffffffff8169378a: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81746360)
Location: drivers/tty/vt/vc_screen.c:185
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81746360-ffffffff817463c9: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81762000)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff81762000-ffffffff81762063: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81745cc0)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff81745cc0-ffffffff81745d23: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff817c6c50)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff817c6c50-ffffffff817c6ccb: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81903c50)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff81903c50-ffffffff81903cd3: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81a5dd10)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff81a5dd10-ffffffff81a5dd93: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81aa8340)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff81aa8340-ffffffff81aa83c3: vcs_vc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81afae00)
Location: drivers/tty/vt/vc_screen.c:183
Inline: True
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_lseek
```
**Symbols:**

```
ffffffff81afae00-ffffffff81afae83: vcs_vc.isra.0 (STB_LOCAL)
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
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffff800010867780)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffff800010867780-ffff800010867830: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (c096cb94)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
c096cb94-c096cc44: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (c000000000906f60)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
c000000000906f60-c00000000090707c: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffe00053ca98)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffe00053ca98-ffffffe00053cb22: vcs_vc (STB_LOCAL)
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
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff816591a0)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff816591a0-ffffffff8165920a: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81639520)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81639520-ffffffff8163958a: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff81687560)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff81687560-ffffffff816875ca: vcs_vc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vc_data *vcs_vc(struct inode *inode, int *viewed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vc_screen.c (ffffffff816a1b50)
Location: drivers/tty/vt/vc_screen.c:185
Inline: False
Direct callers:
  - drivers/tty/vt/vc_screen.c:vcs_write
  - drivers/tty/vt/vc_screen.c:vcs_read
  - drivers/tty/vt/vc_screen.c:vcs_size
```
**Symbols:**

```
ffffffff816a1b50-ffffffff816a1bba: vcs_vc (STB_LOCAL)
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
