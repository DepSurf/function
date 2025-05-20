# Function: <code>raw_notifier_chain_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1510)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:unregister_cpu_notifier
  - kernel/cpu.c:__unregister_cpu_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_interest
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/core/dev.c:unregister_netdevice_notifier
```
**Symbols:**

```
ffffffff810a1510-ffffffff810a1559: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4c30)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/cpu.c:__unregister_cpu_notifier
  - kernel/cpu.c:unregister_cpu_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810a4c30-ffffffff810a4c79: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa890)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/switchdev/switchdev.c:unregister_switchdev_notifier
```
**Symbols:**

```
ffffffff810aa890-ffffffff810aa8d9: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7410)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810a7410-ffffffff810a7454: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adb90)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810adb90-ffffffff810adbd4: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4a00)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810b4a00-ffffffff810b4a49: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdb50)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810bdb50-ffffffff810bdb99: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3b10)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810c3b10-ffffffff810c3b54: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccc20)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810ccc20-ffffffff810ccc64: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d67b0)
Location: kernel/notifier.c:331
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810d67b0-ffffffff810d67f4: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1360)
Location: kernel/notifier.c:376
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810d1360-ffffffff810d13a4: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d2f40)
Location: kernel/notifier.c:376
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810d2f40-ffffffff810d2f84: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6080)
Location: kernel/notifier.c:357
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810e6080-ffffffff810e60c4: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810fff00)
Location: kernel/notifier.c:421
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810fff00-ffffffff810fff58: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81124d50)
Location: kernel/notifier.c:421
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff81124d50-ffffffff81124da8: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132c00)
Location: kernel/notifier.c:427
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/base/power/domain.c:dev_pm_genpd_remove_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff81132c00-ffffffff81132c18: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113db10)
Location: kernel/notifier.c:427
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_remove_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_notifier_dev_net
  - net/core/dev.c:unregister_netdevice_notifier_net
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff8113db10-ffffffff8113db28: raw_notifier_chain_unregister (STB_GLOBAL)
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
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012b9e8)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffff80001012b9e8-ffff80001012ba60: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037be74)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
c037be74-c037bee0: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c0000000001745b0)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
c0000000001745b0-c000000000174610: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e06e6)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffe0000e06e6-ffffffe0000e0740: raw_notifier_chain_unregister (STB_GLOBAL)
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
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6fa0)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810c6fa0-ffffffff810c6fe4: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b57c0)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810b57c0-ffffffff810b5804: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c64f0)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810c64f0-ffffffff810c6534: raw_notifier_chain_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int raw_notifier_chain_unregister(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ce900)
Location: kernel/notifier.c:366
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_unregister_notifier
  - drivers/video/console/dummycon.c:dummycon_unregister_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_unregister
  - drivers/extcon/extcon.c:extcon_unregister_notifier_all
  - drivers/extcon/extcon.c:extcon_unregister_notifier
  - net/core/dev.c:unregister_netdevice_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810ce900-ffffffff810ce944: raw_notifier_chain_unregister (STB_GLOBAL)
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
