# Function: <code>set_bringup_idt_handler</code>

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
In arch/x86/kernel/head64.c (ffffffff81003000)
Location: arch/x86/kernel/head64.c:547
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
**Symbols:**

```
ffffffff81003000-ffffffff81003051: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81003000)
Location: arch/x86/kernel/head64.c:547
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
**Symbols:**

```
ffffffff81003000-ffffffff81003051: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81003070)
Location: arch/x86/kernel/head64.c:547
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:early_setup_idt
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
```
**Symbols:**

```
ffffffff81003000-ffffffff81003051: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81000ab0)
Location: arch/x86/kernel/head64.c:578
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
**Symbols:**

```
ffffffff81000ab0-ffffffff81000b34: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81000b00)
Location: arch/x86/kernel/head64.c:578
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
**Symbols:**

```
ffffffff81000b00-ffffffff81000b84: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81049fe0)
Location: arch/x86/kernel/head64.c:578
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
**Symbols:**

```
ffffffff81049fe0-ffffffff8104a062: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
In arch/x86/kernel/head64.c (ffffffff81051240)
Location: arch/x86/kernel/head64.c:577
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:startup_64_setup_env
  - arch/x86/kernel/head64.c:early_setup_idt
```
**Symbols:**

```
ffffffff81051240-ffffffff810512c2: set_bringup_idt_handler.constprop.0 (STB_LOCAL)
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
