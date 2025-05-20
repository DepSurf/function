# Function: <code>ldm_relative</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff813cfe40)
Location: block/partitions/ldm.c:687
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff813cfe40-ffffffff813cff3d: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81415370)
Location: block/partitions/ldm.c:635
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81415370-ffffffff81415468: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff814308a0)
Location: block/partitions/ldm.c:635
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff814308a0-ffffffff81430998: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff8143d810)
Location: block/partitions/ldm.c:635
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff8143d810-ffffffff8143d903: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81469b60)
Location: block/partitions/ldm.c:635
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff81469b60-ffffffff81469c53: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:635
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff8149dac0-ffffffff8149db51: ldm_relative (STB_LOCAL)
ffffffff8149f634-ffffffff8149f694: ldm_relative.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:635
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
```
**Symbols:**

```
ffffffff814b7de0-ffffffff814b7e71: ldm_relative (STB_LOCAL)
ffffffff814b99e1-ffffffff814b9a41: ldm_relative.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814e63c0-ffffffff814e6433: ldm_relative (STB_LOCAL)
ffffffff814e808d-ffffffff814e8111: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814ff790-ffffffff814ff807: ldm_relative (STB_LOCAL)
ffffffff8150145d-ffffffff815014e1: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_dsk4
  - block/partitions/ldm.c:ldm_parse_dsk4
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81560090-ffffffff81560107: ldm_relative (STB_LOCAL)
ffffffff81561f2a-ffffffff81561fae: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_dsk4
  - block/partitions/ldm.c:ldm_parse_dsk4
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dsk3
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr4
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_dgr3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff8157bb80-ffffffff8157bbf7: ldm_relative (STB_LOCAL)
ffffffff81bf2e27-ffffffff81bf2eab: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81583700-ffffffff81583777: ldm_relative (STB_LOCAL)
ffffffff81be4cfb-ffffffff81be4d7f: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff815e8f00-ffffffff815e8f77: ldm_relative (STB_LOCAL)
ffffffff81cd9039-ffffffff81cd90bd: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81698800-ffffffff81698887: ldm_relative (STB_LOCAL)
ffffffff81e8cb4c-ffffffff81e8cbc1: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81757780)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81757780-ffffffff8175786b: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff81794b20)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff81794b20-ffffffff81794c0b: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffff817d8480)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vblk
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
  - block/partitions/ldm.c:ldm_parse_cmp3
```
**Symbols:**

```
ffffffff817d8480-ffffffff817d856b: ldm_relative (STB_LOCAL)
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
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffff800010601458)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
  - block/partitions/ldm.c:ldm_parse_prt3
```
**Symbols:**

```
ffff800010601458-ffff800010601598: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c07ac6b8)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
c07ac6b8-c07ac7d0: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (c00000000079c290)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
c00000000079c290-c00000000079c448: ldm_relative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/partitions/ldm.c (ffffffe00043c86a)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffe00043c86a-ffffffe00043c95e: ldm_relative (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814f7d70-ffffffff814f7de7: ldm_relative (STB_LOCAL)
ffffffff814f9a3d-ffffffff814f9ac1: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814e8280-ffffffff814e82f7: ldm_relative (STB_LOCAL)
ffffffff814e9f4d-ffffffff814e9fd1: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff814f3e00-ffffffff814f3e77: ldm_relative (STB_LOCAL)
ffffffff814f5acd-ffffffff814f5b51: ldm_relative.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ldm_relative(const u8 *buffer, int buflen, int base, int offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/partitions/ldm.c (0)
Location: block/partitions/ldm.c:621
Inline: False
Direct callers:
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
  - block/partitions/ldm.c:ldm_parse_vol5
```
**Symbols:**

```
ffffffff8150ce60-ffffffff8150ced7: ldm_relative (STB_LOCAL)
ffffffff8150eb2d-ffffffff8150ebb1: ldm_relative.cold (STB_LOCAL)
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
