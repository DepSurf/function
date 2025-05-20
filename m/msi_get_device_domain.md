# Function: <code>msi_get_device_domain</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *msi_get_device_domain(struct device *dev, unsigned int domid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a33a0)
Location: kernel/irq/msi.c:584
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_ctrl_valid
  - kernel/irq/msi.c:msi_insert_desc
```
**Symbols:**

```
ffffffff811a33a0-ffffffff811a3401: msi_get_device_domain (STB_LOCAL)
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
In kernel/irq/msi.c (ffffffff811b81a7)
Location: kernel/irq/msi.c:584
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_ctrl_valid
  - kernel/irq/msi.c:msi_insert_desc
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
In kernel/irq/msi.c (ffffffff811c8067)
Location: kernel/irq/msi.c:584
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:__msi_domain_alloc_locked
  - kernel/irq/msi.c:msi_match_device_irq_domain
  - kernel/irq/msi.c:msi_remove_device_irq_domain
  - kernel/irq/msi.c:msi_create_device_irq_domain
  - kernel/irq/msi.c:msi_ctrl_valid
  - kernel/irq/msi.c:msi_insert_desc
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
</ul>
