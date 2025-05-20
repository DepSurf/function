# Function: <code>cmdline_find_option</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff819821b0)
Location: arch/x86/lib/cmdline.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt.c:sme_enable
```
**Symbols:**

```
ffffffff819821b0-ffffffff8198239e: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff819de6e0)
Location: arch/x86/lib/cmdline.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff819de6e0-ffffffff819de8af: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81a19610)
Location: arch/x86/lib/cmdline.c:210
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81a19610-ffffffff81a197df: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81a89320)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81a89320-ffffffff81a894f0: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81ac05c0)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81ac05c0-ffffffff81ac0790: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff815fc8b0)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/crash.c:crash_reserve_low_1M
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff815fc8b0-ffffffff815fca80: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff816214d0)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/crash.c:crash_reserve_low_1M
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff816214d0-ffffffff816216a1: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81604de0)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/kernel/cpu/intel.c:sld_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/kernel/crash.c:crash_reserve_low_1M
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81604de0-ffffffff81604fa7: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff816736d0)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff816736d0-ffffffff81673897: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff8178dd20)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8178dd20-ffffffff8178de26: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff8204b500)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff8204b500-ffffffff8204b606: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff820c9db0)
Location: arch/x86/lib/cmdline.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff820c9db0-ffffffff820c9ed6: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff821a4730)
Location: arch/x86/lib/cmdline.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:cpu_parse_early_param
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff821a4730-ffffffff821a4856: cmdline_find_option (STB_GLOBAL)
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
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81a5f410)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81a5f410-ffffffff81a5f5e0: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81a1c4e0)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81a1c4e0-ffffffff81a1c6b0: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81acb800)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81acb800-ffffffff81acb9d0: cmdline_find_option (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cmdline_find_option(const char *cmdline, const char *option, char *buffer, int bufsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cmdline.c (ffffffff81ad7d50)
Location: arch/x86/lib/cmdline.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/tsx.c:tsx_init
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - arch/x86/mm/mem_encrypt_identity.c:sme_enable
```
**Symbols:**

```
ffffffff81ad7d50-ffffffff81ad7f20: cmdline_find_option (STB_GLOBAL)
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
