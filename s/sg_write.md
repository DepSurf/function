# Function: <code>sg_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff815c6a80)
Location: drivers/scsi/sg.c:583
Inline: False
```
**Symbols:**

```
ffffffff815c6a80-ffffffff815c6ecc: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161f290)
Location: drivers/scsi/sg.c:583
Inline: False
```
**Symbols:**

```
ffffffff8161f290-ffffffff8161f705: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164fde0)
Location: drivers/scsi/sg.c:572
Inline: False
```
**Symbols:**

```
ffffffff8164fde0-ffffffff81650273: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81664660)
Location: drivers/scsi/sg.c:573
Inline: False
```
**Symbols:**

```
ffffffff81664660-ffffffff81664aca: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816cdcb0)
Location: drivers/scsi/sg.c:573
Inline: False
```
**Symbols:**

```
ffffffff816cdcb0-ffffffff816ce11d: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8170aa10)
Location: drivers/scsi/sg.c:608
Inline: True
```
**Symbols:**

```
ffffffff8170a610-ffffffff8170aa0a: sg_write.part.27 (STB_LOCAL)
ffffffff8170ab0f-ffffffff8170ab43: sg_write.part.27.cold.33 (STB_LOCAL)
ffffffff8170aa10-ffffffff8170aa5c: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8172ce80)
Location: drivers/scsi/sg.c:608
Inline: True
```
**Symbols:**

```
ffffffff8172ca80-ffffffff8172ce7a: sg_write.part.27 (STB_LOCAL)
ffffffff8172cf7f-ffffffff8172cfb3: sg_write.part.27.cold.33 (STB_LOCAL)
ffffffff8172ce80-ffffffff8172cecc: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81768620)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff81768210-ffffffff8176861d: sg_write.part.0 (STB_LOCAL)
ffffffff81768773-ffffffff817687a6: sg_write.part.0.cold (STB_LOCAL)
ffffffff81768620-ffffffff8176866f: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8178c610)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff8178c200-ffffffff8178c60d: sg_write.part.0 (STB_LOCAL)
ffffffff8178c73d-ffffffff8178c770: sg_write.part.0.cold (STB_LOCAL)
ffffffff8178c610-ffffffff8178c65f: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81850010)
Location: drivers/scsi/sg.c:599
Inline: True
```
**Symbols:**

```
ffffffff8184fbf0-ffffffff81850001: sg_write.part.0 (STB_LOCAL)
ffffffff8185131f-ffffffff81851353: sg_write.part.0.cold (STB_LOCAL)
ffffffff81850010-ffffffff8185005f: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81860950)
Location: drivers/scsi/sg.c:599
Inline: True
```
**Symbols:**

```
ffffffff81860530-ffffffff81860941: sg_write.part.0 (STB_LOCAL)
ffffffff81c16efb-ffffffff81c16f2f: sg_write.part.0.cold (STB_LOCAL)
ffffffff81860950-ffffffff818609c8: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81843650)
Location: drivers/scsi/sg.c:599
Inline: True
```
**Symbols:**

```
ffffffff81843220-ffffffff8184364f: sg_write.part.0 (STB_LOCAL)
ffffffff81c08c43-ffffffff81c08c77: sg_write.part.0.cold (STB_LOCAL)
ffffffff81843650-ffffffff818436c8: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818cf6d0)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff818cf2a0-ffffffff818cf6c3: sg_write.part.0 (STB_LOCAL)
ffffffff81d0d48f-ffffffff81d0d4c3: sg_write.part.0.cold (STB_LOCAL)
ffffffff818cf6d0-ffffffff818cf731: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:599
Inline: False
```
**Symbols:**

```
ffffffff81a1cf40-ffffffff81a1d420: sg_write (STB_LOCAL)
ffffffff81ed63fd-ffffffff81ed6431: sg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9e210)
Location: drivers/scsi/sg.c:599
Inline: False
```
**Symbols:**

```
ffffffff81b9e210-ffffffff81b9e71f: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf4830)
Location: drivers/scsi/sg.c:599
Inline: False
```
**Symbols:**

```
ffffffff81bf4830-ffffffff81bf4d38: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c4a170)
Location: drivers/scsi/sg.c:599
Inline: False
```
**Symbols:**

```
ffffffff81c4a170-ffffffff81c4a678: sg_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffff8000109926c8)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffff8000109926c8-ffff800010992dc8: sg_write.part.0 (STB_LOCAL)
ffff800010992dc8-ffff800010992e38: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (c0a6552c)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
c0a6552c-c0a6598c: sg_write.part.0 (STB_LOCAL)
c0a6598c-c0a659d4: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (c000000000a56f70)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
c000000000a56f70-c000000000a57588: sg_write.part.0 (STB_LOCAL)
c000000000a57590-c000000000a5761c: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f66ca)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffe0005f66ca-ffffffe0005f69e8: sg_write.part.0 (STB_LOCAL)
ffffffe0005f69e8-ffffffe0005f6a36: sg_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81740d00)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff817408f0-ffffffff81740cfd: sg_write.part.0 (STB_LOCAL)
ffffffff81740e2d-ffffffff81740e60: sg_write.part.0.cold (STB_LOCAL)
ffffffff81740d00-ffffffff81740d4f: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81722990)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff81722580-ffffffff8172298d: sg_write.part.0 (STB_LOCAL)
ffffffff81722abd-ffffffff81722af0: sg_write.part.0.cold (STB_LOCAL)
ffffffff81722990-ffffffff817229df: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81781490)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff81781080-ffffffff8178148d: sg_write.part.0 (STB_LOCAL)
ffffffff817815bd-ffffffff817815f0: sg_write.part.0.cold (STB_LOCAL)
ffffffff81781490-ffffffff817814df: sg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_write(struct file *filp, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8179b260)
Location: drivers/scsi/sg.c:603
Inline: True
```
**Symbols:**

```
ffffffff8179ae50-ffffffff8179b25d: sg_write.part.0 (STB_LOCAL)
ffffffff8179b3a3-ffffffff8179b3d6: sg_write.part.0.cold (STB_LOCAL)
ffffffff8179b260-ffffffff8179b2af: sg_write (STB_LOCAL)
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
