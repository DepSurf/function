# Function: <code>__ext4_link</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142aab0)
Location: fs/ext4/namei.c:3424
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff8142aab0-ffffffff8142ac67: __ext4_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814317d0)
Location: fs/ext4/namei.c:3554
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff814317d0-ffffffff81431985: __ext4_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81484fe0)
Location: fs/ext4/namei.c:3382
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81484fe0-ffffffff81485195: __ext4_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81508310)
Location: fs/ext4/namei.c:3415
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81508310-ffffffff815084cd: __ext4_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a2dd0)
Location: fs/ext4/namei.c:3432
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff815a2dd0-ffffffff815a2f95: __ext4_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d97b0)
Location: fs/ext4/namei.c:3454
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff815d97b0-ffffffff815d9975: __ext4_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_link(struct inode *dir, struct inode *inode, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81611e60)
Location: fs/ext4/namei.c:3456
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81611e60-ffffffff81612011: __ext4_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
