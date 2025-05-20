# Function: <code>cache_cpu_init</code>

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
void cache_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106acc0)
Location: arch/x86/kernel/cpu/cacheinfo.c:1126
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_restore
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
```
**Symbols:**

```
ffffffff8106acc0-ffffffff8106ad26: cache_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cache_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff8106c630)
Location: arch/x86/kernel/cpu/cacheinfo.c:1125
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_restore
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
```
**Symbols:**

```
ffffffff8106c630-ffffffff8106c696: cache_cpu_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cache_cpu_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/cacheinfo.c (ffffffff81073880)
Location: arch/x86/kernel/cpu/cacheinfo.c:1119
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_restore
  - arch/x86/kernel/cpu/cacheinfo.c:cache_bp_init
  - arch/x86/kernel/cpu/cacheinfo.c:cache_rendezvous_handler
```
**Symbols:**

```
ffffffff81073880-ffffffff810738e6: cache_cpu_init (STB_LOCAL)
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
