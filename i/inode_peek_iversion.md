# Function: <code>inode_peek_iversion</code>

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
In fs/ext4/dir.c (ffffffff81337a8f)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8134e26e)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81351dc0)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813b0e49)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In security/integrity/ima/ima_main.c (ffffffff81451d1f)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff8134ed0f)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8136640e)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81369885)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813ca4a9)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff813ea007)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff8146ecdf)
Location: include/linux/iversion.h:262
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff81377abf)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8138f79b)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81392d03)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813f5039)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff814168ab)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff8149c6ec)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff8138fe3f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a81fb)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813ab675)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8140ef09)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff814307cb)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814b686c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff813db40f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813f42ba)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813f79ba)
Location: include/linux/iversion.h:286
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8145cd49)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff814803bc)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff81515eec)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff813ece3f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff81406a4a)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8140aa1d)
Location: include/linux/iversion.h:286
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff81478a39)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff8149ba9f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff81532fbc)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff813f336f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8140cedf)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81410be6)
Location: include/linux/iversion.h:286
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff8147e4a9)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff814a0bbf)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff8153b46b)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff814453b0)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8145fd1f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff81463926)
Location: include/linux/iversion.h:286
Inline: True
```
```
In fs/fat/namei_vfat.c (ffffffff814d5c59)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff814f8a9e)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff81599eeb)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff814c1472)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff814de464)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff814e25ff)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/fat/namei_vfat.c (ffffffff815633ff)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8158908f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff8163eb0c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff81559712)
Location: include/linux/iversion.h:232
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815774d4)
Location: include/linux/iversion.h:232
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff8157b9ef)
Location: include/linux/iversion.h:232
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81605fef)
Location: include/linux/iversion.h:232
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8162f5a8)
Location: include/linux/iversion.h:232
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff816f679c)
Location: include/linux/iversion.h:232
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff81591535)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815aea0c)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff815b2de7)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8163df0f)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8166781b)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
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
In fs/ext4/dir.c (ffffffff815ca275)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff815e77cc)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff815ebbdd)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8167747f)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff816a1b75)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (ffffffff8177121c)
Location: include/linux/iversion.h:250
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/ext4/dir.c (ffff800010462794)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffff80001047ba48)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffff80001047ff10)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffff8000104f0240)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffff8000105152f8)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffff8000105aea58)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (c0622a00)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c063d2d8)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (c06412ac)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (c06ad710)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (c06cffac)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (c075e144)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (c00000000057eefc)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (c00000000059f060)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (c0000000005a3d0c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (c00000000062f4a0)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (c00000000065daac)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir_cached
```
```
In security/integrity/ima/ima_main.c (c00000000072db00)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffe0002f1218)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffe000305db2)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffe000308c2e)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffe00035feda)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffe00037ec7c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f6b78)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff8138841f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813a07db)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a3c55)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff814074e9)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff81428dab)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814aee4c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff81378eaf)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139126b)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813946e5)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff813f7f69)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff8141982b)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff8149f86c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff81385d7f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff8139e03b)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813a14b5)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff81404869)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate_shortname
```
```
In fs/fuse/readdir.c (ffffffff81424f4b)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814aaeec)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
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
In fs/ext4/dir.c (ffffffff81399a6f)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
  - fs/ext4/dir.c:ext4_dir_llseek
  - fs/ext4/dir.c:ext4_readdir
```
```
In fs/ext4/inline.c (ffffffff813b25ab)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_read_inline_dir
```
```
In fs/ext4/inode.c (ffffffff813b60c6)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
```
In fs/fat/namei_vfat.c (ffffffff8141acc7)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_revalidate
```
```
In fs/fuse/readdir.c (ffffffff8143bde6)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - fs/fuse/readdir.c:fuse_readdir
```
```
In security/integrity/ima/ima_main.c (ffffffff814c392c)
Location: include/linux/iversion.h:286
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:ima_file_free
```
</details>
</li>
</ul>

## Differences
