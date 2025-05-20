# Function: <code>machine_check_poll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810451b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:568
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:__mcheck_cpu_init_generic
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff810451b0-ffffffff81045428: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81045230)
Location: arch/x86/kernel/cpu/mcheck/mce.c:633
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81045230-ffffffff810454e8: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046e30)
Location: arch/x86/kernel/cpu/mcheck/mce.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81046e30-ffffffff810470f3: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046780)
Location: arch/x86/kernel/cpu/mcheck/mce.c:673
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81046780-ffffffff8104698c: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104a1b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:683
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104a1b0-ffffffff8104a3d7: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104c860)
Location: arch/x86/kernel/cpu/mcheck/mce.c:689
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104c860-ffffffff8104ca84: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81049f50)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81049f50-ffffffff8104a162: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d0b0)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104d0b0-ffffffff8104d2e7: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104da50)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104da50-ffffffff8104dc87: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053100)
Location: arch/x86/kernel/cpu/mce/core.c:672
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81053100-ffffffff81053362: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052250)
Location: arch/x86/kernel/cpu/mce/core.c:738
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81052250-ffffffff81052484: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053b00)
Location: arch/x86/kernel/cpu/mce/core.c:738
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81053b00-ffffffff81053d34: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81c9b7ec-ffffffff81c9b801: machine_check_poll.cold (STB_LOCAL)
ffffffff8105c320-ffffffff8105c59b: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:672
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff81e4acdf-ffffffff81e4acf3: machine_check_poll.cold (STB_LOCAL)
ffffffff81068a00-ffffffff81068c89: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:672
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff82052de3-ffffffff82052e04: machine_check_poll.cold (STB_LOCAL)
ffffffff810784d0-ffffffff8107873d: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:658
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff820d1312-ffffffff820d1333: machine_check_poll.cold (STB_LOCAL)
ffffffff8107a780-ffffffff8107a9ed: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:679
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mc_poll_banks_default
  - arch/x86/kernel/cpu/mce/intel.c:cmci_mc_poll_banks
  - arch/x86/kernel/cpu/mce/intel.c:intel_threshold_interrupt
```
**Symbols:**

```
ffffffff821abe65-ffffffff821abea7: machine_check_poll.cold (STB_LOCAL)
ffffffff81081cb0-ffffffff81081f4d: machine_check_poll (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104dbb0)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104dbb0-ffffffff8104dde7: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103d060)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8103d060-ffffffff8103d297: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104da00)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104da00-ffffffff8104dc37: machine_check_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool machine_check_poll(enum mcp_flags flags, mce_banks_t *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ee40)
Location: arch/x86/kernel/cpu/mce/core.c:692
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_cmci_poll
```
**Symbols:**

```
ffffffff8104ee40-ffffffff8104f077: machine_check_poll (STB_GLOBAL)
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
