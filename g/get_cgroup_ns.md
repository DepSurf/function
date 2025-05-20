# Function: <code>get_cgroup_ns</code>

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
In kernel/cgroup.c (ffffffff81111fff)
Location: include/linux/cgroup.h:594
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:copy_cgroup_ns
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
In kernel/cgroup.c (ffffffff8111971f)
Location: include/linux/cgroup.h:652
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:cgroup_mount
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
In kernel/cgroup.c (ffffffff81120eef)
Location: include/linux/cgroup.h:675
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroupns_get
  - kernel/cgroup.c:cgroupns_install
  - kernel/cgroup.c:copy_cgroup_ns
  - kernel/cgroup.c:cgroup_mount
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
In kernel/cgroup/cgroup.c (ffffffff811255f4)
Location: include/linux/cgroup.h:716
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/cgroup/namespace.c (ffffffff81128c71)
Location: include/linux/cgroup.h:716
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff811318b4)
Location: include/linux/cgroup.h:824
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/cgroup/namespace.c (ffffffff81135a51)
Location: include/linux/cgroup.h:824
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8113ffe4)
Location: include/linux/cgroup.h:832
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/cgroup/namespace.c (ffffffff811442c1)
Location: include/linux/cgroup.h:832
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8114ba54)
Location: include/linux/cgroup.h:870
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/cgroup/namespace.c (ffffffff8114fdcf)
Location: include/linux/cgroup.h:870
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff81157350)
Location: include/linux/cgroup.h:885
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115bcce)
Location: include/linux/cgroup.h:885
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff81163187)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811678ee)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8117127a)
Location: include/linux/cgroup.h:889
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811791a1)
Location: include/linux/cgroup.h:889
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8116e00a)
Location: include/linux/cgroup.h:888
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81175ec1)
Location: include/linux/cgroup.h:888
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8116ec0a)
Location: include/linux/cgroup.h:888
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81176b21)
Location: include/linux/cgroup.h:888
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff81194d93)
Location: include/linux/cgroup.h:881
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8119e3a1)
Location: include/linux/cgroup.h:881
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff811c5a31)
Location: include/linux/cgroup.h:878
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff811ce6ae)
Location: include/linux/cgroup.h:878
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff81207e51)
Location: include/linux/cgroup.h:805
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff81211f0e)
Location: include/linux/cgroup.h:805
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8121d5e1)
Location: include/linux/cgroup.h:803
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8122786e)
Location: include/linux/cgroup.h:803
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff812353e1)
Location: include/linux/cgroup.h:801
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8123f67e)
Location: include/linux/cgroup.h:801
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffff8000101d4890)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffff8000101d9fbc)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (c041746c)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c041c928)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (c00000000023fe90)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (c000000000247180)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffe00014dd36)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffe000152948)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8115b7a7)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115ff0e)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff8114ea97)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115317e)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff81159577)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8115dcde)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
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
In kernel/cgroup/cgroup.c (ffffffff811665e7)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/cgroup/namespace.c (ffffffff8116af41)
Location: include/linux/cgroup.h:887
Inline: True
Inline callers:
  - kernel/cgroup/namespace.c:cgroupns_get
  - kernel/cgroup/namespace.c:cgroupns_install
  - kernel/cgroup/namespace.c:copy_cgroup_ns
```
</details>
</li>
</ul>

## Differences
