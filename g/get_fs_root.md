# Function: <code>get_fs_root</code>

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
In fs/namei.c (ffffffff81217c34)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:follow_dotdot
  - fs/namei.c:path_init
  - fs/namei.c:link_path_walk
```
```
In fs/namespace.c (ffffffff8122ff48)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:current_chrooted
```
```
In fs/proc_namespace.c (ffffffff8124f0c4)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/proc/base.c (ffffffff8127b72b)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff8137995f)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff8123d2bf)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff81258b8d)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81277844)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8129aec0)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812a8247)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff813b2731)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff8125005f)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8126c03d)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/proc_namespace.c (ffffffff8128b524)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812afa7a)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812bdb27)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff813c98f1)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff8125bfa3)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8127982e)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81298324)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812bccbe)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812ca9c9)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff813defd6)
Location: include/linux/fs_struct.h:26
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff8127e363)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8129c25e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:SyS_pivot_root
```
```
In fs/proc_namespace.c (ffffffff812bb624)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff812e0589)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff812ef1f9)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff81405959)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff812a6ba3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff812c278d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff812e41c3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8130c7be)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8131d3ab)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff81436e99)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff812bbdd3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff812d7a2d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff812f8e43)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813220f3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8133347b)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff81453af9)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - security/apparmor/path.c:aa_path_name
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
In fs/namei.c (ffffffff812d8962)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff812f5f0d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81319466)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8134a016)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135b3b8)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff814814c5)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff812ea462)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff81307a8d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff8132c296)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813622b6)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff81373808)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff8149b1f5)
Location: include/linux/fs_struct.h:27
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
In fs/exec.c (ffffffff8131d2cc)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/exec.c:kernel_read_file_from_path_initns
```
```
In fs/namei.c (ffffffff813220d6)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff81340f6d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81365f6e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813a8321)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff813bc910)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff814f3c2b)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff8132d853)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8134d05d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff81365f0f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff81372e60)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813b9392)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff813ce3c0)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff81510d8b)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff813335a3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff81353c3d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff8136c94f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff813797ec)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff813c0285)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff813d5d30)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff8151770b)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff81380ed3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff813a208d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff813bb61f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff813c634c)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff814100b5)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff814275f0)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff8157570b)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff8140121e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff81425b5f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff81441574)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8144cbcb)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81485a5e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8149f89f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff81613213)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff8148b14e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff814b235f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff814d0504)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff814db13b)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8151931b)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8153482f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff816c5e63)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff814c1d8e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff814e73af)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff815067b4)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff8150f6e3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81550c23)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8156c8cf)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff816fec43)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff814f424e)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8151b23f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_listmount
  - fs/namespace.c:__x64_sys_listmount
  - fs/namespace.c:__do_sys_statmount
  - fs/namespace.c:__do_sys_pivot_root
```
```
In fs/kernel_read_file.c (ffffffff8153b4d4)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/kernel_read_file.c:kernel_read_file_from_path_initns
```
```
In fs/proc_namespace.c (ffffffff81543be3)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81586ab4)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff815a50cf)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff8173c1d3)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffff800010393b28)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffff8000103baf34)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__arm64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffff8000103e7a34)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffff800010428a40)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffff80001043f1f0)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffff800010591404)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (c0578554)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (c0598cf8)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
```
```
In fs/proc_namespace.c (c05bf59c)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (c05f1630)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c0603f78)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (c0742154)
Location: include/linux/fs_struct.h:27
Inline: True
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
In fs/namei.c (c000000000489e70)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (c0000000004b88ac)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
```
```
In fs/proc_namespace.c (c0000000004ee1ec)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (c000000000538c04)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (c0000000005521d0)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (c000000000705048)
Location: include/linux/fs_struct.h:27
Inline: True
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
In fs/namei.c (ffffffe000262766)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffe00027d036)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__se_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffe00029c876)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffe0002c6bd0)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffe0002d6b3a)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffe0003ded98)
Location: include/linux/fs_struct.h:27
Inline: True
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
In fs/namei.c (ffffffff812e2a42)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8130006d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81324876)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8135a896)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8136bde8)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff814937d5)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff812d3682)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff812f0c8d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81315416)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8134b53a)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8135c878)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff814841f5)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff812e0852)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff812fde5d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff81322346)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff81358366)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff813698b8)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff8148f875)
Location: include/linux/fs_struct.h:27
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
In fs/namei.c (ffffffff812efdf2)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namei.c:set_root
```
```
In fs/namespace.c (ffffffff8130f19d)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/namespace.c:current_chrooted
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
```
```
In fs/proc_namespace.c (ffffffff813340a7)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
```
In fs/coredump.c (ffffffff8136ba8f)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/proc/base.c (ffffffff8137d188)
Location: include/linux/fs_struct.h:27
Inline: True
Inline callers:
  - fs/proc/base.c:proc_root_link
```
```
In security/apparmor/path.c (ffffffff814a7785)
Location: include/linux/fs_struct.h:27
Inline: True
```
</details>
</li>
</ul>

## Differences
