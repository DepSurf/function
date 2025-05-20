# Function: <code>file_open_root_mnt</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/usermode_driver.c (ffffffff810ea7f0)
Location: include/linux/fs.h:2747
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_load_blob
```
```
In fs/proc/proc_sysctl.c (ffffffff81431213)
Location: include/linux/fs.h:2747
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:process_sysctl_arg
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
In kernel/usermode_driver.c (ffffffff811055ea)
Location: include/linux/fs.h:2623
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_load_blob
```
```
In fs/proc/proc_sysctl.c (ffffffff814ab230)
Location: include/linux/fs.h:2623
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:process_sysctl_arg
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
In kernel/usermode_driver.c (ffffffff8112b0aa)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_load_blob
```
```
In fs/proc/proc_sysctl.c (ffffffff815410e0)
Location: include/linux/fs.h:2762
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:process_sysctl_arg
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
In kernel/usermode_driver.c (ffffffff8113839a)
Location: include/linux/fs.h:2356
Inline: True
Inline callers:
  - kernel/usermode_driver.c:umd_load_blob
```
```
In fs/proc/proc_sysctl.c (ffffffff81579470)
Location: include/linux/fs.h:2356
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:process_sysctl_arg
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
In fs/proc/proc_sysctl.c (ffffffff815b1ca0)
Location: include/linux/fs.h:2586
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:process_sysctl_arg
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
