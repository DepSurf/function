# Function: <code>update_symbol_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int update_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811697a0)
Location: kernel/trace/trace_kprobe.c:93
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
Direct callers:
  - kernel/trace/trace_probe.c:update_deref_fetch_param
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
```
**Symbols:**

```
ffffffff811697a0-ffffffff811697c4: update_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int update_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81176ec0)
Location: kernel/trace/trace_kprobe.c:93
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:update_deref_fetch_param
```
**Symbols:**

```
ffffffff81176e20-ffffffff81176e44: update_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long unsigned int update_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81182970)
Location: kernel/trace/trace_kprobe.c:104
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:update_deref_fetch_param
```
**Symbols:**

```
ffffffff811828d0-ffffffff811828f4: update_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int update_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81185820)
Location: kernel/trace/trace_kprobe.c:107
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:update_deref_fetch_param
```
**Symbols:**

```
ffffffff81185780-ffffffff811857a4: update_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int update_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81193510)
Location: kernel/trace/trace_kprobe.c:107
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:update_deref_fetch_param
```
**Symbols:**

```
ffffffff81193470-ffffffff81193494: update_symbol_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int update_symbol_cache(struct symbol_cache *sc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a89b0)
Location: kernel/trace/trace_kprobe.c:131
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_symbol_cache
Direct callers:
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:traceprobe_update_arg
  - kernel/trace/trace_probe.c:update_deref_fetch_param
```
**Symbols:**

```
ffffffff811a8910-ffffffff811a8934: update_symbol_cache (STB_GLOBAL)
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
