# Function: <code>pcpu_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811b0fe0)
Location: mm/percpu.c:873
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_percpu_gfp
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_reserved_percpu
```
**Symbols:**

```
ffffffff811b0fe0-ffffffff811b1642: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811ca170)
Location: mm/percpu.c:868
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff811ca170-ffffffff811ca7a3: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811da280)
Location: mm/percpu.c:868
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff811da280-ffffffff811da8ca: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e3930)
Location: mm/percpu.c:859
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff811e3930-ffffffff811e3fe5: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811fa410)
Location: mm/percpu.c:1343
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff811fa410-ffffffff811faa2f: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1341
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8121b010-ffffffff8121b613: pcpu_alloc (STB_LOCAL)
ffffffff8121c2e6-ffffffff8121c323: pcpu_alloc.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1352
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8122dfe0-ffffffff8122e5f2: pcpu_alloc (STB_LOCAL)
ffffffff8122f2e3-ffffffff8122f320: pcpu_alloc.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8123e840-ffffffff8123ee64: pcpu_alloc (STB_LOCAL)
ffffffff8123f35c-ffffffff8123f3af: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8124cca0-ffffffff8124d2c9: pcpu_alloc (STB_LOCAL)
ffffffff8124d775-ffffffff8124d7b2: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1558
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8127af70-ffffffff8127b602: pcpu_alloc (STB_LOCAL)
ffffffff8127baff-ffffffff8127bb3c: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1676
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff81285980-ffffffff81286137: pcpu_alloc (STB_LOCAL)
ffffffff81be727e-ffffffff81be72bb: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1677
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8128a550-ffffffff8128ad1d: pcpu_alloc (STB_LOCAL)
ffffffff81bd901f-ffffffff81bd905c: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1722
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff812ca970-ffffffff812cb0da: pcpu_alloc (STB_LOCAL)
ffffffff81cbb0e8-ffffffff81cbb177: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1722
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff81328250-ffffffff81328aa7: pcpu_alloc (STB_LOCAL)
ffffffff81e6cc7e-ffffffff81e6cd1c: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1719
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff8139d4c0-ffffffff8139dce9: pcpu_alloc (STB_LOCAL)
ffffffff8206311f-ffffffff82063181: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1719
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff813d05f0-ffffffff813d0e4f: pcpu_alloc (STB_LOCAL)
ffffffff820e29bc-ffffffff820e2a1e: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1717
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff813fafb0-ffffffff813fb7e8: pcpu_alloc (STB_LOCAL)
ffffffff821bf3ad-ffffffff821bf40f: pcpu_alloc.cold (STB_LOCAL)
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
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffff8000102e3250)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffff8000102e3250-ffff8000102e3b5c: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c05073f8)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
c05073f8-c0507b90: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a2c30)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
c0000000003a2c30-c0000000003a3520: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f962c)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffe0001f962c-ffffffe0001f9c28: pcpu_alloc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff812452f0-ffffffff81245919: pcpu_alloc (STB_LOCAL)
ffffffff81245dc5-ffffffff81245e02: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff812382a0-ffffffff812388c9: pcpu_alloc (STB_LOCAL)
ffffffff81238d75-ffffffff81238db2: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff81243090-ffffffff812436b9: pcpu_alloc (STB_LOCAL)
ffffffff81243b65-ffffffff81243ba2: pcpu_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *pcpu_alloc(size_t size, size_t align, bool reserved, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:1586
Inline: False
Direct callers:
  - mm/percpu.c:__alloc_reserved_percpu
  - mm/percpu.c:__alloc_percpu
  - mm/percpu.c:__alloc_percpu_gfp
```
**Symbols:**

```
ffffffff81252820-ffffffff81252e7b: pcpu_alloc (STB_LOCAL)
ffffffff81253325-ffffffff81253362: pcpu_alloc.cold (STB_LOCAL)
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
