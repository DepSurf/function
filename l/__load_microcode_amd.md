# Function: <code>__load_microcode_amd</code>

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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e91c)
Location: arch/x86/kernel/cpu/microcode/amd.c:818
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104eaab)
Location: arch/x86/kernel/cpu/microcode/amd.c:828
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050af0)
Location: arch/x86/kernel/cpu/microcode/amd.c:829
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81050af0-ffffffff81050e77: __load_microcode_amd (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050cfb)
Location: arch/x86/kernel/cpu/microcode/amd.c:641
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105483e)
Location: arch/x86/kernel/cpu/microcode/amd.c:648
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057601)
Location: arch/x86/kernel/cpu/microcode/amd.c:656
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:805
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810550b0-ffffffff810552d7: __load_microcode_amd (STB_LOCAL)
ffffffff8105563c-ffffffff81055697: __load_microcode_amd.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810582e0-ffffffff81058507: __load_microcode_amd (STB_LOCAL)
ffffffff8105886e-ffffffff810588c9: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058bb0-ffffffff81058dd7: __load_microcode_amd (STB_LOCAL)
ffffffff8105913e-ffffffff81059199: __load_microcode_amd.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dfe9)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: True
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c649)
Location: arch/x86/kernel/cpu/microcode/amd.c:802
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:802
Inline: False
```
**Symbols:**

```
ffffffff8105c950-ffffffff8105cb9e: __load_microcode_amd (STB_LOCAL)
ffffffff81bc851a-ffffffff81bc8575: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:802
Inline: False
```
**Symbols:**

```
ffffffff81065ff0-ffffffff8106623e: __load_microcode_amd (STB_LOCAL)
ffffffff81c9c412-ffffffff81c9c46d: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:808
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
**Symbols:**

```
ffffffff81072c70-ffffffff81072eb1: __load_microcode_amd (STB_LOCAL)
ffffffff81e4b742-ffffffff81e4b78f: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082c80)
Location: arch/x86/kernel/cpu/microcode/amd.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
**Symbols:**

```
ffffffff81082c80-ffffffff81082ede: __load_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81085530)
Location: arch/x86/kernel/cpu/microcode/amd.c:816
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
```
**Symbols:**

```
ffffffff81085530-ffffffff8108578e: __load_microcode_amd (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c706)
Location: arch/x86/kernel/cpu/microcode/amd.c:789
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058730-ffffffff81058957: __load_microcode_amd (STB_LOCAL)
ffffffff81058cbe-ffffffff81058d19: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810488b0-ffffffff81048ad7: __load_microcode_amd (STB_LOCAL)
ffffffff81048ec8-ffffffff81048f23: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81058b60-ffffffff81058d87: __load_microcode_amd (STB_LOCAL)
ffffffff810590ee-ffffffff81059149: __load_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum ucode_state __load_microcode_amd(u8 family, const u8 *data, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:803
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:request_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105a000-ffffffff8105a227: __load_microcode_amd (STB_LOCAL)
ffffffff8105a58e-ffffffff8105a5e9: __load_microcode_amd.cold (STB_LOCAL)
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
