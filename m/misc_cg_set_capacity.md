# Function: <code>misc_cg_set_capacity</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int misc_cg_set_capacity(enum misc_res_type type, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff81180c60)
Location: kernel/cgroup/misc.c:98
Inline: False
```
**Symbols:**

```
ffffffff81180c60-ffffffff81180c83: misc_cg_set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int misc_cg_set_capacity(enum misc_res_type type, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff811a8a60)
Location: kernel/cgroup/misc.c:98
Inline: False
```
**Symbols:**

```
ffffffff811a8a60-ffffffff811a8aa2: misc_cg_set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int misc_cg_set_capacity(enum misc_res_type type, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff811d9c30)
Location: kernel/cgroup/misc.c:98
Inline: False
```
**Symbols:**

```
ffffffff811d9c30-ffffffff811d9c82: misc_cg_set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int misc_cg_set_capacity(enum misc_res_type type, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff8121f130)
Location: kernel/cgroup/misc.c:98
Inline: False
```
**Symbols:**

```
ffffffff8121f130-ffffffff8121f182: misc_cg_set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int misc_cg_set_capacity(enum misc_res_type type, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff81235260)
Location: kernel/cgroup/misc.c:98
Inline: False
```
**Symbols:**

```
ffffffff81235260-ffffffff812352b2: misc_cg_set_capacity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int misc_cg_set_capacity(enum misc_res_type type, u64 capacity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff8124eeb0)
Location: kernel/cgroup/misc.c:98
Inline: False
```
**Symbols:**

```
ffffffff8124eeb0-ffffffff8124ef02: misc_cg_set_capacity (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int capacity</code> ➡️ <code>u64 capacity</code>
</li>
</ul>
</details>
</li>
</ul>
