# Function: <code>ext4_fname_prepare_lookup</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac940)
Location: fs/ext4/ext4.h:2348
Inline: False
```
**Symbols:**

```
ffffffff813ac940-ffffffff813aca70: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c5880)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffffffff813c5880-ffffffff813c59b0: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411cd0)
Location: fs/ext4/ext4.h:2504
Inline: False
```
**Symbols:**

```
ffffffff81411cd0-ffffffff81411dea: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81425170)
Location: fs/ext4/ext4.h:2636
Inline: False
```
**Symbols:**

```
ffffffff81425170-ffffffff8142528a: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142be80)
Location: fs/ext4/ext4.h:2688
Inline: False
```
**Symbols:**

```
ffffffff8142be80-ffffffff8142bf9b: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147fd20)
Location: fs/ext4/ext4.h:2758
Inline: False
```
**Symbols:**

```
ffffffff8147fd20-ffffffff8147fe3b: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8153cb20)
Location: fs/ext4/crypto.c:40
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8153cb20-ffffffff8153cc03: ext4_fname_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff815db2c0)
Location: fs/ext4/crypto.c:40
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff815db2c0-ffffffff815db3a3: ext4_fname_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff81612d70)
Location: fs/ext4/crypto.c:40
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff81612d70-ffffffff81612e53: ext4_fname_prepare_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8164bb30)
Location: fs/ext4/crypto.c:42
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8164bb30-ffffffff8164bc55: ext4_fname_prepare_lookup (STB_GLOBAL)
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
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d3a0)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffff80001049d3a0-ffff80001049d474: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065ff3c)
Location: fs/ext4/ext4.h:2406
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8810)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
c0000000005c8810-c0000000005c8980: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe000320190)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffffffe000320190-ffffffe000320248: ext4_fname_prepare_lookup (STB_LOCAL)
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
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bde60)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffffffff813bde60-ffffffff813bdf90: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ae8f0)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffffffff813ae8f0-ffffffff813aea20: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b9750)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffffffff813b9750-ffffffff813b9832: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_fname_prepare_lookup(struct inode *dir, struct dentry *dentry, struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d03f0)
Location: fs/ext4/ext4.h:2406
Inline: False
```
**Symbols:**

```
ffffffff813d03f0-ffffffff813d0520: ext4_fname_prepare_lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
