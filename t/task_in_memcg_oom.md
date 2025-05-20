# Function: <code>task_in_memcg_oom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/memcontrol.h:422
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:422
Inline: True
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
In mm/memory.c (0)
Location: include/linux/memcontrol.h:464
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:464
Inline: True
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
In mm/memory.c (0)
Location: include/linux/memcontrol.h:482
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:482
Inline: True
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
In mm/memory.c (0)
Location: include/linux/memcontrol.h:476
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:476
Inline: True
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
In mm/memory.c (0)
Location: include/linux/memcontrol.h:476
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:476
Inline: True
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
In mm/memory.c (ffffffff812303d2)
Location: include/linux/memcontrol.h:509
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff8128186e)
Location: include/linux/memcontrol.h:509
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff81242d82)
Location: include/linux/memcontrol.h:546
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff8129884c)
Location: include/linux/memcontrol.h:546
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff81254c0b)
Location: include/linux/memcontrol.h:536
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812b3cc2)
Location: include/linux/memcontrol.h:536
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff81263117)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812c55bf)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff81294f6e)
Location: include/linux/memcontrol.h:549
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812fb278)
Location: include/linux/memcontrol.h:549
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff8129f869)
Location: include/linux/memcontrol.h:867
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff81307079)
Location: include/linux/memcontrol.h:867
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff812a486c)
Location: include/linux/memcontrol.h:946
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff8130d70d)
Location: include/linux/memcontrol.h:946
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff812e5b2e)
Location: include/linux/memcontrol.h:937
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff81358448)
Location: include/linux/memcontrol.h:937
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
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
In mm/memory.c (ffffffff81347e0e)
Location: include/linux/memcontrol.h:936
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff813d22c5)
Location: include/linux/memcontrol.h:936
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
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
In mm/memory.c (ffffffff813c02c4)
Location: include/linux/memcontrol.h:927
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff81457a0a)
Location: include/linux/memcontrol.h:927
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
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
In mm/memory.c (ffffffff813f4f80)
Location: include/linux/memcontrol.h:945
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff8148d73a)
Location: include/linux/memcontrol.h:945
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
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
In mm/memory.c (ffffffff81421641)
Location: include/linux/memcontrol.h:964
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff814bd0ba)
Location: include/linux/memcontrol.h:964
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
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
In mm/memory.c (ffff8000102fa420)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffff800010368434)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (c051bed0)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (c0559880)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (c0000000003c45d0)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (c000000000456168)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffe000209bb8)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffe000246176)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff8125b767)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812bdb9f)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff8124dd31)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812aecd7)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff81259507)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812bb9af)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In mm/memory.c (ffffffff81268f11)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/memcontrol.c (ffffffff812cc13d)
Location: include/linux/memcontrol.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
```
</details>
</li>
</ul>

## Differences
