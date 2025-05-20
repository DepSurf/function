# Function: <code>pci_oxsemi_tornado_set_divisor</code>

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
void pci_oxsemi_tornado_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192a230)
Location: drivers/tty/serial/8250/8250_pci.c:1206
Inline: False
```
**Symbols:**

```
ffffffff8192a230-ffffffff8192a2f7: pci_oxsemi_tornado_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_oxsemi_tornado_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a86980)
Location: drivers/tty/serial/8250/8250_pci.c:1206
Inline: False
```
**Symbols:**

```
ffffffff81a86980-ffffffff81a86a47: pci_oxsemi_tornado_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_oxsemi_tornado_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad2010)
Location: drivers/tty/serial/8250/8250_pci.c:1186
Inline: False
```
**Symbols:**

```
ffffffff81ad2010-ffffffff81ad20d7: pci_oxsemi_tornado_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_oxsemi_tornado_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b25f60)
Location: drivers/tty/serial/8250/8250_pci.c:1267
Inline: False
```
**Symbols:**

```
ffffffff81b25f60-ffffffff81b26027: pci_oxsemi_tornado_set_divisor (STB_LOCAL)
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
