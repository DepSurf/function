# Function: <code>xen_get_user_pgd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101df10)
Location: arch/x86/xen/mmu.c:521
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pgd_free
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
```
**Symbols:**

```
ffffffff8101df10-ffffffff8101df76: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101d300)
Location: arch/x86/xen/mmu.c:522
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pgd_free
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
```
**Symbols:**

```
ffffffff8101d300-ffffffff8101d36f: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8101da20)
Location: arch/x86/xen/mmu.c:522
Inline: False
Direct callers:
  - arch/x86/xen/mmu.c:xen_pgd_free
  - arch/x86/xen/mmu.c:xen_pgd_alloc
  - arch/x86/xen/mmu.c:xen_write_cr3
  - arch/x86/xen/mmu.c:__xen_pgd_unpin
  - arch/x86/xen/mmu.c:__xen_pgd_pin
  - arch/x86/xen/mmu.c:xen_set_pgd
```
**Symbols:**

```
ffffffff8101da20-ffffffff8101da8b: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff8101fd00)
Location: arch/x86/xen/mmu_pv.c:487
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff8101fd00-ffffffff8101fd6b: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020960)
Location: arch/x86/xen/mmu_pv.c:467
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81020960-ffffffff810209cb: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81021470)
Location: arch/x86/xen/mmu_pv.c:475
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81021470-ffffffff810214da: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81020ce0)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81020ce0-ffffffff81020d4a: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810227d0)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff810227d0-ffffffff81022843: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023110)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81023110-ffffffff81023183: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025980)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81025980-ffffffff81025a3c: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810260a0)
Location: arch/x86/xen/mmu_pv.c:442
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff810260a0-ffffffff8102615c: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81027fe0)
Location: arch/x86/xen/mmu_pv.c:442
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81027fe0-ffffffff8102807c: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:442
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff8102c640-ffffffff8102c717: xen_get_user_pgd (STB_LOCAL)
ffffffff81c9767b-ffffffff81c976d0: xen_get_user_pgd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:446
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff810313e0-ffffffff810314c3: xen_get_user_pgd (STB_LOCAL)
ffffffff81e46ad9-ffffffff81e46b2e: xen_get_user_pgd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:446
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81038b90-ffffffff81038c73: xen_get_user_pgd (STB_LOCAL)
ffffffff82051a8a-ffffffff82051adf: xen_get_user_pgd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:462
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81038ad0-ffffffff81038bb0: xen_get_user_pgd (STB_LOCAL)
ffffffff820cff76-ffffffff820cffca: xen_get_user_pgd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/mmu_pv.c (0)
Location: arch/x86/xen/mmu_pv.c:462
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff8103eee0-ffffffff8103efc0: xen_get_user_pgd (STB_LOCAL)
ffffffff821aa8e3-ffffffff821aa937: xen_get_user_pgd.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023270)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81023270-ffffffff810232e3: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810230d0)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff810230d0-ffffffff81023143: xen_get_user_pgd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pgd_t *xen_get_user_pgd(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81023540)
Location: arch/x86/xen/mmu_pv.c:484
Inline: False
Direct callers:
  - arch/x86/xen/mmu_pv.c:xen_pgd_free
  - arch/x86/xen/mmu_pv.c:xen_pgd_alloc
  - arch/x86/xen/mmu_pv.c:xen_write_cr3
  - arch/x86/xen/mmu_pv.c:__xen_pgd_unpin
  - arch/x86/xen/mmu_pv.c:__xen_pgd_pin
  - arch/x86/xen/mmu_pv.c:xen_set_p4d
```
**Symbols:**

```
ffffffff81023540-ffffffff810235b3: xen_get_user_pgd (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
