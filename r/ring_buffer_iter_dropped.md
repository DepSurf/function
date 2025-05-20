# Function: <code>ring_buffer_iter_dropped</code>

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
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4b20)
Location: kernel/trace/ring_buffer.c:4193
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff811b4b20-ffffffff811b4b30: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b23d0)
Location: kernel/trace/ring_buffer.c:4739
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff811b23d0-ffffffff811b23e0: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2ed0)
Location: kernel/trace/ring_buffer.c:4846
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff811b2ed0-ffffffff811b2ee0: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dce00)
Location: kernel/trace/ring_buffer.c:4846
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff811dce00-ffffffff811dce10: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213310)
Location: kernel/trace/ring_buffer.c:4888
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff81213310-ffffffff81213326: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125cb80)
Location: kernel/trace/ring_buffer.c:4994
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff8125cb80-ffffffff8125cb96: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273ad0)
Location: kernel/trace/ring_buffer.c:5001
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff81273ad0-ffffffff81273ae6: ring_buffer_iter_dropped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ring_buffer_iter_dropped(struct ring_buffer_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e060)
Location: kernel/trace/ring_buffer.c:4907
Inline: False
Direct callers:
  - kernel/trace/trace.c:peek_next_entry
```
**Symbols:**

```
ffffffff8128e060-ffffffff8128e076: ring_buffer_iter_dropped (STB_GLOBAL)
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
