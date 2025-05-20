# Function: <code>uv_set_in_nmi</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s *hub_nmi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810993d0)
Location: arch/x86/platform/uv/uv_nmi.c:454
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff810993d0-ffffffff8109941b: uv_set_in_nmi (STB_LOCAL)
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
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109eaa0)
Location: arch/x86/platform/uv/uv_nmi.c:454
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff8109eaa0-ffffffff8109eae2: uv_set_in_nmi.isra.0 (STB_LOCAL)
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
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a600)
Location: arch/x86/platform/uv/uv_nmi.c:496
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff8109a600-ffffffff8109a642: uv_set_in_nmi.isra.0 (STB_LOCAL)
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
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109adc0)
Location: arch/x86/platform/uv/uv_nmi.c:499
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff8109adc0-ffffffff8109ae02: uv_set_in_nmi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab0a0)
Location: arch/x86/platform/uv/uv_nmi.c:499
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff810ab0a0-ffffffff810ab0e2: uv_set_in_nmi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c0d00)
Location: arch/x86/platform/uv/uv_nmi.c:500
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff810c0d00-ffffffff810c0d4e: uv_set_in_nmi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810dcd10)
Location: arch/x86/platform/uv/uv_nmi.c:500
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff810dcd10-ffffffff810dcd5e: uv_set_in_nmi.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e82f0)
Location: arch/x86/platform/uv/uv_nmi.c:500
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff810e82f0-ffffffff810e833e: uv_set_in_nmi.isra.0 (STB_LOCAL)
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
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f0690)
Location: arch/x86/platform/uv/uv_nmi.c:499
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_check_nmi
```
**Symbols:**

```
ffffffff810f0690-ffffffff810f06de: uv_set_in_nmi.isra.0 (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int uv_set_in_nmi(int cpu, struct uv_hub_nmi_s *hub_nmi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109a8a0)
Location: arch/x86/platform/uv/uv_nmi.c:454
Inline: True
Direct callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
**Symbols:**

```
ffffffff8109a8a0-ffffffff8109a8eb: uv_set_in_nmi (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
