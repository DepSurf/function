# Function: <code>uart_get_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81500460)
Location: drivers/tty/serial/serial_core.c:708
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81500460-ffffffff8150057a: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81550ff0)
Location: drivers/tty/serial/serial_core.c:731
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81550ff0-ffffffff81551121: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157d880)
Location: drivers/tty/serial/serial_core.c:723
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff8157d880-ffffffff8157d9b1: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81591aa0)
Location: drivers/tty/serial/serial_core.c:724
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff81591aa0-ffffffff81591bd1: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f64d0)
Location: drivers/tty/serial/serial_core.c:732
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff815f64d0-ffffffff815f6601: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8162f6a0)
Location: drivers/tty/serial/serial_core.c:739
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_ioctl
```
**Symbols:**

```
ffffffff8162f6a0-ffffffff8162f7d1: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164d820)
Location: drivers/tty/serial/serial_core.c:759
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff8164d820-ffffffff8164d96c: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81682370)
Location: drivers/tty/serial/serial_core.c:753
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81682370-ffffffff816824c7: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a4a00)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff816a4a00-ffffffff816a4b57: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81757030)
Location: drivers/tty/serial/serial_core.c:755
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81757030-ffffffff81757187: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817721b0)
Location: drivers/tty/serial/serial_core.c:756
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff817721b0-ffffffff81772307: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81755c70)
Location: drivers/tty/serial/serial_core.c:756
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81755c70-ffffffff81755d9f: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d93a0)
Location: drivers/tty/serial/serial_core.c:739
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff817d93a0-ffffffff817d94cf: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81917950)
Location: drivers/tty/serial/serial_core.c:751
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81917950-ffffffff81917a86: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a73450)
Location: drivers/tty/serial/serial_core.c:757
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81a73450-ffffffff81a73586: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abdb90)
Location: drivers/tty/serial/serial_core.c:778
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81abdb90-ffffffff81abdcc6: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b109e0)
Location: drivers/tty/serial/serial_core.c:769
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:iomem_reg_shift_show
  - drivers/tty/serial/serial_core.c:iomem_base_show
  - drivers/tty/serial/serial_core.c:io_type_show
  - drivers/tty/serial/serial_core.c:custom_divisor_show
  - drivers/tty/serial/serial_core.c:closing_wait_show
  - drivers/tty/serial/serial_core.c:close_delay_show
  - drivers/tty/serial/serial_core.c:xmit_fifo_size_show
  - drivers/tty/serial/serial_core.c:flags_show
  - drivers/tty/serial/serial_core.c:irq_show
  - drivers/tty/serial/serial_core.c:port_show
  - drivers/tty/serial/serial_core.c:line_show
  - drivers/tty/serial/serial_core.c:type_show
  - drivers/tty/serial/serial_core.c:uartclk_show
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81b109e0-ffffffff81b10b25: uart_get_info (STB_LOCAL)
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
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087ce60)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffff80001087ce60-ffff80001087cf84: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097e90c)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
c097e90c-c097ea0c: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000923980)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
c000000000923980-c000000000923aec: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054b9da)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffe00054b9da-ffffffe00054bad4: uart_get_info (STB_LOCAL)
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
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166a460)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff8166a460-ffffffff8166a5b7: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816495d0)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff816495d0-ffffffff81649727: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81698840)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff81698840-ffffffff81698997: uart_get_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uart_get_info(struct tty_port *port, struct serial_struct *retinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b2f00)
Location: drivers/tty/serial/serial_core.c:754
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_reg_shift
  - drivers/tty/serial/serial_core.c:uart_get_attr_iomem_base
  - drivers/tty/serial/serial_core.c:uart_get_attr_io_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_custom_divisor
  - drivers/tty/serial/serial_core.c:uart_get_attr_closing_wait
  - drivers/tty/serial/serial_core.c:uart_get_attr_close_delay
  - drivers/tty/serial/serial_core.c:uart_get_attr_xmit_fifo_size
  - drivers/tty/serial/serial_core.c:uart_get_attr_flags
  - drivers/tty/serial/serial_core.c:uart_get_attr_irq
  - drivers/tty/serial/serial_core.c:uart_get_attr_port
  - drivers/tty/serial/serial_core.c:uart_get_attr_line
  - drivers/tty/serial/serial_core.c:uart_get_attr_type
  - drivers/tty/serial/serial_core.c:uart_get_attr_uartclk
  - drivers/tty/serial/serial_core.c:uart_get_info_user
```
**Symbols:**

```
ffffffff816b2f00-ffffffff816b3057: uart_get_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
