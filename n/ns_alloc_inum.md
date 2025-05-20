# Function: <code>ns_alloc_inum</code>

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
In kernel/cgroup.c (ffffffff81119ae5)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8111dd29)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8111efa0)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8111f9e4)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff8122b6da)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8132e9ee)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff8170fd16)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup.c (ffffffff811218f6)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81125bf9)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81126f00)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811279e2)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff81253e4a)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff81363680)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81777656)
Location: include/linux/proc_ns.h:64
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup.c (ffffffff81129ec0)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - kernel/cgroup.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8112f639)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81130a25)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8113169c)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff81267155)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff81379e89)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff817a46d6)
Location: include/linux/proc_ns.h:66
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff81128ed6)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81130bb7)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81132066)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81132b9b)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812749a5)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8138da95)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff817c2876)
Location: include/linux/proc_ns.h:68
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff81135b6a)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8113db08)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8113ede5)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8113f988)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812972d5)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff813b2eb4)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff8183c1b6)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff8114446c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8114c4a9)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8114d729)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8114e2a6)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812bd4c5)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff813e35e4)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81886922)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff8114ff7c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811590c9)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115a3e9)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115af86)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812d27d5)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff813fdf54)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff818a7012)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff8115be7c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811657fe)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81166ab7)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81167636)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812efa32)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8142a584)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff818f2712)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff81167a9c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811716be)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81172977)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811734f6)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff81301502)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff814442b4)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81924675)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff81159c26)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff811793f7)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811832eb)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811847d7)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81184fd8)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff8133abcf)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff81494ee5)
Location: include/linux/proc_ns.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f7eb5)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff81155c3b)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:clone_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff8117610b)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811801df)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81181827)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81182147)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff81346dfc)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff814b2875)
Location: include/linux/proc_ns.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff819f7905)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff8115721a)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff81176c83)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811813c4)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8118298d)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81183297)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff8134d2fc)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff814b8ad2)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff819dda85)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff8117c06a)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff8119e503)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811a9334)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff811aa95d)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811ab351)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff8139b2cc)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff81511302)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81a8dd85)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff811b17b9)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff811ce934)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff811da47f)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff811dbfc7)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811dcac2)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff8141eb33)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff815a3135)
Location: include/linux/proc_ns.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81c03925)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff811f2509)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff812121b4)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8121fa3f)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81221827)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81222422)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff814ab5a3)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8164cce5)
Location: include/linux/proc_ns.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81db2f95)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff81206c89)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff81227af4)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81235c2f)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff81237cdc)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81238a53)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff814e03a3)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff816854f1)
Location: include/linux/proc_ns.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81e23565)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/time/namespace.c (ffffffff8121de99)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/time/namespace.c:copy_time_ns
```
```
In kernel/cgroup/namespace.c (ffffffff8123f904)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8124f8af)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/utsname.c:clone_uts_ns
```
```
In kernel/user_namespace.c (ffffffff812517dc)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81252723)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - kernel/pid_namespace.c:create_pid_namespace
```
```
In fs/namespace.c (ffffffff81513664)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff816c1911)
Location: include/linux/proc_ns.h:67
Inline: True
```
```
In net/core/net_namespace.c (ffffffff81ee14c5)
Location: include/linux/proc_ns.h:67
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffff8000101da390)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffff8000101e52dc)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffff8000101e6900)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffff8000101e782c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffff8000103b4cf0)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffff80001052cce0)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffff800010bc0094)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (c041cbf8)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0425b88)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c0426ffc)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c0427c1c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (c0592a1c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (c06e55dc)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (c0cdbc10)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (c000000000247618)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (c0000000002556e8)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (c000000000257088)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (c000000000258128)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (c0000000004b0c20)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (c000000000678ce0)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (c000000000c996dc)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffe000152a90)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffe00015afb8)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffe00015c1b4)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffe00015ccf2)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffe000277430)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffe00038ebee)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffe00074d9aa)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff811600bc)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81169cde)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8116af97)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8116bb16)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812f9ae2)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8143c894)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff818c4675)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff81153326)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8115cede)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff8115e197)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff8115ed16)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812ea702)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8142d304)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff8187e5b5)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff8115de8c)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff81167aae)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81168d67)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff811698e6)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff812f78d2)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff81438a34)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81915675)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
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
In kernel/cgroup/namespace.c (ffffffff8116b0f7)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
```
In kernel/utsname.c (ffffffff8117518e)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
```
In kernel/user_namespace.c (ffffffff81176457)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/user_namespace.c:create_user_ns
```
```
In kernel/pid_namespace.c (ffffffff81177006)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - kernel/pid_namespace.c:copy_pid_ns
```
```
In fs/namespace.c (ffffffff81308be2)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - fs/namespace.c:alloc_mnt_ns
```
```
In ipc/namespace.c (ffffffff8144fba4)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - ipc/namespace.c:copy_ipcs
```
```
In net/core/net_namespace.c (ffffffff81936855)
Location: include/linux/proc_ns.h:69
Inline: True
Inline callers:
  - net/core/net_namespace.c:net_ns_net_init
```
</details>
</li>
</ul>

## Differences
