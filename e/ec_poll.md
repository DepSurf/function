# Function: <code>ec_poll</code>

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
In drivers/acpi/ec.c (ffffffff81483c47)
Location: drivers/acpi/ec.c:644
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff814d2704)
Location: drivers/acpi/ec.c:651
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff814f4bd3)
Location: drivers/acpi/ec.c:765
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff81502f44)
Location: drivers/acpi/ec.c:754
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815453a4)
Location: drivers/acpi/ec.c:756
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff8157b9f4)
Location: drivers/acpi/ec.c:756
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815930b4)
Location: drivers/acpi/ec.c:756
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815c402b)
Location: drivers/acpi/ec.c:770
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815e526b)
Location: drivers/acpi/ec.c:762
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ec_poll(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690370)
Location: drivers/acpi/ec.c:758
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
**Symbols:**

```
ffffffff81690370-ffffffff8169045f: ec_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ec_poll(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ae070)
Location: drivers/acpi/ec.c:745
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
```
**Symbols:**

```
ffffffff816ae070-ffffffff816ae161: ec_poll (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81690a97)
Location: drivers/acpi/ec.c:746
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff817064f7)
Location: drivers/acpi/ec.c:748
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff81834671)
Location: drivers/acpi/ec.c:771
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff81968299)
Location: drivers/acpi/ec.c:772
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff819ae879)
Location: drivers/acpi/ec.c:757
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff819f8cf9)
Location: drivers/acpi/ec.c:757
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffff800010771d44)
Location: drivers/acpi/ec.c:762
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815d715b)
Location: drivers/acpi/ec.c:762
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815c0d1b)
Location: drivers/acpi/ec.c:762
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815d954b)
Location: drivers/acpi/ec.c:762
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
In drivers/acpi/ec.c (ffffffff815f340b)
Location: drivers/acpi/ec.c:762
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
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
