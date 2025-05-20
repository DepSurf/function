# Function: <code>ata_msleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815c8660)
Location: drivers/ata/libata-core.c:6693
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
**Symbols:**

```
ffffffff815c8660-ffffffff815c86b4: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816217f0)
Location: drivers/ata/libata-core.c:6892
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff816217f0-ffffffff8162186a: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81652370)
Location: drivers/ata/libata-core.c:6934
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81652370-ffffffff816523ea: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81666990)
Location: drivers/ata/libata-core.c:7020
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81666990-ffffffff81666a0a: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816cfff0)
Location: drivers/ata/libata-core.c:7050
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff816cfff0-ffffffff816d006a: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8170ca20)
Location: drivers/ata/libata-core.c:7097
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff8170ca20-ffffffff8170caa1: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8172eea0)
Location: drivers/ata/libata-core.c:7101
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff8172eea0-ffffffff8172ef21: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8176a680)
Location: drivers/ata/libata-core.c:7086
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff8176a680-ffffffff8176a6fc: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178e6f0)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff8178e6f0-ffffffff8178e76c: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81854c3a)
Location: drivers/ata/libata-core.c:6338
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff818526a0-ffffffff8185271c: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81864f0a)
Location: drivers/ata/libata-core.c:6338
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81862a00-ffffffff81862a7c: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818479aa)
Location: drivers/ata/libata-core.c:6338
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81845800-ffffffff81845879: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff818d495a)
Location: drivers/ata/libata-core.c:6400
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff818d2290-ffffffff818d230e: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81a25179)
Location: drivers/ata/libata-core.c:6411
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81a22950-ffffffff81a22a18: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba72d9)
Location: drivers/ata/libata-core.c:6417
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
**Symbols:**

```
ffffffff81ba4120-ffffffff81ba41e8: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfdea9)
Location: drivers/ata/libata-core.c:6643
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
**Symbols:**

```
ffffffff81bfa820-ffffffff81bfa8e8: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c53c59)
Location: drivers/ata/libata-core.c:6614
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_resume
  - drivers/ata/libata-sata.c:sata_link_debounce
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
```
**Symbols:**

```
ffffffff81c502c0-ffffffff81c50388: ata_msleep (STB_GLOBAL)
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
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff8000109973c8)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/ata/libahci.c:ahci_set_lpm
```
**Symbols:**

```
ffff8000109973c8-ffff800010997468: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a67e90)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libahci.c:ahci_do_softreset
  - drivers/ata/libahci.c:ahci_set_lpm
```
**Symbols:**

```
c0a67e90-c0a67f28: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5a9d0)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
c000000000a5a9d0-c000000000a5aab0: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005f8c6c)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffe0005f8c6c-ffffffe0005f8d00: ata_msleep (STB_GLOBAL)
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
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81753860)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81753860-ffffffff817538dc: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81733700)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81733700-ffffffff8173377c: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81783570)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff81783570-ffffffff817835ec: ata_msleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ata_msleep(struct ata_port *ap, unsigned int msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179d430)
Location: drivers/ata/libata-core.c:7133
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_register
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_resume
  - drivers/ata/libata-core.c:sata_link_debounce
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:ata_wait_ready
  - drivers/ata/libata-eh.c:ata_port_wait_eh
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_pio_task
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
  - drivers/ata/libata-sff.c:ata_sff_busy_sleep
```
**Symbols:**

```
ffffffff8179d430-ffffffff8179d4ac: ata_msleep (STB_GLOBAL)
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
