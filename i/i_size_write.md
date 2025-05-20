# Function: <code>i_size_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f15c)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff8119f5e6)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff811a8b31)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_fallocate
```
```
In fs/libfs.c (ffffffff81234b29)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81241261)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff81244640)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
  - fs/buffer.c:nobh_write_end
```
```
In fs/block_dev.c (ffffffff81247526)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/proc/kcore.c (ffffffff8128710a)
Location: include/linux/fs.h:754
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8129de64)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_setattr
```
```
In fs/ext4/ioctl.c (ffffffff812a040c)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:ext4_ioctl
```
```
In fs/ext4/super.c (ffffffff812b8d03)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/extents.c (ffffffff812c3500)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812cc733)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/indirect.c (ffffffff812d9ea8)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
```
In fs/ext4/inline.c (ffffffff812dffd6)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4dda)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/inode.c (ffffffff81302beb)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8130479e)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81304c2f)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81306749)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dir.c (ffffffff81314bd4)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff813166cf)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
  - fs/fuse/file.c:fuse_write_update_size
```
```
In fs/fuse/inode.c (ffffffff8131bdee)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff813212ca)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81321a38)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8134bf8c)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff813c8eb3)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff81441cf7)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff816a43d0)
Location: include/linux/fs.h:754
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2760)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff811b5316)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff811c30a1)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8125d008)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81269591)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8126c786)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff81270676)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/proc/kcore.c (ffffffff812b4345)
Location: include/linux/fs.h:816
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812cd0a2)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff812cff4e)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/super.c (ffffffff812e7b87)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/extents.c (ffffffff812f9afb)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff812fc080)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/inline.c (ffffffff8130fc9c)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff813288a3)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/inode.c (ffffffff81336b6b)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff813388be)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81338d96)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8133ac7c)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81349243)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8134d34a)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff813508dc)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff813566a8)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81356e1e)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff81381c4b)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff8140d0c1)
Location: include/linux/fs.h:816
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (0)
Location: include/linux/fs.h:816
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/fs.h:816
Inline: True
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
In mm/filemap.c (ffffffff811b25a0)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff811c5926)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff811d3102)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8127053f)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff8127c541)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8127f7e6)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff81283e46)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/proc/kcore.c (ffffffff812c9bd5)
Location: include/linux/fs.h:769
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812e2e1e)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff812e5d28)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/super.c (ffffffff812fd8c7)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/extents.c (ffffffff8130faf8)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
```
```
In fs/ext4/migrate.c (ffffffff81312030)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/inline.c (ffffffff81325ac0)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e5e7)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In fs/ecryptfs/inode.c (ffffffff8134c82b)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8134e65e)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff8134eb2d)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81350a0c)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8135ea42)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81362c5a)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8136623c)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8136caf8)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8136d2e8)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff813986cb)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff81428393)
Location: include/linux/fs.h:769
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (0)
Location: include/linux/fs.h:769
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/fs.h:769
Inline: True
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
In mm/filemap.c (ffffffff811b924e)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff811cdc36)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff811dba4b)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8127dc5f)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81289c11)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8128d82c)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff81291506)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/proc/kcore.c (ffffffff812d7080)
Location: include/linux/fs.h:788
Inline: True
```
```
In fs/ext4/extents.c (ffffffff812ee02a)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff812f9b07)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8130708f)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff81308e21)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff81313ad5)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8133262f)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff8133bea7)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81353200)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff81361398)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff813631bf)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81363605)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8136551c)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81373537)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff813775ea)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8137a8fc)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff81381094)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8138184b)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff813aeb28)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814366d6)
Location: include/linux/fs.h:788
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (0)
Location: include/linux/fs.h:788
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/fs.h:788
Inline: True
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
In mm/filemap.c (ffffffff811cf6e1)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff811e2fe6)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff811f187a)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff812a070f)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff812ac751)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff812b03e0)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff812b4256)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/proc/kcore.c (ffffffff812fb829)
Location: include/linux/fs.h:792
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81312af7)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff8131e147)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8132bc4f)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8132dca8)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff81338295)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81356b3f)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff81360375)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
```
```
In fs/hugetlbfs/inode.c (ffffffff81377de9)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff81386068)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81387e83)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81388328)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8138a1ec)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81398247)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8139c38a)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8139f79c)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff813a60a4)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813a685b)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff813d4bd8)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff81462466)
Location: include/linux/fs.h:792
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (0)
Location: include/linux/fs.h:792
Inline: True
```
```
In drivers/md/dm.c (0)
Location: include/linux/fs.h:792
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
In mm/filemap.c (ffffffff811f079f)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81204643)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff812133bc)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff812c6c6f)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff812d4330)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff812d7c7d)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff812db86b)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/proc/kcore.c (ffffffff81328e77)
Location: include/linux/fs.h:799
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81340993)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff8134c143)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8135a020)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8135c448)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff81366816)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81384e50)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff8138e35d)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6229)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff813b4d78)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff813b6b91)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff813b6f4c)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813b8fd2)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff813c73ea)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff813cb7ba)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff813ceb3d)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff813d5321)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813d5b5f)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff81404da2)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff81495d88)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff8152a94f)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff8180a165)
Location: include/linux/fs.h:799
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff81200f8f)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81217003)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81224e69)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff812dbe3f)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff812e9700)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff812ed78d)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:__generic_write_end
```
```
In fs/block_dev.c (ffffffff812f26b3)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap.c (ffffffff813241c9)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff8133fcb7)
Location: include/linux/fs.h:847
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81357f83)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff81364288)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff81372350)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff813748b5)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff8137ec68)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8139d940)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813a6944)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff813bec59)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff813ce298)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff813d00e1)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff813d049c)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813d2542)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff813e05da)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff813e486a)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff813e7fad)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff813ef971)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff813f015f)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8141f782)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814afc38)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff815407cf)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff81836165)
Location: include/linux/fs.h:847
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff81218b9c)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81226966)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81235946)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff812fa4df)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff813080c0)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8130ee11)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff81314060)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff8134c3d3)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8134dc9a)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff81367fc7)
Location: include/linux/fs.h:862
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813814f7)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff8138ddd9)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8139ba23)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8139d391)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff813a80b2)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813c7b5a)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813d11b3)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff813e94ec)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff813f8de9)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff813facd4)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff813fb30c)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813fcfe0)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8140c23e)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81410542)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_short_read
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81414052)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8141bc84)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8141c4d5)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8144d3ce)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814de000)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff815700bf)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff81878d92)
Location: include/linux/fs.h:862
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff8122644c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff812347d6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81243b86)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8130c25f)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff8131b160)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff81321e31)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff8132782a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff813646a3)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff81365f4b)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff8138022c)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81399aa7)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff813a6839)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813b45a0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff813b5e01)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff813c0f07)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813e0f1a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813ea889)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff8140358c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff81412c49)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81414ba4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff814151dc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81416ec0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81425dfc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8142a152)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8142e0f2)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff81435ad4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81436325)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff814671e6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814f745d)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff81591278)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff818aabd2)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff812513a4)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81261d96)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81270c83)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff81345741)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81354e10)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8135d0c1)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff81360b10)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff813ac216)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff813ad97f)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/kcore.c (ffffffff813ca43c)
Location: include/linux/fs.h:894
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813e443d)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813e900e)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff813f1a06)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813ffa48)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff81401803)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff8140d4b2)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8142db1e)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff81436812)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff8145134c)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff814607b2)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81462dfc)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81463486)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81465416)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81475364)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8147a202)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8147dd62)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8148593f)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814860d6)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff814bbab6)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/partitions/core.c (ffffffff8155db3c)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
```
```
In drivers/pci/proc.c (ffffffff8163f1a5)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff81977295)
Location: include/linux/fs.h:894
Inline: True
Inline callers:
  - drivers/md/dm.c:__bind
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
In mm/filemap.c (ffffffff8125cb73)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff8126c096)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff8127bd06)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff81351e7f)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81361730)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff81369bbe)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff813bd809)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff813befbf)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/kcore.c (ffffffff813dc0fc)
Location: include/linux/fs.h:857
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813f5c9f)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff813fae74)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814040a6)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8141222e)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff814141fe)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff81420912)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff814467de)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff8144f232)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff8146d86c)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff8147c3d2)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8147e899)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff8147ecd3)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81480cb6)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8148ff85)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81494ef5)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff814990e5)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff814a2f4f)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814a36d8)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff814d9432)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/genhd.c (ffffffff81577707)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff8157998f)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/proc.c (ffffffff816654c2)
Location: include/linux/fs.h:857
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffffffff812617f7)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81270f86)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81280e92)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff81358ba3)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81368210)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8136fd5e)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff813c4951)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff813c60ff)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_actor
```
```
In fs/proc/kcore.c (ffffffff813e309c)
Location: include/linux/fs.h:858
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813fbfcb)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff81401449)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_end_io
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8140a585)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8141866e)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8141a470)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff814270cd)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff8144bf8e)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff81454af2)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff81472de0)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff81481e99)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8148442d)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81484865)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff814865a6)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff814959bd)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81499f55)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8149e315)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff814a900f)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff814a96b9)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff814dfb22)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/genhd.c (ffffffff8157f46f)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81581649)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/proc.c (ffffffff81647b89)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffffffff8129a0ed)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff812adf56)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff812bf307)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff813a7293)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff813b6f10)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff813bf638)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8141410c)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff814154cb)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/kcore.c (ffffffff81434bac)
Location: include/linux/fs.h:903
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8144e384)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814539c9)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_end_io
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff8145d195)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8146b881)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8146d663)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff8147ad7c)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff814a0008)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff814a8c18)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff814c98f0)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff814d9c59)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff814dbaaa)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff814dbee5)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff814ddd36)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff814ed457)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff814f1975)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff814f61c5)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff815014c9)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81501a49)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff81538aa0)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/genhd.c (ffffffff815e44fc)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff815e6978)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/proc.c (ffffffff816b94e9)
Location: include/linux/fs.h:903
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffffffff812f7199)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81308b46)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff8131b047)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8142c7aa)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff8143c530)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff814471dd)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8148a232)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8148cc0c)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/kcore.c (ffffffff814aed05)
Location: include/linux/fs.h:858
Inline: True
```
```
In fs/ext4/extents.c (ffffffff814cafc0)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff814d170b)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_end_io
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff814db9b3)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff814eb9be)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff814edf31)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff814fd1a9)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff81526c55)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff815301cd)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff81555aa7)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff815674a4)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81569712)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81569bc4)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8156be45)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8157c3bf)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8157f8dc)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81585fd3)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff81592816)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81592e62)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff815d004d)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/genhd.c (ffffffff81692c75)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81695ae9)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/proc.c (ffffffff817ddc16)
Location: include/linux/fs.h:858
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffffffff81360a3e)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81372966)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff8138ed3f)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff814ba01a)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff814cac00)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff814d5d86)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8151dc22)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8152012f)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/kcore.c (ffffffff815453a5)
Location: include/linux/fs.h:873
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81563645)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff8156a06b)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_end_io
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff81574903)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8158569c)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff81587e0e)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff8159796c)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815c4535)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff815cebce)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff815f6d17)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff8160aae4)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8160d30d)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff8160d7f6)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8160ff65)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81621dcc)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff816255bc)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8162c1c5)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8163a0a6)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8163a8a0)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8167dd3d)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/genhd.c (ffffffff817519c5)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - block/genhd.c:invalidate_disk
  - block/genhd.c:del_gendisk
  - block/genhd.c:set_capacity_and_notify
```
```
In block/partitions/core.c (ffffffff81754d1c)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - block/partitions/core.c:bdev_resize_partition
  - block/partitions/core.c:add_partition
```
```
In drivers/pci/proc.c (ffffffff81900736)
Location: include/linux/fs.h:873
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffffffff81392f2a)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff813a4ac6)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff813c2111)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff814eef97)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81500e40)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8150a921)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff81555d9a)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8155819f)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/kcore.c (ffffffff8157cf85)
Location: include/linux/fs.h:888
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8159b330)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815a1e6e)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_end_io
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815ac7c3)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815bbee5)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff815be68e)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff815ce3a3)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff815fbc0f)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff816064ad)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff8162edd7)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff816429b4)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff816451cd)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff816456ad)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff81647df5)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8165a225)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8165d958)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81664405)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff81672506)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81672e7a)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff816b5f2d)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/bdev.c (ffffffff81766a94)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - block/bdev.c:bdev_set_nr_sectors
```
```
In drivers/pci/proc.c (ffffffff81943ccd)
Location: include/linux/fs.h:888
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffffffff813bcbda)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff813ce626)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff813ece80)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff81522c15)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81535a60)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8153f471)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/buffer.c:generic_write_end
```
```
In fs/iomap/buffered-io.c (ffffffff8158c308)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8158e7cf)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
```
In fs/proc/kcore.c (ffffffff815b58d4)
Location: include/linux/fs.h:921
Inline: True
```
```
In fs/ext4/extents.c (ffffffff815d416c)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
```
```
In fs/ext4/file.c (ffffffff815da8aa)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_handle_inode_extension
```
```
In fs/ext4/inline.c (ffffffff815e5553)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_finish_convert_inline_dir
  - fs/ext4/inline.c:ext4_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff815f4caf)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_da_write_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff815f7447)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff81606c23)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff816347af)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff8163f1ed)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/hugetlbfs/inode.c (ffffffff816682c7)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff8167bfe7)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e6f7)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff8167eb9d)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff816812a8)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_headers_virt
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff81693ec1)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81697695)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_end
  - fs/fuse/file.c:fuse_write_update_attr
  - fs/fuse/file.c:fuse_read_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8169e602)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff816ae546)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff816af21c)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff816f369f)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/bdev.c (ffffffff817a86b4)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - block/bdev.c:bdev_set_nr_sectors
```
```
In drivers/pci/proc.c (ffffffff8198cf9d)
Location: include/linux/fs.h:921
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
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
In mm/filemap.c (ffff8000102b374c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffff8000102c4e08)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffff8000102d5d00)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffff8000103c0a34)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffff8000103d24ec)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffff8000103d99b8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffff8000103e2730)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffff80001042b1c8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffff80001042cde8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffff80001044dc34)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffff80001046c4bc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffff80001047a14c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffff800010488c98)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffff80001048a7dc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffff800010498740)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffff8000104ba2b0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffff8000104c2db8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffff8000104e2018)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffff8000104f3fd4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffff8000104f635c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffff8000104f6724)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffff8000104f8504)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dir.c (ffff800010509640)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffff80001050e154)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffff80001051276c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffff80001051bcf0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffff80001051c6a8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffff8000105555ac)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffff8000105f82cc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffff8000106f669c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffff800010b00cfc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (c04e09f0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (c04ef674)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (c04fe078)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (c059dfcc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (c05ad138)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (c05b3eb4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (c05b8a38)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:bd_set_size
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (c05f44c0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (c05f5bcc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/ext4/extents.c (c062d7ac)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (c063b9c4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (c064b10c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (c064ca70)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (c0659f74)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c067d954)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (c068603c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_write
```
```
In fs/ecryptfs/inode.c (c06b1a3c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c06b3d58)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (c06b4208)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c06b5d84)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dir.c (c06c5590)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (c06c9784)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (c06cd8a0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (c06d87b4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (c06d8d04)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (c070b060)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (c07a35cc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (c0890808)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (c0be05d4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (c00000000036a394)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (c00000000037f574)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (c000000000395d3c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (c0000000004bf180)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (c0000000004d4fe0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (c0000000004dfc70)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (c0000000004e84ac)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (c00000000053ba58)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (c00000000053e6f0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (c00000000056544c)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (c00000000058bddc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (c00000000059c394)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (c0000000005af940)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (c0000000005b1bd4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (c0000000005c2698)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (c0000000005ef9f0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (c0000000005faec4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (c00000000061eac8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (c000000000634598)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (c000000000637300)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (c0000000006376d8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (c00000000063a5b8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (c00000000064f3c4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (c000000000655054)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (c00000000065a47c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In security/selinux/selinuxfs.c (c0000000006b594c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (c0000000007904cc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (c00000000087590c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (c000000000befef4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffe0001d8e38)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffe0001e54fa)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffe0001f17d0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffe00028108e)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffe00028d854)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffe0002935c6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffe000298d1c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffe0002c8898)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffe0002ca170)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffe0002e24b8)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffffffe0002f9a00)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffe000304374)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffe00031065a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffe000311cc4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffe00031c4bc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffe0003367ce)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffe00033e52c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffe000355b36)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffe0003633b6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffe00036515a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffe00036539a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffe000366e5a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_i_size_init
```
```
In fs/fuse/dir.c (ffffffe0003750d0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffe000378e0e)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffe00037c7ee)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In security/selinux/selinuxfs.c (ffffffe0003ae09c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffe00043512a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffe0004c89ba)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffe0006f0e64)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff8121ea9c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff8122ce26)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff8123c1d6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8130483f)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81313740)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8131a411)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff8131fe0a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff8135cc83)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8135e52b)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff8137880c)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81392087)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff8139ee19)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813acb80)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff813ae3e1)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff813b94e7)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813d94fa)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813e2e69)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff813fbb6c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff8140b229)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8140d184)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff8140d7bc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8140f4a0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8141e3dc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81422732)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff814266d2)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8142e0b4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8142e905)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8145f7c6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814efa3d)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff81585108)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff81850a52)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff81211c5c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff8121fef6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff8122f1d6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff812f545f)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81304350)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff8130afb1)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff813109aa)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff8134d923)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8134f1cb)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff813692dc)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffffffff81382b17)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff8138f8a9)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff8139d610)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff8139ee71)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff813a9f77)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813c9f7a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813d38e9)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff813ec5ec)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff813fbca9)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff813fdc04)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff813fe23c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff813fff20)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8140ee5c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff814131b2)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81417152)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8141eb34)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8141f385)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff814501f6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814dff7d)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff81573ed8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff81818062)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff8121c83c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff8122abc6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81239f76)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff8130262f)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81311530)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff81317ee1)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff8131d8da)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff8135a753)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8135bffb)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff813762dc)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffffffff8138f9e7)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff8139c679)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813aa3e0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff813abc41)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff813b6d47)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813d698a)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813e01e9)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff813f8eec)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff814085a9)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff8140a504)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff8140ab3c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff8140c820)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff8141a57c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff8141e8d2)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff81422872)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff8142a254)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff8142aaa5)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff8145b866)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff814ebacd)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff81584fc8)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff818a0082)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
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
In mm/filemap.c (ffffffff8122b8cc)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_direct_write
```
```
In mm/truncate.c (ffffffff81239fc6)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/truncate.c:truncate_setsize
```
```
In mm/shmem.c (ffffffff81249665)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fallocate
  - mm/shmem.c:shmem_write_end
  - mm/shmem.c:shmem_setattr
```
```
In fs/libfs.c (ffffffff81313c4f)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_end
```
```
In fs/stack.c (ffffffff81322d80)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/stack.c:fsstack_copy_inode_size
```
```
In fs/buffer.c (ffffffff81329af1)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_end
  - fs/buffer.c:generic_write_end
```
```
In fs/block_dev.c (ffffffff8132f5da)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:check_disk_size_change
```
```
In fs/iomap/buffered-io.c (ffffffff8136dea3)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8136f74b)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
```
In fs/proc/kcore.c (ffffffff81389d8c)
Location: include/linux/fs.h:876
Inline: True
```
```
In fs/ext4/extents.c (ffffffff813a381b)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_zero_range
  - fs/ext4/extents.c:ext4_alloc_file_blocks
```
```
In fs/ext4/inline.c (ffffffff813b0b8c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_convert_inline_data_nolock
  - fs/ext4/inline.c:ext4_da_write_inline_data_end
```
```
In fs/ext4/inode.c (ffffffff813becf0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_direct_IO_write
  - fs/ext4/inode.c:ext4_iomap_end
  - fs/ext4/inode.c:ext4_journalled_write_end
  - fs/ext4/inode.c:ext4_write_end
```
```
In fs/ext4/ioctl.c (ffffffff813c05e1)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:swap_inode_boot_loader
  - fs/ext4/ioctl.c:swap_inode_data
  - fs/ext4/ioctl.c:swap_inode_data
```
```
In fs/ext4/migrate.c (ffffffff813cba57)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
```
In fs/ext4/super.c (ffffffff813ebc35)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_quota_write
```
```
In fs/ext4/xattr.c (ffffffff813f5609)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
```
```
In fs/hugetlbfs/inode.c (ffffffff8140ed2c)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_file_mmap
```
```
In fs/ecryptfs/inode.c (ffffffff8141e269)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/inode.c:ecryptfs_link
```
```
In fs/ecryptfs/mmap.c (ffffffff81420208)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_end
```
```
In fs/ecryptfs/read_write.c (ffffffff81420807)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/read_write.c:ecryptfs_write
```
```
In fs/ecryptfs/crypto.c (ffffffff814224a0)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_xattr_region
  - fs/ecryptfs/crypto.c:ecryptfs_read_and_validate_header_region
```
```
In fs/fuse/dir.c (ffffffff814312f2)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
```
In fs/fuse/file.c (ffffffff81435642)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_write_update_size
  - fs/fuse/file.c:fuse_finish_open
```
```
In fs/fuse/inode.c (ffffffff8143969d)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_change_attributes
```
```
In fs/efivarfs/file.c (ffffffff81441114)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/file.c:efivarfs_file_write
```
```
In fs/efivarfs/super.c (ffffffff81441965)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
```
In security/selinux/selinuxfs.c (ffffffff81473006)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In block/ioctl.c (ffffffff81504add)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - block/ioctl.c:blkpg_ioctl
```
```
In drivers/pci/proc.c (ffffffff8159f478)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_write
```
```
In drivers/md/dm.c (ffffffff818bc2f4)
Location: include/linux/fs.h:876
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
```
</details>
</li>
</ul>

## Differences
