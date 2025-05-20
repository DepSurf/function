# Function: <code>kernfs_encode_fh</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813cc9e0)
Location: fs/kernfs/mount.c:56
Inline: False
```
**Symbols:**

```
ffffffff813cc9e0-ffffffff813cca16: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813de630)
Location: fs/kernfs/mount.c:56
Inline: False
```
**Symbols:**

```
ffffffff813de630-ffffffff813de666: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff813e5390)
Location: fs/kernfs/mount.c:56
Inline: False
```
**Symbols:**

```
ffffffff813e5390-ffffffff813e53c0: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81436f60)
Location: fs/kernfs/mount.c:56
Inline: False
```
**Symbols:**

```
ffffffff81436f60-ffffffff81436f90: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff814b1ac0)
Location: fs/kernfs/mount.c:56
Inline: False
```
**Symbols:**

```
ffffffff814b1ac0-ffffffff814b1b04: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81548540)
Location: fs/kernfs/mount.c:57
Inline: False
```
**Symbols:**

```
ffffffff81548540-ffffffff81548584: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff81580100)
Location: fs/kernfs/mount.c:57
Inline: False
```
**Symbols:**

```
ffffffff81580100-ffffffff81580144: kernfs_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernfs_encode_fh(struct inode *inode, __u32 *fh, int *max_len, struct inode *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/mount.c (ffffffff815b8af0)
Location: fs/kernfs/mount.c:67
Inline: False
```
**Symbols:**

```
ffffffff815b8af0-ffffffff815b8b34: kernfs_encode_fh (STB_LOCAL)
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
