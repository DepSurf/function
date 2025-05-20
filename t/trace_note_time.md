# Function: <code>trace_note_time</code>

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
In kernel/trace/blktrace.c (ffffffff8115ccd3)
Location: kernel/trace/blktrace.c:128
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
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
In kernel/trace/blktrace.c (ffffffff81167693)
Location: kernel/trace/blktrace.c:128
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
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
In kernel/trace/blktrace.c (ffffffff81172ae3)
Location: kernel/trace/blktrace.c:128
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
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
In kernel/trace/blktrace.c (ffffffff81175df2)
Location: kernel/trace/blktrace.c:130
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
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
In kernel/trace/blktrace.c (ffffffff81183511)
Location: kernel/trace/blktrace.c:142
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811927d1)
Location: kernel/trace/blktrace.c:142
Inline: True
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
In kernel/trace/blktrace.c (ffffffff8119ff11)
Location: kernel/trace/blktrace.c:130
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811adc60)
Location: kernel/trace/blktrace.c:130
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811b9500)
Location: kernel/trace/blktrace.c:130
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d1c29)
Location: kernel/trace/blktrace.c:132
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cf5a9)
Location: kernel/trace/blktrace.c:132
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cfad5)
Location: kernel/trace/blktrace.c:132
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811fc725)
Location: kernel/trace/blktrace.c:132
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_note_time(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81237330)
Location: kernel/trace/blktrace.c:132
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
```
**Symbols:**

```
ffffffff81237330-ffffffff812373e7: trace_note_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_note_time(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812840d0)
Location: kernel/trace/blktrace.c:132
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_start
```
**Symbols:**

```
ffffffff812840d0-ffffffff81284187: trace_note_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_note_time(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812a0d80)
Location: kernel/trace/blktrace.c:132
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_start
```
**Symbols:**

```
ffffffff812a0d80-ffffffff812a0e37: trace_note_time (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_note_time(struct blk_trace *bt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812bc4b0)
Location: kernel/trace/blktrace.c:132
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_start
```
**Symbols:**

```
ffffffff812bc4b0-ffffffff812bc567: trace_note_time (STB_LOCAL)
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
In kernel/trace/blktrace.c (ffff8000102367f8)
Location: kernel/trace/blktrace.c:130
Inline: True
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
In kernel/trace/blktrace.c (c04738bc)
Location: kernel/trace/blktrace.c:130
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
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
In kernel/trace/blktrace.c (c0000000002c3de0)
Location: kernel/trace/blktrace.c:130
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
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
In kernel/trace/blktrace.c (ffffffe00018e900)
Location: kernel/trace/blktrace.c:130
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
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
In kernel/trace/blktrace.c (ffffffff811b1b20)
Location: kernel/trace/blktrace.c:130
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811a4ab4)
Location: kernel/trace/blktrace.c:130
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811af8f0)
Location: kernel/trace/blktrace.c:130
Inline: True
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
In kernel/trace/blktrace.c (ffffffff811bd95e)
Location: kernel/trace/blktrace.c:130
Inline: True
```
</details>
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
