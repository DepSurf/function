# Function: <code>xen_setup_gdt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_setup_gdt(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81818010)
Location: arch/x86/xen/enlighten.c:1413
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_pvh_secondary_vcpu_init
  - arch/x86/xen/enlighten.c:xen_start_kernel
```
**Symbols:**

```
ffffffff81818010-ffffffff81818086: xen_setup_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_setup_gdt(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff81891af0)
Location: arch/x86/xen/enlighten.c:1433
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_pvh_secondary_vcpu_init
```
**Symbols:**

```
ffffffff81891af0-ffffffff81891b66: xen_setup_gdt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_setup_gdt(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff818c6400)
Location: arch/x86/xen/enlighten.c:1421
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_start_kernel
  - arch/x86/xen/enlighten.c:xen_pvh_secondary_vcpu_init
```
**Symbols:**

```
ffffffff818c6400-ffffffff818c6476: xen_setup_gdt (STB_LOCAL)
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
In arch/x86/xen/enlighten_pv.c (ffffffff820a5c16)
Location: arch/x86/xen/enlighten_pv.c:1212
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff826ac300)
Location: arch/x86/xen/enlighten_pv.c:1202
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff826d5444)
Location: arch/x86/xen/enlighten_pv.c:1178
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff8288b4c8)
Location: arch/x86/xen/enlighten_pv.c:1174
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a2908)
Location: arch/x86/xen/enlighten_pv.c:1175
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a59c7)
Location: arch/x86/xen/enlighten_pv.c:1169
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff82ccbda3)
Location: arch/x86/xen/enlighten_pv.c:1225
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff82fb7beb)
Location: arch/x86/xen/enlighten_pv.c:1188
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff831c2154)
Location: arch/x86/xen/enlighten_pv.c:1202
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff832a2bc0)
Location: arch/x86/xen/enlighten_pv.c:1176
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff83451fd1)
Location: arch/x86/xen/enlighten_pv.c:1165
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff83e6ef0a)
Location: arch/x86/xen/enlighten_pv.c:1208
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff8368fe42)
Location: arch/x86/xen/enlighten_pv.c:1263
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff838bf992)
Location: arch/x86/xen/enlighten_pv.c:1289
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff828939d0)
Location: arch/x86/xen/enlighten_pv.c:1169
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff828a69c7)
Location: arch/x86/xen/enlighten_pv.c:1169
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
In arch/x86/xen/enlighten_pv.c (ffffffff828a699b)
Location: arch/x86/xen/enlighten_pv.c:1169
Inline: True
Inline callers:
  - arch/x86/xen/enlighten_pv.c:xen_start_kernel
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
