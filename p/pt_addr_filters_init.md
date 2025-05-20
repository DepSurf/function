# Function: <code>pt_addr_filters_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810142a5)
Location: arch/x86/events/intel/pt.c:1050
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff8101447a)
Location: arch/x86/events/intel/pt.c:1071
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff81012ab2)
Location: arch/x86/events/intel/pt.c:1150
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff81012b82)
Location: arch/x86/events/intel/pt.c:1151
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff810134f4)
Location: arch/x86/events/intel/pt.c:1151
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff81013764)
Location: arch/x86/events/intel/pt.c:1161
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff81014ba7)
Location: arch/x86/events/intel/pt.c:1154
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff810154f7)
Location: arch/x86/events/intel/pt.c:1237
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pt_addr_filters_init(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016c90)
Location: arch/x86/events/intel/pt.c:1323
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81016c90-ffffffff81016d96: pt_addr_filters_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pt_addr_filters_init(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81017130)
Location: arch/x86/events/intel/pt.c:1323
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81017130-ffffffff81017236: pt_addr_filters_init (STB_LOCAL)
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
In arch/x86/events/intel/pt.c (ffffffff810190aa)
Location: arch/x86/events/intel/pt.c:1323
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff81019fbe)
Location: arch/x86/events/intel/pt.c:1324
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pt_addr_filters_init(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101be20)
Location: arch/x86/events/intel/pt.c:1342
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff8101be20-ffffffff8101bf4d: pt_addr_filters_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pt_addr_filters_init(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81020160)
Location: arch/x86/events/intel/pt.c:1351
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81020160-ffffffff8102028d: pt_addr_filters_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pt_addr_filters_init(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101feb0)
Location: arch/x86/events/intel/pt.c:1351
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff8101feb0-ffffffff8101ffdd: pt_addr_filters_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pt_addr_filters_init(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81025f70)
Location: arch/x86/events/intel/pt.c:1355
Inline: False
Direct callers:
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81025f70-ffffffff810260cc: pt_addr_filters_init (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810154f7)
Location: arch/x86/events/intel/pt.c:1237
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff810147c7)
Location: arch/x86/events/intel/pt.c:1237
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff810154b7)
Location: arch/x86/events/intel/pt.c:1237
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
In arch/x86/events/intel/pt.c (ffffffff810156f7)
Location: arch/x86/events/intel/pt.c:1237
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
