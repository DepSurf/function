# Function: <code>__die_body</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:398
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff81037660-ffffffff810376ee: __die_body (STB_LOCAL)
ffffffff81037cb9-ffffffff81037cc6: __die_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff810386d0-ffffffff81038765: __die_body (STB_LOCAL)
ffffffff81bd387e-ffffffff81bd388b: __die_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff8103a1f0-ffffffff8103a285: __die_body (STB_LOCAL)
ffffffff81bc5cf0-ffffffff81bc5cfd: __die_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:415
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff8103fba0-ffffffff8103fc35: __die_body (STB_LOCAL)
ffffffff81c98a3a-ffffffff81c98a47: __die_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/dumpstack.c (0)
Location: arch/x86/kernel/dumpstack.c:409
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:__die
```
**Symbols:**

```
ffffffff81047330-ffffffff810473d1: __die_body (STB_LOCAL)
ffffffff81e47fcf-ffffffff81e47fdc: __die_body.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051e8f)
Location: arch/x86/kernel/dumpstack.c:415
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff81051c90-ffffffff81051d01: __die_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052bcf)
Location: arch/x86/kernel/dumpstack.c:418
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff810529d0-ffffffff81052a41: __die_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __die_body(const char *str, struct pt_regs *regs, long int err);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059def)
Location: arch/x86/kernel/dumpstack.c:418
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:die_addr
  - arch/x86/kernel/dumpstack.c:die
```
**Symbols:**

```
ffffffff81059bf0-ffffffff81059c61: __die_body (STB_LOCAL)
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
