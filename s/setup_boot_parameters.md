# Function: <code>setup_boot_parameters</code>

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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8105e5c7)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8105e4de)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810615a8)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8106049f)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810644ef)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8106712e)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff8106d163)
Location: arch/x86/kernel/kexec-bzimage64.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810711c1)
Location: arch/x86/kernel/kexec-bzimage64.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810721c1)
Location: arch/x86/kernel/kexec-bzimage64.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int efi_setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81078af0)
Location: arch/x86/kernel/kexec-bzimage64.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff81078af0-ffffffff81078eee: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int efi_setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81078ae0)
Location: arch/x86/kernel/kexec-bzimage64.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff81078ae0-ffffffff81078edb: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int efi_setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81079a80)
Location: arch/x86/kernel/kexec-bzimage64.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff81079a80-ffffffff81079e77: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int efi_setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81087ae0)
Location: arch/x86/kernel/kexec-bzimage64.c:190
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff81087ae0-ffffffff81087fdb: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int efi_setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81097d30)
Location: arch/x86/kernel/kexec-bzimage64.c:189
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff81097d30-ffffffff81098240: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810ae3a0)
Location: arch/x86/kernel/kexec-bzimage64.c:237
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff810ae3a0-ffffffff810ae894: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810b13a0)
Location: arch/x86/kernel/kexec-bzimage64.c:237
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff810b13a0-ffffffff810b189c: setup_boot_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int setup_boot_parameters(struct kimage *image, struct boot_params *params, long unsigned int params_load_addr, unsigned int efi_map_offset, unsigned int efi_map_sz, unsigned int setup_data_offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kexec-bzimage64.c (0)
Location: arch/x86/kernel/kexec-bzimage64.c:237
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
**Symbols:**

```
ffffffff810b8670-ffffffff810b8c7a: setup_boot_parameters (STB_LOCAL)
ffffffff821ad3de-ffffffff821ad426: setup_boot_parameters.cold (STB_LOCAL)
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810711c1)
Location: arch/x86/kernel/kexec-bzimage64.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810611d1)
Location: arch/x86/kernel/kexec-bzimage64.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff81071171)
Location: arch/x86/kernel/kexec-bzimage64.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810731d1)
Location: arch/x86/kernel/kexec-bzimage64.c:200
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int setup_data_offset</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int efi_setup_data_offset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
