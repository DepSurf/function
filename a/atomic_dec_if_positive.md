# Function: <code>atomic_dec_if_positive</code>

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
In kernel/module.c (ffffffff811052e6)
Location: include/linux/atomic.h:544
Inline: True
Inline callers:
  - kernel/module.c:module_put
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
In kernel/module.c (ffffffff8110cbc6)
Location: include/linux/atomic.h:613
Inline: True
Inline callers:
  - kernel/module.c:module_put
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
In kernel/ucount.c (ffffffff810ad9fe)
Location: include/linux/atomic.h:613
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/module.c (ffffffff81114606)
Location: include/linux/atomic.h:613
Inline: True
Inline callers:
  - kernel/module.c:module_put
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
In kernel/kmod.c (ffffffff8109c59a)
Location: include/linux/atomic.h:636
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/ucount.c (ffffffff810aa5cf)
Location: include/linux/atomic.h:636
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/module.c (ffffffff81115213)
Location: include/linux/atomic.h:636
Inline: True
Inline callers:
  - kernel/module.c:module_put
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
In kernel/ucount.c (ffffffff810b0e2f)
Location: include/linux/atomic.h:640
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810b110c)
Location: include/linux/atomic.h:640
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff811207b3)
Location: include/linux/atomic.h:640
Inline: True
Inline callers:
  - kernel/module.c:module_put
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
In kernel/ucount.c (ffffffff810b7c3f)
Location: include/linux/atomic.h:640
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810b7f11)
Location: include/linux/atomic.h:640
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff8112ed63)
Location: include/linux/atomic.h:640
Inline: True
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
In kernel/ucount.c (ffffffff810c0d47)
Location: include/linux/atomic.h:709
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c0ffc)
Location: include/linux/atomic.h:709
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff8113a703)
Location: include/linux/atomic.h:709
Inline: True
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
In kernel/ucount.c (ffffffff810c6e2f)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c70e4)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff811460a1)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In net/core/skbuff.c (ffffffff818e73dd)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (ffffffff810cfeff)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d01b4)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff81151b81)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81713ab5)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff817d0e55)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (ffffffff819197d9)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (ffffffff810d9e12)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810da105)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff81160ef6)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (ffffffff817cf585)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff8189b635)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (ffffffff819ea051)
Location: include/asm-generic/atomic-instrumented.h:826
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
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d58e8)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff8115f931)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (ffffffff817e3b85)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff818aa3d5)
Location: include/asm-generic/atomic-instrumented.h:826
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
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d7561)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff811601f1)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (ffffffff817c7fc5)
Location: include/asm-generic/atomic-instrumented.h:826
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff8188d5e5)
Location: include/asm-generic/atomic-instrumented.h:826
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
Location: include/linux/atomic/atomic-instrumented.h:596
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff811853a1)
Location: include/linux/atomic/atomic-instrumented.h:596
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff814b1089)
Location: include/linux/atomic/atomic-instrumented.h:596
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff818523f5)
Location: include/linux/atomic/atomic-instrumented.h:596
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff81920b45)
Location: include/linux/atomic/atomic-instrumented.h:596
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
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module/main.c (ffffffff8118ae39)
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff81539b34)
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff81998265)
Location: include/linux/atomic/atomic-instrumented.h:636
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
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module/main.c (ffffffff811c74f9)
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff815d8064)
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b092b5)
Location: include/linux/atomic/atomic-instrumented.h:636
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
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
In kernel/module/main.c (ffffffff811da38e)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
```
```
In fs/ext4/orphan.c (ffffffff8160fbf4)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In drivers/base/power/wakeup.c (ffffffff81b572d5)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
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
In kernel/module/main.c (ffffffff811f003e)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - kernel/module/main.c:module_put
```
```
In kernel/seccomp.c (ffffffff81279a32)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - kernel/seccomp.c:recv_wait_event
  - kernel/seccomp.c:recv_wait_event
```
```
In fs/ext4/orphan.c (ffffffff816489b4)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_orphan_file_add
```
```
In block/bdev.c (ffffffff817a7710)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - block/bdev.c:bdev_thaw
```
```
In drivers/base/power/wakeup.c (ffffffff81baf8c5)
Location: include/linux/atomic/atomic-instrumented.h:1576
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
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
In kernel/ucount.c (ffff800010130378)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffff80001013076c)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffff8000101c1914)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (ffff800010905078)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In net/core/skbuff.c (ffff800010bb4340)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (c037fd04)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (c037fff0)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (c0408208)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (c09eeea0)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In net/core/skbuff.c (c0cd0020)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In arch/powerpc/kernel/eeh.c (c000000000045aec)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - arch/powerpc/kernel/eeh.c:eeh_dev_release
```
```
In kernel/ucount.c (c000000000179ad0)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (c000000000179eac)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (c000000000224040)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - kernel/module.c:module_put
```
```
In drivers/base/power/wakeup.c (c0000000009a3b50)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (c000000000aae990)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (c000000000c87538)
Location: arch/powerpc/include/asm/atomic.h:273
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/ucount.c (ffffffff810ca27f)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810ca534)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff8114a1a1)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816d9de5)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In net/core/skbuff.c (ffffffff818b97d9)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (ffffffff810b8a8f)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810b8d44)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff8113d451)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff816b4465)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff8177af05)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (ffffffff81873729)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (ffffffff810c97af)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810c9a64)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff81148051)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81707775)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff817c5cd5)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (ffffffff8190a7d9)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
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
In kernel/ucount.c (ffffffff810d1cef)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/ucount.c:dec_ucount
```
```
In kernel/kmod.c (ffffffff810d1fb8)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
  - kernel/kmod.c:__request_module
```
```
In kernel/module.c (ffffffff81154c78)
Location: include/linux/atomic-fallback.h:1166
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff817221a5)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:pm_system_cancel_wakeup
```
```
In drivers/vfio/vfio.c (ffffffff817dff75)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_try_dissolve_container
```
```
In net/core/skbuff.c (ffffffff8192b8d9)
Location: include/linux/atomic-fallback.h:1166
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
</details>
</li>
</ul>

## Differences
