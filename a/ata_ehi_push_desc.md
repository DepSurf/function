# Function: <code>ata_ehi_push_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff815d5440)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff815d5440-ffffffff815d54e6: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8162eeb0)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8162eeb0-ffffffff8162ef56: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81660000)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81660000-ffffffff816600a6: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816751a0)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff816751a0-ffffffff8167524a: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff816de800)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff816de800-ffffffff816de8aa: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8171b080)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8171b080-ffffffff8171b128: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8173d980)
Location: drivers/ata/libata-eh.c:216
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8173d980-ffffffff8173da28: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81779480)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81779480-ffffffff81779528: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff8179d2f0)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff8179d2f0-ffffffff8179d398: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818614e0)
Location: drivers/ata/libata-eh.c:196
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff818614e0-ffffffff81861588: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81870300)
Location: drivers/ata/libata-eh.c:196
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81870300-ffffffff818703a8: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81852b10)
Location: drivers/ata/libata-eh.c:196
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81852b10-ffffffff81852bb8: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff818e0a90)
Location: drivers/ata/libata-eh.c:204
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-sff.c:atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff818e0a90-ffffffff818e0b38: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81a31800)
Location: drivers/ata/libata-eh.c:204
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81a31800-ffffffff81a318d6: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81bb5c50)
Location: drivers/ata/libata-eh.c:206
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81bb5c50-ffffffff81bb5d26: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c0d170)
Location: drivers/ata/libata-eh.c:206
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81c0d170-ffffffff81c0d246: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81c621c0)
Location: drivers/ata/libata-eh.c:208
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:__atapi_pio_bytes
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81c621c0-ffffffff81c62296: ata_ehi_push_desc (STB_GLOBAL)
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
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffff8000109a84f0)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
```
**Symbols:**

```
ffff8000109a84f0-ffff8000109a85d4: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c0a78304)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
  - drivers/ata/libahci.c:ahci_error_intr
```
**Symbols:**

```
c0a78304-c0a783a8: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (c000000000a6ece0)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
c000000000a6ece0-c000000000a6edc4: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffe00060686c)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
```
**Symbols:**

```
ffffffe00060686c-ffffffe0006068de: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817623e0)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff817623e0-ffffffff81762488: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81742240)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81742240-ffffffff817422e8: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff81792170)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff81792170-ffffffff81792218: ata_ehi_push_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_ehi_push_desc(struct ata_eh_info *ehi, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-eh.c (ffffffff817abfb0)
Location: drivers/ata/libata-eh.c:199
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_qc_issue
  - drivers/ata/libata-sff.c:ata_bmdma_port_intr
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-sff.c:ata_sff_hsm_move
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
  - drivers/ata/libata-acpi.c:ata_acpi_handle_hotplug
```
**Symbols:**

```
ffffffff817abfb0-ffffffff817ac058: ata_ehi_push_desc (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
