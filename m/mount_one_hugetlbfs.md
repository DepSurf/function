# Function: <code>mount_one_hugetlbfs</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff828e5a41)
Location: fs/hugetlbfs/inode.c:1427
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff828ee3f4)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff828ee3f4-ffffffff828ee46d: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff82d037c2)
Location: fs/hugetlbfs/inode.c:1513
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff82d037c2-ffffffff82d0383b: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff82ff0b0e)
Location: fs/hugetlbfs/inode.c:1514
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff82ff0b0e-ffffffff82ff0b87: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff831fb3b5)
Location: fs/hugetlbfs/inode.c:1508
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff831fb3b5-ffffffff831fb42f: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff832e2312)
Location: fs/hugetlbfs/inode.c:1509
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff832e2312-ffffffff832e238c: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff83498554)
Location: fs/hugetlbfs/inode.c:1553
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff83498554-ffffffff834985d7: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff83ecdec0)
Location: fs/hugetlbfs/inode.c:1629
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff83ecdec0-ffffffff83ecdf7c: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff836f2f60)
Location: fs/hugetlbfs/inode.c:1624
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff836f2f60-ffffffff836f301c: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff83926130)
Location: fs/hugetlbfs/inode.c:1646
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff83926130-ffffffff839261ec: mount_one_hugetlbfs (STB_LOCAL)
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
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffff800011467ec8)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffff800011467ec8-ffff800011467f58: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (c000000001395890)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
c000000001395890-c00000000139594c: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffe0000230e2)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffe0000230e2-ffffffe00002316a: mount_one_hugetlbfs (STB_LOCAL)
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
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff828d72a8)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff828d72a8-ffffffff828d7321: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff828cf9c4)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff828cf9c4-ffffffff828cfa3d: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff828ea028)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff828ea028-ffffffff828ea0a1: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *mount_one_hugetlbfs(struct hstate *h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/hugetlbfs/inode.c (ffffffff828ef43e)
Location: fs/hugetlbfs/inode.c:1427
Inline: False
Direct callers:
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
```
**Symbols:**

```
ffffffff828ef43e-ffffffff828ef4b7: mount_one_hugetlbfs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
