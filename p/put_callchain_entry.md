# Function: <code>put_callchain_entry</code>

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
In kernel/events/callchain.c (ffffffff8118631f)
Location: kernel/events/callchain.c:154
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
In kernel/events/callchain.c (ffffffff8119866d)
Location: kernel/events/callchain.c:174
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
In kernel/events/callchain.c (ffffffff811a804d)
Location: kernel/events/callchain.c:174
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
In kernel/events/callchain.c (ffffffff811af863)
Location: kernel/events/callchain.c:176
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
In kernel/events/callchain.c (ffffffff811c33e1)
Location: kernel/events/callchain.c:176
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
In kernel/events/callchain.c (ffffffff811e3783)
Location: kernel/events/callchain.c:173
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
In kernel/events/callchain.c (ffffffff811f3c51)
Location: kernel/events/callchain.c:173
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
In kernel/events/callchain.c (ffffffff8120b939)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (ffffffff81218c19)
Location: kernel/events/callchain.c:172
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
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
In kernel/events/callchain.c (ffffffff8124480d)
Location: kernel/events/callchain.c:172
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8124eec0)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff8124edf0-ffffffff8124ee11: put_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff812537d0)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff81253700-ffffffff81253721: put_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8128f110)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff8128f040-ffffffff8128f061: put_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff812e4088)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff812e3fa0-ffffffff812e3fc9: put_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8134c7d8)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff8134c6e0-ffffffff8134c709: put_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff8137d828)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff8137d730-ffffffff8137d759: put_callchain_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_callchain_entry(int rctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/callchain.c (ffffffff813a6a88)
Location: kernel/events/callchain.c:174
Inline: True
Inline callers:
  - kernel/events/callchain.c:get_perf_callchain
Direct callers:
  - kernel/bpf/stackmap.c:__bpf_get_stack
```
**Symbols:**

```
ffffffff813a6990-ffffffff813a69b9: put_callchain_entry (STB_GLOBAL)
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
In kernel/events/callchain.c (ffff8000102a3984)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (c04d315c)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (c000000000355ee4)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (ffffffe0001d1fc6)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (ffffffff81211269)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (ffffffff81203ff9)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (ffffffff8120f009)
Location: kernel/events/callchain.c:172
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
In kernel/events/callchain.c (ffffffff8121df19)
Location: kernel/events/callchain.c:172
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
