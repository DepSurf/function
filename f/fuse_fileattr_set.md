# Function: <code>fuse_fileattr_set</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814a2170)
Location: fs/fuse/ioctl.c:456
Inline: False
```
**Symbols:**

```
ffffffff814a2170-ffffffff814a229f: fuse_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814fa210)
Location: fs/fuse/ioctl.c:459
Inline: False
```
**Symbols:**

```
ffffffff814fa210-ffffffff814fa33f: fuse_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff8158a4c0)
Location: fs/fuse/ioctl.c:470
Inline: False
```
**Symbols:**

```
ffffffff8158a4c0-ffffffff8158a61a: fuse_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81630c10)
Location: fs/fuse/ioctl.c:476
Inline: False
```
**Symbols:**

```
ffffffff81630c10-ffffffff81630d2c: fuse_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81668e40)
Location: fs/fuse/ioctl.c:481
Inline: False
```
**Symbols:**

```
ffffffff81668e40-ffffffff81668f5c: fuse_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816a3140)
Location: fs/fuse/ioctl.c:481
Inline: False
```
**Symbols:**

```
ffffffff816a3140-ffffffff816a325c: fuse_fileattr_set (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
