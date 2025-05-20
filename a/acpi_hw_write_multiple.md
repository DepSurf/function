# Function: <code>acpi_hw_write_multiple</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8149ac81)
Location: drivers/acpi/acpica/hwregs.c:636
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8149ac81-ffffffff8149acb2: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff814e9cdb)
Location: drivers/acpi/acpica/hwregs.c:730
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff814e9cdb-ffffffff814e9d0c: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8150c563)
Location: drivers/acpi/acpica/hwregs.c:730
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8150c563-ffffffff8150c594: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8151cc39)
Location: drivers/acpi/acpica/hwregs.c:795
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8151cc39-ffffffff8151cc6a: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8156d35f)
Location: drivers/acpi/acpica/hwregs.c:801
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8156d35f-ffffffff8156d394: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815a3fa7)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff815a3fa7-ffffffff815a3fdc: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815bc93f)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff815bc93f-ffffffff815bc974: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815ee52d)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff815ee52d-ffffffff815ee564: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8160f9bb)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8160f9bb-ffffffff8160f9f2: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bbda9)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff816bbda9-ffffffff816bbde0: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816d98b7)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff816d98b7-ffffffff816d98ee: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff816bb84d)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff816bb84d-ffffffff816bb884: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81732999)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff81732999-ffffffff817329d0: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff818637fc)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff818637fc-ffffffff8186383b: acpi_hw_write_multiple (STB_LOCAL)
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
In drivers/acpi/acpica/hwregs.c (ffffffff819a12cb)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
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
In drivers/acpi/acpica/hwregs.c (ffffffff819e7fab)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
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
In drivers/acpi/acpica/hwregs.c (ffffffff81a32cfb)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_clear_acpi_status
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815f0ec9)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff815f0ec9-ffffffff815f0f00: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff815dc49b)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff815dc49b-ffffffff815dc4d2: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff81603c9b)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff81603c9b-ffffffff81603cd2: acpi_hw_write_multiple (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_hw_write_multiple(u32 value, struct acpi_generic_address *register_a, struct acpi_generic_address *register_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwregs.c (ffffffff8161db4b)
Location: drivers/acpi/acpica/hwregs.c:770
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwregs.c:acpi_hw_register_write
```
**Symbols:**

```
ffffffff8161db4b-ffffffff8161db82: acpi_hw_write_multiple (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
