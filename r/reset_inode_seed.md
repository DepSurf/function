# Function: <code>reset_inode_seed</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81373a90)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81373a90-ffffffff81373b7a: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139d0c0)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff8139d0c0-ffffffff8139d198: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813b5b30)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff813b5b30-ffffffff813b5c08: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81401510)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff81401510-ffffffff814015e6: reset_inode_seed (STB_LOCAL)
```
</details>
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
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffff80001048a520)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffff80001048a520-ffff80001048a5e4: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c064c74c)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
c064c74c-c064c848: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c0000000005b1820)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
c0000000005b1820-c0000000005b195c: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffe000311922)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffe000311922-ffffffe0003119e0: reset_inode_seed (STB_LOCAL)
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
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813ae110)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff813ae110-ffffffff813ae1e8: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139eba0)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff8139eba0-ffffffff8139ec78: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813ab970)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff813ab970-ffffffff813aba48: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reset_inode_seed(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813c0310)
Location: fs/ext4/ioctl.c:89
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_boot_loader
```
**Symbols:**

```
ffffffff813c0310-ffffffff813c03e8: reset_inode_seed (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
