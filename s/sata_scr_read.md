# Function: <code>sata_scr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c86c0)
Location: drivers/ata/libata-core.c:5138
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815c86c0-ffffffff815c8709: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81620de0)
Location: drivers/ata/libata-core.c:5330
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81620de0-ffffffff81620e29: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81651960)
Location: drivers/ata/libata-core.c:5372
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81651960-ffffffff816519a9: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81665fd0)
Location: drivers/ata/libata-core.c:5458
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81665fd0-ffffffff81666019: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cf600)
Location: drivers/ata/libata-core.c:5489
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816cf600-ffffffff816cf64c: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170c030)
Location: drivers/ata/libata-core.c:5505
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8170c030-ffffffff8170c081: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172e4b0)
Location: drivers/ata/libata-core.c:5509
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8172e4b0-ffffffff8172e501: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81769ca0)
Location: drivers/ata/libata-core.c:5494
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81769ca0-ffffffff81769cf1: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178dd00)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8178dd00-ffffffff8178dd51: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81867590)
Location: drivers/ata/libata-sata.c:63
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_online
  - drivers/ata/libata-core.c:ata_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff81867590-ffffffff818675e1: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818763a0)
Location: drivers/ata/libata-sata.c:63
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_online
  - drivers/ata/libata-core.c:ata_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff818763a0-ffffffff818763f1: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81858bd0)
Location: drivers/ata/libata-sata.c:63
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_online
  - drivers/ata/libata-core.c:ata_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff81858bd0-ffffffff81858c21: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff818e7560)
Location: drivers/ata/libata-sata.c:63
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff818e7560-ffffffff818e75b1: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81a3a1cc)
Location: drivers/ata/libata-sata.c:63
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff81a38cc0-ffffffff81a38d22: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbf58c)
Location: drivers/ata/libata-sata.c:63
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff81bbdcf0-ffffffff81bbdd52: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c1707c)
Location: drivers/ata/libata-sata.c:65
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff81c15540-ffffffff81c155a2: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6c17c)
Location: drivers/ata/libata-sata.c:65
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:sata_set_spd
Direct callers:
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_link_offline
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-sata.c:sata_async_notification
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_scr_lpm
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sata.c:sata_link_debounce
```
**Symbols:**

```
ffffffff81c6a6e0-ffffffff81c6a742: sata_scr_read (STB_GLOBAL)
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
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010996bb0)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffff800010996bb0-ffff800010996c60: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a67250)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/sata_highbank.c:ahci_highbank_hardreset
```
**Symbols:**

```
c0a67250-c0a672d0: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a598c0)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a598c0-c000000000a5998c: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f80e2)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0005f80e2-ffffffe0005f816e: sata_scr_read (STB_GLOBAL)
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
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81752e90)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81752e90-ffffffff81752ee1: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81732d30)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81732d30-ffffffff81732d81: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81782b80)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81782b80-ffffffff81782bd1: sata_scr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sata_scr_read(struct ata_link *link, int reg, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179ca40)
Location: drivers/ata/libata-core.c:5518
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_phys_link_offline
  - drivers/ata/libata-core.c:ata_phys_link_online
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_scr_lpm
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_set_spd
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:sata_async_notification
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8179ca40-ffffffff8179ca91: sata_scr_read (STB_GLOBAL)
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
