# Function: <code>acpi_acquire_global_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81492d6d)
Location: drivers/acpi/acpica/evxface.c:1052
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81492d6d-ffffffff81492dc3: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff814e1b68)
Location: drivers/acpi/acpica/evxface.c:1051
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff814e1b68-ffffffff814e1bc2: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815044a7)
Location: drivers/acpi/acpica/evxface.c:1051
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815044a7-ffffffff81504501: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815142d5)
Location: drivers/acpi/acpica/evxface.c:1051
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815142d5-ffffffff8151432f: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8155daf6)
Location: drivers/acpi/acpica/evxface.c:1051
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff8155daf6-ffffffff8155db50: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81594693)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81594693-ffffffff815946ed: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815acd96)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815acd96-ffffffff815acdf0: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815de5ae)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815de5ae-ffffffff815de60a: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815ff8f1)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815ff8f1-ffffffff815ff94d: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ac7ae)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff816ac7ae-ffffffff816ac80a: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ca0ed)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff816ca0ed-ffffffff816ca149: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff816ac0ce)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff816ac0ce-ffffffff816ac12a: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81722deb)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81722deb-ffffffff81722e47: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81853287)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81853287-ffffffff818532ec: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8198d820)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff8198d820-ffffffff8198d892: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff819d42b0)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff819d42b0-ffffffff819d4322: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff81a1eee0)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff81a1eee0-ffffffff81a1ef52: acpi_acquire_global_lock (STB_GLOBAL)
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
In drivers/acpi/ec.c (0)
Location: include/acpi/acpixf.h:666
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
<summary>In <code>aws</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815e8000)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815e8000-ffffffff815e805c: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815d362e)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815d362e-ffffffff815d368a: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff815f3bd1)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff815f3bd1-ffffffff815f3c2d: acpi_acquire_global_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_acquire_global_lock(u16 timeout, u32 *handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxface.c (ffffffff8160da81)
Location: drivers/acpi/acpica/evxface.c:1026
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_transaction
```
**Symbols:**

```
ffffffff8160da81-ffffffff8160dadd: acpi_acquire_global_lock (STB_GLOBAL)
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
