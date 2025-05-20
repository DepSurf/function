# Function: <code>handle_stack_overflow</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102eb00)
Location: arch/x86/kernel/traps.c:296
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff8102eb00-ffffffff8102eb4a: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102ce10)
Location: arch/x86/kernel/traps.c:331
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff8102ce10-ffffffff8102ce5a: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102dbd0)
Location: arch/x86/kernel/traps.c:323
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff8102dbd0-ffffffff8102dc1a: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8102ef60)
Location: arch/x86/kernel/traps.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff8102ef60-ffffffff8102efaa: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810301e8)
Location: arch/x86/kernel/traps.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff810301e8-ffffffff81030239: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81031fa9)
Location: arch/x86/kernel/traps.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff81031fa9-ffffffff81031ffb: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032869)
Location: arch/x86/kernel/traps.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff81032869-ffffffff810328bb: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103477f)
Location: arch/x86/kernel/traps.c:311
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff8103477f-ffffffff810347d1: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bd332b)
Location: arch/x86/kernel/traps.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff81bd332b-ffffffff81bd337d: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81bc5743)
Location: arch/x86/kernel/traps.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff81bc5743-ffffffff81bc5795: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void handle_stack_overflow(struct pt_regs *regs, long unsigned int fault_address, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8103bcd0)
Location: arch/x86/kernel/traps.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff8103bcd0-ffffffff8103bd2d: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handle_stack_overflow(struct pt_regs *regs, long unsigned int fault_address, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81042d20)
Location: arch/x86/kernel/traps.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff81042d20-ffffffff81042d7d: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_stack_overflow(struct pt_regs *regs, long unsigned int fault_address, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104c790)
Location: arch/x86/kernel/traps.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff8104c790-ffffffff8104c7ed: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_stack_overflow(struct pt_regs *regs, long unsigned int fault_address, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff8104d000)
Location: arch/x86/kernel/traps.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff8104d000-ffffffff8104d05d: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_stack_overflow(struct pt_regs *regs, long unsigned int fault_address, struct stack_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81054280)
Location: arch/x86/kernel/traps.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:exc_double_fault
```
**Symbols:**

```
ffffffff81054280-ffffffff810542dd: handle_stack_overflow (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff810329c9)
Location: arch/x86/kernel/traps.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff810329c9-ffffffff81032a1b: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81022322)
Location: arch/x86/kernel/traps.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff81022322-ffffffff81022374: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81032829)
Location: arch/x86/kernel/traps.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff81032829-ffffffff8103287b: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void handle_stack_overflow(const char *message, struct pt_regs *regs, long unsigned int fault_address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/traps.c (ffffffff81033789)
Location: arch/x86/kernel/traps.c:300
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_double_fault
```
**Symbols:**

```
ffffffff81033789-ffffffff810337db: handle_stack_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct stack_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *message</code>
</li>
<li>
<b>Param reordered. </b>
<code>message, regs, fault_address</code> ➡️ <code>regs, fault_address, info</code>
</li>
</ul>
</details>
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
