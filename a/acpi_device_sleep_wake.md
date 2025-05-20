# Function: <code>acpi_device_sleep_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81488b74)
Location: drivers/acpi/power.c:505
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
```
**Symbols:**

```
ffffffff81488b74-ffffffff81488c4a: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814d796b)
Location: drivers/acpi/power.c:505
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff814d796b-ffffffff814d7a41: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814fa053)
Location: drivers/acpi/power.c:505
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff814fa053-ffffffff814fa129: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81509280)
Location: drivers/acpi/power.c:506
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81509280-ffffffff8150936e: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154b850)
Location: drivers/acpi/power.c:506
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff8154b850-ffffffff8154b93e: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:506
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81582a16-ffffffff81582a35: acpi_device_sleep_wake.cold.11 (STB_LOCAL)
ffffffff81581e80-ffffffff81581f56: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:528
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff8159ab46-ffffffff8159ab65: acpi_device_sleep_wake.cold.12 (STB_LOCAL)
ffffffff81599f40-ffffffff8159a016: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff815cc22f-ffffffff815cc269: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff815cb690-ffffffff815cb74e: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff815ed4af-ffffffff815ed4e9: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff815ec910-ffffffff815ec9ce: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:647
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff8169904f-ffffffff81699089: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff816985e0-ffffffff8169869e: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:647
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_get_wakeup_device_flags
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81c0223f-ffffffff81c02279: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff816b5710-ffffffff816b57ce: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816975e0)
Location: drivers/acpi/power.c:638
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff816975e0-ffffffff816976de: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170d3e0)
Location: drivers/acpi/power.c:660
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff8170d3e0-ffffffff8170d4de: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183bce0)
Location: drivers/acpi/power.c:660
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff8183bce0-ffffffff8183bdee: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81971510)
Location: drivers/acpi/power.c:660
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81971510-ffffffff8197161e: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b7b90)
Location: drivers/acpi/power.c:661
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff819b7b90-ffffffff819b7ca5: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a02160)
Location: drivers/acpi/power.c:661
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff81a02160-ffffffff81a02275: acpi_device_sleep_wake (STB_GLOBAL)
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
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff800010777fe8)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffff800010777fe8-ffff8000107780f4: acpi_device_sleep_wake (STB_GLOBAL)
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
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff815dc59f-ffffffff815dc5d9: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff815dbb00-ffffffff815dbbbe: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff815c7bdf-ffffffff815c7c19: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff815c7140-ffffffff815c71fe: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff815e178f-ffffffff815e17c9: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff815e0bf0-ffffffff815e0cae: acpi_device_sleep_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_device_sleep_wake(struct acpi_device *dev, int enable, int sleep_state, int dev_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (0)
Location: drivers/acpi/power.c:649
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
```
**Symbols:**

```
ffffffff815fb64f-ffffffff815fb689: acpi_device_sleep_wake.cold (STB_LOCAL)
ffffffff815faab0-ffffffff815fab6e: acpi_device_sleep_wake (STB_GLOBAL)
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
