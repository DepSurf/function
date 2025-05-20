# Function: <code>bpf_test_timer_continue</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer *t, u32 repeat, int *err, u32 *duration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a70b50)
Location: net/bpf/test_run.c:52
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81a70b50-ffffffff81a70c3a: bpf_test_timer_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer *t, u32 repeat, int *err, u32 *duration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81b2a470)
Location: net/bpf/test_run.c:54
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
```
**Symbols:**

```
ffffffff81b2a470-ffffffff81b2a55a: bpf_test_timer_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer *t, int iterations, u32 repeat, int *err, u32 *duration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb4070)
Location: net/bpf/test_run.c:57
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81cb4070-ffffffff81cb418b: bpf_test_timer_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer *t, int iterations, u32 repeat, int *err, u32 *duration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e722d0)
Location: net/bpf/test_run.c:57
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e722d0-ffffffff81e723eb: bpf_test_timer_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer *t, int iterations, u32 repeat, int *err, u32 *duration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ece440)
Location: net/bpf/test_run.c:59
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81ece440-ffffffff81ece55b: bpf_test_timer_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_test_timer_continue(struct bpf_test_timer *t, int iterations, u32 repeat, int *err, u32 *duration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f91c70)
Location: net/bpf/test_run.c:60
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81f91c70-ffffffff81f91d8b: bpf_test_timer_continue (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int iterations</code>
</li>
<li>
<b>Param reordered. </b>
<code>t, repeat, err, duration</code> ➡️ <code>t, iterations, repeat, err, duration</code>
</li>
</ul>
</details>
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
