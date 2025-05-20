# Function: <code>init_transition_pgtable</code>

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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b980)
Location: arch/x86/kernel/machine_kexec_64.c:44
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ba6e)
Location: arch/x86/kernel/machine_kexec_64.c:44
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e9eb)
Location: arch/x86/kernel/machine_kexec_64.c:44
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e090)
Location: arch/x86/kernel/machine_kexec_64.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061d58)
Location: arch/x86/kernel/machine_kexec_64.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064e05)
Location: arch/x86/kernel/machine_kexec_64.c:51
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106aa75)
Location: arch/x86/kernel/machine_kexec_64.c:51
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e210)
Location: arch/x86/kernel/machine_kexec_64.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8106e210-ffffffff8106e587: init_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f7c0)
Location: arch/x86/kernel/machine_kexec_64.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8106f7c0-ffffffff8106fb37: init_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81076c10)
Location: arch/x86/kernel/machine_kexec_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff81076c10-ffffffff81077086: init_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077240)
Location: arch/x86/kernel/machine_kexec_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff81077240-ffffffff810776b6: init_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077cf0)
Location: arch/x86/kernel/machine_kexec_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff81077cf0-ffffffff81078141: init_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/kernel/machine_kexec_64.c:123
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff810854f0-ffffffff81085956: init_transition_pgtable (STB_LOCAL)
ffffffff81c9e83b-ffffffff81c9e85b: init_transition_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/kernel/machine_kexec_64.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff810958d0-ffffffff81095d39: init_transition_pgtable (STB_LOCAL)
ffffffff81e4dca9-ffffffff81e4dcc9: init_transition_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/kernel/machine_kexec_64.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff810ab510-ffffffff810ab98b: init_transition_pgtable (STB_LOCAL)
ffffffff820540a4-ffffffff820540c4: init_transition_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/kernel/machine_kexec_64.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff810af0d0-ffffffff810af54f: init_transition_pgtable (STB_LOCAL)
ffffffff820d2651-ffffffff820d2671: init_transition_pgtable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/kernel/machine_kexec_64.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
```
**Symbols:**

```
ffffffff810b5c60-ffffffff810b60df: init_transition_pgtable (STB_LOCAL)
ffffffff821ad367-ffffffff821ad387: init_transition_pgtable.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e760)
Location: arch/x86/kernel/machine_kexec_64.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8106e760-ffffffff8106ead7: init_transition_pgtable (STB_LOCAL)
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ee20)
Location: arch/x86/kernel/machine_kexec_64.c:124
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ec10)
Location: arch/x86/kernel/machine_kexec_64.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8106ec10-ffffffff8106ef87: init_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_transition_pgtable(struct kimage *image, pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070e90)
Location: arch/x86/kernel/machine_kexec_64.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff81070e90-ffffffff81071207: init_transition_pgtable (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
