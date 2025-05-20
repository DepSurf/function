# Function: <code>_kprobe_addr</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81142abe)
Location: kernel/kprobes.c:1401
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114f87e)
Location: kernel/kprobes.c:1403
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115e3b5)
Location: kernel/kprobes.c:1432
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116af35)
Location: kernel/kprobes.c:1423
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81177d25)
Location: kernel/kprobes.c:1427
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81183c35)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81197b64)
Location: kernel/kprobes.c:1512
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194e39)
Location: kernel/kprobes.c:1476
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81195e40)
Location: kernel/kprobes.c:1477
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bedb0)
Location: kernel/kprobes.c:1469
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
kprobe_opcode_t *_kprobe_addr(kprobe_opcode_t *addr, const char *symbol_name, long unsigned int offset, bool *on_func_entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f1a40)
Location: kernel/kprobes.c:1449
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kprobe
```
**Symbols:**

```
ffffffff811f1a40-ffffffff811f1ae9: _kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
kprobe_opcode_t *_kprobe_addr(kprobe_opcode_t *addr, const char *symbol_name, long unsigned int offset, bool *on_func_entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812386c0)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kprobe
```
**Symbols:**

```
ffffffff812386c0-ffffffff81238769: _kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
kprobe_opcode_t *_kprobe_addr(kprobe_opcode_t *addr, const char *symbol_name, long unsigned int offset, bool *on_func_entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124f820)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kprobe
```
**Symbols:**

```
ffffffff8124f820-ffffffff8124f8c9: _kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
kprobe_opcode_t *_kprobe_addr(kprobe_opcode_t *addr, const char *symbol_name, long unsigned int offset, bool *on_func_entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81269750)
Location: kernel/kprobes.c:1446
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kprobe
```
**Symbols:**

```
ffffffff81269750-ffffffff812697f9: _kprobe_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f9270)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c0439538)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
kprobe_opcode_t *_kprobe_addr(kprobe_opcode_t *addr, const char *symbol_name, unsigned int offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c00000000026f250)
Location: kernel/kprobes.c:1472
Inline: True
Direct callers:
  - kernel/kprobes.c:kprobe_on_func_entry
```
**Symbols:**

```
c00000000026f250-c00000000026f2f0: _kprobe_addr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117c255)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116f3f5)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117a025)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81187955)
Location: kernel/kprobes.c:1472
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/kprobes.c:kprobe_addr
```
</details>
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
<b>Arch</b>
<ul>
</ul>
