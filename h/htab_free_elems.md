# Function: <code>htab_free_elems</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186200)
Location: kernel/bpf/hashtab.c:72
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81186200-ffffffff81186260: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811933f0)
Location: kernel/bpf/hashtab.c:90
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff811933f0-ffffffff81193457: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a4e0)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff8119a4e0-ffffffff8119a547: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9cf0)
Location: kernel/bpf/hashtab.c:104
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811a9cf0-ffffffff811a9d56: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c11a0)
Location: kernel/bpf/hashtab.c:104
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811c11a0-ffffffff811c1206: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d2980)
Location: kernel/bpf/hashtab.c:108
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811d2980-ffffffff811d29e6: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e70c0)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811e70c0-ffffffff811e7126: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f3820)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811f3820-ffffffff811f3886: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81217060)
Location: kernel/bpf/hashtab.c:204
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81217060-ffffffff812170c6: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219330)
Location: kernel/bpf/hashtab.c:231
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81219330-ffffffff81219399: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121cd30)
Location: kernel/bpf/hashtab.c:231
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8121cd30-ffffffff8121cd99: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81253d00)
Location: kernel/bpf/hashtab.c:257
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81253d00-ffffffff81253d69: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129c1e0)
Location: kernel/bpf/hashtab.c:277
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8129c1e0-ffffffff8129c253: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f8410)
Location: kernel/bpf/hashtab.c:257
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff812f8410-ffffffff812f8483: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81326460)
Location: kernel/bpf/hashtab.c:268
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff81326460-ffffffff813264d3: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134aaa0)
Location: kernel/bpf/hashtab.c:272
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_init
```
**Symbols:**

```
ffffffff8134aaa0-ffffffff8134ab13: htab_free_elems (STB_LOCAL)
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
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff8000102776a8)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffff8000102776a8-ffff800010277728: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04a9fd0)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
c04a9fd0-c04aa044: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c00000000031fe50)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
c00000000031fe50-c00000000031ff38: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001af75e)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffe0001af75e-ffffffe0001af7d2: htab_free_elems (STB_LOCAL)
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
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ebe40)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811ebe40-ffffffff811ebea6: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811debd0)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811debd0-ffffffff811dec36: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9c10)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811e9c10-ffffffff811e9c76: htab_free_elems (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void htab_free_elems(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f7fe0)
Location: kernel/bpf/hashtab.c:100
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/hashtab.c:prealloc_destroy
```
**Symbols:**

```
ffffffff811f7fe0-ffffffff811f8041: htab_free_elems (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
