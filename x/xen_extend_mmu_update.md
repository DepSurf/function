# Function: <code>xen_extend_mmu_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101fbd0)
Location: arch/x86/xen/mmu.c:217
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
```
**Symbols:**

```
ffffffff8101fbd0-ffffffff8101fca5: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101fbe0)
Location: arch/x86/xen/mmu.c:218
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff8101fbe0-ffffffff8101fcae: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff810202a0)
Location: arch/x86/xen/mmu.c:218
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:__xen_set_pgd_hyper
  - arch/x86/xen/mmu.c:xen_set_pud_hyper
  - arch/x86/xen/mmu.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu.c:xen_set_pte_at
  - arch/x86/xen/mmu.c:xen_set_pte
  - arch/x86/xen/mmu.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff810202a0-ffffffff8102036e: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810208c0)
Location: arch/x86/xen/mmu_pv.c:185
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff810208c0-ffffffff81020992: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021450)
Location: arch/x86/xen/mmu_pv.c:165
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81021450-ffffffff81021525: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021ee0)
Location: arch/x86/xen/mmu_pv.c:174
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81021ee0-ffffffff81021fa7: xen_extend_mmu_update.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021860)
Location: arch/x86/xen/mmu_pv.c:183
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_batched_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81021860-ffffffff81021927: xen_extend_mmu_update.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024900)
Location: arch/x86/xen/mmu_pv.c:183
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81024900-ffffffff810249c7: xen_extend_mmu_update.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024ee0)
Location: arch/x86/xen/mmu_pv.c:183
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81024ee0-ffffffff81024fa7: xen_extend_mmu_update.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810275d0)
Location: arch/x86/xen/mmu_pv.c:183
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff810275d0-ffffffff81027697: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027490)
Location: arch/x86/xen/mmu_pv.c:172
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81027490-ffffffff81027539: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81029970)
Location: arch/x86/xen/mmu_pv.c:172
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff81029970-ffffffff81029a19: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8102de30)
Location: arch/x86/xen/mmu_pv.c:172
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd
```
**Symbols:**

```
ffffffff8102de30-ffffffff8102ded6: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81032e10)
Location: arch/x86/xen/mmu_pv.c:174
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81032e10-ffffffff81032ede: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a790)
Location: arch/x86/xen/mmu_pv.c:174
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff8103a790-ffffffff8103a85e: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8103a860)
Location: arch/x86/xen/mmu_pv.c:190
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff8103a860-ffffffff8103a92e: xen_extend_mmu_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_extend_mmu_update(const struct mmu_update *update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81040d20)
Location: arch/x86/xen/mmu_pv.c:190
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:__xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81040d20-ffffffff81040dee: xen_extend_mmu_update (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025040)
Location: arch/x86/xen/mmu_pv.c:183
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81025040-ffffffff81025107: xen_extend_mmu_update.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024ea0)
Location: arch/x86/xen/mmu_pv.c:183
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff81024ea0-ffffffff81024f67: xen_extend_mmu_update.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810257f0)
Location: arch/x86/xen/mmu_pv.c:183
Inline: True
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_set_pte_init
  - arch/x86/xen/mmu_pv.c:__xen_set_p4d_hyper
  - arch/x86/xen/mmu_pv.c:xen_set_pud_hyper
  - arch/x86/xen/mmu_pv.c:xen_ptep_modify_prot_commit
  - arch/x86/xen/mmu_pv.c:xen_set_pte_at
  - arch/x86/xen/mmu_pv.c:xen_set_pte
  - arch/x86/xen/mmu_pv.c:xen_set_pmd_hyper
```
**Symbols:**

```
ffffffff810257f0-ffffffff810258d0: xen_extend_mmu_update.isra.0 (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
