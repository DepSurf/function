# Function: <code>acpi_os_wait_command_ready</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1309
Inline: False
```
**Symbols:**

```
ffffffff814c8b53-ffffffff814c8b63: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1304
Inline: False
```
**Symbols:**

```
ffffffff814eaa97-ffffffff814eaaa7: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f6930)
Location: drivers/acpi/osl.c:1303
Inline: True
```
**Symbols:**

```
ffffffff814f6930-ffffffff814f6940: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81537960)
Location: drivers/acpi/osl.c:1313
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81537960-ffffffff81537973: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8156d4f0)
Location: drivers/acpi/osl.c:1318
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8156d4f0-ffffffff8156d503: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815850b0)
Location: drivers/acpi/osl.c:1324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815850b0-ffffffff815850c3: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5cd0)
Location: drivers/acpi/osl.c:1310
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815b5cd0-ffffffff815b5ce3: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d6f00)
Location: drivers/acpi/osl.c:1330
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815d6f00-ffffffff815d6f13: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81680c30)
Location: drivers/acpi/osl.c:1330
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81680c30-ffffffff81680c43: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169f720)
Location: drivers/acpi/osl.c:1334
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8169f720-ffffffff8169f733: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816823d0)
Location: drivers/acpi/osl.c:1334
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816823d0-ffffffff816823e3: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f7540)
Location: drivers/acpi/osl.c:1334
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816f7540-ffffffff816f7553: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81824480)
Location: drivers/acpi/osl.c:1336
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81824480-ffffffff81824497: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81955870)
Location: drivers/acpi/osl.c:1336
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81955870-ffffffff81955887: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199bc70)
Location: drivers/acpi/osl.c:1336
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8199bc70-ffffffff8199bc87: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e41c0)
Location: drivers/acpi/osl.c:1330
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff819e41c0-ffffffff819e41d7: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010764298)
Location: drivers/acpi/osl.c:1330
Inline: True
```
**Symbols:**

```
ffff800010764298-ffff8000107642b4: acpi_os_wait_command_ready (STB_GLOBAL)
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
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca450)
Location: drivers/acpi/osl.c:1330
Inline: False
```
**Symbols:**

```
ffffffff815ca450-ffffffff815ca460: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b34d0)
Location: drivers/acpi/osl.c:1330
Inline: False
```
**Symbols:**

```
ffffffff815b34d0-ffffffff815b34e0: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb1e0)
Location: drivers/acpi/osl.c:1330
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815cb1e0-ffffffff815cb1f3: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_os_wait_command_ready();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e5080)
Location: drivers/acpi/osl.c:1330
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815e5080-ffffffff815e5093: acpi_os_wait_command_ready (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
