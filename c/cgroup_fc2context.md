# Function: <code>cgroup_fc2context</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811575df)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d8a2)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8116324f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811694b2)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8117135f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8117b2a5)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8116e15f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178175)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8116ed4f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81178cf5)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff81194fdf)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811a0625)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff811c5c9f)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff811d0d75)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8120844f)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff812148d5)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8121dbef)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8122a1f5)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8123585f)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81242095)
Location: kernel/cgroup/cgroup-internal.h:60
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffff8000101d49c4)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffff8000101dc6f4)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (c0417584)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (c041e998)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (c00000000023fff4)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (c00000000024a3d0)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffe00014de08)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffe00015467a)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8115b86f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81161ad2)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8114eb5f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff81154d32)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff8115963f)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8115f8a2)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
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
In kernel/cgroup/cgroup.c (ffffffff811666af)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cpuset_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_get_tree
  - kernel/cgroup/cgroup.c:cgroup_fs_context_free
  - kernel/cgroup/cgroup.c:cgroup_do_get_tree
  - kernel/cgroup/cgroup.c:cgroup_reconfigure
  - kernel/cgroup/cgroup.c:cgroup2_parse_param
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8116cb42)
Location: kernel/cgroup/cgroup-internal.h:61
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
  - kernel/cgroup/cgroup-v1.c:cgroup1_reconfigure
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
```
</details>
</li>
</ul>

## Differences
