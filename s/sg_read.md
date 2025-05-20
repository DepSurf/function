# Function: <code>sg_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff815c3750)
Location: drivers/scsi/sg.c:399
Inline: False
```
**Symbols:**

```
ffffffff815c3750-ffffffff815c3cbe: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161bf70)
Location: drivers/scsi/sg.c:399
Inline: False
```
**Symbols:**

```
ffffffff8161bf70-ffffffff8161c4f5: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164cbc0)
Location: drivers/scsi/sg.c:388
Inline: False
```
**Symbols:**

```
ffffffff8164cbc0-ffffffff8164d102: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81661bc0)
Location: drivers/scsi/sg.c:387
Inline: False
```
**Symbols:**

```
ffffffff81661bc0-ffffffff81662157: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816cab40)
Location: drivers/scsi/sg.c:387
Inline: False
```
**Symbols:**

```
ffffffff816cab40-ffffffff816cb0dd: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff817074f0)
Location: drivers/scsi/sg.c:414
Inline: True
```
**Symbols:**

```
ffffffff817074f0-ffffffff81707ae6: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8172a030)
Location: drivers/scsi/sg.c:414
Inline: True
```
**Symbols:**

```
ffffffff8172a030-ffffffff8172a62f: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81765710)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffff81765710-ffffffff81765ce2: sg_read.part.0 (STB_LOCAL)
ffffffff81765cf0-ffffffff81765d3f: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81789700)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffff81789700-ffffffff81789cd2: sg_read.part.0 (STB_LOCAL)
ffffffff81789ce0-ffffffff81789d2f: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81850060)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff81850060-ffffffff8185057d: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185ece0)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff8185ece0-ffffffff8185f25e: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81842cb0)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff81842cb0-ffffffff81843215: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818cfc50)
Location: drivers/scsi/sg.c:442
Inline: False
```
**Symbols:**

```
ffffffff818cfc50-ffffffff818d019d: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff81a1bff0-ffffffff81a1c4f8: sg_read (STB_LOCAL)
ffffffff81ed63b9-ffffffff81ed63e8: sg_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff81b9d250-ffffffff81b9d758: sg_read (STB_LOCAL)
ffffffff8209c472-ffffffff8209c4a1: sg_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff81bf3870-ffffffff81bf3d81: sg_read (STB_LOCAL)
ffffffff8211d3ab-ffffffff8211d3da: sg_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:441
Inline: False
```
**Symbols:**

```
ffffffff81c49190-ffffffff81c496d0: sg_read (STB_LOCAL)
ffffffff821fb3e3-ffffffff821fb412: sg_read.cold (STB_LOCAL)
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
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffff800010993230)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffff800010993230-ffff800010993ac0: sg_read.part.0 (STB_LOCAL)
ffff800010993ac0-ffff800010993b30: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (c0a62a4c)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
c0a62a4c-c0a63188: sg_read.part.0 (STB_LOCAL)
c0a63188-c0a631d0: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (c000000000a531a0)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
c000000000a531a0-c000000000a53b30: sg_read.part.0 (STB_LOCAL)
c000000000a53b30-c000000000a53bbc: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f468c)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffe0005f468c-ffffffe0005f4b56: sg_read.part.0 (STB_LOCAL)
ffffffe0005f4b56-ffffffe0005f4ba4: sg_read (STB_LOCAL)
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
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8173ddf0)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffff8173ddf0-ffffffff8173e3c2: sg_read.part.0 (STB_LOCAL)
ffffffff8173e3d0-ffffffff8173e41f: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8171fa90)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffff8171fa90-ffffffff81720062: sg_read.part.0 (STB_LOCAL)
ffffffff81720070-ffffffff817200bf: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8177e580)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffff8177e580-ffffffff8177eb52: sg_read.part.0 (STB_LOCAL)
ffffffff8177eb60-ffffffff8177ebaf: sg_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t sg_read(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81798390)
Location: drivers/scsi/sg.c:409
Inline: True
```
**Symbols:**

```
ffffffff81798390-ffffffff81798954: sg_read.part.0 (STB_LOCAL)
ffffffff81798960-ffffffff817989af: sg_read (STB_LOCAL)
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
