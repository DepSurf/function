# Function: <code>is_blacklisted</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810532a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:946
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810532a0-ffffffff81053339: is_blacklisted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:954
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81055fb0-ffffffff81056022: is_blacklisted (STB_LOCAL)
ffffffff81056ee2-ffffffff81056f17: is_blacklisted.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105371e)
Location: arch/x86/kernel/cpu/microcode/intel.c:954
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810536c0-ffffffff8105372f: is_blacklisted (STB_LOCAL)
ffffffff81054572-ffffffff810545a7: is_blacklisted.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810568ae)
Location: arch/x86/kernel/cpu/microcode/intel.c:945
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81056850-ffffffff810568c4: is_blacklisted (STB_LOCAL)
ffffffff81057792-ffffffff810577c8: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105715e)
Location: arch/x86/kernel/cpu/microcode/intel.c:945
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81057100-ffffffff81057174: is_blacklisted (STB_LOCAL)
ffffffff81058072-ffffffff810580a8: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:946
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8105c190-ffffffff8105c204: is_blacklisted (STB_LOCAL)
ffffffff8105d282-ffffffff8105d2b8: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8105ab10-ffffffff8105ab84: is_blacklisted (STB_LOCAL)
ffffffff81bd5ff2-ffffffff81bd6028: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff8105b4c0-ffffffff8105b534: is_blacklisted (STB_LOCAL)
ffffffff81bc839e-ffffffff81bc83d4: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81064b00-ffffffff81064bb2: is_blacklisted (STB_LOCAL)
ffffffff81c9c24a-ffffffff81c9c2b9: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_user
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810714c0-ffffffff81071586: is_blacklisted (STB_LOCAL)
ffffffff81e4b5a7-ffffffff81e4b5ee: is_blacklisted.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081aa6)
Location: arch/x86/kernel/cpu/microcode/intel.c:725
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083fe6)
Location: arch/x86/kernel/cpu/microcode/intel.c:717
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b6e6)
Location: arch/x86/kernel/cpu/microcode/intel.c:570
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
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

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056cde)
Location: arch/x86/kernel/cpu/microcode/intel.c:945
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81056c80-ffffffff81056cf4: is_blacklisted (STB_LOCAL)
ffffffff81057bf2-ffffffff81057c28: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81046eee)
Location: arch/x86/kernel/cpu/microcode/intel.c:945
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81046e90-ffffffff81046f04: is_blacklisted (STB_LOCAL)
ffffffff81047de2-ffffffff81047e18: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105710e)
Location: arch/x86/kernel/cpu/microcode/intel.c:945
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff810570b0-ffffffff81057124: is_blacklisted (STB_LOCAL)
ffffffff81058022-ffffffff81058058: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool is_blacklisted(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810585ae)
Location: arch/x86/kernel/cpu/microcode/intel.c:945
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:request_microcode_fw
```
**Symbols:**

```
ffffffff81058550-ffffffff810585c4: is_blacklisted (STB_LOCAL)
ffffffff810594c2-ffffffff810594f8: is_blacklisted.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
