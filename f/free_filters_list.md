# Function: <code>free_filters_list</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81189910)
Location: kernel/events/core.c:7779
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff81189910-ffffffff81189984: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81198ce0)
Location: kernel/events/core.c:7966
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_event_set_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff81198ce0-ffffffff81198d54: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0dc0)
Location: kernel/events/core.c:8189
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811a0dc0-ffffffff811a0e34: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b46c0)
Location: kernel/events/core.c:8175
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:perf_ioctl
```
**Symbols:**

```
ffffffff811b46c0-ffffffff811b4734: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d3850)
Location: kernel/events/core.c:8701
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811d3850-ffffffff811d38bf: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3c20)
Location: kernel/events/core.c:8741
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
```
**Symbols:**

```
ffffffff811e3c20-ffffffff811e3c8f: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fade0)
Location: kernel/events/core.c:9045
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff811fade0-ffffffff811fae51: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81207eb0)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff81207eb0-ffffffff81207f21: free_filters_list (STB_LOCAL)
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
In kernel/events/core.c (ffffffff81239099)
Location: kernel/events/core.c:9709
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
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
In kernel/events/core.c (ffffffff81243039)
Location: kernel/events/core.c:9993
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
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
In kernel/events/core.c (ffffffff81242b55)
Location: kernel/events/core.c:10123
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff8127d35c)
Location: kernel/events/core.c:10235
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff812d16e5)
Location: kernel/events/core.c:10170
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff8133a4a5)
Location: kernel/events/core.c:10535
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff8136b355)
Location: kernel/events/core.c:10575
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
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
In kernel/events/core.c (ffffffff81393fc6)
Location: kernel/events/core.c:10645
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:perf_addr_filters_splice
  - kernel/events/core.c:_perf_ioctl
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
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010291638)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffff800010291638-ffff8000102916b4: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c2580)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
c04c2580-c04c25e0: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033f950)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
c00000000033f950-c00000000033fa24: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4024)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffe0001c4024-ffffffe0001c408c: free_filters_list (STB_LOCAL)
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
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812004d0)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff812004d0-ffffffff81200541: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f3220)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff811f3220-ffffffff811f3291: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe2a0)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff811fe2a0-ffffffff811fe311: free_filters_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_filters_list(struct list_head *filters);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d300)
Location: kernel/events/core.c:9161
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_event_set_filter
  - kernel/events/core.c:perf_addr_filters_splice
```
**Symbols:**

```
ffffffff8120d300-ffffffff8120d371: free_filters_list (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
