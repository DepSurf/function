# Function: <code>i_gid_needs_update</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81527fa2)
Location: include/linux/fs.h:1714
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815851be)
Location: include/linux/fs.h:1714
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/evm/evm_main.c (ffffffff81701ed5)
Location: include/linux/fs.h:1714
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff815604b0)
Location: include/linux/fs.h:1394
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815bbb10)
Location: include/linux/fs.h:1394
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/evm/evm_main.c (ffffffff8173c7e5)
Location: include/linux/fs.h:1394
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813ec4d6)
Location: include/linux/fs.h:1439
Inline: True
Inline callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
```
```
In fs/quota/dquot.c (ffffffff81596ba0)
Location: include/linux/fs.h:1439
Inline: True
Inline callers:
  - fs/quota/dquot.c:dquot_transfer
```
```
In fs/ext4/inode.c (ffffffff815f48e9)
Location: include/linux/fs.h:1439
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
```
```
In security/integrity/evm/evm_main.c (ffffffff8177d5b0)
Location: include/linux/fs.h:1439
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_setattr
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
