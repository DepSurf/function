# Function: <code>type_merge</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 type_merge(u8 type, u8 new_type, u8 *uniform);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81082754)
Location: arch/x86/kernel/cpu/mtrr/generic.c:478
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_type_lookup
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_type_lookup
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_type_lookup
```
**Symbols:**

```
ffffffff81082030-ffffffff8108209a: type_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 type_merge(u8 type, u8 new_type, u8 *uniform);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff8108a264)
Location: arch/x86/kernel/cpu/mtrr/generic.c:482
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_type_lookup
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_type_lookup
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_type_lookup
```
**Symbols:**

```
ffffffff81089b40-ffffffff81089baa: type_merge (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
