# Function: <code>bpf_ringbuf_commit</code>

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
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8121e5e5)
Location: kernel/bpf/ringbuf.c:392
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff8121e1d0-ffffffff8121e242: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81221345)
Location: kernel/bpf/ringbuf.c:370
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff81220f70-ffffffff81220fe2: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81224dc9)
Location: kernel/bpf/ringbuf.c:370
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff81224a20-ffffffff81224a97: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8125cd09)
Location: kernel/bpf/ringbuf.c:370
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff8125c960-ffffffff8125c9d7: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812a6d10)
Location: kernel/bpf/ringbuf.c:370
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff812a6700-ffffffff812a679f: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff813052a0)
Location: kernel/bpf/ringbuf.c:456
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff81304940-ffffffff813049df: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81333cd0)
Location: kernel/bpf/ringbuf.c:474
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff813332f0-ffffffff81333383: bpf_ringbuf_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_ringbuf_commit(void *sample, u64 flags, bool discard);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff813583c0)
Location: kernel/bpf/ringbuf.c:470
Inline: True
Inline callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_discard
  - kernel/bpf/ringbuf.c:bpf_ringbuf_submit
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
```
**Symbols:**

```
ffffffff813579e0-ffffffff81357a73: bpf_ringbuf_commit (STB_LOCAL)
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
