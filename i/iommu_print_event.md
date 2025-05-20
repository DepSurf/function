# Function: <code>iommu_print_event</code>

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
In drivers/iommu/amd_iommu.c (ffffffff81531fc6)
Location: drivers/iommu/amd_iommu.c:449
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff815867b6)
Location: drivers/iommu/amd_iommu.c:547
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff815b3ca2)
Location: drivers/iommu/amd_iommu.c:550
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_int_thread
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
In drivers/iommu/amd_iommu.c (ffffffff815c9904)
Location: drivers/iommu/amd_iommu.c:608
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
In drivers/iommu/amd_iommu.c (ffffffff816302b4)
Location: drivers/iommu/amd_iommu.c:547
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
In drivers/iommu/amd_iommu.c (ffffffff8166adc4)
Location: drivers/iommu/amd_iommu.c:547
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
In drivers/iommu/amd_iommu.c (ffffffff816894b4)
Location: drivers/iommu/amd_iommu.c:564
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
In drivers/iommu/amd_iommu.c (ffffffff816c0dc0)
Location: drivers/iommu/amd_iommu.c:552
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
In drivers/iommu/amd_iommu.c (ffffffff816e3dfd)
Location: drivers/iommu/amd_iommu.c:558
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
void iommu_print_event(struct amd_iommu *iommu, void *__evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:502
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81795440-ffffffff81795512: iommu_print_event (STB_LOCAL)
ffffffff8179a58e-ffffffff8179a81d: iommu_print_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:572
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff817a4000-ffffffff817a41ae: iommu_print_event.isra.0 (STB_LOCAL)
ffffffff81c0b4fe-ffffffff81c0b6e7: iommu_print_event.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:496
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff817868a0-ffffffff81786c37: iommu_print_event.isra.0 (STB_LOCAL)
ffffffff81bfce00-ffffffff81bfd19c: iommu_print_event.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:502
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff8180d970-ffffffff8180dd57: iommu_print_event.isra.0 (STB_LOCAL)
ffffffff81cfdcaf-ffffffff81cfe03d: iommu_print_event.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:524
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff8194e2e0-ffffffff8194e707: iommu_print_event.isra.0 (STB_LOCAL)
ffffffff81ec65fd-ffffffff81ec6971: iommu_print_event.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_print_event(struct amd_iommu *iommu, void *__evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab2ab0)
Location: drivers/iommu/amd/iommu.c:593
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81ab2ab0-ffffffff81ab3171: iommu_print_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iommu_print_event(struct amd_iommu *iommu, void *__evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:593
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81aff460-ffffffff81affb8c: iommu_print_event (STB_LOCAL)
ffffffff82117c4e-ffffffff82117c62: iommu_print_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iommu_print_event(struct amd_iommu *iommu, void *__evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:711
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_int_thread
```
**Symbols:**

```
ffffffff81b52850-ffffffff81b52f7c: iommu_print_event (STB_LOCAL)
ffffffff821f597e-ffffffff821f5992: iommu_print_event.cold (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816a98dd)
Location: drivers/iommu/amd_iommu.c:558
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
In drivers/iommu/amd_iommu.c (ffffffff8168723d)
Location: drivers/iommu/amd_iommu.c:558
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
In drivers/iommu/amd_iommu.c (ffffffff816d7abd)
Location: drivers/iommu/amd_iommu.c:558
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
In drivers/iommu/amd_iommu.c (ffffffff816f206d)
Location: drivers/iommu/amd_iommu.c:558
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
