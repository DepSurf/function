# Function: <code>__e820__range_add</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff820ab208)
Location: arch/x86/kernel/e820.c:133
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff820ab208-ffffffff820ab24c: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826b19ad)
Location: arch/x86/kernel/e820.c:153
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff826b19ad-ffffffff826b19f1: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff826dafaf)
Location: arch/x86/kernel/e820.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff826dafaf-ffffffff826daff3: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891396)
Location: arch/x86/kernel/e820.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff82891396-ffffffff828913da: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828a88de)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff828a88de-ffffffff828a8922: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ab942)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff828ab942-ffffffff828ab986: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82cd0c7e)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff82cd0c7e-ffffffff82cd0cc1: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82fbcabe)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff82fbcabe-ffffffff82fbcb01: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff831c71d4)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff831c71d4-ffffffff831c7218: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff832a80cc)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff832a80cc-ffffffff832a8110: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff834574d8)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff834574d8-ffffffff83457545: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff83e78283)
Location: arch/x86/kernel/e820.c:166
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__append_e820_table
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
In arch/x86/kernel/e820.c (ffffffff8369a747)
Location: arch/x86/kernel/e820.c:166
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__append_e820_table
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
In arch/x86/kernel/e820.c (ffffffff838ca4c7)
Location: arch/x86/kernel/e820.c:166
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__memory_setup_default
  - arch/x86/kernel/e820.c:e820__range_remove
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__append_e820_table
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
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82899954)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff82899954-ffffffff82899998: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff82891c12)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff82891c12-ffffffff82891c56: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac934)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff828ac934-ffffffff828ac978: __e820__range_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __e820__range_add(struct e820_table *table, u64 start, u64 size, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff828ac952)
Location: arch/x86/kernel/e820.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:__e820__range_update
  - arch/x86/kernel/e820.c:e820__range_add
```
**Symbols:**

```
ffffffff828ac952-ffffffff828ac996: __e820__range_add (STB_LOCAL)
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
