# Function: <code>ata_dev_phys_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815ca2a0)
Location: drivers/ata/libata-core.c:308
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_init
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff815ca2a0-ffffffff815ca2d2: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81627ccc)
Location: drivers/ata/libata-core.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81622b10-ffffffff81622b42: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8165892c)
Location: drivers/ata/libata-core.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81653680-ffffffff816536b2: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166d12c)
Location: drivers/ata/libata-core.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81667de0-ffffffff81667e10: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d677c)
Location: drivers/ata/libata-core.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816d1450-ffffffff816d1480: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817123b5)
Location: drivers/ata/libata-core.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8170dca0-ffffffff8170dcd2: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81734855)
Location: drivers/ata/libata-core.c:311
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81730110-ffffffff81730142: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817701e5)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8176b870-ffffffff8176b8a2: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81794245)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8178f8e0-ffffffff8178f912: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81858575)
Location: drivers/ata/libata-core.c:296
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81854220-ffffffff81854252: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818687d5)
Location: drivers/ata/libata-core.c:296
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff818644f0-ffffffff81864522: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8184b145)
Location: drivers/ata/libata-core.c:296
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81846fb0-ffffffff81846fe2: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d8555)
Location: drivers/ata/libata-core.c:302
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff818d3cb0-ffffffff818d3ce2: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a29745)
Location: drivers/ata/libata-core.c:303
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81a24370-ffffffff81a243c0: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bac255)
Location: drivers/ata/libata-core.c:303
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81ba6330-ffffffff81ba6380: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c033f5)
Location: drivers/ata/libata-core.c:303
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81bfcea0-ffffffff81bfcef0: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c58bb5)
Location: drivers/ata/libata-core.c:303
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81c52ba0-ffffffff81c52bf0: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099e86c)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffff800010999378-ffff8000109993d0: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6ef6c)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
c0a692fc-c0a69344: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a62c28)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
c000000000a5c370-c000000000a5c3b8: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fe838)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffe0005f9d84-ffffffe0005f9dca: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81759355)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81754a50-ffffffff81754a82: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817391f5)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff817348f0-ffffffff81734922: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817890c5)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81784760-ffffffff81784792: ata_dev_phys_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct ata_link *ata_dev_phys_link(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a2f15)
Location: drivers/ata/libata-core.c:295
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_init
  - drivers/ata/libata-core.c:ata_dev_configure
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8179e550-ffffffff8179e582: ata_dev_phys_link (STB_GLOBAL)
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
