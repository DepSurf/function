# Function: <code>split_fs_names</code>

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
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff8329a134)
Location: init/do_mounts.c:342
Inline: True
Direct callers:
  - init/do_mounts.c:mount_root
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff8329a134-ffffffff8329a170: split_fs_names.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff8344824c)
Location: init/do_mounts.c:341
Inline: True
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff8344824c-ffffffff83448292: split_fs_names.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff83e61e30)
Location: init/do_mounts.c:341
Inline: True
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff83e61e30-ffffffff83e61ea2: split_fs_names.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff83682250)
Location: init/do_mounts.c:106
Inline: True
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_root_generic
```
**Symbols:**

```
ffffffff83682250-ffffffff836822c2: split_fs_names.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff838b12e0)
Location: init/do_mounts.c:132
Inline: True
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_root_generic
```
**Symbols:**

```
ffffffff838b12e0-ffffffff838b1352: split_fs_names.constprop.0 (STB_LOCAL)
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
