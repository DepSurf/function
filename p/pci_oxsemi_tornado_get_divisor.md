# Function: <code>pci_oxsemi_tornado_get_divisor</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int pci_oxsemi_tornado_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81927360)
Location: drivers/tty/serial/8250/8250_pci.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81927360-ffffffff819275b3: pci_oxsemi_tornado_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int pci_oxsemi_tornado_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a84090)
Location: drivers/tty/serial/8250/8250_pci.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81a84090-ffffffff81a842e5: pci_oxsemi_tornado_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int pci_oxsemi_tornado_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81acf870)
Location: drivers/tty/serial/8250/8250_pci.c:1066
Inline: False
```
**Symbols:**

```
ffffffff81acf870-ffffffff81acfad6: pci_oxsemi_tornado_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int pci_oxsemi_tornado_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b236d0)
Location: drivers/tty/serial/8250/8250_pci.c:1147
Inline: False
```
**Symbols:**

```
ffffffff81b236d0-ffffffff81b23936: pci_oxsemi_tornado_get_divisor (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
