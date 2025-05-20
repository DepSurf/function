# Function: <code>acpi_processor_get_platform_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814ad780)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
```
```
In drivers/acpi/processor_perflib.c (ffffffff814aea7d)
Location: drivers/acpi/processor_perflib.c:114
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff814ad780-ffffffff814ad824: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff814aea7d-ffffffff814aeb58: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814fd0b3)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff814fe446)
Location: drivers/acpi/processor_perflib.c:114
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff814fd0b3-ffffffff814fd157: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff814fe446-ffffffff814fe521: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8151fd4f)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff8152113a)
Location: drivers/acpi/processor_perflib.c:114
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff8151fd4f-ffffffff8151fdf3: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff8152113a-ffffffff81521215: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81531370)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff815329d0)
Location: drivers/acpi/processor_perflib.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81531370-ffffffff81531418: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff815329d0-ffffffff81532aa4: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815923d0)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff81593f80)
Location: drivers/acpi/processor_perflib.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff815923d0-ffffffff81592478: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81593f80-ffffffff81594054: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815c9820)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff815cb400)
Location: drivers/acpi/processor_perflib.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff815c9820-ffffffff815c98c8: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff815cb400-ffffffff815cb4d4: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815e2e00)
Location: drivers/acpi/processor_throttling.c:288
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff815e49e0)
Location: drivers/acpi/processor_perflib.c:112
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff815e2e00-ffffffff815e2ea8: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff815e49e0-ffffffff815e4ab4: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81614990)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff816165c0)
Location: drivers/acpi/processor_perflib.c:99
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81614990-ffffffff81614a38: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff816165c0-ffffffff81616694: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81635e80)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81635e80-ffffffff81635f28: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81637b90-ffffffff81637cb9: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81638cd3-ffffffff81638ceb: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e2a80)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff816e2a80-ffffffff816e2b27: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff816e4900-ffffffff816e4a29: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff816e5a63-ffffffff816e5a7b: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff817006e0)
Location: drivers/acpi/processor_throttling.c:274
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:54
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff817006e0-ffffffff81700787: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81702390-ffffffff817024b9: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81c02cd1-ffffffff81c02ce9: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e2110)
Location: drivers/acpi/processor_throttling.c:270
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:52
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff816e2110-ffffffff816e21ae: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff816e3c80-ffffffff816e3da0: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81bf4718-ffffffff81bf4730: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8175a8e0)
Location: drivers/acpi/processor_throttling.c:266
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:52
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff8175a8e0-ffffffff8175a97e: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff8175c900-ffffffff8175ca1d: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81cf1835-ffffffff81cf184d: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8188e030)
Location: drivers/acpi/processor_throttling.c:266
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:52
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff8188e030-ffffffff8188e0d4: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff8188ff30-ffffffff8189005b: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81eb97e5-ffffffff81eb97fb: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff819d5690)
Location: drivers/acpi/processor_throttling.c:264
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff819d7460)
Location: drivers/acpi/processor_perflib.c:52
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff819d5690-ffffffff819d5734: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff819d7460-ffffffff819d759d: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a1cfe0)
Location: drivers/acpi/processor_throttling.c:264
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a1ee20)
Location: drivers/acpi/processor_perflib.c:52
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81a1cfe0-ffffffff81a1d084: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81a1ee20-ffffffff81a1ef96: acpi_processor_get_platform_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a682f0)
Location: drivers/acpi/processor_throttling.c:264
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (ffffffff81a6a140)
Location: drivers/acpi/processor_perflib.c:52
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81a682f0-ffffffff81a68394: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81a6a140-ffffffff81a6a2b6: acpi_processor_get_platform_limit (STB_LOCAL)
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
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffff8000107a3120)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffff8000107a3120-ffff8000107a3274: acpi_processor_get_platform_limit (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816055f0)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff816055f0-ffffffff81605698: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81606dc0-ffffffff81606ee9: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81607cf8-ffffffff81607d10: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815f0690)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff815f0690-ffffffff815f0738: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff815f1e90-ffffffff815f1fb9: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff815f2df8-ffffffff815f2e10: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8162a160)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff8162a160-ffffffff8162a208: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff8162be70-ffffffff8162bf99: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff8162cfb3-ffffffff8162cfcb: acpi_processor_get_platform_limit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
int acpi_processor_get_platform_limit(struct acpi_processor *pr);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81644000)
Location: drivers/acpi/processor_throttling.c:275
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info
  - drivers/acpi/processor_throttling.c:acpi_processor_tstate_has_changed
```
```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:55
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_get_performance_info
  - drivers/acpi/processor_perflib.c:acpi_processor_ppc_has_changed
```
**Symbols:**

```
ffffffff81644000-ffffffff816440a8: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81645d10-ffffffff81645e39: acpi_processor_get_platform_limit (STB_LOCAL)
ffffffff81646e53-ffffffff81646e6b: acpi_processor_get_platform_limit.cold (STB_LOCAL)
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
