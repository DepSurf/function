# Function: <code>kprobe_busy_end</code>

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
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194edd)
Location: kernel/kprobes.c:1269
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81197360-ffffffff81197377: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81192ed4)
Location: kernel/kprobes.c:1252
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff81194470-ffffffff81194487: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193d74)
Location: kernel/kprobes.c:1253
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff811954a0-ffffffff811954b7: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bcc34)
Location: kernel/kprobes.c:1246
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_flush_task
Direct callers:
  - arch/x86/kernel/kprobes/core.c:trampoline_handler
```
**Symbols:**

```
ffffffff811be400-ffffffff811be417: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f1770)
Location: kernel/kprobes.c:1254
Inline: False
```
**Symbols:**

```
ffffffff811f1770-ffffffff811f179e: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81238390)
Location: kernel/kprobes.c:1251
Inline: False
```
**Symbols:**

```
ffffffff81238390-ffffffff812383be: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124f470)
Location: kernel/kprobes.c:1251
Inline: False
```
**Symbols:**

```
ffffffff8124f470-ffffffff8124f49e: kprobe_busy_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kprobe_busy_end();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812693a0)
Location: kernel/kprobes.c:1251
Inline: False
```
**Symbols:**

```
ffffffff812693a0-ffffffff812693ce: kprobe_busy_end (STB_GLOBAL)
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
