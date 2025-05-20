# Function: <code>bpf_prog_get_curr_or_next</code>

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
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812016a0)
Location: kernel/bpf/syscall.c:3180
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff812016a0-ffffffff812016fe: bpf_prog_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81202560)
Location: kernel/bpf/syscall.c:3203
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff81202560-ffffffff812025be: bpf_prog_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81234580)
Location: kernel/bpf/syscall.c:3386
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff81234580-ffffffff812345de: bpf_prog_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81277b90)
Location: kernel/bpf/syscall.c:3644
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff81277b90-ffffffff81277bf8: bpf_prog_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cdf80)
Location: kernel/bpf/syscall.c:3687
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff812cdf80-ffffffff812cdfe8: bpf_prog_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f5510)
Location: kernel/bpf/syscall.c:3823
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff812f5510-ffffffff812f5578: bpf_prog_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_prog_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81314310)
Location: kernel/bpf/syscall.c:4160
Inline: False
Direct callers:
  - kernel/bpf/prog_iter.c:bpf_prog_seq_next
  - kernel/bpf/prog_iter.c:bpf_prog_seq_start
```
**Symbols:**

```
ffffffff81314310-ffffffff81314378: bpf_prog_get_curr_or_next (STB_GLOBAL)
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
