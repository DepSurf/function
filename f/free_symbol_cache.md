# Function: <code>free_symbol_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811697d0)
Location: kernel/trace/trace_kprobe.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:free_deref_fetch_param
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
```
**Symbols:**

```
ffffffff811697d0-ffffffff811697eb: free_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81176e50)
Location: kernel/trace/trace_kprobe.c:103
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:free_deref_fetch_param
```
**Symbols:**

```
ffffffff81176e50-ffffffff81176e6b: free_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81182900)
Location: kernel/trace/trace_kprobe.c:114
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:free_deref_fetch_param
```
**Symbols:**

```
ffffffff81182900-ffffffff8118291b: free_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811857b0)
Location: kernel/trace/trace_kprobe.c:117
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:free_deref_fetch_param
```
**Symbols:**

```
ffffffff811857b0-ffffffff811857cb: free_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811934a0)
Location: kernel/trace/trace_kprobe.c:117
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:free_deref_fetch_param
```
**Symbols:**

```
ffffffff811934a0-ffffffff811934bb: free_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a8940)
Location: kernel/trace/trace_kprobe.c:141
Inline: False
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:traceprobe_free_probe_arg
  - kernel/trace/trace_probe.c:free_deref_fetch_param
```
**Symbols:**

```
ffffffff811a8940-ffffffff811a895b: free_symbol_cache (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
