# Function: <code>get_sigframe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e0d0)
Location: arch/x86/kernel/signal.c:202
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81078120)
Location: arch/x86/ia32/ia32_signal.c:214
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
```
**Symbols:**

```
ffffffff8102e0d0-ffffffff8102e261: get_sigframe.isra.8.constprop.9 (STB_LOCAL)
ffffffff81078120-ffffffff81078244: get_sigframe.isra.3.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d190)
Location: arch/x86/kernel/signal.c:237
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81079600)
Location: arch/x86/ia32/ia32_signal.c:214
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8102d190-ffffffff8102d34c: get_sigframe.isra.12.constprop.13 (STB_LOCAL)
ffffffff81079600-ffffffff8107972f: get_sigframe.isra.5.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d030)
Location: arch/x86/kernel/signal.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107d3f0)
Location: arch/x86/ia32/ia32_signal.c:214
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8102d030-ffffffff8102d1ec: get_sigframe.isra.13.constprop.14 (STB_LOCAL)
ffffffff8107d3f0-ffffffff8107d51f: get_sigframe.isra.4.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102b290)
Location: arch/x86/kernel/signal.c:239
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107bbf0)
Location: arch/x86/ia32/ia32_signal.c:215
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8102b290-ffffffff8102b453: get_sigframe.isra.13.constprop.14 (STB_LOCAL)
ffffffff8107bbf0-ffffffff8107bd0e: get_sigframe.isra.4.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102bfc0)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810822f0)
Location: arch/x86/ia32/ia32_signal.c:216
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8102bfc0-ffffffff8102c183: get_sigframe.isra.13.constprop.14 (STB_LOCAL)
ffffffff810822f0-ffffffff8108240e: get_sigframe.isra.4.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102d290)
Location: arch/x86/kernel/signal.c:241
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810859b0)
Location: arch/x86/ia32/ia32_signal.c:215
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8102d290-ffffffff8102d447: get_sigframe.isra.13.constprop.14 (STB_LOCAL)
ffffffff810859b0-ffffffff81085ace: get_sigframe.isra.4.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8102e4e0)
Location: arch/x86/kernel/signal.c:241
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108c720)
Location: arch/x86/ia32/ia32_signal.c:215
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8102e4e0-ffffffff8102e697: get_sigframe.isra.13.constprop.14 (STB_LOCAL)
ffffffff8108c720-ffffffff8108c83e: get_sigframe.isra.4.constprop.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030240)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090480)
Location: arch/x86/ia32/ia32_signal.c:220
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81030240-ffffffff81030434: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
ffffffff81090480-ffffffff81090589: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030b80)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81090fe0)
Location: arch/x86/ia32/ia32_signal.c:221
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81030b80-ffffffff81030d74: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
ffffffff81090fe0-ffffffff810910e9: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810330a0)
Location: arch/x86/kernel/signal.c:232
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096bf0)
Location: arch/x86/ia32/ia32_signal.c:203
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff810330a0-ffffffff8103329c: get_sigframe.constprop.0.isra.0 (STB_LOCAL)
ffffffff81096bf0-ffffffff81096d06: get_sigframe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81033af0)
Location: arch/x86/kernel/signal.c:233
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81095e30)
Location: arch/x86/ia32/ia32_signal.c:203
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81033af0-ffffffff81033cec: get_sigframe.constprop.0.isra.0 (STB_LOCAL)
ffffffff81095e30-ffffffff81095f46: get_sigframe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:233
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81096750)
Location: arch/x86/ia32/ia32_signal.c:203
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81035630-ffffffff810357e2: get_sigframe.constprop.0.isra.0 (STB_LOCAL)
ffffffff81bc5623-ffffffff81bc564e: get_sigframe.constprop.0.isra.0.cold (STB_LOCAL)
ffffffff81096750-ffffffff81096866: get_sigframe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:x32_setup_rt_frame
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810a66f0)
Location: arch/x86/ia32/ia32_signal.c:203
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8103a910-ffffffff8103aac2: get_sigframe.constprop.0.isra.0 (STB_LOCAL)
ffffffff81c9823a-ffffffff81c98265: get_sigframe.constprop.0.isra.0.cold (STB_LOCAL)
ffffffff810a66f0-ffffffff810a6806: get_sigframe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (0)
Location: arch/x86/kernel/signal.c:241
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:__setup_rt_frame
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff810bb980)
Location: arch/x86/ia32/ia32_signal.c:202
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81041b80-ffffffff81041d37: get_sigframe.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e476d5-ffffffff81e476fc: get_sigframe.constprop.0.isra.0.cold (STB_LOCAL)
ffffffff810bb980-ffffffff810bbab2: get_sigframe.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *get_sigframe(struct ksignal *ksig, struct pt_regs *regs, size_t frame_size, void **fpstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104b2b0)
Location: arch/x86/kernel/signal.c:74
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8104b2b0-ffffffff8104b56e: get_sigframe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *get_sigframe(struct ksignal *ksig, struct pt_regs *regs, size_t frame_size, void **fpstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff8104bb50)
Location: arch/x86/kernel/signal.c:74
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff8104bb50-ffffffff8104bdfe: get_sigframe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *get_sigframe(struct ksignal *ksig, struct pt_regs *regs, size_t frame_size, void **fpstate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81052dd0)
Location: arch/x86/kernel/signal.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/signal_64.c:x64_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_rt_frame
  - arch/x86/kernel/signal_32.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81052dd0-ffffffff8105307e: get_sigframe (STB_GLOBAL)
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
In arch/arm64/kernel/signal.c (ffff800010091a90)
Location: arch/arm64/kernel/signal.c:695
Inline: True
Inline callers:
  - arch/arm64/kernel/signal.c:setup_rt_frame
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
In arch/arm/kernel/signal.c (c030ea08)
Location: arch/arm/kernel/signal.c:342
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:do_work_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *get_sigframe(struct ksignal *ksig, long unsigned int sp, size_t frame_size, int is_32);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/signal.c (c000000000023600)
Location: arch/powerpc/kernel/signal.c:36
Inline: False
Direct callers:
  - arch/powerpc/kernel/signal_32.c:handle_signal32
  - arch/powerpc/kernel/signal_32.c:handle_rt_signal32
  - arch/powerpc/kernel/signal_64.c:handle_rt_signal64
```
**Symbols:**

```
c000000000023600-c000000000023698: get_sigframe (STB_GLOBAL)
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
In arch/riscv/kernel/signal.c (ffffffe0000b6614)
Location: arch/riscv/kernel/signal.c:146
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:handle_signal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030ce0)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108ffa0)
Location: arch/x86/ia32/ia32_signal.c:221
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81030ce0-ffffffff81030ed4: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
ffffffff8108ffa0-ffffffff810900a9: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81020700)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8107eab0)
Location: arch/x86/ia32/ia32_signal.c:221
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81020700-ffffffff810208f4: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
ffffffff8107eab0-ffffffff8107ebb9: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff81030b40)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff8108ff50)
Location: arch/x86/ia32/ia32_signal.c:221
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff81030b40-ffffffff81030d34: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
ffffffff8108ff50-ffffffff81090059: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/signal.c (ffffffff810319d0)
Location: arch/x86/kernel/signal.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/signal.c:do_signal
```
```
In arch/x86/ia32/ia32_signal.c (ffffffff81092330)
Location: arch/x86/ia32/ia32_signal.c:221
Inline: True
Direct callers:
  - arch/x86/ia32/ia32_signal.c:ia32_setup_rt_frame
  - arch/x86/ia32/ia32_signal.c:ia32_setup_frame
```
**Symbols:**

```
ffffffff810319d0-ffffffff81031bc4: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
ffffffff81092330-ffffffff81092439: get_sigframe.isra.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
