# Function: <code>__acpi_power_off</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814888fb)
Location: drivers/acpi/power.c:265
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814d83d4)
Location: drivers/acpi/power.c:265
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814faabc)
Location: drivers/acpi/power.c:265
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_resume_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81509fbd)
Location: drivers/acpi/power.c:266
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154b450)
Location: drivers/acpi/power.c:266
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff8154b450-ffffffff8154b4cd: __acpi_power_off.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff81581a80)
Location: drivers/acpi/power.c:266
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff81581a80-ffffffff81581afd: __acpi_power_off.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff81599b40)
Location: drivers/acpi/power.c:288
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff81599b40-ffffffff81599bbd: __acpi_power_off.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff815cb050)
Location: drivers/acpi/power.c:409
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff815cb050-ffffffff815cb0cd: __acpi_power_off.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff815ec2d0)
Location: drivers/acpi/power.c:409
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff815ec2d0-ffffffff815ec34d: __acpi_power_off.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697f30)
Location: drivers/acpi/power.c:407
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff81697f30-ffffffff81697fb5: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b5060)
Location: drivers/acpi/power.c:407
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff816b5060-ffffffff816b50e5: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816970b0)
Location: drivers/acpi/power.c:402
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff816970b0-ffffffff8169710b: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170cc30)
Location: drivers/acpi/power.c:420
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff8170cc30-ffffffff8170cc95: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b3f0)
Location: drivers/acpi/power.c:420
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff8183b3f0-ffffffff8183b45c: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81970b40)
Location: drivers/acpi/power.c:420
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff81970b40-ffffffff81970bac: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b71c0)
Location: drivers/acpi/power.c:421
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff819b71c0-ffffffff819b722c: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __acpi_power_off(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a01770)
Location: drivers/acpi/power.c:421
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
  - drivers/acpi/power.c:acpi_power_wakeup_list_init
  - drivers/acpi/power.c:acpi_power_off_unlocked
```
**Symbols:**

```
ffffffff81a01770-ffffffff81a017dc: __acpi_power_off (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff800010777a00)
Location: drivers/acpi/power.c:409
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815dc79f)
Location: drivers/acpi/power.c:409
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815c7ddf)
Location: drivers/acpi/power.c:409
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e05b0)
Location: drivers/acpi/power.c:409
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff815e05b0-ffffffff815e062d: __acpi_power_off.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff815fa470)
Location: drivers/acpi/power.c:409
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_turn_off_unused_power_resources
```
**Symbols:**

```
ffffffff815fa470-ffffffff815fa4ed: __acpi_power_off.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
