# Function: <code>__bpf_trace_credit_entropy_bits</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, int entropy_total, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81645c10)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff81645c10-ffffffff81645c22: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, int entropy_total, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81663f10)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff81663f10-ffffffff81663f22: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816998b0)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff816998b0-ffffffff816998bf: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bc4c0)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff816bc4c0-ffffffff816bc4cf: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770850)
Location: include/trace/events/random.h:63
Inline: True
```
**Symbols:**

```
ffffffff81770850-ffffffff8177085f: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178b8b0)
Location: include/trace/events/random.h:63
Inline: True
```
**Symbols:**

```
ffffffff8178b8b0-ffffffff8178b8bf: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8176eb00)
Location: include/trace/events/random.h:63
Inline: True
```
**Symbols:**

```
ffffffff8176eb00-ffffffff8176eb0f: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f42d0)
Location: include/trace/events/random.h:63
Inline: True
```
**Symbols:**

```
ffffffff817f42d0-ffffffff817f42df: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108ac3b8)
Location: include/trace/events/random.h:63
Inline: True
```
**Symbols:**

```
ffff8000108ac3b8-ffff8000108ac3d4: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a9320)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
c09a9320-c09a9364: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000945630)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
c000000000945630-c000000000945664: __bpf_trace_credit_entropy_bits (STB_LOCAL)
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
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81681f20)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff81681f20-ffffffff81681f2f: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8165fda0)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff8165fda0-ffffffff8165fdaf: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b0300)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff816b0300-ffffffff816b030f: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_credit_entropy_bits(void *__data, const char *pool_name, int bits, int entropy_count, long unsigned int IP);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816ca960)
Location: include/trace/events/random.h:63
Inline: False
```
**Symbols:**

```
ffffffff816ca960-ffffffff816ca96f: __bpf_trace_credit_entropy_bits (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int entropy_total</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, pool_name, bits, entropy_count, entropy_total, IP</code> ➡️ <code>__data, pool_name, bits, entropy_count, IP</code>
</li>
</ul>
</details>
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
