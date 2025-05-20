# Function: <code>sock_hash_get_next_key</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811d0370)
Location: kernel/bpf/sockmap.c:2294
Inline: False
```
**Symbols:**

```
ffffffff811d0370-ffffffff811d05be: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f3000)
Location: net/core/sock_map.c:746
Inline: False
```
**Symbols:**

```
ffffffff818f3000-ffffffff818f329a: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff819454d0)
Location: net/core/sock_map.c:753
Inline: False
```
**Symbols:**

```
ffffffff819454d0-ffffffff81945767: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8197a4f0)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffffffff8197a4f0-ffffffff8197a787: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4e010)
Location: net/core/sock_map.c:954
Inline: False
```
**Symbols:**

```
ffffffff81a4e010-ffffffff81a4e106: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a54000)
Location: net/core/sock_map.c:1054
Inline: False
```
**Symbols:**

```
ffffffff81a54000-ffffffff81a540f6: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4fb10)
Location: net/core/sock_map.c:1039
Inline: False
```
**Symbols:**

```
ffffffff81a4fb10-ffffffff81a4fc0d: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08540)
Location: net/core/sock_map.c:1030
Inline: False
```
**Symbols:**

```
ffffffff81b08540-ffffffff81b0863a: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8e4a0)
Location: net/core/sock_map.c:1032
Inline: False
```
**Symbols:**

```
ffffffff81c8e4a0-ffffffff81c8e5a0: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e49850)
Location: net/core/sock_map.c:1034
Inline: False
```
**Symbols:**

```
ffffffff81e49850-ffffffff81e49950: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea4f10)
Location: net/core/sock_map.c:1039
Inline: False
```
**Symbols:**

```
ffffffff81ea4f10-ffffffff81ea5010: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67970)
Location: net/core/sock_map.c:1043
Inline: False
```
**Symbols:**

```
ffffffff81f67970-ffffffff81f67a70: sock_hash_get_next_key (STB_LOCAL)
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
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c217d8)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffff800010c217d8-ffff800010c21a9c: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d38e9c)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
c0d38e9c-c0d390e8: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d13c70)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
c000000000d13c70-c000000000d14064: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe00079a5e2)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffffffe00079a5e2-ffffffe00079a8e8: sock_hash_get_next_key (STB_LOCAL)
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
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8191a360)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffffffff8191a360-ffffffff8191a5f7: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d4110)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffffffff818d4110-ffffffff818d43a7: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196b4f0)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffffffff8196b4f0-ffffffff8196b787: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_hash_get_next_key(struct bpf_map *map, void *key, void *key_next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198d960)
Location: net/core/sock_map.c:763
Inline: False
```
**Symbols:**

```
ffffffff8198d960-ffffffff8198dbf7: sock_hash_get_next_key (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *key_next</code>
</li>
<li>
<b>Param removed. </b>
<code>void *next_key</code>
</li>
</ul>
</details>
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
