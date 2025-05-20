# Function: <code>msi_desc_match</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116eb6c)
Location: kernel/irq/msi.c:127
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_free_msi_descs_range
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
In kernel/irq/msi.c (ffffffff811a49cb)
Location: kernel/irq/msi.c:149
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_domain_free_descs
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
In kernel/irq/msi.c (ffffffff811b68fb)
Location: kernel/irq/msi.c:149
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_domain_free_descs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c67e4)
Location: kernel/irq/msi.c:149
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_domain_free_descs
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
