# Function: <code>__zswap_cpu_comp_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __zswap_cpu_comp_notifier(struct zswap_pool *pool, long unsigned int action, long unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zswap.c (ffffffff811d7c90)
Location: mm/zswap.c:419
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
Direct callers:
  - mm/zswap.c:zswap_cpu_comp_notifier
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
```
**Symbols:**

```
ffffffff811d7c90-ffffffff811d7d31: __zswap_cpu_comp_notifier.part.6 (STB_LOCAL)
ffffffff811d7d40-ffffffff811d7dcf: __zswap_cpu_comp_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __zswap_cpu_comp_notifier(struct zswap_pool *pool, long unsigned int action, long unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/zswap.c (ffffffff811f6111)
Location: mm/zswap.c:421
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_create
Direct callers:
  - mm/zswap.c:__zswap_pool_release
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_cpu_comp_notifier
```
**Symbols:**

```
ffffffff811f5d90-ffffffff811f5e31: __zswap_cpu_comp_notifier.part.8 (STB_LOCAL)
ffffffff811f5e40-ffffffff811f5ecf: __zswap_cpu_comp_notifier (STB_LOCAL)
```
</details>
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
</ul>
