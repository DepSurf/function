# Function: <code>early_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d99f0)
Location: kernel/printk/printk.c:1959
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - kernel/events/core.c:perf_sample_event_took
```
**Symbols:**

```
ffffffff810d99f0-ffffffff810d9aa5: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810debb0)
Location: kernel/printk/printk.c:2029
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810debb0-ffffffff810dec65: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e5110)
Location: kernel/printk/printk.c:1913
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:finish_e820_parsing
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810e5110-ffffffff810e51c5: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e4400)
Location: kernel/printk/printk.c:1881
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810e4400-ffffffff810e44af: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ec6a0)
Location: kernel/printk/printk.c:1869
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810ec6a0-ffffffff810ec752: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f44a0)
Location: kernel/printk/printk.c:2032
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810f44a0-ffffffff810f4558: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ffc50)
Location: kernel/printk/printk.c:2035
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810ffc50-ffffffff810ffd08: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811083a0)
Location: kernel/printk/printk.c:2090
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff811083a0-ffffffff81108458: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81114780)
Location: kernel/printk/printk.c:2100
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff81114780-ffffffff81114838: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811204a0)
Location: kernel/printk/printk.c:2114
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff811204a0-ffffffff81120558: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111b440)
Location: kernel/printk/printk.c:2191
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff8111b440-ffffffff8111b4f8: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111bb20)
Location: kernel/printk/printk.c:2260
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff8111bb20-ffffffff8111bbd8: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113bb30)
Location: kernel/printk/printk.c:2309
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff8113bb30-ffffffff8113bbe8: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115efc0)
Location: kernel/printk/printk.c:2340
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff8115efc0-ffffffff8115f0bd: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81192040)
Location: kernel/printk/printk.c:2430
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff81192040-ffffffff8119213d: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a38e0)
Location: kernel/printk/printk.c:2372
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff811a38e0-ffffffff811a39dd: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b1310)
Location: kernel/printk/printk.c:2356
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff811b1310-ffffffff811b140d: early_printk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: include/linux/printk.h:146
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: include/linux/printk.h:146
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cef60)
Location: kernel/printk/printk.c:2100
Inline: False
Direct callers:
  - kernel/events/core.c:perf_sample_event_took
```
**Symbols:**

```
c0000000001cef60-c0000000001cf030: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (0)
Location: include/linux/printk.h:146
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110cd60)
Location: kernel/printk/printk.c:2100
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff8110cd60-ffffffff8110ce18: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fdb30)
Location: kernel/printk/printk.c:2100
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff810fdb30-ffffffff810fdbe8: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110ac50)
Location: kernel/printk/printk.c:2100
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff8110ac50-ffffffff8110ad08: early_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void early_printk(const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81116060)
Location: kernel/printk/printk.c:2100
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__finish_early_params
  - arch/x86/mm/extable.c:early_fixup_exception
  - kernel/events/core.c:perf_sample_event_took
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
  - arch/x86/lib/kaslr.c:kaslr_get_random_long
```
**Symbols:**

```
ffffffff81116060-ffffffff81116118: early_printk (STB_GLOBAL)
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
