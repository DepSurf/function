# Function: <code>get_mnt_ns</code>

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
In fs/namespace.c (ffffffff8122b683)
Location: fs/mount.h:103
Inline: True
Inline callers:
  - fs/namespace.c:mntns_get
  - fs/namespace.c:mnt_init
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mntns_install
```
```
In fs/proc_namespace.c (ffffffff8124f0b0)
Location: fs/mount.h:103
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff81258a1b)
Location: fs/mount.h:103
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81277830)
Location: fs/mount.h:103
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff8126becb)
Location: fs/mount.h:111
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff8128b510)
Location: fs/mount.h:111
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812796c3)
Location: fs/mount.h:112
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81298310)
Location: fs/mount.h:112
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff8129c0f3)
Location: fs/mount.h:113
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff812bb610)
Location: fs/mount.h:113
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812c2623)
Location: fs/mount.h:113
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff812e41af)
Location: fs/mount.h:113
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812d78c3)
Location: fs/mount.h:113
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff812f8e2f)
Location: fs/mount.h:113
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812f5d8a)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81319450)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff8130790a)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff8132c280)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff81340df5)
Location: fs/mount.h:121
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:copy_mnt_ns
```
```
In fs/proc_namespace.c (ffffffff81365f59)
Location: fs/mount.h:121
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff8134ceb2)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:init_mount_tree
  - fs/namespace.c:copy_mnt_ns
```
```
In fs/proc_namespace.c (ffffffff81372e20)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff81353a92)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff813797b0)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff813a1ee2)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff813c6310)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff81425981)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff8144cb91)
Location: fs/mount.h:120
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff814b2151)
Location: fs/mount.h:119
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff814db101)
Location: fs/mount.h:119
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff814e71a1)
Location: fs/mount.h:119
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff8150f6b1)
Location: fs/mount.h:119
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff8151b031)
Location: fs/mount.h:117
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81543bb1)
Location: fs/mount.h:117
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffff8000103bad90)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffff8000103e7a18)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (c0598b40)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (c05bf578)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (c0000000004b86c0)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (c0000000004ee1d0)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffe00027ac60)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffe00029c868)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812ffeea)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81324860)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812f0b0a)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81315400)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff812fdcda)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81322330)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
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
In fs/namespace.c (ffffffff8130f01a)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_get
  - fs/namespace.c:copy_mnt_ns
  - fs/namespace.c:mnt_init
```
```
In fs/proc_namespace.c (ffffffff81334092)
Location: fs/mount.h:115
Inline: True
Inline callers:
  - fs/proc_namespace.c:mounts_open_common
```
</details>
</li>
</ul>

## Differences
