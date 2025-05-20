# Function: <code>rb_iter_head_event</code>

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
In kernel/trace/ring_buffer.c (ffffffff811495ab)
Location: kernel/trace/ring_buffer.c:1860
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_advance_iter
  - kernel/trace/ring_buffer.c:rb_iter_peek
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811521c7)
Location: kernel/trace/ring_buffer.c:1851
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115c577)
Location: kernel/trace/ring_buffer.c:1820
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115f5fa)
Location: kernel/trace/ring_buffer.c:1822
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8116c6ba)
Location: kernel/trace/ring_buffer.c:1819
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117b17a)
Location: kernel/trace/ring_buffer.c:1892
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81188722)
Location: kernel/trace/ring_buffer.c:1940
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195393)
Location: kernel/trace/ring_buffer.c:1917
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a1283)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b62b0)
Location: kernel/trace/ring_buffer.c:1943
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff811b62b0-ffffffff811b63a5: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b3d60)
Location: kernel/trace/ring_buffer.c:2188
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff811b3d60-ffffffff811b3e55: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4cd0)
Location: kernel/trace/ring_buffer.c:2267
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff811b4cd0-ffffffff811b4dc8: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811def30)
Location: kernel/trace/ring_buffer.c:2267
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff811def30-ffffffff811df025: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216590)
Location: kernel/trace/ring_buffer.c:2303
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff81216590-ffffffff812166b9: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125fa50)
Location: kernel/trace/ring_buffer.c:2384
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff8125fa50-ffffffff8125fb79: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81276cb0)
Location: kernel/trace/ring_buffer.c:2382
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff81276cb0-ffffffff81276e71: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ring_buffer_event *rb_iter_head_event(struct ring_buffer_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812917c0)
Location: kernel/trace/ring_buffer.c:2220
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
**Symbols:**

```
ffffffff812917c0-ffffffff812918de: rb_iter_head_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021bb88)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0459278)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029da74)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017991a)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811998a3)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118cf33)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197673)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a52a3)
Location: kernel/trace/ring_buffer.c:1918
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:rb_iter_peek
  - kernel/trace/ring_buffer.c:rb_advance_iter
```
</details>
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
