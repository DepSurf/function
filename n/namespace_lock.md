# Function: <code>namespace_lock</code>

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
In fs/namespace.c (ffffffff8122bcd2)
Location: fs/namespace.c:1355
Inline: True
Inline callers:
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_mount
  - fs/namespace.c:copy_mnt_ns
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
In fs/namespace.c (ffffffff8125813d)
Location: fs/namespace.c:1355
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff8126b5cd)
Location: fs/namespace.c:1429
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff81278d9d)
Location: fs/namespace.c:1371
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff8129b7dd)
Location: fs/namespace.c:1436
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff812c18ad)
Location: fs/namespace.c:1462
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff812d6b5d)
Location: fs/namespace.c:1374
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff812f4f80)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff81306b00)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff81340460)
Location: fs/namespace.c:1441
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff8134c4b7)
Location: fs/namespace.c:1444
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff81353087)
Location: fs/namespace.c:1455
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff813a14d7)
Location: fs/namespace.c:1464
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:__do_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff81424ea5)
Location: fs/namespace.c:1505
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff814b15e5)
Location: fs/namespace.c:1610
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff814e6625)
Location: fs/namespace.c:1584
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffffffff8151a464)
Location: fs/namespace.c:1581
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:path_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:finish_automount
  - fs/namespace.c:do_set_group
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (ffff8000103ba1c8)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__arm64_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (c0597bc0)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:do_umount
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
In fs/namespace.c (c0000000004b78b8)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffe00027c398)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:__se_sys_open_tree
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff812ff0e0)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff812efd00)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff812fced0)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
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
In fs/namespace.c (ffffffff8130e230)
Location: fs/namespace.c:1391
Inline: True
Inline callers:
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:do_mount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:mnt_set_expiry
  - fs/namespace.c:finish_automount
  - fs/namespace.c:open_detached_copy
  - fs/namespace.c:lock_mount
  - fs/namespace.c:drop_collected_mounts
  - fs/namespace.c:dissolve_on_fput
  - fs/namespace.c:collect_mounts
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:__detach_mounts
```
</details>
</li>
</ul>

## Differences
