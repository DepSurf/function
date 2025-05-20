# Function: <code>hpet_ioctl_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81519890)
Location: drivers/char/hpet.c:577
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81519890-ffffffff81519cc9: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8156c590)
Location: drivers/char/hpet.c:577
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff8156c590-ffffffff8156c9c9: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81598d00)
Location: drivers/char/hpet.c:577
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81598d00-ffffffff81599139: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff815aca90)
Location: drivers/char/hpet.c:578
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff815aca90-ffffffff815acedd: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81613460)
Location: drivers/char/hpet.c:578
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81613460-ffffffff816138ad: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (0)
Location: drivers/char/hpet.c:578
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff8164d480-ffffffff8164d8c4: hpet_ioctl_common (STB_LOCAL)
ffffffff8164dc55-ffffffff8164dc69: hpet_ioctl_common.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff8166b5b7)
Location: drivers/char/hpet.c:578
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff8166b3a0-ffffffff8166b7e4: hpet_ioctl_common (STB_LOCAL)
ffffffff8166bdd5-ffffffff8166bde9: hpet_ioctl_common.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff816a114a)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff816a0f50-ffffffff816a1361: hpet_ioctl_common (STB_LOCAL)
ffffffff816a1979-ffffffff816a198d: hpet_ioctl_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff816c3eea)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff816c3cf0-ffffffff816c4101: hpet_ioctl_common (STB_LOCAL)
ffffffff816c46d9-ffffffff816c46ed: hpet_ioctl_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff81777fb0)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81777fb0-ffffffff8177815f: hpet_ioctl_common.part.0 (STB_LOCAL)
ffffffff817789d0-ffffffff81778a29: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff81792a80)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81792a80-ffffffff81792c2f: hpet_ioctl_common.part.0 (STB_LOCAL)
ffffffff817934b0-ffffffff81793509: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff817757a0)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff817757a0-ffffffff8177594f: hpet_ioctl_common.part.0 (STB_LOCAL)
ffffffff817761b0-ffffffff81776209: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff817fb500)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff817fb500-ffffffff817fb6af: hpet_ioctl_common.part.0 (STB_LOCAL)
ffffffff817fbf40-ffffffff817fbf99: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff8193a500)
Location: drivers/char/hpet.c:559
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff8193a500-ffffffff8193a6f3: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81a9a940)
Location: drivers/char/hpet.c:559
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81a9a940-ffffffff81a9ab33: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81ae61e0)
Location: drivers/char/hpet.c:559
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81ae61e0-ffffffff81ae63cf: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/hpet.c (ffffffff81b39570)
Location: drivers/char/hpet.c:540
Inline: False
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81b39570-ffffffff81b3975f: hpet_ioctl_common (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff8168993a)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff81689740-ffffffff81689b51: hpet_ioctl_common (STB_LOCAL)
ffffffff8168a129-ffffffff8168a13d: hpet_ioctl_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff8166739b)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff816671c0-ffffffff81667596: hpet_ioctl_common (STB_LOCAL)
ffffffff81667b49-ffffffff81667b5d: hpet_ioctl_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff816b7baa)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff816b79b0-ffffffff816b7dc1: hpet_ioctl_common (STB_LOCAL)
ffffffff816b8399-ffffffff816b83ad: hpet_ioctl_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_ioctl_common(struct hpet_dev *devp, unsigned int cmd, long unsigned int arg, struct hpet_info *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/hpet.c (ffffffff816d23fd)
Location: drivers/char/hpet.c:574
Inline: True
Direct callers:
  - drivers/char/hpet.c:hpet_compat_ioctl
  - drivers/char/hpet.c:hpet_ioctl
```
**Symbols:**

```
ffffffff816d2210-ffffffff816d2603: hpet_ioctl_common (STB_LOCAL)
ffffffff816d2969-ffffffff816d297d: hpet_ioctl_common.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int cmd</code> ➡️ <code>unsigned int cmd</code>
</li>
</ul>
</details>
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
