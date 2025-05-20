# Function: <code>pebs_update_adaptive_cfg</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f39f)
Location: arch/x86/events/intel/ds.c:959
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff8100fa6a)
Location: arch/x86/events/intel/ds.c:965
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 pebs_update_adaptive_cfg(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010c30)
Location: arch/x86/events/intel/ds.c:966
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
```
**Symbols:**

```
ffffffff81010c30-ffffffff81010d00: pebs_update_adaptive_cfg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 pebs_update_adaptive_cfg(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010190)
Location: arch/x86/events/intel/ds.c:967
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
```
**Symbols:**

```
ffffffff81010190-ffffffff81010250: pebs_update_adaptive_cfg (STB_LOCAL)
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
In arch/x86/events/intel/ds.c (ffffffff810114f8)
Location: arch/x86/events/intel/ds.c:1065
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff81012318)
Location: arch/x86/events/intel/ds.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff81013cf3)
Location: arch/x86/events/intel/ds.c:1115
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff81017d5e)
Location: arch/x86/events/intel/ds.c:1132
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff81017628)
Location: arch/x86/events/intel/ds.c:1181
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff8101d168)
Location: arch/x86/events/intel/ds.c:1186
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff8100fa6a)
Location: arch/x86/events/intel/ds.c:965
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff8100e7ca)
Location: arch/x86/events/intel/ds.c:965
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff8100fa2a)
Location: arch/x86/events/intel/ds.c:965
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
In arch/x86/events/intel/ds.c (ffffffff8100fc3a)
Location: arch/x86/events/intel/ds.c:965
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:pebs_update_state
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
