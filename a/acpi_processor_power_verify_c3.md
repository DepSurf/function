# Function: <code>acpi_processor_power_verify_c3</code>

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
In drivers/acpi/processor_idle.c (ffffffff814aca33)
Location: drivers/acpi/processor_idle.c:494
Inline: True
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
In drivers/acpi/processor_idle.c (ffffffff814fc2ce)
Location: drivers/acpi/processor_idle.c:459
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff8151efa2)
Location: drivers/acpi/processor_idle.c:460
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81530582)
Location: drivers/acpi/processor_idle.c:460
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81591432)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815c8592)
Location: drivers/acpi/processor_idle.c:466
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815e1b52)
Location: drivers/acpi/processor_idle.c:467
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81613695)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81634b95)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e0ef0)
Location: drivers/acpi/processor_idle.c:318
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff816e0ef0-ffffffff816e10b4: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816fec50)
Location: drivers/acpi/processor_idle.c:310
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff816fec50-ffffffff816fee14: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff816e08d0)
Location: drivers/acpi/processor_idle.c:307
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff816e08d0-ffffffff816e0a14: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81758b40)
Location: drivers/acpi/processor_idle.c:307
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81758b40-ffffffff81758c77: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8188c1c0)
Location: drivers/acpi/processor_idle.c:309
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff8188c1c0-ffffffff8188c32f: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff819d39a0)
Location: drivers/acpi/processor_idle.c:310
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff819d39a0-ffffffff819d3b0f: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a1b0e0)
Location: drivers/acpi/processor_idle.c:310
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81a1b0e0-ffffffff81a1b24f: acpi_processor_power_verify_c3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_processor_power_verify_c3(struct acpi_processor *pr, struct acpi_processor_cx *cx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff81a663e0)
Location: drivers/acpi/processor_idle.c:310
Inline: False
Direct callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_verify
```
**Symbols:**

```
ffffffff81a663e0-ffffffff81a6654f: acpi_processor_power_verify_c3 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_idle.c (ffffffff8160464c)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff815ef6fc)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81628e75)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
In drivers/acpi/processor_idle.c (ffffffff81642d25)
Location: drivers/acpi/processor_idle.c:462
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_get_power_info
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
