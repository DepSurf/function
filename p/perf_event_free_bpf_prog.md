# Function: <code>perf_event_free_bpf_prog</code>

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
In kernel/events/core.c (ffffffff81180737)
Location: kernel/events/core.c:7103
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81192495)
Location: kernel/events/core.c:7713
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811a1c3e)
Location: kernel/events/core.c:7898
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811a942e)
Location: kernel/events/core.c:8121
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811bcc8e)
Location: kernel/events/core.c:8114
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811dce4e)
Location: kernel/events/core.c:8640
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811ed24e)
Location: kernel/events/core.c:8680
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81204c3e)
Location: kernel/events/core.c:8984
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8121182e)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8123d910)
Location: kernel/events/core.c:9648
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81247cb0)
Location: kernel/events/core.c:9932
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff8124bb70)
Location: kernel/events/core.c:10062
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void perf_event_free_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81287430)
Location: kernel/events/core.c:10173
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_release
```
**Symbols:**

```
ffffffff8128ce40-ffffffff8128ce9f: perf_event_free_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void perf_event_free_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812dbbb7)
Location: kernel/events/core.c:10108
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_release
```
**Symbols:**

```
ffffffff812e1ae0-ffffffff812e1b5c: perf_event_free_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void perf_event_free_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81343e87)
Location: kernel/events/core.c:10473
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_release
```
**Symbols:**

```
ffffffff8134a070-ffffffff8134a0ec: perf_event_free_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void perf_event_free_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81374f17)
Location: kernel/events/core.c:10513
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_release
```
**Symbols:**

```
ffffffff8137b0a0-ffffffff8137b11c: perf_event_free_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void perf_event_free_bpf_prog(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8139e247)
Location: kernel/events/core.c:10583
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
Direct callers:
  - kernel/bpf/syscall.c:bpf_perf_link_release
```
**Symbols:**

```
ffffffff813a42a0-ffffffff813a431c: perf_event_free_bpf_prog (STB_GLOBAL)
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
In kernel/events/core.c (ffff80001029bbf4)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (c04cb12c)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (c00000000034bc8c)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffe0001c9724)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81209e7e)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff811fcc2e)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff81207c1e)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
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
In kernel/events/core.c (ffffffff812169ae)
Location: kernel/events/core.c:9100
Inline: True
Inline callers:
  - kernel/events/core.c:_free_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
