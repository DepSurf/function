# Function: <code>acpi_notifier_call_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff81489631)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81489631-ffffffff814896e0: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff814d8427)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff814d8427-ffffffff814d84d6: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff814fab0f)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff814fab0f-ffffffff814fabbe: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff8150a000)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff8150a000-ffffffff8150a0ed: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff8154c500)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff8154c500-ffffffff8154c5ed: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff81582b70)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81582b70-ffffffff81582d2c: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff8159aca0)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff8159aca0-ffffffff8159ae5c: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff815cc684-ffffffff815cc690: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff815cc3f0-ffffffff815cc4c1: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff815ed904-ffffffff815ed910: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff815ed670-ffffffff815ed741: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81699484-ffffffff81699490: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff81699200-ffffffff816992c9: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:25
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81c023ef-ffffffff81c02407: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff816b6190-ffffffff816b6388: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:25
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81bf3be8-ffffffff81bf3c00: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff81698240-ffffffff81698440: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81cf0913-ffffffff81cf092b: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff8170dfc0-ffffffff8170e1c0: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81eb877a-ffffffff81eb8792: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff8183c950-ffffffff8183cb6f: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff81972360)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81972360-ffffffff8197258b: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff819b8a30)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff819b8a30-ffffffff819b8c5b: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffffffff81a03060)
Location: drivers/acpi/event.c:27
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff81a03060-ffffffff81a0328b: acpi_notifier_call_chain (STB_GLOBAL)
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
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/event.c (ffff800010778b08)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffff800010778b08-ffff800010778be8: acpi_notifier_call_chain (STB_GLOBAL)
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
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
```
**Symbols:**

```
ffffffff815dca54-ffffffff815dca60: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff815dc7c0-ffffffff815dc891: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
```
**Symbols:**

```
ffffffff815c8094-ffffffff815c80a0: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff815c7e00-ffffffff815c7ed1: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff815e1be4-ffffffff815e1bf0: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff815e1950-ffffffff815e1a21: acpi_notifier_call_chain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_notifier_call_chain(struct acpi_device *dev, u32 type, u32 data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/event.c (0)
Location: drivers/acpi/event.c:28
Inline: False
Direct callers:
  - drivers/acpi/ac.c:acpi_ac_notify
  - drivers/acpi/battery.c:acpi_battery_notify
```
**Symbols:**

```
ffffffff815fbaa4-ffffffff815fbab0: acpi_notifier_call_chain.cold (STB_LOCAL)
ffffffff815fb810-ffffffff815fb8e1: acpi_notifier_call_chain (STB_GLOBAL)
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
