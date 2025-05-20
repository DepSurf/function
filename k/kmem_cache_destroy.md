# Function: <code>kmem_cache_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811b3120)
Location: mm/slab_common.c:700
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/mbcache.c:mb_cache_destroy
  - fs/dcookies.c:dcookie_register
  - fs/dcookies.c:dcookie_unregister
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/crypto.c:ext4_exit_crypto
  - fs/ext4/crypto.c:ext4_exit_crypto
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:journal_init
  - fs/hugetlbfs/inode.c:exit_hugetlbfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - block/bio.c:bioset_free
  - block/elevator.c:elv_register
  - block/elevator.c:elv_unregister
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_exit
  - lib/btree.c:btree_module_exit
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_init_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
```
**Symbols:**

```
ffffffff811b3120-ffffffff811b338f: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811ccb80)
Location: mm/slab_common.c:706
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/mbcache.c:mbcache_exit
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - block/bio.c:bioset_free
  - block/elevator.c:elv_unregister
  - block/elevator.c:elv_register
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_exit
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811ccb80-ffffffff811ccdce: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811dcc70)
Location: mm/slab_common.c:735
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/mbcache.c:mbcache_exit
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - block/bio.c:bioset_free
  - block/elevator.c:elv_unregister
  - block/elevator.c:elv_register
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_exit
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_on_init_error
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/scsi/scsi.c:scsi_setup_command_freelist
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811dcc70-ffffffff811dcebe: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811e5ef0)
Location: mm/slab_common.c:811
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/ss/ebitmap.c:ebitmap_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - block/bio.c:bioset_free
  - block/elevator.c:elv_register
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_exit
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:__dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811e5ef0-ffffffff811e60d3: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff811fc130)
Location: mm/slab_common.c:820
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/selinux/ss/ebitmap.c:ebitmap_cache_destroy
  - security/selinux/ss/hashtab.c:hashtab_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - security/selinux/ss/avtab.c:avtab_cache_destroy
  - block/bio.c:bioset_free
  - block/elevator.c:elv_register
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_exit
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:__dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff811fc130-ffffffff811fc313: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8121daf0)
Location: mm/slab_common.c:874
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_init
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/bsg.c:bsg_init
  - block/cfq-iosched.c:cfq_exit
  - block/cfq-iosched.c:cfq_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/dax/super.c:__dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8121daf0-ffffffff8121dd02: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff81230ad0)
Location: mm/slab_common.c:901
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_init
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_caches
  - fs/jbd2/journal.c:journal_init
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:free_iommu_resources
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_fs_init
  - drivers/dax/super.c:__dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_exit
  - drivers/md/dm.c:local_init
  - drivers/md/dm.c:local_init
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81230ad0-ffffffff81230ce2: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:926
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_exit
  - fs/crypto/crypto.c:fscrypt_init
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81242752-ffffffff8124276c: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff81240f00-ffffffff8124110b: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81250c5f-ffffffff81250c79: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff8124f380-ffffffff8124f5b0: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_slab_init
  - mm/ksm.c:ksm_slab_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_exit
  - fs/dcookies.c:dcookie_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - block/bio.c:bio_put_slab
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_init_mempool
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8127f2cc-ffffffff8127f2e6: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff8127d740-ffffffff8127d806: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:482
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_slab_init
  - mm/ksm.c:ksm_slab_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_exit
  - fs/dcookies.c:dcookie_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - block/bio.c:bio_put_slab
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dmaengine_init_unmap_pool
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:iommu_init_mempool
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81be72f6-ffffffff81be7311: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff81287ee0-ffffffff81287fd1: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:496
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81bd9098-ffffffff81bd90b3: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff8128d2a0-ffffffff8128d37d: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:498
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff81cbb3ce-ffffffff81cbb3f0: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff812cd0c0-ffffffff812cd1b7: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8132b9e0)
Location: mm/slab_common.c:494
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:free_iommu_resources
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8132b9e0-ffffffff8132bb0a: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813a0d50)
Location: mm/slab_common.c:480
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:exit_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/apparmor/lsm.c:apparmor_init
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff813a0d50-ffffffff813a0e9f: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813d3fd0)
Location: mm/slab_common.c:480
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - mm/shmem.c:shmem_init
  - mm/zswap.c:zswap_setup
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:exit_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/apparmor/lsm.c:apparmor_init
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/virtio_scsi.c:virtio_scsi_fini
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff813d3fd0-ffffffff813d411f: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff813fed40)
Location: mm/slab_common.c:475
Inline: False
Direct callers:
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - mm/shmem.c:shmem_init
  - mm/zswap.c:zswap_setup
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/page-io.c:ext4_init_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/fast_commit.c:ext4_fc_destroy_dentry_cache
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:exit_fat_fs
  - fs/ecryptfs/main.c:ecryptfs_exit
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/ecryptfs/main.c:ecryptfs_init
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_exit
  - fs/fuse/inode.c:fuse_init
  - ipc/mqueue.c:init_mqueue_fs
  - security/apparmor/lsm.c:apparmor_init
  - block/bio.c:bioset_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/amd/init.c:state_next
  - drivers/dax/super.c:dax_core_exit
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_core_init
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/virtio_scsi.c:virtio_scsi_fini
  - drivers/scsi/virtio_scsi.c:virtio_scsi_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff813fed40-ffffffff813feea0: kmem_cache_destroy (STB_GLOBAL)
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
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e57e8)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_exit
  - virt/kvm/kvm_main.c:kvm_init
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffff8000102e57e8-ffff8000102e5a5c: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0509a68)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/omap-iommu.c:omap_iommu_init
  - drivers/iommu/exynos-iommu.c:exynos_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
c0509a68-c0509c74: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0000000003a7810)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
c0000000003a7810-c0000000003a7b50: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc1e8)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffe0001fc1e8-ffffffe0001fc3d2: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff812492af-ffffffff812492c9: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff812479d0-ffffffff81247c00: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8123c25f-ffffffff8123c279: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff8123a980-ffffffff8123abaa: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/virtio_scsi.c:fini
  - drivers/scsi/virtio_scsi.c:init
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_init_start
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_cleanup_end
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_fini
  - net/netfilter/nf_conntrack_expect.c:nf_conntrack_expect_init
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8124704f-ffffffff81247069: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff81245770-ffffffff812459a0: kmem_cache_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void kmem_cache_destroy(struct kmem_cache *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:940
Inline: False
Direct callers:
  - mm/shmem.c:shmem_init
  - mm/zswap.c:init_zswap
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_init
  - mm/khugepaged.c:khugepaged_destroy
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_destroy_pool
  - mm/zsmalloc.c:zs_create_pool
  - fs/crypto/crypto.c:fscrypt_init
  - fs/crypto/crypto.c:fscrypt_init
  - fs/verity/open.c:fsverity_exit_info_cache
  - fs/mbcache.c:mbcache_exit
  - fs/configfs/mount.c:configfs_exit
  - fs/configfs/mount.c:configfs_init
  - fs/dcookies.c:dcookie_unregister
  - fs/dcookies.c:dcookie_register
  - fs/ext4/block_validity.c:ext4_exit_system_zone
  - fs/ext4/extents_status.c:ext4_exit_pending
  - fs/ext4/extents_status.c:ext4_exit_es
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_exit_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/mballoc.c:ext4_init_mballoc
  - fs/ext4/page-io.c:ext4_exit_pageio
  - fs/ext4/readpage.c:ext4_exit_post_read_processing
  - fs/ext4/readpage.c:ext4_init_post_read_processing
  - fs/ext4/super.c:ext4_exit_fs
  - fs/ext4/super.c:ext4_init_fs
  - fs/jbd2/transaction.c:jbd2_journal_destroy_transaction_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_table_cache
  - fs/jbd2/revoke.c:jbd2_journal_destroy_revoke_record_cache
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/jbd2/journal.c:jbd2_journal_destroy_caches
  - fs/squashfs/super.c:exit_squashfs_fs
  - fs/squashfs/super.c:init_squashfs_fs
  - fs/hugetlbfs/inode.c:init_hugetlbfs_fs
  - fs/fat/cache.c:fat_cache_destroy
  - fs/fat/inode.c:fat_destroy_inodecache
  - fs/ecryptfs/main.c:ecryptfs_free_kmem_caches
  - fs/fuse/dev.c:fuse_dev_cleanup
  - fs/fuse/dev.c:fuse_dev_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_fs_cleanup
  - ipc/mqueue.c:init_mqueue_fs
  - security/smack/smack_lsm.c:smack_init
  - block/bio.c:bioset_exit
  - block/elevator.c:elv_register
  - lib/btree.c:btree_module_exit
  - lib/sg_pool.c:sg_pool_exit
  - lib/sg_pool.c:sg_pool_init
  - drivers/acpi/osl.c:acpi_os_delete_cache
  - drivers/dma/dmaengine.c:dma_bus_init
  - drivers/iommu/iova.c:iova_cache_put
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/dax/super.c:dax_core_init
  - drivers/dax/super.c:dax_fs_exit
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/scsi_lib.c:scsi_exit_queue
  - drivers/scsi/sd.c:exit_sd
  - drivers/scsi/sd.c:init_sd
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_cleanup
  - drivers/usb/host/uhci-hcd.c:uhci_hcd_init
  - drivers/md/dm-uevent.c:dm_uevent_exit
  - drivers/md/dm-io.c:dm_io_exit
  - drivers/md/dm-kcopyd.c:dm_kcopyd_exit
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_unregister
  - net/core/sock.c:proto_register
  - net/core/sock.c:proto_register
  - net/ipv4/inet_fragment.c:inet_frags_fini
  - net/ipv4/ipmr.c:ip_mr_init
  - net/ipv6/route.c:ip6_route_cleanup
  - net/ipv6/route.c:ip6_route_init
  - net/ipv6/ip6_fib.c:fib6_gc_cleanup
  - net/ipv6/ip6_fib.c:fib6_init
  - net/ipv6/ip6mr.c:ip6_mr_cleanup
  - net/ipv6/ip6mr.c:ip6_mr_init
```
**Symbols:**

```
ffffffff8125687f-ffffffff81256899: kmem_cache_destroy.cold (STB_LOCAL)
ffffffff81254680-ffffffff812548a7: kmem_cache_destroy (STB_GLOBAL)
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
