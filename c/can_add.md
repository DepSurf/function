# Function: <code>can_add</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814fedd4)
Location: block/sed-opal.c:536
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffff814fea30-ffffffff814fea6e: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8151cd24)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffff8151c980-ffffffff8151c9be: can_add.part.0 (STB_LOCAL)
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
In block/sed-opal.c (ffffffff8157d3c8)
Location: block/sed-opal.c:537
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
  - block/sed-opal.c:add_bytestring_header
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
In block/sed-opal.c (ffffffff8159a408)
Location: block/sed-opal.c:537
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
  - block/sed-opal.c:add_bytestring_header
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
In block/sed-opal.c (ffffffff815a0efd)
Location: block/sed-opal.c:537
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
  - block/sed-opal.c:add_bytestring_header
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
In block/sed-opal.c (ffffffff816098dd)
Location: block/sed-opal.c:537
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
  - block/sed-opal.c:add_bytestring_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool can_add(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bda68)
Location: block/sed-opal.c:537
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff816bcb70-ffffffff816bcbff: can_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool can_add(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e7f8)
Location: block/sed-opal.c:577
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
```
**Symbols:**

```
ffffffff8177d5f0-ffffffff8177d67f: can_add (STB_LOCAL)
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
In block/sed-opal.c (ffffffff817bdfd8)
Location: block/sed-opal.c:585
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
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
In block/sed-opal.c (ffffffff81802c98)
Location: block/sed-opal.c:698
Inline: True
Inline callers:
  - block/sed-opal.c:add_bytestring_header
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffff8000106258b8)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffff8000106254e8-ffff800010625554: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (c07cd344)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
c07ccf2c-c07ccf84: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (c0000000007c66f8)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
c0000000007c6220-c0000000007c62a4: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffe000456b3e)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffe00045670c-ffffffe000456766: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81515304)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffff81514f60-ffffffff81514f9e: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81505614)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffff81505270-ffffffff815052ae: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81511394)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffff81510ff0-ffffffff8151102e: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8152ab54)
Location: block/sed-opal.c:535
Inline: True
Inline callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
Direct callers:
  - block/sed-opal.c:add_token_u64
  - block/sed-opal.c:add_token_u8
```
**Symbols:**

```
ffffffff8152a7b0-ffffffff8152a7ee: can_add.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
