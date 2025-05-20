# Function: <code>acpi_aml_lock_write</code>

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
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8159b510)
Location: drivers/acpi/acpi_dbg.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8159b510-ffffffff8159b5b1: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815d35e0)
Location: drivers/acpi/acpi_dbg.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff815d35e0-ffffffff815d3678: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff815ecd90)
Location: drivers/acpi/acpi_dbg.c:213
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff815ecd90-ffffffff815ece28: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8161eb50)
Location: drivers/acpi/acpi_dbg.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8161eb50-ffffffff8161ebe9: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81640600)
Location: drivers/acpi/acpi_dbg.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff81640600-ffffffff81640699: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ed050)
Location: drivers/acpi/acpi_dbg.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_user
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
```
**Symbols:**

```
ffffffff816ed050-ffffffff816ed0ec: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8170a640)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_user
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
```
**Symbols:**

```
ffffffff8170a640-ffffffff8170a6dc: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff816ebd10)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff816ebd10-ffffffff816ebdad: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81765e30)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff81765e30-ffffffff81765ecd: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8189a250)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8189a250-ffffffff8189a2f9: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff819e2780)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
```
**Symbols:**

```
ffffffff819e2780-ffffffff819e2829: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a2ad80)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
```
**Symbols:**

```
ffffffff81a2ad80-ffffffff81a2ae29: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81a75f50)
Location: drivers/acpi/acpi_dbg.c:203
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_kern
```
**Symbols:**

```
ffffffff81a75f50-ffffffff81a75ff9: acpi_aml_lock_write (STB_LOCAL)
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
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff81634440)
Location: drivers/acpi/acpi_dbg.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff81634440-ffffffff816344d9: acpi_aml_lock_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_aml_lock_write(struct circ_buf *circ, long unsigned int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_dbg.c (ffffffff8164e760)
Location: drivers/acpi/acpi_dbg.c:210
Inline: False
Direct callers:
  - drivers/acpi/acpi_dbg.c:acpi_aml_write_log
```
**Symbols:**

```
ffffffff8164e760-ffffffff8164e7f9: acpi_aml_lock_write (STB_LOCAL)
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
