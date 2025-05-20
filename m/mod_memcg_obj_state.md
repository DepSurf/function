# Function: <code>mod_memcg_obj_state</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6f60)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffff812c6f60-ffffffff812c6fae: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc950)
Location: mm/memcontrol.c:779
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffff812fc950-ffffffff812fc9a3: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369d20)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffff800010369d20-ffff800010369d8c: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b078)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
c055b078-c055b0bc: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0000000004588c0)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
c0000000004588c0-c00000000045893c: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002475a0)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffe0002475a0-ffffffe0002475ee: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bf540)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffff812bf540-ffffffff812bf58e: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0630)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffff812b0630-ffffffff812b0668: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd350)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffff812bd350-ffffffff812bd39e: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mod_memcg_obj_state(void *p, int idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cdbb0)
Location: mm/memcontrol.c:789
Inline: False
Direct callers:
  - kernel/fork.c:account_kernel_stack
```
**Symbols:**

```
ffffffff812cdbb0-ffffffff812cdc10: mod_memcg_obj_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
