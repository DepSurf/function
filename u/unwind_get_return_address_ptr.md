# Function: <code>unwind_get_return_address_ptr</code>

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
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030b2f)
Location: arch/x86/include/asm/unwind.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81069a0a)
Location: arch/x86/include/asm/unwind.h:46
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:unwind_get_return_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102ee3b)
Location: arch/x86/include/asm/unwind.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
```
In arch/x86/kernel/unwind_frame.c (ffffffff81068ec4)
Location: arch/x86/include/asm/unwind.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d744)
Location: arch/x86/kernel/unwind_frame.c:22
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8106dad0-ffffffff8106dafc: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107052f)
Location: arch/x86/kernel/unwind_frame.c:22
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff810708c0-ffffffff810708ec: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107650a)
Location: arch/x86/kernel/unwind_frame.c:22
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff810768d0-ffffffff810768fc: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a0c8)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8107a470-ffffffff8107a49c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b1b8)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8107b560-ffffffff8107b58c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810825c8)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff81082980-ffffffff810829ac: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082078)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff81082430-ffffffff8108245c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082e98)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff81083250-ffffffff8108327c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81091ed8)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff81092350-ffffffff8109237c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810a3143)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff810a35e0-ffffffff810a361e: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb593)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff810bba10-ffffffff810bba4e: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810be6d3)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff810beb50-ffffffff810beb8e: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810c5853)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff810c5cd0-ffffffff810c5d0e: unwind_get_return_address_ptr (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a1b8)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8107a560-ffffffff8107a58c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810698e8)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff81069c90-ffffffff81069cbc: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a168)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8107a510-ffffffff8107a53c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int *unwind_get_return_address_ptr(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c268)
Location: arch/x86/kernel/unwind_frame.c:23
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:update_stack_state
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
```
**Symbols:**

```
ffffffff8107c610-ffffffff8107c63c: unwind_get_return_address_ptr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
