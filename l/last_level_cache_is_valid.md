# Function: <code>last_level_cache_is_valid</code>

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
bool last_level_cache_is_valid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81af7780)
Location: drivers/base/cacheinfo.c:54
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:last_level_cache_is_shared
  - drivers/base/cacheinfo.c:last_level_cache_is_shared
```
**Symbols:**

```
ffffffff81af7780-ffffffff81af7885: last_level_cache_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool last_level_cache_is_valid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b45ad0)
Location: drivers/base/cacheinfo.c:57
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:last_level_cache_is_shared
  - drivers/base/cacheinfo.c:last_level_cache_is_shared
```
**Symbols:**

```
ffffffff81b45ad0-ffffffff81b45bd5: last_level_cache_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool last_level_cache_is_valid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/cacheinfo.c (ffffffff81b9dac0)
Location: drivers/base/cacheinfo.c:57
Inline: False
Direct callers:
  - drivers/base/cacheinfo.c:update_per_cpu_data_slice_size
  - drivers/base/cacheinfo.c:cache_shared_cpu_map_setup
  - drivers/base/cacheinfo.c:last_level_cache_is_shared
  - drivers/base/cacheinfo.c:last_level_cache_is_shared
```
**Symbols:**

```
ffffffff81b9dac0-ffffffff81b9dbf9: last_level_cache_is_valid (STB_GLOBAL)
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
