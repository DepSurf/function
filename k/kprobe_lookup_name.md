# Function: <code>kprobe_lookup_name</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81141cb0)
Location: kernel/kprobes.c:75
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
**Symbols:**

```
ffffffff81141cb0-ffffffff81141cc0: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114ea60)
Location: kernel/kprobes.c:75
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
**Symbols:**

```
ffffffff8114ea60-ffffffff8114ea70: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115d4e0)
Location: kernel/kprobes.c:75
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
**Symbols:**

```
ffffffff8115d4e0-ffffffff8115d4f0: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a110)
Location: kernel/kprobes.c:75
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
**Symbols:**

```
ffffffff8116a110-ffffffff8116a120: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81176e70)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
```
**Symbols:**

```
ffffffff81176e70-ffffffff81176e80: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81182da0)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81182da0-ffffffff81182db0: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81196c80)
Location: kernel/kprobes.c:67
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81196c80-ffffffff81196c90: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193d30)
Location: kernel/kprobes.c:64
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81193d30-ffffffff81193d40: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194d20)
Location: kernel/kprobes.c:65
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81194d20-ffffffff81194d30: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bdbe0)
Location: kernel/kprobes.c:65
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff811bdbe0-ffffffff811bdbf0: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f0ef0)
Location: kernel/kprobes.c:70
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff811f0ef0-ffffffff811f0f06: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812379a0)
Location: kernel/kprobes.c:70
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff812379a0-ffffffff812379b6: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124ea60)
Location: kernel/kprobes.c:70
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff8124ea60-ffffffff8124ea76: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81268990)
Location: kernel/kprobes.c:70
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:within_kprobe_blacklist
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81268990-ffffffff812689a6: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f86f0)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_on_func_entry
```
**Symbols:**

```
ffff8000101f86f0-ffff8000101f871c: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c04384cc)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_on_func_entry
```
**Symbols:**

```
c04384cc-c04384e8: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/kprobes.c (c000000000057450)
Location: arch/powerpc/kernel/kprobes.c:41
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
c000000000057450-c00000000005752c: kprobe_lookup_name (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b3c0)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff8117b3c0-ffffffff8117b3d0: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116e560)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff8116e560-ffffffff8116e570: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81179190)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81179190-ffffffff811791a0: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
kprobe_opcode_t *kprobe_lookup_name(const char *name, unsigned int __unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81186a60)
Location: kernel/kprobes.c:62
Inline: False
Direct callers:
  - kernel/kprobes.c:init_kprobes
  - kernel/kprobes.c:kprobe_on_func_entry
  - kernel/kprobes.c:kprobe_addr
  - kernel/trace/trace_kprobe.c:within_notrace_func
```
**Symbols:**

```
ffffffff81186a60-ffffffff81186a70: kprobe_lookup_name (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int __unused</code>
</li>
</ul>
</details>
</li>
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
