# Function: <code>rethook_recycle</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rethook_recycle(struct rethook_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff81268ff1)
Location: kernel/trace/rethook.c:128
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff81268f30-ffffffff81268faf: rethook_recycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rethook_recycle(struct rethook_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812bb311)
Location: kernel/trace/rethook.c:130
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff812bb240-ffffffff812bb2bf: rethook_recycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rethook_recycle(struct rethook_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812def15)
Location: kernel/trace/rethook.c:143
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/trace/rethook.c:rethook_trampoline_handler
```
**Symbols:**

```
ffffffff812dee40-ffffffff812deebf: rethook_recycle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rethook_recycle(struct rethook_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812fd17a)
Location: kernel/trace/rethook.c:142
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_trampoline_handler
  - kernel/trace/rethook.c:rethook_flush_task
  - kernel/trace/rethook.c:rethook_flush_task
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
**Symbols:**

```
ffffffff812fcd50-ffffffff812fcd8e: rethook_recycle (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
