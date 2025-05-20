# Function: <code>ring_buffer_iter_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81146350)
Location: kernel/trace/ring_buffer.c:3440
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81146350-ffffffff8114637b: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81152194)
Location: kernel/trace/ring_buffer.c:3435
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff8114eba0-ffffffff8114ebce: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c544)
Location: kernel/trace/ring_buffer.c:3404
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81158ae0-ffffffff81158b0e: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115bd90)
Location: kernel/trace/ring_buffer.c:3406
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff8115bd90-ffffffff8115bdee: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81168e50)
Location: kernel/trace/ring_buffer.c:3398
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81168e50-ffffffff81168eae: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81177df0)
Location: kernel/trace/ring_buffer.c:3547
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81177df0-ffffffff81177e47: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185390)
Location: kernel/trace/ring_buffer.c:3610
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81185390-ffffffff811853e7: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81192530)
Location: kernel/trace/ring_buffer.c:3587
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81192530-ffffffff81192591: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119e1e0)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff8119e1e0-ffffffff8119e241: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4a90)
Location: kernel/trace/ring_buffer.c:3661
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff811b4a90-ffffffff811b4b16: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2340)
Location: kernel/trace/ring_buffer.c:4207
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff811b2340-ffffffff811b23c6: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2e40)
Location: kernel/trace/ring_buffer.c:4314
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff811b2e40-ffffffff811b2ec9: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dcd70)
Location: kernel/trace/ring_buffer.c:4314
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff811dcd70-ffffffff811dcdf9: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213250)
Location: kernel/trace/ring_buffer.c:4352
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff81213250-ffffffff81213303: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125cab0)
Location: kernel/trace/ring_buffer.c:4431
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff8125cab0-ffffffff8125cb63: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273a00)
Location: kernel/trace/ring_buffer.c:4435
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff81273a00-ffffffff81273ab3: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128df90)
Location: kernel/trace/ring_buffer.c:4339
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/trace.c:trace_empty
  - kernel/trace/trace.c:trace_empty
```
**Symbols:**

```
ffffffff8128df90-ffffffff8128e043: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010216ff0)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffff800010216ff0-ffff800010217060: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0455ecc)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
c0455ecc-c0455f58: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c000000000299470)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
c000000000299470-c000000000299504: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe0001769ba)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffe0001769ba-ffffffe000176a18: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81196800)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81196800-ffffffff81196861: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189910)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff81189910-ffffffff81189971: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811945d0)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff811945d0-ffffffff81194631: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ring_buffer_iter_empty(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a21b0)
Location: kernel/trace/ring_buffer.c:3588
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
**Symbols:**

```
ffffffff811a21b0-ffffffff811a2211: ring_buffer_iter_empty (STB_GLOBAL)
```
</details>
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
