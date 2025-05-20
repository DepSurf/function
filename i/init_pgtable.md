# Function: <code>init_pgtable</code>

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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b88e)
Location: arch/x86/kernel/machine_kexec_64.c:101
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105b985)
Location: arch/x86/kernel/machine_kexec_64.c:101
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e902)
Location: arch/x86/kernel/machine_kexec_64.c:101
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105df84)
Location: arch/x86/kernel/machine_kexec_64.c:112
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81061c44)
Location: arch/x86/kernel/machine_kexec_64.c:112
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff81064d0f)
Location: arch/x86/kernel/machine_kexec_64.c:116
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106a97f)
Location: arch/x86/kernel/machine_kexec_64.c:116
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106e69d)
Location: arch/x86/kernel/machine_kexec_64.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106fc4d)
Location: arch/x86/kernel/machine_kexec_64.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077090)
Location: arch/x86/kernel/machine_kexec_64.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff81077090-ffffffff81077299: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810776c0)
Location: arch/x86/kernel/machine_kexec_64.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff810776c0-ffffffff810778c9: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078150)
Location: arch/x86/kernel/machine_kexec_64.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff81078150-ffffffff81078359: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81085960)
Location: arch/x86/kernel/machine_kexec_64.c:193
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff81085960-ffffffff81085bbb: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81095d40)
Location: arch/x86/kernel/machine_kexec_64.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff81095d40-ffffffff81095faa: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ab9a0)
Location: arch/x86/kernel/machine_kexec_64.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff810ab9a0-ffffffff810abc0a: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810af560)
Location: arch/x86/kernel/machine_kexec_64.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff810af560-ffffffff810af7ca: init_pgtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_pgtable(struct kimage *image, long unsigned int start_pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b60f0)
Location: arch/x86/kernel/machine_kexec_64.c:192
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
```
**Symbols:**

```
ffffffff810b60f0-ffffffff810b635a: init_pgtable (STB_LOCAL)
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106ebed)
Location: arch/x86/kernel/machine_kexec_64.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105ec8f)
Location: arch/x86/kernel/machine_kexec_64.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f09d)
Location: arch/x86/kernel/machine_kexec_64.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
In arch/x86/kernel/machine_kexec_64.c (ffffffff8107131d)
Location: arch/x86/kernel/machine_kexec_64.c:194
Inline: True
Inline callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
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
