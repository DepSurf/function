# Function: <code>mce_rdmsrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810446c0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:372
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
```
**Symbols:**

```
ffffffff810446c0-ffffffff810447ca: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044770)
Location: arch/x86/kernel/cpu/mcheck/mce.c:415
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
```
**Symbols:**

```
ffffffff81044770-ffffffff81044819: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046320)
Location: arch/x86/kernel/cpu/mcheck/mce.c:440
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
```
**Symbols:**

```
ffffffff81046320-ffffffff810463c9: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045fc0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:371
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
```
**Symbols:**

```
ffffffff81045fc0-ffffffff8104605f: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810497e0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:380
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
```
**Symbols:**

```
ffffffff810497e0-ffffffff8104987f: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c020)
Location: arch/x86/kernel/cpu/mcheck/mce.c:377
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:machine_check_poll
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_read_aux
```
**Symbols:**

```
ffffffff8104c020-ffffffff8104c0c1: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049710)
Location: arch/x86/kernel/cpu/mce/core.c:375
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff81049710-ffffffff810497b1: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c6d0)
Location: arch/x86/kernel/cpu/mce/core.c:392
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff8104c6d0-ffffffff8104c775: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d090)
Location: arch/x86/kernel/cpu/mce/core.c:392
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff8104d090-ffffffff8104d135: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051c40)
Location: arch/x86/kernel/cpu/mce/core.c:374
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff81051c40-ffffffff81051ce1: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c36a50)
Location: arch/x86/kernel/cpu/mce/core.c:395
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff81c36a50-ffffffff81c36a8e: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81c28f00)
Location: arch/x86/kernel/cpu/mce/core.c:395
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff81c28f00-ffffffff81c28f3e: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81d47090)
Location: arch/x86/kernel/cpu/mce/core.c:404
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:__mc_scan_banks
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff81d47090-ffffffff81d470ce: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81f15e20)
Location: arch/x86/kernel/cpu/mce/core.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
```
**Symbols:**

```
ffffffff81f15e20-ffffffff81f15e72: mce_rdmsrl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff820bd3e0)
Location: arch/x86/kernel/cpu/mce/core.c:342
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
```
**Symbols:**

```
ffffffff820bd3e0-ffffffff820bd432: mce_rdmsrl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8213edf0)
Location: arch/x86/kernel/cpu/mce/core.c:336
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
```
**Symbols:**

```
ffffffff8213edf0-ffffffff8213ee42: mce_rdmsrl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff82220e10)
Location: arch/x86/kernel/cpu/mce/core.c:367
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:quirk_skylake_repmov
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
  - arch/x86/kernel/cpu/mce/core.c:mce_gather_info
```
**Symbols:**

```
ffffffff82220e10-ffffffff82220e62: mce_rdmsrl (STB_GLOBAL)
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
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d200)
Location: arch/x86/kernel/cpu/mce/core.c:392
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff8104d200-ffffffff8104d2a5: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103c680)
Location: arch/x86/kernel/cpu/mce/core.c:392
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff8103c680-ffffffff8103c722: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d040)
Location: arch/x86/kernel/cpu/mce/core.c:392
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff8104d040-ffffffff8104d0e5: mce_rdmsrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 mce_rdmsrl(u32 msr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e450)
Location: arch/x86/kernel/cpu/mce/core.c:392
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:machine_check_poll
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
  - arch/x86/kernel/cpu/mce/core.c:mce_read_aux
```
**Symbols:**

```
ffffffff8104e450-ffffffff8104e4f5: mce_rdmsrl (STB_LOCAL)
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
