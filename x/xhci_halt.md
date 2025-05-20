# Function: <code>xhci_halt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164cde0)
Location: drivers/usb/host/xhci.c:107
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8164cde0-ffffffff8164ce9c: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ad710)
Location: drivers/usb/host/xhci.c:108
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff816ad710-ffffffff816ad7c7: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816db9f0)
Location: drivers/usb/host/xhci.c:108
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
```
**Symbols:**

```
ffffffff816db9f0-ffffffff816dbaa4: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f00a0)
Location: drivers/usb/host/xhci.c:108
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff816f00a0-ffffffff816f0154: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175c260)
Location: drivers/usb/host/xhci.c:98
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8175c260-ffffffff8175c314: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179cc30)
Location: drivers/usb/host/xhci.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8179cc30-ffffffff8179ccf2: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c3010)
Location: drivers/usb/host/xhci.c:113
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817c3010-ffffffff817c30d2: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81807cde-ffffffff81807cfd: xhci_halt.cold (STB_LOCAL)
ffffffff81802d10-ffffffff81802d8d: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81838b8d-ffffffff81838bac: xhci_halt.cold (STB_LOCAL)
ffffffff81833c10-ffffffff81833c8d: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff8190b478-ffffffff8190b497: xhci_halt.cold (STB_LOCAL)
ffffffff81906ae0-ffffffff81906b5c: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c20ea5-ffffffff81c20ec4: xhci_halt.cold (STB_LOCAL)
ffffffff8190f280-ffffffff8190f2fc: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:110
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c12eea-ffffffff81c12f09: xhci_halt.cold (STB_LOCAL)
ffffffff818f2850-ffffffff818f28cf: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:110
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d1fc6c-ffffffff81d1fc8b: xhci_halt.cold (STB_LOCAL)
ffffffff8198fac0-ffffffff8198fb3f: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:110
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81eeb82d-ffffffff81eeb84c: xhci_halt.cold (STB_LOCAL)
ffffffff81aec020-ffffffff81aec0ab: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c787c0)
Location: drivers/usb/host/xhci.c:110
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81c787c0-ffffffff81c78873: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdf840)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81cdf840-ffffffff81cdf8f3: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d94900)
Location: drivers/usb/host/xhci.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run_finished
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
```
**Symbols:**

```
ffffffff81d94900-ffffffff81d949b3: xhci_halt (STB_GLOBAL)
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
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a71038)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffff800010a71038-ffff800010a710d0: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b44e50)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c0b44e50-c0b44edc: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b45d40)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
c000000000b45d40-c000000000b45df8: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006896b0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffe0006896b0-ffffffe000689742: xhci_halt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817f0f3d-ffffffff817f0f5c: xhci_halt.cold (STB_LOCAL)
ffffffff817ebfe0-ffffffff817ec05d: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff817b60d3-ffffffff817b60f2: xhci_halt.cold (STB_LOCAL)
ffffffff817b10f0-ffffffff817b116d: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff8182da0d-ffffffff8182da2c: xhci_halt.cold (STB_LOCAL)
ffffffff81828a90-ffffffff81828b0d: xhci_halt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_halt(struct xhci_hcd *xhci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:111
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_shutdown
  - drivers/usb/host/xhci.c:xhci_stop
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
**Symbols:**

```
ffffffff81847af6-ffffffff81847b15: xhci_halt.cold (STB_LOCAL)
ffffffff81842a50-ffffffff81842acd: xhci_halt (STB_GLOBAL)
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
