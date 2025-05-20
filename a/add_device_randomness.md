# Function: <code>add_device_randomness</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81511890)
Location: drivers/char/random.c:759
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:__dev_open
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81511890-ffffffff815119ce: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815649e0)
Location: drivers/char/random.c:996
Inline: False
Direct callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_exit
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff815649e0-ffffffff81564ace: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81590550)
Location: drivers/char/random.c:996
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81590550-ffffffff8159063e: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a5930)
Location: drivers/char/random.c:980
Inline: False
Direct callers:
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff815a5930-ffffffff815a5a34: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160c230)
Location: drivers/char/random.c:979
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff8160c230-ffffffff8160c337: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81644940)
Location: drivers/char/random.c:1087
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81644940-ffffffff81644b04: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662b00)
Location: drivers/char/random.c:1100
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81662b00-ffffffff81662cc4: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169a000)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - drivers/firmware/efi/efi.c:efi_config_parse_tables
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff8169a000-ffffffff8169a1bf: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bcd30)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff816bcd30-ffffffff816bceef: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81771360)
Location: drivers/char/random.c:1124
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:__exit_signal
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81771360-ffffffff8177146e: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178c390)
Location: drivers/char/random.c:1124
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:__exit_signal
  - lib/random32.c:prandom_seed
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff8178c390-ffffffff8178c48a: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8176f1d0)
Location: drivers/char/random.c:1114
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:__exit_signal
  - lib/random32.c:prandom_seed
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff8176f1d0-ffffffff8176f384: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f4a10)
Location: drivers/char/random.c:1134
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:__exit_signal
  - lib/random32.c:prandom_seed
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff817f4a10-ffffffff817f4bc1: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81933bd0)
Location: drivers/char/random.c:829
Inline: False
Direct callers:
  - kernel/exit.c:__exit_signal
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_decode_cid
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81933bd0-ffffffff81933c74: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a929b0)
Location: drivers/char/random.c:917
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:__exit_signal
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_init
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_decode_cid
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81a929b0-ffffffff81a92a54: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81ade230)
Location: drivers/char/random.c:917
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:__exit_signal
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_init
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_decode_cid
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81ade230-ffffffff81ade2d4: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b31650)
Location: drivers/char/random.c:917
Inline: False
Direct callers:
  - init/main.c:do_one_initcall
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:__exit_signal
  - kernel/sys.c:__ia32_sys_setdomainname
  - kernel/sys.c:__x64_sys_setdomainname
  - kernel/sys.c:__ia32_sys_sethostname
  - kernel/sys.c:__x64_sys_sethostname
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_adjtimex
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/utsname_sysctl.c:proc_do_uts_string
  - drivers/char/random.c:add_vmfork_randomness
  - drivers/char/random.c:random_init
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_decode_cid
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:dev_set_mac_address
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81b31650-ffffffff81b316f4: add_device_randomness (STB_GLOBAL)
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
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108b1640)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffff8000108b1640-ffff8000108b190c: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a7d90)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - arch/arm/mach-omap2/id.c:__omap_feed_randpool
  - kernel/exit.c:release_task
  - drivers/soc/tegra/fuse/fuse-tegra30.c:tegra30_fuse_init
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_init
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
c09a7d90-c09a7fe4: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000945760)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
c000000000945760-c000000000945a10: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000560628)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffe000560628-ffffffe0005607f6: add_device_randomness (STB_GLOBAL)
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
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81682790)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/random.c:add_bootloader_randomness
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff81682790-ffffffff8168294f: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8165eb00)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff8165eb00-ffffffff8165ecaa: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b0b70)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff816b0b70-ffffffff816b0d2f: add_device_randomness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_device_randomness(const void *buf, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cb0d0)
Location: drivers/char/random.c:1177
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/exit.c:release_task
  - drivers/char/hw_random/core.c:add_early_randomness
  - drivers/mfd/wm831x-otp.c:wm831x_otp_init
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/firmware/dmi_scan.c:dmi_walk_early
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:__dev_open
```
**Symbols:**

```
ffffffff816cb0d0-ffffffff816cb2a8: add_device_randomness (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int size</code>
</li>
</ul>
</details>
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
