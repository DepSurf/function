# Function: <code>get_trace_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *get_trace_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114a7c0)
Location: kernel/trace/trace.c:1998
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
```
**Symbols:**

```
ffffffff8114a7c0-ffffffff8114a810: get_trace_buf (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811581a6)
Location: kernel/trace/trace.c:2365
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff81161406)
Location: kernel/trace/trace.c:2589
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff81164776)
Location: kernel/trace/trace.c:2795
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811716b6)
Location: kernel/trace/trace.c:2804
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff81180816)
Location: kernel/trace/trace.c:2805
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff8118e1d6)
Location: kernel/trace/trace.c:2807
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff8119bb5a)
Location: kernel/trace/trace.c:2978
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811a754a)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811bcb5a)
Location: kernel/trace/trace.c:3115
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811ba76a)
Location: kernel/trace/trace.c:3135
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811be4d3)
Location: kernel/trace/trace.c:3186
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811e8d65)
Location: kernel/trace/trace.c:3246
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220a57)
Location: kernel/trace/trace.c:3244
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126b8d3)
Location: kernel/trace/trace.c:3268
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282a1d)
Location: kernel/trace/trace.c:3359
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129db0d)
Location: kernel/trace/trace.c:3336
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
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
char *get_trace_buf();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010221360)
Location: kernel/trace/trace.c:3004
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
```
**Symbols:**

```
ffff800010221360-ffff8000102213a0: get_trace_buf (STB_LOCAL)
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
In kernel/trace/trace.c (c045f50c)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (c0000000002a5830)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffe00017e34e)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff8119fb6a)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff81192b9a)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff8119d93a)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
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
In kernel/trace/trace.c (ffffffff811ab601)
Location: kernel/trace/trace.c:3004
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_vbprintk
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
