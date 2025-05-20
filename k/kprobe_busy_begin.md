# Function: <code>kprobe_busy_begin</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194df4)
Location: kernel/kprobes.c:1259
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81197330-ffffffff8119735d: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81192e33)
Location: kernel/kprobes.c:1242
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81194440-ffffffff8119446d: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193cd3)
Location: kernel/kprobes.c:1243
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81195470-ffffffff8119549d: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bcb93)
Location: kernel/kprobes.c:1236
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff811be3d0-ffffffff811be3fd: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f1730)
Location: kernel/kprobes.c:1244
Inline: False
```
**Symbols:**

```
ffffffff811f1730-ffffffff811f176a: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81238340)
Location: kernel/kprobes.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81238340-ffffffff8123837a: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124f420)
Location: kernel/kprobes.c:1241
Inline: False
```
**Symbols:**

```
ffffffff8124f420-ffffffff8124f45a: kprobe_busy_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kprobe_busy_begin();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81269350)
Location: kernel/kprobes.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81269350-ffffffff8126938a: kprobe_busy_begin (STB_GLOBAL)
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
