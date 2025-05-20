# Function: <code>htab_map_update_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81177750)
Location: kernel/bpf/hashtab.c:224
Inline: False
```
**Symbols:**

```
ffffffff81177750-ffffffff81177a2b: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81187180)
Location: kernel/bpf/hashtab.c:519
Inline: False
```
**Symbols:**

```
ffffffff81187180-ffffffff8118744b: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81194830)
Location: kernel/bpf/hashtab.c:659
Inline: False
```
**Symbols:**

```
ffffffff81194830-ffffffff81194afe: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119b740)
Location: kernel/bpf/hashtab.c:753
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff8119b740-ffffffff8119ba0c: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811aaf90)
Location: kernel/bpf/hashtab.c:786
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811aaf90-ffffffff811ab264: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c2830)
Location: kernel/bpf/hashtab.c:806
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811c2830-ffffffff811c2afd: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d3df0)
Location: kernel/bpf/hashtab.c:820
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811d3df0-ffffffff811d413d: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9250)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811e9250-ffffffff811e9671: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f59b0)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811f59b0-ffffffff811f5dd1: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81218320)
Location: kernel/bpf/hashtab.c:929
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff81218320-ffffffff8121857c: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121a1e0)
Location: kernel/bpf/hashtab.c:977
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff8121a1e0-ffffffff8121a46c: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121dbe0)
Location: kernel/bpf/hashtab.c:977
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff8121dbe0-ffffffff8121de6c: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81256a60)
Location: kernel/bpf/hashtab.c:1019
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff81256a60-ffffffff81256d17: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129f410)
Location: kernel/bpf/hashtab.c:1038
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff8129f410-ffffffff8129f69e: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fb090)
Location: kernel/bpf/hashtab.c:1060
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff812fb090-ffffffff812fb398: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff813291d0)
Location: kernel/bpf/hashtab.c:1072
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff813291d0-ffffffff8132953b: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134df50)
Location: kernel/bpf/hashtab.c:1090
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff8134df50-ffffffff8134e23a: htab_map_update_elem (STB_LOCAL)
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
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010279e10)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffff800010279e10-ffff80001027a264: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04ac094)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
c04ac094-c04ac498: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000322ea0)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
c000000000322ea0-c0000000003233f4: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001afd1c)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffe0001afd1c-ffffffe0001b00fc: htab_map_update_elem (STB_LOCAL)
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
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811edfd0)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811edfd0-ffffffff811ee3f1: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e0d60)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811e0d60-ffffffff811e1181: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ebda0)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811ebda0-ffffffff811ec1c1: htab_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int htab_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811fa1a0)
Location: kernel/bpf/hashtab.c:819
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_update_elem
```
**Symbols:**

```
ffffffff811fa1a0-ffffffff811fa5c1: htab_map_update_elem (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
