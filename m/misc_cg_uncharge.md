# Function: <code>misc_cg_uncharge</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void misc_cg_uncharge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff81181140)
Location: kernel/cgroup/misc.c:189
Inline: True
```
**Symbols:**

```
ffffffff81181140-ffffffff811811cb: misc_cg_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_uncharge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:189
Inline: True
```
**Symbols:**

```
ffffffff81cb332e-ffffffff81cb334b: misc_cg_uncharge.cold (STB_LOCAL)
ffffffff811a9080-ffffffff811a913d: misc_cg_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_uncharge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:187
Inline: True
```
**Symbols:**

```
ffffffff81e64128-ffffffff81e6413d: misc_cg_uncharge.cold (STB_LOCAL)
ffffffff811da320-ffffffff811da3e8: misc_cg_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_uncharge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:187
Inline: True
```
**Symbols:**

```
ffffffff8205c46a-ffffffff8205c47f: misc_cg_uncharge.cold (STB_LOCAL)
ffffffff8121f8c0-ffffffff8121f988: misc_cg_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_uncharge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:187
Inline: True
```
**Symbols:**

```
ffffffff820dadbe-ffffffff820daddb: misc_cg_uncharge.cold (STB_LOCAL)
ffffffff81235a80-ffffffff81235b80: misc_cg_uncharge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_uncharge(enum misc_res_type type, struct misc_cg *cg, u64 amount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (0)
Location: kernel/cgroup/misc.c:186
Inline: True
```
**Symbols:**

```
ffffffff821b6abc-ffffffff821b6ad9: misc_cg_uncharge.cold (STB_LOCAL)
ffffffff8124f700-ffffffff8124f800: misc_cg_uncharge (STB_GLOBAL)
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
