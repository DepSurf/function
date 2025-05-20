# Function: <code>acpi_ec_submit_query</code>

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
In drivers/acpi/ec.c (ffffffff814837aa)
Location: drivers/acpi/ec.c:423
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff814d22ca)
Location: drivers/acpi/ec.c:430
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff814f477c)
Location: drivers/acpi/ec.c:461
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81502845)
Location: drivers/acpi/ec.c:465
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81544cb2)
Location: drivers/acpi/ec.c:464
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff8157acad)
Location: drivers/acpi/ec.c:464
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815929a7)
Location: drivers/acpi/ec.c:464
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815c384c)
Location: drivers/acpi/ec.c:454
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815e4a8c)
Location: drivers/acpi/ec.c:456
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ec_submit_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168f810)
Location: drivers/acpi/ec.c:462
Inline: False
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff8168f810-ffffffff8168f8ab: acpi_ec_submit_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ec_submit_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ad4e0)
Location: drivers/acpi/ec.c:445
Inline: False
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff816ad4e0-ffffffff816ad57b: acpi_ec_submit_query (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff816902c8)
Location: drivers/acpi/ec.c:446
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff81705d35)
Location: drivers/acpi/ec.c:447
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_ec_submit_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81834af0)
Location: drivers/acpi/ec.c:1172
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81834af0-ffffffff81834ceb: acpi_ec_submit_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_ec_submit_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819686b0)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff819686b0-ffffffff819688ab: acpi_ec_submit_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_ec_submit_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819aec90)
Location: drivers/acpi/ec.c:1166
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff819aec90-ffffffff819aee8b: acpi_ec_submit_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_ec_submit_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f9110)
Location: drivers/acpi/ec.c:1166
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff819f9110-ffffffff819f933a: acpi_ec_submit_query (STB_LOCAL)
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
In drivers/acpi/ec.c (ffff800010771848)
Location: drivers/acpi/ec.c:456
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815d697c)
Location: drivers/acpi/ec.c:456
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815c053c)
Location: drivers/acpi/ec.c:456
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815d8d6c)
Location: drivers/acpi/ec.c:456
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
In drivers/acpi/ec.c (ffffffff815f2c2c)
Location: drivers/acpi/ec.c:456
Inline: True
Inline callers:
  - drivers/acpi/ec.c:advance_transaction
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
