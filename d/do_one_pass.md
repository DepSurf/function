# Function: <code>do_one_pass</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff81f8d1e7)
Location: mm/memtest.c:65
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff812eb890)
Location: fs/jbd2/recovery.c:420
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
```
**Symbols:**

```
ffffffff812eb890-ffffffff812ec660: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff81fb722a)
Location: mm/memtest.c:65
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff813193a0)
Location: fs/jbd2/recovery.c:419
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813193a0-ffffffff8131a0cc: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff81ff3ba3)
Location: mm/memtest.c:65
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff8132f390)
Location: fs/jbd2/recovery.c:419
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff8132f390-ffffffff813300bc: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff820d6371)
Location: mm/memtest.c:65
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff81344420)
Location: fs/jbd2/recovery.c:419
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81344420-ffffffff81344fd4: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff826defdf)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff81368ac0)
Location: fs/jbd2/recovery.c:419
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81368ac0-ffffffff81369674: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff82709540)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813972f0-ffffffff81397ca4: do_one_pass (STB_LOCAL)
ffffffff81397eff-ffffffff81397ff7: do_one_pass.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828c07e2)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813b0020-ffffffff813b0a2c: do_one_pass (STB_LOCAL)
ffffffff813b0c7f-ffffffff813b0d74: do_one_pass.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828d9b61)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813da5c0-ffffffff813dafd4: do_one_pass (STB_LOCAL)
ffffffff813db226-ffffffff813db322: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828e2008)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813f4610-ffffffff813f5024: do_one_pass (STB_LOCAL)
ffffffff813f5276-ffffffff813f5372: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff82cff3e9)
Location: mm/memtest.c:66
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff82cff3e9-ffffffff82cff592: do_one_pass (STB_LOCAL)
ffffffff81441be0-ffffffff814423cf: do_one_pass (STB_LOCAL)
ffffffff81442621-ffffffff814426f5: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff82febd95)
Location: mm/memtest.c:66
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:456
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff82febd95-ffffffff82febf3e: do_one_pass (STB_LOCAL)
ffffffff8145de00-ffffffff8145e738: do_one_pass (STB_LOCAL)
ffffffff81becdac-ffffffff81becec7: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff831f65f6)
Location: mm/memtest.c:66
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:455
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff831f65f6-ffffffff831f679d: do_one_pass (STB_LOCAL)
ffffffff814634a0-ffffffff81463fdf: do_one_pass (STB_LOCAL)
ffffffff81bdee51-ffffffff81bdefab: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff832dd08b)
Location: mm/memtest.c:66
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:455
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff832dd08b-ffffffff832dd232: do_one_pass (STB_LOCAL)
ffffffff814b8a20-ffffffff814b95b3: do_one_pass (STB_LOCAL)
ffffffff81cce695-ffffffff81cce7f5: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff8349287a)
Location: mm/memtest.c:66
Inline: False
Direct callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:455
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff8349287a-ffffffff83492a07: do_one_pass (STB_LOCAL)
ffffffff815425d0-ffffffff81543260: do_one_pass (STB_LOCAL)
ffffffff81e81748-ffffffff81e8189d: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff83ec662a)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff815e1300)
Location: fs/jbd2/recovery.c:461
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff815e1300-ffffffff815e20d3: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff836eb5ba)
Location: mm/memtest.c:72
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff81618bf0)
Location: fs/jbd2/recovery.c:467
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81618bf0-ffffffff81619a32: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffff8391e22a)
Location: mm/memtest.c:73
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffff81651b70)
Location: fs/jbd2/recovery.c:466
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff81651b70-ffffffff81652934: do_one_pass (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffff80001145b1c0)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffff8000104cff78)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffff8000104cff78-ffff8000104d0ae0: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (c1533d60)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (c0692a50)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
c0692a50-c06936a8: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (c0000000013857b0)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (c000000000608f40)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
c000000000608f40-c000000000609c4c: do_one_pass (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memtest.c (ffffffe000019180)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (ffffffe000347560)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffe000347560-ffffffe00034810c: do_one_pass (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828caebc)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813ecbf0-ffffffff813ed604: do_one_pass (STB_LOCAL)
ffffffff813ed856-ffffffff813ed952: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828c35e1)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813dd670-ffffffff813de084: do_one_pass (STB_LOCAL)
ffffffff813de2d6-ffffffff813de3d2: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828ddc3c)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813e9f70-ffffffff813ea984: do_one_pass (STB_LOCAL)
ffffffff813eabd6-ffffffff813eacd2: do_one_pass.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
void do_one_pass(u64 pattern, phys_addr_t start, phys_addr_t end);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memtest.c (ffffffff828e3053)
Location: mm/memtest.c:66
Inline: True
Inline callers:
  - mm/memtest.c:early_memtest
```
```
In fs/jbd2/recovery.c (0)
Location: fs/jbd2/recovery.c:416
Inline: False
Direct callers:
  - fs/jbd2/recovery.c:jbd2_journal_skip_recovery
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
  - fs/jbd2/recovery.c:jbd2_journal_recover
```
**Symbols:**

```
ffffffff813ff8b0-ffffffff814002e9: do_one_pass (STB_LOCAL)
ffffffff81400536-ffffffff81400632: do_one_pass.cold (STB_LOCAL)
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
