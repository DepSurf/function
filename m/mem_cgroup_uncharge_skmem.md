# Function: <code>mem_cgroup_uncharge_skmem</code>

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
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812243a0)
Location: mm/memcontrol.c:5756
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
```
**Symbols:**

```
ffffffff812243a0-ffffffff81224425: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81236970)
Location: mm/memcontrol.c:5744
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff81236970-ffffffff812369f5: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81242410)
Location: mm/memcontrol.c:5806
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff81242410-ffffffff81242498: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81262210)
Location: mm/memcontrol.c:5905
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff81262210-ffffffff81262249: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286260)
Location: mm/memcontrol.c:5973
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff81286260-ffffffff812862eb: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129b1b0)
Location: mm/memcontrol.c:6304
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff8129b1b0-ffffffff8129b23b: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6450)
Location: mm/memcontrol.c:6596
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812b6450-ffffffff812b64b9: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c8320)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812c8320-ffffffff812c8389: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fdb80)
Location: mm/memcontrol.c:6784
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812fdb80-ffffffff812fdbee: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309fd0)
Location: mm/memcontrol.c:7044
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff81309fd0-ffffffff8130a03e: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310840)
Location: mm/memcontrol.c:6905
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff81310840-ffffffff813108b2: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135bb40)
Location: mm/memcontrol.c:7084
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff8135bb40-ffffffff8135bbaa: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d5410)
Location: mm/memcontrol.c:7064
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff813d5410-ffffffff813d5469: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145aec0)
Location: mm/memcontrol.c:7253
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff8145aec0-ffffffff8145af19: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81490b30)
Location: mm/memcontrol.c:7321
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff81490b30-ffffffff81490b89: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c04a0)
Location: mm/memcontrol.c:7698
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
  - net/core/sock.c:sk_setsockopt
```
**Symbols:**

```
ffffffff814c04a0-ffffffff814c04f9: mem_cgroup_uncharge_skmem (STB_GLOBAL)
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
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036b220)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffff80001036b220-ffff80001036b2a8: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c948)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
c055c948-c055c9ac: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045aad0)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
c00000000045aad0-c00000000045ab74: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248978)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffe000248978-ffffffe0002489f8: mem_cgroup_uncharge_skmem (STB_GLOBAL)
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
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0900)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812c0900-ffffffff812c0969: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b19b0)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812b19b0-ffffffff812b1a03: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be710)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812be710-ffffffff812be779: mem_cgroup_uncharge_skmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_uncharge_skmem(struct mem_cgroup *memcg, unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cf170)
Location: mm/memcontrol.c:6926
Inline: False
Direct callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
**Symbols:**

```
ffffffff812cf170-ffffffff812cf1d9: mem_cgroup_uncharge_skmem (STB_GLOBAL)
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
