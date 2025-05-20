# Function: <code>serial_base_device_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int serial_base_device_init(struct uart_port *port, struct device *dev, struct device *parent_dev, const struct device_type *type, void (*release)(struct device *), unsigned int ctrl_id, unsigned int port_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_base_bus.c (0)
Location: drivers/tty/serial/serial_base_bus.c:61
Inline: False
Direct callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
**Symbols:**

```
ffffffff81ac3f70-ffffffff81ac40a5: serial_base_device_init (STB_LOCAL)
ffffffff82116c19-ffffffff82116c34: serial_base_device_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int serial_base_device_init(struct uart_port *port, struct device *dev, struct device *parent_dev, const struct device_type *type, void (*release)(struct device *), unsigned int ctrl_id, unsigned int port_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_base_bus.c (0)
Location: drivers/tty/serial/serial_base_bus.c:61
Inline: False
Direct callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
**Symbols:**

```
ffffffff81b16e10-ffffffff81b16f45: serial_base_device_init (STB_LOCAL)
ffffffff821f4973-ffffffff821f498e: serial_base_device_init.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
