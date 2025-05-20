# Function: <code>buf_nr_pages</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int buf_nr_pages(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8100ee80)
Location: arch/x86/events/intel/bts.c:66
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
**Symbols:**

```
ffffffff8100ee80-ffffffff8100ee9e: buf_nr_pages (STB_LOCAL)
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
In arch/x86/events/intel/bts.c (ffffffff81010363)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff8100f8c3)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff81010912)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff810115e6)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff81012cd1)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff81016d01)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff810166e4)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
In arch/x86/events/intel/bts.c (ffffffff8101c224)
Location: arch/x86/events/intel/bts.c:66
Inline: True
Inline callers:
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:bts_buffer_reset
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
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
<summary>In <code>aws</code>: ✅</summary>

```c
int buf_nr_pages(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8100ee80)
Location: arch/x86/events/intel/bts.c:66
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
**Symbols:**

```
ffffffff8100ee80-ffffffff8100ee9e: buf_nr_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int buf_nr_pages(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8100dbe0)
Location: arch/x86/events/intel/bts.c:66
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
**Symbols:**

```
ffffffff8100dbe0-ffffffff8100dbfe: buf_nr_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int buf_nr_pages(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8100ee40)
Location: arch/x86/events/intel/bts.c:66
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
**Symbols:**

```
ffffffff8100ee40-ffffffff8100ee5e: buf_nr_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int buf_nr_pages(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/bts.c (ffffffff8100f010)
Location: arch/x86/events/intel/bts.c:66
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:__bts_event_start
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
  - arch/x86/events/intel/bts.c:bts_buffer_setup_aux
```
**Symbols:**

```
ffffffff8100f010-ffffffff8100f02e: buf_nr_pages (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
