# Function: <code>handle_vc_boot_ghcb</code>

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
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff82fd14f0)
Location: arch/x86/kernel/sev-es.c:1384
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff82fd14f0-ffffffff82fd16ae: handle_vc_boot_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff831dc198)
Location: arch/x86/kernel/sev.c:1465
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff831dc198-ffffffff831dc363: handle_vc_boot_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff832bf24e)
Location: arch/x86/kernel/sev.c:1461
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff832bf24e-ffffffff832bf419: handle_vc_boot_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff834716e7)
Location: arch/x86/kernel/sev.c:2007
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff834716e7-ffffffff8347185c: handle_vc_boot_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e988e0)
Location: arch/x86/kernel/sev.c:2007
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff83e988e0-ffffffff83e98a75: handle_vc_boot_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bc310)
Location: arch/x86/kernel/sev.c:1964
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff836bc310-ffffffff836bc499: handle_vc_boot_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool handle_vc_boot_ghcb(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838ecd80)
Location: arch/x86/kernel/sev.c:2002
Inline: False
Direct callers:
  - arch/x86/kernel/head64.c:do_early_exception
```
**Symbols:**

```
ffffffff838ecd80-ffffffff838ecf09: handle_vc_boot_ghcb (STB_GLOBAL)
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
