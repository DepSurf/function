# Function: <code>hw_breakpoint_arch_parse</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811e3af5)
Location: kernel/events/hw_breakpoint.c:404
Inline: True
```
**Symbols:**

```
ffffffff811e4030-ffffffff811e4073: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81038920)
Location: arch/x86/kernel/hw_breakpoint.c:329
Inline: False
```
**Symbols:**

```
ffffffff81038920-ffffffff81038a78: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103aec0)
Location: arch/x86/kernel/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff8103aec0-ffffffff8103b006: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b690)
Location: arch/x86/kernel/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff8103b690-ffffffff8103b7d6: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e540)
Location: arch/x86/kernel/hw_breakpoint.c:400
Inline: False
```
**Symbols:**

```
ffffffff8103e540-ffffffff8103e5b2: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103e5f0)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
```
**Symbols:**

```
ffffffff8103e5f0-ffffffff8103e662: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103fef0)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
```
**Symbols:**

```
ffffffff8103fef0-ffffffff8103ff62: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81045eb0)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
```
**Symbols:**

```
ffffffff81045eb0-ffffffff81045f22: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8104ea80)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8104ea80-ffffffff8104eb0a: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105b870)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8105b870-ffffffff8105b9f3: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8105cdb0)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff8105cdb0-ffffffff8105cf29: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff81063e70)
Location: arch/x86/kernel/hw_breakpoint.c:422
Inline: False
Direct callers:
  - kernel/events/hw_breakpoint.c:modify_user_hw_breakpoint_check
  - kernel/events/hw_breakpoint.c:register_perf_hw_breakpoint
```
**Symbols:**

```
ffffffff81063e70-ffffffff81063fe9: hw_breakpoint_arch_parse (STB_GLOBAL)
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
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/hw_breakpoint.c (ffff8000100a64d8)
Location: arch/arm64/kernel/hw_breakpoint.c:507
Inline: False
```
**Symbols:**

```
ffff8000100a64d8-ffff8000100a67a8: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/hw_breakpoint.c (c0317354)
Location: arch/arm/kernel/hw_breakpoint.c:583
Inline: False
```
**Symbols:**

```
c0317354-c03176e8: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/hw_breakpoint.c (c0000000000386e0)
Location: arch/powerpc/kernel/hw_breakpoint.c:132
Inline: False
```
**Symbols:**

```
c0000000000386e0-c000000000038874: hw_breakpoint_arch_parse (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b7f0)
Location: arch/x86/kernel/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff8103b7f0-ffffffff8103b936: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8102afa0)
Location: arch/x86/kernel/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff8102afa0-ffffffff8102b0e6: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103b650)
Location: arch/x86/kernel/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff8103b650-ffffffff8103b796: hw_breakpoint_arch_parse (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hw_breakpoint_arch_parse(struct perf_event *bp, const struct perf_event_attr *attr, struct arch_hw_breakpoint *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hw_breakpoint.c (ffffffff8103c650)
Location: arch/x86/kernel/hw_breakpoint.c:314
Inline: False
```
**Symbols:**

```
ffffffff8103c650-ffffffff8103c796: hw_breakpoint_arch_parse (STB_GLOBAL)
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
