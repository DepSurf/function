# Function: <code>bpf_jit_alloc_exec_page</code>

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
void *bpf_jit_alloc_exec_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8121ef25)
Location: kernel/bpf/trampoline.c:26
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8121ed90-ffffffff8121edd8: bpf_jit_alloc_exec_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *bpf_jit_alloc_exec_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8122273b)
Location: kernel/bpf/trampoline.c:28
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81222840-ffffffff81222888: bpf_jit_alloc_exec_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *bpf_jit_alloc_exec_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81227633)
Location: kernel/bpf/trampoline.c:29
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81226eb0-ffffffff81226ef8: bpf_jit_alloc_exec_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *bpf_jit_alloc_exec_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125f7bb)
Location: kernel/bpf/trampoline.c:29
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8125efb0-ffffffff8125eff8: bpf_jit_alloc_exec_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *bpf_jit_alloc_exec_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9ed3)
Location: kernel/bpf/trampoline.c:41
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
Direct callers:
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff812a95e0-ffffffff812a962f: bpf_jit_alloc_exec_page (STB_GLOBAL)
```
</details>
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
</ul>
