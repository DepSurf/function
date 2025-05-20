# Function: <code>amd_iommu_report_page_fault</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c9988)
Location: drivers/iommu/amd_iommu.c:585
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff81630338)
Location: drivers/iommu/amd_iommu.c:524
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff8166b058)
Location: drivers/iommu/amd_iommu.c:523
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff81689829)
Location: drivers/iommu/amd_iommu.c:540
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff816c0e57)
Location: drivers/iommu/amd_iommu.c:528
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff816e3e9e)
Location: drivers/iommu/amd_iommu.c:534
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void amd_iommu_report_page_fault(u16 devid, u16 domain_id, u64 address, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:478
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
**Symbols:**

```
ffffffff81795390-ffffffff81795435: amd_iommu_report_page_fault (STB_LOCAL)
ffffffff8179a511-ffffffff8179a58e: amd_iommu_report_page_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void amd_iommu_report_page_fault(u16 devid, u16 domain_id, u64 address, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:548
Inline: False
```
**Symbols:**

```
ffffffff817a3750-ffffffff817a37fa: amd_iommu_report_page_fault (STB_LOCAL)
ffffffff81c0b37d-ffffffff81c0b3fa: amd_iommu_report_page_fault.cold (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81786b8e)
Location: drivers/iommu/amd/iommu.c:472
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8180dc75)
Location: drivers/iommu/amd/iommu.c:476
Inline: True
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
In drivers/iommu/amd/iommu.c (ffffffff8194e5ce)
Location: drivers/iommu/amd/iommu.c:483
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_iommu_report_page_fault(struct amd_iommu *iommu, u16 devid, u16 domain_id, u64 address, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab1f20)
Location: drivers/iommu/amd/iommu.c:542
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
**Symbols:**

```
ffffffff81ab1f20-ffffffff81ab212b: amd_iommu_report_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_iommu_report_page_fault(struct amd_iommu *iommu, u16 devid, u16 domain_id, u64 address, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afdfd0)
Location: drivers/iommu/amd/iommu.c:542
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
**Symbols:**

```
ffffffff81afdfd0-ffffffff81afe1db: amd_iommu_report_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_iommu_report_page_fault(struct amd_iommu *iommu, u16 devid, u16 domain_id, u64 address, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b516c0)
Location: drivers/iommu/amd/iommu.c:660
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_print_event
```
**Symbols:**

```
ffffffff81b516c0-ffffffff81b518cb: amd_iommu_report_page_fault (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816a997e)
Location: drivers/iommu/amd_iommu.c:534
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff816872de)
Location: drivers/iommu/amd_iommu.c:534
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff816d7b5e)
Location: drivers/iommu/amd_iommu.c:534
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff816f210e)
Location: drivers/iommu/amd_iommu.c:534
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
