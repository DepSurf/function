# Function: <code>__bpf_ringbuf_reserve</code>

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
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8121e070)
Location: kernel/bpf/ringbuf.c:330
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff8121e070-ffffffff8121e183: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81220e10)
Location: kernel/bpf/ringbuf.c:308
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff81220e10-ffffffff81220f23: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812248a0)
Location: kernel/bpf/ringbuf.c:305
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff812248a0-ffffffff812249dc: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff8125c7e0)
Location: kernel/bpf/ringbuf.c:305
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff8125c7e0-ffffffff8125c91c: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff812a6550)
Location: kernel/bpf/ringbuf.c:305
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff812a6550-ffffffff812a6689: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff813047a0)
Location: kernel/bpf/ringbuf.c:391
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff813047a0-ffffffff813048e0: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81333140)
Location: kernel/bpf/ringbuf.c:409
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff81333140-ffffffff81333288: __bpf_ringbuf_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__bpf_ringbuf_reserve(struct bpf_ringbuf *rb, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/ringbuf.c (ffffffff81357830)
Location: kernel/bpf/ringbuf.c:405
Inline: False
Direct callers:
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve_dynptr
  - kernel/bpf/ringbuf.c:bpf_ringbuf_output
  - kernel/bpf/ringbuf.c:bpf_ringbuf_reserve
```
**Symbols:**

```
ffffffff81357830-ffffffff81357978: __bpf_ringbuf_reserve (STB_LOCAL)
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
