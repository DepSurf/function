# Function: <code>acpi_aml_unlock_fifo</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159af60)
Location: drivers/acpi/acpi_dbg.c:251
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8159af60-ffffffff8159afb6: acpi_aml_unlock_fifo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815d2c00)
Location: drivers/acpi/acpi_dbg.c:251
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff815d2c00-ffffffff815d2c58: acpi_aml_unlock_fifo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815ec3b0)
Location: drivers/acpi/acpi_dbg.c:251
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff815ec3b0-ffffffff815ec408: acpi_aml_unlock_fifo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8161e180)
Location: drivers/acpi/acpi_dbg.c:248
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8161e180-ffffffff8161e1d8: acpi_aml_unlock_fifo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8163fc30)
Location: drivers/acpi/acpi_dbg.c:248
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8163fc30-ffffffff8163fc88: acpi_aml_unlock_fifo (STB_LOCAL)
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
In drivers/acpi/acpi_dbg.c (ffffffff816ed1ae)
Location: drivers/acpi/acpi_dbg.c:248
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_user
  - drivers/acpi/acpi_dbg.c:acpi_aml_read_user
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
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
In drivers/acpi/acpi_dbg.c (ffffffff8170a79e)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_user
  - drivers/acpi/acpi_dbg.c:acpi_aml_read_user
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
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
In drivers/acpi/acpi_dbg.c (ffffffff816ec4fd)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
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
In drivers/acpi/acpi_dbg.c (ffffffff81766630)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
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
In drivers/acpi/acpi_dbg.c (ffffffff8189a813)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
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
In drivers/acpi/acpi_dbg.c (ffffffff819e28d3)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
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
In drivers/acpi/acpi_dbg.c (ffffffff81a2aed3)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
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
In drivers/acpi/acpi_dbg.c (ffffffff81a760a3)
Location: drivers/acpi/acpi_dbg.c:241
Inline: True
Inline callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81633a70)
Location: drivers/acpi/acpi_dbg.c:248
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff81633a70-ffffffff81633ac8: acpi_aml_unlock_fifo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_aml_unlock_fifo(long unsigned int flag, bool wakeup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8164dda0)
Location: drivers/acpi/acpi_dbg.c:248
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8164dda0-ffffffff8164ddf8: acpi_aml_unlock_fifo (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
