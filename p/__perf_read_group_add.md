# Function: <code>__perf_read_group_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff8117a220)
Location: kernel/events/core.c:3917
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8117a220-ffffffff8117a3bb: __perf_read_group_add.part.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff81190e3f)
Location: kernel/events/core.c:4225
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8118af50-ffffffff8118b0e4: __perf_read_group_add.part.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (ffffffff811a051f)
Location: kernel/events/core.c:4322
Inline: True
Inline callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81199e80-ffffffff8119a014: __perf_read_group_add.part.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3810)
Location: kernel/events/core.c:4409
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff811a3810-ffffffff811a39ac: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7850)
Location: kernel/events/core.c:4360
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff811b7850-ffffffff811b79e5: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d7250)
Location: kernel/events/core.c:4698
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff811d7250-ffffffff811d73d8: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e7680)
Location: kernel/events/core.c:4699
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff811e7680-ffffffff811e7808: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fecd0)
Location: kernel/events/core.c:4742
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff811fecd0-ffffffff811fee58: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120bd30)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8120bd30-ffffffff8120beb8: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812350e0)
Location: kernel/events/core.c:5065
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read_group
  - kernel/events/core.c:perf_read_group
```
**Symbols:**

```
ffffffff812350e0-ffffffff81235270: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f530)
Location: kernel/events/core.c:5144
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read_group
  - kernel/events/core.c:perf_read_group
```
**Symbols:**

```
ffffffff8123f530-ffffffff8123f6b3: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243700)
Location: kernel/events/core.c:5228
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81243700-ffffffff81243884: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8127e010)
Location: kernel/events/core.c:5334
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8127e010-ffffffff8127e194: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812d2e30)
Location: kernel/events/core.c:5232
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff812d2e30-ffffffff812d2fe1: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8133be90)
Location: kernel/events/core.c:5444
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8133be90-ffffffff8133c075: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8136c9e0)
Location: kernel/events/core.c:5444
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff8136c9e0-ffffffff8136cbc5: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81395bf0)
Location: kernel/events/core.c:5493
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81395bf0-ffffffff81395e0a: __perf_read_group_add (STB_LOCAL)
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
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010295e08)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffff800010295e08-ffff800010295fac: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c5ec8)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
c04c5ec8-c04c6148: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000343670)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
c000000000343670-c0000000003438a4: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c6c5a)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffe0001c6c5a-ffffffe0001c6d80: __perf_read_group_add (STB_LOCAL)
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
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204350)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81204350-ffffffff812044d8: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f70e0)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff811f70e0-ffffffff811f7268: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81202120)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81202120-ffffffff812022a8: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __perf_read_group_add(struct perf_event *leader, u64 read_format, u64 *values);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81211970)
Location: kernel/events/core.c:4837
Inline: False
Direct callers:
  - kernel/events/core.c:perf_read
  - kernel/events/core.c:perf_read
```
**Symbols:**

```
ffffffff81211970-ffffffff81211af8: __perf_read_group_add (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
