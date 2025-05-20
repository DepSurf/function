# Function: <code>msi_domain_free_irqs_range_locked</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void msi_domain_free_irqs_range_locked(struct device *dev, unsigned int domid, unsigned int first, unsigned int last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a5e72)
Location: kernel/irq/msi.c:1585
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_free_irqs_range
```
**Symbols:**

```
ffffffff811a5c10-ffffffff811a5c81: msi_domain_free_irqs_range_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void msi_domain_free_irqs_range_locked(struct device *dev, unsigned int domid, unsigned int first, unsigned int last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b81e8)
Location: kernel/irq/msi.c:1582
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_free_irqs_range
```
**Symbols:**

```
ffffffff811b7f20-ffffffff811b7f91: msi_domain_free_irqs_range_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void msi_domain_free_irqs_range_locked(struct device *dev, unsigned int domid, unsigned int first, unsigned int last);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c80a8)
Location: kernel/irq/msi.c:1572
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_free_irqs_all
  - kernel/irq/msi.c:msi_domain_free_irqs_range
```
**Symbols:**

```
ffffffff811c7de0-ffffffff811c7e51: msi_domain_free_irqs_range_locked (STB_GLOBAL)
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
