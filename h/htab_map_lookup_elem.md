# Function: <code>htab_map_lookup_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81177a30)
Location: kernel/bpf/hashtab.c:141
Inline: False
```
**Symbols:**

```
ffffffff81177a30-ffffffff81177bd7: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186d40)
Location: kernel/bpf/hashtab.c:316
Inline: False
```
**Symbols:**

```
ffffffff81186d40-ffffffff81186d6f: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81193ec0)
Location: kernel/bpf/hashtab.c:408
Inline: False
```
**Symbols:**

```
ffffffff81193ec0-ffffffff81193eef: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119af3d)
Location: kernel/bpf/hashtab.c:461
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
```
**Symbols:**

```
ffffffff8119af00-ffffffff8119af2f: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811aa77d)
Location: kernel/bpf/hashtab.c:470
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811aa740-ffffffff811aa76f: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1dc5)
Location: kernel/bpf/hashtab.c:480
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
```
**Symbols:**

```
ffffffff811c1d90-ffffffff811c1dc0: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d33d5)
Location: kernel/bpf/hashtab.c:494
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811d3310-ffffffff811d333b: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e8105)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811e8040-ffffffff811e806b: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f4865)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811f47a0-ffffffff811f47cb: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812190e5)
Location: kernel/bpf/hashtab.c:594
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff81219000-ffffffff8121906b: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121ba00)
Location: kernel/bpf/hashtab.c:612
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff8121b980-ffffffff8121b9eb: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121f480)
Location: kernel/bpf/hashtab.c:612
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff8121f310-ffffffff8121f37b: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81255db0)
Location: kernel/bpf/hashtab.c:643
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff81255cc0-ffffffff81255d2b: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129eb70)
Location: kernel/bpf/hashtab.c:659
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff8129eae0-ffffffff8129eb5a: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fb4e0)
Location: kernel/bpf/hashtab.c:674
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff812fb3b0-ffffffff812fb42a: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81329e30)
Location: kernel/bpf/hashtab.c:681
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff81329cf0-ffffffff81329d6a: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134ccd0)
Location: kernel/bpf/hashtab.c:692
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff8134cb00-ffffffff8134cb7a: htab_map_lookup_elem (STB_LOCAL)
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
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010278a2c)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffff800010278918-ffff800010278968: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04ab04c)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
c04aaf70-c04aafa8: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000321730)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
c0000000003215b0-c000000000321610: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b0ba8)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffe0001b0aa4-ffffffe0001b0aec: htab_map_lookup_elem (STB_LOCAL)
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
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ece85)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811ecdc0-ffffffff811ecdeb: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811dfc15)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811dfb50-ffffffff811dfb7b: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811eac55)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811eab90-ffffffff811eabbb: htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f9045)
Location: kernel/bpf/hashtab.c:482
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
```
**Symbols:**

```
ffffffff811f8f70-ffffffff811f8f9b: htab_map_lookup_elem (STB_LOCAL)
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
