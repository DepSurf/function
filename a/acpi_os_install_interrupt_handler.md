# Function: <code>acpi_os_install_interrupt_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479f37)
Location: drivers/acpi/osl.c:829
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81479f37-ffffffff8147a025: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c84ee)
Location: drivers/acpi/osl.c:551
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff814c84ee-ffffffff814c85dc: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea432)
Location: drivers/acpi/osl.c:546
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff814ea432-ffffffff814ea520: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f61e0)
Location: drivers/acpi/osl.c:545
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff814f61e0-ffffffff814f62d9: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536940)
Location: drivers/acpi/osl.c:545
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81536940-ffffffff81536a39: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:550
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff8156d7ca-ffffffff8156d803: acpi_os_install_interrupt_handler.cold.19 (STB_LOCAL)
ffffffff8156c560-ffffffff8156c628: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:550
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff8158538a-ffffffff815853c3: acpi_os_install_interrupt_handler.cold.20 (STB_LOCAL)
ffffffff81584190-ffffffff81584258: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:536
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff815b5ff4-ffffffff815b602e: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff815b4d90-ffffffff815b4e59: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff815d7224-ffffffff815d725e: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff815d5fc0-ffffffff815d6089: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81680fec-ffffffff81681026: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff8167fcc0-ffffffff8167fd89: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:560
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81c00954-ffffffff81c0098e: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff8169e770-ffffffff8169e839: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:562
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81bf2449-ffffffff81bf2483: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff81681420-ffffffff816814e9: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:562
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81ceeced-ffffffff81ceed27: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff816f6510-ffffffff816f65d9: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:561
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff81eb6476-ffffffff81eb64ac: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff81823300-ffffffff818233e5: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819544c0)
Location: drivers/acpi/osl.c:561
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff819544c0-ffffffff819545db: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199a8d0)
Location: drivers/acpi/osl.c:561
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff8199a8d0-ffffffff8199a9eb: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e2d50)
Location: drivers/acpi/osl.c:557
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff819e2d50-ffffffff819e2e6b: acpi_os_install_interrupt_handler (STB_GLOBAL)
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
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763820)
Location: drivers/acpi/osl.c:556
Inline: False
```
**Symbols:**

```
ffff800010763820-ffff800010763938: acpi_os_install_interrupt_handler (STB_GLOBAL)
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
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff815ca86e-ffffffff815ca8a8: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff815c9d20-ffffffff815c9de9: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff815b38d1-ffffffff815b390b: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff815b2da0-ffffffff815b2e69: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff815cb504-ffffffff815cb53e: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff815ca2a0-ffffffff815ca369: acpi_os_install_interrupt_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_os_install_interrupt_handler(u32 gsi, acpi_osd_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:556
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
  - drivers/acpi/acpica/evsci.c:acpi_ev_install_sci_handler
```
**Symbols:**

```
ffffffff815e53a4-ffffffff815e53de: acpi_os_install_interrupt_handler.cold (STB_LOCAL)
ffffffff815e4100-ffffffff815e41c9: acpi_os_install_interrupt_handler (STB_GLOBAL)
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
