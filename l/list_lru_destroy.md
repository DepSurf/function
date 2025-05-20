# Function: <code>list_lru_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811b93d0)
Location: mm/list_lru.c:567
Inline: False
Direct callers:
  - fs/super.c:destroy_super
  - fs/super.c:destroy_super
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff811b93d0-ffffffff811b94c0: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811d36d0)
Location: mm/list_lru.c:567
Inline: False
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
  - fs/super.c:destroy_super
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff811d36d0-ffffffff811d37c0: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811e3580)
Location: mm/list_lru.c:569
Inline: False
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
  - fs/super.c:destroy_super
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff811e3580-ffffffff811e367a: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff811ed9c0)
Location: mm/list_lru.c:567
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
  - fs/super.c:destroy_super
  - fs/super.c:destroy_super
```
**Symbols:**

```
ffffffff811ed9c0-ffffffff811edab1: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81203e20)
Location: mm/list_lru.c:568
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81203e20-ffffffff81203f11: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812249b0)
Location: mm/list_lru.c:591
Inline: True
Direct callers:
  - mm/workingset.c:workingset_init
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff812249b0-ffffffff81224aa1: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81237910)
Location: mm/list_lru.c:641
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81237910-ffffffff81237a08: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81248e90)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81248e90-ffffffff81248f87: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812572e0)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff812572e0-ffffffff812573d7: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81285be0)
Location: mm/list_lru.c:630
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81285be0-ffffffff81285cf2: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8128fea0)
Location: mm/list_lru.c:630
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff8128fea0-ffffffff8128ffb2: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812952a0)
Location: mm/list_lru.c:622
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff812952a0-ffffffff812953b5: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff812d5b6a)
Location: mm/list_lru.c:622
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81cbbc97-ffffffff81cbbcab: list_lru_destroy.cold (STB_LOCAL)
ffffffff812d5b50-ffffffff812d5c71: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff81334cbe)
Location: mm/list_lru.c:589
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff81e6d8ba-ffffffff81e6d8cf: list_lru_destroy.cold (STB_LOCAL)
ffffffff81334ca0-ffffffff81334d49: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff813ababe)
Location: mm/list_lru.c:589
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff82063bd5-ffffffff82063bea: list_lru_destroy.cold (STB_LOCAL)
ffffffff813abaa0-ffffffff813abb49: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff813dfe4e)
Location: mm/list_lru.c:589
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff820e32cc-ffffffff820e32e1: list_lru_destroy.cold (STB_LOCAL)
ffffffff813dfe30-ffffffff813dfed9: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/list_lru.c (ffffffff8140a5be)
Location: mm/list_lru.c:590
Inline: True
Direct callers:
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
  - fs/super.c:alloc_super
  - fs/super.c:alloc_super
```
**Symbols:**

```
ffffffff821bfd19-ffffffff821bfd2e: list_lru_destroy.cold (STB_LOCAL)
ffffffff8140a5a0-ffffffff8140a649: list_lru_destroy (STB_GLOBAL)
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
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102eed78)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffff8000102eed78-ffff8000102eee70: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512d14)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
c0512d14-c0512de0: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b3330)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
c0000000003b3330-c0000000003b34e8: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe000202cb6)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffe000202cb6-ffffffe000202d84: list_lru_destroy (STB_GLOBAL)
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
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124f930)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff8124f930-ffffffff8124fa27: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812428d0)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff812428d0-ffffffff812429c7: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124d6d0)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff8124d6d0-ffffffff8124d7c7: list_lru_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void list_lru_destroy(struct list_lru *lru);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d390)
Location: mm/list_lru.c:640
Inline: True
Direct callers:
  - fs/super.c:deactivate_locked_super
  - fs/super.c:deactivate_locked_super
```
**Symbols:**

```
ffffffff8125d390-ffffffff8125d487: list_lru_destroy (STB_GLOBAL)
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
