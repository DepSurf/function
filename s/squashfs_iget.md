# Function: <code>squashfs_iget</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81323920)
Location: fs/squashfs/inode.c:85
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81323920-ffffffff813239ad: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813397b0)
Location: fs/squashfs/inode.c:85
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813397b0-ffffffff8133983d: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff8134e490)
Location: fs/squashfs/inode.c:85
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8134e490-ffffffff8134e51d: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81372b40)
Location: fs/squashfs/inode.c:85
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81372b40-ffffffff81372bcd: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813a1420)
Location: fs/squashfs/inode.c:85
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813a1420-ffffffff813a14ad: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813ba210)
Location: fs/squashfs/inode.c:85
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813ba210-ffffffff813ba29d: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813e4ac0)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813e4ac0-ffffffff813e4b54: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813feb10)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813feb10-ffffffff813feba4: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff8144c450)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8144c450-ffffffff8144c4e4: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81468b40)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81468b40-ffffffff81468bd4: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff8146e240)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8146e240-ffffffff8146e2d4: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff814c4ad0)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff814c4ad0-ffffffff814c4b61: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff8154f8b0)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8154f8b0-ffffffff8154f962: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff815f0350)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff815f0350-ffffffff815f0402: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81628390)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81628390-ffffffff81628442: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff81661510)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81661510-ffffffff816615c2: squashfs_iget (STB_GLOBAL)
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
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffff8000104dcbd8)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffff8000104dcbd8-ffff8000104dccb0: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (c069e620)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
c069e620-c069e6c8: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (c0000000006181c0)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
c0000000006181c0-c0000000006182d8: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffe0003516d8)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffe0003516d8-ffffffe0003517a2: squashfs_iget (STB_GLOBAL)
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
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813f70f0)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813f70f0-ffffffff813f7184: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813e7b70)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813e7b70-ffffffff813e7c04: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff813f4470)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff813f4470-ffffffff813f4504: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inode *squashfs_iget(struct super_block *sb, long long int ino, unsigned int ino_number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/inode.c (ffffffff8140a0a0)
Location: fs/squashfs/inode.c:72
Inline: False
Direct callers:
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8140a0a0-ffffffff8140a134: squashfs_iget (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
