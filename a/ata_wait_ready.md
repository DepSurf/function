# Function: <code>ata_wait_ready</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cecb0)
Location: drivers/ata/libata-core.c:3403
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff815cecb0-ffffffff815cee19: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816278b0)
Location: drivers/ata/libata-core.c:3578
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff816278b0-ffffffff816279f8: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81658510)
Location: drivers/ata/libata-core.c:3620
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81658510-ffffffff81658658: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166cd20)
Location: drivers/ata/libata-core.c:3697
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff8166cd20-ffffffff8166ce5b: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d6370)
Location: drivers/ata/libata-core.c:3706
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff816d6370-ffffffff816d64ad: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81711fc0)
Location: drivers/ata/libata-core.c:3702
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81711fc0-ffffffff817120f4: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81734460)
Location: drivers/ata/libata-core.c:3702
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81734460-ffffffff81734594: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81771d26-ffffffff81771d5d: ata_wait_ready.cold (STB_LOCAL)
ffffffff8176fe20-ffffffff8176ff3d: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81795cde-ffffffff81795d02: ata_wait_ready.cold (STB_LOCAL)
ffffffff81793e70-ffffffff81793f93: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3397
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff8185950d-ffffffff81859531: ata_wait_ready.cold (STB_LOCAL)
ffffffff81854aa0-ffffffff81854c19: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3397
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81c17520-ffffffff81c17544: ata_wait_ready.cold (STB_LOCAL)
ffffffff81864d70-ffffffff81864ee9: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3397
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81c0914d-ffffffff81c09171: ata_wait_ready.cold (STB_LOCAL)
ffffffff81847810-ffffffff81847989: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3448
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81d0d9c3-ffffffff81d0d9e7: ata_wait_ready.cold (STB_LOCAL)
ffffffff818d4730-ffffffff818d4939: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3479
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81ed69a1-ffffffff81ed69e4: ata_wait_ready.cold (STB_LOCAL)
ffffffff81a24f30-ffffffff81a2515c: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba7040)
Location: drivers/ata/libata-core.c:3481
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81ba7040-ffffffff81ba72b0: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81bfdc10)
Location: drivers/ata/libata-core.c:3674
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81bfdc10-ffffffff81bfde80: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c539c0)
Location: drivers/ata/libata-core.c:3671
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sata.c:sata_link_hardreset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff81c539c0-ffffffff81c53c30: ata_wait_ready (STB_GLOBAL)
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
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099e3a8)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffff80001099e3a8-ffff80001099e548: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6eac0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
c0a6eac0-c0a6ec68: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a62650)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
c000000000a62650-c000000000a6287c: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fe4aa)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffe0005fe4aa-ffffffe0005fe5d6: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff8175adf5-ffffffff8175ae19: ata_wait_ready.cold (STB_LOCAL)
ffffffff81758f80-ffffffff817590a3: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff8173ac95-ffffffff8173acb9: ata_wait_ready.cold (STB_LOCAL)
ffffffff81738e20-ffffffff81738f43: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff8178ab5e-ffffffff8178ab82: ata_wait_ready.cold (STB_LOCAL)
ffffffff81788cf0-ffffffff81788e13: ata_wait_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_wait_ready(struct ata_link *link, long unsigned int deadline, int (*check_ready)(struct ata_link *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3686
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:sata_link_hardreset
  - drivers/ata/libata-core.c:ata_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
  - drivers/ata/libata-sff.c:ata_sff_wait_after_reset
```
**Symbols:**

```
ffffffff817a49ae-ffffffff817a49d2: ata_wait_ready.cold (STB_LOCAL)
ffffffff817a2b40-ffffffff817a2c63: ata_wait_ready (STB_GLOBAL)
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
