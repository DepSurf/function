# Function: <code>__mmu_notifier_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3ca0)
Location: mm/mmu_notifier.c:325
Inline: False
```
**Symbols:**

```
ffffffff811e3ca0-ffffffff811e3cb2: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202740)
Location: mm/mmu_notifier.c:325
Inline: False
```
**Symbols:**

```
ffffffff81202740-ffffffff81202752: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81214580)
Location: mm/mmu_notifier.c:325
Inline: False
```
**Symbols:**

```
ffffffff81214580-ffffffff81214592: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121fa00)
Location: mm/mmu_notifier.c:306
Inline: False
```
**Symbols:**

```
ffffffff8121fa00-ffffffff8121fa12: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123ac10)
Location: mm/mmu_notifier.c:313
Inline: False
```
**Symbols:**

```
ffffffff8123ac10-ffffffff8123ac22: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125e2a0)
Location: mm/mmu_notifier.c:344
Inline: False
```
**Symbols:**

```
ffffffff8125e2a0-ffffffff8125e2b2: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81272b20)
Location: mm/mmu_notifier.c:315
Inline: False
```
**Symbols:**

```
ffffffff81272b20-ffffffff81272b32: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128e110)
Location: mm/mmu_notifier.c:313
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffff8128e110-ffffffff8128e122: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129db20)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8129db20-ffffffff8129dc28: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d21e0)
Location: mm/mmu_notifier.c:606
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_interval_notifier_insert
  - mm/mmu_notifier.c:mmu_notifier_get_locked
```
**Symbols:**

```
ffffffff812d21e0-ffffffff812d2349: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812ddc00)
Location: mm/mmu_notifier.c:629
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff812ddc00-ffffffff812ddd69: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e51b0)
Location: mm/mmu_notifier.c:629
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff812e51b0-ffffffff812e5319: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132ce10)
Location: mm/mmu_notifier.c:629
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8132ce10-ffffffff8132cf79: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139d010)
Location: mm/mmu_notifier.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8139d010-ffffffff8139d181: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141c460)
Location: mm/mmu_notifier.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8141c460-ffffffff8141c5d1: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8144fa10)
Location: mm/mmu_notifier.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8144fa10-ffffffff8144fb86: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *subscription, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff814896f0)
Location: mm/mmu_notifier.c:611
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - mm/mmu_notifier.c:mmu_interval_notifier_insert_locked
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff814896f0-ffffffff814898bd: __mmu_notifier_register (STB_GLOBAL)
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
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033cfc8)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffff80001033cfc8-ffff80001033d128: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c05433dc)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
c05433dc-c05434fc: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c000000000417f40)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
c000000000417f40-c0000000004180e8: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe0002325bc)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffe0002325bc-ffffffe0002326f8: __mmu_notifier_register (STB_GLOBAL)
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
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81296100)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff81296100-ffffffff81296208: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81287d10)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff81287d10-ffffffff81287e18: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81293f10)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff81293f10-ffffffff81294018: __mmu_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a3d30)
Location: mm/mmu_notifier.c:249
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_get_locked
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff812a3d30-ffffffff812a3e35: __mmu_notifier_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_notifier *subscription</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mmu_notifier *mn</code>
</li>
</ul>
</details>
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
