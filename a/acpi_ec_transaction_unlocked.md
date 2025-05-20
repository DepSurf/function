# Function: <code>acpi_ec_transaction_unlocked</code>

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
In drivers/acpi/ec.c (ffffffff81483bcc)
Location: drivers/acpi/ec.c:667
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
In drivers/acpi/ec.c (ffffffff814d2665)
Location: drivers/acpi/ec.c:674
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
In drivers/acpi/ec.c (ffffffff814f4b41)
Location: drivers/acpi/ec.c:788
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
In drivers/acpi/ec.c (ffffffff81502ec5)
Location: drivers/acpi/ec.c:777
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
In drivers/acpi/ec.c (ffffffff81545325)
Location: drivers/acpi/ec.c:779
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
In drivers/acpi/ec.c (ffffffff8157b924)
Location: drivers/acpi/ec.c:779
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
In drivers/acpi/ec.c (ffffffff81592fe4)
Location: drivers/acpi/ec.c:779
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
In drivers/acpi/ec.c (ffffffff815c3fa1)
Location: drivers/acpi/ec.c:793
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
In drivers/acpi/ec.c (ffffffff815e51e1)
Location: drivers/acpi/ec.c:785
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
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690750)
Location: drivers/acpi/ec.c:781
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81690750-ffffffff8169099f: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ae470)
Location: drivers/acpi/ec.c:768
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff816ae470-ffffffff816ae6c1: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816909d0)
Location: drivers/acpi/ec.c:769
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff816909d0-ffffffff81690ce8: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81706430)
Location: drivers/acpi/ec.c:771
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81706430-ffffffff81706745: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff818345a0)
Location: drivers/acpi/ec.c:794
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff818345a0-ffffffff818348de: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819681e0)
Location: drivers/acpi/ec.c:795
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff819681e0-ffffffff8196846d: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819ae7c0)
Location: drivers/acpi/ec.c:780
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff819ae7c0-ffffffff819aea4d: acpi_ec_transaction_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_ec_transaction_unlocked(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f8c40)
Location: drivers/acpi/ec.c:780
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff819f8c40-ffffffff819f8ecd: acpi_ec_transaction_unlocked (STB_LOCAL)
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
In drivers/acpi/ec.c (ffff800010771c9c)
Location: drivers/acpi/ec.c:785
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
In drivers/acpi/ec.c (ffffffff815d70d1)
Location: drivers/acpi/ec.c:785
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
In drivers/acpi/ec.c (ffffffff815c0c91)
Location: drivers/acpi/ec.c:785
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
In drivers/acpi/ec.c (ffffffff815d94c1)
Location: drivers/acpi/ec.c:785
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
In drivers/acpi/ec.c (ffffffff815f3381)
Location: drivers/acpi/ec.c:785
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
