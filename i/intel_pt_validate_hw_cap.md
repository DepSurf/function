# Function: <code>intel_pt_validate_hw_cap</code>

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
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828889ae)
Location: arch/x86/events/intel/pt.c:89
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
ffffffff81012b50-ffffffff81012b87: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8289fb39)
Location: arch/x86/events/intel/pt.c:81
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
ffffffff81013ef0-ffffffff81013f27: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828a2c0b)
Location: arch/x86/events/intel/pt.c:81
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
ffffffff810146a0-ffffffff810146d7: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff82cc8cb1)
Location: arch/x86/events/intel/pt.c:81
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
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
ffffffff81016b50-ffffffff81016b87: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff82fb4ac8)
Location: arch/x86/events/intel/pt.c:81
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
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
ffffffff81016ff0-ffffffff81017027: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff831bf039)
Location: arch/x86/events/intel/pt.c:81
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
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
```
**Symbols:**

```
ffffffff81018050-ffffffff81018087: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8329f4c5)
Location: arch/x86/events/intel/pt.c:81
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
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
```
**Symbols:**

```
ffffffff81c96618-ffffffff81c9663b: intel_pt_validate_hw_cap.cold (STB_LOCAL)
ffffffff8101bb30-ffffffff8101bb8f: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8344e2bd)
Location: arch/x86/events/intel/pt.c:85
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
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
ffffffff81e45aad-ffffffff81e45ad0: intel_pt_validate_hw_cap.cold (STB_LOCAL)
ffffffff8101e1e0-ffffffff8101e24b: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff83e69861)
Location: arch/x86/events/intel/pt.c:85
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
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
ffffffff820512d1-ffffffff820512f4: intel_pt_validate_hw_cap.cold (STB_LOCAL)
ffffffff81022680-ffffffff810226eb: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8368a1f1)
Location: arch/x86/events/intel/pt.c:85
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
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
ffffffff820cf703-ffffffff820cf726: intel_pt_validate_hw_cap.cold (STB_LOCAL)
ffffffff81022370-ffffffff810223db: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff838b9db1)
Location: arch/x86/events/intel/pt.c:85
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_addr_filters_validate
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
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
ffffffff821a9ffc-ffffffff821aa01f: intel_pt_validate_hw_cap.cold (STB_LOCAL)
ffffffff81027b50-ffffffff81027bbb: intel_pt_validate_hw_cap (STB_GLOBAL)
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
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff82890c0b)
Location: arch/x86/events/intel/pt.c:81
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
ffffffff810146a0-ffffffff810146d7: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff8288eaf2)
Location: arch/x86/events/intel/pt.c:81
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
ffffffff810139d0-ffffffff81013a07: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828a3c0b)
Location: arch/x86/events/intel/pt.c:81
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
ffffffff81014660-ffffffff81014697: intel_pt_validate_hw_cap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 intel_pt_validate_hw_cap(enum pt_capabilities cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/pt.c (ffffffff828a3c1f)
Location: arch/x86/events/intel/pt.c:81
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
ffffffff810148a0-ffffffff810148d7: intel_pt_validate_hw_cap (STB_GLOBAL)
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
