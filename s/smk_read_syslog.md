# Function: <code>smk_read_syslog</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813644b0)
Location: security/smack/smackfs.c:2656
Inline: True
```
**Symbols:**

```
ffffffff813644b0-ffffffff81364520: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8139a4f0)
Location: security/smack/smackfs.c:2615
Inline: True
```
**Symbols:**

```
ffffffff8139a4f0-ffffffff8139a560: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813b11e0)
Location: security/smack/smackfs.c:2610
Inline: True
```
**Symbols:**

```
ffffffff813b11e0-ffffffff813b1250: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813c7b10)
Location: security/smack/smackfs.c:2615
Inline: True
```
**Symbols:**

```
ffffffff813c7b10-ffffffff813c7b83: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813edfa0)
Location: security/smack/smackfs.c:2615
Inline: True
```
**Symbols:**

```
ffffffff813edfa0-ffffffff813ee013: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8141f080)
Location: security/smack/smackfs.c:2615
Inline: True
```
**Symbols:**

```
ffffffff8141f080-ffffffff8141f0f2: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8143b9f0)
Location: security/smack/smackfs.c:2615
Inline: True
```
**Symbols:**

```
ffffffff8143b9f0-ffffffff8143ba62: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814695d0)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffff814695d0-ffffffff81469644: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814833b0)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffff814833b0-ffffffff81483424: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff814d91c0)
Location: security/smack/smackfs.c:2608
Inline: True
```
**Symbols:**

```
ffffffff814d91c0-ffffffff814d922b: smk_read_syslog.part.0 (STB_LOCAL)
ffffffff814d9230-ffffffff814d9252: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/smack/smackfs.c (ffffffff814f6750)
Location: security/smack/smackfs.c:2623
Inline: True
```
**Symbols:**

```
ffffffff814f6750-ffffffff814f67bb: smk_read_syslog.part.0 (STB_LOCAL)
ffffffff814f67c0-ffffffff814f67e2: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814fd3c0)
Location: security/smack/smackfs.c:2625
Inline: True
```
**Symbols:**

```
ffffffff814fd3c0-ffffffff814fd434: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81558110)
Location: security/smack/smackfs.c:2626
Inline: True
```
**Symbols:**

```
ffffffff81558110-ffffffff81558184: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff815f2460)
Location: security/smack/smackfs.c:2625
Inline: True
```
**Symbols:**

```
ffffffff815f2460-ffffffff815f24f0: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816a2c80)
Location: security/smack/smackfs.c:2625
Inline: True
```
**Symbols:**

```
ffffffff816a2c80-ffffffff816a2d10: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816dbac0)
Location: security/smack/smackfs.c:2636
Inline: True
```
**Symbols:**

```
ffffffff816dbac0-ffffffff816dbb50: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81718240)
Location: security/smack/smackfs.c:2648
Inline: True
```
**Symbols:**

```
ffffffff81718240-ffffffff817182d0: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffff800010574f88)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffff800010574f88-ffff800010575018: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c07280bc)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
c07280bc-c072814c: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0000000006ddec0)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
c0000000006ddec0-c0000000006ddf88: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffe0003c8200)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffe0003c8200-ffffffe0003c8274: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8147b990)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffff8147b990-ffffffff8147ba04: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146c3b0)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffff8146c3b0-ffffffff8146c424: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81477a30)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffff81477a30-ffffffff81477aa4: smk_read_syslog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t smk_read_syslog(struct file *filp, char *buf, size_t cn, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8148f4e0)
Location: security/smack/smackfs.c:2589
Inline: True
```
**Symbols:**

```
ffffffff8148f4e0-ffffffff8148f554: smk_read_syslog (STB_LOCAL)
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
