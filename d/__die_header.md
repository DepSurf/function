# Function: <code>__die_header</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103781d)
Location: arch/x86/kernel/dumpstack.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff8103781d-ffffffff8103789b: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd33f9)
Location: arch/x86/kernel/dumpstack.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff81bd33f9-ffffffff81bd3477: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc586c)
Location: arch/x86/kernel/dumpstack.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff81bc586c-ffffffff81bc58ea: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c985b6)
Location: arch/x86/kernel/dumpstack.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff81c985b6-ffffffff81c98634: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e47ac2)
Location: arch/x86/kernel/dumpstack.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff81e47ac2-ffffffff81e47b57: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051240)
Location: arch/x86/kernel/dumpstack.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff81051240-ffffffff810512d6: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051fa0)
Location: arch/x86/kernel/dumpstack.c:396
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff81051fa0-ffffffff81052036: __die_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __die_header(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810591c0)
Location: arch/x86/kernel/dumpstack.c:396
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff810591c0-ffffffff81059256: __die_header (STB_LOCAL)
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
