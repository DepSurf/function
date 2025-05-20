# Function: <code>ex_handler_msr_mce</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ex_handler_msr_mce(struct pt_regs *regs, bool wrmsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81e4ad08)
Location: arch/x86/kernel/cpu/mce/core.c:322
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff81e4ad08-ffffffff81e4ad62: ex_handler_msr_mce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ex_handler_msr_mce(struct pt_regs *regs, bool wrmsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078a40)
Location: arch/x86/kernel/cpu/mce/core.c:322
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff81078a40-ffffffff81078a9a: ex_handler_msr_mce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ex_handler_msr_mce(struct pt_regs *regs, bool wrmsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107acf0)
Location: arch/x86/kernel/cpu/mce/core.c:316
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff8107acf0-ffffffff8107ad4a: ex_handler_msr_mce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ex_handler_msr_mce(struct pt_regs *regs, bool wrmsr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81082190)
Location: arch/x86/kernel/cpu/mce/core.c:347
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff81082190-ffffffff810821ea: ex_handler_msr_mce (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
