# Function: <code>wait_for_completion_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81821020)
Location: kernel/sched/completion.c:139
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/misc/bmp085.c:bmp085_update_raw_temperature
  - drivers/misc/bmp085.c:show_pressure
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81821020-ffffffff8182115a: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8189b5d0)
Location: kernel/sched/completion.c:139
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff8189b5d0-ffffffff8189b70a: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff818cfbf0)
Location: kernel/sched/completion.c:139
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff818cfbf0-ffffffff818cfd2b: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81907360)
Location: kernel/sched/completion.c:142
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81907360-ffffffff8190749b: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81991180)
Location: kernel/sched/completion.c:156
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/tty/serdev/core.c:serdev_device_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81991180-ffffffff819912c0: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819eda70)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/tty/serdev/core.c:serdev_device_write
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/i2c/busses/i2c-amd-platdrv.c:i2c_amd_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff819eda70-ffffffff819edbae: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a28ca0)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81a28ca0-ffffffff81a28dde: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a99180)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/soundwire/stream.c:do_bank_switch
  - drivers/soundwire/stream.c:sdw_prep_deprep_ports
```
**Symbols:**

```
ffffffff81a99180-ffffffff81a9929f: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ad0ad0)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81ad0ad0-ffffffff81ad0bef: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81bc92e0)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/io_uring.c:io_ring_exit_work
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81bc92e0-ffffffff81bc92ff: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c42100)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/io_uring.c:io_ring_exit_work
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81c42100-ffffffff81c4211f: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c34070)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/io_uring.c:io_ring_exit_work
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81c34070-ffffffff81c3408f: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81d52a10)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_ring_exit_work
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81d52a10-ffffffff81d52a2f: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f23070)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - io_uring/io_uring.c:io_ring_exit_work
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff81f23070-ffffffff81f2309b: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cdc80)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - io_uring/io_uring.c:io_ring_exit_work
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff820cdc80-ffffffff820cddcb: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151e30)
Location: kernel/sched/completion.c:155
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - security/apparmor/notify.c:aa_do_notification
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff82151e30-ffffffff82151f7b: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234c40)
Location: kernel/sched/completion.c:165
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - security/apparmor/notify.c:aa_do_notification
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/gpu/drm/drm_atomic.c:drm_crtc_commit_wait
  - drivers/gpu/drm/drm_atomic.c:drm_crtc_commit_wait
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_wait_for_flip_done
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume
  - drivers/input/serio/i8042.c:i8042_check_aux
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/platform/x86/intel_scu_ipc.c:intel_scu_ipc_check_status
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/mailbox.c:mbox_send_message
  - net/core/selftests.c:__net_test_loopback
```
**Symbols:**

```
ffffffff82234c40-ffffffff82234d8b: wait_for_completion_timeout (STB_GLOBAL)
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
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff800010da2a70)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:__cpu_up
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/soc/qcom/rpmh.c:rpmh_write_batch
  - drivers/soc/qcom/rpmh.c:rpmh_write
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/firmware/raspberrypi.c:rpi_firmware_property_list
  - drivers/firmware/ti_sci.c:ti_sci_probe
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_get_status
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_control
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_set_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_handover
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_release
  - drivers/firmware/ti_sci.c:ti_sci_cmd_proc_request
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_flow_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_rx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_udmap_tx_ch_cfg
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_unpair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_rm_psil_pair
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_get_config
  - drivers/firmware/ti_sci.c:ti_sci_cmd_ring_config
  - drivers/firmware/ti_sci.c:ti_sci_get_resource_range
  - drivers/firmware/ti_sci.c:ti_sci_cmd_core_reboot
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_match_freq
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_num_parents
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_get_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_clk_set_parent
  - drivers/firmware/ti_sci.c:ti_sci_cmd_get_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_set_clock_state
  - drivers/firmware/ti_sci.c:ti_sci_cmd_set_device_resets
  - drivers/firmware/ti_sci.c:ti_sci_get_device_state
  - drivers/firmware/ti_sci.c:ti_sci_set_device_state
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer_with_response
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
```
**Symbols:**

```
ffff800010da2a70-ffff800010da2ab0: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0e9acc8)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:__cpu_up
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/video/fbdev/mx3fb.c:mx3fb_pan_display
  - drivers/soc/tegra/fuse/fuse-tegra20.c:tegra20_fuse_read
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_wait
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_write
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_mdio_read
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_xfer
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_read
  - drivers/i2c/busses/i2c-omap.c:omap_i2c_xfer_msg
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer_with_response
  - drivers/firmware/arm_scmi/driver.c:scmi_do_xfer
  - drivers/firmware/imx/imx-scu.c:imx_scu_call_rpc
  - drivers/firmware/tegra/bpmp.c:tegra_bpmp_transfer
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/mailbox/pl320-ipc.c:pl320_ipc_transmit
  - drivers/memory/tegra/tegra20-emc.c:tegra_emc_clk_change_notify
```
**Symbols:**

```
c0e9acc8-c0e9ae28: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c000000000ee44a0)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
c000000000ee44a0-c000000000ee46e0: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0008c5fda)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - arch/riscv/kernel/smpboot.c:__cpu_up
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffe0008c5fda-ffffffe0008c614a: wait_for_completion_timeout (STB_GLOBAL)
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
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a6f940)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81a6f940-ffffffff81a6fa5f: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a2bd60)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/scsi/storvsc_drv.c:storvsc_host_reset_handler
  - drivers/scsi/storvsc_drv.c:storvsc_channel_init
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/mailbox/mailbox.c:mbox_send_message
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff81a2bd60-ffffffff81a2be73: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81adbd50)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_check_cmd_completion
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81adbd50-ffffffff81adbe6f: wait_for_completion_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int wait_for_completion_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ae83f0)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
  - drivers/mfd/wm8350-core.c:wm8350_read_auxadc
  - drivers/mfd/twl6040.c:twl6040_power
  - drivers/mfd/da9052-core.c:da9052_adc_manual_read
  - drivers/scsi/scsi_error.c:scsi_send_eh_cmnd
  - drivers/ata/libata-core.c:ata_exec_internal_sg
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_get_port_status
  - drivers/input/serio/i8042.c:i8042_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
  - drivers/mailbox/mailbox.c:mbox_send_message
```
**Symbols:**

```
ffffffff81ae83f0-ffffffff81ae84f4: wait_for_completion_timeout (STB_GLOBAL)
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
