# Function: <code>is_copy_from_user</code>

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
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81052a90)
Location: arch/x86/kernel/cpu/mce/severity.c:218
Inline: False
```
**Symbols:**

```
ffffffff81052a90-ffffffff81052bbf: is_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff810543b0)
Location: arch/x86/kernel/cpu/mce/severity.c:218
Inline: False
```
**Symbols:**

```
ffffffff810543b0-ffffffff810544a1: is_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8105cd00)
Location: arch/x86/kernel/cpu/mce/severity.c:218
Inline: False
```
**Symbols:**

```
ffffffff8105cd00-ffffffff8105cdf1: is_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff810694d0)
Location: arch/x86/kernel/cpu/mce/severity.c:218
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff810694d0-ffffffff810695e7: is_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81079150)
Location: arch/x86/kernel/cpu/mce/severity.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff81079150-ffffffff81079267: is_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8107b400)
Location: arch/x86/kernel/cpu/mce/severity.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff8107b400-ffffffff8107b518: is_copy_from_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_copy_from_user(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff810828c0)
Location: arch/x86/kernel/cpu/mce/severity.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff810828c0-ffffffff810829d8: is_copy_from_user (STB_LOCAL)
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
