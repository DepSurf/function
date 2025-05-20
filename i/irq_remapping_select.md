# Function: <code>irq_remapping_select</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3c50)
Location: drivers/iommu/amd/iommu.c:3853
Inline: True
```
**Symbols:**

```
ffffffff817a3c50-ffffffff817a3cf7: irq_remapping_select.part.0 (STB_LOCAL)
ffffffff817a3d00-ffffffff817a3d1c: irq_remapping_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81786590)
Location: drivers/iommu/amd/iommu.c:3219
Inline: True
```
**Symbols:**

```
ffffffff81786590-ffffffff8178663f: irq_remapping_select (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180d5d5)
Location: drivers/iommu/amd/iommu.c:3287
Inline: True
```
**Symbols:**

```
ffffffff8180d5a0-ffffffff8180d665: irq_remapping_select (STB_LOCAL)
ffffffff81cfdc9a-ffffffff81cfdcaf: irq_remapping_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3313
Inline: False
```
**Symbols:**

```
ffffffff8194dd70-ffffffff8194de58: irq_remapping_select (STB_LOCAL)
ffffffff81ec65aa-ffffffff81ec65bf: irq_remapping_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3466
Inline: False
```
**Symbols:**

```
ffffffff81ab3500-ffffffff81ab361f: irq_remapping_select (STB_LOCAL)
ffffffff82096d9b-ffffffff82096db0: irq_remapping_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3504
Inline: False
```
**Symbols:**

```
ffffffff81b00340-ffffffff81b0045f: irq_remapping_select (STB_LOCAL)
ffffffff82117cce-ffffffff82117ce3: irq_remapping_select.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int irq_remapping_select(struct irq_domain *d, struct irq_fwspec *fwspec, enum irq_domain_bus_token bus_token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:3555
Inline: False
```
**Symbols:**

```
ffffffff81b53810-ffffffff81b5392f: irq_remapping_select (STB_LOCAL)
ffffffff821f5a0c-ffffffff821f5a21: irq_remapping_select.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
