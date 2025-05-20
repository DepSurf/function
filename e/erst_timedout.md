# Function: <code>erst_timedout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff814b3ec0)
Location: drivers/acpi/apei/erst.c:107
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
```
**Symbols:**

```
ffffffff814b3ec0-ffffffff814b3efb: erst_timedout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81503830)
Location: drivers/acpi/apei/erst.c:108
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff81503830-ffffffff8150386b: erst_timedout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff81527a20)
Location: drivers/acpi/apei/erst.c:108
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff81527a20-ffffffff81527a5b: erst_timedout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8153a970)
Location: drivers/acpi/apei/erst.c:108
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff8153a970-ffffffff8153a9b0: erst_timedout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffffffff8159d4d0)
Location: drivers/acpi/apei/erst.c:108
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff8159d4d0-ffffffff8159d510: erst_timedout (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:108
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff815d5200-ffffffff815d5231: erst_timedout (STB_LOCAL)
ffffffff815d65e9-ffffffff815d65ff: erst_timedout.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:108
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff815ee9b0-ffffffff815ee9e1: erst_timedout (STB_LOCAL)
ffffffff815efd99-ffffffff815efdaf: erst_timedout.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:100
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff81620750-ffffffff81620784: erst_timedout (STB_LOCAL)
ffffffff81621b10-ffffffff81621b26: erst_timedout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:100
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff81642230-ffffffff81642264: erst_timedout (STB_LOCAL)
ffffffff816435f0-ffffffff81643606: erst_timedout.cold (STB_LOCAL)
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
In drivers/acpi/apei/erst.c (ffffffff816efe65)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff8170d245)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_clear_from_storage
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff816ee91c)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff817689fc)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff8189d26e)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff819e600d)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff81a2e68d)
Location: drivers/acpi/apei/erst.c:100
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
In drivers/acpi/apei/erst.c (ffffffff81a79970)
Location: drivers/acpi/apei/erst.c:118
Inline: True
Inline callers:
  - drivers/acpi/apei/erst.c:__erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
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
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/erst.c (ffff8000107ad1b8)
Location: drivers/acpi/apei/erst.c:100
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffff8000107ad1b8-ffff8000107ad218: erst_timedout (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:100
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff815fe640-ffffffff815fe674: erst_timedout (STB_LOCAL)
ffffffff815ff9d0-ffffffff815ff9e6: erst_timedout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:100
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff81636070-ffffffff816360a4: erst_timedout (STB_LOCAL)
ffffffff81637430-ffffffff81637446: erst_timedout.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int erst_timedout(u64 *t, u64 spin_unit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/apei/erst.c (0)
Location: drivers/acpi/apei/erst.c:100
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_read
  - drivers/acpi/apei/erst.c:erst_write
  - drivers/acpi/apei/erst.c:erst_exec_stall_while_true
```
**Symbols:**

```
ffffffff81650380-ffffffff816503b4: erst_timedout (STB_LOCAL)
ffffffff81651740-ffffffff81651756: erst_timedout.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
