# Function: <code>__msi_domain_alloc_locked</code>

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
int __msi_domain_alloc_locked(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4d20)
Location: kernel/irq/msi.c:1337
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:msi_domain_alloc_irqs_range
```
**Symbols:**

```
ffffffff811a4d20-ffffffff811a4ddc: __msi_domain_alloc_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __msi_domain_alloc_locked(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b6c50)
Location: kernel/irq/msi.c:1334
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:msi_domain_alloc_irqs_range
```
**Symbols:**

```
ffffffff811b6c50-ffffffff811b6d42: __msi_domain_alloc_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __msi_domain_alloc_locked(struct device *dev, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6b10)
Location: kernel/irq/msi.c:1324
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irqs_all_locked
  - kernel/irq/msi.c:msi_domain_alloc_irqs_range
```
**Symbols:**

```
ffffffff811c6b10-ffffffff811c6c02: __msi_domain_alloc_locked (STB_LOCAL)
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
