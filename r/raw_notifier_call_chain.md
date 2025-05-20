# Function: <code>raw_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1570)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - kernel/time/timekeeping.c:timekeeping_update
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810a1570-ffffffff810a1588: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4c90)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_update_state
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810a4c90-ffffffff810a4ca8: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa8f0)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/switchdev/switchdev.c:call_switchdev_notifiers
```
**Symbols:**

```
ffffffff810aa8f0-ffffffff810aa908: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7470)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810a7470-ffffffff810a7488: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adbf0)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810adbf0-ffffffff810adc08: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4a60)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810b4a60-ffffffff810b4a78: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdbb0)
Location: kernel/notifier.c:398
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810bdbb0-ffffffff810bdbc8: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3b70)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810c3b70-ffffffff810c3b88: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccc80)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810ccc80-ffffffff810ccc98: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6da0)
Location: kernel/notifier.c:365
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810d6da0-ffffffff810d6dfb: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1830)
Location: kernel/notifier.c:407
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810d1830-ffffffff810d188b: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3410)
Location: kernel/notifier.c:407
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810d3410-ffffffff810d346b: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e65a0)
Location: kernel/notifier.c:388
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810e65a0-ffffffff810e65fb: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811003c0)
Location: kernel/notifier.c:452
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff811003c0-ffffffff81100425: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811252a0)
Location: kernel/notifier.c:452
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff811252a0-ffffffff81125305: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811328f0)
Location: kernel/notifier.c:458
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/base/power/domain.c:_genpd_power_on
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff811328f0-ffffffff81132917: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d800)
Location: kernel/notifier.c:458
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/pmdomain/core.c:_genpd_power_off
  - drivers/pmdomain/core.c:_genpd_power_off
  - drivers/pmdomain/core.c:_genpd_power_on
  - drivers/pmdomain/core.c:_genpd_power_on
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff8113d800-ffffffff8113d827: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bac0)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffff80001012bac0-ffff80001012bb0c: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037bf0c)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_resume_noirq
  - drivers/clk/renesas/renesas-cpg-mssr.c:cpg_mssr_suspend_noirq
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
c037bf0c-c037bf3c: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174630)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/video/console/dummycon.c:dummycon_putc
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
c000000000174630-c00000000017464c: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e078a)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffe0000e078a-ffffffe0000e07c8: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7000)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810c7000-ffffffff810c7018: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5820)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810b5820-ffffffff810b5838: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6550)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810c6550-ffffffff810c6568: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int raw_notifier_call_chain(struct raw_notifier_head *nh, long unsigned int val, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ce960)
Location: kernel/notifier.c:400
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_update
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_putcs
  - drivers/video/console/dummycon.c:dummycon_putc
  - drivers/xen/manage.c:do_suspend
  - drivers/extcon/extcon.c:extcon_sync
  - drivers/extcon/extcon.c:extcon_sync
  - net/core/dev.c:call_netdevice_notifiers_info
```
**Symbols:**

```
ffffffff810ce960-ffffffff810ce978: raw_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
