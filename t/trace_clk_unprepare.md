# Function: <code>trace_clk_unprepare</code>

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
In drivers/clk/clk.c (ffffffff816e5504)
Location: include/trace/events/clk.h:82
Inline: True
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
In drivers/clk/clk.c (ffffffff8174a2dc)
Location: include/trace/events/clk.h:82
Inline: True
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
In drivers/clk/clk.c (ffffffff81532b5c)
Location: include/trace/events/clk.h:82
Inline: True
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
In drivers/clk/clk.c (ffffffff815453c5)
Location: include/trace/events/clk.h:82
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff815a8834)
Location: include/trace/events/clk.h:82
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff815e1bc8)
Location: include/trace/events/clk.h:82
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff815fbd58)
Location: include/trace/events/clk.h:82
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff8162e9a8)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff816504d8)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff82d16498)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff8300414a)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_clk_unprepare(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fcbc7)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
```
**Symbols:**

```
ffffffff81bf5a9d-ffffffff81bf5ad6: trace_clk_unprepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_clk_unprepare(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81778928)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
```
**Symbols:**

```
ffffffff81cf3079-ffffffff81cf30af: trace_clk_unprepare (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff834b003c)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff83ee9902)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff8370f2f2)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff83942ac2)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffff8000107c06a8)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (c08ea594)
Location: include/trace/events/clk.h:74
Inline: True
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050e8fe)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff81616538)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff8160aa68)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff81644318)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
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
In drivers/clk/clk.c (ffffffff8165e758)
Location: include/trace/events/clk.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
