# Function: <code>__xas_nomem</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a17ca0)
Location: lib/xarray.c:314
Inline: True
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_reserve
  - lib/xarray.c:__xa_reserve
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81a17ca0-ffffffff81a17d97: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86c10)
Location: lib/xarray.c:321
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81a86c10-ffffffff81a86d14: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abde80)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81abde80-ffffffff81abdf84: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb7c0)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff815fb7c0-ffffffff815fb8d7: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620330)
Location: lib/xarray.c:324
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81620330-ffffffff81620468: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604540)
Location: lib/xarray.c:324
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81604540-ffffffff8160467a: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81672e30)
Location: lib/xarray.c:324
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81672e30-ffffffff81672f6a: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178c2b0)
Location: lib/xarray.c:327
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff8178c2b0-ffffffff8178c3fc: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049930)
Location: lib/xarray.c:327
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff82049930-ffffffff82049a7c: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c83a0)
Location: lib/xarray.c:325
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff820c83a0-ffffffff820c84ec: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a2d20)
Location: lib/xarray.c:325
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff821a2d20-ffffffff821a2e6c: __xas_nomem (STB_LOCAL)
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
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b220)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffff800010d9b220-ffff800010d9b3c4: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96ae0)
Location: lib/xarray.c:322
Inline: True
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
c0e96ae0-c0e96c50: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edeba0)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
c000000000edeba0-c000000000ededf0: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c356e)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffe0008c356e-ffffffe0008c36ea: __xas_nomem (STB_LOCAL)
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
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5ccd0)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81a5ccd0-ffffffff81a5cdd4: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19db0)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81a19db0-ffffffff81a19eae: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac90c0)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81ac90c0-ffffffff81ac91c4: __xas_nomem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __xas_nomem(struct xa_state *xas, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad55a0)
Location: lib/xarray.c:322
Inline: False
Direct callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
  - lib/xarray.c:__xa_store
```
**Symbols:**

```
ffffffff81ad55a0-ffffffff81ad569f: __xas_nomem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
