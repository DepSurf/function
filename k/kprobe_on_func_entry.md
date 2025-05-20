# Function: <code>kprobe_on_func_entry</code>

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
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81142ab0)
Location: kernel/kprobes.c:1902
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/kprobes.c:register_jprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81142ab0-ffffffff81142b28: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114f870)
Location: kernel/kprobes.c:1906
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff8114f870-ffffffff8114f8e8: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115e3b0)
Location: kernel/kprobes.c:1950
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff8115e3b0-ffffffff8115e428: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116af30)
Location: kernel/kprobes.c:1867
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff8116af30-ffffffff8116afa8: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81177d20)
Location: kernel/kprobes.c:1871
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff81177d20-ffffffff81177d98: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81183c30)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff81183c30-ffffffff81183ca8: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811979f0)
Location: kernel/kprobes.c:1958
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff811979f0-ffffffff81197a66: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194e30)
Location: kernel/kprobes.c:1970
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff81194e30-ffffffff81194ebb: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81195e30)
Location: kernel/kprobes.c:1975
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff81195e30-ffffffff81195eb5: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811beda0)
Location: kernel/kprobes.c:1967
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff811beda0-ffffffff811bee25: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811f20de)
Location: kernel/kprobes.c:2158
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff81e64781-ffffffff81e64795: kprobe_on_func_entry.cold (STB_LOCAL)
ffffffff811f21f0-ffffffff811f22c4: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81238dbe)
Location: kernel/kprobes.c:2166
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff8205c825-ffffffff8205c839: kprobe_on_func_entry.cold (STB_LOCAL)
ffffffff81238ef0-ffffffff81238fc4: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8124ff18)
Location: kernel/kprobes.c:2179
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff820db17a-ffffffff820db18e: kprobe_on_func_entry.cold (STB_LOCAL)
ffffffff81250030-ffffffff81250104: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81269bd1)
Location: kernel/kprobes.c:2180
Inline: True
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff821b6eb5-ffffffff821b6ec9: kprobe_on_func_entry.cold (STB_LOCAL)
ffffffff81269e40-ffffffff81269f14: kprobe_on_func_entry (STB_GLOBAL)
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
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f9250)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffff8000101f9250-ffff8000101f92f8: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c0439520)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
c0439520-c04395b4: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c0000000002708e0)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
c0000000002708e0-c00000000027095c: kprobe_on_func_entry (STB_GLOBAL)
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
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117c250)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff8117c250-ffffffff8117c2c8: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116f3f0)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff8116f3f0-ffffffff8116f468: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117a020)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff8117a020-ffffffff8117a098: kprobe_on_func_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kprobe_on_func_entry(kprobe_opcode_t *addr, const char *sym, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81187950)
Location: kernel/kprobes.c:1914
Inline: False
Direct callers:
  - kernel/kprobes.c:register_kretprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
  - kernel/trace/trace_kprobe.c:trace_kprobe_on_func_entry
```
**Symbols:**

```
ffffffff81187950-ffffffff811879c8: kprobe_on_func_entry (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
