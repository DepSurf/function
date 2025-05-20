# Function: <code>perf_callchain_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007640)
Location: arch/x86/events/core.c:2279
Inline: True
Direct callers:
  - kernel/events/callchain.c:perf_callchain
```
**Symbols:**

```
ffffffff81007640-ffffffff8100786f: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810077d0)
Location: arch/x86/events/core.c:2375
Inline: True
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff810077d0-ffffffff81007aa8: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007870)
Location: arch/x86/events/core.c:2388
Inline: True
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007870-ffffffff81007abf: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007600)
Location: arch/x86/events/core.c:2407
Inline: True
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007600-ffffffff8100781e: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007a30)
Location: arch/x86/events/core.c:2442
Inline: True
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007a30-ffffffff81007c73: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008060)
Location: arch/x86/events/core.c:2448
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008060-ffffffff810082a5: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007f40)
Location: arch/x86/events/core.c:2464
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81007f40-ffffffff81008185: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008230)
Location: arch/x86/events/core.c:2430
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008230-ffffffff81008390: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008450)
Location: arch/x86/events/core.c:2519
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008450-ffffffff8100868e: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810094c0)
Location: arch/x86/events/core.c:2526
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff810094c0-ffffffff8100963b: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008570)
Location: arch/x86/events/core.c:2637
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008570-ffffffff810087d1: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008f40)
Location: arch/x86/events/core.c:2867
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008f40-ffffffff81009163: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8128eea0)
Location: arch/x86/events/core.c:2867
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81c953d4-ffffffff81c95453: perf_callchain_user.cold (STB_LOCAL)
ffffffff81009df0-ffffffff8100a085: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff812e3dc0)
Location: arch/x86/events/core.c:2880
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81e4469c-ffffffff81e446ff: perf_callchain_user.cold (STB_LOCAL)
ffffffff81009540-ffffffff810097b9: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8134c4c0)
Location: arch/x86/events/core.c:2864
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff820503a3-ffffffff82050406: perf_callchain_user.cold (STB_LOCAL)
ffffffff8100a9e0-ffffffff8100ac5a: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8137d510)
Location: arch/x86/events/core.c:2862
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff820ce801-ffffffff820ce85b: perf_callchain_user.cold (STB_LOCAL)
ffffffff8100a230-ffffffff8100a44b: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff813a6770)
Location: arch/x86/events/core.c:2859
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff821a903d-ffffffff821a9097: perf_callchain_user.cold (STB_LOCAL)
ffffffff8100f950-ffffffff8100fb6b: perf_callchain_user (STB_GLOBAL)
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
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/perf_callchain.c (ffff8000100a3490)
Location: arch/arm64/kernel/perf_callchain.c:102
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffff8000100a3490-ffff8000100a3928: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/perf_callchain.c (c0317bc4)
Location: arch/arm/kernel/perf_callchain.c:63
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
c0317bc4-c0317df4: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/callchain.c (c0000000001257e0)
Location: arch/powerpc/perf/callchain.c:487
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
c0000000001257e0-c000000000125f60: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/perf_callchain.c (ffffffe0000b9942)
Location: arch/riscv/kernel/perf_callchain.c:60
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffe0000b9942-ffffffe0000b99dc: perf_callchain_user (STB_GLOBAL)
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
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008450)
Location: arch/x86/events/core.c:2519
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008450-ffffffff8100868e: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006c40)
Location: arch/x86/events/core.c:2519
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81006c40-ffffffff81006e7e: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008410)
Location: arch/x86/events/core.c:2519
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008410-ffffffff8100864e: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void perf_callchain_user(struct perf_callchain_entry_ctx *entry, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008570)
Location: arch/x86/events/core.c:2519
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81008570-ffffffff810087ae: perf_callchain_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct perf_callchain_entry *entry</code> ➡️ <code>struct perf_callchain_entry_ctx *entry</code>
</li>
</ul>
</details>
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
