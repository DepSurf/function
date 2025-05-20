# Function: <code>blkg_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blkg_free(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d6f80)
Location: block/blk-cgroup.c:64
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkcg_init_queue
```
**Symbols:**

```
ffffffff813d6f80-ffffffff813d7041: blkg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blkg_free(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141cca0)
Location: block/blk-cgroup.c:64
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff8141cca0-ffffffff8141cd4e: blkg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkg_free(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81438270)
Location: block/blk-cgroup.c:64
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkcg_init_queue
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81438270-ffffffff8143831e: blkg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff81447aa6)
Location: block/blk-cgroup.c:65
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81446290-ffffffff81446350: blkg_free.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff814746a6)
Location: block/blk-cgroup.c:65
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff81472e40-ffffffff81472f06: blkg_free.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a8791)
Location: block/blk-cgroup.c:65
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
```
**Symbols:**

```
ffffffff814a7210-ffffffff814a72d6: blkg_free.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blkg_free(struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c1320)
Location: block/blk-cgroup.c:68
Inline: True
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff814c1320-ffffffff814c13b5: blkg_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f14cd)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff814efac0-ffffffff814efb55: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150ab0b)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff81508f70-ffffffff81509005: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156bbe0)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff8156a100-ffffffff8156a15c: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586773)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff81584b50-ffffffff81584ba9: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158d483)
Location: block/blk-cgroup.c:70
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff8158b810-ffffffff8158b869: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f2f3f)
Location: block/blk-cgroup.c:73
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff815f0ac0-ffffffff815f0b6f: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a431b)
Location: block/blk-cgroup.c:108
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817630d3)
Location: block/blk-cgroup.c:140
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a1124)
Location: block/blk-cgroup.c:156
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e4c71)
Location: block/blk-cgroup.c:156
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
  - block/blk-cgroup.c:__blkg_release
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffff80001060e20c)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffff80001060be18-ffff80001060bebc: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (c07b8c0c)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
c07b6fb8-c07b7050: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (c0000000007ab5ac)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
c0000000007a8930-c0000000007a8a10: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffe0004467bc)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffe000444b7c-ffffffe000444c12: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff815030eb)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff81501550-ffffffff815015e5: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f35c5)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff814f1a60-ffffffff814f1af5: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff814ff17b)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff814fd5e0-ffffffff814fd675: blkg_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-cgroup.c (ffffffff81518301)
Location: block/blk-cgroup.c:72
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_alloc
  - block/blk-cgroup.c:__blkg_release
```
**Symbols:**

```
ffffffff81516ab0-ffffffff81516b45: blkg_free.part.0 (STB_LOCAL)
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
</ul>
