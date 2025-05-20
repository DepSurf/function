# Function: <code>__e820__range_update</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab24c)
Location: arch/x86/kernel/e820.c:413
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff820ab24c-ffffffff820ab3db: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b19f1)
Location: arch/x86/kernel/e820.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff826b19f1-ffffffff826b1b80: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826db08e)
Location: arch/x86/kernel/e820.c:435
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff826db08e-ffffffff826db21b: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891475)
Location: arch/x86/kernel/e820.c:434
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff82891475-ffffffff82891602: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a89c0)
Location: arch/x86/kernel/e820.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff828a89c0-ffffffff828a8b6e: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828aba24)
Location: arch/x86/kernel/e820.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff828aba24-ffffffff828abbd2: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd0d7d)
Location: arch/x86/kernel/e820.c:449
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff82cd0d7d-ffffffff82cd0f10: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbcbbd)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff82fbcbbd-ffffffff82fbcd50: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c72d4)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff831c72d4-ffffffff831c7464: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a81cc)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff832a81cc-ffffffff832a835c: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8345760b)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff8345760b-ffffffff834577c2: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e76040)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff83e76040-ffffffff83e76326: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83697c40)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff83697c40-ffffffff83698239: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff838c79c0)
Location: arch/x86/kernel/e820.c:463
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
```
**Symbols:**

```
ffffffff838c79c0-ffffffff838c7fb9: __e820__range_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82899a36)
Location: arch/x86/kernel/e820.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff82899a36-ffffffff82899be4: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891cf4)
Location: arch/x86/kernel/e820.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff82891cf4-ffffffff82891ea2: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828aca16)
Location: arch/x86/kernel/e820.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff828aca16-ffffffff828acbc4: __e820__range_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 __e820__range_update(struct e820_table *table, u64 start, u64 size, enum e820_type old_type, enum e820_type new_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828aca34)
Location: arch/x86/kernel/e820.c:448
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__reserve_setup_data
  - arch/x86/kernel/e820.c:e820__memblock_alloc_reserved
  - arch/x86/kernel/e820.c:e820__range_update
```
**Symbols:**

```
ffffffff828aca34-ffffffff828acbe2: __e820__range_update (STB_LOCAL)
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
