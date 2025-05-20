# Function: <code>__e820__mapped_all</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81033ef5)
Location: arch/x86/kernel/e820.c:99
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff81035225)
Location: arch/x86/kernel/e820.c:99
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff81036405)
Location: arch/x86/kernel/e820.c:98
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff810385f5)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff81038dc5)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8103b8c5)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff8103b7b0-ffffffff8103b856: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8103c065)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff8103bf50-ffffffff8103bff6: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8103d9f5)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff8103d8f0-ffffffff8103d98d: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81043665)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff81043560-ffffffff810435fd: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8104b655)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff8104b4d0-ffffffff8104b5bd: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff810573c5)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff81057220-ffffffff8105730d: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81058535)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff810582b0-ffffffff810583e4: __e820__mapped_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct e820_entry *__e820__mapped_all(u64 start, u64 end, enum e820_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff8105f7d5)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
Direct callers:
  - arch/x86/kernel/e820.c:e820__mapped_all
```
**Symbols:**

```
ffffffff8105f550-ffffffff8105f684: __e820__mapped_all (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81038f25)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff81028835)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff81038d85)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
In arch/x86/kernel/e820.c (ffffffff81039d85)
Location: arch/x86/kernel/e820.c:112
Inline: True
Inline callers:
  - arch/x86/kernel/e820.c:e820__get_entry_type
  - arch/x86/kernel/e820.c:e820__mapped_all
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
