# Function: <code>__do_sys_ni_syscall</code>

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
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004b60)
Location: arch/x86/entry/common.c:564
Inline: False
```
**Symbols:**

```
ffffffff81004b60-ffffffff81004b68: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810045d0)
Location: arch/x86/entry/common.c:212
Inline: False
```
**Symbols:**

```
ffffffff810045d0-ffffffff810045d8: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810045c0)
Location: arch/x86/entry/common.c:215
Inline: False
```
**Symbols:**

```
ffffffff810045c0-ffffffff810045c8: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004bf0)
Location: arch/x86/entry/common.c:250
Inline: True
```
**Symbols:**

```
ffffffff81004bf0-ffffffff81004bf8: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003c70)
Location: arch/x86/entry/common.c:250
Inline: True
```
**Symbols:**

```
ffffffff81003c70-ffffffff81003c7c: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81004560)
Location: arch/x86/entry/common.c:250
Inline: True
```
**Symbols:**

```
ffffffff81004560-ffffffff8100456c: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d20)
Location: arch/x86/entry/common.c:250
Inline: True
```
**Symbols:**

```
ffffffff81003d20-ffffffff81003d2c: __do_sys_ni_syscall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_ni_syscall(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81006600)
Location: arch/x86/entry/common.c:388
Inline: True
```
**Symbols:**

```
ffffffff81006600-ffffffff8100660c: __do_sys_ni_syscall (STB_LOCAL)
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
