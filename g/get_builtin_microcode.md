# Function: <code>get_builtin_microcode</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool get_builtin_microcode(struct cpio_data *cp, unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050a50)
Location: arch/x86/kernel/cpu/microcode/amd.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff81050a50-ffffffff81050aec: get_builtin_microcode (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050bbc)
Location: arch/x86/kernel/cpu/microcode/amd.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810546fc)
Location: arch/x86/kernel/cpu/microcode/amd.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810574a5)
Location: arch/x86/kernel/cpu/microcode/amd.c:239
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054b25)
Location: arch/x86/kernel/cpu/microcode/amd.c:460
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057d65)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058635)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105d6b5)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105bd55)
Location: arch/x86/kernel/cpu/microcode/amd.c:457
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c725)
Location: arch/x86/kernel/cpu/microcode/amd.c:457
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81065dd5)
Location: arch/x86/kernel/cpu/microcode/amd.c:457
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072b62)
Location: arch/x86/kernel/cpu/microcode/amd.c:457
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082ad2)
Location: arch/x86/kernel/cpu/microcode/amd.c:465
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084d02)
Location: arch/x86/kernel/cpu/microcode/amd.c:463
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff838d696d)
Location: arch/x86/kernel/cpu/microcode/amd.c:468
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810581b5)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810482d5)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810585e5)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059a85)
Location: arch/x86/kernel/cpu/microcode/amd.c:458
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
