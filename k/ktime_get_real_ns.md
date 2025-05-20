# Function: <code>ktime_get_real_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81179820)
Location: include/linux/timekeeping.h:214
Inline: False
```
```
In net/core/secure_seq.c (ffffffff81711247)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
```
**Symbols:**

```
ffffffff81179820-ffffffff8117982d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118a0c0)
Location: include/linux/timekeeping.h:230
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff8146f656)
Location: include/linux/timekeeping.h:230
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff81778d88)
Location: include/linux/timekeeping.h:230
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
**Symbols:**

```
ffffffff8118a0c0-ffffffff8118a0cd: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811994b0)
Location: include/linux/timekeeping.h:230
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff814919c6)
Location: include/linux/timekeeping.h:230
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff817a5ec8)
Location: include/linux/timekeeping.h:230
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_sequence_number
  - net/core/secure_seq.c:secure_tcpv6_sequence_number
```
**Symbols:**

```
ffffffff811994b0-ffffffff811994bd: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a1400)
Location: include/linux/timekeeping.h:219
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff8149b5f6)
Location: include/linux/timekeeping.h:219
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff817c3e70)
Location: include/linux/timekeeping.h:219
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
**Symbols:**

```
ffffffff811a1400-ffffffff811a140d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b4f80)
Location: include/linux/timekeeping.h:99
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff814da496)
Location: include/linux/timekeeping.h:99
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff8183d91c)
Location: include/linux/timekeeping.h:99
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
**Symbols:**

```
ffffffff811b4f80-ffffffff811b4f8d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3de0)
Location: include/linux/timekeeping.h:114
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff81507585)
Location: include/linux/timekeeping.h:114
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
```
```
In net/core/secure_seq.c (ffffffff8188813e)
Location: include/linux/timekeeping.h:114
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
**Symbols:**

```
ffffffff811d3de0-ffffffff811d3ded: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e42e0)
Location: include/linux/timekeeping.h:129
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff8151bb05)
Location: include/linux/timekeeping.h:129
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff818a8d0e)
Location: include/linux/timekeeping.h:129
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
**Symbols:**

```
ffffffff811e42e0-ffffffff811e42ed: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fb5d0)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff81549cb5)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff818f43ae)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
**Symbols:**

```
ffffffff811fb5d0-ffffffff811fb5dd: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208980)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff8156ae55)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff8192635e)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff8197d7ca)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff81208980-ffffffff8120898d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81231400)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In net/core/secure_seq.c (ffffffff819fa33a)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81a53ed2)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff81231400-ffffffff8123140d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123b070)
Location: include/linux/timekeeping.h:156
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b8c6)
Location: include/linux/timekeeping.h:156
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In net/core/secure_seq.c (ffffffff819f9f2a)
Location: include/linux/timekeeping.h:156
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81a5ba52)
Location: include/linux/timekeeping.h:156
Inline: True
```
**Symbols:**

```
ffffffff8123b070-ffffffff8123b07d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f830)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f7a6)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In net/core/secure_seq.c (ffffffff819e00ee)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81a3eb79)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff8123f830-ffffffff8123f83d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127a050)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In fs/ext4/super.c (ffffffff81498973)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ed33)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In net/core/secure_seq.c (ffffffff81a904fb)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81af485b)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff8127a050-ffffffff8127a05d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cd550)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In fs/ext4/super.c (ffffffff81523723)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aca81)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In net/core/secure_seq.c (ffffffff81c063b4)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81c77f0f)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff812cd550-ffffffff812cd563: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81335480)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In fs/ext4/super.c (ffffffff815c0903)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c4ba0)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In net/core/secure_seq.c (ffffffff81db5cf4)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81e3098f)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff81335480-ffffffff81335493: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813661d0)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In fs/ext4/super.c (ffffffff815f809a)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81907c70)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In net/core/secure_seq.c (ffffffff81e262c4)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/devlink/health.c (ffffffff82046d5f)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff813661d0-ffffffff813661e3: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138f2f0)
Location: include/linux/timekeeping.h:158
Inline: False
```
```
In fs/ext4/super.c (ffffffff81630c4a)
Location: include/linux/timekeeping.h:158
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_run_li_request
  - fs/ext4/super.c:ext4_run_li_request
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194f491)
Location: include/linux/timekeeping.h:158
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In net/core/secure_seq.c (ffffffff81ee4254)
Location: include/linux/timekeeping.h:158
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/devlink/health.c (ffffffff82112461)
Location: include/linux/timekeeping.h:158
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_health_do_dump
```
**Symbols:**

```
ffffffff8138f2f0-ffffffff8138f303: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010291d80)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffff8000106be740)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffff800010bc25b4)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffff800010c25380)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffff800010291d80-ffff800010291d98: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/common/bL_switcher.c (c03267e0)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_trace_trigger_cpu
  - arch/arm/common/bL_switcher.c:bL_switch_to
  - arch/arm/common/bL_switcher.c:bL_switch_to
```
```
In kernel/events/core.c (c04c2f48)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (c085e54c)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (c0cdd938)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (c0d3c488)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
c04c2f48-c04c2f60: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003403e0)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (c00000000083b6b0)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (c000000000c9c41c)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (c000000000d1ab40)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
c0000000003403e0-c000000000340410: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4642)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a565a)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffe00074f550)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffe00079d7e4)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffe0001c4642-ffffffe0001c465c: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200fa0)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff81560615)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff818c635e)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff8191d63a)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff81200fa0-ffffffff81200fad: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f3cf0)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff81551465)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff8188029e)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff818d73ea)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff811f3cf0-ffffffff811f3cfd: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fed70)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff8155f185)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff8191735e)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff8196e7ca)
Location: include/linux/timekeeping.h:157
Inline: True
```
```
In net/netfilter/nf_conntrack_core.c (ffffffff819a00b1)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1138)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_start
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819ae0cd)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_create_conntrack
```
**Symbols:**

```
ffffffff811fed70-ffffffff811fed7d: ktime_get_real_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u64 ktime_get_real_ns();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120de00)
Location: include/linux/timekeeping.h:157
Inline: False
```
```
In drivers/gpio/gpiolib.c (ffffffff81579005)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In net/core/secure_seq.c (ffffffff8193856e)
Location: include/linux/timekeeping.h:157
Inline: True
Inline callers:
  - net/core/secure_seq.c:secure_dccpv6_sequence_number
  - net/core/secure_seq.c:secure_dccp_sequence_number
  - net/core/secure_seq.c:secure_tcp_seq
  - net/core/secure_seq.c:secure_tcpv6_seq
```
```
In net/core/devlink.c (ffffffff81990c7a)
Location: include/linux/timekeeping.h:157
Inline: True
```
**Symbols:**

```
ffffffff8120de00-ffffffff8120de0d: ktime_get_real_ns (STB_LOCAL)
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
