# Function: <code>ima_restore_template_data</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff813ee3b2)
Location: security/integrity/ima/ima_template.c:272
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff813fa8c9)
Location: security/integrity/ima/ima_template.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff81422d69)
Location: security/integrity/ima/ima_template.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff8145535e)
Location: security/integrity/ima/ima_template.c:275
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff8147273e)
Location: security/integrity/ima/ima_template.c:276
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff814a0423)
Location: security/integrity/ima/ima_template.c:277
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff814baa80)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8151ab10)
Location: security/integrity/ima/ima_template.c:299
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff8151ab10-ffffffff8151acc9: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81537a70)
Location: security/integrity/ima/ima_template.c:325
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81537a70-ffffffff81537c20: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81540060)
Location: security/integrity/ima/ima_template.c:325
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81540060-ffffffff81540205: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff8159f850)
Location: security/integrity/ima/ima_template.c:349
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff8159f850-ffffffff8159f9f5: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81644fe0)
Location: security/integrity/ima/ima_template.c:353
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81644fe0-ffffffff8164518d: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff816fd430)
Location: security/integrity/ima/ima_template.c:356
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff816fd430-ffffffff816fd5e3: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81737460)
Location: security/integrity/ima/ima_template.c:356
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81737460-ffffffff81737608: ima_restore_template_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_restore_template_data(struct ima_template_desc *template_desc, void *template_data, int template_data_size, struct ima_template_entry **entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffff81777f50)
Location: security/integrity/ima/ima_template.c:356
Inline: False
Direct callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
**Symbols:**

```
ffffffff81777f50-ffffffff817780f8: ima_restore_template_data (STB_LOCAL)
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
In security/integrity/ima/ima_template.c (ffff8000105b2f44)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (c0762568)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (c000000000735598)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_template.c (ffffffe0003fa5ee)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
</details>
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
In security/integrity/ima/ima_template.c (ffffffff814b3060)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff814a3a80)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff814af0f0)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
In security/integrity/ima/ima_template.c (ffffffff814c7b70)
Location: security/integrity/ima/ima_template.c:301
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
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
