# Function: <code>free_htab_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186a10)
Location: kernel/bpf/hashtab.c:407
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81186a10-ffffffff81186a51: free_htab_elem.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81193770)
Location: kernel/bpf/hashtab.c:539
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81193770-ffffffff811937b4: free_htab_elem.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119a5e0)
Location: kernel/bpf/hashtab.c:618
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8119a5e0-ffffffff8119a64d: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811a9df0)
Location: kernel/bpf/hashtab.c:650
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811a9df0-ffffffff811a9e5f: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1390)
Location: kernel/bpf/hashtab.c:664
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
```
In kernel/bpf/sockmap.c (ffffffff811d0322)
Location: kernel/bpf/sockmap.c:287
Inline: True
Inline callers:
  - kernel/bpf/sockmap.c:sock_hash_delete_elem
  - kernel/bpf/sockmap.c:sock_hash_free
  - kernel/bpf/sockmap.c:bpf_tcp_close
```
**Symbols:**

```
ffffffff811c1390-ffffffff811c13ff: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d2bf0)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811d2bf0-ffffffff811d2c5f: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e7340)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811e7340-ffffffff811e73af: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f3aa0)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811f3aa0-ffffffff811f3b0f: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812181d0)
Location: kernel/bpf/hashtab.c:793
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff812181d0-ffffffff81218242: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81219ce0)
Location: kernel/bpf/hashtab.c:814
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81219ce0-ffffffff81219d52: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121d9a0)
Location: kernel/bpf/hashtab.c:814
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8121d9a0-ffffffff8121da12: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81254ac0)
Location: kernel/bpf/hashtab.c:855
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81254ac0-ffffffff81254b55: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129ce60)
Location: kernel/bpf/hashtab.c:874
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8129ce60-ffffffff8129cef5: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f9580)
Location: kernel/bpf/hashtab.c:903
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff812f9580-ffffffff812f9659: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81327560)
Location: kernel/bpf/hashtab.c:918
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff81327560-ffffffff81327622: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134bbf0)
Location: kernel/bpf/hashtab.c:934
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff8134bbf0-ffffffff8134bcc6: free_htab_elem (STB_LOCAL)
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
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010278060)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffff800010278060-ffff800010278108: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aa244)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
c04aa244-c04aa2d8: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c0000000003202b0)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
c0000000003202b0-c000000000320394: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001af96a)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffe0001af96a-ffffffe0001af9ea: free_htab_elem (STB_LOCAL)
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
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec0c0)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811ec0c0-ffffffff811ec12f: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811dee50)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811dee50-ffffffff811deebf: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e9e90)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811e9e90-ffffffff811e9eff: free_htab_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_htab_elem(struct bpf_htab *htab, struct htab_elem *l);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f8260)
Location: kernel/bpf/hashtab.c:678
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_delete_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
```
**Symbols:**

```
ffffffff811f8260-ffffffff811f82cf: free_htab_elem (STB_LOCAL)
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
