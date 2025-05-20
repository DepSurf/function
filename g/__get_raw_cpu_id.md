# Function: <code>__get_raw_cpu_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 __get_raw_cpu_id(u64 ctx, u64 a, u64 x, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817309e0)
Location: net/core/filter.c:147
Inline: False
```
**Symbols:**

```
ffffffff817309e0-ffffffff817309f4: __get_raw_cpu_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 __get_raw_cpu_id(u64 ctx, u64 a, u64 x, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179b180)
Location: net/core/filter.c:148
Inline: False
```
**Symbols:**

```
ffffffff8179b180-ffffffff8179b194: __get_raw_cpu_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 __get_raw_cpu_id(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817c8f20)
Location: net/core/filter.c:151
Inline: False
```
**Symbols:**

```
ffffffff817c8f20-ffffffff817c8f34: __get_raw_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 __get_raw_cpu_id(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e7ad0)
Location: net/core/filter.c:160
Inline: False
```
**Symbols:**

```
ffffffff817e7ad0-ffffffff817e7ae4: __get_raw_cpu_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 __get_raw_cpu_id(u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4, u64 __ur_5);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81862a10)
Location: net/core/filter.c:162
Inline: False
```
**Symbols:**

```
ffffffff81862a10-ffffffff81862a24: __get_raw_cpu_id (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_4</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_5</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 a</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 x</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
