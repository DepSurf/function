# Function: <code>clock_t_to_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eaec0)
Location: kernel/time/time.c:643
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff810eaec0-ffffffff810eaf05: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1b60)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff810f1b60-ffffffff810f1ba8: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8ce0)
Location: kernel/time/time.c:650
Inline: False
Direct callers:
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - kernel/compat.c:compat_SyS_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff810f8ce0-ffffffff810f8d28: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fad00)
Location: kernel/time/time.c:740
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:compat_SyS_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff810fad00-ffffffff810fad46: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105690)
Location: kernel/time/time.c:707
Inline: False
Direct callers:
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:compat_SyS_times
  - kernel/sys.c:compat_SyS_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81105690-ffffffff811056d6: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811104f0)
Location: kernel/time/time.c:719
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff811104f0-ffffffff81110536: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111bae0)
Location: kernel/time/time.c:657
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8111bae0-ffffffff8111bb26: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126500)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81126500-ffffffff81126543: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811324a0)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff811324a0-ffffffff811324e3: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81141850)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81141850-ffffffff81141893: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113da60)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8113da60-ffffffff8113daa3: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8113ecb0)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8113ecb0-ffffffff8113ecf3: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81162140)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__x64_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81162140-ffffffff81162183: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811950b0)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff811950b0-ffffffff811950f8: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811d2e60)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff811d2e60-ffffffff811d2ea8: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811e7150)
Location: kernel/time/time.c:635
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff811e7150-ffffffff811e7198: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811fcea0)
Location: kernel/time/time.c:682
Inline: False
Direct callers:
  - kernel/sysctl.c:do_proc_dointvec_userhz_jiffies_conv
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/bsg.c:bsg_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv4/nexthop.c:rtm_to_nh_config
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff811fcea0-ffffffff811fced0: clock_t_to_jiffies (STB_GLOBAL)
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
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199fa8)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_compat_sys_times
  - kernel/sys.c:__arm64_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffff800010199fa8-ffff80001019a014: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5280)
Location: kernel/time/time.c:725
Inline: True
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c03e5280-c03e5300: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa220)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_compat_sys_times
  - kernel/sys.c:__se_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
c0000000001fa220-c0000000001fa278: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a434)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffe00012a434-ffffffe00012a472: clock_t_to_jiffies (STB_GLOBAL)
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
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112ac50)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8112ac50-ffffffff8112ac93: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d4c0)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff8111d4c0-ffffffff8111d503: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81128970)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81128970-ffffffff811289b3: clock_t_to_jiffies (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int clock_t_to_jiffies(long unsigned int x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134ff0)
Location: kernel/time/time.c:725
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__x32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - kernel/sys.c:__ia32_compat_sys_times
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - net/ipv6/route.c:ip6_route_info_create
```
**Symbols:**

```
ffffffff81134ff0-ffffffff81135018: clock_t_to_jiffies (STB_GLOBAL)
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
