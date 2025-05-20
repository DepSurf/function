# Function: <code>acpi_power_on_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81488892)
Location: drivers/acpi/power.c:239
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_on_list
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_transition
```
**Symbols:**

```
ffffffff81488892-ffffffff814888df: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814d7684)
Location: drivers/acpi/power.c:239
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814d7684-ffffffff814d76d1: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814f9dbc)
Location: drivers/acpi/power.c:239
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814f9dbc-ffffffff814f9e09: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff8150941a)
Location: drivers/acpi/power.c:240
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
Direct callers:
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
```
**Symbols:**

```
ffffffff81508ee0-ffffffff81508f18: acpi_power_on_unlocked.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154b3b0)
Location: drivers/acpi/power.c:240
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8154b3b0-ffffffff8154b44c: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815819e0)
Location: drivers/acpi/power.c:240
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815819e0-ffffffff81581a7c: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81599aa0)
Location: drivers/acpi/power.c:262
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81599aa0-ffffffff81599b3c: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815cb1b0)
Location: drivers/acpi/power.c:383
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815cb1b0-ffffffff815cb241: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815ec430)
Location: drivers/acpi/power.c:383
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815ec430-ffffffff815ec4c1: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697e90)
Location: drivers/acpi/power.c:381
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81697e90-ffffffff81697f21: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b4fc0)
Location: drivers/acpi/power.c:381
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff816b4fc0-ffffffff816b5051: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697040)
Location: drivers/acpi/power.c:378
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81697040-ffffffff816970a5: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170ce30)
Location: drivers/acpi/power.c:395
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8170ce30-ffffffff8170ce8f: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b600)
Location: drivers/acpi/power.c:395
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8183b600-ffffffff8183b66d: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81970d80)
Location: drivers/acpi/power.c:395
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81970d80-ffffffff81970ded: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b7410)
Location: drivers/acpi/power.c:396
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff819b7410-ffffffff819b747d: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a019c0)
Location: drivers/acpi/power.c:396
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81a019c0-ffffffff81a01a2d: acpi_power_on_unlocked (STB_LOCAL)
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
In drivers/acpi/power.c (ffff800010778178)
Location: drivers/acpi/power.c:383
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
  - drivers/acpi/power.c:acpi_power_on
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
In drivers/acpi/power.c (ffffffff815dbc63)
Location: drivers/acpi/power.c:383
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
  - drivers/acpi/power.c:acpi_power_on
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
In drivers/acpi/power.c (ffffffff815c72a3)
Location: drivers/acpi/power.c:383
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on
  - drivers/acpi/power.c:acpi_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e0710)
Location: drivers/acpi/power.c:383
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815e0710-ffffffff815e07a1: acpi_power_on_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_on_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815fa5d0)
Location: drivers/acpi/power.c:383
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_enable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815fa5d0-ffffffff815fa661: acpi_power_on_unlocked (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
