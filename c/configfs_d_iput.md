# Function: <code>configfs_d_iput</code>

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
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e01e0)
Location: fs/configfs/dir.c:53
Inline: False
```
**Symbols:**

```
ffffffff812e01e0-ffffffff812e026a: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81304b60)
Location: fs/configfs/dir.c:53
Inline: False
```
**Symbols:**

```
ffffffff81304b60-ffffffff81304bea: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81331e40)
Location: fs/configfs/dir.c:53
Inline: False
```
**Symbols:**

```
ffffffff81331e40-ffffffff81331ebd: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81349450)
Location: fs/configfs/dir.c:53
Inline: False
```
**Symbols:**

```
ffffffff81349450-ffffffff813494cd: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/dir.c (0)
Location: fs/configfs/dir.c:40
Inline: False
```
**Symbols:**

```
ffffffff813726b0-ffffffff81372748: configfs_d_iput (STB_LOCAL)
ffffffff81373624-ffffffff81373637: configfs_d_iput.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138ac80)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff8138ac80-ffffffff8138ad18: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d4ee0)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff813d4ee0-ffffffff813d4f82: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e6c00)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff813e6c00-ffffffff813e6ca2: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ed590)
Location: fs/configfs/dir.c:37
Inline: False
```
**Symbols:**

```
ffffffff813ed590-ffffffff813ed632: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8143fb00)
Location: fs/configfs/dir.c:45
Inline: False
```
**Symbols:**

```
ffffffff8143fb00-ffffffff8143fba2: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bc070)
Location: fs/configfs/dir.c:45
Inline: False
```
**Symbols:**

```
ffffffff814bc070-ffffffff814bc110: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81552f40)
Location: fs/configfs/dir.c:45
Inline: False
```
**Symbols:**

```
ffffffff81552f40-ffffffff81552fe0: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158acc0)
Location: fs/configfs/dir.c:45
Inline: False
```
**Symbols:**

```
ffffffff8158acc0-ffffffff8158ad60: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c39b0)
Location: fs/configfs/dir.c:45
Inline: False
```
**Symbols:**

```
ffffffff815c39b0-ffffffff815c3a53: configfs_d_iput (STB_LOCAL)
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
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045aec0)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffff80001045aec0-ffff80001045afd8: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061cea0)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
c061cea0-c061cf90: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000577020)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
c000000000577020-c000000000577180: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002eb2e2)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffe0002eb2e2-ffffffe0002eb3d2: configfs_d_iput (STB_LOCAL)
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
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81383260)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff81383260-ffffffff813832f8: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81373cf0)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff81373cf0-ffffffff81373d88: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81380d30)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff81380d30-ffffffff81380dc8: configfs_d_iput (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void configfs_d_iput(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813947f0)
Location: fs/configfs/dir.c:39
Inline: False
```
**Symbols:**

```
ffffffff813947f0-ffffffff81394886: configfs_d_iput (STB_LOCAL)
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
