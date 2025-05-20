# Function: <code>__aafs_setup_d_inode</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __aafs_setup_d_inode(struct inode *dir, struct dentry *dentry, umode_t mode, void *data, char *link, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d89f0)
Location: security/apparmor/apparmorfs.c:179
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aafs_create
```
**Symbols:**

```
ffffffff813d89f0-ffffffff813d8b17: __aafs_setup_d_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ff230)
Location: security/apparmor/apparmorfs.c:179
Inline: True
```
**Symbols:**

```
ffffffff813ff230-ffffffff813ff34f: __aafs_setup_d_inode.constprop.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814301c0)
Location: security/apparmor/apparmorfs.c:176
Inline: True
```
**Symbols:**

```
ffffffff814301c0-ffffffff814302dd: __aafs_setup_d_inode.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144cd10)
Location: security/apparmor/apparmorfs.c:176
Inline: True
```
**Symbols:**

```
ffffffff8144cd10-ffffffff8144ce2d: __aafs_setup_d_inode.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147aaa0)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffff8147aaa0-ffffffff8147abc0: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81494830)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffff81494830-ffffffff81494950: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ebca0)
Location: security/apparmor/apparmorfs.c:211
Inline: True
```
**Symbols:**

```
ffffffff814ebca0-ffffffff814ebdc0: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81509080)
Location: security/apparmor/apparmorfs.c:211
Inline: True
```
**Symbols:**

```
ffffffff81509080-ffffffff815091a0: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150fab0)
Location: security/apparmor/apparmorfs.c:211
Inline: True
```
**Symbols:**

```
ffffffff8150fab0-ffffffff8150fbd0: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156d740)
Location: security/apparmor/apparmorfs.c:211
Inline: True
```
**Symbols:**

```
ffffffff8156d740-ffffffff8156d860: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81609dd0)
Location: security/apparmor/apparmorfs.c:214
Inline: True
```
**Symbols:**

```
ffffffff81609dd0-ffffffff81609f00: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bba50)
Location: security/apparmor/apparmorfs.c:215
Inline: True
```
**Symbols:**

```
ffffffff816bba50-ffffffff816bbb80: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f4190)
Location: security/apparmor/apparmorfs.c:216
Inline: True
```
**Symbols:**

```
ffffffff816f4190-ffffffff816f42c0: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81730f20)
Location: security/apparmor/apparmorfs.c:216
Inline: True
```
**Symbols:**

```
ffffffff81730f20-ffffffff81731033: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff800010589ff0)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffff800010589ff0-ffff80001058a108: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c073b198)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
c073b198-c073b2ec: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fb3d0)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
c0000000006fb3d0-c0000000006fb574: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d9498)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffe0003d9498-ffffffe0003d959c: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148ce10)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffff8148ce10-ffffffff8148cf30: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147d830)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffff8147d830-ffffffff8147d950: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81488eb0)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffff81488eb0-ffffffff81488fd0: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a09f0)
Location: security/apparmor/apparmorfs.c:181
Inline: True
```
**Symbols:**

```
ffffffff814a09f0-ffffffff814a0b10: __aafs_setup_d_inode.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
