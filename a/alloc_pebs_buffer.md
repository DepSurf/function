# Function: <code>alloc_pebs_buffer</code>

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
In arch/x86/events/intel/ds.c (ffffffff81010489)
Location: arch/x86/events/intel/ds.c:262
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff8100fe86)
Location: arch/x86/events/intel/ds.c:271
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff8101000e)
Location: arch/x86/events/intel/ds.c:271
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff8100e5d7)
Location: arch/x86/events/intel/ds.c:281
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff8100ed2e)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff8100f671)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff8100fc41)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff81010d58)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff81011438)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011100)
Location: arch/x86/events/intel/ds.c:335
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff81011100-ffffffff81011254: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010730)
Location: arch/x86/events/intel/ds.c:335
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff81010730-ffffffff81010884: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810116d0)
Location: arch/x86/events/intel/ds.c:400
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810116d0-ffffffff81011824: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810124f0)
Location: arch/x86/events/intel/ds.c:400
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810124f0-ffffffff810126ed: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810140e0)
Location: arch/x86/events/intel/ds.c:449
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff810140e0-ffffffff810142d9: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81018290)
Location: arch/x86/events/intel/ds.c:456
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff81018290-ffffffff81018489: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017b70)
Location: arch/x86/events/intel/ds.c:504
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff81017b70-ffffffff81017d69: alloc_pebs_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int alloc_pebs_buffer(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101d6b0)
Location: arch/x86/events/intel/ds.c:509
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
```
**Symbols:**

```
ffffffff8101d6b0-ffffffff8101d8d8: alloc_pebs_buffer (STB_LOCAL)
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
In arch/x86/events/intel/ds.c (ffffffff81011438)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff810101d8)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff810113f8)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
In arch/x86/events/intel/ds.c (ffffffff81011608)
Location: arch/x86/events/intel/ds.c:334
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:reserve_ds_buffers
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
