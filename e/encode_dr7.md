# Function: <code>encode_dr7</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81036f86)
Location: arch/x86/kernel/hw_breakpoint.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
```
**Symbols:**

```
ffffffff810370a0-ffffffff810370cc: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81036140)
Location: arch/x86/kernel/hw_breakpoint.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff810362a0-ffffffff810362d4: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81035e60)
Location: arch/x86/kernel/hw_breakpoint.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81035fc0-ffffffff81035ff4: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81033dea)
Location: arch/x86/kernel/hw_breakpoint.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81033f40-ffffffff81033f74: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103613a)
Location: arch/x86/kernel/hw_breakpoint.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81036290-ffffffff810362c4: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff810371ea)
Location: arch/x86/kernel/hw_breakpoint.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81037300-ffffffff81037334: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff810383fa)
Location: arch/x86/kernel/hw_breakpoint.c:78
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81038510-ffffffff81038544: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103a99a)
Location: arch/x86/kernel/hw_breakpoint.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103aab0-ffffffff8103aae4: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b16a)
Location: arch/x86/kernel/hw_breakpoint.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103b280-ffffffff8103b2b4: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103dd5a)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_write_dr7
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103e1c0-ffffffff8103e1f1: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e39d)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_write_dr7
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103e270-ffffffff8103e2a1: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103fcd9)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103fbc0-ffffffff8103fbed: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81045c37)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81c998b4-ffffffff81c998f0: encode_dr7.cold (STB_LOCAL)
ffffffff81045a90-ffffffff81045ae3: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104e7bc)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff81e49361-ffffffff81e4939d: encode_dr7.cold (STB_LOCAL)
ffffffff8104e600-ffffffff8104e65f: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b56c)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff82052455-ffffffff82052491: encode_dr7.cold (STB_LOCAL)
ffffffff8105b390-ffffffff8105b3ef: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105caac)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff820d094e-ffffffff820d098a: encode_dr7.cold (STB_LOCAL)
ffffffff8105c8d0-ffffffff8105c92f: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81063b6c)
Location: arch/x86/kernel/hw_breakpoint.c:68
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff821ab477-ffffffff821ab4b3: encode_dr7.cold (STB_LOCAL)
ffffffff81063990-ffffffff810639ef: encode_dr7 (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b2ca)
Location: arch/x86/kernel/hw_breakpoint.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103b3e0-ffffffff8103b414: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8102aada)
Location: arch/x86/kernel/hw_breakpoint.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8102abc0-ffffffff8102abf4: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b12a)
Location: arch/x86/kernel/hw_breakpoint.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103b240-ffffffff8103b274: encode_dr7 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int encode_dr7(int drnum, unsigned int len, unsigned int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c12a)
Location: arch/x86/kernel/hw_breakpoint.c:66
Inline: True
Inline callers:
  - arch/x86/kernel/hw_breakpoint.c:aout_dump_debugregs
  - arch/x86/kernel/hw_breakpoint.c:arch_install_hw_breakpoint
Direct callers:
  - arch/x86/kernel/kgdb.c:kgdb_disable_hw_debug
  - arch/x86/kernel/kgdb.c:kgdb_remove_all_hw_break
  - arch/x86/kernel/kgdb.c:kgdb_correct_hw_break
```
**Symbols:**

```
ffffffff8103c240-ffffffff8103c274: encode_dr7 (STB_GLOBAL)
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
