# Function: <code>amd_iommu_enable_interrupts</code>

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
In drivers/iommu/amd_iommu_init.c (ffffffff81532e1c)
Location: drivers/iommu/amd_iommu_init.c:1961
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff81fd6ee2)
Location: drivers/iommu/amd_iommu_init.c:2189
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff815b4d3b)
Location: drivers/iommu/amd_iommu_init.c:2346
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff815cab86)
Location: drivers/iommu/amd_iommu_init.c:2374
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff81631946)
Location: drivers/iommu/amd_iommu_init.c:2550
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166c4cc)
Location: drivers/iommu/amd_iommu_init.c:2551
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff8168addc)
Location: drivers/iommu/amd_iommu_init.c:2586
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fcdbb)
Location: drivers/iommu/amd_iommu_init.c:2651
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff82905d93)
Location: drivers/iommu/amd_iommu_init.c:2682
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2652
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff8179b270-ffffffff8179b437: amd_iommu_enable_interrupts (STB_LOCAL)
ffffffff8179c09e-ffffffff8179c0bd: amd_iommu_enable_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9670)
Location: drivers/iommu/amd/init.c:2852
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff817a9670-ffffffff817a97d1: amd_iommu_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b200)
Location: drivers/iommu/amd/init.c:2804
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff8178b200-ffffffff8178b4d1: amd_iommu_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2836
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81812970-ffffffff81812c02: amd_iommu_enable_interrupts (STB_LOCAL)
ffffffff81cfe85b-ffffffff81cfe870: amd_iommu_enable_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:2850
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81953910-ffffffff81953bc1: amd_iommu_enable_interrupts (STB_LOCAL)
ffffffff81ec70a7-ffffffff81ec70bc: amd_iommu_enable_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3073
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81ab9000-ffffffff81ab92a9: amd_iommu_enable_interrupts (STB_LOCAL)
ffffffff820970ef-ffffffff82097104: amd_iommu_enable_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3146
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81b05460-ffffffff81b05717: amd_iommu_enable_interrupts (STB_LOCAL)
ffffffff82118039-ffffffff8211804e: amd_iommu_enable_interrupts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int amd_iommu_enable_interrupts();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/init.c (0)
Location: drivers/iommu/amd/init.c:3164
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:amd_iommu_reenable
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff81b59520-ffffffff81b59862: amd_iommu_enable_interrupts (STB_LOCAL)
ffffffff821f5d01-ffffffff821f5d16: amd_iommu_enable_interrupts.cold (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ed57a)
Location: drivers/iommu/amd_iommu_init.c:2682
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e4a07)
Location: drivers/iommu/amd_iommu_init.c:2682
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff829010b6)
Location: drivers/iommu/amd_iommu_init.c:2682
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
In drivers/iommu/amd_iommu_init.c (ffffffff82906df5)
Location: drivers/iommu/amd_iommu_init.c:2682
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
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
