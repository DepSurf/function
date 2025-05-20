# Function: <code>cache_enable</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void cache_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ac40)
Location: arch/x86/kernel/cpu/cacheinfo.c:1107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_cpu_init
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
```
**Symbols:**

```
ffffffff8106ac40-ffffffff8106aca7: cache_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cache_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c5b0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1106
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_cpu_init
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
```
**Symbols:**

```
ffffffff8106c5b0-ffffffff8106c617: cache_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cache_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073800)
Location: arch/x86/kernel/cpu/cacheinfo.c:1100
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_cpu_init
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
  - arch/x86/kernel/cpu/mtrr/generic.c:generic_set_mtrr
```
**Symbols:**

```
ffffffff81073800-ffffffff81073867: cache_enable (STB_GLOBAL)
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
