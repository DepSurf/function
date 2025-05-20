# Function: <code>acpi_hw_low_set_gpe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8149a632)
Location: drivers/acpi/acpica/hwgpe.c:98
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8149a632-ffffffff8149a6f7: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff814e953d)
Location: drivers/acpi/acpica/hwgpe.c:98
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff814e953d-ffffffff814e9602: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8150bd96)
Location: drivers/acpi/acpica/hwgpe.c:98
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8150bd96-ffffffff8150be76: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8151c3cb)
Location: drivers/acpi/acpica/hwgpe.c:98
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8151c3cb-ffffffff8151c4ab: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8156c7f0)
Location: drivers/acpi/acpica/hwgpe.c:98
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8156c7f0-ffffffff8156c8da: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815a3407)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff815a3407-ffffffff815a34f4: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815bc0d2)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff815bc0d2-ffffffff815bc1bf: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815edcb2)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff815edcb2-ffffffff815edda1: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8160f0d6)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8160f0d6-ffffffff8160f1c5: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816bb449)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff816bb449-ffffffff816bb538: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816d8f57)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff816d8f57-ffffffff816d9046: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816baeef)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff816baeef-ffffffff816bafda: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81731f56)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff81731f56-ffffffff81732041: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff81862d11)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff81862d11-ffffffff81862e0d: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (0)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_add_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff82092075-ffffffff8209209a: acpi_hw_low_set_gpe.cold (STB_LOCAL)
ffffffff819a04d0-ffffffff819a0621: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (0)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_add_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8211294a-ffffffff82112986: acpi_hw_low_set_gpe.cold (STB_LOCAL)
ffffffff819e71a0-ffffffff819e72f6: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (0)
Location: drivers/acpi/acpica/hwgpe.c:134
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_add_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff821f069e-ffffffff821f06da: acpi_hw_low_set_gpe.cold (STB_LOCAL)
ffffffff81a31ef0-ffffffff81a32046: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815f07ac)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff815f07ac-ffffffff815f0896: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff815dbd7e)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff815dbd7e-ffffffff815dbe68: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff816033b6)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff816033b6-ffffffff816034a5: acpi_hw_low_set_gpe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_hw_low_set_gpe(struct acpi_gpe_event_info *gpe_event_info, u32 action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwgpe.c (ffffffff8161d266)
Location: drivers/acpi/acpica/hwgpe.c:64
Inline: False
Direct callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_gpe_dispatch
  - drivers/acpi/acpica/evgpe.c:acpi_ev_finish_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_remove_gpe_reference
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_mask_gpe
  - drivers/acpi/acpica/evgpe.c:acpi_ev_enable_gpe
  - drivers/acpi/acpica/evgpeinit.c:acpi_ev_match_gpe_method
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
  - drivers/acpi/acpica/evxfgpe.c:acpi_set_gpe
```
**Symbols:**

```
ffffffff8161d266-ffffffff8161d355: acpi_hw_low_set_gpe (STB_GLOBAL)
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
