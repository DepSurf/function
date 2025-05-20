# Function: <code>mem_cgroup_id</code>

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
In mm/memcontrol.c (ffffffff811fa9f6)
Location: mm/memcontrol.c:272
Inline: True
Inline callers:
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811d41ec)
Location: include/linux/memcontrol.h:370
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812245c6)
Location: include/linux/memcontrol.h:370
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811e422c)
Location: include/linux/memcontrol.h:372
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81236b96)
Location: include/linux/memcontrol.h:372
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff811ee5fc)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81242657)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81204a6c)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81262497)
Location: include/linux/memcontrol.h:355
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8122581c)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8128656f)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81238d9c)
Location: include/linux/memcontrol.h:423
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8129b4c6)
Location: include/linux/memcontrol.h:423
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81249f9d)
Location: include/linux/memcontrol.h:424
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812b670b)
Location: include/linux/memcontrol.h:424
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812583ec)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812c85db)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81286acd)
Location: include/linux/memcontrol.h:435
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812fde9e)
Location: include/linux/memcontrol.h:435
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81290d2e)
Location: include/linux/memcontrol.h:755
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8130a305)
Location: include/linux/memcontrol.h:755
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8129636a)
Location: include/linux/memcontrol.h:834
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff81310b93)
Location: include/linux/memcontrol.h:834
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812d6afe)
Location: include/linux/memcontrol.h:830
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff8135be98)
Location: include/linux/memcontrol.h:830
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8133622e)
Location: include/linux/memcontrol.h:831
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff813d57ad)
Location: include/linux/memcontrol.h:831
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81382382)
Location: include/linux/memcontrol.h:813
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
```
```
In mm/workingset.c (ffffffff813ad4c5)
Location: include/linux/memcontrol.h:813
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_refault
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memcontrol.c (ffffffff8145b230)
Location: include/linux/memcontrol.h:813
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b3f01)
Location: include/linux/memcontrol.h:831
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
```
```
In mm/workingset.c (ffffffff813e18d2)
Location: include/linux/memcontrol.h:831
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memcontrol.c (ffffffff81490ea0)
Location: include/linux/memcontrol.h:831
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813dd581)
Location: include/linux/memcontrol.h:851
Inline: True
Inline callers:
  - mm/vmscan.c:run_cmd
  - mm/vmscan.c:lru_gen_seq_show
```
```
In mm/workingset.c (ffffffff8140c012)
Location: include/linux/memcontrol.h:851
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
  - mm/workingset.c:lru_gen_eviction
```
```
In mm/memcontrol.c (ffffffff814c080d)
Location: include/linux/memcontrol.h:851
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffff8000102f01d0)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffff80001036b4d8)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (c05138d0)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (c055cbcc)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (c0000000003b4b78)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (c00000000045aed8)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffe000203bca)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffe000248bba)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff81250a3c)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812c0bbb)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff812439bc)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812b1c47)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8124e7dc)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812be9cb)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (ffffffff8125e14c)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/workingset.c:workingset_eviction
```
```
In mm/memcontrol.c (ffffffff812cf43b)
Location: include/linux/memcontrol.h:458
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_swapout
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:get_mctgt_type
```
</details>
</li>
</ul>

## Differences
