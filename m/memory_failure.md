# Function: <code>memory_failure</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812023f0)
Location: mm/memory-failure.c:1068
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_hard_offline_page
```
**Symbols:**

```
ffffffff812023f0-ffffffff81202f43: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81226860)
Location: mm/memory-failure.c:1031
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_hard_offline_page
```
**Symbols:**

```
ffffffff81226860-ffffffff812276ae: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81238e30)
Location: mm/memory-failure.c:1029
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_hard_offline_page
```
**Symbols:**

```
ffffffff81238e30-ffffffff81239c36: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812452d0)
Location: mm/memory-failure.c:1123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_hard_offline_page
```
**Symbols:**

```
ffffffff812452d0-ffffffff8124590e: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int trapno, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81265220)
Location: mm/memory-failure.c:1123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - mm/madvise.c:SyS_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_hard_offline_page
```
**Symbols:**

```
ffffffff81265220-ffffffff812658c7: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1247
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:store_hard_offline_page
```
**Symbols:**

```
ffffffff8128aaa3-ffffffff8128ab7a: memory_failure.cold.42 (STB_LOCAL)
ffffffff81289540-ffffffff81289cad: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff8129e569)
Location: mm/memory-failure.c:1251
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff8129fa0a-ffffffff8129fae4: memory_failure.cold.43 (STB_LOCAL)
ffffffff8129e390-ffffffff8129eb11: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1244
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff812b9b20-ffffffff812ba0aa: memory_failure.part.0 (STB_LOCAL)
ffffffff812bad51-ffffffff812bae12: memory_failure.part.0.cold (STB_LOCAL)
ffffffff812bae12-ffffffff812bae3b: memory_failure.cold (STB_LOCAL)
ffffffff812ba0b0-ffffffff812ba2e8: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff812cccc1-ffffffff812ccdab: memory_failure.cold (STB_LOCAL)
ffffffff812cbd80-ffffffff812cc52d: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1271
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff81302eaa-ffffffff81302f69: memory_failure.cold (STB_LOCAL)
ffffffff81301f30-ffffffff81302441: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff81bea25b-ffffffff81bea2ca: memory_failure.cold (STB_LOCAL)
ffffffff8130e5b0-ffffffff8130eabf: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1463
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff81bdc274-ffffffff81bdc2e3: memory_failure.cold (STB_LOCAL)
ffffffff81314b80-ffffffff81314fa9: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff81cc3300-ffffffff81cc3391: memory_failure.cold (STB_LOCAL)
ffffffff81360c00-ffffffff8136102f: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1758
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_never
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff81e757f9-ffffffff81e7586d: memory_failure.cold (STB_LOCAL)
ffffffff813dc2f0-ffffffff813dca53: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814632c0)
Location: mm/memory-failure.c:2007
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/madvise.c:madvise_inject_error
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff814632c0-ffffffff81463c3e: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81498f60)
Location: mm/memory-failure.c:2135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_never
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/madvise.c:do_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff81498f60-ffffffff814997a1: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c8620)
Location: mm/memory-failure.c:2185
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:kill_me_never
  - arch/x86/kernel/cpu/mce/core.c:kill_me_maybe
  - mm/madvise.c:do_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff814c8620-ffffffff814c8f19: memory_failure (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036f318)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - mm/madvise.c:__arm64_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffff80001036f318-ffff80001036fc2c: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c000000000460ee0)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - arch/powerpc/kernel/mce.c:machine_process_ue_event
  - arch/powerpc/platforms/powernv/opal-memory-errors.c:mem_error_handler
  - mm/madvise.c:__se_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
c000000000460ee0-c000000000461c34: memory_failure (STB_GLOBAL)
```
</details>
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
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff812c52a1-ffffffff812c538b: memory_failure.cold (STB_LOCAL)
ffffffff812c4360-ffffffff812c4b0d: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff812b62e1-ffffffff812b63cb: memory_failure.cold (STB_LOCAL)
ffffffff812b53a0-ffffffff812b5b4d: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff812c30b1-ffffffff812c319b: memory_failure.cold (STB_LOCAL)
ffffffff812c2170-ffffffff812c291d: memory_failure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int memory_failure(long unsigned int pfn, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1248
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - mm/madvise.c:__do_sys_madvise
  - mm/memory-failure.c:memory_failure_work_func
  - drivers/base/memory.c:hard_offline_page_store
```
**Symbols:**

```
ffffffff812d3b51-ffffffff812d3c3b: memory_failure.cold (STB_LOCAL)
ffffffff812d2c00-ffffffff812d33b7: memory_failure (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int trapno</code>
</li>
<li>
<b>Param reordered. </b>
<code>pfn, trapno, flags</code> ➡️ <code>pfn, flags</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
