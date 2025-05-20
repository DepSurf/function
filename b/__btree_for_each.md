# Function: <code>__btree_for_each</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81403930)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:__btree_for_each
  - lib/btree.c:btree_visitor
  - lib/btree.c:btree_grim_visitor
```
**Symbols:**

```
ffffffff81403930-ffffffff81403a34: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff8144b4d0)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff8144b4d0-ffffffff8144b5da: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81469e90)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81469e90-ffffffff81469f9a: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff8146f560)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff8146f560-ffffffff8146f651: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff8149bc70)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff8149bc70-ffffffff8149bd63: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff814d11e0)
Location: lib/btree.c:678
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff814d11e0-ffffffff814d12e3: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff814e5b10)
Location: lib/btree.c:678
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff814e5b10-ffffffff814e5c13: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81512490)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81512490-ffffffff81512575: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81532ed0)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81532ed0-ffffffff81532fb5: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81596d40)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81596d40-ffffffff81596e24: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff815b2760)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff815b2760-ffffffff815b2844: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff815bd5e0)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff815bd5e0-ffffffff815bd6c4: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81624980)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81624980-ffffffff81624a64: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff816f50f0)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff816f50f0-ffffffff816f51e4: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff817e73f0)
Location: lib/btree.c:672
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff817e73f0-ffffffff817e74e4: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81827410)
Location: lib/btree.c:672
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81827410-ffffffff81827504: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81878e20)
Location: lib/btree.c:672
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81878e20-ffffffff81878f14: __btree_for_each (STB_LOCAL)
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
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffff80001063f650)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffff80001063f650-ffff80001063f77c: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (c07e4f20)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
c07e4f20-c07e5028: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (c0000000007e92d0)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
c0000000007e92d0-c0000000007e947c: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffe00046c3cc)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffe00046c3cc-ffffffe00046c49c: __btree_for_each (STB_LOCAL)
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
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff8152b4b0)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff8152b4b0-ffffffff8152b595: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff8151b790)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff8151b790-ffffffff8151b875: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81527540)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81527540-ffffffff81527625: __btree_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t __btree_for_each(struct btree_head *head, struct btree_geo *geo, long unsigned int *node, long unsigned int opaque, void (*func)(void *, long unsigned int, long unsigned int *, size_t, void *), void *func2, int reap, int height, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/btree.c (ffffffff81540f20)
Location: lib/btree.c:676
Inline: False
Direct callers:
  - lib/btree.c:btree_grim_visitor
  - lib/btree.c:btree_visitor
  - lib/btree.c:__btree_for_each
```
**Symbols:**

```
ffffffff81540f20-ffffffff81541005: __btree_for_each (STB_LOCAL)
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
