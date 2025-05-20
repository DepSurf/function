# Function: <code>misc_cg_try_charge</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int misc_cg_try_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:140
Inline: True
```
**Symbols:**

```
ffffffff81bd66b7-ffffffff81bd66f9: misc_cg_try_charge.cold (STB_LOCAL)
ffffffff81180fb0-ffffffff811810ce: misc_cg_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int misc_cg_try_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:140
Inline: True
```
**Symbols:**

```
ffffffff81cb3311-ffffffff81cb332e: misc_cg_try_charge.cold (STB_LOCAL)
ffffffff811a8e00-ffffffff811a9007: misc_cg_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int misc_cg_try_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff811da0f0)
Location: kernel/cgroup/misc.c:140
Inline: False
```
**Symbols:**

```
ffffffff811da0f0-ffffffff811da29f: misc_cg_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int misc_cg_try_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff8121f670)
Location: kernel/cgroup/misc.c:140
Inline: False
```
**Symbols:**

```
ffffffff8121f670-ffffffff8121f81f: misc_cg_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int misc_cg_try_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff812357c0)
Location: kernel/cgroup/misc.c:140
Inline: False
```
**Symbols:**

```
ffffffff812357c0-ffffffff812359de: misc_cg_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int misc_cg_try_charge(enum misc_res_type type, struct misc_cg *cg, u64 amount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff8124f410)
Location: kernel/cgroup/misc.c:140
Inline: False
```
**Symbols:**

```
ffffffff8124f410-ffffffff8124f62b: misc_cg_try_charge (STB_GLOBAL)
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
<code>long unsigned int amount</code> ➡️ <code>u64 amount</code>
</li>
</ul>
</details>
</li>
</ul>
