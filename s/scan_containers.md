# Function: <code>scan_containers</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050a11)
Location: arch/x86/kernel/cpu/microcode/amd.c:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810545b1)
Location: arch/x86/kernel/cpu/microcode/amd.c:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057384)
Location: arch/x86/kernel/cpu/microcode/amd.c:160
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054d50)
Location: arch/x86/kernel/cpu/microcode/amd.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81054d50-ffffffff81054eab: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057f90)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81057f90-ffffffff810580db: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058860)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058860-ffffffff810589ab: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105da30)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105da30-ffffffff8105da76: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c0d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:375
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105c0d0-ffffffff8105c116: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cd80)
Location: arch/x86/kernel/cpu/microcode/amd.c:375
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105cd80-ffffffff8105cee1: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81066460)
Location: arch/x86/kernel/cpu/microcode/amd.c:375
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81066460-ffffffff810665c1: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072990)
Location: arch/x86/kernel/cpu/microcode/amd.c:375
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81072990-ffffffff81072b07: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810828f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810828f0-ffffffff81082a67: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085220)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81085220-ffffffff81085393: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c4a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:401
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff8108c4a0-ffffffff8108c605: scan_containers (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810583e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810583e0-ffffffff8105852b: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048560)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81048560-ffffffff810486ab: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058810)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058810-ffffffff8105895b: scan_containers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scan_containers(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059cb0)
Location: arch/x86/kernel/cpu/microcode/amd.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81059cb0-ffffffff81059dfb: scan_containers (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
