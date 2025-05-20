# Function: <code>acpi_ec_complete_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814830d5)
Location: drivers/acpi/ec.c:433
Inline: True
Direct callers:
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
**Symbols:**

```
ffffffff814830d5-ffffffff81483110: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d1be2)
Location: drivers/acpi/ec.c:440
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814d1be2-ffffffff814d1c1a: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f3e76)
Location: drivers/acpi/ec.c:472
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff814f3e76-ffffffff814f3eae: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81502d30)
Location: drivers/acpi/ec.c:478
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81502d30-ffffffff81502d7a: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81545190)
Location: drivers/acpi/ec.c:477
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81545190-ffffffff815451da: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157b830)
Location: drivers/acpi/ec.c:477
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff8157b830-ffffffff8157b87b: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81592e50)
Location: drivers/acpi/ec.c:477
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81592e50-ffffffff81592e9b: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c3df0)
Location: drivers/acpi/ec.c:467
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815c3df0-ffffffff815c3e3e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e5030)
Location: drivers/acpi/ec.c:469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815e5030-ffffffff815e507e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816905c0)
Location: drivers/acpi/ec.c:475
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff816905c0-ffffffff8169061e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ae2e0)
Location: drivers/acpi/ec.c:458
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff816ae2e0-ffffffff816ae33e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690840)
Location: drivers/acpi/ec.c:459
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff81690840-ffffffff8169089e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff817062b0)
Location: drivers/acpi/ec.c:461
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff817062b0-ffffffff8170630b: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010770978)
Location: drivers/acpi/ec.c:469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffff800010770978-ffff800010770a24: acpi_ec_complete_query (STB_LOCAL)
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
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d6f20)
Location: drivers/acpi/ec.c:469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815d6f20-ffffffff815d6f6e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c0ae0)
Location: drivers/acpi/ec.c:469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815c0ae0-ffffffff815c0b2e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d9310)
Location: drivers/acpi/ec.c:469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815d9310-ffffffff815d935e: acpi_ec_complete_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_complete_query(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f31d0)
Location: drivers/acpi/ec.c:469
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
  - drivers/acpi/ec.c:advance_transaction
```
**Symbols:**

```
ffffffff815f31d0-ffffffff815f321e: acpi_ec_complete_query (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
