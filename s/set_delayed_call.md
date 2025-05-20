# Function: <code>set_delayed_call</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c3165)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8123d94d)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/proc/inode.c (ffffffff812a5fe2)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff812b0c08)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff812b0eb5)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff812b98f2)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/kernfs/symlink.c:kernfs_iop_get_link
```
```
In fs/ext4/symlink.c (ffffffff812edfbe)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff8133576a)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
```
```
In fs/fuse/dir.c (ffffffff81345fd4)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d31e0)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8125074d)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/proc/inode.c (ffffffff812bb902)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff812c6568)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff812c6755)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff812cf032)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/kernfs/symlink.c:kernfs_iop_get_link
```
```
In fs/ext4/symlink.c (ffffffff81304004)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff8134b41a)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
```
```
In fs/fuse/dir.c (ffffffff8135b9a4)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811da85d)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8125c8d9)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/proc/inode.c (ffffffff812c8e42)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff812d3767)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff812d3952)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff812dc743)
Location: include/linux/delayed_call.h:17
Inline: True
```
```
In fs/configfs/symlink.c (ffffffff812e122e)
Location: include/linux/delayed_call.h:17
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff8133924d)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff8136084a)
Location: include/linux/delayed_call.h:17
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81370331)
Location: include/linux/delayed_call.h:17
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f05f0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8127ebf9)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/proc/inode.c (ffffffff812ed6b2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff812f7f97)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff812f8182)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff81301041)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/configfs/symlink.c (ffffffff81305b84)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff8135d592)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_encrypted_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff8138551a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81395031)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff813ffffb)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81211d60)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812a5589)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff812fb555)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/proc/inode.c (ffffffff8131a58c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff813252c7)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813254b2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8132ed1a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/configfs/symlink.c (ffffffff81333b7d)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813b428a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff813c4264)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff81431b34)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81223bfd)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812ba6f9)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81310965)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/proc/inode.c (ffffffff81331acc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff8133c467)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8133c652)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff813460ee)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/configfs/symlink.c (ffffffff8134af15)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813cd7aa)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff813dde9c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8144d8b4)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123542a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812d7303)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81337c11)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff813598ac)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff813646c7)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813648a2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8136e3fb)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/configfs/symlink.c (ffffffff8137388f)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813f835a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81409e8d)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8147d979)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124366a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812e8e63)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff8134bc94)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff81371afc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff8137c957)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff8137cb32)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff813865ab)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff814121ba)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814234cd)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff81497649)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126f82a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff81321513)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff813915f9)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff813b95ff)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff813c62ea)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813c64c5)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff813d1218)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81460088)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81472a3d)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff814ecd5f)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127ab9a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8132cab3)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff813a2c07)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff813cb00f)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff813d829d)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813d848a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff813e2e18)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8147bca8)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8148d3d4)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8150a5aa)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127fd0e)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff81332683)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff813a9da2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff813d204c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff813df13a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813df315)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff813e9a3d)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81481538)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81492ad4)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff81510fb2)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812be01e)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8137fe13)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff813f95e2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff8142357c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff81430aea)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81430cc5)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8143b7ad)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff814d8e38)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff814ea4b4)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8156ebb2)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131a8be)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8140077a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff8146c507)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff8149c19c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff814aa82a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff814aaa15)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff814b6a9a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff8152ea12)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff81565fe2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
```
```
In fs/fuse/dir.c (ffffffff81579092)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8160b05f)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138d9de)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff8148b1fa)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff814fd8a7)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff81530abc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff8154048a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815406a5)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8154dd8a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff815ccb72)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff81609352)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
```
```
In fs/fuse/dir.c (ffffffff8161e6b2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff816bd2af)
Location: include/linux/delayed_call.h:18
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
In mm/shmem.c (ffffffff813c1b6e)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff814c0b28)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81534e07)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff81568c3c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff8157884a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81578a65)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff81585a4a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff81604662)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff81641212)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
```
```
In fs/fuse/dir.c (ffffffff81656ae2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff816f5d67)
Location: include/linux/delayed_call.h:18
Inline: True
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
In mm/shmem.c (ffffffff813ec8eb)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff814f2f48)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81569dc7)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff815a125c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff815b0fad)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815b121c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff815be52d)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ext4/symlink.c (ffffffff8163d332)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ext4/symlink.c:ext4_get_link
  - fs/ext4/symlink.c:ext4_get_link
```
```
In fs/ecryptfs/inode.c (ffffffff8167a7c5)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_get_link
```
```
In fs/fuse/dir.c (ffffffff81690362)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff81732ac7)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d593c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffff8000103939d0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffff80001040c860)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffff80001043b820)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffff8000104492b8)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffff80001044948c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffff800010456050)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffff8000104f35c4)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffff800010506930)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffff80001058acd8)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fdae0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (c05797bc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (c05d99f0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (c0601d0c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (c060e384)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c060e5a0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (c0618158)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (c06b0d38)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (c06c2a3c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (c073e038)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000395844)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (c00000000048aab0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (c000000000519750)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (c00000000054f4c4)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (c00000000055fd58)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (c000000000560000)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (c00000000056fc98)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (c00000000063371c)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (c00000000064bd80)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (c0000000006ff7cc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f13a2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffe00026144a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffe0002b5f64)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffe0002d3be0)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffe0002dec68)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffe0002dee14)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffe0002e799c)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffe000362ad6)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffe000372b40)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffe0003d8f10)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:rawdata_get_link_base
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123bcba)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812e1443)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81344274)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff8136a0dc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff81374f37)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81375112)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8137eb8b)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8140a79a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8141baad)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8148fc29)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122ecba)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812d2083)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81334f54)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff8135ab6c)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff81365a07)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81365be2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8136f61b)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff813fb21a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8140c52d)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff81480649)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81239a5a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812df253)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81341d44)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff81367bac)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff81372a07)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff81372be2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8137c65b)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff81407b1a)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff81417c4d)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff8148bcc9)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124914a)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - mm/shmem.c:shmem_get_link
```
```
In fs/namei.c (ffffffff812f0643)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/namei.c:page_get_link
```
```
In fs/crypto/hooks.c (ffffffff81355044)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/crypto/hooks.c:fscrypt_get_symlink
```
```
In fs/proc/inode.c (ffffffff8137b1fc)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/inode.c:proc_get_link
```
```
In fs/proc/self.c (ffffffff813863e7)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff813865c2)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/kernfs/symlink.c (ffffffff8139013b)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/ecryptfs/inode.c (ffffffff8141d7da)
Location: include/linux/delayed_call.h:18
Inline: True
```
```
In fs/fuse/dir.c (ffffffff8142ea3d)
Location: include/linux/delayed_call.h:18
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_get_link
```
```
In security/apparmor/apparmorfs.c (ffffffff814a3ace)
Location: include/linux/delayed_call.h:18
Inline: True
```
</details>
</li>
</ul>

## Differences
