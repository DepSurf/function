# Function: <code>irq_domain_alloc_fwnode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fwnode_handle *irq_domain_alloc_fwnode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0d30)
Location: kernel/irq/irqdomain.c:44
Inline: False
```
**Symbols:**

```
ffffffff810e0d30-ffffffff810e0db0: irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fwnode_handle *irq_domain_alloc_fwnode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6600)
Location: kernel/irq/irqdomain.c:42
Inline: False
```
**Symbols:**

```
ffffffff810e6600-ffffffff810e6680: irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fwnode_handle *irq_domain_alloc_fwnode(void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecff0)
Location: kernel/irq/irqdomain.c:42
Inline: False
```
**Symbols:**

```
ffffffff810ecff0-ffffffff810ed070: irq_domain_alloc_fwnode (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/irqchip/irq-gic.c (ffff80001147190c)
Location: include/linux/irqdomain.h:251
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_v2_acpi_init
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff800011472260)
Location: include/linux/irqdomain.h:251
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:acpi_parse_madt_msi
```
```
In drivers/irqchip/irq-gic-v3.c (ffff8000114734d4)
Location: include/linux/irqdomain.h:251
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff8000114744c4)
Location: include/linux/irqdomain.h:251
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:gic_acpi_parse_madt_its
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
