# Function: <code>__zswap_pool_empty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff811d8240)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
```
**Symbols:**

```
ffffffff811d8240-ffffffff811d82b8: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff811f6370)
Location: mm/zswap.c:674
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff811f6370-ffffffff811f640f: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81206d00)
Location: mm/zswap.c:601
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81206d00-ffffffff81206d9f: __zswap_pool_empty (STB_LOCAL)
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
In mm/zswap.c (ffffffff812121d5)
Location: mm/zswap.c:632
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8122cbc0)
Location: mm/zswap.c:632
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff8122cbc0-ffffffff8122cc63: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8124fa70)
Location: mm/zswap.c:647
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff8124fa70-ffffffff8124fb00: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81264010)
Location: mm/zswap.c:647
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81264010-ffffffff812640a0: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff8127ef50-ffffffff8127eff3: __zswap_pool_empty (STB_LOCAL)
ffffffff81280131-ffffffff81280144: __zswap_pool_empty.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8128e9a0)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff8128e9a0-ffffffff8128ea43: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812c1630)
Location: mm/zswap.c:669
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff812c1630-ffffffff812c16d0: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812cd160)
Location: mm/zswap.c:725
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff812cd160-ffffffff812cd200: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff812d3b50)
Location: mm/zswap.c:725
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff812d3b50-ffffffff812d3bf0: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81319800)
Location: mm/zswap.c:725
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81319800-ffffffff813198a0: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81384aa0)
Location: mm/zswap.c:740
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81384aa0-ffffffff81384b4a: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81402730)
Location: mm/zswap.c:740
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81402730-ffffffff814027da: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81435c50)
Location: mm/zswap.c:838
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81435c50-ffffffff81435d33: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8146ee60)
Location: mm/zswap.c:1180
Inline: False
Direct callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:shrink_memcg
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff8146ee60-ffffffff8146ef48: __zswap_pool_empty (STB_LOCAL)
```
</details>
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
In mm/zswap.c (ffff80001032b3f4)
Location: mm/zswap.c:638
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
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
In mm/zswap.c (c054192c)
Location: mm/zswap.c:638
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
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
In mm/zswap.c (c0000000004022a0)
Location: mm/zswap.c:638
Inline: True
Inline callers:
  - mm/zswap.c:zswap_pool_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffe00022a1d0)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffe00022a1d0-ffffffe00022a296: __zswap_pool_empty (STB_LOCAL)
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
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81286f80)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81286f80-ffffffff81287023: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81278de0)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81278de0-ffffffff81278e83: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81284d90)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81284d90-ffffffff81284e33: __zswap_pool_empty (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __zswap_pool_empty(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81294980)
Location: mm/zswap.c:638
Inline: False
Direct callers:
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:zswap_frontswap_store
  - mm/zswap.c:__zswap_param_set
  - mm/zswap.c:zswap_free_entry
```
**Symbols:**

```
ffffffff81294980-ffffffff81294a21: __zswap_pool_empty (STB_LOCAL)
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
