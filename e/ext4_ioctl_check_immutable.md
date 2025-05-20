# Function: <code>ext4_ioctl_check_immutable</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139ccf0)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8139ccf0-ffffffff8139cd3e: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813b5770)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813b5770-ffffffff813b57be: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81400850)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81400850-ffffffff8140089e: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81413160)
Location: fs/ext4/ioctl.c:279
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81413160-ffffffff814131ae: ext4_ioctl_check_immutable (STB_LOCAL)
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
In fs/ext4/ioctl.c (ffffffff8141b62f)
Location: fs/ext4/ioctl.c:283
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
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
In fs/ext4/ioctl.c (ffffffff8146e94f)
Location: fs/ext4/ioctl.c:282
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
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
In fs/ext4/ioctl.c (ffffffff814ef310)
Location: fs/ext4/ioctl.c:511
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
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
In fs/ext4/ioctl.c (ffffffff81589560)
Location: fs/ext4/ioctl.c:522
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
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
In fs/ext4/ioctl.c (ffffffff815bfd80)
Location: fs/ext4/ioctl.c:520
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
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
In fs/ext4/ioctl.c (ffffffff815f8b20)
Location: fs/ext4/ioctl.c:530
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_fileattr_set
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffff80001048a338)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff80001048a338-ffff80001048a3b0: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c064c2e8)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c064c2e8-c064c358: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c0000000005b17a0)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0000000005b17a0-c0000000005b1820: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffe0003118b4)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe0003118b4-ffffffe000311922: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813add50)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813add50-ffffffff813add9e: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139e7e0)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8139e7e0-ffffffff8139e82e: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813ab5b0)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813ab5b0-ffffffff813ab5fe: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_ioctl_check_immutable(struct inode *inode, __u32 new_projid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813bff50)
Location: fs/ext4/ioctl.c:277
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813bff50-ffffffff813bff9e: ext4_ioctl_check_immutable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
