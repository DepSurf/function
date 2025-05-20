# Function: <code>acpi_power_off_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814888df)
Location: drivers/acpi/power.c:279
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_on_list
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_transition
```
**Symbols:**

```
ffffffff814888df-ffffffff8148892f: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814d76d1)
Location: drivers/acpi/power.c:279
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814d76d1-ffffffff814d7721: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff814f9d6c)
Location: drivers/acpi/power.c:279
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff814f9d6c-ffffffff814f9dbc: acpi_power_off_unlocked (STB_LOCAL)
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
In drivers/acpi/power.c (ffffffff8150958d)
Location: drivers/acpi/power.c:280
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
```
**Symbols:**

```
ffffffff81508f80-ffffffff81508fb8: acpi_power_off_unlocked.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154b4d0)
Location: drivers/acpi/power.c:280
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8154b4d0-ffffffff8154b5a8: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81581b00)
Location: drivers/acpi/power.c:280
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81581b00-ffffffff81581bda: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81599bc0)
Location: drivers/acpi/power.c:302
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81599bc0-ffffffff81599c9a: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815cb0d0)
Location: drivers/acpi/power.c:423
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815cb0d0-ffffffff815cb1aa: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815ec350)
Location: drivers/acpi/power.c:423
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815ec350-ffffffff815ec42a: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697fc0)
Location: drivers/acpi/power.c:421
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81697fc0-ffffffff8169808f: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b50f0)
Location: drivers/acpi/power.c:421
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff816b50f0-ffffffff816b51bf: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697110)
Location: drivers/acpi/power.c:416
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81697110-ffffffff816971a0: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170cca0)
Location: drivers/acpi/power.c:438
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8170cca0-ffffffff8170cd24: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b460)
Location: drivers/acpi/power.c:438
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff8183b460-ffffffff8183b4ec: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81970bc0)
Location: drivers/acpi/power.c:438
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81970bc0-ffffffff81970c4c: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b7240)
Location: drivers/acpi/power.c:439
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff819b7240-ffffffff819b72d2: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a017f0)
Location: drivers/acpi/power.c:439
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81a017f0-ffffffff81a01882: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffff8000107782e8)
Location: drivers/acpi/power.c:423
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
```
**Symbols:**

```
ffff8000107779e8-ffff800010777a40: acpi_power_off_unlocked.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff815dbd9d)
Location: drivers/acpi/power.c:423
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
```
**Symbols:**

```
ffffffff815db600-ffffffff815db638: acpi_power_off_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/power.c (ffffffff815c73dd)
Location: drivers/acpi/power.c:423
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
Direct callers:
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_off
```
**Symbols:**

```
ffffffff815c6c40-ffffffff815c6c78: acpi_power_off_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e0630)
Location: drivers/acpi/power.c:423
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815e0630-ffffffff815e070a: acpi_power_off_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_power_off_unlocked(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815fa4f0)
Location: drivers/acpi/power.c:423
Inline: True
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_disable_wakeup_device_power
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815fa4f0-ffffffff815fa5ca: acpi_power_off_unlocked (STB_LOCAL)
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
