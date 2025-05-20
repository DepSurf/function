# Function: <code>static_call_text_reserved</code>

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
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239ec0)
Location: kernel/static_call.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81239ec0-ffffffff81239f09: static_call_text_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff8123e5b0)
Location: kernel/static_call.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff8123e5b0-ffffffff8123e6d4: static_call_text_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81279090)
Location: kernel/static_call.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
```
**Symbols:**

```
ffffffff81279090-ffffffff812791b4: static_call_text_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff812cbf20)
Location: kernel/static_call_inline.c:462
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff812cbf20-ffffffff812cc07a: static_call_text_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81333910)
Location: kernel/static_call_inline.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff81333910-ffffffff81333a6a: static_call_text_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81364660)
Location: kernel/static_call_inline.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff81364660-ffffffff813647d1: static_call_text_reserved (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int static_call_text_reserved(void *start, void *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8138d590)
Location: kernel/static_call_inline.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions
  - kernel/kprobes.c:check_kprobe_address_safe
```
**Symbols:**

```
ffffffff8138d590-ffffffff8138d701: static_call_text_reserved (STB_GLOBAL)
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
