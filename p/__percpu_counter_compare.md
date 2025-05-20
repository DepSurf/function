# Function: <code>__percpu_counter_compare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81411ca0)
Location: lib/percpu_counter.c:200
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_getpage_gfp
```
**Symbols:**

```
ffffffff81411ca0-ffffffff81411d1f: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81459a00)
Location: lib/percpu_counter.c:200
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff81459a00-ffffffff81459a7b: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814784a0)
Location: lib/percpu_counter.c:196
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff814784a0-ffffffff8147851c: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814817e0)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff814817e0-ffffffff8148185c: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814bd620)
Location: lib/percpu_counter.c:203
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff814bd620-ffffffff814bd69c: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff814efe80)
Location: lib/percpu_counter.c:203
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff814efe80-ffffffff814efefa: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81503da0)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff81503da0-ffffffff81503e1a: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81531f10)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_remount_fs
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff81531f10-ffffffff81531f8a: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81552c60)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff81552c60-ffffffff81552cb4: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc040)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff815dc040-ffffffff815dc09a: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815f9ce0)
Location: lib/percpu_counter.c:221
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff815f9ce0-ffffffff815f9d3a: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc8c0)
Location: lib/percpu_counter.c:221
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff815dc8c0-ffffffff815dc917: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81648200)
Location: lib/percpu_counter.c:221
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff81648200-ffffffff81648257: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8175e510)
Location: lib/percpu_counter.c:221
Inline: False
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_charge
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff8175e510-ffffffff8175e57f: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8188bce0)
Location: lib/percpu_counter.c:238
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_charge
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff8188bce0-ffffffff8188bd56: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff818ce2c0)
Location: lib/percpu_counter.c:234
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_folio
  - mm/shmem.c:shmem_charge
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff818ce2c0-ffffffff818ce32f: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8191fef0)
Location: lib/percpu_counter.c:258
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - mm/shmem.c:shmem_reconfigure
  - fs/eventpoll.c:ep_insert
```
**Symbols:**

```
ffffffff8191fef0-ffffffff8191ff5f: __percpu_counter_compare (STB_GLOBAL)
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
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffff80001065ee90)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffff80001065ee90-ffff80001065eef8: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c08084bc)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
c08084bc-c080855c: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (c000000000811650)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
c000000000811650-c000000000811710: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffe00048c4aa)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffe00048c4aa-ffffffe00048c508: __percpu_counter_compare (STB_GLOBAL)
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
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8154b240)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff8154b240-ffffffff8154b294: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8153b520)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff8153b520-ffffffff8153b574: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81546f80)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff81546f80-ffffffff81546fd4: __percpu_counter_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __percpu_counter_compare(struct percpu_counter *fbc, s64 rhs, s32 batch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81560e70)
Location: lib/percpu_counter.c:202
Inline: True
Direct callers:
  - mm/shmem.c:shmem_reconfigure
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_alloc_and_acct_page
  - mm/shmem.c:shmem_charge
```
**Symbols:**

```
ffffffff81560e70-ffffffff81560ec4: __percpu_counter_compare (STB_GLOBAL)
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
