# Function: <code>acpi_os_execute</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479cff)
Location: drivers/acpi/osl.c:1120
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffffffff81479cff-ffffffff81479dac: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c82c4)
Location: drivers/acpi/osl.c:1036
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffffffff814c82c4-ffffffff814c839f: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea1d4)
Location: drivers/acpi/osl.c:1031
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffffffff814ea1d4-ffffffff814ea2af: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f5f60)
Location: drivers/acpi/osl.c:1030
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffffffff814f5f60-ffffffff814f6055: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536f10)
Location: drivers/acpi/osl.c:1040
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81536f10-ffffffff8153706e: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1045
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff8156d803-ffffffff8156d848: acpi_os_execute.cold.20 (STB_LOCAL)
ffffffff8156cb10-ffffffff8156cc24: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1050
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815853c3-ffffffff81585408: acpi_os_execute.cold.21 (STB_LOCAL)
ffffffff81584740-ffffffff81584854: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1036
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815b602e-ffffffff815b6073: acpi_os_execute.cold (STB_LOCAL)
ffffffff815b5350-ffffffff815b546c: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815d725e-ffffffff815d72a3: acpi_os_execute.cold (STB_LOCAL)
ffffffff815d6580-ffffffff815d669c: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81681026-ffffffff8168106b: acpi_os_execute.cold (STB_LOCAL)
ffffffff81680280-ffffffff8168039c: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1060
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81c0098e-ffffffff81c009d3: acpi_os_execute.cold (STB_LOCAL)
ffffffff8169ed70-ffffffff8169ee8c: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1061
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81bf2483-ffffffff81bf24c8: acpi_os_execute.cold (STB_LOCAL)
ffffffff81681a20-ffffffff81681b55: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1061
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81ceed3b-ffffffff81ceed80: acpi_os_execute.cold (STB_LOCAL)
ffffffff816f6b20-ffffffff816f6c55: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1063
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81eb64c0-ffffffff81eb64fd: acpi_os_execute.cold (STB_LOCAL)
ffffffff818239f0-ffffffff81823b16: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81954c90)
Location: drivers/acpi/osl.c:1063
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff81954c90-ffffffff81954de8: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199b090)
Location: drivers/acpi/osl.c:1063
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/button.c:acpi_button_event
```
**Symbols:**

```
ffffffff8199b090-ffffffff8199b1e8: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e3510)
Location: drivers/acpi/osl.c:1060
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
  - drivers/acpi/button.c:acpi_button_event
```
**Symbols:**

```
ffffffff819e3510-ffffffff819e36d4: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763020)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffff800010763020-ffff800010763130: acpi_os_execute (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffffffff815ca6e4-ffffffff815ca729: acpi_os_execute.cold (STB_LOCAL)
ffffffff815c97a0-ffffffff815c9854: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
```
**Symbols:**

```
ffffffff815b3764-ffffffff815b37a9: acpi_os_execute.cold (STB_LOCAL)
ffffffff815b2830-ffffffff815b28e4: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815cb53e-ffffffff815cb583: acpi_os_execute.cold (STB_LOCAL)
ffffffff815ca860-ffffffff815ca97c: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_execute(acpi_execute_type type, acpi_osd_exec_callback function, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1056
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_device_fixed_event
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evmisc.c:acpi_ev_queue_notify_request
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_thread
  - drivers/acpi/acpica/dbxface.c:acpi_initialize_debugger
```
**Symbols:**

```
ffffffff815e53de-ffffffff815e5423: acpi_os_execute.cold (STB_LOCAL)
ffffffff815e4700-ffffffff815e481c: acpi_os_execute (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
