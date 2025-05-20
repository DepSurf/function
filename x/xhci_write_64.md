# Function: <code>xhci_write_64</code>

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
In drivers/usb/host/xhci.c (ffffffff8164aea5)
Location: drivers/usb/host/xhci.h:1722
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8165609f)
Location: drivers/usb/host/xhci.h:1722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81658293)
Location: drivers/usb/host/xhci.h:1722
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
In drivers/usb/host/xhci.c (ffffffff816ae695)
Location: drivers/usb/host/xhci.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b6ade)
Location: drivers/usb/host/xhci.h:1739
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816bcf08)
Location: drivers/usb/host/xhci.h:1739
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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dc835)
Location: drivers/usb/host/xhci.h:1736
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e4dac)
Location: drivers/usb/host/xhci.h:1736
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816eae16)
Location: drivers/usb/host/xhci.h:1736
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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f0d7d)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f8cfa)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff816ff25c)
Location: drivers/usb/host/xhci.h:1909
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
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
In drivers/usb/host/xhci.c (ffffffff8175cf55)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817658cc)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8176be4c)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8177392f)
Location: drivers/usb/host/xhci.h:1918
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
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
In drivers/usb/host/xhci.c (ffffffff8179d97d)
Location: drivers/usb/host/xhci.h:1932
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a5c2c)
Location: drivers/usb/host/xhci.h:1932
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817ad23f)
Location: drivers/usb/host/xhci.h:1932
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3fb6)
Location: drivers/usb/host/xhci.h:1932
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
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
In drivers/usb/host/xhci.c (ffffffff817c3da3)
Location: drivers/usb/host/xhci.h:1938
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cbcdf)
Location: drivers/usb/host/xhci.h:1938
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817d3510)
Location: drivers/usb/host/xhci.h:1938
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da3f4)
Location: drivers/usb/host/xhci.h:1938
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff817df315)
Location: drivers/usb/host/xhci.h:1938
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff818035f4)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180c0a5)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81812ad2)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181ad0c)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8181fda5)
Location: drivers/usb/host/xhci.h:1951
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff818344f0)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183d073)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81843ee8)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c38c)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81851215)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff819073c9)
Location: drivers/usb/host/xhci.h:1962
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190fb1d)
Location: drivers/usb/host/xhci.h:1962
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81916938)
Location: drivers/usb/host/xhci.h:1962
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191ef2b)
Location: drivers/usb/host/xhci.h:1962
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81923a54)
Location: drivers/usb/host/xhci.h:1962
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff8190fb4c)
Location: drivers/usb/host/xhci.h:1973
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8191767d)
Location: drivers/usb/host/xhci.h:1973
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8191dec8)
Location: drivers/usb/host/xhci.h:1973
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192b1c6)
Location: drivers/usb/host/xhci.h:1973
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff818f3123)
Location: drivers/usb/host/xhci.h:1986
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818fab0e)
Location: drivers/usb/host/xhci.h:1986
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81900823)
Location: drivers/usb/host/xhci.h:1986
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8190e6ec)
Location: drivers/usb/host/xhci.h:1986
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff819900d5)
Location: drivers/usb/host/xhci.h:1993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819998c8)
Location: drivers/usb/host/xhci.h:1993
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff8199ffc8)
Location: drivers/usb/host/xhci.h:1993
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff819af4aa)
Location: drivers/usb/host/xhci.h:1993
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff81aecac3)
Location: drivers/usb/host/xhci.h:2018
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af68c0)
Location: drivers/usb/host/xhci.h:2018
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81afd693)
Location: drivers/usb/host/xhci.h:2018
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81b0dc2a)
Location: drivers/usb/host/xhci.h:2018
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff81c7901c)
Location: drivers/usb/host/xhci.h:2020
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c84259)
Location: drivers/usb/host/xhci.h:2020
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81c8c32e)
Location: drivers/usb/host/xhci.h:2020
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c9dcea)
Location: drivers/usb/host/xhci.h:2020
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff81ce04f6)
Location: drivers/usb/host/xhci.h:2029
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ceaf59)
Location: drivers/usb/host/xhci.h:2029
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2ebc)
Location: drivers/usb/host/xhci.h:2029
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d0505a)
Location: drivers/usb/host/xhci.h:2029
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffffffff81d955ee)
Location: drivers/usb/host/xhci.h:2005
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81da0727)
Location: drivers/usb/host/xhci.h:2005
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_add_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_add_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-mem.c:xhci_remove_secondary_interrupter
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81da8806)
Location: drivers/usb/host/xhci.h:2005
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81dbac1a)
Location: drivers/usb/host/xhci.h:2005
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_handle_events
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
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
In drivers/usb/host/xhci.c (ffff800010a71b18)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7ae68)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffff800010a8300c)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b180)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
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
In drivers/usb/host/xhci.c (c0b45850)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (c0b4e78c)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (c0b5687c)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5e55c)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
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
In drivers/usb/host/xhci.c (c000000000b46914)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (c000000000b52b04)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (c000000000b5c9c0)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b66ddc)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
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
In drivers/usb/host/xhci.c (ffffffe00068a05e)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
  - drivers/usb/host/xhci.c:xhci_zero_64b_regs
```
```
In drivers/usb/host/xhci-mem.c (ffffffe0006924ae)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffe000699416)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069fb52)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
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
In drivers/usb/host/xhci.c (ffffffff817ec8b0)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f5423)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817fc298)
Location: drivers/usb/host/xhci.h:1960
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
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b19ba)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817ba5c3)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff817c1438)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c98dc)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
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
In drivers/usb/host/xhci.c (ffffffff81829370)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81831ef3)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff81838d68)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184120c)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
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
In drivers/usb/host/xhci.c (ffffffff81843317)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_resume
  - drivers/usb/host/xhci.c:xhci_set_cmd_ring_deq
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184c0d3)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ring.c (ffffffff818531d1)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_update_erst_dequeue
  - drivers/usb/host/xhci-ring.c:xhci_handle_command_timeout
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b73e)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81860615)
Location: drivers/usb/host/xhci.h:1960
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
  - drivers/usb/early/xhci-dbc.c:xdbc_mem_init
```
</details>
</li>
</ul>

## Differences
