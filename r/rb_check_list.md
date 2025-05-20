# Function: <code>rb_check_list</code>

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
In kernel/trace/ring_buffer.c (ffffffff81147190)
Location: kernel/trace/ring_buffer.c:1088
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81147190-ffffffff811471e1: rb_check_list.isra.43 (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff8114f9a0)
Location: kernel/trace/ring_buffer.c:1079
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8114f9a0-ffffffff8114f9f1: rb_check_list.isra.43 (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff81159ba0)
Location: kernel/trace/ring_buffer.c:1077
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81159ba0-ffffffff81159bf1: rb_check_list.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115ca20)
Location: kernel/trace/ring_buffer.c:1079
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8115ca20-ffffffff8115ca53: rb_check_list.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811699c0)
Location: kernel/trace/ring_buffer.c:1082
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff811699c0-ffffffff811699f3: rb_check_list.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81178920)
Location: kernel/trace/ring_buffer.c:1111
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81178920-ffffffff81178952: rb_check_list.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81185e50)
Location: kernel/trace/ring_buffer.c:1159
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81185e50-ffffffff81185e82: rb_check_list.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811931b0)
Location: kernel/trace/ring_buffer.c:1136
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff811931b0-ffffffff811931fa: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119ebd0)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8119ebd0-ffffffff8119ebfb: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rb_check_list(struct ring_buffer_per_cpu *cpu_buffer, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4bf0)
Location: kernel/trace/ring_buffer.c:1139
Inline: False
```
**Symbols:**

```
ffffffff811b4bf0-ffffffff811b4c1e: rb_check_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rb_check_list(struct ring_buffer_per_cpu *cpu_buffer, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b24a0)
Location: kernel/trace/ring_buffer.c:1383
Inline: False
```
**Symbols:**

```
ffffffff811b24a0-ffffffff811b24ce: rb_check_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rb_check_list(struct ring_buffer_per_cpu *cpu_buffer, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2fa0)
Location: kernel/trace/ring_buffer.c:1466
Inline: False
```
**Symbols:**

```
ffffffff811b2fa0-ffffffff811b2fce: rb_check_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rb_check_list(struct ring_buffer_per_cpu *cpu_buffer, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dced0)
Location: kernel/trace/ring_buffer.c:1466
Inline: False
```
**Symbols:**

```
ffffffff811dced0-ffffffff811dcefe: rb_check_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81213c10)
Location: kernel/trace/ring_buffer.c:1502
Inline: True
```
**Symbols:**

```
ffffffff81213c10-ffffffff81213c4d: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff800010218038)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffff800010218038-ffff8000102180b4: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rb_check_list(struct ring_buffer_per_cpu *cpu_buffer, struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c04562a8)
Location: kernel/trace/ring_buffer.c:1137
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
c04562a8-c0456354: rb_check_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029a730)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
c00000000029a730-c00000000029a7a4: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177690)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffe000177690-ffffffe0001776d0: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811971f0)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff811971f0-ffffffff8119721b: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118a4d0)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff8118a4d0-ffffffff8118a4fb: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81194fc0)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff81194fc0-ffffffff81194feb: rb_check_list.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2bd0)
Location: kernel/trace/ring_buffer.c:1137
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:rb_check_pages
  - kernel/trace/ring_buffer.c:rb_check_pages
```
**Symbols:**

```
ffffffff811a2bd0-ffffffff811a2bfb: rb_check_list.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
