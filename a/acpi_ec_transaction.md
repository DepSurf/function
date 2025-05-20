# Function: <code>acpi_ec_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81483b3b)
Location: drivers/acpi/ec.c:702
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_read
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_write
```
**Symbols:**

```
ffffffff81483b3b-ffffffff81483e87: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d25d2)
Location: drivers/acpi/ec.c:709
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:acpi_ec_read
```
**Symbols:**

```
ffffffff814d25d2-ffffffff814d28f2: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f4aae)
Location: drivers/acpi/ec.c:823
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:acpi_ec_read
```
**Symbols:**

```
ffffffff814f4aae-ffffffff814f4dc3: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81502e20)
Location: drivers/acpi/ec.c:812
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff81502e20-ffffffff815031d1: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81545280)
Location: drivers/acpi/ec.c:814
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff81545280-ffffffff81545631: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157b880)
Location: drivers/acpi/ec.c:814
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff8157b880-ffffffff8157bc1c: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81592f40)
Location: drivers/acpi/ec.c:814
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff81592f40-ffffffff815932dc: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c3ef0)
Location: drivers/acpi/ec.c:828
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff815c3ef0-ffffffff815c42a9: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e5130)
Location: drivers/acpi/ec.c:820
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff815e5130-ffffffff815e54e9: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816909a0)
Location: drivers/acpi/ec.c:816
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff816909a0-ffffffff81690af2: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ae6d0)
Location: drivers/acpi/ec.c:803
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff816ae6d0-ffffffff816ae822: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690cf0)
Location: drivers/acpi/ec.c:804
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff81690cf0-ffffffff81690e42: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:806
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff81706750-ffffffff817068c2: acpi_ec_transaction (STB_LOCAL)
ffffffff81cefa2c-ffffffff81cefa55: acpi_ec_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:829
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff818348e0-ffffffff81834a65: acpi_ec_transaction (STB_LOCAL)
ffffffff81eb75a2-ffffffff81eb75cb: acpi_ec_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:830
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff81968480-ffffffff81968605: acpi_ec_transaction (STB_LOCAL)
ffffffff82091a8b-ffffffff82091ab4: acpi_ec_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:815
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff819aea60-ffffffff819aebe5: acpi_ec_transaction (STB_LOCAL)
ffffffff821123ab-ffffffff821123d4: acpi_ec_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:815
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff819f8ee0-ffffffff819f9065: acpi_ec_transaction (STB_LOCAL)
ffffffff821f0113-ffffffff821f013c: acpi_ec_transaction.cold (STB_LOCAL)
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
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010771c30)
Location: drivers/acpi/ec.c:820
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffff800010771c30-ffff8000107720e8: acpi_ec_transaction (STB_LOCAL)
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
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d7020)
Location: drivers/acpi/ec.c:820
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff815d7020-ffffffff815d73d9: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c0be0)
Location: drivers/acpi/ec.c:820
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff815c0be0-ffffffff815c0f99: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d9410)
Location: drivers/acpi/ec.c:820
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff815d9410-ffffffff815d97c9: acpi_ec_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_ec_transaction(struct acpi_ec *ec, struct transaction *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f32d0)
Location: drivers/acpi/ec.c:820
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_space_handler
  - drivers/acpi/ec.c:acpi_ec_query
  - drivers/acpi/ec.c:ec_transaction
  - drivers/acpi/ec.c:ec_write
  - drivers/acpi/ec.c:ec_read
```
**Symbols:**

```
ffffffff815f32d0-ffffffff815f3689: acpi_ec_transaction (STB_LOCAL)
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
