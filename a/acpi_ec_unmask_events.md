# Function: <code>acpi_ec_unmask_events</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690933)
Location: drivers/acpi/ec.c:430
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff81690500-ffffffff816905c0: acpi_ec_unmask_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ae653)
Location: drivers/acpi/ec.c:413
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff816ae210-ffffffff816ae2d2: acpi_ec_unmask_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690c7a)
Location: drivers/acpi/ec.c:414
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff81690770-ffffffff81690832: acpi_ec_unmask_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff817066da)
Location: drivers/acpi/ec.c:415
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_complete_query
```
**Symbols:**

```
ffffffff817061f0-ffffffff817062a8: acpi_ec_unmask_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81834871)
Location: drivers/acpi/ec.c:411
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_close_event
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_close_event
```
**Symbols:**

```
ffffffff81834330-ffffffff818343f5: acpi_ec_unmask_events.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ec_unmask_events(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81967fd0)
Location: drivers/acpi/ec.c:412
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_close_event
```
**Symbols:**

```
ffffffff81967fd0-ffffffff8196809b: acpi_ec_unmask_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ec_unmask_events(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819ae5b0)
Location: drivers/acpi/ec.c:412
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_close_event
```
**Symbols:**

```
ffffffff819ae5b0-ffffffff819ae67b: acpi_ec_unmask_events (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ec_unmask_events(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f8a30)
Location: drivers/acpi/ec.c:412
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_close_event
```
**Symbols:**

```
ffffffff819f8a30-ffffffff819f8afb: acpi_ec_unmask_events (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
