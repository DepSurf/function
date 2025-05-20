# Function: <code>do_early_exception</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff82fae523)
Location: arch/x86/kernel/head64.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff82fae523-ffffffff82fae57b: do_early_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff831b8523)
Location: arch/x86/kernel/head64.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff831b8523-ffffffff831b857b: do_early_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8329859d)
Location: arch/x86/kernel/head64.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff8329859d-ffffffff832985f5: do_early_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff834465c4)
Location: arch/x86/kernel/head64.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff834465c4-ffffffff83446632: do_early_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83e5f710)
Location: arch/x86/kernel/head64.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff83e5f710-ffffffff83e5f78d: do_early_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff83694960)
Location: arch/x86/kernel/head64.c:411
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff83694960-ffffffff836949dd: do_early_exception (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_early_exception(struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff838c4850)
Location: arch/x86/kernel/head64.c:410
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:handle_vc_boot_ghcb
```
**Symbols:**

```
ffffffff838c4850-ffffffff838c48cd: do_early_exception (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
