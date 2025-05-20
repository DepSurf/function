# Function: <code>sata_down_spd_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815ca770)
Location: drivers/ata/libata-core.c:2764
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff815ca770-ffffffff815ca8b8: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81622fb0)
Location: drivers/ata/libata-core.c:2939
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81622fb0-ffffffff816230f8: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81653b30)
Location: drivers/ata/libata-core.c:2981
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81653b30-ffffffff81653c78: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81668260)
Location: drivers/ata/libata-core.c:3058
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81668260-ffffffff816683ae: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d18d0)
Location: drivers/ata/libata-core.c:3060
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff816d18d0-ffffffff816d1a1c: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3054
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8171309e-ffffffff81713102: sata_down_spd_limit.cold.50 (STB_LOCAL)
ffffffff8170e100-ffffffff8170e1db: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff817305ae)
Location: drivers/ata/libata-core.c:3054
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8173554e-ffffffff817355b2: sata_down_spd_limit.cold.51 (STB_LOCAL)
ffffffff81730570-ffffffff8173064b: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8176bd1e)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81770f9c-ffffffff81771000: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff8176bce0-ffffffff8176bdbb: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8178fd8e)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81794f9a-ffffffff81794ffe: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff8178fd50-ffffffff8178fe2b: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2992
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff818593f3-ffffffff81859457: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff818546e0-ffffffff818547b6: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2992
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c17406-ffffffff81c1746a: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff818649b0-ffffffff81864a86: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2992
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81c09033-ffffffff81c09097: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81847440-ffffffff81847516: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3043
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81d0d887-ffffffff81d0d928: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff818d4150-ffffffff818d42f8: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3074
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff81ed683d-ffffffff81ed68ee: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81a248e0-ffffffff81a24ae8: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3076
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff8209c548-ffffffff8209c5d4: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81ba6960-ffffffff81ba6b8c: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3269
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff8211d481-ffffffff8211d504: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81bfd540-ffffffff81bfd764: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3266
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover_pmp
```
**Symbols:**

```
ffffffff821fb4b9-ffffffff821fb53c: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81c53300-ffffffff81c5352f: sata_down_spd_limit (STB_GLOBAL)
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
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff8000109998c0)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffff8000109998c0-ffff800010999a30: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a69898)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c0a69898-c0a69a0c: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5c990)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
c000000000a5c990-c000000000a5cb68: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fa238)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffe0005fa238-ffffffe0005fa42a: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81754efe)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff8175a0aa-ffffffff8175a10e: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81754ec0-ffffffff81754f9b: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81734d9e)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81739f4a-ffffffff81739fae: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81734d60-ffffffff81734e3b: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81784c0e)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff81789e1a-ffffffff81789e7e: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff81784bd0-ffffffff81784cab: sata_down_spd_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sata_down_spd_limit(struct ata_link *link, u32 spd_limit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8179e9fe)
Location: drivers/ata/libata-core.c:3038
Inline: True
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_schedule_probe
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_reset
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-pmp.c:sata_pmp_eh_recover
```
**Symbols:**

```
ffffffff817a3c6a-ffffffff817a3cce: sata_down_spd_limit.cold (STB_LOCAL)
ffffffff8179e9c0-ffffffff8179ea9b: sata_down_spd_limit (STB_GLOBAL)
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
