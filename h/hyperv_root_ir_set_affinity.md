# Function: <code>hyperv_root_ir_set_affinity</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hyperv_root_ir_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff817a4620)
Location: drivers/iommu/hyperv-iommu.c:246
Inline: False
```
**Symbols:**

```
ffffffff817a4620-ffffffff817a4673: hyperv_root_ir_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hyperv_root_ir_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff8182de10)
Location: drivers/iommu/hyperv-iommu.c:246
Inline: False
```
**Symbols:**

```
ffffffff8182de10-ffffffff8182de63: hyperv_root_ir_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hyperv_root_ir_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff8196eb60)
Location: drivers/iommu/hyperv-iommu.c:246
Inline: False
```
**Symbols:**

```
ffffffff8196eb60-ffffffff8196ebbd: hyperv_root_ir_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hyperv_root_ir_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81ad9520)
Location: drivers/iommu/hyperv-iommu.c:249
Inline: False
```
**Symbols:**

```
ffffffff81ad9520-ffffffff81ad957d: hyperv_root_ir_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hyperv_root_ir_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81b276a0)
Location: drivers/iommu/hyperv-iommu.c:249
Inline: False
```
**Symbols:**

```
ffffffff81b276a0-ffffffff81b276fd: hyperv_root_ir_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hyperv_root_ir_set_affinity(struct irq_data *data, const struct cpumask *mask, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e530)
Location: drivers/iommu/hyperv-iommu.c:249
Inline: False
```
**Symbols:**

```
ffffffff81b7e530-ffffffff81b7e58d: hyperv_root_ir_set_affinity (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
