# Function: <code>trace_clk_unprepare_complete</code>

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
In drivers/clk/clk.c (ffffffff816e551c)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff8174a2f4)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff81532b74)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff815453dd)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff815a8862)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff815e1bf6)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff815fbd86)
Location: include/trace/events/clk.h:89
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
In drivers/clk/clk.c (ffffffff8162e9d7)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff81650507)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff82d1654b)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff830041ed)
Location: include/trace/events/clk.h:81
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
void trace_clk_unprepare_complete(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fcbf6)
Location: include/trace/events/clk.h:81
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
```
**Symbols:**

```
ffffffff81bf5ad6-ffffffff81bf5b0f: trace_clk_unprepare_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_clk_unprepare_complete(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81778963)
Location: include/trace/events/clk.h:81
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_unprepare
  - drivers/clk/clk.c:clk_core_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
```
**Symbols:**

```
ffffffff81cf30af-ffffffff81cf30e5: trace_clk_unprepare_complete (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff834b00fd)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff83ee991d)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff8370f30d)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff83942add)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffff8000107c06d4)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (c08ea5c0)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffe00050e92e)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff81616567)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff8160aa97)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff81644347)
Location: include/trace/events/clk.h:81
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
In drivers/clk/clk.c (ffffffff8165e787)
Location: include/trace/events/clk.h:81
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
