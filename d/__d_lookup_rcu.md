# Function: <code>__d_lookup_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225c70)
Location: fs/dcache.c:2144
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff81225c70-ffffffff81225db8: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ddd0)
Location: fs/dcache.c:2085
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff8124ddd0-ffffffff8124df49: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260eb0)
Location: fs/dcache.c:2094
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81260eb0-ffffffff81261029: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e6a0)
Location: fs/dcache.c:2124
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff8126e6a0-ffffffff8126e82e: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290fc0)
Location: fs/dcache.c:2136
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81290fc0-ffffffff81291154: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b76a0)
Location: fs/dcache.c:2160
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812b76a0-ffffffff812b781e: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc800)
Location: fs/dcache.c:2141
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812cc800-ffffffff812cc97e: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e93f0)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812e93f0-ffffffff812e9553: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812faf90)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812faf90-ffffffff812fb0f3: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333c70)
Location: fs/dcache.c:2234
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81333c70-ffffffff81333ddd: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133f5f0)
Location: fs/dcache.c:2241
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff8133f5f0-ffffffff8133f75d: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81345a70)
Location: fs/dcache.c:2268
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81345a70-ffffffff81345bdd: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2269
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81cc3b9e-ffffffff81cc3bc5: __d_lookup_rcu.cold (STB_LOCAL)
ffffffff81393680-ffffffff813937f6: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2294
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81e763cb-ffffffff81e763f2: __d_lookup_rcu.cold (STB_LOCAL)
ffffffff81414df0-ffffffff81414f97: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2344
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff82068975-ffffffff82068994: __d_lookup_rcu.cold (STB_LOCAL)
ffffffff814a0340-ffffffff814a0497: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2344
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff820e82b3-ffffffff820e82d2: __d_lookup_rcu.cold (STB_LOCAL)
ffffffff814d5660-ffffffff814d57b7: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2168
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff821c4ff0-ffffffff821c500f: __d_lookup_rcu.cold (STB_LOCAL)
ffffffff81507ab0-ffffffff81507c07: __d_lookup_rcu (STB_GLOBAL)
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
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa310)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffff8000103aa310-ffff8000103aa4c0: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b2a8)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
c058b2a8-c058b460: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a51d0)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
c0000000004a51d0-c0000000004a5434: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe000270078)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffe000270078-ffffffe000270194: __d_lookup_rcu (STB_GLOBAL)
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
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f3570)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812f3570-ffffffff812f36d3: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e41a0)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812e41a0-ffffffff812e4303: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f1380)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff812f1380-ffffffff812f14e3: __d_lookup_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *__d_lookup_rcu(const struct dentry *parent, const struct qstr *name, unsigned int *seqp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302540)
Location: fs/dcache.c:2213
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/dcache.c:d_alloc_parallel
```
**Symbols:**

```
ffffffff81302540-ffffffff813026a3: __d_lookup_rcu (STB_GLOBAL)
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
