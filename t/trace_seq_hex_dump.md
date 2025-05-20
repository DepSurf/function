# Function: <code>trace_seq_hex_dump</code>

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
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c7a10)
Location: kernel/trace/trace_seq.c:377
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff811c7a10-ffffffff811c7ae5: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c5110)
Location: kernel/trace/trace_seq.c:377
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff811c5110-ffffffff811c51e5: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811c6300)
Location: kernel/trace/trace_seq.c:377
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff811c6300-ffffffff811c63d5: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff811f18f0)
Location: kernel/trace/trace_seq.c:377
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff811f18f0-ffffffff811f19c5: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8122a280)
Location: kernel/trace/trace_seq.c:377
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff8122a280-ffffffff8122a376: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff81275a80)
Location: kernel/trace/trace_seq.c:377
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff81275a80-ffffffff81275b76: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff8128d440)
Location: kernel/trace/trace_seq.c:378
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff8128d440-ffffffff8128d536: trace_seq_hex_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_seq_hex_dump(struct trace_seq *s, const char *prefix_str, int prefix_type, int rowsize, int groupsize, const void *buf, size_t len, bool ascii);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_seq.c (ffffffff812a8830)
Location: kernel/trace/trace_seq.c:379
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_print_hex_dump_seq
```
**Symbols:**

```
ffffffff812a8830-ffffffff812a8929: trace_seq_hex_dump (STB_GLOBAL)
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
