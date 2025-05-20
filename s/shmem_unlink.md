# Function: <code>shmem_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a77e0)
Location: mm/shmem.c:2344
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rmdir
  - mm/shmem.c:shmem_rename2
```
**Symbols:**

```
ffffffff811a77e0-ffffffff811a7864: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bdbb0)
Location: mm/shmem.c:3015
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff811bdbb0-ffffffff811bdc34: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ce210)
Location: mm/shmem.c:2921
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff811ce210-ffffffff811ce28d: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d72e0)
Location: mm/shmem.c:3090
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff811d72e0-ffffffff811d7361: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ec4c0)
Location: mm/shmem.c:3117
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff811ec4c0-ffffffff811ec541: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120e680)
Location: mm/shmem.c:2917
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff8120e680-ffffffff8120e6ff: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81221950)
Location: mm/shmem.c:2903
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff81221950-ffffffff812219cf: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812311c0)
Location: mm/shmem.c:2985
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff812311c0-ffffffff81231241: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123f280)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff8123f280-ffffffff8123f301: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126d1a0)
Location: mm/shmem.c:2977
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff8126d1a0-ffffffff8126d24e: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81277990)
Location: mm/shmem.c:3019
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff81277990-ffffffff81277a3d: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127cfc0)
Location: mm/shmem.c:2958
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff8127cfc0-ffffffff8127d06d: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bb110)
Location: mm/shmem.c:2929
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff812bb110-ffffffff812bb1bd: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81316950)
Location: mm/shmem.c:2948
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff81316950-ffffffff81316a08: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138b310)
Location: mm/shmem.c:3021
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff8138b310-ffffffff8138b3d5: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bd730)
Location: mm/shmem.c:3178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff813bd730-ffffffff813bd7f5: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e8d10)
Location: mm/shmem.c:3357
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff813e8d10-ffffffff813e8dd5: shmem_unlink (STB_LOCAL)
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
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d12b8)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffff8000102d12b8-ffff8000102d134c: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04f96fc)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
c04f96fc-c04f97d8: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c00000000038e960)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
c00000000038e960-c00000000038ea2c: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ee054)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffe0001ee054-ffffffe0001ee0e0: shmem_unlink (STB_LOCAL)
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
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812378d0)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff812378d0-ffffffff81237951: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122a9c0)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff8122a9c0-ffffffff8122aa41: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81235670)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff81235670-ffffffff812356f1: shmem_unlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_unlink(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243e80)
Location: mm/shmem.c:3005
Inline: False
Direct callers:
  - mm/shmem.c:shmem_rename2
  - mm/shmem.c:shmem_rmdir
```
**Symbols:**

```
ffffffff81243e80-ffffffff81243f01: shmem_unlink (STB_LOCAL)
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
