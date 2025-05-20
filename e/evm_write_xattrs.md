# Function: <code>evm_write_xattrs</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814578a0)
Location: security/integrity/evm/evm_secfs.c:177
Inline: False
```
**Symbols:**

```
ffffffff814578a0-ffffffff81457bc4: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff81474da0)
Location: security/integrity/evm/evm_secfs.c:177
Inline: False
```
**Symbols:**

```
ffffffff81474da0-ffffffff814750b8: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814a2ac0)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffff814a2ac0-ffffffff814a2dc4: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814bd790)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffff814bd790-ffffffff814bda94: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8151e080)
Location: security/integrity/evm/evm_secfs.c:172
Inline: False
```
**Symbols:**

```
ffffffff8151e080-ffffffff8151e385: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff8153ae50)
Location: security/integrity/evm/evm_secfs.c:172
Inline: False
```
**Symbols:**

```
ffffffff8153ae50-ffffffff8153b155: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff81543520)
Location: security/integrity/evm/evm_secfs.c:173
Inline: False
```
**Symbols:**

```
ffffffff81543520-ffffffff8154382a: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (0)
Location: security/integrity/evm/evm_secfs.c:180
Inline: False
```
**Symbols:**

```
ffffffff815a3c50-ffffffff815a3fa1: evm_write_xattrs (STB_LOCAL)
ffffffff81cd7596-ffffffff81cd75b7: evm_write_xattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (0)
Location: security/integrity/evm/evm_secfs.c:180
Inline: False
```
**Symbols:**

```
ffffffff8164a650-ffffffff8164a9b7: evm_write_xattrs (STB_LOCAL)
ffffffff81e8a878-ffffffff81e8a899: evm_write_xattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (0)
Location: security/integrity/evm/evm_secfs.c:180
Inline: False
```
**Symbols:**

```
ffffffff817037a0-ffffffff81703b07: evm_write_xattrs (STB_LOCAL)
ffffffff8207568d-ffffffff820756ae: evm_write_xattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (0)
Location: security/integrity/evm/evm_secfs.c:180
Inline: False
```
**Symbols:**

```
ffffffff8173d7d0-ffffffff8173db2d: evm_write_xattrs (STB_LOCAL)
ffffffff820f51ef-ffffffff820f5210: evm_write_xattrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_secfs.c (0)
Location: security/integrity/evm/evm_secfs.c:180
Inline: False
```
**Symbols:**

```
ffffffff8177e600-ffffffff8177e98c: evm_write_xattrs (STB_LOCAL)
ffffffff821d23c3-ffffffff821d23e4: evm_write_xattrs.cold (STB_LOCAL)
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
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffff8000105b6680)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffff8000105b6680-ffff8000105b6958: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (c076564c)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
c076564c-c0765910: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (c00000000073a730)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
c00000000073a730-c00000000073adac: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffe0003fd2e0)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffe0003fd2e0-ffffffe0003fd560: evm_write_xattrs (STB_LOCAL)
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
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814b5d70)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffff814b5d70-ffffffff814b6074: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814a6790)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffff814a6790-ffffffff814a6a94: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814b1e00)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffff814b1e00-ffffffff814b2104: evm_write_xattrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t evm_write_xattrs(struct file *file, const char *buf, size_t count, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_secfs.c (ffffffff814ca880)
Location: security/integrity/evm/evm_secfs.c:174
Inline: False
```
**Symbols:**

```
ffffffff814ca880-ffffffff814cab84: evm_write_xattrs (STB_LOCAL)
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
