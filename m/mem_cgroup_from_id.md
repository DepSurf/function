# Function: <code>mem_cgroup_from_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812001d5)
Location: mm/memcontrol.c:283
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8122464c)
Location: mm/memcontrol.c:4125
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81223e20-ffffffff81223e5b: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236c1c)
Location: mm/memcontrol.c:4100
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81236310-ffffffff8123634b: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812426e3)
Location: mm/memcontrol.c:4120
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81241e20-ffffffff81241e3a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262523)
Location: mm/memcontrol.c:4147
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81261b50-ffffffff81261b6a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286692)
Location: mm/memcontrol.c:4081
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81285ab0-ffffffff81285aca: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129b602)
Location: mm/memcontrol.c:4354
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8129a9c0-ffffffff8129a9da: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6845)
Location: mm/memcontrol.c:4694
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812b5c60-ffffffff812b5c7a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8715)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812c7b50-ffffffff812c7b6a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fdfda)
Location: mm/memcontrol.c:4896
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812fd5e0-ffffffff812fd5fa: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130a46a)
Location: mm/memcontrol.c:5158
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81309a20-ffffffff81309a3a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310d0a)
Location: mm/memcontrol.c:4926
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff81310070-ffffffff8131008a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135bfda)
Location: mm/memcontrol.c:5093
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8135b3c0-ffffffff8135b3da: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d5931)
Location: mm/memcontrol.c:5057
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_page
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff813d4af0-ffffffff813d4b12: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145b391)
Location: mm/memcontrol.c:5178
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
Direct callers:
  - mm/vmscan.c:run_cmd
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff8145a550-ffffffff8145a572: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81491001)
Location: mm/memcontrol.c:5205
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
Direct callers:
  - mm/vmscan.c:run_cmd
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:lru_gen_refault
```
**Symbols:**

```
ffffffff814901b0-ffffffff814901d2: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c096f)
Location: mm/memcontrol.c:5402
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_swapin_charge_folio
Direct callers:
  - mm/vmscan.c:run_cmd
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:workingset_test_recent
  - mm/workingset.c:lru_gen_refault
```
**Symbols:**

```
ffffffff814bf9c0-ffffffff814bf9e2: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b608)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffff80001036aa08-ffff80001036aa40: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055cd28)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
c055c010-c055c038: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045b0f8)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
c000000000459d50-c000000000459d90: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248cdc)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffe000248204-ffffffe000248236: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0cf5)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812c0130-ffffffff812c014a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1d65)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812b1200-ffffffff812b121a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812beb05)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812bdf40-ffffffff812bdf5a: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *mem_cgroup_from_id(short unsigned int id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cf57d)
Location: mm/memcontrol.c:5014
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge
Direct callers:
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff812ce8e0-ffffffff812ce8fa: mem_cgroup_from_id (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
