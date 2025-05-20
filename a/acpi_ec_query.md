# Function: <code>acpi_ec_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81484178)
Location: drivers/acpi/ec.c:1063
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_clear
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
**Symbols:**

```
ffffffff81484178-ffffffff81484352: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d2be3)
Location: drivers/acpi/ec.c:1070
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_clear
```
**Symbols:**

```
ffffffff814d2be3-ffffffff814d2dbc: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f50b4)
Location: drivers/acpi/ec.c:1150
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff814f50b4-ffffffff814f528d: acpi_ec_query (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81503638)
Location: drivers/acpi/ec.c:1161
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
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
In drivers/acpi/ec.c (ffffffff81545a98)
Location: drivers/acpi/ec.c:1163
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
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
In drivers/acpi/ec.c (ffffffff8157c09a)
Location: drivers/acpi/ec.c:1169
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
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
In drivers/acpi/ec.c (ffffffff8159375a)
Location: drivers/acpi/ec.c:1181
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c46b0)
Location: drivers/acpi/ec.c:1195
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff815c46b0-ffffffff815c4889: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e58f0)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff815e58f0-ffffffff815e5ac9: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690b70)
Location: drivers/acpi/ec.c:1157
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81690b70-ffffffff81690d84: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ae8a0)
Location: drivers/acpi/ec.c:1144
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff816ae8a0-ffffffff816aeab4: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690ec0)
Location: drivers/acpi/ec.c:1145
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81690ec0-ffffffff816910cf: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81706940)
Location: drivers/acpi/ec.c:1157
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81706940-ffffffff81706b61: acpi_ec_query (STB_LOCAL)
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
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010772558)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffff800010772558-ffff800010772744: acpi_ec_query (STB_LOCAL)
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
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d77e0)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff815d77e0-ffffffff815d79b9: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c13a0)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff815c13a0-ffffffff815c1579: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d9bd0)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff815d9bd0-ffffffff815d9da9: acpi_ec_query (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec *ec, u8 *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f3a90)
Location: drivers/acpi/ec.c:1169
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff815f3a90-ffffffff815f3c69: acpi_ec_query (STB_LOCAL)
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
