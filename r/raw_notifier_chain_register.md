# Function: <code>raw_notifier_chain_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a14d0)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/cpu.c:register_cpu_notifier
  - kernel/cpu.c:__register_cpu_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier
  - drivers/extcon/extcon.c:extcon_register_interest
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810a14d0-ffffffff810a1508: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4bf0)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/cpu.c:__register_cpu_notifier
  - kernel/cpu.c:register_cpu_notifier
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810a4bf0-ffffffff810a4c28: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aa850)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - net/core/dev.c:register_netdevice_notifier
  - net/switchdev/switchdev.c:register_switchdev_notifier
```
**Symbols:**

```
ffffffff810aa850-ffffffff810aa888: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a73d0)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810a73d0-ffffffff810a7408: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810adb50)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810adb50-ffffffff810adb88: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b49c0)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810b49c0-ffffffff810b49f8: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bdb10)
Location: kernel/notifier.c:347
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810bdb10-ffffffff810bdb48: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3cc0)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810c3cc0-ffffffff810c3cd0: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ccdd0)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810ccdd0-ffffffff810ccde0: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d69d0)
Location: kernel/notifier.c:314
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810d69d0-ffffffff810d69e0: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d14d0)
Location: kernel/notifier.c:359
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810d14d0-ffffffff810d14e0: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d30b0)
Location: kernel/notifier.c:359
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810d30b0-ffffffff810d30c0: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6380)
Location: kernel/notifier.c:340
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810e6380-ffffffff810e63cc: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100430)
Location: kernel/notifier.c:404
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff81100430-ffffffff81100496: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125320)
Location: kernel/notifier.c:404
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/char/random.c:execute_with_initialized_rng
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff81125320-ffffffff81125386: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff811325b0)
Location: kernel/notifier.c:410
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/char/random.c:execute_with_initialized_rng
  - drivers/base/power/domain.c:dev_pm_genpd_add_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff811325b0-ffffffff811325cc: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113d4c0)
Location: kernel/notifier.c:410
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/pmdomain/core.c:dev_pm_genpd_add_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/char/random.c:execute_with_initialized_rng
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:__register_netdevice_notifier_net
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff8113d4c0-ffffffff8113d4dc: raw_notifier_chain_register (STB_GLOBAL)
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
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012bc28)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/rcar-gen3-cpg.c:rcar_gen3_cpg_clk_register
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffff80001012bc28-ffff80001012bc5c: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c0bc)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/clk/renesas/clk-div6.c:cpg_div6_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
c037c0bc-c037c0d8: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174840)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
c000000000174840-c000000000174854: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e08a2)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffe0000e08a2-ffffffe0000e08d4: raw_notifier_chain_register (STB_GLOBAL)
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
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c7150)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810c7150-ffffffff810c7160: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5970)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810b5970-ffffffff810b5980: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c66a0)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810c66a0-ffffffff810c66b0: raw_notifier_chain_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int raw_notifier_chain_register(struct raw_notifier_head *nh, struct notifier_block *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cea50)
Location: kernel/notifier.c:349
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:pvclock_gtod_register_notifier
  - drivers/video/console/dummycon.c:dummycon_register_output_notifier
  - drivers/xen/manage.c:xen_resume_notifier_register
  - drivers/extcon/extcon.c:extcon_register_notifier_all
  - drivers/extcon/extcon.c:extcon_register_notifier
  - net/core/dev.c:register_netdevice_notifier
```
**Symbols:**

```
ffffffff810cea50-ffffffff810cea60: raw_notifier_chain_register (STB_GLOBAL)
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
