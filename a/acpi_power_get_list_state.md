# Function: <code>acpi_power_get_list_state</code>

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
In drivers/acpi/power.c (ffffffff81488ed2)
Location: drivers/acpi/power.c:194
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff814d7cc3)
Location: drivers/acpi/power.c:194
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff814fa3ab)
Location: drivers/acpi/power.c:194
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff81509641)
Location: drivers/acpi/power.c:194
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff8154bbe5)
Location: drivers/acpi/power.c:194
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff81582215)
Location: drivers/acpi/power.c:194
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff8159a2d5)
Location: drivers/acpi/power.c:216
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff815cba05)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff815ecc85)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_power_get_list_state(struct list_head *list, int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff81697b90)
Location: drivers/acpi/power.c:207
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
```
**Symbols:**

```
ffffffff81697b90-ffffffff81697ca9: acpi_power_get_list_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_power_get_list_state(struct list_head *list, int *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/power.c (ffffffff816b4cc0)
Location: drivers/acpi/power.c:207
Inline: False
Direct callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
```
**Symbols:**

```
ffffffff816b4cc0-ffffffff816b4dd9: acpi_power_get_list_state (STB_LOCAL)
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
In drivers/acpi/power.c (ffffffff816979a5)
Location: drivers/acpi/power.c:206
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff8170d6f9)
Location: drivers/acpi/power.c:219
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff8183c0cc)
Location: drivers/acpi/power.c:219
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff8197195c)
Location: drivers/acpi/power.c:219
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff819b7fec)
Location: drivers/acpi/power.c:220
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff81a025bc)
Location: drivers/acpi/power.c:220
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffff8000107783e8)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff815dbe55)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff815c7495)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff815e0f65)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
In drivers/acpi/power.c (ffffffff815fae25)
Location: drivers/acpi/power.c:209
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_power_get_inferred_state
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
</ul>
