# Function: <code>copy_kmsg_to_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81320674)
Location: fs/pstore/platform.c:255
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81355c76)
Location: fs/pstore/platform.c:454
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8136c083)
Location: fs/pstore/platform.c:454
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff813808e8)
Location: fs/pstore/platform.c:458
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff813a58fe)
Location: fs/pstore/platform.c:458
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff813d4a85)
Location: fs/pstore/platform.c:304
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff813ef097)
Location: fs/pstore/platform.c:364
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff8141b350)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff814351a0)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t copy_kmsg_to_buffer(int hsize, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81484940)
Location: fs/pstore/platform.c:351
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81484940-ffffffff814849cf: copy_kmsg_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t copy_kmsg_to_buffer(int hsize, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff814a1f70)
Location: fs/pstore/platform.c:351
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff814a1f70-ffffffff814a1fff: copy_kmsg_to_buffer (STB_LOCAL)
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
In fs/pstore/platform.c (ffffffff814a88a0)
Location: fs/pstore/platform.c:351
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff81500bd0)
Location: fs/pstore/platform.c:351
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t copy_kmsg_to_buffer(int hsize, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff815915d0)
Location: fs/pstore/platform.c:352
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff815915d0-ffffffff81591673: copy_kmsg_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t copy_kmsg_to_buffer(int hsize, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81638cc0)
Location: fs/pstore/platform.c:354
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81638cc0-ffffffff81638d64: copy_kmsg_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t copy_kmsg_to_buffer(int hsize, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816710c0)
Location: fs/pstore/platform.c:354
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff816710c0-ffffffff81671164: copy_kmsg_to_buffer (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/pstore/platform.c (ffff80001051b214)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (c06d5638)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (c000000000665190)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffe0003841a4)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff8142d780)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff8141e200)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff81429920)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
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
In fs/pstore/platform.c (ffffffff814407e0)
Location: fs/pstore/platform.c:354
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
