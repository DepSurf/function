# Function: <code>acpi_ec_started</code>

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
In drivers/acpi/ec.c (ffffffff81483be4)
Location: drivers/acpi/ec.c:231
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_stop
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
In drivers/acpi/ec.c (ffffffff814d2fe7)
Location: drivers/acpi/ec.c:236
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_ec_started(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f38c1)
Location: drivers/acpi/ec.c:243
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff814f38c1-ffffffff814f38e7: acpi_ec_started (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff815023fd)
Location: drivers/acpi/ec.c:247
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff8154486d)
Location: drivers/acpi/ec.c:246
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff8157a8bd)
Location: drivers/acpi/ec.c:246
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff8159253d)
Location: drivers/acpi/ec.c:246
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815c344d)
Location: drivers/acpi/ec.c:236
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815e468d)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff8168fc1c)
Location: drivers/acpi/ec.c:236
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_query
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
In drivers/acpi/ec.c (ffffffff816ad8ec)
Location: drivers/acpi/ec.c:236
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_query
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
In drivers/acpi/ec.c (ffffffff8168fe5c)
Location: drivers/acpi/ec.c:237
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff817057fc)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff818334fd)
Location: drivers/acpi/ec.c:234
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_ec_started(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819665d0)
Location: drivers/acpi/ec.c:235
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff819665d0-ffffffff819665fc: acpi_ec_started (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_ec_started(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819acb60)
Location: drivers/acpi/ec.c:235
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff819acb60-ffffffff819acb8c: acpi_ec_started (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_ec_started(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f6f80)
Location: drivers/acpi/ec.c:235
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff819f6f80-ffffffff819f6fac: acpi_ec_started (STB_LOCAL)
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
In drivers/acpi/ec.c (ffff8000107711e8)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815d657d)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815c013d)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815d896d)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
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
In drivers/acpi/ec.c (ffffffff815f282d)
Location: drivers/acpi/ec.c:238
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_stop
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
</details>
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
