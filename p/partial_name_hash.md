# Function: <code>partial_name_hash</code>

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
In fs/kernfs/dir.c (ffffffff812891ff)
Location: include/linux/dcache.h:74
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff812fed18)
Location: include/linux/dcache.h:74
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8132175b)
Location: include/linux/dcache.h:74
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff813502c7)
Location: include/linux/dcache.h:74
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff812b66ec)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81332d24)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff81356b2c)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81386305)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff812cc47c)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81348ac4)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8136cf8c)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff8139cd95)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff812d941c)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8135d621)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff813814e0)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff813b34e5)
Location: include/linux/stringhash.h:42
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff812fdc5c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81382321)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff813a64f0)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff813d9635)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff8132b8bc)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813b0f0c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff813d57fd)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81409be7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff81342c1c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813ca56c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff813efe4d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81425ed7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff8136aea7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813f5100)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8141c17d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81453917)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff81383067)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8140efd0)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff81435fcd)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff8146d6b7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff813cd9b5)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8145ce15)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff81485d67)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff814c1ea7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff813df5e9)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81478b05)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff814882ae)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff814a335b)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff814e24aa)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
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
In fs/kernfs/dir.c (ffffffff813e6289)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8147e56d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff8148dc8e)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff814a937b)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff814e869c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
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
In fs/kernfs/dir.c (ffffffff81437e89)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff814d5d1d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff814e56fe)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff8150170b)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81541fdc)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
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
In fs/kernfs/dir.c (ffffffff814b2c2b)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81562e52)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff815736dc)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff81592aeb)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff815d9dbc)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
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
In fs/kernfs/dir.c (ffffffff8154985a)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81605922)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff81618ccc)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff8163a51b)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81688891)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
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
In fs/kernfs/dir.c (ffffffff8158142a)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8163d832)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff81650d8c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff8167297b)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff816c1ff4)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
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
In fs/kernfs/dir.c (ffffffff815b9eea)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81676da2)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/unicode/utf8-core.c (ffffffff8168a36c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/efivarfs/super.c (ffffffff816ae9fb)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
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
In fs/kernfs/dir.c (ffff80001045165c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffff8000104efd7c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffff80001051c31c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffff80001055c7a0)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (c0614580)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (c06ad81c)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (c06d8a24)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (c0710f64)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (c000000000569df4)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (c00000000062f110)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In security/selinux/ss/policydb.c (c0000000006bbfa0)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/namei.c (ffffffe0002633d0)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_common
  - fs/namei.c:hashlen_string
```
```
In fs/kernfs/dir.c (ffffffe0002e4794)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffe00035fbc4)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In security/selinux/ss/policydb.c (ffffffe0003b3486)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff8137b647)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff814075b0)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8142e5ad)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81465c97)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff8136c117)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813f8030)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8141f02d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff814566c7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff81379117)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81404930)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8142a74d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81461d37)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
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
In fs/kernfs/dir.c (ffffffff8138cbc7)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8141a530)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/efivarfs/super.c (ffffffff8144160d)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/selinux/ss/policydb.c (ffffffff81479537)
Location: include/linux/stringhash.h:43
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:filenametr_hash
```
</details>
</li>
</ul>

## Differences
