# Function: <code>ata_link_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c9340)
Location: drivers/ata/libata-core.c:6829
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
```
**Symbols:**

```
ffffffff815c9340-ffffffff815c93ec: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81621ad0)
Location: drivers/ata/libata-core.c:7033
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81621ad0-ffffffff81621b7c: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81652650)
Location: drivers/ata/libata-core.c:7075
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81652650-ffffffff816526fc: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666c70)
Location: drivers/ata/libata-core.c:7161
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81666c70-ffffffff81666d18: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d02d0)
Location: drivers/ata/libata-core.c:7191
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff816d02d0-ffffffff816d0378: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81712ea0)
Location: drivers/ata/libata-core.c:7238
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81712ea0-ffffffff81712f48: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81735350)
Location: drivers/ata/libata-core.c:7242
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81735350-ffffffff817353f8: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81770d3f)
Location: drivers/ata/libata-core.c:7227
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81770d3f-ffffffff81770de7: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81794d3d)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81794d3d-ffffffff81794de5: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81858fb5)
Location: drivers/ata/libata-core.c:6451
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_force_link_limits
  - drivers/ata/libata-core.c:ata_force_link_limits
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81858fb5-ffffffff8185905d: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c16fc8)
Location: drivers/ata/libata-core.c:6451
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:sata_print_link_status
  - drivers/ata/libata-core.c:ata_force_link_limits
  - drivers/ata/libata-core.c:ata_force_link_limits
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_handle_disabled_links
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81c16fc8-ffffffff81c17070: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c08d10)
Location: drivers/ata/libata-core.c:6451
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81c08d10-ffffffff81c08db8: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81d0d5b9)
Location: drivers/ata/libata-core.c:6513
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_prereset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:sata_down_spd_limit
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_set_lpm
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81d0d5b9-ffffffff81d0d661: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099f76c)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
```
**Symbols:**

```
ffff80001099f76c-ffff80001099f840: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6fc70)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
  - drivers/ata/libahci.c:ahci_pmp_retry_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/ata/libahci.c:ahci_do_softreset
```
**Symbols:**

```
c0a6fc70-c0a6fd38: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a63d70)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
c000000000a63d70-c000000000a63e44: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005ff3ec)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffe0005ff3ec-ffffffe0005ff482: ata_link_printk (STB_GLOBAL)
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
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81759e4d)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81759e4d-ffffffff81759ef5: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81739ced)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81739ced-ffffffff81739d95: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81789bbd)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff81789bbd-ffffffff81789c65: ata_link_printk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_link_printk(const struct ata_link *link, const char *level, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817a3a0d)
Location: drivers/ata/libata-core.c:7274
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:ata_std_postreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_link_report
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
  - drivers/ata/libata-sff.c:ata_sff_softreset
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_handle_link_fail
  - drivers/ata/libata-pmp.c:sata_pmp_scr_write
  - drivers/ata/libata-pmp.c:sata_pmp_scr_read
```
**Symbols:**

```
ffffffff817a3a0d-ffffffff817a3ab5: ata_link_printk (STB_GLOBAL)
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
