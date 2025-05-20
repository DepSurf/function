# Function: <code>evm_read_xattrs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff81457c70)
Location: security/integrity/evm/evm_secfs.c:131
Inline: True
```
**Symbols:**

```
ffffffff81457c70-ffffffff81457dfc: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff81475160)
Location: security/integrity/evm/evm_secfs.c:131
Inline: True
```
**Symbols:**

```
ffffffff81475160-ffffffff814752eb: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814a2e80)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff814a2e80-ffffffff814a3006: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814bdb50)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff814bdb50-ffffffff814bdcd6: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8151e440)
Location: security/integrity/evm/evm_secfs.c:126
Inline: True
```
**Symbols:**

```
ffffffff8151e440-ffffffff8151e553: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff8151e560-ffffffff8151e5b0: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8153b210)
Location: security/integrity/evm/evm_secfs.c:126
Inline: True
```
**Symbols:**

```
ffffffff8153b210-ffffffff8153b323: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff8153b330-ffffffff8153b380: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff815438e0)
Location: security/integrity/evm/evm_secfs.c:127
Inline: True
```
**Symbols:**

```
ffffffff815438e0-ffffffff815439f3: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff81543a00-ffffffff81543a50: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff815a41a0)
Location: security/integrity/evm/evm_secfs.c:127
Inline: True
```
**Symbols:**

```
ffffffff815a4060-ffffffff815a4199: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff81cd75cf-ffffffff81cd75ff: evm_read_xattrs.part.0.cold (STB_LOCAL)
ffffffff815a41a0-ffffffff815a41f0: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8164ab10)
Location: security/integrity/evm/evm_secfs.c:127
Inline: True
```
**Symbols:**

```
ffffffff8164a9c0-ffffffff8164ab08: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff81e8a899-ffffffff81e8a8c9: evm_read_xattrs.part.0.cold (STB_LOCAL)
ffffffff8164ab10-ffffffff8164ab76: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff81703c80)
Location: security/integrity/evm/evm_secfs.c:127
Inline: True
```
**Symbols:**

```
ffffffff81703b20-ffffffff81703c68: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff820756ae-ffffffff820756de: evm_read_xattrs.part.0.cold (STB_LOCAL)
ffffffff81703c80-ffffffff81703ce6: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8173dce0)
Location: security/integrity/evm/evm_secfs.c:127
Inline: True
```
**Symbols:**

```
ffffffff8173db40-ffffffff8173dcc7: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff820f5210-ffffffff820f523f: evm_read_xattrs.part.0.cold (STB_LOCAL)
ffffffff8173dce0-ffffffff8173dd46: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8177eb40)
Location: security/integrity/evm/evm_secfs.c:127
Inline: True
```
**Symbols:**

```
ffffffff8177e9a0-ffffffff8177eb27: evm_read_xattrs.part.0 (STB_LOCAL)
ffffffff821d23e4-ffffffff821d2413: evm_read_xattrs.part.0.cold (STB_LOCAL)
ffffffff8177eb40-ffffffff8177eba6: evm_read_xattrs (STB_LOCAL)
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
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffff8000105b6a30)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffff8000105b6a30-ffff8000105b6ba4: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (c07659e8)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
c07659e8-c0765b18: evm_read_xattrs.part.0 (STB_LOCAL)
c0765b18-c0765b80: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (c00000000073aee0)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
c00000000073aee0-c00000000073b0ec: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd5d2)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffe0003fd5d2-ffffffe0003fd700: evm_read_xattrs (STB_LOCAL)
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
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814b6130)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff814b6130-ffffffff814b62b6: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814a6b50)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff814a6b50-ffffffff814a6cd6: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814b21c0)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff814b21c0-ffffffff814b2346: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t evm_read_xattrs(struct file *filp, char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814cac40)
Location: security/integrity/evm/evm_secfs.c:128
Inline: True
```
**Symbols:**

```
ffffffff814cac40-ffffffff814cadc6: evm_read_xattrs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
