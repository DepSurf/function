# Function: <code>acpi_battery_get_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff814b1de3)
Location: drivers/acpi/battery.c:486
Inline: False
Direct callers:
  - drivers/acpi/battery.c:acpi_battery_get_property
  - drivers/acpi/battery.c:battery_notify
```
**Symbols:**

```
ffffffff814b1de3-ffffffff814b1fa0: acpi_battery_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815016fd)
Location: drivers/acpi/battery.c:486
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff815016fd-ffffffff815018ba: acpi_battery_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815241bb)
Location: drivers/acpi/battery.c:510
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff815241bb-ffffffff81524378: acpi_battery_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff815368a0)
Location: drivers/acpi/battery.c:516
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff815368a0-ffffffff81536a9f: acpi_battery_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffffffff81598030)
Location: drivers/acpi/battery.c:520
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81598030-ffffffff8159822f: acpi_battery_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:543
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff815cf450-ffffffff815cf664: acpi_battery_get_state (STB_LOCAL)
ffffffff815d07a1-ffffffff815d07b9: acpi_battery_get_state.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:557
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff815e8a30-ffffffff815e8c44: acpi_battery_get_state (STB_LOCAL)
ffffffff815e9dd5-ffffffff815e9ded: acpi_battery_get_state.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:544
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff8161a750-ffffffff8161a96e: acpi_battery_get_state (STB_LOCAL)
ffffffff8161bad2-ffffffff8161baea: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:567
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff8163c180-ffffffff8163c39e: acpi_battery_get_state (STB_LOCAL)
ffffffff8163d575-ffffffff8163d58d: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:567
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff816e9680-ffffffff816e989e: acpi_battery_get_state (STB_LOCAL)
ffffffff816ea7a5-ffffffff816ea7bd: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:556
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81706e60-ffffffff81707081: acpi_battery_get_state (STB_LOCAL)
ffffffff81c03206-ffffffff81c0321e: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:556
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff816e8460-ffffffff816e868d: acpi_battery_get_state (STB_LOCAL)
ffffffff81bf4bff-ffffffff81bf4c17: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:559
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81761aa0-ffffffff81761cdc: acpi_battery_get_state (STB_LOCAL)
ffffffff81cf1e70-ffffffff81cf1e9d: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:554
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff818957c0-ffffffff818959fb: acpi_battery_get_state (STB_LOCAL)
ffffffff81eb9e35-ffffffff81eb9e62: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:554
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff819dd560-ffffffff819dd7b2: acpi_battery_get_state (STB_LOCAL)
ffffffff8209285e-ffffffff82092873: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:565
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81a25270-ffffffff81a254b9: acpi_battery_get_state (STB_LOCAL)
ffffffff821135e0-ffffffff821135f5: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:565
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff81a700b0-ffffffff81a702f9: acpi_battery_get_state (STB_LOCAL)
ffffffff821f0f53-ffffffff821f0f68: acpi_battery_get_state.cold (STB_LOCAL)
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
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/battery.c (ffff8000107a6f48)
Location: drivers/acpi/battery.c:567
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffff8000107a6f48-ffff8000107a7164: acpi_battery_get_state (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:567
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff8162ffc0-ffffffff816301de: acpi_battery_get_state (STB_LOCAL)
ffffffff816313b5-ffffffff816313cd: acpi_battery_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_battery_get_state(struct acpi_battery *battery);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/battery.c (0)
Location: drivers/acpi/battery.c:567
Inline: False
Direct callers:
  - drivers/acpi/battery.c:battery_notify
  - drivers/acpi/battery.c:acpi_battery_get_property
```
**Symbols:**

```
ffffffff8164a300-ffffffff8164a51e: acpi_battery_get_state (STB_LOCAL)
ffffffff8164b6f5-ffffffff8164b70d: acpi_battery_get_state.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
