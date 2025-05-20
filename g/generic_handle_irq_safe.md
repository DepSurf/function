# Function: <code>generic_handle_irq_safe</code>

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
int generic_handle_irq_safe(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81161ab0)
Location: kernel/irq/irqdesc.c:678
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff81161ab0-ffffffff81161afe: generic_handle_irq_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_handle_irq_safe(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811951d0)
Location: kernel/irq/irqdesc.c:681
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811951d0-ffffffff81195229: generic_handle_irq_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_handle_irq_safe(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811a6b60)
Location: kernel/irq/irqdesc.c:702
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811a6b60-ffffffff811a6bb9: generic_handle_irq_safe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_handle_irq_safe(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b6680)
Location: kernel/irq/irqdesc.c:702
Inline: False
Direct callers:
  - drivers/mfd/ezx-pcap.c:pcap_isr_work
  - drivers/i2c/i2c-core-base.c:i2c_handle_smbus_host_notify
```
**Symbols:**

```
ffffffff811b6680-ffffffff811b66d9: generic_handle_irq_safe (STB_GLOBAL)
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
