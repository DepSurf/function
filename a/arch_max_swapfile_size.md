# Function: <code>arch_max_swapfile_size</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_max_swapfile_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81400aa0)
Location: arch/x86/mm/init.c:1061
Inline: False
Direct callers:
  - mm/swapfile.c:swapfile_init
```
**Symbols:**

```
ffffffff820547b8-ffffffff820547df: arch_max_swapfile_size.cold (STB_LOCAL)
ffffffff810c1040-ffffffff810c10a9: arch_max_swapfile_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_max_swapfile_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81433990)
Location: arch/x86/mm/init.c:1091
Inline: False
Direct callers:
  - mm/swapfile.c:swapfile_init
```
**Symbols:**

```
ffffffff820d2dc6-ffffffff820d2ded: arch_max_swapfile_size.cold (STB_LOCAL)
ffffffff810c4720-ffffffff810c4788: arch_max_swapfile_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_max_swapfile_size();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8146cd80)
Location: arch/x86/mm/init.c:1081
Inline: False
Direct callers:
  - mm/swapfile.c:swapfile_init
```
**Symbols:**

```
ffffffff821adc3c-ffffffff821adc63: arch_max_swapfile_size.cold (STB_LOCAL)
ffffffff810ccb70-ffffffff810ccbd9: arch_max_swapfile_size (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
