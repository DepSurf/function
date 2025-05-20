# Function: <code>acpi_ec_enable_gpe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_enable_gpe(struct acpi_ec *ec, bool open);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8148383d)
Location: drivers/acpi/ec.c:317
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff8148383d-ffffffff814838d4: acpi_ec_enable_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_enable_gpe(struct acpi_ec *ec, bool open);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d2436)
Location: drivers/acpi/ec.c:322
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff814d2436-ffffffff814d24cd: acpi_ec_enable_gpe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_enable_gpe(struct acpi_ec *ec, bool open);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f4912)
Location: drivers/acpi/ec.c:353
Inline: True
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff814f4912-ffffffff814f49a9: acpi_ec_enable_gpe (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff81503ab3)
Location: drivers/acpi/ec.c:357
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff81545f33)
Location: drivers/acpi/ec.c:356
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff8157b34a)
Location: drivers/acpi/ec.c:356
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff81593b3a)
Location: drivers/acpi/ec.c:356
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815c4be6)
Location: drivers/acpi/ec.c:346
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815e5e26)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff816911b1)
Location: drivers/acpi/ec.c:346
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff816aeee3)
Location: drivers/acpi/ec.c:346
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff816914f3)
Location: drivers/acpi/ec.c:347
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff81706f81)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff818350b3)
Location: drivers/acpi/ec.c:344
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
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
In drivers/acpi/ec.c (ffffffff81969235)
Location: drivers/acpi/ec.c:345
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff819af81d)
Location: drivers/acpi/ec.c:345
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff819f9ccd)
Location: drivers/acpi/ec.c:345
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffff800010770934)
Location: drivers/acpi/ec.c:348
Inline: True
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d7d16)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815c18d6)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815da106)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
In drivers/acpi/ec.c (ffffffff815f3fc6)
Location: drivers/acpi/ec.c:348
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_submit_request
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
</ul>
