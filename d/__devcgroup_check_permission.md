# Function: <code>__devcgroup_check_permission</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff81395620)
Location: security/device_cgroup.c:813
Inline: False
Direct callers:
  - security/device_cgroup.c:__devcgroup_inode_permission
  - security/device_cgroup.c:devcgroup_inode_mknod
```
**Symbols:**

```
ffffffff81395620-ffffffff8139567d: __devcgroup_check_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813d1370)
Location: security/device_cgroup.c:813
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_inode_mknod
  - security/device_cgroup.c:__devcgroup_inode_permission
```
**Symbols:**

```
ffffffff813d1370-ffffffff813d13cd: __devcgroup_check_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813e8aa0)
Location: security/device_cgroup.c:813
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_inode_mknod
  - security/device_cgroup.c:__devcgroup_inode_permission
```
**Symbols:**

```
ffffffff813e8aa0-ffffffff813e8afd: __devcgroup_check_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff813f4e40)
Location: security/device_cgroup.c:813
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_inode_mknod
  - security/device_cgroup.c:__devcgroup_inode_permission
```
**Symbols:**

```
ffffffff813f4e40-ffffffff813f4e9d: __devcgroup_check_permission (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8141d050)
Location: security/device_cgroup.c:805
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8141d050-ffffffff8141d0ad: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8144f310)
Location: security/device_cgroup.c:805
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8144f310-ffffffff8144f367: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8146c2f0)
Location: security/device_cgroup.c:805
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8146c2f0-ffffffff8146c347: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814999d0)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff814999d0-ffffffff81499a27: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814b3bd0)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff814b3bd0-ffffffff814b3c27: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffff8000105ab9f0)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffff8000105ab9f0-ffff8000105aba80: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (c075b544)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c075b544-c075b5bc: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (c000000000729aa0)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c000000000729aa0-c000000000729b2c: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffe0003f4488)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffe0003f4488-ffffffe0003f4504: __devcgroup_check_permission (STB_GLOBAL)
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
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814ac1b0)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff814ac1b0-ffffffff814ac207: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff8149cbd0)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8149cbd0-ffffffff8149cc27: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814a8250)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff814a8250-ffffffff814a82a7: __devcgroup_check_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __devcgroup_check_permission(short int type, u32 major, u32 minor, short int access);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/device_cgroup.c (ffffffff814c0c20)
Location: security/device_cgroup.c:804
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff814c0c20-ffffffff814c0c97: __devcgroup_check_permission (STB_GLOBAL)
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
