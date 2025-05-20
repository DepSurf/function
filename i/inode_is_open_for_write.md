# Function: <code>inode_is_open_for_write</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fde8a)
Location: include/linux/fs.h:2888
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff8131492d)
Location: include/linux/fs.h:2888
Inline: True
```
```
In security/integrity/ima/ima_main.c (ffffffff8146e90d)
Location: include/linux/fs.h:2888
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ebf4)
Location: include/linux/fs.h:2894
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff813399ba)
Location: include/linux/fs.h:2894
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff81393c4f)
Location: include/linux/fs.h:2894
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8139ef11)
Location: include/linux/fs.h:2894
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff8149c1fa)
Location: include/linux/fs.h:2894
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff813319d5)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81351f0a)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff813ac5ef)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813b7d31)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff814b62ec)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8136c42a)
Location: include/linux/fs.h:2998
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff8139897a)
Location: include/linux/fs.h:2998
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff813f88a7)
Location: include/linux/fs.h:2998
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8140335f)
Location: include/linux/fs.h:2998
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff81515523)
Location: include/linux/fs.h:2998
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81379d52)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff813aa45a)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff8140af9b)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff81415df8)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff81532ada)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8138089b)
Location: include/linux/fs.h:3086
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff813b1921)
Location: include/linux/fs.h:3086
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff8141115b)
Location: include/linux/fs.h:3086
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8141c323)
Location: include/linux/fs.h:3086
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff8153ad95)
Location: include/linux/fs.h:3086
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/khugepaged.c (ffffffff8134efc2)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd6f5)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81401611)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff81463f74)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8146f725)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff815997a2)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/khugepaged.c (ffffffff813c5b40)
Location: include/linux/fs.h:2840
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456e37)
Location: include/linux/fs.h:2840
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81475936)
Location: include/linux/fs.h:2840
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff814e3482)
Location: include/linux/fs.h:2840
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff814f0181)
Location: include/linux/fs.h:2840
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff8163e4f1)
Location: include/linux/fs.h:2840
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/khugepaged.c (ffffffff8144a4fa)
Location: include/linux/fs.h:2994
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e5e06)
Location: include/linux/fs.h:2994
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81507e36)
Location: include/linux/fs.h:2994
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff8157c962)
Location: include/linux/fs.h:2994
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff8158a2da)
Location: include/linux/fs.h:2994
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff816f611d)
Location: include/linux/fs.h:2994
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/khugepaged.c (ffffffff8148082c)
Location: include/linux/fs.h:2608
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151c837)
Location: include/linux/fs.h:2608
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81541280)
Location: include/linux/fs.h:2608
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b3d62)
Location: include/linux/fs.h:2608
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff815c0a7e)
Location: include/linux/fs.h:2608
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff817302cb)
Location: include/linux/fs.h:2608
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/khugepaged.c (ffffffff814ae246)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
```
```
In fs/notify/fanotify/fanotify_user.c (ffffffff81550d76)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81576762)
Location: include/linux/fs.h:2892
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815ecb77)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff815fa696)
Location: include/linux/fs.h:2892
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff81770caf)
Location: include/linux/fs.h:2892
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
In fs/notify/fanotify/fanotify_user.c (ffff8000103eed10)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffff80001041400c)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffff800010480d2c)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffff80001048eb14)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae6d8)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (c05c5dc4)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/locks.c (c05e0178)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (c0641e18)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c064f7dc)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (c075dd04)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (c0000000004f7714)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (c000000000522440)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (c0000000005a5110)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (c0000000005b4c3c)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (c00000000072d53c)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a2c38)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
```
In fs/locks.c (ffffffe0002bb8f4)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffe000309ae8)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffe0003134a2)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f6844)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81329fb5)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff8134a4ea)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff813a4bcf)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813b0311)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff814ae8cc)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff8131ab55)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff8133b1ca)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff8139565f)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813a0da1)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff8149f2ec)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81327a85)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff81347fba)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff813a242f)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813adb71)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff814aa96c)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In fs/notify/fanotify/fanotify_user.c (ffffffff81339ea5)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
```
In fs/locks.c (ffffffff8135b3ca)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/locks.c:check_conflicting_open
```
```
In fs/ext4/inode.c (ffffffff813b6afd)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_update_reserve_space
```
```
In fs/ext4/mballoc.c (ffffffff813c2531)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_initialize_context
```
```
In security/integrity/ima/ima_main.c (ffffffff814c33ac)
Location: include/linux/fs.h:2956
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
</ul>

## Differences
