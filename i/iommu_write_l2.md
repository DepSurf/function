# Function: <code>iommu_write_l2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_write_l2(struct amd_iommu *iommu, u8 address, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815325d0)
Location: drivers/iommu/amd_iommu_init.c:276
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:state_next
```
**Symbols:**

```
ffffffff815325d0-ffffffff8153261a: iommu_write_l2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_write_l2(struct amd_iommu *iommu, u8 address, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81586db0)
Location: drivers/iommu/amd_iommu_init.c:295
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:state_next
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
```
**Symbols:**

```
ffffffff81586db0-ffffffff81586dfa: iommu_write_l2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_write_l2(struct amd_iommu *iommu, u8 address, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4500)
Location: drivers/iommu/amd_iommu_init.c:300
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
```
**Symbols:**

```
ffffffff815b4500-ffffffff815b454a: iommu_write_l2 (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff815cab19)
Location: drivers/iommu/amd_iommu_init.c:307
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff816318d9)
Location: drivers/iommu/amd_iommu_init.c:336
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff8166c473)
Location: drivers/iommu/amd_iommu_init.c:336
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff8168ad83)
Location: drivers/iommu/amd_iommu_init.c:339
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff816c27c7)
Location: drivers/iommu/amd_iommu_init.c:324
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff816e56e7)
Location: drivers/iommu/amd_iommu_init.c:325
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b573)
Location: drivers/iommu/amd/init.c:325
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff817a99b3)
Location: drivers/iommu/amd/init.c:343
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff8178b6b3)
Location: drivers/iommu/amd/init.c:339
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff818122e2)
Location: drivers/iommu/amd/init.c:356
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff819531e8)
Location: drivers/iommu/amd/init.c:360
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff81ab8a28)
Location: drivers/iommu/amd/init.c:352
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff81b04d98)
Location: drivers/iommu/amd/init.c:360
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd/init.c (ffffffff81b58aa8)
Location: drivers/iommu/amd/init.c:345
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:iommu_apply_resume_quirks
  - drivers/iommu/amd/init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff816ab1c7)
Location: drivers/iommu/amd_iommu_init.c:325
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff81688b27)
Location: drivers/iommu/amd_iommu_init.c:325
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff816d93a7)
Location: drivers/iommu/amd_iommu_init.c:325
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
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
In drivers/iommu/amd_iommu_init.c (ffffffff816f3957)
Location: drivers/iommu/amd_iommu_init.c:325
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_resume
  - drivers/iommu/amd_iommu_init.c:iommu_init_pci
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
