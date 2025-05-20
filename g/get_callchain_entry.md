# Function: <code>get_callchain_entry</code>

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
In kernel/events/callchain.c (ffffffff8118626c)
Location: kernel/events/callchain.c:135
Inline: True
Inline callers:
  - kernel/events/callchain.c:perf_callchain
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
In kernel/events/callchain.c (ffffffff81198541)
Location: kernel/events/callchain.c:154
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff811a7f21)
Location: kernel/events/callchain.c:154
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff811af675)
Location: kernel/events/callchain.c:156
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff811c3205)
Location: kernel/events/callchain.c:156
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff811e35c3)
Location: kernel/events/callchain.c:153
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff811f3a83)
Location: kernel/events/callchain.c:153
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff8120b778)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff81218a58)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81244440)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81244440-ffffffff812444fc: get_callchain_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8124ed30)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff8124ed30-ffffffff8124edec: get_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff81253640)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff81253640-ffffffff812536fc: get_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8128ef80)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff8128ef80-ffffffff8128f03c: get_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff812e3ec0)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff812e3ec0-ffffffff812e3f99: get_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8134c5f0)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff8134c5f0-ffffffff8134c6c9: get_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8137d640)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff8137d640-ffffffff8137d719: get_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_callchain_entry *get_callchain_entry(int *rctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff813a68a0)
Location: kernel/events/callchain.c:152
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
  - kernel/events/callchain.c:get_perf_callchain
```
**Symbols:**

```
ffffffff813a68a0-ffffffff813a6979: get_callchain_entry (STB_GLOBAL)
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
In kernel/events/callchain.c (ffff8000102a3830)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (c04d3018)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (c000000000355c64)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffe0001d1e4c)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff812110a8)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff81203e38)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff8120ee48)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff8121dd58)
Location: kernel/events/callchain.c:152
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
