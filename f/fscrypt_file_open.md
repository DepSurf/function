# Function: <code>fscrypt_file_open</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812d0a80)
Location: fs/crypto/hooks.c:30
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_open
```
**Symbols:**

```
ffffffff812d0a80-ffffffff812d0b62: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff812fb728-ffffffff812fb755: fscrypt_file_open.cold.9 (STB_LOCAL)
ffffffff812fb690-ffffffff812fb728: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff81310b34-ffffffff81310b61: fscrypt_file_open.cold.9 (STB_LOCAL)
ffffffff81310aa0-ffffffff81310b34: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff81338080-ffffffff813380ad: fscrypt_file_open.cold (STB_LOCAL)
ffffffff81337fd0-ffffffff81338066: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff8134c0e7-ffffffff8134c10e: fscrypt_file_open.cold (STB_LOCAL)
ffffffff8134c050-ffffffff8134c0e7: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813917c0)
Location: fs/crypto/hooks.c:32
Inline: True
```
**Symbols:**

```
ffffffff81391b0e-ffffffff81391b35: fscrypt_file_open.cold (STB_LOCAL)
ffffffff813917a0-ffffffff81391839: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2d70)
Location: fs/crypto/hooks.c:32
Inline: True
```
**Symbols:**

```
ffffffff81beae12-ffffffff81beae39: fscrypt_file_open.cold (STB_LOCAL)
ffffffff813a2d50-ffffffff813a2deb: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9fb0)
Location: fs/crypto/hooks.c:32
Inline: True
```
**Symbols:**

```
ffffffff81bdce5f-ffffffff81bdce86: fscrypt_file_open.cold (STB_LOCAL)
ffffffff813a9f90-ffffffff813aa02b: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f9800)
Location: fs/crypto/hooks.c:32
Inline: True
```
**Symbols:**

```
ffffffff81cc642e-ffffffff81cc6455: fscrypt_file_open.cold (STB_LOCAL)
ffffffff813f97e0-ffffffff813f987b: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c6bf)
Location: fs/crypto/hooks.c:32
Inline: True
```
**Symbols:**

```
ffffffff81e7889c-ffffffff81e788c4: fscrypt_file_open.cold (STB_LOCAL)
ffffffff8146c6a0-ffffffff8146c744: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fda70)
Location: fs/crypto/hooks.c:30
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_file_open
```
**Symbols:**

```
ffffffff814fda70-ffffffff814fdb3d: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81535050)
Location: fs/crypto/hooks.c:30
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_file_open
```
**Symbols:**

```
ffffffff81535050-ffffffff81535123: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8156a010)
Location: fs/crypto/hooks.c:30
Inline: True
```
**Symbols:**

```
ffffffff8156a010-ffffffff8156a0e3: fscrypt_file_open (STB_GLOBAL)
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
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffff80001040ca38)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffff80001040ca38-ffff80001040cb08: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c05d9bbc)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
c05d9bbc-c05d9c8c: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c000000000519e80)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
c000000000519e80-c000000000519fac: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffe0002b632c)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffe0002b632c-ffffffe0002b63e8: fscrypt_file_open (STB_GLOBAL)
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
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff813446c7-ffffffff813446ee: fscrypt_file_open.cold (STB_LOCAL)
ffffffff81344630-ffffffff813446c7: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff813353a7-ffffffff813353ce: fscrypt_file_open.cold (STB_LOCAL)
ffffffff81335310-ffffffff813353a7: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff81342197-ffffffff813421be: fscrypt_file_open.cold (STB_LOCAL)
ffffffff81342100-ffffffff81342197: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_file_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:30
Inline: False
```
**Symbols:**

```
ffffffff81355497-ffffffff813554be: fscrypt_file_open.cold (STB_LOCAL)
ffffffff81355400-ffffffff81355497: fscrypt_file_open (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
