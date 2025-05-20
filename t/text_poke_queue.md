# Function: <code>text_poke_queue</code>

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
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81bc0390)
Location: arch/x86/kernel/alternative.c:1306
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff81bc0390-ffffffff81bc03fe: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81c39350)
Location: arch/x86/kernel/alternative.c:1357
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff81c39350-ffffffff81c393be: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81c2b7a0)
Location: arch/x86/kernel/alternative.c:1278
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff81c2b7a0-ffffffff81c2b80e: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81d49e70)
Location: arch/x86/kernel/alternative.c:1278
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff81d49e70-ffffffff81d49efe: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81f193e0)
Location: arch/x86/kernel/alternative.c:1670
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff81f193e0-ffffffff81f19490: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff820c0ee0)
Location: arch/x86/kernel/alternative.c:2173
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff820c0ee0-ffffffff820c0f65: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff82144ba0)
Location: arch/x86/kernel/alternative.c:2408
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff82144ba0-ffffffff82144c25: text_poke_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void text_poke_queue(void *addr, const void *opcode, size_t len, const void *emulate);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff822272c0)
Location: arch/x86/kernel/alternative.c:2498
Inline: False
Direct callers:
  - arch/x86/kernel/jump_label.c:arch_jump_label_transform_queue
  - arch/x86/kernel/ftrace.c:ftrace_replace_code
  - arch/x86/kernel/ftrace.c:ftrace_modify_code_direct
```
**Symbols:**

```
ffffffff822272c0-ffffffff82227345: text_poke_queue (STB_GLOBAL)
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
