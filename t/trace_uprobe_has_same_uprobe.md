# Function: <code>trace_uprobe_has_same_uprobe</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d98c4)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool trace_uprobe_has_same_uprobe(struct trace_uprobe *orig, struct trace_uprobe *comp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f55a0)
Location: kernel/trace/trace_uprobe.c:407
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
**Symbols:**

```
ffffffff811f55a0-ffffffff811f56a1: trace_uprobe_has_same_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool trace_uprobe_has_same_uprobe(struct trace_uprobe *orig, struct trace_uprobe *comp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f3f30)
Location: kernel/trace/trace_uprobe.c:407
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
**Symbols:**

```
ffffffff811f3f30-ffffffff811f4031: trace_uprobe_has_same_uprobe (STB_LOCAL)
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
In kernel/trace/trace_uprobe.c (ffffffff811f52d7)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff812273c7)
Location: kernel/trace/trace_uprobe.c:408
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff81266e17)
Location: kernel/trace/trace_uprobe.c:409
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff812b8ef7)
Location: kernel/trace/trace_uprobe.c:411
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff812dc557)
Location: kernel/trace/trace_uprobe.c:409
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff812fa637)
Location: kernel/trace/trace_uprobe.c:404
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffff800010259250)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (c048cd24)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (c0000000002fcd14)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d1ee4)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (ffffffff811c4cb4)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (ffffffff811cfcb4)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
In kernel/trace/trace_uprobe.c (ffffffff811ddf54)
Location: kernel/trace/trace_uprobe.c:407
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
</ul>
