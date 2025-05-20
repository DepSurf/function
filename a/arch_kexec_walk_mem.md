# Function: <code>arch_kexec_walk_mem</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int arch_kexec_walk_mem(struct kexec_buf *kbuf, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111d6b0)
Location: kernel/kexec_file.c:444
Inline: True
```
**Symbols:**

```
ffffffff8111d6b0-ffffffff8111d702: arch_kexec_walk_mem (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int arch_kexec_walk_mem(struct kexec_buf *kbuf, int (*func)(u64, u64, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111f2b0)
Location: kernel/kexec_file.c:445
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8111f2b0-ffffffff8111f302: arch_kexec_walk_mem (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int arch_kexec_walk_mem(struct kexec_buf *kbuf, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8112aa50)
Location: kernel/kexec_file.c:447
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8112aa50-ffffffff8112aaa2: arch_kexec_walk_mem (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int arch_kexec_walk_mem(struct kexec_buf *kbuf, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81139020)
Location: kernel/kexec_file.c:513
Inline: True
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81139020-ffffffff81139072: arch_kexec_walk_mem (STB_WEAK)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*func)(u64, u64, void *)</code> ➡️ <code>int (*func)(struct resource *, void *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
