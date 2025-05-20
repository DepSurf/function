# Function: <code>i2c_acpi_install_space_handler</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff8170dfe8)
Location: drivers/i2c/i2c-core.c:607
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81724bb0)
Location: drivers/i2c/i2c-core-acpi.c:610
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81724bb0-ffffffff81724ca5: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81796080)
Location: drivers/i2c/i2c-core-acpi.c:610
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81796080-ffffffff8179616d: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817d8be0)
Location: drivers/i2c/i2c-core-acpi.c:624
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817d8be0-ffffffff817d8ccd: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff817ffd80)
Location: drivers/i2c/i2c-core-acpi.c:650
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817ffd80-ffffffff817ffe6d: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:673
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81841223-ffffffff8184124e: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff81840f80-ffffffff81841059: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:702
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81872b9c-ffffffff81872bc7: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff818728e0-ffffffff818729b9: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:694
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81946cf0-ffffffff81946d1b: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff81946a70-ffffffff81946b49: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:694
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81c24e9c-ffffffff81c24ec7: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff8194c9d0-ffffffff8194caa1: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:690
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81c16efc-ffffffff81c16f27: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff81930540-ffffffff81930611: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:723
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81d25bf6-ffffffff81d25c21: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff819d3820-ffffffff819d38f1: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:739
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81ef1945-ffffffff81ef196a: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff81b35f60-ffffffff81b36046: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81ccb240)
Location: drivers/i2c/i2c-core-acpi.c:759
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81ccb240-ffffffff81ccb327: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81d32fb0)
Location: drivers/i2c/i2c-core-acpi.c:748
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81d32fb0-ffffffff81d33097: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de8fd0)
Location: drivers/i2c/i2c-core-acpi.c:748
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81de8fd0-ffffffff81de90eb: i2c_acpi_install_space_handler (STB_GLOBAL)
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
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (ffff800010ab6180)
Location: drivers/i2c/i2c-core-acpi.c:702
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffff800010ab6180-ffff800010ab6290: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core.h:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core.h:88
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core.h:88
Inline: True
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
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:702
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81866d2c-ffffffff81866d57: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff81866a70-ffffffff81866b49: i2c_acpi_install_space_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int i2c_acpi_install_space_handler(struct i2c_adapter *adapter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-acpi.c (0)
Location: drivers/i2c/i2c-core-acpi.c:702
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81881fdc-ffffffff81882007: i2c_acpi_install_space_handler.cold (STB_LOCAL)
ffffffff81881d20-ffffffff81881df9: i2c_acpi_install_space_handler (STB_GLOBAL)
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
