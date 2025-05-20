# Function: <code>old_encode_dev</code>

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
In kernel/acct.c (ffffffff8110ba83)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (0)
Location: include/linux/kdev_t.h:28
Inline: True
```
```
In fs/compat.c (0)
Location: include/linux/kdev_t.h:28
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/linux/kdev_t.h:28
Inline: True
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
In kernel/acct.c (ffffffff811132e3)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff8123818f)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/compat.c (ffffffff8128f5dd)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/compat.c:cp_compat_stat
  - fs/compat.c:cp_compat_stat
```
```
In fs/ext4/inode.c (ffffffff812c7720)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff8111a9f3)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff8124ae4f)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/compat.c (ffffffff812a45cd)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/compat.c:cp_compat_stat
  - fs/compat.c:cp_compat_stat
```
```
In fs/ext4/inode.c (ffffffff812dd2bf)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff8111c59f)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff81257209)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff812ff0b1)
Location: include/linux/kdev_t.h:28
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff81127cbf)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff81279459)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff81323861)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff81135ac4)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff8129ff96)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff81351d8c)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff81141254)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812b4f76)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff81369851)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff8114c676)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812d1d0d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff81392ccc)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff81158346)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812e389d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff813ab640)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff811692b5)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff8131a45d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff813f7aee)
Location: include/linux/kdev_t.h:29
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
In kernel/acct.c (ffffffff8116598f)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff81325aed)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff8140ac0f)
Location: include/linux/kdev_t.h:29
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
In kernel/acct.c (ffffffff811666c3)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff8132bc1d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff81410dd8)
Location: include/linux/kdev_t.h:29
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
In kernel/acct.c (ffffffff8118be83)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff8137938d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff81463a59)
Location: include/linux/kdev_t.h:29
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
In kernel/acct.c (ffffffff811bb257)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff813f8318)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff814e2782)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
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
In kernel/acct.c (ffffffff811fd047)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff81481802)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff8157bb72)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
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
In kernel/acct.c (ffffffff812121e7)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff814b6402)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff815b2f6a)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
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
In kernel/acct.c (ffffffff81229878)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (ffffffff814e8732)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff815ebd60)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_fill_raw_inode
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97844)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_free
```
```
In drivers/gpu/drm/drm_ioctl.c (ffffffff81c9e8fe)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb92ce)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:drm_compat_ioctl
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
In kernel/acct.c (ffff8000101c7be8)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffff80001038acbc)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
```
```
In fs/ext4/inode.c (ffff80001047feec)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (c040e6dc)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In fs/stat.c (c05729ac)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_new_stat
  - fs/stat.c:cp_new_stat
```
```
In fs/ext4/inode.c (c064125c)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (c00000000022fd64)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (c00000000048279c)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
```
```
In fs/ext4/inode.c (c0000000005a3f28)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffe0001479fa)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/ext4/inode.c (ffffffe000308dfe)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff81150966)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812dbe7d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff813a3c20)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff81143c16)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812ccafd)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff813946b0)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff8114e816)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812d9c8d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff813a1480)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
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
In kernel/acct.c (ffffffff8115b5f6)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/stat.c (ffffffff812eab9d)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_compat_stat
  - fs/stat.c:cp_old_stat
  - fs/stat.c:cp_old_stat
```
```
In fs/ext4/inode.c (ffffffff813b6091)
Location: include/linux/kdev_t.h:29
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_do_update_inode
```
</details>
</li>
</ul>

## Differences
