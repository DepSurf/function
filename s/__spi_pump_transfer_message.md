# Function: <code>__spi_pump_transfer_message</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __spi_pump_transfer_message(struct spi_controller *ctlr, struct spi_message *msg, bool was_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1628
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81bd6880-ffffffff81bd6bd8: __spi_pump_transfer_message (STB_LOCAL)
ffffffff8209d26d-ffffffff8209d2bf: __spi_pump_transfer_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __spi_pump_transfer_message(struct spi_controller *ctlr, struct spi_message *msg, bool was_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1635
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81c2d2b0-ffffffff81c2d608: __spi_pump_transfer_message (STB_LOCAL)
ffffffff8211e12a-ffffffff8211e17c: __spi_pump_transfer_message.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __spi_pump_transfer_message(struct spi_controller *ctlr, struct spi_message *msg, bool was_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1708
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_sync
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff81cdfcb0-ffffffff81ce0000: __spi_pump_transfer_message (STB_LOCAL)
ffffffff821ff6a7-ffffffff821ff6f9: __spi_pump_transfer_message.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
