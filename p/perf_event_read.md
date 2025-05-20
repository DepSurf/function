# Function: <code>perf_event_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b440)
Location: kernel/events/core.c:3342
Inline: True
Direct callers:
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:_perf_event_reset
```
**Symbols:**

```
ffffffff8117b440-ffffffff8117b584: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118c5b0)
Location: kernel/events/core.c:3543
Inline: True
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8118c5b0-ffffffff8118c710: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119bd00)
Location: kernel/events/core.c:3631
Inline: True
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff8119bd00-ffffffff8119beba: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3560)
Location: kernel/events/core.c:3724
Inline: True
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:perf_event_read_value
  - kernel/events/core.c:perf_event_read_value
```
**Symbols:**

```
ffffffff811a3560-ffffffff811a3717: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7530)
Location: kernel/events/core.c:3640
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff811b7530-ffffffff811b7760: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d6f40)
Location: kernel/events/core.c:3973
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff811d6f40-ffffffff811d715f: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e7370)
Location: kernel/events/core.c:3974
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff811e7370-ffffffff811e758d: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe9a0)
Location: kernel/events/core.c:3994
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff811fe9a0-ffffffff811febc7: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ba00)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff8120ba00-ffffffff8120bc27: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81234d60)
Location: kernel/events/core.c:4314
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff81234d60-ffffffff81234f88: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f1b0)
Location: kernel/events/core.c:4391
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff8123f1b0-ffffffff8123f3d8: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243380)
Location: kernel/events/core.c:4471
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff81243380-ffffffff812435ab: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127dc10)
Location: kernel/events/core.c:4578
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff8127dc10-ffffffff8127debb: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d2a20)
Location: kernel/events/core.c:4476
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff812d2a20-ffffffff812d2cb2: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133ba60)
Location: kernel/events/core.c:4596
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff8133ba60-ffffffff8133bceb: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c5c0)
Location: kernel/events/core.c:4596
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff8136c5c0-ffffffff8136c83d: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395850)
Location: kernel/events/core.c:4640
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff81395850-ffffffff81395a46: perf_event_read (STB_LOCAL)
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
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010295a28)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffff800010295a28-ffff800010295ca8: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c5ab8)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
c04c5ab8-c04c5d08: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003432b0)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
c0000000003432b0-c000000000343528: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c6976)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffe0001c6976-ffffffe0001c6b30: perf_event_read (STB_LOCAL)
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
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204020)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff81204020-ffffffff81204247: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f6db0)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff811f6db0-ffffffff811f6fd7: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201df0)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff81201df0-ffffffff81202017: perf_event_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_read(struct perf_event *event, bool group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211620)
Location: kernel/events/core.c:4091
Inline: False
Direct callers:
  - kernel/events/core.c:_perf_event_reset
  - kernel/events/core.c:__perf_read_group_add
  - kernel/events/core.c:__perf_event_read_value
  - kernel/events/core.c:__perf_event_read_value
```
**Symbols:**

```
ffffffff81211620-ffffffff8121186b: perf_event_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
