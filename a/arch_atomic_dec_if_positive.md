# Function: <code>arch_atomic_dec_if_positive</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff810d9e12)
Location: include/linux/atomic-arch-fallback.h:1168
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810da105)
Location: include/linux/atomic-arch-fallback.h:1168
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff81160ef6)
Location: include/linux/atomic-arch-fallback.h:1168
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (ffffffff817cf585)
Location: include/linux/atomic-arch-fallback.h:1168
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff8189b635)
Location: include/linux/atomic-arch-fallback.h:1168
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (ffffffff819ea051)
Location: include/linux/atomic-arch-fallback.h:1168
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (ffffffff810d4fc2)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d58e8)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff8115f931)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (ffffffff817e3b85)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff818aa3d5)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
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
In kernel/ucount.c (ffffffff810d6c9f)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d7561)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff811601f1)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (ffffffff817c7fc5)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff8188d5e5)
Location: include/linux/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
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
In kernel/kmod.c (ffffffff810eae11)
Location: include/linux/atomic/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff811853a1)
Location: include/linux/atomic/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff814b1089)
Location: include/linux/atomic/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff818523f5)
Location: include/linux/atomic/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff81920b45)
Location: include/linux/atomic/atomic-arch-fallback.h:1238
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
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
In kernel/kmod.c (ffffffff81105c73)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module/main.c (ffffffff8118ae39)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff81539b34)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff81998265)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
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
In kernel/kmod.c (ffffffff8112b78f)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module/main.c (ffffffff811c74f9)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff815d8064)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b092b5)
Location: include/linux/atomic/atomic-arch-fallback.h:1322
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
