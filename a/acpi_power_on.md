# Function: <code>acpi_power_on</code>

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
In drivers/acpi/power.c (ffffffff81488951)
Location: drivers/acpi/power.c:255
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_on_list
  - drivers/acpi/power.c:acpi_power_transition
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
In drivers/acpi/power.c (ffffffff814d7e89)
Location: drivers/acpi/power.c:255
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
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
In drivers/acpi/power.c (ffffffff814fa571)
Location: drivers/acpi/power.c:255
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81508f20)
Location: drivers/acpi/power.c:256
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff81508f20-ffffffff81508f73: acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8154be53)
Location: drivers/acpi/power.c:256
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81582476)
Location: drivers/acpi/power.c:256
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8159a536)
Location: drivers/acpi/power.c:278
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815cbc8c)
Location: drivers/acpi/power.c:399
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815ecf0c)
Location: drivers/acpi/power.c:399
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81698b09)
Location: drivers/acpi/power.c:397
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b5c3c)
Location: drivers/acpi/power.c:397
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697c07)
Location: drivers/acpi/power.c:392
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8170d9b8)
Location: drivers/acpi/power.c:410
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff8183b841)
Location: drivers/acpi/power.c:410
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81971011)
Location: drivers/acpi/power.c:410
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff819b769d)
Location: drivers/acpi/power.c:411
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81a01c4d)
Location: drivers/acpi/power.c:411
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_on_list
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
int acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffff800010777ab8)
Location: drivers/acpi/power.c:399
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffff800010777ab8-ffff800010777b48: acpi_power_on (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815db6a0)
Location: drivers/acpi/power.c:399
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815db6a0-ffffffff815db700: acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_power_on(struct acpi_power_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815c6ce0)
Location: drivers/acpi/power.c:399
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
**Symbols:**

```
ffffffff815c6ce0-ffffffff815c6d40: acpi_power_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815e11ec)
Location: drivers/acpi/power.c:399
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff815fb0ac)
Location: drivers/acpi/power.c:399
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_transition
  - drivers/acpi/power.c:acpi_power_on_list
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
