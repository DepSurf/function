# Function: <code>advance_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81483498)
Location: drivers/acpi/ec.c:511
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_event_handler
```
**Symbols:**

```
ffffffff81483498-ffffffff8148383d: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d2074)
Location: drivers/acpi/ec.c:518
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff814d2074-ffffffff814d2436: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f451d)
Location: drivers/acpi/ec.c:632
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff814f451d-ffffffff814f4912: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81502680)
Location: drivers/acpi/ec.c:621
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff81502680-ffffffff81502b74: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81544af0)
Location: drivers/acpi/ec.c:623
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff81544af0-ffffffff81544fd5: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8157ab40)
Location: drivers/acpi/ec.c:623
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff8157ab40-ffffffff8157b03b: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815927c0)
Location: drivers/acpi/ec.c:623
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815927c0-ffffffff81592cb6: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c36c0)
Location: drivers/acpi/ec.c:637
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815c36c0-ffffffff815c3cda: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e4900)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815e4900-ffffffff815e4f1a: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168ff00)
Location: drivers/acpi/ec.c:635
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_irq_handler
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:ec_poll
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff8168ff00-ffffffff8169036f: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816adbd0)
Location: drivers/acpi/ec.c:628
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_irq_handler
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:ec_poll
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff816adbd0-ffffffff816ae064: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690140)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_irq_handler
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81690140-ffffffff816906ca: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:631
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_irq_handler
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81705bb0-ffffffff81706146: advance_transaction (STB_LOCAL)
ffffffff81cefa18-ffffffff81cefa2c: advance_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:656
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_irq_handler
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_start
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffffffff81833d00-ffffffff81834280: advance_transaction (STB_LOCAL)
ffffffff81eb758d-ffffffff81eb75a2: advance_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:657
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_irq_handler
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff819679a0-ffffffff81967ee4: advance_transaction (STB_LOCAL)
ffffffff82091a76-ffffffff82091a8b: advance_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:657
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff819adf70-ffffffff819ae44a: advance_transaction (STB_LOCAL)
ffffffff82112396-ffffffff821123ab: advance_transaction.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void advance_transaction(struct acpi_ec *ec, bool interrupt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:657
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction_unlocked
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_unmask_events
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff819f83f0-ffffffff819f88ca: advance_transaction (STB_LOCAL)
ffffffff821f00fe-ffffffff821f0113: advance_transaction.cold (STB_LOCAL)
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
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010771698)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
```
**Symbols:**

```
ffff800010771698-ffff800010771c2c: advance_transaction (STB_LOCAL)
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
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d67f0)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815d67f0-ffffffff815d6e0a: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c03b0)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815c03b0-ffffffff815c09ca: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d8be0)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815d8be0-ffffffff815d91fa: advance_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void advance_transaction(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f2aa0)
Location: drivers/acpi/ec.c:629
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_gpe_handler
  - drivers/acpi/ec.c:acpi_ec_event_handler
  - drivers/acpi/ec.c:acpi_ec_transaction
  - drivers/acpi/ec.c:acpi_ec_enable_event
  - drivers/acpi/ec.c:acpi_ec_submit_request
```
**Symbols:**

```
ffffffff815f2aa0-ffffffff815f30ba: advance_transaction (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool interrupt</code>
</li>
</ul>
</details>
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
