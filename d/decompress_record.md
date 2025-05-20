# Function: <code>decompress_record</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81380ad4)
Location: fs/pstore/platform.c:778
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff813a5aec)
Location: fs/pstore/platform.c:775
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff813d4c79)
Location: fs/pstore/platform.c:621
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff813ef289)
Location: fs/pstore/platform.c:664
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff8141b509)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff81435359)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:668
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:668
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814a2320-ffffffff814a2426: decompress_record (STB_LOCAL)
ffffffff81bef9cc-ffffffff81befa09: decompress_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:671
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814a83c0-ffffffff814a84c6: decompress_record (STB_LOCAL)
ffffffff81be1a75-ffffffff81be1ab2: decompress_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:671
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff815006e0-ffffffff815007f5: decompress_record (STB_LOCAL)
ffffffff81cd2710-ffffffff81cd2762: decompress_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:669
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81591760-ffffffff8159188d: decompress_record (STB_LOCAL)
ffffffff81e85762-ffffffff81e857b4: decompress_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:684
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81638d80-ffffffff81638ee1: decompress_record (STB_LOCAL)
ffffffff82072b07-ffffffff82072b1c: decompress_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:684
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81671180-ffffffff81671324: decompress_record (STB_LOCAL)
ffffffff820f276b-ffffffff820f2780: decompress_record.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void decompress_record(struct pstore_record *record, struct z_stream_s *zstream);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:582
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff816ad3e0-ffffffff816ad5b2: decompress_record (STB_LOCAL)
ffffffff821cfa1b-ffffffff821cfa30: decompress_record.cold (STB_LOCAL)
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
In fs/pstore/platform.c (ffff80001051b3f8)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (c06d58d8)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (c000000000665464)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffe000384318)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
</details>
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
In fs/pstore/platform.c (ffffffff8142d939)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff8141e3b9)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff81429ad9)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
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
In fs/pstore/platform.c (ffffffff81440999)
Location: fs/pstore/platform.c:658
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct z_stream_s *zstream</code>
</li>
</ul>
</details>
</li>
</ul>
