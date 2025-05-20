# Function: <code>acpi_ex_release_mutex_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff814960b4)
Location: drivers/acpi/acpica/exmutex.c:300
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff814960b4-ffffffff8149611b: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff814e53c5)
Location: drivers/acpi/acpica/exmutex.c:317
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff814e53c5-ffffffff814e542c: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81507c19)
Location: drivers/acpi/acpica/exmutex.c:317
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff81507c19-ffffffff81507c80: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8151824b)
Location: drivers/acpi/acpica/exmutex.c:317
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff8151824b-ffffffff815182b3: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815659e1)
Location: drivers/acpi/acpica/exmutex.c:317
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff815659e1-ffffffff81565ada: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8159c711)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff8159c711-ffffffff8159c80a: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815b4c4b)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff815b4c4b-ffffffff815b4d44: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815e67a5)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff815e67a5-ffffffff815e689e: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81607b3a)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff81607b3a-ffffffff81607c33: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816b3e33)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff816b3e33-ffffffff816b3f2c: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816d175e)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff816d175e-ffffffff816d1857: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816b370c)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff816b370c-ffffffff816b3805: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8172a6d5)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff8172a6d5-ffffffff8172a7ce: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8185afd0)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff8185afd0-ffffffff8185b0d5: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81997190)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff81997190-ffffffff81997301: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff819dde10)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff819dde10-ffffffff819ddf81: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81a28b00)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff81a28b00-ffffffff81a28c71: acpi_ex_release_mutex_object (STB_GLOBAL)
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
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffff8000107861b0)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffff8000107861b0-ffff80001078622c: acpi_ex_release_mutex_object (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815ec0af)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff815ec0af-ffffffff815ec117: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815d76c8)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff815d76c8-ffffffff815d7730: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815fbe1a)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff815fbe1a-ffffffff815fbf13: acpi_ex_release_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ex_release_mutex_object(union acpi_operand_object *obj_desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81615cca)
Location: drivers/acpi/acpica/exmutex.c:283
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_release_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_release_global_lock
```
**Symbols:**

```
ffffffff81615cca-ffffffff81615dc3: acpi_ex_release_mutex_object (STB_GLOBAL)
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
