# Function: <code>match_option</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff826b4c12)
Location: arch/x86/kernel/cpu/bugs.c:136
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81043d3c)
Location: arch/x86/kernel/cpu/bugs.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81043d3c-ffffffff81043d79: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810456fc)
Location: arch/x86/kernel/cpu/bugs.c:239
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff810456fc-ffffffff81045739: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81047ea8)
Location: arch/x86/kernel/cpu/bugs.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81047ea8-ffffffff81047ee5: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81048738)
Location: arch/x86/kernel/cpu/bugs.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81048738-ffffffff81048775: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8104c7db)
Location: arch/x86/kernel/cpu/bugs.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff82cd5118)
Location: arch/x86/kernel/cpu/intel.c:996
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
```
**Symbols:**

```
ffffffff8104c7db-ffffffff8104c81b: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81bd5078)
Location: arch/x86/kernel/cpu/bugs.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff82fc10d0)
Location: arch/x86/kernel/cpu/intel.c:997
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:split_lock_setup
```
**Symbols:**

```
ffffffff81bd5078-ffffffff81bd50b8: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81bc742c)
Location: arch/x86/kernel/cpu/bugs.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff831cb7c2)
Location: arch/x86/kernel/cpu/intel.c:1002
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_setup
```
**Symbols:**

```
ffffffff81bc742c-ffffffff81bc746e: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81c9abbf)
Location: arch/x86/kernel/cpu/bugs.c:680
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff832ace45)
Location: arch/x86/kernel/cpu/intel.c:1009
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
**Symbols:**

```
ffffffff81c9abbf-ffffffff81c9ac01: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81e4a055)
Location: arch/x86/kernel/cpu/bugs.c:1005
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff8345dbfa)
Location: arch/x86/kernel/cpu/intel.c:1039
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
**Symbols:**

```
ffffffff81e4a055-ffffffff81e4a0a3: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7d51b)
Location: arch/x86/kernel/cpu/bugs.c:1042
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff83e7eb9f)
Location: arch/x86/kernel/cpu/intel.c:1205
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff836a018b)
Location: arch/x86/kernel/cpu/bugs.c:1154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff836a18ff)
Location: arch/x86/kernel/cpu/intel.c:1205
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff838d05cb)
Location: arch/x86/kernel/cpu/bugs.c:1219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation
```
```
In arch/x86/kernel/cpu/intel.c (ffffffff838d19ff)
Location: arch/x86/kernel/cpu/intel.c:1021
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
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
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810488a8)
Location: arch/x86/kernel/cpu/bugs.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff810488a8-ffffffff810488e5: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81037c18)
Location: arch/x86/kernel/cpu/bugs.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81037c18-ffffffff81037c55: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff810486e8)
Location: arch/x86/kernel/cpu/bugs.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff810486e8-ffffffff81048725: match_option (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool match_option(const char *arg, int arglen, const char *opt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff81049af8)
Location: arch/x86/kernel/cpu/bugs.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
**Symbols:**

```
ffffffff81049af8-ffffffff81049b35: match_option (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
