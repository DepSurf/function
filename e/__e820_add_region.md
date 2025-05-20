# Function: <code>__e820_add_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __e820_add_region(struct e820map *e820x, u64 start, u64 size, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67860)
Location: arch/x86/kernel/e820.c:111
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:e820_add_region
```
**Symbols:**

```
ffffffff81f67860-ffffffff81f6789f: __e820_add_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __e820_add_region(struct e820map *e820x, u64 start, u64 size, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8f70a)
Location: arch/x86/kernel/e820.c:111
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:e820_add_region
```
**Symbols:**

```
ffffffff81f8f70a-ffffffff81f8f749: __e820_add_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __e820_add_region(struct e820map *e820x, u64 start, u64 size, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fcaa62)
Location: arch/x86/kernel/e820.c:113
Inline: True
Direct callers:
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:__e820_update_range
  - arch/x86/kernel/e820.c:e820_add_region
```
**Symbols:**

```
ffffffff81fcaa62-ffffffff81fcaaa1: __e820_add_region (STB_LOCAL)
```
</details>
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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
