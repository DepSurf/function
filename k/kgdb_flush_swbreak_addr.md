# Function: <code>kgdb_flush_swbreak_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:226
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:226
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:226
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:227
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:227
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8115ed6e)
Location: kernel/debug/debug_core.c:227
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116ba9e)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811788ab)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff81178310-ffffffff8117831b: kgdb_flush_swbreak_addr.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811846fb)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff811841e0-ffffffff811841eb: kgdb_flush_swbreak_addr.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81198750)
Location: kernel/debug/debug_core.c:282
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81195510)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff811955e0-ffffffff811955eb: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81196500)
Location: kernel/debug/debug_core.c:283
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff811965d0-ffffffff811965db: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811bf79a)
Location: kernel/debug/debug_core.c:280
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff811bf5b0-ffffffff811bf61f: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811f2dca)
Location: kernel/debug/debug_core.c:281
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff811f2a50-ffffffff811f2ac7: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff812395a0)
Location: kernel/debug/debug_core.c:280
Inline: True
```
**Symbols:**

```
ffffffff812395a0-ffffffff812395af: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff812505b0)
Location: kernel/debug/debug_core.c:280
Inline: True
```
**Symbols:**

```
ffffffff812505b0-ffffffff812505bf: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126a400)
Location: kernel/debug/debug_core.c:280
Inline: True
```
**Symbols:**

```
ffffffff8126a400-ffffffff8126a40f: kgdb_flush_swbreak_addr (STB_LOCAL)
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
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffff8000101f97e8)
Location: kernel/debug/debug_core.c:284
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffff8000101f97e8-ffff8000101f9834: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c0439968)
Location: kernel/debug/debug_core.c:284
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
c0439968-c04399ec: kgdb_flush_swbreak_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kgdb_flush_swbreak_addr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (c000000000271050)
Location: kernel/debug/debug_core.c:284
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
c000000000271050-c000000000271088: kgdb_flush_swbreak_addr (STB_LOCAL)
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117cd1b)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff8117c800-ffffffff8117c80b: kgdb_flush_swbreak_addr.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116fe9b)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff8116f9a0-ffffffff8116f9ab: kgdb_flush_swbreak_addr.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117aaeb)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff8117a5d0-ffffffff8117a5db: kgdb_flush_swbreak_addr.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8118841b)
Location: kernel/debug/debug_core.c:284
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
Direct callers:
  - kernel/debug/debug_core.c:dbg_deactivate_sw_breakpoints
  - kernel/debug/debug_core.c:dbg_activate_sw_breakpoints
```
**Symbols:**

```
ffffffff81187f00-ffffffff81187f0b: kgdb_flush_swbreak_addr.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
