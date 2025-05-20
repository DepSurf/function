# Function: <code>sata_scr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c8830)
Location: drivers/ata/libata-core.c:5165
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815c8830-ffffffff815c887b: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81620e30)
Location: drivers/ata/libata-core.c:5357
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81620e30-ffffffff81620e7b: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816519b0)
Location: drivers/ata/libata-core.c:5399
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816519b0-ffffffff816519fb: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666020)
Location: drivers/ata/libata-core.c:5485
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81666020-ffffffff8166606b: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cf650)
Location: drivers/ata/libata-core.c:5516
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816cf650-ffffffff816cf6a1: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170c090)
Location: drivers/ata/libata-core.c:5532
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8170c090-ffffffff8170c0e6: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172e510)
Location: drivers/ata/libata-core.c:5536
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8172e510-ffffffff8172e566: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81769d00)
Location: drivers/ata/libata-core.c:5521
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81769d00-ffffffff81769d56: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178dd60)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8178dd60-ffffffff8178ddb6: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818675f0)
Location: drivers/ata/libata-sata.c:91
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
```
**Symbols:**

```
ffffffff818675f0-ffffffff81867646: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81876400)
Location: drivers/ata/libata-sata.c:91
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
```
**Symbols:**

```
ffffffff81876400-ffffffff81876456: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81858c30)
Location: drivers/ata/libata-sata.c:91
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
```
**Symbols:**

```
ffffffff81858c30-ffffffff81858c86: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818e75c0)
Location: drivers/ata/libata-sata.c:91
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
```
**Symbols:**

```
ffffffff818e75c0-ffffffff818e7616: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81a38d30)
Location: drivers/ata/libata-sata.c:91
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
```
**Symbols:**

```
ffffffff81a38d30-ffffffff81a38d97: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbdd70)
Location: drivers/ata/libata-sata.c:91
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
```
**Symbols:**

```
ffffffff81bbdd70-ffffffff81bbddd7: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c155c0)
Location: drivers/ata/libata-sata.c:93
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
```
**Symbols:**

```
ffffffff81c155c0-ffffffff81c15627: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6a760)
Location: drivers/ata/libata-sata.c:93
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-eh.c:ata_eh_unload
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_set_spd
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
```
**Symbols:**

```
ffffffff81c6a760-ffffffff81c6a7c7: sata_scr_write (STB_GLOBAL)
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
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010996c60)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffff800010996c60-ffff800010996d14: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a672d0)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c0a672d0-c0a67354: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a59990)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a59990-c000000000a59a5c: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f816e)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0005f816e-ffffffe0005f81fc: sata_scr_write (STB_GLOBAL)
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
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81752ef0)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81752ef0-ffffffff81752f46: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81732d90)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81732d90-ffffffff81732de6: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81782be0)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81782be0-ffffffff81782c36: sata_scr_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sata_scr_write(struct ata_link *link, int reg, u32 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179caa0)
Location: drivers/ata/libata-core.c:5545
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_scsi_port_error_handler
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8179caa0-ffffffff8179caf6: sata_scr_write (STB_GLOBAL)
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
