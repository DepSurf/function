# Function: <code>configfs_release_bin_file</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff812de580)
Location: fs/configfs/file.c:482
Inline: False
```
**Symbols:**

```
ffffffff812de580-ffffffff812de61c: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81302ec0)
Location: fs/configfs/file.c:482
Inline: False
```
**Symbols:**

```
ffffffff81302ec0-ffffffff81302f62: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81330e10)
Location: fs/configfs/file.c:482
Inline: False
```
**Symbols:**

```
ffffffff81330e10-ffffffff81330eb2: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81348200)
Location: fs/configfs/file.c:482
Inline: False
```
**Symbols:**

```
ffffffff81348200-ffffffff813482a2: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813706d0)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff813706d0-ffffffff81370776: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81388bb0)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff81388bb0-ffffffff81388c56: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813d3f20)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff813d3f20-ffffffff813d3ff1: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813e5c60)
Location: fs/configfs/file.c:467
Inline: False
```
**Symbols:**

```
ffffffff813e5c60-ffffffff813e5d31: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff813ec870)
Location: fs/configfs/file.c:465
Inline: False
```
**Symbols:**

```
ffffffff813ec870-ffffffff813ec932: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:401
Inline: False
```
**Symbols:**

```
ffffffff8143e7a0-ffffffff8143e866: configfs_release_bin_file (STB_LOCAL)
ffffffff81cc879e-ffffffff81cc87c8: configfs_release_bin_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:401
Inline: False
```
**Symbols:**

```
ffffffff814ba0d0-ffffffff814ba19e: configfs_release_bin_file (STB_LOCAL)
ffffffff81e7b4e9-ffffffff81e7b513: configfs_release_bin_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:401
Inline: False
```
**Symbols:**

```
ffffffff815518f0-ffffffff815519be: configfs_release_bin_file (STB_LOCAL)
ffffffff8206bd13-ffffffff8206bd3d: configfs_release_bin_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:401
Inline: False
```
**Symbols:**

```
ffffffff81589610-ffffffff815896e1: configfs_release_bin_file (STB_LOCAL)
ffffffff820ebba1-ffffffff820ebbcb: configfs_release_bin_file.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:401
Inline: False
```
**Symbols:**

```
ffffffff815c2220-ffffffff815c22f4: configfs_release_bin_file (STB_LOCAL)
ffffffff821c8e05-ffffffff821c8e2f: configfs_release_bin_file.cold (STB_LOCAL)
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
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffff800010458f98)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffff800010458f98-ffff80001045906c: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (c061b058)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
c061b058-c061b108: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (c000000000573f40)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
c000000000573f40-c000000000574074: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffe0002ea1c0)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffe0002ea1c0-ffffffe0002ea268: configfs_release_bin_file (STB_LOCAL)
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
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81381190)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff81381190-ffffffff81381236: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81371c20)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff81371c20-ffffffff81371cc6: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff8137ec60)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff8137ec60-ffffffff8137ed06: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int configfs_release_bin_file(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/file.c (ffffffff81392760)
Location: fs/configfs/file.c:469
Inline: False
```
**Symbols:**

```
ffffffff81392760-ffffffff81392806: configfs_release_bin_file (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct file *file</code>
</li>
<li>
<b>Param removed. </b>
<code>struct file *filp</code>
</li>
</ul>
</details>
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
