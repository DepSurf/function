# Function: <code>inode_query_iversion</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813382c4)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e31d)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff813b23d0)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In security/integrity/ima/ima_api.c (ffffffff814536a7)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff8134f559)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813664b9)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff813cb927)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff813eaa8d)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff81470887)
Location: include/linux/iversion.h:281
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff81377ae7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f83c)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff813f55a7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff81416a40)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff8149e237)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff8138fe67)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a829c)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff8140f477)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff81430960)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814b86d1)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff813db437)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f4349)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff8145d367)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff81480532)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff81518310)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff813ece67)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406ad9)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff81479037)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff8149bc15)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff815352e0)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff813f3397)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140cf53)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff8147eaa7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff814a0d35)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8153d900)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff814453d8)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145fd93)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff814d6257)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff814f8c75)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8159c790)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff814c149a)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de502)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff8156354b)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff815892b8)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff8164180c)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff8155973a)
Location: include/linux/iversion.h:251
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81577572)
Location: include/linux/iversion.h:251
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff8160636b)
Location: include/linux/iversion.h:251
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff8162f920)
Location: include/linux/iversion.h:251
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (ffffffff816f981c)
Location: include/linux/iversion.h:251
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 inode_query_iversion(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814eca10)
Location: fs/libfs.c:1594
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr_nosec
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff814eca10-ffffffff814eca60: inode_query_iversion (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 inode_query_iversion(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81520960)
Location: fs/libfs.c:1895
Inline: False
Direct callers:
  - fs/stat.c:generic_fillattr
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/inline.c:ext4_read_inline_dir
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/readdir.c:fuse_readdir_cached
```
**Symbols:**

```
ffffffff81520960-ffffffff815209b0: inode_query_iversion (STB_GLOBAL)
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
In fs/ext4/dir.c (ffff8000104627b0)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047baa8)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffff8000104f13e0)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffff800010515438)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffff8000105b0a30)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (c06233b0)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d3d4)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (c06aed78)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (c06d01d4)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (c0760094)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (c00000000057fb80)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f128)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (c000000000631784)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (c00000000065dc84)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_api.c (c000000000730754)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffe0002f1ac4)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000305e44)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffe00036022e)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffe00037eda2)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffe0003f8540)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff81388447)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a087c)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff81407a57)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff81428f40)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814b0cb1)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff81378ed7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139130c)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff813f84d7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff814199c0)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814a16d1)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff81385da7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e0dc)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff81404dd7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff814250e0)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814acd41)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
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
In fs/ext4/dir.c (ffffffff81399a97)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b264c)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/fat/namei_vfat.c (ffffffff8141a9d7)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_unlink
  - fs/fat/namei_vfat.c:vfat_rmdir
  - fs/fat/namei_vfat.c:vfat_lookup
```
```
In fs/fuse/readdir.c (ffffffff8143bf78)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_api.c (ffffffff814c5791)
Location: include/linux/iversion.h:305
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
