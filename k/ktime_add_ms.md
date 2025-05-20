# Function: <code>ktime_add_ms</code>

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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/ktime.h:224
Inline: True
```
```
In arch/x86/events/intel/rapl.c (0)
Location: include/linux/ktime.h:224
Inline: True
```
```
In drivers/mailbox/mailbox.c (0)
Location: include/linux/ktime.h:224
Inline: True
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
In arch/x86/events/intel/cqm.c (0)
Location: include/linux/ktime.h:224
Inline: True
```
```
In drivers/mailbox/mailbox.c (ffffffff817503b0)
Location: include/linux/ktime.h:224
Inline: True
```
</details>
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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735c54)
Location: include/linux/ktime.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81719463)
Location: include/linux/ktime.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81797300)
Location: include/linux/ktime.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818d02dc)
Location: include/linux/ktime.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a21a7c)
Location: include/linux/ktime.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6ae0c)
Location: include/linux/ktime.h:184
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
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
In init/do_mounts.c (ffffffff838b1ca5)
Location: include/linux/ktime.h:182
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
```
```
In drivers/xen/events/events_base.c (ffffffff81abd02d)
Location: include/linux/ktime.h:182
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:handle_irq_for_port
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/sdhci.c (c0c25eb4)
Location: include/linux/ktime.h:201
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_enable_clk
  - drivers/mmc/host/sdhci.c:sdhci_reset
```
</details>
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
