# Function: <code>pt_event_snapshot_aux</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810165c0)
Location: arch/x86/events/intel/pt.c:1583
Inline: False
```
**Symbols:**

```
ffffffff810165c0-ffffffff81016708: pt_event_snapshot_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016a60)
Location: arch/x86/events/intel/pt.c:1583
Inline: False
```
**Symbols:**

```
ffffffff81016a60-ffffffff81016ba8: pt_event_snapshot_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81017d40)
Location: arch/x86/events/intel/pt.c:1583
Inline: False
```
**Symbols:**

```
ffffffff81017d40-ffffffff81017e85: pt_event_snapshot_aux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1584
Inline: False
```
**Symbols:**

```
ffffffff8101aac0-ffffffff8101ac0f: pt_event_snapshot_aux (STB_LOCAL)
ffffffff81c9652b-ffffffff81c96546: pt_event_snapshot_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1627
Inline: False
```
**Symbols:**

```
ffffffff8101d310-ffffffff8101d480: pt_event_snapshot_aux (STB_LOCAL)
ffffffff81e45991-ffffffff81e459ac: pt_event_snapshot_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81021720-ffffffff81021890: pt_event_snapshot_aux (STB_LOCAL)
ffffffff820511e6-ffffffff82051201: pt_event_snapshot_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81021470-ffffffff810215e0: pt_event_snapshot_aux (STB_LOCAL)
ffffffff820cf619-ffffffff820cf634: pt_event_snapshot_aux.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int pt_event_snapshot_aux(struct perf_event *event, struct perf_output_handle *handle, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (0)
Location: arch/x86/events/intel/pt.c:1640
Inline: False
```
**Symbols:**

```
ffffffff81027df0-ffffffff81027f84: pt_event_snapshot_aux (STB_LOCAL)
ffffffff821aa056-ffffffff821aa071: pt_event_snapshot_aux.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
