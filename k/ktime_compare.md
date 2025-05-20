# Function: <code>ktime_compare</code>

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
In drivers/base/power/wakeup.c (ffffffff8155c19b)
Location: include/linux/ktime.h:135
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_destroy
```
```
In drivers/md/dm.c (ffffffff816a3e04)
Location: include/linux/ktime.h:135
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_request_fn
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
In drivers/base/power/wakeup.c (ffffffff815ae398)
Location: include/linux/ktime.h:135
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_destroy
```
```
In drivers/md/dm-rq.c (ffffffff8170f532)
Location: include/linux/ktime.h:135
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff8151cf58)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815251f9)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/misc/sram.c (ffffffff815fb3b1)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/md/dm-rq.c (ffffffff8174151a)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff8152d7d9)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81537af8)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/misc/sram.c (ffffffff8160f14b)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816126e1)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d5be2)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/md/dm-rq.c (ffffffff8175b4d3)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In drivers/acpi/button.c (ffffffff8158e649)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159935d)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/misc/sram.c (ffffffff816779cb)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff8167af51)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817422d2)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/rtc/interface.c (ffffffff8178b4e6)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/md/dm-rq.c (ffffffff817cd726)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In kernel/time/hrtimer.c (ffffffff8111667e)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8151264c)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/acpi/button.c (ffffffff815c598b)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d0c01)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8165fe07)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/misc/sram.c (ffffffff816b343f)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816b6cc5)
Location: include/linux/ktime.h:109
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81782e2b)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/rtc/interface.c (ffffffff817cd704)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817ee9ef)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/dm-rq.c (ffffffff818164c9)
Location: include/linux/ktime.h:109
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_old_request_fn
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
In kernel/time/hrtimer.c (ffffffff81121cbe)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81527ecc)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/acpi/button.c (ffffffff815def4b)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ea231)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e457)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff816d469f)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816d7f03)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817a9d8b)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/rtc/interface.c (ffffffff817f47c9)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8181a8bf)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
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
In kernel/time/hrtimer.c (ffffffff8112c5fe)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8155712c)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/acpi/button.c (ffffffff81610a53)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161bfa3)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816b5107)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff816f39e2)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff8170fef0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff81713246)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817e8f2b)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff818027a1)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/rtc/interface.c (ffffffff818357f2)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8185cd14)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81863884)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8113861e)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8157876c)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/acpi/button.c (ffffffff81631f03)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163da43)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7de7)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81717de2)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff817341e0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff81737546)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81819deb)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff818336a1)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffff81856c95)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff81866fc2)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188eb24)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff818955cf)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8114742e)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8161d51e)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/pwm/pwm-lpss.c:pwm_lpss_wait_for_update
```
```
In drivers/acpi/button.c (ffffffff816def92)
Location: include/linux/ktime.h:94
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eae03)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/reset/reset-brcmstb-rescal.c (ffffffff81733259)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8178c187)
Location: include/linux/ktime.h:94
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:94
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff817d399d)
Location: include/linux/ktime.h:94
Inline: True
```
```
In drivers/misc/sram.c (ffffffff817f179b)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff817f45b0)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/net/phy/phy_device.c (ffffffff81883771)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_poll_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff81889058)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ea95b)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff81908995)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffff8192a315)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff8193a642)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819487cd)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff8194db73)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195d7c4)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81965bef)
Location: include/linux/ktime.h:94
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8114393e)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff81154bac)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff816440a2)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/button.c (ffffffff816fcfb2)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81708563)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/reset/reset-brcmstb-rescal.c (ffffffff8174f3f9)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/reset/reset-brcmstb-rescal.c:brcm_rescal_reset_set
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff817a2717)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff817e83fd)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/misc/sram.c (ffffffff81805deb)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff81808010)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/net/phy/phy_device.c (ffffffff81891ea1)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_poll_reset
```
```
In drivers/net/phy/bcm84881.c (ffffffff818972c8)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_wait_init
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818f1f3c)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f384b)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff819113d5)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81929cc3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192b259)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
```
```
In drivers/input/input.c (ffffffff81931655)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff81940a42)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194e5cd)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81953563)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81964174)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8196c6bb)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff81144aee)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff811560fc)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81626df7)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/button.c (ffffffff816ded6d)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9b62)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81707a72)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81785417)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff817cc994)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/misc/sram.c (ffffffff817eaa6b)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff817ecbe0)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/net/phy/phy_device.c (ffffffff81874cfe)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879eb7)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff818d572c)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8387)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff818f49c7)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff8190d213)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e77f)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
```
In drivers/input/input.c (ffffffff81914c75)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff81924182)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8193213d)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81932bb9)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819373f3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81948594)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8195167b)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff81168349)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff8117adac)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81696673)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/button.c (ffffffff81756f0d)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff817633c3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81783342)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8180bf4c)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81856f81)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/misc/sram.c (ffffffff818772db)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff818ffab3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81905753)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190af57)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81970397)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197319f)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff819922c3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff819adde3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/input/input.c (ffffffff819b6e05)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff819c71af)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d545d)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d5f69)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff819db658)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed23f)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff819f6bbb)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8119bd4c)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff811afd1c)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff817b7513)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/button.c (ffffffff8188a0ab)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81897318)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff818b9f1e)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8194c51c)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff8199d3b4)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/misc/sram.c (ffffffff819bf537)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff81a50ff9)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5805e)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e455)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81aca399)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81acea65)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff81aeed50)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81b0c513)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/input/input.c (ffffffff81b16b45)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff81b28243)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37e85)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b38a92)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81b3a326)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81b3f0c0)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b53b57)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81b55767)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff811da68c)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff811f075c)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff818d1bd6)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/button.c (ffffffff819d0a8f)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df062)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a0887e)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_reset
  - drivers/dma/lgm/lgm-dma.c:ldma_chan_off
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab06cc)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81b0ebd4)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/misc/sram.c (ffffffff81b34cd7)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/spi/spi-mem.c (ffffffff81bda1f9)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81be1dfa)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9193)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/usb/host/pci-quirks.c (ffffffff81c54939)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c59325)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff81c7bd82)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/usb/early/ehci-dbgp.c (ffffffff81c9c4e3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/early/ehci-dbgp.c:dbgp_wait_until_done
```
```
In drivers/input/input.c (ffffffff81ca7c35)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff81cbbcc3)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccd4c5)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81cce3a2)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/i2c/busses/i2c-designware-amdpsp.c (ffffffff81ccfd66)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
  - drivers/i2c/busses/i2c-designware-amdpsp.c:psp_send_check_i2c_req
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81cd54a0)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cecab7)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81cee827)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff811eebbc)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff8120517c)
Location: include/linux/ktime.h:95
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff81296b99)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff81914bc6)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/button.c (ffffffff81a180ef)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26d74)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc51c)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81b55b5c)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_record
```
```
In drivers/base/power/domain_governor.c (ffffffff81b5cc84)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/base/power/domain_governor.c:cpu_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
  - drivers/base/power/domain_governor.c:_default_power_down_ok
```
```
In drivers/misc/sram.c (ffffffff81b881b7)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81bc155c)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/spi/spi-mem.c (ffffffff81c30c8a)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81c396f6)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c415c1)
Location: include/linux/ktime.h:95
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc0325)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff81ce2ff1)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/input/input.c (ffffffff81d0f145)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/input/misc/uinput.c (ffffffff81d1f2fc)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/interface.c (ffffffff81d23573)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d35235)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36c48)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81d3d132)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81d557d7)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/md/md.c (ffffffff81d575a7)
Location: include/linux/ktime.h:95
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In init/do_mounts.c (ffffffff838b1ce8)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In kernel/time/hrtimer.c (ffffffff81204d3c)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In kernel/time/tick-sched.c (ffffffff8121b84c)
Location: include/linux/ktime.h:93
Inline: True
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b21b9)
Location: include/linux/ktime.h:93
Inline: True
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8195cb36)
Location: include/linux/ktime.h:93
Inline: True
```
```
In drivers/pci/controller/dwc/pcie-designware-host.c (ffffffff819b4b40)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
```
In drivers/acpi/button.c (ffffffff81a6335f)
Location: include/linux/ktime.h:93
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71d84)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/pmdomain/governor.c (ffffffff81aa4784)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/pmdomain/governor.c:cpu_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
  - drivers/pmdomain/governor.c:_default_power_down_ok
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4fb2c)
Location: include/linux/ktime.h:93
Inline: True
```
```
In drivers/base/power/wakeup.c (ffffffff81bae11c)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_record
```
```
In drivers/misc/sram.c (ffffffff81bdc067)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/dma-buf/dma-fence-unwrap.c (ffffffff81c15ce7)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence-unwrap.c:__dma_fence_unwrap_merge
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c198a6)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:timeline_fence_set_deadline
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81caef74)
Location: include/linux/ktime.h:93
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc31ea)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_fences
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3b1a)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_poll_status
```
```
In drivers/net/phy/phy_device.c (ffffffff81ceea86)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_loopback
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6c51)
Location: include/linux/ktime.h:93
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d750e5)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff81d98143)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm
```
```
In drivers/input/input.c (ffffffff81dc4e65)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/input/misc/uinput.c (ffffffff81dd502c)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
  - drivers/input/misc/uinput.c:uinput_write
```
```
In drivers/rtc/interface.c (ffffffff81dd92d3)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81deb3c5)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable
```
```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81deca08)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:txgbe_i2c_dw_xfer_quirk
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_check_stopbit
```
```
In drivers/power/reset/mt6323-poweroff.c (ffffffff81df3a82)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/power/reset/mt6323-poweroff.c:mt6323_do_pwroff
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c6e7)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
```
In drivers/md/md.c (ffffffff81e141e7)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e9385f)
Location: include/linux/ktime.h:93
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
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
In virt/kvm/kvm_main.c (ffff8000100bb280)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_block
```
```
In kernel/time/hrtimer.c (ffff8000101a2248)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pci/controller/pcie-mediatek.c (ffff80001072b994)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
```
```
In drivers/pci/controller/dwc/pci-imx6.c (ffff800010731fb4)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/acpi/button.c (ffff8000107a047c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffff8000107a8934)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/clk/bcm/clk-bcm2835.c (ffff8000107cdd34)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_clock_off
  - drivers/clk/bcm/clk-bcm2835.c:bcm2835_pll_on
```
```
In drivers/clk/imx/clk-frac-pll.c (ffff8000107d3b34)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-pfdv2.c (ffff8000107d4870)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv4.c (ffff8000107d5d9c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
```
```
In drivers/clk/imx/clk-sccg-pll.c (ffff8000107d65f8)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (ffff8000107d6b0c)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/clk/sunxi-ng/ccu_common.c (ffff8000107f4878)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/soc/imx/gpcv2.c (ffff800010818224)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-infracfg.c (ffff800010818ba8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
```
```
In drivers/soc/mediatek/mtk-scpsys.c (ffff8000108194c4)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-clk-measure.c (ffff800010819938)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_best_id
```
```
In drivers/soc/rockchip/pm_domains.c (ffff80001081eae4)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5878)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
```
```
In drivers/char/tpm/tpm_crb.c (ffff8000108c3214)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/iommu/arm-smmu.c (ffff8000108d193c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/iommu/arm-smmu.c:arm_smmu_iova_to_phys_hard
```
```
In drivers/iommu/arm-smmu-v3.c (ffff8000108d3f34)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/iommu/rockchip-iommu.c (ffff8000108d8c2c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable_stall
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable_stall
```
```
In drivers/iommu/qcom_iommu.c (ffff8000108dae00)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffff80001090ac34)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffff80001092ae4c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (ffff800010931250)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (ffff800010932478)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/spi/spi-omap2-mcspi.c (ffff8000109ccf70)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
```
```
In drivers/usb/phy/phy-mxs-usb.c (ffff800010a39a84)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a5a3c0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffff800010a70678)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffff800010a95ec8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffff800010aa8a38)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/thermal/armada_thermal.c (ffff800010addce4)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adf6f0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffff800010aeae50)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/firmware/arm_scmi/driver.c (ffff800010b56c5c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
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
In arch/arm/mach-meson/platsmp.c (c03305f0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - arch/arm/mach-meson/platsmp.c:meson8b_smp_boot_secondary
```
```
In kernel/time/hrtimer.c (c03ebf94)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/bus/ti-sysc.c (c0828d60)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_init_module
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
  - drivers/bus/ti-sysc.c:sysc_reset_done_quirk_wdt
```
```
In drivers/phy/samsung/phy-exynos-pcie.c (c082c7a0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/phy/samsung/phy-exynos-pcie.c:exynos5440_pcie_phy_power_off
```
```
In drivers/pci/controller/pci-tegra.c (c08ad1ac)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_resume
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_pm_suspend
```
```
In drivers/pci/controller/pcie-mediatek.c (c08b55a0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_startup_port_v2
  - drivers/pci/controller/pcie-mediatek.c:mtk_pcie_check_cfg_cpld
```
```
In drivers/pci/controller/dwc/pci-imx6.c (c08bbd58)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pci-imx6.c:imx6_pcie_deassert_core_reset
```
```
In drivers/pci/controller/dwc/pcie-uniphier.c (c08bf39c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-uniphier.c:uniphier_pcie_probe
```
```
In drivers/clk/clk-milbeaut.c (c08f4f08)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/clk-milbeaut.c:m10v_clk_divider_set_rate
```
```
In drivers/clk/imx/clk-frac-pll.c (c08fae88)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_set_rate
  - drivers/clk/imx/clk-frac-pll.c:clk_pll_prepare
```
```
In drivers/clk/imx/clk-pfdv2.c (c08fb918)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pfdv2.c:clk_pfdv2_enable
```
```
In drivers/clk/imx/clk-pllv4.c (c08fcd90)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pllv4.c:clk_pllv4_enable
```
```
In drivers/clk/imx/clk-sccg-pll.c (c08fd214)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/clk/imx/clk-pll14xx.c (c08fde9c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/clk/imx/clk-pll14xx.c:clk_pll14xx_wait_lock
```
```
In drivers/clk/uniphier/clk-uniphier-cpugear.c (c091c2f8)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/soc/imx/gpcv2.c (c0934eac)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/imx/gpcv2.c:imx_gpc_pu_pgc_sw_pxx_req
```
```
In drivers/soc/mediatek/mtk-infracfg.c (c09358a0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_clear_bus_protection
  - drivers/soc/mediatek/mtk-infracfg.c:mtk_infracfg_set_bus_protection
```
```
In drivers/soc/mediatek/mtk-scpsys.c (c0935d78)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_off
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
  - drivers/soc/mediatek/mtk-scpsys.c:scpsys_power_on
```
```
In drivers/soc/amlogic/meson-clk-measure.c (c0936458)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/amlogic/meson-clk-measure.c:meson_measure_id
```
```
In drivers/soc/rockchip/pm_domains.c (c0939110)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/rockchip/pm_domains.c:rockchip_pd_power
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
  - drivers/soc/rockchip/pm_domains.c:rockchip_pmu_set_idle_request
```
```
In drivers/soc/tegra/pmc.c (c093d78c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/soc/tegra/pmc.c:tegra_powergate_set
```
```
In drivers/tty/serial/mvebu-uart.c (c09a1480)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:wait_for_xmitr
```
```
In drivers/iommu/rockchip-iommu.c (c09c5f3c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_enable
  - drivers/iommu/rockchip-iommu.c:rk_iommu_disable
```
```
In drivers/iommu/qcom_iommu.c (c09cb7dc)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/iommu/qcom_iommu.c:qcom_iommu_tlb_sync
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (c09f449c)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (c0a095a0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (c0a14374)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (c0a14cf4)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/spi/spi-omap2-mcspi.c (c0ab602c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/spi/spi-omap2-mcspi.c:mcspi_wait_for_reg_bit
```
```
In drivers/net/ethernet/ti/davinci_mdio.c (c0acfb08)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_runtime_suspend
```
```
In drivers/usb/phy/phy-mxs-usb.c (c0b0ca10)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/phy/phy-mxs-usb.c:mxs_phy_init
```
```
In drivers/usb/host/ehci-hcd.c (c0b25fb8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (c0b44608)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (c0b78b8c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (c0b875b0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/thermal/armada_thermal.c (c0bbf8fc)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/thermal/armada_thermal.c:armada_wait_sensor_validity
```
```
In drivers/watchdog/watchdog_dev.c (c0bc1324)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (c0bc3714)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
```
In drivers/mmc/host/sdhci.c (c0c25ef8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_reset
```
```
In drivers/mmc/host/cqhci.c (c0c300c8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_off
```
```
In drivers/firmware/arm_scmi/driver.c (c0c38090)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/arm_scmi/driver.c:scmi_xfer_done_no_timeout
```
```
In drivers/firmware/tegra/bpmp.c (c0c42064)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer_atomic
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
In kernel/time/hrtimer.c (c0000000002036fc)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (c0000000009ab2f4)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (c0000000009c9e2c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (c0000000009d1778)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (c0000000009d2548)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1cf44)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (c000000000b44cd8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (c000000000b754b8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (c000000000b8a244)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7928)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (c000000000bd6320)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffe00012f3c8)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
```
```
In drivers/misc/sram.c (ffffffe0005a27ca)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/lochnagar-i2c.c (ffffffe0005a76a2)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/lochnagar-i2c.c:lochnagar_update_config
```
```
In drivers/mfd/arizona-core.c (ffffffe0005a7e14)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/mfd/arizona-core.c:arizona_poll_reg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066fc2a)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffe000688e1c)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffe0006a78ac)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffe0006b421a)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d756e)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffe0006e02e0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff81130dce)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/acpi/button.c (ffffffff816023c3)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81609473)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8169d837)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff816de112)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff816fa270)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816fb2a6)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d21cb)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff817eba81)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffff8180bca5)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff81819c72)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff818349a4)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8183b44f)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8112383e)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/acpi/button.c (ffffffff815ed873)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fb0b3)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b227)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff816b8772)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff816ce080)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff816cf0b6)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/xhci.c (ffffffff817b0b91)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffff817d3415)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff817e1362)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc034)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff81802abb)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8112eaee)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff8156c4bc)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/acpi/button.c (ffffffff816261e3)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81631883)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816cbaa7)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff8170baa2)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff817276a0)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff8172aa06)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8180ec6b)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff81828521)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffff8184ae25)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff8185b152)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81883fd4)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff8188aa7f)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
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
In kernel/time/hrtimer.c (ffffffff8113b4ee)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimer_run_queues
  - kernel/time/hrtimer.c:hrtimer_interrupt
  - kernel/time/hrtimer.c:hrtimer_reprogram
  - kernel/time/hrtimer.c:hrtimer_reprogram
```
```
In drivers/pwm/pwm-lpss.c (ffffffff815869b7)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/acpi/button.c (ffffffff81640093)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_lid_notify_state
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164bbbe)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/char/tpm/tpm_crb.c (ffffffff816e5f77)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/wakeup.c (0)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/base/power/domain_governor.c (ffffffff81726492)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/misc/sram.c (ffffffff81742adb)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/misc/sram.c:atmel_securam_wait
```
```
In drivers/mfd/arizona-core.c (ffffffff81745e46)
Location: include/linux/ktime.h:112
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182973b)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:ehci_hrtimer_func
```
```
In drivers/usb/host/xhci.c (ffffffff818424f1)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_handshake
```
```
In drivers/input/input.c (ffffffff81866075)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
```
```
In drivers/rtc/interface.c (ffffffff818762a6)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_timer_enqueue
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fa94)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
```
```
In drivers/md/md.c (ffffffff818a10bf)
Location: include/linux/ktime.h:112
Inline: True
Inline callers:
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
  - drivers/md/md.c:md_flush_request
```
</details>
</li>
</ul>

## Differences
