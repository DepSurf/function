# Function: <code>hyperv_flush_tlb_others_ex</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102a540)
Location: arch/x86/hyperv/mmu.c:190
Inline: False
```
**Symbols:**

```
ffffffff8102a540-ffffffff8102a9c9: hyperv_flush_tlb_others_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff8102b140)
Location: arch/x86/hyperv/mmu.c:140
Inline: False
```
**Symbols:**

```
ffffffff8102b140-ffffffff8102b5c9: hyperv_flush_tlb_others_ex (STB_LOCAL)
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
In arch/x86/hyperv/mmu.c (ffffffff8102c005)
Location: arch/x86/hyperv/mmu.c:162
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102e0d6)
Location: arch/x86/hyperv/mmu.c:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102e9e6)
Location: arch/x86/hyperv/mmu.c:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff81030c60)
Location: arch/x86/hyperv/mmu.c:164
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
**Symbols:**

```
ffffffff81030c60-ffffffff81030fe3: hyperv_flush_tlb_others_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810319d0)
Location: arch/x86/hyperv/mmu.c:170
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
**Symbols:**

```
ffffffff810319d0-ffffffff81031d53: hyperv_flush_tlb_others_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/mmu.c (ffffffff810324f0)
Location: arch/x86/hyperv/mmu.c:170
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
**Symbols:**

```
ffffffff810324f0-ffffffff81032867: hyperv_flush_tlb_others_ex (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:169
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
**Symbols:**

```
ffffffff81037670-ffffffff810379ff: hyperv_flush_tlb_others_ex (STB_LOCAL)
ffffffff81c97e25-ffffffff81c97e43: hyperv_flush_tlb_others_ex.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:169
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
**Symbols:**

```
ffffffff8103d880-ffffffff8103dc1d: hyperv_flush_tlb_others_ex (STB_LOCAL)
ffffffff81e47266-ffffffff81e4727e: hyperv_flush_tlb_others_ex.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:169
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
**Symbols:**

```
ffffffff81046680-ffffffff81046a48: hyperv_flush_tlb_others_ex (STB_LOCAL)
ffffffff82051efe-ffffffff82051f16: hyperv_flush_tlb_others_ex.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:173
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
**Symbols:**

```
ffffffff810468c0-ffffffff81046c9f: hyperv_flush_tlb_others_ex (STB_LOCAL)
ffffffff820d038e-ffffffff820d03c3: hyperv_flush_tlb_others_ex.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 hyperv_flush_tlb_others_ex(const struct cpumask *cpus, const struct flush_tlb_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/mmu.c (0)
Location: arch/x86/hyperv/mmu.c:173
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
```
**Symbols:**

```
ffffffff8104d0d0-ffffffff8104d41a: hyperv_flush_tlb_others_ex (STB_LOCAL)
ffffffff821aad4e-ffffffff821aad83: hyperv_flush_tlb_others_ex.cold (STB_LOCAL)
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
In arch/x86/hyperv/mmu.c (ffffffff8102eb46)
Location: arch/x86/hyperv/mmu.c:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8101e460)
Location: arch/x86/hyperv/mmu.c:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102e9a6)
Location: arch/x86/hyperv/mmu.c:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
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
In arch/x86/hyperv/mmu.c (ffffffff8102f7af)
Location: arch/x86/hyperv/mmu.c:164
Inline: True
Inline callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
