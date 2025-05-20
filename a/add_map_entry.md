# Function: <code>add_map_entry</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_map_entry(u64 start, u64 end, u8 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff810820b0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_build_map
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_build_map
  - arch/x86/kernel/cpu/mtrr/generic.c:map_add_var
  - arch/x86/kernel/cpu/mtrr/generic.c:map_add_var
```
**Symbols:**

```
ffffffff810820b0-ffffffff81082282: add_map_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_map_entry(u64 start, u64 end, u8 type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/generic.c (ffffffff81089bc0)
Location: arch/x86/kernel/cpu/mtrr/generic.c:262
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_build_map
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_build_map
  - arch/x86/kernel/cpu/mtrr/generic.c:map_add_var
  - arch/x86/kernel/cpu/mtrr/generic.c:map_add_var
```
**Symbols:**

```
ffffffff81089bc0-ffffffff81089d92: add_map_entry (STB_LOCAL)
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
