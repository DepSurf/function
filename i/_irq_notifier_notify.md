# Function: <code>_irq_notifier_notify</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1a90)
Location: drivers/iommu/amd_iommu_init.c:1961
Inline: False
```
**Symbols:**

```
ffffffff816c1a90-ffffffff816c1ad1: _irq_notifier_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e49b0)
Location: drivers/iommu/amd_iommu_init.c:1981
Inline: False
```
**Symbols:**

```
ffffffff816e49b0-ffffffff816e49f1: _irq_notifier_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b220)
Location: drivers/iommu/amd/init.c:1968
Inline: False
```
**Symbols:**

```
ffffffff8179b220-ffffffff8179b261: _irq_notifier_notify (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa490)
Location: drivers/iommu/amd_iommu_init.c:1981
Inline: False
```
**Symbols:**

```
ffffffff816aa490-ffffffff816aa4d1: _irq_notifier_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816885c0)
Location: drivers/iommu/amd_iommu_init.c:1981
Inline: False
```
**Symbols:**

```
ffffffff816885c0-ffffffff81688601: _irq_notifier_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8670)
Location: drivers/iommu/amd_iommu_init.c:1981
Inline: False
```
**Symbols:**

```
ffffffff816d8670-ffffffff816d86b1: _irq_notifier_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _irq_notifier_notify(struct irq_affinity_notify *notify, const cpumask_t *mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2c20)
Location: drivers/iommu/amd_iommu_init.c:1981
Inline: False
```
**Symbols:**

```
ffffffff816f2c20-ffffffff816f2c61: _irq_notifier_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
