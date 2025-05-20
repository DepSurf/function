# Function: <code>acpi_ex_acquire_mutex_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81495f44)
Location: drivers/acpi/acpica/exmutex.c:160
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff81495f44-ffffffff81495faa: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff814e525e)
Location: drivers/acpi/acpica/exmutex.c:160
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff814e525e-ffffffff814e52c4: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81507ab2)
Location: drivers/acpi/acpica/exmutex.c:160
Inline: True
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff81507ab2-ffffffff81507b18: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815180e2)
Location: drivers/acpi/acpica/exmutex.c:160
Inline: True
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff815180e2-ffffffff81518149: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8156564f)
Location: drivers/acpi/acpica/exmutex.c:160
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff8156564f-ffffffff8156576e: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8159c38d)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff8159c38d-ffffffff8159c4ac: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815b48c7)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff815b48c7-ffffffff815b49e6: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815e6421)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff815e6421-ffffffff815e6540: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816077b6)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff816077b6-ffffffff816078d5: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816b3aaf)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff816b3aaf-ffffffff816b3bce: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816d13da)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff816d13da-ffffffff816d14f9: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff816b3388)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff816b3388-ffffffff816b34a7: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8172a351)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff8172a351-ffffffff8172a470: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff8185ac2f)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff8185ac2f-ffffffff8185ad5b: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81996d30)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff81996d30-ffffffff81996e94: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff819dd9b0)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff819dd9b0-ffffffff819ddb14: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81a286a0)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff81a286a0-ffffffff81a28804: acpi_ex_acquire_mutex_object (STB_GLOBAL)
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffff800010786010)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffff800010786010-ffff8000107860a4: acpi_ex_acquire_mutex_object (STB_GLOBAL)
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
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815ebf4a)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff815ebf4a-ffffffff815ebfb5: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815d7563)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff815d7563-ffffffff815d75ce: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff815fba96)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff815fba96-ffffffff815fbbb5: acpi_ex_acquire_mutex_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_ex_acquire_mutex_object(u16 timeout, union acpi_operand_object *obj_desc, u64 thread_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exmutex.c (ffffffff81615946)
Location: drivers/acpi/acpica/exmutex.c:126
Inline: False
Direct callers:
  - drivers/acpi/acpica/evxface.c:acpi_acquire_global_lock
  - drivers/acpi/acpica/exmutex.c:acpi_ex_acquire_mutex
  - drivers/acpi/acpica/exutils.c:acpi_ex_acquire_global_lock
```
**Symbols:**

```
ffffffff81615946-ffffffff81615a65: acpi_ex_acquire_mutex_object (STB_GLOBAL)
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
