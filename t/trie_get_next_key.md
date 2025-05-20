# Function: <code>trie_get_next_key</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8119e4a0)
Location: kernel/bpf/lpm_trie.c:504
Inline: False
```
**Symbols:**

```
ffffffff8119e4a0-ffffffff8119e4b0: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ae080)
Location: kernel/bpf/lpm_trie.c:601
Inline: False
```
**Symbols:**

```
ffffffff811ae080-ffffffff811ae090: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811c5cd0)
Location: kernel/bpf/lpm_trie.c:596
Inline: False
```
**Symbols:**

```
ffffffff811c5cd0-ffffffff811c5f5f: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811d7940)
Location: kernel/bpf/lpm_trie.c:638
Inline: False
```
**Symbols:**

```
ffffffff811d7940-ffffffff811d7b46: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811ec2c0)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff811ec2c0-ffffffff811ec4bc: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811f8a20)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff811f8a20-ffffffff811f8c1c: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8121c310)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff8121c310-ffffffff8121c4e0: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8121f220)
Location: kernel/bpf/lpm_trie.c:612
Inline: False
```
**Symbols:**

```
ffffffff8121f220-ffffffff8121f3f0: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81222cb0)
Location: kernel/bpf/lpm_trie.c:612
Inline: False
```
**Symbols:**

```
ffffffff81222cb0-ffffffff81222e76: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff8125aa60)
Location: kernel/bpf/lpm_trie.c:614
Inline: False
```
**Symbols:**

```
ffffffff8125aa60-ffffffff8125ac26: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff812a3c20)
Location: kernel/bpf/lpm_trie.c:615
Inline: False
```
**Symbols:**

```
ffffffff812a3c20-ffffffff812a3dfc: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81301830)
Location: kernel/bpf/lpm_trie.c:615
Inline: False
```
**Symbols:**

```
ffffffff81301830-ffffffff81301a0c: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff813303e0)
Location: kernel/bpf/lpm_trie.c:612
Inline: False
```
**Symbols:**

```
ffffffff813303e0-ffffffff813305b6: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff81354910)
Location: kernel/bpf/lpm_trie.c:615
Inline: False
```
**Symbols:**

```
ffffffff81354910-ffffffff81354ae6: trie_get_next_key (STB_LOCAL)
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
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffff80001027d9b8)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffff80001027d9b8-ffff80001027dbac: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (c04af690)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
c04af690-c04af860: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (c000000000327be0)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
c000000000327be0-c000000000327e84: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffe0001b5184)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffe0001b5184-ffffffe0001b5304: trie_get_next_key (STB_LOCAL)
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
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811f1040)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff811f1040-ffffffff811f123c: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811e3d90)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff811e3d90-ffffffff811e3f8c: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811eee10)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff811eee10-ffffffff811ef00c: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int trie_get_next_key(struct bpf_map *map, void *_key, void *_next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/lpm_trie.c (ffffffff811fd2e0)
Location: kernel/bpf/lpm_trie.c:630
Inline: False
```
**Symbols:**

```
ffffffff811fd2e0-ffffffff811fd4dc: trie_get_next_key (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *_key</code>
</li>
<li>
<b>Param added. </b>
<code>void *_next_key</code>
</li>
<li>
<b>Param removed. </b>
<code>void *key</code>
</li>
<li>
<b>Param removed. </b>
<code>void *next_key</code>
</li>
</ul>
</details>
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
