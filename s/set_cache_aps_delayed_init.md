# Function: <code>set_cache_aps_delayed_init</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_cache_aps_delayed_init(bool val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ae9b)
Location: arch/x86/kernel/cpu/cacheinfo.c:1145
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
Direct callers:
  - arch/x86/kernel/smpboot.c:arch_thaw_secondary_cpus_begin
```
**Symbols:**

```
ffffffff8106ada0-ffffffff8106adb8: set_cache_aps_delayed_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_cache_aps_delayed_init(bool val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c80b)
Location: arch/x86/kernel/cpu/cacheinfo.c:1144
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
Direct callers:
  - arch/x86/kernel/smpboot.c:arch_thaw_secondary_cpus_begin
```
**Symbols:**

```
ffffffff8106c710-ffffffff8106c728: set_cache_aps_delayed_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_cache_aps_delayed_init(bool val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073a5b)
Location: arch/x86/kernel/cpu/cacheinfo.c:1138
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
Direct callers:
  - arch/x86/kernel/smpboot.c:arch_thaw_secondary_cpus_begin
```
**Symbols:**

```
ffffffff81073960-ffffffff81073978: set_cache_aps_delayed_init (STB_GLOBAL)
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
