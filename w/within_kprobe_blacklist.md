# Function: <code>within_kprobe_blacklist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112ec60)
Location: kernel/kprobes.c:1335
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
**Symbols:**

```
ffffffff8112ec60-ffffffff8112eca9: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81136ee0)
Location: kernel/kprobes.c:1335
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
**Symbols:**

```
ffffffff81136ee0-ffffffff81136f32: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140c60)
Location: kernel/kprobes.c:1335
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
**Symbols:**

```
ffffffff81140c60-ffffffff81140cb2: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811423d0)
Location: kernel/kprobes.c:1377
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
**Symbols:**

```
ffffffff811423d0-ffffffff81142422: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114f190)
Location: kernel/kprobes.c:1379
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
**Symbols:**

```
ffffffff8114f190-ffffffff8114f1e2: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115dc30)
Location: kernel/kprobes.c:1408
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:arch_validate_hwbkpt_settings
```
**Symbols:**

```
ffffffff8115dc30-ffffffff8115dc82: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a850)
Location: kernel/kprobes.c:1399
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff8116a850-ffffffff8116a899: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811775a0)
Location: kernel/kprobes.c:1401
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff811775a0-ffffffff81177637: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff81177640-ffffffff81177678: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811834d0)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff811834d0-ffffffff81183567: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff81183570-ffffffff811835a8: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811973a0)
Location: kernel/kprobes.c:1486
Inline: True
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff811973a0-ffffffff81197456: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff81197460-ffffffff811974b6: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811944b0)
Location: kernel/kprobes.c:1450
Inline: True
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff811944b0-ffffffff81194566: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff81194570-ffffffff811945c6: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811954e0)
Location: kernel/kprobes.c:1451
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff811954e0-ffffffff81195598: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff811955a0-ffffffff811955f6: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811be440)
Location: kernel/kprobes.c:1443
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff811be440-ffffffff811be4f8: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff811be500-ffffffff811be556: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f17d0)
Location: kernel/kprobes.c:1400
Inline: False
Direct callers:
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff811f17d0-ffffffff811f18e1: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81238410)
Location: kernel/kprobes.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff81238410-ffffffff81238521: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124f4f0)
Location: kernel/kprobes.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff8124f4f0-ffffffff8124f601: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81269420)
Location: kernel/kprobes.c:1397
Inline: False
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
  - kernel/kprobes.c:check_kprobe_address_safe
  - kernel/debug/debug_core.c:kgdb_validate_break_address
```
**Symbols:**

```
ffffffff81269420-ffffffff81269531: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffff8000101f8ab0)
Location: kernel/kprobes.c:1446
Inline: True
```
**Symbols:**

```
ffff8000101f8ab0-ffff8000101f8b54: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffff8000101f8b58-ffff8000101f8ba8: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c0438d78)
Location: kernel/kprobes.c:1446
Inline: True
```
**Symbols:**

```
c0438d78-c0438e20: within_kprobe_blacklist.part.0 (STB_LOCAL)
c0438e20-c0438e60: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c00000000026fe20)
Location: kernel/kprobes.c:1446
Inline: True
```
**Symbols:**

```
c00000000026fe20-c00000000026fee4: within_kprobe_blacklist.part.0 (STB_LOCAL)
c00000000026fef0-c00000000026ff68: within_kprobe_blacklist (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117baf0)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff8117baf0-ffffffff8117bb87: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff8117bb90-ffffffff8117bbc8: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116ec90)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff8116ec90-ffffffff8116ed27: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff8116ed30-ffffffff8116ed68: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811798c0)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff811798c0-ffffffff81179957: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff81179960-ffffffff81179998: within_kprobe_blacklist (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool within_kprobe_blacklist(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811871d0)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - arch/x86/kernel/hw_breakpoint.c:hw_breakpoint_arch_parse
```
**Symbols:**

```
ffffffff811871d0-ffffffff81187267: within_kprobe_blacklist.part.0 (STB_LOCAL)
ffffffff81187270-ffffffff811872a8: within_kprobe_blacklist (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
