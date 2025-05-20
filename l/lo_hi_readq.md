# Function: <code>lo_hi_readq</code>

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
In drivers/usb/host/xhci.c (ffffffff8164ae55)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816561cb)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81658207)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
```
In drivers/usb/host/xhci-dbg.c (ffffffff8165fc55)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs
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
In drivers/usb/host/xhci.c (ffffffff816acdd3)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6c10)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816bceae)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbg.c (ffffffff816c10d3)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
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
In drivers/usb/host/xhci.c (ffffffff816db094)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4ede)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816eadbb)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbg.c (ffffffff816ef043)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
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
In drivers/usb/host/xhci.c (ffffffff816ef86e)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8e26)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816ff1f5)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbg.c (ffffffff817034b3)
Location: include/linux/io-64-nonatomic-lo-hi.h:7
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
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
In drivers/usb/host/xhci.c (ffffffff817616d0)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817659fe)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8176bde5)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbg.c (ffffffff81770213)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_cmd_ptrs
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
  - drivers/usb/host/xhci-dbg.c:xhci_print_ir_set
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
In drivers/usb/host/xhci.c (ffffffff817a2183)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a5d67)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817ad1c9)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff817c84d6)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cbe16)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d349a)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff818073a8)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c1d9)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81812a60)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff8183826a)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d1a7)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81843ecd)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff8190a9cd)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190fc51)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191691e)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff819131da)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819177b1)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191deae)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff818f66aa)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818fac42)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81900809)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff81994977)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81999a07)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199ffad)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff81af1551)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af69ff)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afd678)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff81c7e650)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c84398)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c314)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff81ce57d8)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ceb0a7)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2ea5)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/platform/x86/intel/pmc/core_ssram.c (ffffffff81ddca38)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
  - drivers/platform/x86/intel/pmc/core_ssram.c:pmc_core_ssram_get_pmc
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
In drivers/usb/host/xhci.c (ffffffff81d9a856)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da0875)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_interrupter
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da87ef)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
__u64 lo_hi_readq(volatile const void *addr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a76564)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
Direct callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7af88)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a82fd0)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
ffff800010a6f1a8-ffff800010a6f1dc: lo_hi_readq (STB_LOCAL)
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
In drivers/usb/host/xhci.c (c0b4a118)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (c0b4e8d0)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (c0b56860)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
__u64 lo_hi_readq(volatile const void *addr);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4cce8)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
Direct callers:
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (c000000000b52c5c)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (c000000000b5c97c)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
**Symbols:**

```
c000000000b44260-c000000000b44390: lo_hi_readq (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffe00068e490)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffe0006925e2)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffe0006993f8)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/nvme/host/pci.c (ffffffff8174c94c)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_reg_read64
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/usb/host/xhci.c (ffffffff817f061a)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f5557)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817fc27d)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/nvme/host/pci.c (ffffffff8172c7ec)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_pci_reg_read64
  - drivers/nvme/host/pci.c:nvme_reset_work
```
```
In drivers/usb/host/xhci.c (ffffffff817b577a)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ba6f7)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817c141d)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff8182d0ea)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81832027)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81838d4d)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff8184711a)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_suspend
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_run
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c207)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818531b6)
Location: include/linux/io-64-nonatomic-lo-hi.h:8
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
