# Function: <code>p4d_populate_init</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a94b97)
Location: arch/x86/mm/init_64.c:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81acc477)
Location: arch/x86/mm/init_64.c:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff810863f2)
Location: arch/x86/mm/init_64.c:72
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff810863f2-ffffffff81086540: p4d_populate_init.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81bd906c)
Location: arch/x86/mm/init_64.c:72
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81bd906c-ffffffff81bd91ba: p4d_populate_init.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81bcab47)
Location: arch/x86/mm/init_64.c:72
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81bcab47-ffffffff81bcac97: p4d_populate_init.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81ca002f)
Location: arch/x86/mm/init_64.c:73
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81ca002f-ffffffff81ca017f: p4d_populate_init.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff81e4f69f)
Location: arch/x86/mm/init_64.c:73
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
```
**Symbols:**

```
ffffffff81e4f69f-ffffffff81e4f80d: p4d_populate_init.constprop.0 (STB_LOCAL)
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
In arch/x86/mm/init_64.c (ffffffff820c710d)
Location: arch/x86/mm/init_64.c:73
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
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
In arch/x86/mm/init_64.c (ffffffff8214b17f)
Location: arch/x86/mm/init_64.c:73
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
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
In arch/x86/mm/init_64.c (ffffffff8222dc2f)
Location: arch/x86/mm/init_64.c:73
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
  - arch/x86/mm/init_64.c:phys_p4d_init
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
In arch/x86/mm/init_64.c (ffffffff81a6b2e7)
Location: arch/x86/mm/init_64.c:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81a278af)
Location: arch/x86/mm/init_64.c:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81ad76f7)
Location: arch/x86/mm/init_64.c:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
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
In arch/x86/mm/init_64.c (ffffffff81ae3bb7)
Location: arch/x86/mm/init_64.c:72
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__kernel_physical_mapping_init
```
</details>
</li>
</ul>

## Differences
