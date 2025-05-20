# Function: <code>tty_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e30b0)
Location: drivers/tty/tty_io.c:1764
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814e30b0-ffffffff814e362e: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815330d0)
Location: drivers/tty/tty_io.c:1766
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff815330d0-ffffffff81533797: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155f800)
Location: drivers/tty/tty_io.c:1766
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8155f800-ffffffff8155fec7: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81573100)
Location: drivers/tty/tty_io.c:1565
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81573100-ffffffff815736f5: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8b80)
Location: drivers/tty/tty_io.c:1617
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff815d8b80-ffffffff815d9178: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1635
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8161325e-ffffffff81613350: tty_release.cold.39 (STB_LOCAL)
ffffffff816112c0-ffffffff81611867: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1647
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81630312-ffffffff81630404: tty_release.cold.38 (STB_LOCAL)
ffffffff8162e030-ffffffff8162e5d7: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8166423a-ffffffff81664338: tty_release.cold (STB_LOCAL)
ffffffff81661c00-ffffffff816621b5: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81686881-ffffffff8168697f: tty_release.cold (STB_LOCAL)
ffffffff81684270-ffffffff81684825: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81738697-ffffffff81738795: tty_release.cold (STB_LOCAL)
ffffffff81736ac0-ffffffff81736ecf: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1733
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81c0755f-ffffffff81c0765d: tty_release.cold (STB_LOCAL)
ffffffff81752360-ffffffff8175276f: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1748
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81bf921f-ffffffff81bf931d: tty_release.cold (STB_LOCAL)
ffffffff817364b0-ffffffff817368bc: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1741
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81cf89bc-ffffffff81cf8aba: tty_release.cold (STB_LOCAL)
ffffffff817b6e70-ffffffff817b727c: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1728
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81ec08db-ffffffff81ec09c1: tty_release.cold (STB_LOCAL)
ffffffff818f31d0-ffffffff818f35a7: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4b960)
Location: drivers/tty/tty_io.c:1723
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81a4b960-ffffffff81a4bdcf: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a95b60)
Location: drivers/tty/tty_io.c:1732
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81a95b60-ffffffff81a95fe8: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae85c0)
Location: drivers/tty/tty_io.c:1730
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81ae85c0-ffffffff81ae8a48: tty_release (STB_GLOBAL)
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
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff8000108516f8)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffff8000108516f8-ffff800010851d58: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095c244)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
c095c244-c095c880: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008eeee0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
c0000000008eeee0-c0000000008ef6c8: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052ed3a)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffe00052ed3a-ffffffe00052f2b0: tty_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8164c301-ffffffff8164c3ff: tty_release.cold (STB_LOCAL)
ffffffff81649cf0-ffffffff8164a2a5: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8162c751-ffffffff8162c84f: tty_release.cold (STB_LOCAL)
ffffffff8162a140-ffffffff8162a6f5: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff8167a6c1-ffffffff8167a7bf: tty_release.cold (STB_LOCAL)
ffffffff816780b0-ffffffff81678665: tty_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tty_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:1649
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff81694d29-ffffffff81694e27: tty_release.cold (STB_LOCAL)
ffffffff81693260-ffffffff8169381d: tty_release (STB_GLOBAL)
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
