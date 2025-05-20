# Function: <code>sema_init</code>

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
In kernel/printk/printk.c (ffffffff810d899f)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In drivers/acpi/osl.c (ffffffff8147a4b0)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff8173850c)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/printk/printk.c (ffffffff810dd43c)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In drivers/acpi/osl.c (ffffffff814c8a68)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff817a4801)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/printk/printk.c (ffffffff810e3a67)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
```
```
In drivers/acpi/osl.c (ffffffff814ea9ac)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff817d3271)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In drivers/acpi/osl.c (ffffffff814f6826)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff817f25be)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In drivers/acpi/osl.c (ffffffff8153763d)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff8186db84)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In drivers/acpi/osl.c (ffffffff8156d1bd)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff818becf4)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff811796e4)
Location: include/linux/semaphore.h:32
Inline: True
```
```
In fs/pstore/platform.c (ffffffff813eed1a)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff81584d78)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff818e7ae5)
Location: include/linux/semaphore.h:32
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff811864cc)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff8141afda)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff815b5989)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff81937465)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff8119241b)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff81434e2a)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff815d6bb9)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff8196a325)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff811a65f4)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:init_listener
```
```
In fs/pstore/platform.c (ffffffff81484bd2)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff816808e9)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e5a5)
Location: include/linux/semaphore.h:31
Inline: True
```
```
In net/core/netpoll.c (ffffffff81a3e1cc)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff811a3ae0)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:init_listener
```
```
In fs/pstore/platform.c (ffffffff814a2202)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff8169f3d9)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173b525)
Location: include/linux/semaphore.h:31
Inline: True
```
```
In drivers/md/dm.c (ffffffff8197ea1a)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81a40f72)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff811a54cb)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff814a82a2)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff81682089)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171f075)
Location: include/linux/semaphore.h:31
Inline: True
```
```
In drivers/md/dm.c (ffffffff8196286a)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81a25c2e)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff811cec1b)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff815005c2)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff816f71b9)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179de95)
Location: include/linux/semaphore.h:31
Inline: True
```
```
In drivers/md/dm.c (ffffffff81a09aa2)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81ada98e)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff81202d7c)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In drivers/acpi/osl.c (ffffffff818240b4)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d785f)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/md/dm.c (ffffffff81b713c5)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81c5c09d)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff8124abdc)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In drivers/acpi/osl.c (ffffffff81955464)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a29e0f)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/md/dm.c (ffffffff81d0e207)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81e12548)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff81261edc)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In drivers/acpi/osl.c (ffffffff8199b864)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a73591)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/md/dm.c (ffffffff81d77807)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81e85d88)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In drivers/acpi/osl.c (ffffffff819e3db4)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac56f0)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
```
```
In drivers/md/dm.c (ffffffff81e2ea37)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
```
In net/core/netpoll.c (ffffffff81f47d9a)
Location: include/linux/semaphore.h:37
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffff800010209c5c)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffff80001051adac)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffff8000107640fc)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In drivers/firmware/ti_sci.c (ffff800010b51360)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/firmware/ti_sci.c:ti_sci_probe
```
```
In net/core/netpoll.c (ffff800010c106a4)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In arch/arm/mach-vexpress/spc.c (c151b2ac)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - arch/arm/mach-vexpress/spc.c:ve_spc_init
```
```
In kernel/seccomp.c (c0448c20)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (c06d51c4)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/firmware/tegra/bpmp.c (c0c42330)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_probe
```
```
In net/core/netpoll.c (c0d28450)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In arch/powerpc/platforms/powernv/opal-async.c (c00000000135bb14)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal-async.c:opal_async_comp_init
```
```
In kernel/seccomp.c (c000000000287040)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (c000000000664c1c)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In net/core/netpoll.c (c000000000cfcc40)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffe00016bc86)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffe000383dbc)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In net/core/netpoll.c (ffffffe00078cab4)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff8118aa3b)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff8142d40a)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff815ca346)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff8190a2f5)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff8117db65)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff8141de8a)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff815b33c1)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff818c41a5)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff8118880b)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff814295aa)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff815cae99)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff8195b325)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
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
In kernel/seccomp.c (ffffffff81196179)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In fs/pstore/platform.c (ffffffff81440463)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_register
```
```
In drivers/acpi/osl.c (ffffffff815e4d39)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
```
```
In net/core/netpoll.c (ffffffff8197d545)
Location: include/linux/semaphore.h:31
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
</details>
</li>
</ul>

## Differences
