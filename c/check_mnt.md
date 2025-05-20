# Function: <code>check_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122e09e)
Location: fs/namespace.c:783
Inline: True
Inline callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:our_mnt
  - fs/namespace.c:mnt_may_suid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81258c2d)
Location: fs/namespace.c:783
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126c0dd)
Location: fs/namespace.c:784
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812798bd)
Location: fs/namespace.c:785
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129c2ee)
Location: fs/namespace.c:845
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:SyS_oldumount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c282d)
Location: fs/namespace.c:855
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d7acd)
Location: fs/namespace.c:767
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f5fad)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81307b2d)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134100d)
Location: fs/namespace.c:791
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134d0fd)
Location: fs/namespace.c:791
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81353cdd)
Location: fs/namespace.c:805
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a212d)
Location: fs/namespace.c:807
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:mount_setattr_prepare
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81425bfd)
Location: fs/namespace.c:850
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814b240d)
Location: fs/namespace.c:961
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e745d)
Location: fs/namespace.c:870
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151b2ed)
Location: fs/namespace.c:858
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:clone_private_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:path_umount
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103bb020)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0598dac)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
  - fs/namespace.c:__do_loopback
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b89cc)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027d0fa)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130010d)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0d2d)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fdefd)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130f23d)
Location: fs/namespace.c:775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_may_suid
  - fs/namespace.c:our_mnt
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:is_current_mnt_ns
```
</details>
</li>
</ul>

## Differences
