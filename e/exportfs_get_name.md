# Function: <code>exportfs_get_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8130c670)
Location: fs/exportfs/expfs.c:25
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8130c670-ffffffff8130c6d5: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81340940)
Location: fs/exportfs/expfs.c:25
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81340940-ffffffff813409a5: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff813566c0)
Location: fs/exportfs/expfs.c:25
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff813566c0-ffffffff81356725: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8136b2d0)
Location: fs/exportfs/expfs.c:26
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8136b2d0-ffffffff8136b335: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8138fe60)
Location: fs/exportfs/expfs.c:26
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8138fe60-ffffffff8138fec7: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff813bef00)
Location: fs/exportfs/expfs.c:26
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff813bef00-ffffffff813bef67: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff813d8540)
Location: fs/exportfs/expfs.c:26
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff813d8540-ffffffff813d85a7: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81402f00)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81402f00-ffffffff81402f67: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8141ce10)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8141ce10-ffffffff8141ce77: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8146c0f8)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81486846)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8148c294)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814e3aa4)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81571eab)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff816172db)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8164f3cc)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81688944)
Location: fs/exportfs/expfs.c:27
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:reconnect_one
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
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffff8000104fe9e8)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffff8000104fe9e8-ffff8000104fea80: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c06bbaac)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
c06bbaac-c06bbb38: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c000000000641de0)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:reconnect_path
```
**Symbols:**

```
c000000000641de0-c000000000641e84: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffe00036c8f4)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffe00036c8f4-ffffffe00036c95a: exportfs_get_name (STB_LOCAL)
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
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814153f0)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff814153f0-ffffffff81415457: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81405e70)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81405e70-ffffffff81405ed7: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81412770)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81412770-ffffffff814127d7: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int exportfs_get_name(struct vfsmount *mnt, struct dentry *dir, char *name, struct dentry *child);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814283e0)
Location: fs/exportfs/expfs.c:27
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff814283e0-ffffffff81428447: exportfs_get_name (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
