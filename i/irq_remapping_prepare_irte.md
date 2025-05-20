# Function: <code>irq_remapping_prepare_irte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81531d1e)
Location: drivers/iommu/amd_iommu.c:3783
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81585e9e)
Location: drivers/iommu/amd_iommu.c:3798
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b325e)
Location: drivers/iommu/amd_iommu.c:4069
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c8a88)
Location: drivers/iommu/amd_iommu.c:4207
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162f41a)
Location: drivers/iommu/amd_iommu.c:4000
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81669c5f)
Location: drivers/iommu/amd_iommu.c:4058
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168882f)
Location: drivers/iommu/amd_iommu.c:4127
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bfde3)
Location: drivers/iommu/amd_iommu.c:4108
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e2e3f)
Location: drivers/iommu/amd_iommu.c:4163
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_remapping_prepare_irte(struct amd_ir_data *data, struct irq_cfg *irq_cfg, struct irq_alloc_info *info, int devid, int index, int sub_handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81795050)
Location: drivers/iommu/amd/iommu.c:3588
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
**Symbols:**

```
ffffffff81795050-ffffffff8179514a: irq_remapping_prepare_irte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a6dbd)
Location: drivers/iommu/amd/iommu.c:3634
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8178884d)
Location: drivers/iommu/amd/iommu.c:3000
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8181017d)
Location: drivers/iommu/amd/iommu.c:3068
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff819506cf)
Location: drivers/iommu/amd/iommu.c:3094
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab5d13)
Location: drivers/iommu/amd/iommu.c:3249
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd/iommu.c (ffffffff81b021e3)
Location: drivers/iommu/amd/iommu.c:3287
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
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
In drivers/iommu/amd/iommu.c (ffffffff81b55bac)
Location: drivers/iommu/amd/iommu.c:3338
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a888f)
Location: drivers/iommu/amd_iommu.c:4163
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8168627f)
Location: drivers/iommu/amd_iommu.c:4163
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d6aff)
Location: drivers/iommu/amd_iommu.c:4163
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816f10af)
Location: drivers/iommu/amd_iommu.c:4163
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
