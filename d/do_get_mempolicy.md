# Function: <code>do_get_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0f20)
Location: mm/mempolicy.c:830
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff811e0f20-ffffffff811e1298: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ff8f0)
Location: mm/mempolicy.c:862
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff811ff8f0-ffffffff811ffc83: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210f4e)
Location: mm/mempolicy.c:864
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121c8ce)
Location: mm/mempolicy.c:797
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81237a7e)
Location: mm/mempolicy.c:839
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125af53)
Location: mm/mempolicy.c:814
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126f716)
Location: mm/mempolicy.c:843
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128acf5)
Location: mm/mempolicy.c:870
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a865)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cdd40)
Location: mm/mempolicy.c:940
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff812cdd40-ffffffff812ce26e: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8c80)
Location: mm/mempolicy.c:939
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff812d8c80-ffffffff812d91ff: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0350)
Location: mm/mempolicy.c:949
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff812e0350-ffffffff812e09f5: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327750)
Location: mm/mempolicy.c:920
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff81327750-ffffffff81327cef: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81396850)
Location: mm/mempolicy.c:916
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff81396850-ffffffff81396edb: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814163a0)
Location: mm/mempolicy.c:930
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff814163a0-ffffffff81416a61: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814498b0)
Location: mm/mempolicy.c:935
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff814498b0-ffffffff81449f99: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int do_get_mempolicy(int *policy, nodemask_t *nmask, long unsigned int addr, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81483330)
Location: mm/mempolicy.c:889
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff81483330-ffffffff81483a2a: do_get_mempolicy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033941c)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413cf4)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292e45)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284a55)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290c55)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a0a85)
Location: mm/mempolicy.c:871
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
