# Function: <code>swap_inode_boot_loader</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff812a09b1)
Location: fs/ext4/ioctl.c:93
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff812cf6dd)
Location: fs/ext4/ioctl.c:94
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff812e5509)
Location: fs/ext4/ioctl.c:92
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81308ca1)
Location: fs/ext4/ioctl.c:94
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8132db30)
Location: fs/ext4/ioctl.c:96
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8135c2f8)
Location: fs/ext4/ioctl.c:97
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813746e5)
Location: fs/ext4/ioctl.c:113
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139d1a0)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8139d1a0-ffffffff8139d645: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813b5c10)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813b5c10-ffffffff813b60b5: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff814015f0)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff814015f0-ffffffff81401b09: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81413fe0)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81413fe0-ffffffff81414512: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8141a250)
Location: fs/ext4/ioctl.c:115
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff8141a250-ffffffff8141a787: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8146d440)
Location: fs/ext4/ioctl.c:115
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff8146d440-ffffffff8146d96e: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff814edcf0)
Location: fs/ext4/ioctl.c:356
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff814edcf0-ffffffff814ee212: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct user_namespace *mnt_userns, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff81587bb0)
Location: fs/ext4/ioctl.c:365
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff81587bb0-ffffffff815880f4: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct mnt_idmap *idmap, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815be430)
Location: fs/ext4/ioctl.c:362
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff815be430-ffffffff815be978: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct mnt_idmap *idmap, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff815f71f0)
Location: fs/ext4/ioctl.c:371
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:__ext4_ioctl
```
**Symbols:**

```
ffffffff815f71f0-ffffffff815f7721: swap_inode_boot_loader (STB_LOCAL)
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
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffff80001048a5e8)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff80001048a5e8-ffff80001048aa1c: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c064c848)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c064c848-c064cd80: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (c0000000005b1960)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0000000005b1960-c0000000005b1eb8: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffe0003119e0)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe0003119e0-ffffffe000311dc4: swap_inode_boot_loader (STB_LOCAL)
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
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813ae1f0)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813ae1f0-ffffffff813ae695: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff8139ec80)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8139ec80-ffffffff8139f125: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813aba50)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813aba50-ffffffff813abef5: swap_inode_boot_loader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int swap_inode_boot_loader(struct super_block *sb, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ioctl.c (ffffffff813c03f0)
Location: fs/ext4/ioctl.c:113
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813c03f0-ffffffff813c0895: swap_inode_boot_loader (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, inode</code> ➡️ <code>sb, mnt_userns, inode</code>
</li>
</ul>
</details>
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
