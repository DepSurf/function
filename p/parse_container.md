# Function: <code>parse_container</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t parse_container(u8 *ucode, ssize_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050670)
Location: arch/x86/kernel/cpu/microcode/amd.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81050670-ffffffff81050732: parse_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t parse_container(u8 *ucode, ssize_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054280)
Location: arch/x86/kernel/cpu/microcode/amd.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81054280-ffffffff81054342: parse_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t parse_container(u8 *ucode, ssize_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057040)
Location: arch/x86/kernel/cpu/microcode/amd.c:83
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81057040-ffffffff81057118: parse_container (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054d87)
Location: arch/x86/kernel/cpu/microcode/amd.c:298
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057fc7)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058897)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t parse_container(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105d8e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8105d8e0-ffffffff8105da22: parse_container (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t parse_container(u8 *ucode, size_t size, struct cont_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105bf80)
Location: arch/x86/kernel/cpu/microcode/amd.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff8105bf80-ffffffff8105c0c2: parse_container (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cdb7)
Location: arch/x86/kernel/cpu/microcode/amd.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81066497)
Location: arch/x86/kernel/cpu/microcode/amd.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810729cb)
Location: arch/x86/kernel/cpu/microcode/amd.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108292b)
Location: arch/x86/kernel/cpu/microcode/amd.c:297
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085259)
Location: arch/x86/kernel/cpu/microcode/amd.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c4d9)
Location: arch/x86/kernel/cpu/microcode/amd.c:320
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058417)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81048597)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058847)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059ce7)
Location: arch/x86/kernel/cpu/microcode/amd.c:296
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
