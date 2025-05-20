# Function: <code>get_cache_aps_delayed_init</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool get_cache_aps_delayed_init();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106ae6c)
Location: arch/x86/kernel/cpu/cacheinfo.c:1150
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
```
**Symbols:**

```
ffffffff82052849-ffffffff82052873: get_cache_aps_delayed_init.cold (STB_LOCAL)
ffffffff8106add0-ffffffff8106adf2: get_cache_aps_delayed_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool get_cache_aps_delayed_init();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c7dc)
Location: arch/x86/kernel/cpu/cacheinfo.c:1149
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_online
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
```
**Symbols:**

```
ffffffff820d0d04-ffffffff820d0d2e: get_cache_aps_delayed_init.cold (STB_LOCAL)
ffffffff8106c740-ffffffff8106c762: get_cache_aps_delayed_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool get_cache_aps_delayed_init();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073a2c)
Location: arch/x86/kernel/cpu/cacheinfo.c:1143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_aps_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_ap_online
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
```
**Symbols:**

```
ffffffff821ab828-ffffffff821ab852: get_cache_aps_delayed_init.cold (STB_LOCAL)
ffffffff81073990-ffffffff810739b2: get_cache_aps_delayed_init (STB_GLOBAL)
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
