# Function: <code>free_transition_pgtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_transition_pgtable(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b820)
Location: arch/x86/kernel/machine_kexec_64.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
```
**Symbols:**

```
ffffffff8105b820-ffffffff8105b85a: free_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_transition_pgtable(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b830)
Location: arch/x86/kernel/machine_kexec_64.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8105b830-ffffffff8105b86a: free_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_transition_pgtable(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e7c0)
Location: arch/x86/kernel/machine_kexec_64.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8105e7c0-ffffffff8105e7fa: free_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_transition_pgtable(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105de40)
Location: arch/x86/kernel/machine_kexec_64.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff8105de40-ffffffff8105de88: free_transition_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_transition_pgtable(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061b00)
Location: arch/x86/kernel/machine_kexec_64.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff81061b00-ffffffff81061b48: free_transition_pgtable (STB_LOCAL)
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810651c5)
Location: arch/x86/kernel/machine_kexec_64.c:39
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ae35)
Location: arch/x86/kernel/machine_kexec_64.c:39
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e905)
Location: arch/x86/kernel/machine_kexec_64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106feb5)
Location: arch/x86/kernel/machine_kexec_64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810772d5)
Location: arch/x86/kernel/machine_kexec_64.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077905)
Location: arch/x86/kernel/machine_kexec_64.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078395)
Location: arch/x86/kernel/machine_kexec_64.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085bf5)
Location: arch/x86/kernel/machine_kexec_64.c:111
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095fe5)
Location: arch/x86/kernel/machine_kexec_64.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abc65)
Location: arch/x86/kernel/machine_kexec_64.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af825)
Location: arch/x86/kernel/machine_kexec_64.c:113
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b63b5)
Location: arch/x86/kernel/machine_kexec_64.c:110
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ee55)
Location: arch/x86/kernel/machine_kexec_64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f275)
Location: arch/x86/kernel/machine_kexec_64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f305)
Location: arch/x86/kernel/machine_kexec_64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071585)
Location: arch/x86/kernel/machine_kexec_64.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_cleanup
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
</ul>
