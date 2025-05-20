# Function: <code>__traceiter_write_msr</code>

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
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8160bf90)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff8160bf90-ffffffff8160bfe1: __traceiter_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff815ef270)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff815ef270-ffffffff815ef2bf: __traceiter_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff8165c380)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff8165c380-ffffffff8165c3cf: __traceiter_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff817753f0)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff817753f0-ffffffff8177544b: __traceiter_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818a5ff0)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff818a5ff0-ffffffff818a604b: __traceiter_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff818e8e20)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff818e8e20-ffffffff818e8e7b: __traceiter_write_msr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_write_msr(void *__data, unsigned int msr, u64 val, int failed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/msr.c (ffffffff819302c0)
Location: arch/x86/include/asm/msr-trace.h:45
Inline: False
```
**Symbols:**

```
ffffffff819302c0-ffffffff8193031b: __traceiter_write_msr (STB_GLOBAL)
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
