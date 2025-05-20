# Function: <code>verify_and_add_patch</code>

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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e999)
Location: arch/x86/kernel/cpu/microcode/amd.c:754
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104eb25)
Location: arch/x86/kernel/cpu/microcode/amd.c:766
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050b7e)
Location: arch/x86/kernel/cpu/microcode/amd.c:767
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050d77)
Location: arch/x86/kernel/cpu/microcode/amd.c:579
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810548ba)
Location: arch/x86/kernel/cpu/microcode/amd.c:586
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057665)
Location: arch/x86/kernel/cpu/microcode/amd.c:594
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81055193)
Location: arch/x86/kernel/cpu/microcode/amd.c:764
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810583b8)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058c88)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
```
**Symbols:**

```
ffffffff8105da80-ffffffff8105dbea: verify_and_add_patch.constprop.0 (STB_LOCAL)
ffffffff8105e39c-ffffffff8105e3d2: verify_and_add_patch.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:761
Inline: True
```
**Symbols:**

```
ffffffff8105c120-ffffffff8105c28a: verify_and_add_patch.constprop.0 (STB_LOCAL)
ffffffff81bd6174-ffffffff81bd61aa: verify_and_add_patch.constprop.0.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105ca22)
Location: arch/x86/kernel/cpu/microcode/amd.c:761
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810660c2)
Location: arch/x86/kernel/cpu/microcode/amd.c:761
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072d30)
Location: arch/x86/kernel/cpu/microcode/amd.c:767
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082cf7)
Location: arch/x86/kernel/cpu/microcode/amd.c:778
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810855a7)
Location: arch/x86/kernel/cpu/microcode/amd.c:773
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c746)
Location: arch/x86/kernel/cpu/microcode/amd.c:746
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058808)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048988)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058c38)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a0d8)
Location: arch/x86/kernel/cpu/microcode/amd.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_microcode_amd
```
</details>
</li>
</ul>

## Differences
