# Function: <code>misc_cg_cancel_charge</code>

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
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff81180f60)
Location: kernel/cgroup/misc.c:116
Inline: True
```
**Symbols:**

```
ffffffff81180f60-ffffffff81180fa6: misc_cg_cancel_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff811a8da5)
Location: kernel/cgroup/misc.c:116
Inline: True
```
**Symbols:**

```
ffffffff811a8d80-ffffffff811a8df3: misc_cg_cancel_charge (STB_LOCAL)
ffffffff81cb32fc-ffffffff81cb3311: misc_cg_cancel_charge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff811da36e)
Location: kernel/cgroup/misc.c:116
Inline: True
Direct callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
**Symbols:**

```
ffffffff811da060-ffffffff811da0ee: misc_cg_cancel_charge (STB_LOCAL)
ffffffff81e64113-ffffffff81e64128: misc_cg_cancel_charge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff8121f90e)
Location: kernel/cgroup/misc.c:116
Inline: True
Direct callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
**Symbols:**

```
ffffffff8121f5d0-ffffffff8121f65e: misc_cg_cancel_charge (STB_LOCAL)
ffffffff8205c455-ffffffff8205c46a: misc_cg_cancel_charge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg *cg, long unsigned int amount);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff81235757)
Location: kernel/cgroup/misc.c:116
Inline: True
Direct callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
**Symbols:**

```
ffffffff81235700-ffffffff812357a6: misc_cg_cancel_charge (STB_LOCAL)
ffffffff820dadaa-ffffffff820dadbe: misc_cg_cancel_charge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void misc_cg_cancel_charge(enum misc_res_type type, struct misc_cg *cg, u64 amount);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cgroup/misc.c (ffffffff8124f3a7)
Location: kernel/cgroup/misc.c:116
Inline: True
Direct callers:
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
  - kernel/cgroup/misc.c:misc_cg_try_charge
```
**Symbols:**

```
ffffffff8124f350-ffffffff8124f3f6: misc_cg_cancel_charge (STB_LOCAL)
ffffffff821b6aa8-ffffffff821b6abc: misc_cg_cancel_charge.cold (STB_LOCAL)
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
