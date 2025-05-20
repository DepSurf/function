# Function: <code>hist_elt_data_free</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c300)
Location: kernel/trace/trace_events_hist.c:1952
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff8119c300-ffffffff8119c340: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aa660)
Location: kernel/trace/trace_events_hist.c:2036
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811aa660-ffffffff811aa6a0: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b8590)
Location: kernel/trace/trace_events_hist.c:2190
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811b8590-ffffffff811b85d0: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c3b70)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811c3b70-ffffffff811c3bb0: hist_elt_data_free (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e411c)
Location: kernel/trace/trace_events_hist.c:1356
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
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
In kernel/trace/trace_events_hist.c (ffffffff811e1b1d)
Location: kernel/trace/trace_events_hist.c:1359
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
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
In kernel/trace/trace_events_hist.c (ffffffff811e28ed)
Location: kernel/trace/trace_events_hist.c:1376
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
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
In kernel/trace/trace_events_hist.c (ffffffff812141f5)
Location: kernel/trace/trace_events_hist.c:1401
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8125004e)
Location: kernel/trace/trace_events_hist.c:1575
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
**Symbols:**

```
ffffffff8124b9c0-ffffffff8124ba17: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129effe)
Location: kernel/trace/trace_events_hist.c:1607
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
**Symbols:**

```
ffffffff81299ec0-ffffffff81299f17: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bcccb)
Location: kernel/trace/trace_events_hist.c:1612
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
**Symbols:**

```
ffffffff812b7370-ffffffff812b73c4: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d946c)
Location: kernel/trace/trace_events_hist.c:1605
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
```
**Symbols:**

```
ffffffff812d39c0-ffffffff812d3a14: hist_elt_data_free (STB_LOCAL)
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
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010243748)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffff800010243748-ffff800010243798: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d64a0)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
c0000000002d64a0-c0000000002d6518: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc190)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811bc190-ffffffff811bc1d0: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811aef70)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811aef70-ffffffff811aefb0: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9f60)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811b9f60-ffffffff811b9fa0: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hist_elt_data_free(struct hist_elt_data *elt_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c8000)
Location: kernel/trace/trace_events_hist.c:2264
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_free
```
**Symbols:**

```
ffffffff811c8000-ffffffff811c8040: hist_elt_data_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
