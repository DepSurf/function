# Function: <code>arch_prepare_bpf_dispatcher</code>

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
int arch_prepare_bpf_dispatcher(void *image, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a2d60)
Location: arch/x86/net/bpf_jit_comp.c:1795
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff810a2d60-ffffffff810a2dd1: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109e750)
Location: arch/x86/net/bpf_jit_comp.c:1987
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff8109e750-ffffffff8109e7c1: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109f5b0)
Location: arch/x86/net/bpf_jit_comp.c:2198
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff8109f5b0-ffffffff8109f621: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0910)
Location: arch/x86/net/bpf_jit_comp.c:2264
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff810b0910-ffffffff810b0981: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c67e0)
Location: arch/x86/net/bpf_jit_comp.c:2299
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff810c67e0-ffffffff810c6860: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, void *buf, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3750)
Location: arch/x86/net/bpf_jit_comp.c:2419
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff810e3750-ffffffff810e37e7: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, void *buf, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810eede0)
Location: arch/x86/net/bpf_jit_comp.c:2422
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff810eede0-ffffffff810eee77: arch_prepare_bpf_dispatcher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_prepare_bpf_dispatcher(void *image, void *buf, s64 *funcs, int num_funcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f80a0)
Location: arch/x86/net/bpf_jit_comp.c:2924
Inline: False
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_prepare
```
**Symbols:**

```
ffffffff810f80a0-ffffffff810f8137: arch_prepare_bpf_dispatcher (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *buf</code>
</li>
<li>
<b>Param reordered. </b>
<code>image, funcs, num_funcs</code> ➡️ <code>image, buf, funcs, num_funcs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
