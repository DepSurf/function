# Function: <code>msi_find_desc</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_find_desc(struct msi_device_data *md, enum msi_desc_filter filter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116eb2a)
Location: kernel/irq/msi.c:244
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_free_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8116e990-ffffffff8116ea3d: msi_find_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_find_desc(struct msi_device_data *md, unsigned int domid, enum msi_desc_filter filter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4c32)
Location: kernel/irq/msi.c:350
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
Direct callers:
  - kernel/irq/msi.c:msi_next_desc
```
**Symbols:**

```
ffffffff811a3480-ffffffff811a3551: msi_find_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_find_desc(struct msi_device_data *md, unsigned int domid, enum msi_desc_filter filter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b6b61)
Location: kernel/irq/msi.c:350
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
```
**Symbols:**

```
ffffffff811b5350-ffffffff811b5428: msi_find_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct msi_desc *msi_find_desc(struct msi_device_data *md, unsigned int domid, enum msi_desc_filter filter);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6a30)
Location: kernel/irq/msi.c:350
Inline: True
Inline callers:
  - kernel/irq/msi.c:__msi_domain_alloc_irqs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_destroy_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
  - kernel/irq/msi.c:msi_device_populate_sysfs
```
**Symbols:**

```
ffffffff811c51d0-ffffffff811c52a8: msi_find_desc (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int domid</code>
</li>
<li>
<b>Param reordered. </b>
<code>md, filter</code> ➡️ <code>md, domid, filter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
