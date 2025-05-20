# Function: <code>load_microcode_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
enum ucode_state load_microcode_amd(int cpu, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e8f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:853
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8104e8f0-ffffffff8104eccf: load_microcode_amd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
enum ucode_state load_microcode_amd(int cpu, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104ea80)
Location: arch/x86/kernel/cpu/microcode/amd.c:863
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8104ea80-ffffffff8104ee56: load_microcode_amd (STB_GLOBAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050f67)
Location: arch/x86/kernel/cpu/microcode/amd.c:865
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050cd0)
Location: arch/x86/kernel/cpu/microcode/amd.c:677
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81050cd0-ffffffff81051086: load_microcode_amd.constprop.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054810)
Location: arch/x86/kernel/cpu/microcode/amd.c:684
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81054810-ffffffff81054c77: load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:692
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810575c0-ffffffff8105798c: load_microcode_amd (STB_LOCAL)
ffffffff81057c85-ffffffff81057d2a: load_microcode_amd.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810553b2)
Location: arch/x86/kernel/cpu/microcode/amd.c:840
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81054fd0-ffffffff810550a9: load_microcode_amd.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810585e5)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058200-ffffffff810582d6: load_microcode_amd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058eb5)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058ad0-ffffffff81058ba6: load_microcode_amd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105e0cd)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105df90-ffffffff8105e136: load_microcode_amd (STB_LOCAL)
ffffffff8105e471-ffffffff8105e487: load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c72d)
Location: arch/x86/kernel/cpu/microcode/amd.c:837
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105c5f0-ffffffff8105c796: load_microcode_amd (STB_LOCAL)
ffffffff81bd6249-ffffffff81bd625f: load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cfc0)
Location: arch/x86/kernel/cpu/microcode/amd.c:837
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105cfc0-ffffffff8105d0f6: load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810666a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:837
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810666a0-ffffffff810667d6: load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum ucode_state load_microcode_amd(bool save, u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810731f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810731f0-ffffffff81073340: load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum ucode_state load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810832f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:854
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810832f0-ffffffff810835c1: load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum ucode_state load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810857a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:850
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810857a0-ffffffff81085a71: load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum ucode_state load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c6b0)
Location: arch/x86/kernel/cpu/microcode/amd.c:823
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd
```
**Symbols:**

```
ffffffff8108c6b0-ffffffff8108caa7: load_microcode_amd (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058a35)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058650-ffffffff81058726: load_microcode_amd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048bb5)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810487d0-ffffffff810488a6: load_microcode_amd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058e65)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058a80-ffffffff81058b56: load_microcode_amd.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105a305)
Location: arch/x86/kernel/cpu/microcode/amd.c:838
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81059f20-ffffffff81059ff6: load_microcode_amd.part.0 (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool save</code>
</li>
<li>
<b>Param reordered. </b>
<code>save, family, data, size</code> ➡️ <code>family, data, size</code>
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
