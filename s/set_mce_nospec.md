# Function: <code>set_mce_nospec</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104e772)
Location: arch/x86/include/asm/set_memory.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104be49)
Location: arch/x86/include/asm/set_memory.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ed4e)
Location: arch/x86/include/asm/set_memory.h:96
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f700)
Location: arch/x86/include/asm/set_memory.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052cd0)
Location: arch/x86/include/asm/set_memory.h:95
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff81052200-ffffffff81052248: set_mce_nospec.isra.0 (STB_LOCAL)
ffffffff81053b8f-ffffffff81053ba3: set_mce_nospec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051e20)
Location: arch/x86/include/asm/set_memory.h:96
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff81051330-ffffffff81051378: set_mce_nospec.isra.0 (STB_LOCAL)
ffffffff81bd5713-ffffffff81bd5727: set_mce_nospec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810535f0)
Location: arch/x86/include/asm/set_memory.h:96
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff81052aa0-ffffffff81052ae8: set_mce_nospec.isra.0 (STB_LOCAL)
ffffffff81bc7b6b-ffffffff81bc7b7f: set_mce_nospec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105bcc0)
Location: arch/x86/include/asm/set_memory.h:96
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff8105b060-ffffffff8105b0a8: set_mce_nospec.isra.0 (STB_LOCAL)
ffffffff81c9b664-ffffffff81c9b678: set_mce_nospec.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_mce_nospec(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:1919
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_never
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff81e50a07-ffffffff81e50a1b: set_mce_nospec.cold (STB_LOCAL)
ffffffff810b3260-ffffffff810b330d: set_mce_nospec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_mce_nospec(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cdce0)
Location: arch/x86/mm/pat/set_memory.c:2015
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff810cdce0-ffffffff810cdd99: set_mce_nospec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_mce_nospec(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d12a0)
Location: arch/x86/mm/pat/set_memory.c:2016
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_never
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff810d12a0-ffffffff810d135d: set_mce_nospec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_mce_nospec(long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d9980)
Location: arch/x86/mm/pat/set_memory.c:2020
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_never
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
```
**Symbols:**

```
ffffffff810d9980-ffffffff810d9a3d: set_mce_nospec (STB_GLOBAL)
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f809)
Location: arch/x86/include/asm/set_memory.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ed80)
Location: arch/x86/include/asm/set_memory.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104f6b0)
Location: arch/x86/include/asm/set_memory.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
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
In arch/x86/kernel/cpu/mce/core.c (ffffffff81050af0)
Location: arch/x86/include/asm/set_memory.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
