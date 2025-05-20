# Function: <code>__rb_free_aux</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81185268)
Location: kernel/events/ring_buffer.c:555
Inline: True
Inline callers:
  - kernel/events/ring_buffer.c:rb_irq_work
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811970a0)
Location: kernel/events/ring_buffer.c:536
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff811970a0-ffffffff811971c4: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811a6aa0)
Location: kernel/events/ring_buffer.c:536
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff811a6aa0-ffffffff811a6bb6: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811ae270)
Location: kernel/events/ring_buffer.c:548
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff811ae270-ffffffff811ae359: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811c1ee0)
Location: kernel/events/ring_buffer.c:559
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff811c1ee0-ffffffff811c1fce: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811e22a0)
Location: kernel/events/ring_buffer.c:560
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff811e22a0-ffffffff811e238f: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff811f2710)
Location: kernel/events/ring_buffer.c:570
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff811f2710-ffffffff811f27ff: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120a3e0)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8120a3e0-ffffffff8120a4cb: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812176c0)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff812176c0-ffffffff812177ab: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81242f20)
Location: kernel/events/ring_buffer.c:638
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff81242f20-ffffffff8124300b: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8124d5c0)
Location: kernel/events/ring_buffer.c:640
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8124d5c0-ffffffff8124d6ab: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81251f00)
Location: kernel/events/ring_buffer.c:640
Inline: False
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff81251f00-ffffffff81251fe8: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8128d7a0)
Location: kernel/events/ring_buffer.c:640
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8128d7a0-ffffffff8128d888: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff812e2550)
Location: kernel/events/ring_buffer.c:640
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff812e2550-ffffffff812e2644: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8134ab20)
Location: kernel/events/ring_buffer.c:643
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8134ab20-ffffffff8134ac14: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8137bb60)
Location: kernel/events/ring_buffer.c:643
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8137bb60-ffffffff8137bc4f: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct perf_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff813a4da0)
Location: kernel/events/ring_buffer.c:644
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff813a4da0-ffffffff813a4e8f: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffff8000102a1f48)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffff8000102a1f48-ffff8000102a2020: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c04d1ae0)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
c04d1ae0-c04d1bdc: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (c000000000353e40)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
c000000000353e40-c000000000353f78: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffe0001d0bfc)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_alloc_aux
  - kernel/events/ring_buffer.c:perf_aux_output_end
  - kernel/events/ring_buffer.c:perf_aux_output_begin
```
**Symbols:**

```
ffffffe0001d0bfc-ffffffe0001d0cae: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120fd10)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8120fd10-ffffffff8120fdfb: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff81202aa0)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff81202aa0-ffffffff81202b8b: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8120dab0)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8120dab0-ffffffff8120db9b: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __rb_free_aux(struct ring_buffer *rb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/ring_buffer.c (ffffffff8121c960)
Location: kernel/events/ring_buffer.c:602
Inline: True
Direct callers:
  - kernel/events/ring_buffer.c:rb_free_aux
  - kernel/events/ring_buffer.c:rb_alloc_aux
```
**Symbols:**

```
ffffffff8121c960-ffffffff8121ca4b: __rb_free_aux (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ring_buffer *rb</code> ➡️ <code>struct perf_buffer *rb</code>
</li>
</ul>
</details>
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
