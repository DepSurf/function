# Function: <code>vc_slow_virt_to_phys</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81083680)
Location: arch/x86/kernel/sev-es.c:399
Inline: True
Direct callers:
  - arch/x86/kernel/sev-es.c:vc_do_mmio
  - arch/x86/kernel/sev-es.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81083680-ffffffff810837c4: vc_slow_virt_to_phys.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/sev.c (ffffffff81083bf0)
Location: arch/x86/kernel/sev.c:453
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81083bf0-ffffffff81083d2d: vc_slow_virt_to_phys.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:450
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff81092d90-ffffffff81092ee6: vc_slow_virt_to_phys.constprop.0 (STB_LOCAL)
ffffffff81c9f6bc-ffffffff81c9f6ff: vc_slow_virt_to_phys.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:480
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff810a52c0-ffffffff810a5441: vc_slow_virt_to_phys.constprop.0 (STB_LOCAL)
ffffffff81e4eee5-ffffffff81e4ef28: vc_slow_virt_to_phys.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:480
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff810bda50-ffffffff810bdbce: vc_slow_virt_to_phys.constprop.0 (STB_LOCAL)
ffffffff8205465f-ffffffff820546aa: vc_slow_virt_to_phys.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:492
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff810c10c0-ffffffff810c123e: vc_slow_virt_to_phys.isra.0 (STB_LOCAL)
ffffffff820d2c58-ffffffff820d2ca3: vc_slow_virt_to_phys.isra.0.cold (STB_LOCAL)
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
In arch/x86/kernel/sev.c (0)
Location: arch/x86/kernel/sev.c:492
Inline: True
Direct callers:
  - arch/x86/kernel/sev.c:vc_do_mmio
```
**Symbols:**

```
ffffffff810c8520-ffffffff810c869e: vc_slow_virt_to_phys.isra.0 (STB_LOCAL)
ffffffff821adaba-ffffffff821adb05: vc_slow_virt_to_phys.isra.0.cold (STB_LOCAL)
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
