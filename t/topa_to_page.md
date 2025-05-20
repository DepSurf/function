# Function: <code>topa_to_page</code>

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
In arch/x86/events/intel/pt.c (ffffffff81015dad)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81015fd5)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
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
In arch/x86/events/intel/pt.c (ffffffff81016475)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
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
In arch/x86/events/intel/pt.c (ffffffff81018e59)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
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
In arch/x86/events/intel/pt.c (ffffffff8101a749)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_config_buffer
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
In arch/x86/events/intel/pt.c (ffffffff8101cc18)
Location: arch/x86/events/intel/pt.c:600
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81020f92)
Location: arch/x86/events/intel/pt.c:600
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81020ce2)
Location: arch/x86/events/intel/pt.c:600
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81026e03)
Location: arch/x86/events/intel/pt.c:600
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81015dad)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff810153ed)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81015d6d)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
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
In arch/x86/events/intel/pt.c (ffffffff81015fad)
Location: arch/x86/events/intel/pt.c:582
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_start
  - arch/x86/events/intel/pt.c:intel_pt_interrupt
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_offsets
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_topa_entry_for_page
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_update_head
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:topa_insert_table
```
</details>
</li>
</ul>

## Differences
