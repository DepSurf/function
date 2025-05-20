# Function: <code>__list_lru_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811b94c0)
Location: mm/list_lru.c:534
Inline: False
Direct callers:
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff811b94c0-ffffffff811b96b1: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811d37c0)
Location: mm/list_lru.c:534
Inline: False
Direct callers:
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff811d37c0-ffffffff811d39b1: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811e3680)
Location: mm/list_lru.c:534
Inline: False
Direct callers:
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff811e3680-ffffffff811e388a: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811edac0)
Location: mm/list_lru.c:532
Inline: False
Direct callers:
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff811edac0-ffffffff811edcd9: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81203f20)
Location: mm/list_lru.c:533
Inline: False
Direct callers:
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff81203f20-ffffffff8120413e: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81224ab0)
Location: mm/list_lru.c:556
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff81224ab0-ffffffff81224cbc: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81237a10)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:sget_userns
  - fs/super.c:sget_userns
```
**Symbols:**

```
ffffffff81237a10-ffffffff81237c2c: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81248f90)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81248f90-ffffffff812491a8: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812573e0)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812573e0-ffffffff812575f8: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81285990)
Location: mm/list_lru.c:590
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff81285990-ffffffff81285bdc: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8128fc50)
Location: mm/list_lru.c:590
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8128fc50-ffffffff8128fe9c: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812953c0)
Location: mm/list_lru.c:582
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812953c0-ffffffff81295608: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812d5900)
Location: mm/list_lru.c:582
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812d5900-ffffffff812d5b48: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813352a0)
Location: mm/list_lru.c:559
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff813352a0-ffffffff813353d8: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813abf60)
Location: mm/list_lru.c:559
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff813abf60-ffffffff813ac08a: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff813e0300)
Location: mm/list_lru.c:559
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff813e0300-ffffffff813e042a: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8140a660)
Location: mm/list_lru.c:560
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - mm/zswap.c:zswap_pool_create
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8140a660-ffffffff8140a78a: __list_lru_init (STB_GLOBAL)
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
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102eee70)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffff8000102eee70-ffff8000102ef0c8: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512de0)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
c0512de0-c0512f04: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b34f0)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
c0000000003b34f0-c0000000003b3828: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe000202d84)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffe000202d84-ffffffe000202ea2: __list_lru_init (STB_GLOBAL)
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
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124fa30)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8124fa30-ffffffff8124fc48: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812429d0)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff812429d0-ffffffff81242be8: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124d7d0)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8124d7d0-ffffffff8124d9e8: __list_lru_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __list_lru_init(struct list_lru *lru, bool memcg_aware, struct lock_class_key *key, struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d490)
Location: mm/list_lru.c:600
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff8125d490-ffffffff8125d6a8: __list_lru_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct shrinker *shrinker</code>
</li>
</ul>
</details>
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
