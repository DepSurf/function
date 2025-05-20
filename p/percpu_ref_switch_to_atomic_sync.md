# Function: <code>percpu_ref_switch_to_atomic_sync</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8146a190)
Location: lib/percpu-refcount.c:273
Inline: True
Direct callers:
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8146a190-ffffffff8146a21e: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81496480)
Location: lib/percpu-refcount.c:273
Inline: True
Direct callers:
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff81496480-ffffffff8149650e: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814cb6e0)
Location: lib/percpu-refcount.c:273
Inline: True
Direct callers:
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff814cb6e0-ffffffff814cb76e: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814e0410)
Location: lib/percpu-refcount.c:273
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff814e0410-ffffffff814e049e: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8150c3b0)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8150c3b0-ffffffff8150c437: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8152a200)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8152a200-ffffffff8152a287: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8158da90)
Location: lib/percpu-refcount.c:284
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8158da90-ffffffff8158db40: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa760)
Location: lib/percpu-refcount.c:320
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff815aa760-ffffffff815aa81c: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b5380)
Location: lib/percpu-refcount.c:326
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff815b5380-ffffffff815b543c: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8161b720)
Location: lib/percpu-refcount.c:326
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8161b720-ffffffff8161b7dc: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff816e8f30)
Location: lib/percpu-refcount.c:327
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff816e8f30-ffffffff816e9020: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff817d9010)
Location: lib/percpu-refcount.c:328
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff817d9010-ffffffff817d9100: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81818220)
Location: lib/percpu-refcount.c:328
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff81818220-ffffffff81818310: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8185d520)
Location: lib/percpu-refcount.c:328
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8185d520-ffffffff8185d610: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
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
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffff800010635318)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffff800010635318-ffff8000106353b8: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c07db354)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
c07db354-c07db400: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c0000000007dabf0)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
c0000000007dabf0-c0000000007dacd0: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffe000462d44)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffe000462d44-ffffffe000462dbc: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
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
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815227e0)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff815227e0-ffffffff81522867: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81512ac0)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff81512ac0-ffffffff81512b47: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8151e870)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff8151e870-ffffffff8151e8f7: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void percpu_ref_switch_to_atomic_sync(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81538110)
Location: lib/percpu-refcount.c:283
Inline: True
Direct callers:
  - block/blk-pm.c:blk_pre_runtime_suspend
  - drivers/md/md.c:set_in_sync
```
**Symbols:**

```
ffffffff81538110-ffffffff81538192: percpu_ref_switch_to_atomic_sync (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
