# Function: <code>acpi_hw_validate_io_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff8149b26f)
Location: drivers/acpi/acpica/hwvalid.c:124
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
```
**Symbols:**

```
ffffffff8149b26f-ffffffff8149b33c: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff814ea2e5)
Location: drivers/acpi/acpica/hwvalid.c:124
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff814ea2e5-ffffffff814ea3b2: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff8150cb6d)
Location: drivers/acpi/acpica/hwvalid.c:124
Inline: True
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff8150cb6d-ffffffff8150cc3a: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff8151d243)
Location: drivers/acpi/acpica/hwvalid.c:124
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff8151d243-ffffffff8151d310: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff8156ddb7)
Location: drivers/acpi/acpica/hwvalid.c:124
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff8156ddb7-ffffffff8156df6e: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff815a4a05)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff815a4a05-ffffffff815a4c4d: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff815bd3c5)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff815bd3c5-ffffffff815bd60d: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff815eefcb)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff815eefcb-ffffffff815ef213: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff81610459)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff81610459-ffffffff816106a1: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff816bc86c)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff816bc86c-ffffffff816bcab4: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff816da37a)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff816da37a-ffffffff816da5c2: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff816bc310)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff816bc310-ffffffff816bc55f: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff817334f8)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff817334f8-ffffffff81733747: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff818643f6)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff818643f6-ffffffff81864657: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff819a2220)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff819a2220-ffffffff819a24e6: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff819e8ed0)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff819e8ed0-ffffffff819e9195: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff81a33c20)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_validate_io_block
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff81a33c20-ffffffff81a33ee5: acpi_hw_validate_io_request (STB_LOCAL)
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffff80001078b114)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffff80001078b114-ffff80001078b22c: acpi_hw_validate_io_request (STB_LOCAL)
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
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff815f1545)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff815f1545-ffffffff815f1611: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff815dcaec)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff815dcaec-ffffffff815dcbb8: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff81604739)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff81604739-ffffffff81604981: acpi_hw_validate_io_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_hw_validate_io_request(acpi_io_address address, u32 bit_width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/hwvalid.c (ffffffff8161e5e9)
Location: drivers/acpi/acpica/hwvalid.c:90
Inline: False
Direct callers:
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_write_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
  - drivers/acpi/acpica/hwvalid.c:acpi_hw_read_port
```
**Symbols:**

```
ffffffff8161e5e9-ffffffff8161e831: acpi_hw_validate_io_request (STB_LOCAL)
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
