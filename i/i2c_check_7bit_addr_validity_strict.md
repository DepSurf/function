# Function: <code>i2c_check_7bit_addr_validity_strict</code>

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
In drivers/i2c/i2c-core.c (ffffffff8167c8a0)
Location: drivers/i2c/i2c-core.c:889
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
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
In drivers/i2c/i2c-core.c (ffffffff816da6d0)
Location: drivers/i2c/i2c-core.c:1022
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_slave_register
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
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
In drivers/i2c/i2c-core.c (ffffffff8170db12)
Location: drivers/i2c/i2c-core.c:1159
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_new_probed_device
  - drivers/i2c/i2c-core.c:i2c_do_add_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81721a4b)
Location: drivers/i2c/i2c-core-base.c:561
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff81721dd0-ffffffff81721de9: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81792d9d)
Location: drivers/i2c/i2c-core-base.c:566
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff81793200-ffffffff81793219: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d53f6)
Location: drivers/i2c/i2c-core-base.c:547
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff817d5ad0-ffffffff817d5ae9: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fc566)
Location: drivers/i2c/i2c-core-base.c:559
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff817fcc00-ffffffff817fcc19: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183d476)
Location: drivers/i2c/i2c-core-base.c:557
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8183c900-ffffffff8183c919: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186ee76)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8186e300-ffffffff8186e319: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81942e86)
Location: drivers/i2c/i2c-core-base.c:572
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff819420e0-ffffffff819420f9: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81949266)
Location: drivers/i2c/i2c-core-base.c:700
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81948430-ffffffff81948449: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192cb96)
Location: drivers/i2c/i2c-core-base.c:744
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff8192bd90-ffffffff8192bda9: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cfd66)
Location: drivers/i2c/i2c-core-base.c:745
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff819cef50-ffffffff819cef69: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b31c26)
Location: drivers/i2c/i2c-core-base.c:746
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81b30cd0-ffffffff81b30cef: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc6816)
Location: drivers/i2c/i2c-core-base.c:747
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81cc5630-ffffffff81cc564f: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2e4b3)
Location: drivers/i2c/i2c-core-base.c:762
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81d2d2c0-ffffffff81d2d2df: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de4463)
Location: drivers/i2c/i2c-core-base.c:765
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_scanned_device
  - drivers/i2c/i2c-core-base.c:i2c_detect_address
```
**Symbols:**

```
ffffffff81de31b0-ffffffff81de31cf: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
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
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab27c4)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
Direct callers:
  - drivers/i2c/i2c-core-slave.c:i2c_slave_register
```
**Symbols:**

```
ffff800010ab1970-ffff800010ab19a8: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b93e80)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
Direct callers:
  - drivers/i2c/i2c-core-slave.c:i2c_slave_register
```
**Symbols:**

```
c0b930bc-c0b930e4: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b96110)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
c000000000b94e20-c000000000b94e48: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006ba442)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffe0006b979e-ffffffe0006b97d0: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81863006)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff81862490-ffffffff818624a9: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int i2c_check_7bit_addr_validity_strict(short unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187e266)
Location: drivers/i2c/i2c-core-base.c:562
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_probed_device
  - drivers/i2c/i2c-core-base.c:i2c_detect
```
**Symbols:**

```
ffffffff8187d6f0-ffffffff8187d709: i2c_check_7bit_addr_validity_strict (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
