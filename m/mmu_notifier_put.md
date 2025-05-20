# Function: <code>mmu_notifier_put</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129dd60)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff8129dd60-ffffffff8129ddfc: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d2050)
Location: mm/mmu_notifier.c:879
Inline: False
```
**Symbols:**

```
ffffffff812d2050-ffffffff812d20ec: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812dda70)
Location: mm/mmu_notifier.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff812dda70-ffffffff812ddb0c: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5110)
Location: mm/mmu_notifier.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff812e5110-ffffffff812e51ac: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132d2f0)
Location: mm/mmu_notifier.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff8132d2f0-ffffffff8132d38c: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139cf60)
Location: mm/mmu_notifier.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff8139cf60-ffffffff8139d010: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141c3a0)
Location: mm/mmu_notifier.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff8141c3a0-ffffffff8141c450: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8144f950)
Location: mm/mmu_notifier.c:895
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff8144f950-ffffffff8144fa00: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *subscription);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81489630)
Location: mm/mmu_notifier.c:887
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_mmu_notifier_release
```
**Symbols:**

```
ffffffff81489630-ffffffff814896e0: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033ced0)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffff80001033ced0-ffff80001033cfc8: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c054363c)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
c054363c-c0543710: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c000000000418320)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
c000000000418320-c000000000418480: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe00023287a)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffe00023287a-ffffffe00023297e: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81296340)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff81296340-ffffffff812963dc: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81287f50)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff81287f50-ffffffff81287fec: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81294150)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff81294150-ffffffff812941ec: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmu_notifier_put(struct mmu_notifier *mn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a3f80)
Location: mm/mmu_notifier.c:501
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff812a3f80-ffffffff812a4018: mmu_notifier_put (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier *subscription</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mmu_notifier *mn</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
