# Function: <code>acpi_ec_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8148453f)
Location: drivers/acpi/ec.c:877
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff8148453f-ffffffff814846b8: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814d2faa)
Location: drivers/acpi/ec.c:884
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff814d2faa-ffffffff814d3122: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f54ef)
Location: drivers/acpi/ec.c:977
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff814f54ef-ffffffff814f5666: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815023c0)
Location: drivers/acpi/ec.c:966
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815023c0-ffffffff81502555: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81544830)
Location: drivers/acpi/ec.c:968
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff81544830-ffffffff815449c5: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:968
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff8157a880-ffffffff8157aa16: acpi_ec_stop (STB_LOCAL)
ffffffff8157c40c-ffffffff8157c41d: acpi_ec_stop.cold.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:968
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff81592500-ffffffff81592696: acpi_ec_stop (STB_LOCAL)
ffffffff815940ec-ffffffff815940fd: acpi_ec_stop.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:982
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815c3410-ffffffff815c35a6: acpi_ec_stop (STB_LOCAL)
ffffffff815c513c-ffffffff815c514d: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:974
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815e4650-ffffffff815e47e6: acpi_ec_stop (STB_LOCAL)
ffffffff815e636a-ffffffff815e637b: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168fbe0)
Location: drivers/acpi/ec.c:970
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff8168fbe0-ffffffff8168fd8d: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816ad8b0)
Location: drivers/acpi/ec.c:957
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff816ad8b0-ffffffff816ada5d: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168fe20)
Location: drivers/acpi/ec.c:958
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff8168fe20-ffffffff8168ffcd: acpi_ec_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:960
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff817057c0-ffffffff81705973: acpi_ec_stop (STB_LOCAL)
ffffffff81cef9e2-ffffffff81cef9f6: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:983
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff818334c0-ffffffff81833698: acpi_ec_stop (STB_LOCAL)
ffffffff81eb7452-ffffffff81eb7478: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:980
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff81967000-ffffffff819671fe: acpi_ec_stop (STB_LOCAL)
ffffffff820919fa-ffffffff82091a0f: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:965
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff819ad5d0-ffffffff819ad7ce: acpi_ec_stop (STB_LOCAL)
ffffffff8211231a-ffffffff8211232f: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:965
Inline: False
Direct callers:
  - drivers/acpi/ec.c:ec_remove_handlers
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff819f7a50-ffffffff819f7c4e: acpi_ec_stop (STB_LOCAL)
ffffffff821f0082-ffffffff821f0097: acpi_ec_stop.cold (STB_LOCAL)
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
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010771178)
Location: drivers/acpi/ec.c:974
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffff800010771178-ffff8000107713f0: acpi_ec_stop (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:974
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815d6540-ffffffff815d66d6: acpi_ec_stop (STB_LOCAL)
ffffffff815d822a-ffffffff815d823b: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:974
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815c0100-ffffffff815c0296: acpi_ec_stop (STB_LOCAL)
ffffffff815c1e1a-ffffffff815c1e2b: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:974
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815d8930-ffffffff815d8ac6: acpi_ec_stop (STB_LOCAL)
ffffffff815da64a-ffffffff815da65b: acpi_ec_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_ec_stop(struct acpi_ec *ec, bool suspending);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:974
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:ec_install_handlers
  - drivers/acpi/ec.c:acpi_ec_block_transactions
```
**Symbols:**

```
ffffffff815f27f0-ffffffff815f2981: acpi_ec_stop (STB_LOCAL)
ffffffff815f450a-ffffffff815f451b: acpi_ec_stop.cold (STB_LOCAL)
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
