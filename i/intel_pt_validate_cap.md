# Function: <code>intel_pt_validate_cap</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828889ae)
Location: arch/x86/events/intel/pt.c:79
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81012b10-ffffffff81012b43: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8289fb39)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81013eb0-ffffffff81013ee3: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828a2c0b)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81014660-ffffffff81014693: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101674e)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
**Symbols:**

```
ffffffff81015cb0-ffffffff81015ce3: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81016bee)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
**Symbols:**

```
ffffffff81016150-ffffffff81016183: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810190c8)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
```
**Symbols:**

```
ffffffff81017440-ffffffff81017473: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101afec)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81c963d6-ffffffff81c963f9: intel_pt_validate_cap.cold (STB_LOCAL)
ffffffff810193b0-ffffffff81019414: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8101d5e0)
Location: arch/x86/events/intel/pt.c:75
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81e456cd-ffffffff81e456f0: intel_pt_validate_cap.cold (STB_LOCAL)
ffffffff8101b450-ffffffff8101b4c0: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff810219f7)
Location: arch/x86/events/intel/pt.c:75
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_cap_show
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
```
**Symbols:**

```
ffffffff82050f1a-ffffffff82050f3d: intel_pt_validate_cap.cold (STB_LOCAL)
ffffffff8101f6a0-ffffffff8101f710: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81021747)
Location: arch/x86/events/intel/pt.c:75
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_cap_show
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
```
**Symbols:**

```
ffffffff820cf30e-ffffffff820cf331: intel_pt_validate_cap.cold (STB_LOCAL)
ffffffff8101f3b0-ffffffff8101f420: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff81027417)
Location: arch/x86/events/intel/pt.c:75
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_cap_show
Direct callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
```
**Symbols:**

```
ffffffff821a9c7c-ffffffff821a9c9f: intel_pt_validate_cap.cold (STB_LOCAL)
ffffffff81025470-ffffffff810254e0: intel_pt_validate_cap (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff82890c0b)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81014660-ffffffff81014693: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8288eaf2)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81013990-ffffffff810139c3: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828a3c0b)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81014620-ffffffff81014653: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_cap(u32 *caps, enum pt_capabilities capability);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828a3c1f)
Location: arch/x86/events/intel/pt.c:71
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_buffer_reset_markers
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_handle_status
  - arch/x86/events/intel/pt.c:pt_topa_dump
  - arch/x86/events/intel/pt.c:topa_insert_table
  - arch/x86/events/intel/pt.c:pt_cap_show
```
**Symbols:**

```
ffffffff81014860-ffffffff81014893: intel_pt_validate_cap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
