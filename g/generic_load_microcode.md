# Function: <code>generic_load_microcode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d7f0)
Location: arch/x86/kernel/cpu/microcode/intel.c:900
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
```
**Symbols:**

```
ffffffff8104d7f0-ffffffff8104da6f: generic_load_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d780)
Location: arch/x86/kernel/cpu/microcode/intel.c:958
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8104d780-ffffffff8104d9f7: generic_load_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fcf0)
Location: arch/x86/kernel/cpu/microcode/intel.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8104fcf0-ffffffff8104ff8e: generic_load_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fd70)
Location: arch/x86/kernel/cpu/microcode/intel.c:832
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8104fd70-ffffffff8104fffe: generic_load_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053720)
Location: arch/x86/kernel/cpu/microcode/intel.c:856
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81053720-ffffffff810539d8: generic_load_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810563b0-ffffffff8105665b: generic_load_microcode (STB_LOCAL)
ffffffff81056f99-ffffffff81056fbd: generic_load_microcode.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, void *data, size_t size, int (*get_ucode_data)(void *, const void *, size_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81053a40-ffffffff81053ceb: generic_load_microcode (STB_LOCAL)
ffffffff81054629-ffffffff8105464d: generic_load_microcode.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81056be0-ffffffff81056e76: generic_load_microcode (STB_LOCAL)
ffffffff81057847-ffffffff81057883: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81057490-ffffffff81057744: generic_load_microcode (STB_LOCAL)
ffffffff81058127-ffffffff8105816f: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:862
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8105c750-ffffffff8105ca04: generic_load_microcode (STB_LOCAL)
ffffffff8105d337-ffffffff8105d37f: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:819
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8105afd0-ffffffff8105b287: generic_load_microcode (STB_LOCAL)
ffffffff81bd60a7-ffffffff81bd60ef: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:819
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8105b980-ffffffff8105bc37: generic_load_microcode (STB_LOCAL)
ffffffff81bc8453-ffffffff81bc849b: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:819
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81064f90-ffffffff81065296: generic_load_microcode (STB_LOCAL)
ffffffff81c9c338-ffffffff81c9c360: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:781
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810719e0-ffffffff81071d16: generic_load_microcode (STB_LOCAL)
ffffffff81e4b677-ffffffff81e4b6a7: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081670)
Location: arch/x86/kernel/cpu/microcode/intel.c:641
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81081670-ffffffff810819db: generic_load_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083ba0)
Location: arch/x86/kernel/cpu/microcode/intel.c:633
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81083ba0-ffffffff81083f14: generic_load_microcode (STB_LOCAL)
```
</details>
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
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81057010-ffffffff810572c4: generic_load_microcode (STB_LOCAL)
ffffffff81057ca7-ffffffff81057cef: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81047200-ffffffff810474b4: generic_load_microcode (STB_LOCAL)
ffffffff81047e9a-ffffffff81047ee2: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81057440-ffffffff810576f4: generic_load_microcode (STB_LOCAL)
ffffffff810580d7-ffffffff8105811f: generic_load_microcode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum ucode_state generic_load_microcode(int cpu, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:861
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810588e0-ffffffff81058b94: generic_load_microcode (STB_LOCAL)
ffffffff81059577-ffffffff810595bf: generic_load_microcode.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iov_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*get_ucode_data)(void *, const void *, size_t)</code>
</li>
</ul>
</details>
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
