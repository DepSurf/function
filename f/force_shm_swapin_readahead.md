# Function: <code>force_shm_swapin_readahead</code>

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
In mm/madvise.c (ffffffff811d1ace)
Location: mm/madvise.c:189
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ef555)
Location: mm/madvise.c:193
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
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
In mm/madvise.c (ffffffff811ffed5)
Location: mm/madvise.c:193
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
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
In mm/madvise.c (ffffffff81209fb7)
Location: mm/madvise.c:230
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff8122319d)
Location: mm/madvise.c:242
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81244d49)
Location: mm/madvise.c:242
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81259399)
Location: mm/madvise.c:242
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81274bcd)
Location: mm/madvise.c:242
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff8128424b)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812b6192)
Location: mm/madvise.c:223
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void force_shm_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c0f70)
Location: mm/madvise.c:224
Inline: False
```
**Symbols:**

```
ffffffff812c0f70-ffffffff812c11aa: force_shm_swapin_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void force_shm_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff812c7d80)
Location: mm/madvise.c:224
Inline: False
```
**Symbols:**

```
ffffffff812c7d80-ffffffff812c7fb2: force_shm_swapin_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void force_shm_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8130cb40)
Location: mm/madvise.c:226
Inline: False
```
**Symbols:**

```
ffffffff8130cb40-ffffffff8130cd82: force_shm_swapin_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void force_shm_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff81376070)
Location: mm/madvise.c:236
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff81376070-ffffffff8137635f: force_shm_swapin_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void force_shm_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct address_space *mapping);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff813f39c0)
Location: mm/madvise.c:235
Inline: False
Direct callers:
  - mm/madvise.c:madvise_vma_behavior
```
**Symbols:**

```
ffffffff813f39c0-ffffffff813f3ca9: force_shm_swapin_readahead (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffff80001031e698)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c05385b4)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f2888)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffe000221566)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
```
</details>
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
In mm/madvise.c (ffffffff8127c89b)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8126e74b)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8127a63b)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8128a21b)
Location: mm/madvise.c:222
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
