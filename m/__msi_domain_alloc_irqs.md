# Function: <code>__msi_domain_alloc_irqs</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129440)
Location: kernel/irq/msi.c:398
Inline: False
```
**Symbols:**

```
ffffffff81129440-ffffffff811297f9: __msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff81129720)
Location: kernel/irq/msi.c:398
Inline: False
```
**Symbols:**

```
ffffffff81129720-ffffffff81129a85: __msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8114a050)
Location: kernel/irq/msi.c:538
Inline: False
```
**Symbols:**

```
ffffffff8114a050-ffffffff8114a3b2: __msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff8116f320)
Location: kernel/irq/msi.c:853
Inline: False
```
**Symbols:**

```
ffffffff8116f320-ffffffff8116f783: __msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct device *dev, struct irq_domain *domain, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a4870)
Location: kernel/irq/msi.c:1253
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:__msi_domain_alloc_locked
```
**Symbols:**

```
ffffffff811a4870-ffffffff811a4d10: __msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct device *dev, struct irq_domain *domain, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b67a0)
Location: kernel/irq/msi.c:1250
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:__msi_domain_alloc_locked
```
**Symbols:**

```
ffffffff811b67a0-ffffffff811b6c3f: __msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __msi_domain_alloc_irqs(struct device *dev, struct irq_domain *domain, struct msi_ctrl *ctrl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c6690)
Location: kernel/irq/msi.c:1247
Inline: False
Direct callers:
  - kernel/irq/msi.c:msi_domain_alloc_irq_at
  - kernel/irq/msi.c:__msi_domain_alloc_locked
```
**Symbols:**

```
ffffffff811c6690-ffffffff811c6af5: __msi_domain_alloc_irqs (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct msi_ctrl *ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>int nvec</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, dev, nvec</code> ➡️ <code>dev, domain, ctrl</code>
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
