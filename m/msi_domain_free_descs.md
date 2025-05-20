# Function: <code>msi_domain_free_descs</code>

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
void msi_domain_free_descs(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4490)
Location: kernel/irq/msi.c:180
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
  - kernel/irq/msi.c:msi_domain_free_msi_descs_range
```
**Symbols:**

```
ffffffff811a4490-ffffffff811a4599: msi_domain_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void msi_domain_free_descs(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b61c0)
Location: kernel/irq/msi.c:180
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
  - kernel/irq/msi.c:msi_domain_free_msi_descs_range
```
**Symbols:**

```
ffffffff811b61c0-ffffffff811b62c9: msi_domain_free_descs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void msi_domain_free_descs(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6070)
Location: kernel/irq/msi.c:180
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_populate_irqs
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
  - kernel/irq/msi.c:msi_domain_free_msi_descs_range
```
**Symbols:**

```
ffffffff811c6070-ffffffff811c6179: msi_domain_free_descs (STB_LOCAL)
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
