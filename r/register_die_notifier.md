# Function: <code>register_die_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a1810)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810a1810-ffffffff810a1834: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a4f30)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810a4f30-ffffffff810a4f54: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810aab90)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810aab90-ffffffff810aabb4: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810a7690)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:early_trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810a7690-ffffffff810a76b4: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810ade10)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:early_trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810ade10-ffffffff810ade34: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b4c80)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:early_trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810b4c80-ffffffff810b4ca4: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810bddd0)
Location: kernel/notifier.c:553
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:early_trace_init
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:init_uprobes
```
**Symbols:**

```
ffffffff810bddd0-ffffffff810bddf4: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c3f40)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810c3f40-ffffffff810c3f66: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cd050)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810cd050-ffffffff810cd076: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d6cd0)
Location: kernel/notifier.c:520
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:int3_selftest
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810d6cd0-ffffffff810d6d19: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1760)
Location: kernel/notifier.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:int3_selftest
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810d1760-ffffffff810d17a9: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d3340)
Location: kernel/notifier.c:552
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810d3340-ffffffff810d3389: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6450)
Location: kernel/notifier.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810e6450-ffffffff810e64d4: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100660)
Location: kernel/notifier.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:int3_selftest
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff81100660-ffffffff811006fa: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125590)
Location: kernel/notifier.c:597
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:int3_selftest
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff81125590-ffffffff8112562a: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132ed0)
Location: kernel/notifier.c:600
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:int3_selftest
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff81132ed0-ffffffff81132f21: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113dde0)
Location: kernel/notifier.c:600
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:int3_selftest
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff8113dde0-ffffffff8113de31: register_die_notifier (STB_GLOBAL)
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
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffff80001012c3e0)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/arm64/kernel/kgdb.c:kgdb_arch_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
**Symbols:**

```
ffff80001012c3e0-ffff80001012c418: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c037c3c8)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/arm/kernel/kgdb.c:kgdb_arch_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
```
**Symbols:**

```
c037c3c8-c037c3f8: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (c000000000174c80)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
c000000000174c80-c000000000174cc4: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffe0000e0b96)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
```
**Symbols:**

```
ffffffe0000e0b96-ffffffe0000e0bd0: register_die_notifier (STB_GLOBAL)
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
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c73d0)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810c73d0-ffffffff810c73f6: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810b5bf0)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff810b5bf0-ffffffff810b5c16: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810c6920)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810c6920-ffffffff810c6946: register_die_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_die_notifier(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810cede0)
Location: kernel/notifier.c:555
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/kmmio.c:kmmio_init
  - kernel/kprobes.c:init_kprobes
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/events/hw_breakpoint.c:init_hw_breakpoint
  - kernel/events/uprobes.c:uprobes_init
```
**Symbols:**

```
ffffffff810cede0-ffffffff810cee06: register_die_notifier (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
