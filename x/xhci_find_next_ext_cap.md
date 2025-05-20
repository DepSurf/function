# Function: <code>xhci_find_next_ext_cap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8169189f)
Location: drivers/usb/host/xhci-ext-caps.h:106
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816b3962)
Location: drivers/usb/host/xhci-ext-caps.h:106
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816bf94f)
Location: drivers/usb/host/xhci-ext-caps.h:106
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816e1b12)
Location: drivers/usb/host/xhci-ext-caps.h:106
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff816d42ce)
Location: drivers/usb/host/xhci-ext-caps.h:106
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff816f5d0b)
Location: drivers/usb/host/xhci-ext-caps.h:106
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817409be)
Location: drivers/usb/host/xhci-ext-caps.h:94
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8176268b)
Location: drivers/usb/host/xhci-ext-caps.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81774050)
Location: drivers/usb/host/xhci-ext-caps.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817761ba)
Location: drivers/usb/host/xhci-ext-caps.h:94
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81781538)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817a63ae)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817a6c39)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b46b0)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817b6d2a)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817a7d5c)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817cc220)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817ccae9)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817dac00)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817dd31a)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff817df160)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff817df160-ffffffff817df1ab: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817e6f11)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8180942c)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8180c939)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b280)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8181ddbd)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8181fbf0)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8181fbf0-ffffffff8181fc3a: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81817dd1)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183a2f1)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8183d939)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c6b0)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184f18d)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81851060)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81851060-ffffffff818510aa: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818e8c05)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190d021)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81910304)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e534)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81921cea)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81923352)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_reset_debug_port
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
  - drivers/usb/early/xhci-dbc.c:xdbc_bios_handoff
```
**Symbols:**

```
ffffffff81922fd0-ffffffff8192301a: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818f1ed5)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81914a71)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81917c34)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925ba4)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8192933a)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff8192aa82)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_reset_debug_port
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_bios_handoff
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff8192a6f0-ffffffff8192a73a: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff818d56c5)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f7f9e)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff818fb0c4)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909294)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8190c9ba)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81c14b09)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81c14b09-ffffffff81c14b4b: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81970330)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff819965c0)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81999f34)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9b14)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_do_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff819ad3aa)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81d220c9)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81d220c9-ffffffff81d2210b: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81aca313)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af34ad)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81af6f44)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b08b52)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81b0b9f0)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81eedc8a)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81eedc8a-ffffffff81eedcdb: xhci_find_next_ext_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81c548b3)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c809d7)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81c849d4)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98792)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81c9b990)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83efc6d0)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81cbbe17)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce76ef)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81ceb694)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cffb22)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81d02d90)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff837224d0)
Location: drivers/usb/host/xhci-ext-caps.h:98
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81d70b87)
Location: drivers/usb/host/xhci-ext-caps.h:125
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9cb4f)
Location: drivers/usb/host/xhci-ext-caps.h:125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff81da0cb4)
Location: drivers/usb/host/xhci-ext-caps.h:125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db55c2)
Location: drivers/usb/host/xhci-ext-caps.h:125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_create_dbc_dev
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db88f0)
Location: drivers/usb/host/xhci-ext-caps.h:125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff83956300)
Location: drivers/usb/host/xhci-ext-caps.h:125
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffff800010a50e04)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/pci-quirks.c:quirk_usb_handoff_xhci
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a7b3e4)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
```
```
In drivers/usb/host/xhci-ext-caps.c (ffff800010a7b9a4)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8bd94)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffff800010a8fad4)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c0b23298)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c0b4b948)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (c0b4eec4)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (c0b5eb84)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (c0b620c8)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (c000000000b19f24)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c000000000b4e860)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (c000000000b535e4)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67d8c)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (c000000000b6b95c)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffe00066d8ca)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffe00068f8ba)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffe000692bda)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0a2e)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffe0006a30a8)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817d01b1)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f26a1)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817f5ce9)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81804f5d)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff817ae0e1)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b7841)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff817bae89)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9c00)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff817cc6dd)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff8180cc51)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8182f171)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff818327b9)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81841530)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8184400d)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int xhci_find_next_ext_cap(void *base, u32 start, int id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/pci-quirks.c (ffffffff81826d61)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818492e1)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
  - drivers/usb/host/xhci-mem.c:xhci_setup_port_arrays
```
```
In drivers/usb/host/xhci-ext-caps.c (ffffffff8184c999)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
  - drivers/usb/host/xhci-ext-caps.c:xhci_ext_cap_init
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185ba90)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff8185e56d)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_extcap_regset
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff81860460)
Location: drivers/usb/host/xhci-ext-caps.h:97
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter
```
**Symbols:**

```
ffffffff81860460-ffffffff818604aa: xhci_find_next_ext_cap (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
