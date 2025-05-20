# Function: <code>swap_cgroup_record</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81200b10)
Location: mm/swap_cgroup.c:115
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
```
**Symbols:**

```
ffffffff81200b10-ffffffff81200ba1: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81225290)
Location: mm/swap_cgroup.c:115
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff81225290-ffffffff8122531d: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81237880)
Location: mm/swap_cgroup.c:115
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff81237880-ffffffff8123790a: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81243450)
Location: mm/swap_cgroup.c:125
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff81243450-ffffffff8124354b: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812632a0)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812632a0-ffffffff8126339b: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81287580)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff81287580-ffffffff8128767b: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff8129c4d0)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff8129c4d0-ffffffff8129c5cb: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812b7670)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812b7670-ffffffff812b777d: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812c9550)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812c9550-ffffffff812c965d: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812febc0)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812febc0-ffffffff812feccf: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff8130af00)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff8130af00-ffffffff8130b00f: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81311560)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff81311560-ffffffff8131166f: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff8135c880)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff8135c880-ffffffff8135c9c4: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff813d6530)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff813d6530-ffffffff813d6679: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff8145bfd0)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff8145bfd0-ffffffff8145c119: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff81491c70)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff81491c70-ffffffff81491db9: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff814c1680)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff814c1680-ffffffff814c17c9: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffff80001036cba8)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffff80001036cba8-ffff80001036cd0c: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (c055db50)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
c055db50-c055dc40: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (c00000000045cac0)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
c00000000045cac0-c00000000045cc14: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffe000249a64)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffe000249a64-ffffffe000249b6e: swap_cgroup_record (STB_GLOBAL)
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
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812c1b30)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812c1b30-ffffffff812c1c3d: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812b2b80)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812b2b80-ffffffff812b2c8d: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812bf940)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812bf940-ffffffff812bfa4d: swap_cgroup_record (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
short unsigned int swap_cgroup_record(swp_entry_t ent, short unsigned int id, unsigned int nr_ents);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_cgroup.c (ffffffff812d03a0)
Location: mm/swap_cgroup.c:126
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
```
**Symbols:**

```
ffffffff812d03a0-ffffffff812d04ad: swap_cgroup_record (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_ents</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
