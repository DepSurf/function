# Function: <code>fuse_dentry_automount</code>

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
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148ce90)
Location: fs/fuse/dir.c:309
Inline: False
```
**Symbols:**

```
ffffffff8148ce90-ffffffff8148d00b: fuse_dentry_automount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814926f0)
Location: fs/fuse/dir.c:309
Inline: False
```
**Symbols:**

```
ffffffff814926f0-ffffffff8149288d: fuse_dentry_automount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814e9e20)
Location: fs/fuse/dir.c:309
Inline: False
```
**Symbols:**

```
ffffffff814e9e20-ffffffff814e9e8c: fuse_dentry_automount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81578720)
Location: fs/fuse/dir.c:312
Inline: False
```
**Symbols:**

```
ffffffff81578720-ffffffff81578799: fuse_dentry_automount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8161dcb0)
Location: fs/fuse/dir.c:318
Inline: False
```
**Symbols:**

```
ffffffff8161dcb0-ffffffff8161dd29: fuse_dentry_automount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81655de0)
Location: fs/fuse/dir.c:318
Inline: False
```
**Symbols:**

```
ffffffff81655de0-ffffffff81655e59: fuse_dentry_automount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *fuse_dentry_automount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8168f540)
Location: fs/fuse/dir.c:308
Inline: False
```
**Symbols:**

```
ffffffff8168f540-ffffffff8168f5b9: fuse_dentry_automount (STB_LOCAL)
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
