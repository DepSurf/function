# Function: <code>microcode_sanity_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel_lib.c (ffffffff8104ddd0)
Location: arch/x86/kernel/cpu/microcode/intel_lib.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
**Symbols:**

```
ffffffff8104ddd0-ffffffff8104dfbe: microcode_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel_lib.c (ffffffff8104df30)
Location: arch/x86/kernel/cpu/microcode/intel_lib.c:47
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
**Symbols:**

```
ffffffff8104df30-ffffffff8104e14c: microcode_sanity_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f5f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8104f5f0-ffffffff8104f80c: microcode_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104f540)
Location: arch/x86/kernel/cpu/microcode/intel.c:219
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8104f540-ffffffff8104f748: microcode_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81052f90)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81052f90-ffffffff81053198: microcode_sanity_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81055cf0-ffffffff81055ead: microcode_sanity_check (STB_LOCAL)
ffffffff81056e48-ffffffff81056ee2: microcode_sanity_check.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81053390-ffffffff8105354d: microcode_sanity_check (STB_LOCAL)
ffffffff810544d8-ffffffff81054572: microcode_sanity_check.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81056590-ffffffff81056738: microcode_sanity_check (STB_LOCAL)
ffffffff810576f8-ffffffff81057792: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81056e40-ffffffff81056fe8: microcode_sanity_check (STB_LOCAL)
ffffffff81057fd8-ffffffff81058072: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105bff0-ffffffff8105c190: microcode_sanity_check (STB_LOCAL)
ffffffff8105d1e8-ffffffff8105d282: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105a970-ffffffff8105ab10: microcode_sanity_check (STB_LOCAL)
ffffffff81bd5f58-ffffffff81bd5ff2: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105b310-ffffffff8105b4b5: microcode_sanity_check (STB_LOCAL)
ffffffff81bc8304-ffffffff81bc839e: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff810648b0-ffffffff81064a55: microcode_sanity_check (STB_LOCAL)
ffffffff81c9c1b0-ffffffff81c9c24a: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff810711f0-ffffffff810713b7: microcode_sanity_check (STB_LOCAL)
ffffffff81e4b530-ffffffff81e4b5a7: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff810569c0-ffffffff81056b68: microcode_sanity_check (STB_LOCAL)
ffffffff81057b58-ffffffff81057bf2: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81046bd0-ffffffff81046d78: microcode_sanity_check (STB_LOCAL)
ffffffff81047d48-ffffffff81047de2: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81056df0-ffffffff81056f98: microcode_sanity_check (STB_LOCAL)
ffffffff81057f88-ffffffff81058022: microcode_sanity_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int microcode_sanity_check(void *mc, int print_err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81058290-ffffffff81058438: microcode_sanity_check (STB_LOCAL)
ffffffff81059428-ffffffff810594c2: microcode_sanity_check.cold (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
