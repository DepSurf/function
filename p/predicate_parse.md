# Function: <code>predicate_parse</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81199723)
Location: kernel/trace/trace_events_filter.c:422
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (ffffffff811a7883)
Location: kernel/trace/trace_events_filter.c:409
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_preds
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
In kernel/trace/trace_events_filter.c (0)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811b54a0-ffffffff811b5939: predicate_parse.constprop.0 (STB_LOCAL)
ffffffff811b672d-ffffffff811b674f: predicate_parse.constprop.0.cold (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811c0b00)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811c0b00-ffffffff811c0fb9: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811da880)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811da880-ffffffff811dad70: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d79b0)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811d79b0-ffffffff811d7ea0: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d8ca0)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811d8ca0-ffffffff811d918f: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81205fb0)
Location: kernel/trace/trace_events_filter.c:411
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff81205fb0-ffffffff8120649f: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff81241790)
Location: kernel/trace/trace_events_filter.c:411
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff81241790-ffffffff81241d4a: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128f120)
Location: kernel/trace/trace_events_filter.c:447
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff8128f120-ffffffff8128f6da: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812ac2e0)
Location: kernel/trace/trace_events_filter.c:450
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff812ac2e0-ffffffff812ac887: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c8760)
Location: kernel/trace/trace_events_filter.c:470
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff812c8760-ffffffff812c8d1b: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
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
In kernel/trace/trace_events_filter.c (ffff8000102401a0)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffff8000102401a0-ffff800010240688: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047bb08)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
c047bb08-c047c054: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (c0000000002d0ab0)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
c0000000002d0ab0-c0000000002d11b4: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffe000195516)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffe000195516-ffffffe00019590a: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811b9120)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811b9120-ffffffff811b95d9: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811abf00)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811abf00-ffffffff811ac3b9: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811b6ef0)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811b6ef0-ffffffff811b73a9: predicate_parse.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811c4f90)
Location: kernel/trace/trace_events_filter.c:410
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:process_preds
```
**Symbols:**

```
ffffffff811c4f90-ffffffff811c5449: predicate_parse.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
