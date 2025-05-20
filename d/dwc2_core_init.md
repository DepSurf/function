# Function: <code>dwc2_core_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool select_phy, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/core.c (ffffffff81622220)
Location: drivers/usb/dwc2/core.c:772
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
```
**Symbols:**

```
ffffffff81622220-ffffffff816228aa: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81685c40)
Location: drivers/usb/dwc2/hcd.c:2177
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81685c40-ffffffff8168627e: dwc2_core_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b3e90)
Location: drivers/usb/dwc2/hcd.c:2207
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff816b3e90-ffffffff816b44b1: dwc2_core_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c8250)
Location: drivers/usb/dwc2/hcd.c:2224
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff816c8250-ffffffff816c8844: dwc2_core_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81734720)
Location: drivers/usb/dwc2/hcd.c:2230
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81734720-ffffffff81734d43: dwc2_core_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81776550)
Location: drivers/usb/dwc2/hcd.c:2275
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81776550-ffffffff81776a89: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8179bfc0)
Location: drivers/usb/dwc2/hcd.c:2265
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff8179bfc0-ffffffff8179c6da: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff817deb01-ffffffff817deb36: dwc2_core_init.cold (STB_LOCAL)
ffffffff817db080-ffffffff817db39f: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff8180fa2c-ffffffff8180fa61: dwc2_core_init.cold (STB_LOCAL)
ffffffff8180bfa0-ffffffff8180c2bf: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff818e0731-ffffffff818e074c: dwc2_core_init.cold (STB_LOCAL)
ffffffff818dcf00-ffffffff818dd081: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2076
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81c1f7a8-ffffffff81c1f7c3: dwc2_core_init.cold (STB_LOCAL)
ffffffff818e6d50-ffffffff818e6ed1: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2074
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/core_intr.c:dwc_handle_gpwrdn_disc_det
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81c1153a-ffffffff81c1156f: dwc2_core_init.cold (STB_LOCAL)
ffffffff818c8ce0-ffffffff818c9014: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2074
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81d1b420-ffffffff81d1b57b: dwc2_core_init.cold (STB_LOCAL)
ffffffff81961840-ffffffff81961c0c: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2070
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff81ee66f8-ffffffff81ee68bf: dwc2_core_init.cold (STB_LOCAL)
ffffffff81abbc70-ffffffff81abc05f: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2041
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff820a1f5b-ffffffff820a20ed: dwc2_core_init.cold (STB_LOCAL)
ffffffff81c45230-ffffffff81c4565b: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2041
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff8212352e-ffffffff821236b3: dwc2_core_init.cold (STB_LOCAL)
ffffffff81cac820-ffffffff81cacc39: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2041
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_resume
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff82204d05-ffffffff82204e8a: dwc2_core_init.cold (STB_LOCAL)
ffffffff81d614d0-ffffffff81d618e9: dwc2_core_init (STB_GLOBAL)
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
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a44658)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffff800010a44658-ffff800010a44a1c: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b16e38)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
c0b16e38-c0b17218: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b075a0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
c000000000b075a0-c000000000b07c3c: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe000660d5a)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffe000660d5a-ffffffe00066127a: dwc2_core_init (STB_GLOBAL)
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
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff817c7e0c-ffffffff817c7e41: dwc2_core_init.cold (STB_LOCAL)
ffffffff817c4380-ffffffff817c469f: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff818048ac-ffffffff818048e1: dwc2_core_init.cold (STB_LOCAL)
ffffffff81800e20-ffffffff8180113f: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_core_init(struct dwc2_hsotg *hsotg, bool initial_setup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2075
Inline: False
Direct callers:
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/core_intr.c:dwc2_handle_gpwrdn_intr
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
  - drivers/usb/dwc2/hcd.c:dwc2_conn_id_status_change
```
**Symbols:**

```
ffffffff8181e9bc-ffffffff8181e9f1: dwc2_core_init.cold (STB_LOCAL)
ffffffff8181af30-ffffffff8181b24f: dwc2_core_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool initial_setup</code>
</li>
<li>
<b>Param removed. </b>
<code>bool select_phy</code>
</li>
<li>
<b>Param removed. </b>
<code>int irq</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
