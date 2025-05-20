# Function: <code>destroy_hist_trigger_attrs</code>

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
void destroy_hist_trigger_attrs(struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81171980)
Location: kernel/trace/trace_events_hist.c:207
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff81171980-ffffffff811719bc: destroy_hist_trigger_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_hist_trigger_attrs(struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8117d0f0)
Location: kernel/trace/trace_events_hist.c:207
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff8117d0f0-ffffffff8117d12c: destroy_hist_trigger_attrs (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811818a3)
Location: kernel/trace/trace_events_hist.c:208
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff81180600-ffffffff81180636: destroy_hist_trigger_attrs.part.8 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff8118f241)
Location: kernel/trace/trace_events_hist.c:233
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff8118def0-ffffffff8118df26: destroy_hist_trigger_attrs.part.8 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811a1510)
Location: kernel/trace/trace_events_hist.c:1772
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff8119de80-ffffffff8119df0e: destroy_hist_trigger_attrs.part.18 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b1329)
Location: kernel/trace/trace_events_hist.c:1856
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff811ac0e0-ffffffff811ac16e: destroy_hist_trigger_attrs.part.19 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811bf831)
Location: kernel/trace/trace_events_hist.c:2008
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811ba3c0-ffffffff811ba455: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811cb081)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811c59d0-ffffffff811c5a65: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e6f33)
Location: kernel/trace/trace_events_hist.c:1171
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811e20c0-ffffffff811e2155: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e48f3)
Location: kernel/trace/trace_events_hist.c:1174
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811dfce0-ffffffff811dfd75: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e5ed3)
Location: kernel/trace/trace_events_hist.c:1191
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811e0df0-ffffffff811e0e85: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff81216c83)
Location: kernel/trace/trace_events_hist.c:1216
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff81210b10-ffffffff81210be0: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff81255079)
Location: kernel/trace/trace_events_hist.c:1390
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff8124d6b0-ffffffff8124d78c: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812a450f)
Location: kernel/trace/trace_events_hist.c:1419
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff8129b820-ffffffff8129b8fc: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812c23d2)
Location: kernel/trace/trace_events_hist.c:1424
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff812b8f90-ffffffff812b906c: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff812deb6a)
Location: kernel/trace/trace_events_hist.c:1417
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:destroy_hist_data
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff812d55e0-ffffffff812d56bc: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff80001024a438)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffff800010245940-ffff8000102459e8: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e5440)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
c0000000002d9c00-c0000000002d9d04: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c36a1)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811bdff0-ffffffff811be085: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811b6481)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811b0dd0-ffffffff811b0e65: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811c1471)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811bbdc0-ffffffff811bbe55: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811cf511)
Location: kernel/trace/trace_events_hist.c:2080
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811c9e60-ffffffff811c9ef5: destroy_hist_trigger_attrs.part.0 (STB_LOCAL)
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
</ul>
