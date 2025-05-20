# Function: <code>iommu_update_intcapxt</code>

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
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c1970)
Location: drivers/iommu/amd_iommu_init.c:1935
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff816c1970-ffffffff816c1a8b: iommu_update_intcapxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4890)
Location: drivers/iommu/amd_iommu_init.c:1955
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff816e4890-ffffffff816e49ab: iommu_update_intcapxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b100)
Location: drivers/iommu/amd/init.c:1942
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
  - drivers/iommu/amd/init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff8179b100-ffffffff8179b219: iommu_update_intcapxt (STB_LOCAL)
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
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aa370)
Location: drivers/iommu/amd_iommu_init.c:1955
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff816aa370-ffffffff816aa48b: iommu_update_intcapxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81688300)
Location: drivers/iommu/amd_iommu_init.c:1955
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff81688300-ffffffff8168841d: iommu_update_intcapxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8550)
Location: drivers/iommu/amd_iommu_init.c:1955
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff816d8550-ffffffff816d866b: iommu_update_intcapxt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iommu_update_intcapxt(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f2b00)
Location: drivers/iommu/amd_iommu_init.c:1955
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_init_msi
  - drivers/iommu/amd_iommu_init.c:_irq_notifier_notify
```
**Symbols:**

```
ffffffff816f2b00-ffffffff816f2c1b: iommu_update_intcapxt (STB_LOCAL)
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
