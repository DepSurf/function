# Function: <code>fileattr_set_prepare</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133d230)
Location: fs/ioctl.c:791
Inline: True
Inline callers:
  - fs/ioctl.c:vfs_fileattr_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fileattr_set_prepare(struct inode *inode, const struct fileattr *old_ma, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138a880)
Location: fs/ioctl.c:588
Inline: False
Direct callers:
  - fs/ioctl.c:vfs_fileattr_set
```
**Symbols:**

```
ffffffff8138a880-ffffffff8138a9b4: fileattr_set_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fileattr_set_prepare(struct inode *inode, const struct fileattr *old_ma, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140ba90)
Location: fs/ioctl.c:584
Inline: False
Direct callers:
  - fs/ioctl.c:vfs_fileattr_set
```
**Symbols:**

```
ffffffff8140ba90-ffffffff8140bbdb: fileattr_set_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fileattr_set_prepare(struct inode *inode, const struct fileattr *old_ma, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496470)
Location: fs/ioctl.c:584
Inline: False
Direct callers:
  - fs/ioctl.c:vfs_fileattr_set
```
**Symbols:**

```
ffffffff81496470-ffffffff814965bb: fileattr_set_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fileattr_set_prepare(struct inode *inode, const struct fileattr *old_ma, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb4b0)
Location: fs/ioctl.c:584
Inline: False
Direct callers:
  - fs/ioctl.c:vfs_fileattr_set
```
**Symbols:**

```
ffffffff814cb4b0-ffffffff814cb5fb: fileattr_set_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fileattr_set_prepare(struct inode *inode, const struct fileattr *old_ma, struct fileattr *fa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fdd60)
Location: fs/ioctl.c:585
Inline: False
Direct callers:
  - fs/ioctl.c:vfs_fileattr_set
```
**Symbols:**

```
ffffffff814fdd60-ffffffff814fdeab: fileattr_set_prepare (STB_LOCAL)
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
