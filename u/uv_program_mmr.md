# Function: <code>uv_program_mmr</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff81098720)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff81098720-ffffffff810987cd: uv_program_mmr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff8109df10)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff8109df10-ffffffff8109dfaa: uv_program_mmr.isra.0 (STB_LOCAL)
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
In arch/x86/platform/uv/uv_irq.c (ffffffff81099ae0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff81099ae0-ffffffff81099b7c: uv_program_mmr.isra.0 (STB_LOCAL)
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
In arch/x86/platform/uv/uv_irq.c (ffffffff8109a2f0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff8109a2f0-ffffffff8109a36d: uv_program_mmr.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void uv_program_mmr(struct irq_cfg *cfg, struct uv_irq_2_mmr_pnode *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff810aa340-ffffffff810aa3e6: uv_program_mmr (STB_LOCAL)
ffffffff81ca294e-ffffffff81ca2990: uv_program_mmr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void uv_program_mmr(struct irq_cfg *cfg, struct uv_irq_2_mmr_pnode *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff810bfdb0-ffffffff810bfe64: uv_program_mmr (STB_LOCAL)
ffffffff81e521b0-ffffffff81e521f2: uv_program_mmr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void uv_program_mmr(struct irq_cfg *cfg, struct uv_irq_2_mmr_pnode *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff810dbcc0-ffffffff810dbd74: uv_program_mmr (STB_LOCAL)
ffffffff8205565e-ffffffff820556a0: uv_program_mmr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void uv_program_mmr(struct irq_cfg *cfg, struct uv_irq_2_mmr_pnode *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: False
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff810e7290-ffffffff810e7344: uv_program_mmr (STB_LOCAL)
ffffffff820d3c59-ffffffff820d3c9b: uv_program_mmr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff810ef640-ffffffff810ef6d5: uv_program_mmr.isra.0 (STB_LOCAL)
ffffffff821aeac7-ffffffff821aeaed: uv_program_mmr.isra.0.cold (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_irq.c (ffffffff81099bf0)
Location: arch/x86/platform/uv/uv_irq.c:27
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
```
**Symbols:**

```
ffffffff81099bf0-ffffffff81099c9d: uv_program_mmr.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
